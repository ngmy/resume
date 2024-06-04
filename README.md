# 職務経歴書
永宮悠大の職務経歴書です。

## 公開先
[GitHub Pages](https://ngmy.github.io/resume/)

## 公開手順
1. リポジトリをクローンする。
   ```console
   git clone https://github.com/ngmy/resume.git
   ```
2. Hugoサーバーを起動する。
   ```console
   docker compose up -d
   ```
3. `config.toml`ファイルを編集する。
4. [http://localhost:1313/resume/](http://localhost:1313/resume/)で編集結果を確認する。
5. masterブランチにプッシュする。[ビルド](https://github.com/ngmy/resume/actions/workflows/gh-pages.yml)が無事完了したらGitHub Pagesに公開される。
   ```console
   git push origin master
   ```
