# Test

git環境構築時の検証用

## 使い分け

### clone

1. configファイルの切り替え(gitconfigにincludeIfで自動分岐を記述)
2. gitユーザーの切替( ~/.zshrcにコマンドおいておくと楽)
3. `git clone git@{~/.ssh/configで指定したHostName}:{githubのID}/{リポジトリ名}.git`

