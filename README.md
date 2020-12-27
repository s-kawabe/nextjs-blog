# Next.jsチュートリアル
- Next.jsの公式チュートリアルと、日本語翻訳版
[Next.js公式チュートリアル(英語)](https://nextjs.org/learn/basics/create-nextjs-app)<br>
[日本語翻訳版](
https://qiita.com/thesugar/items/01896c1faa8241e6b1bc)

## 1. 環境構築
### 1-1.Next.jsできること
- Next.jsではWebpackやbabelなどが標準搭載
- 動的ルーティングをサポート
- HMRのサポート(コードを変更すると自動でページに反映される)
- CSS と Sass のビルトイン、及びあらゆる CSS-in-JS ライブラリのサポート
etc...

### 1-2.注意事項
- 環境を整えてから実施すること！(npmやnodeのバージョンを要チェック)

## 2. ページ間の移動

## 3 アセット,メタデータ,CSS

## 4

## Q&A
### Q. Next.jsとmaterialUIを同時に使うのはダメ？
A. Qin Salonでも使っている、問題ない
　　Next.jsと何かを合わせて使いたい場合Next.jsのgitリポジトリのexampleに
　　書いてあれば問題ない

### Q.  NextではやはりCSS in JSよりCSSModulesの方がいいのか？
A. 開発者の好み。vercel社は若干CSSModulesを推しているが
   styled-componentなども全然使われている
   CSSModulesで書いた方がパフォーマンスは良い

### Q. scssを使うには？
A. 専用のパッケージをimportして使う。
　　公式に記載してある。

### Q. Twitterなどのリアルタイム性が求められる場合はSSR?
A. SSR,SSGはプリレンダリングの話。
　 CSRというものもある。（それぞれの最適な使い方を理解する）
　 ユーザにローディングを見せても良い場合はCSR？
　 何も使わない場合はCSR、ブラウザ側からfetch?

getStaticProps、getServerSidePropsはサーバ側でfetchをする