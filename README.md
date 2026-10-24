# サービス名

（どんな架空のサービスかを1〜2文で）

- 公開先: `https://mousou-lp.github.io/リポジトリ名/`
- 作った人: @

## はじめにやること

1. このREADMEの上の3行を書きかえる
2. `public/index.html`からLPを作る。mainに入れると、上の公開先に自動で出る
3. 公開できたら、[ポータル](https://github.com/mousou-lp/mousou-lp.github.io)の`lps.json`に足して一覧にのせる

## 作るときの注意

- 公開先は`/リポジトリ名/`の下なので、画像やCSSは`/images/a.webp`ではなく`images/a.webp`のように、`/`で始めずに書く
- ViteやAstroを使うなら、`base`を`/リポジトリ名/`にして、`.github/workflows/pages.yml`にビルドの手順を足す

## 決まり

[AGENTS.md](AGENTS.md)にあります。AIに作らせるときも、まずこれを読ませてください。
