# Web Entertainment Design（コーポレートサイト模写）

CodeJump初級編の課題として、コーポレートサイトを再現実装しました。
`position: absolute`を使った重なりレイアウトと、疑似要素による装飾、レスポンシブ対応の理解を目的としています。

---

## 使用技術

- HTML5
- CSS3（Flexbox / Position / 疑似要素）
- レスポンシブ対応（@media screen and (max-width: 900px)）

---

## 実装内容

- `position: absolute`を使ったテキストと画像の重なりレイアウト（COMPANYセクション）
- `::after` / `::before`疑似要素による装飾線の実装
- Flexboxを使った各セクションのレイアウト構築
- `calc(100vh - 80px)`によるメインビジュアルの高さ制御
- `object-fit: cover`による画像トリミング
- SP表示での`position: static`によるabsolute解除
- `time`タグを使ったセマンティックなHTML構造

---

## 学んだこと

- `position: absolute`と`relative`の親子関係を理解した
- 疑似要素で装飾線を引くテクニックを習得した
- `first-of-type`と`first-child`の違いを理解した
- SPでのposition解除など、レスポンシブの上書き設計を実践できた
- BEMの命名規則の考え方に触れ、クラス設計を意識するようになった

---

## 感想

`position: absolute`を使った重なりレイアウトは最初は難しく感じたが、親要素に`relative`、子要素に`absolute`を設定する仕組みを理解することで整理できた。
疑似要素で装飾線を引くテクニックや、SPでのposition解除など、実践的な技術を身につけることができた。
模写を通じて「なぜこの構造なのか」を意識しながらコーディングする力が少しずつついてきたと感じる。

---

## 公開URL

👉 https://satoru-tanaka-1977.github.io/codejump-beginner-04-web-entertainment/