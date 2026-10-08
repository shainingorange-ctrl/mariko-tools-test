# mariko-tools-test

まりこ用のツールやゲームを置くリポジトリ。ゲームは1フォルダに1つの `index.html` で作り、スマホ（タッチ操作）で遊べるようにする。

## 作業の進め方（まりことの約束）

- PRを作って止まらない。競合（mergeable の状態）、チェック結果（CI）、変更内容（diff）を確認する
- 問題がなければ、下書きを外してマージまで行う
- 問題が見つかった場合や、マージで既存の機能に悪影響が出る可能性がある場合は、勝手に進めずまりこに確認する
- 権限がなくてできない時は、その旨をまりこに伝える
- マージ後は、ゲームをブラウザで遊ぶ方法とURLを必ず伝える

同じ内容は Notion の Memories「GitHubでの作業の進め方」にもある（ゲーム以外の作業にも共通）。

## 遊べるURL

- GitHub Pages：`https://shainingorange-ctrl.github.io/mariko-tools-test/<フォルダ名>/`
  - Settings → Pages で `main` / `(root)` を公開している場合のみ。未設定なら、まりこに設定方法を伝える
- Claude のアーティファクトとして公開したリンクでも遊べる

## ゲーム一覧

| フォルダ | 名前 | アーティファクト |
| --- | --- | --- |
| `flying-game/` | 夕焼けフライト | https://claude.ai/artifact/CEwJsZArNo2aTEBw3oxxit |
