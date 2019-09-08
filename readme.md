# Reactを使ったモダンなフロントエンド開発の環境構築
https://qiita.com/toshi-toma/items/8ee55304f09b5840b9a4

## このtutorialで行うフロントエンド開発構成
- URライブラリ : React
- 静的型付き言語 : TypeScript
- スタイル定義 : styled-components
- コンポーネントの開発環境 : Storybook
- Linter : ESLint
- Formatter : Prettier

## styled-componentsとは？

CSSとほぼ同様のシンタックスを使ってスタイリングされたReactコンポーネントを作成できるライブラリ。
.cssファイルにCSSを書くのではなく、.jsや.tsxファイル内でCSSを書くイメージ。

## 環境構築のゴール

- `npm run storybook` : Storybookを起動して、React+TypeScript+styled-componentsで作成したコンポーネントが表示できる
- `npm run lint` : ESLint + Prettierを使ってコードのチェックが行える
- `npm run tsc` : TypeScriptのコードに対してコンパイルチェックが行える


