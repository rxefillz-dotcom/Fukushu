# 復習用メモ（GitHub 練習）

このフォルダは **Git / GitHub の操作を復習するため** の練習用です。  
README を編集したり、メモを追加したりして、`add` → `commit` → `push` の流れを繰り返し練習しましょう。

---

## 1. Git の復習

### よく使うコマンド

| コマンド | やること |
|----------|----------|
| `git status` | 変更されたファイルを確認する |
| `git add .` または `git add ファイル名` | 変更をステージング（コミットの準備） |
| `git commit -m "メッセージ"` | 変更を記録する |
| `git push` | GitHub に送る |
| `git pull` | GitHub から最新を取ってくる |

### 初回や新しいフォルダでやること

```bash
git init
git add .
git commit -m "最初のコミット"
git remote add origin https://github.com/自分のユーザー名/リポジトリ名.git
git branch -M main
git push -u origin main
```

---

## 2. HTML の復習

学習ログで触れた基本をまとめます。

- **`<!DOCTYPE html>`** … この文書が HTML5 ですよ、という宣言
- **`<html lang="ja">`** … ページの言語を日本語に指定
- **`<h1>`** … いちばん大きい見出し（h2, h3… と小さくなる）
- **`<p>`** … 段落（paragraph）

---

## 3. 練習の流れ（今日やること）

1. この README を開いて、下の「復習メモ」に今日学んだことや思い出したことを 1 行でも書く
2. ターミナルでこのフォルダ（またはリポジトリのルート）に移動する
3. `git add .`
4. `git commit -m "復習メモを追加"`
5. `git push`

何度でも繰り返して、手順に慣れていきましょう。

---

## 復習メモ（ここに追記して push の練習）

- （例）2月○日: Git の add → commit → push の流れを復習した
