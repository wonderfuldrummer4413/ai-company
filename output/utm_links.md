# UTMパラメータ付きリンク集

> 作成: マーケティング部長・田中
> 目的: 有料note記事への流入元を追跡するためのリンク管理

---

## ベースURL

```
https://note.com/takuhai_gogo/n/XXXXX
```

> ※ `XXXXX` の部分を実際のnote記事IDに置き換えてください

---

## 用途別リンク一覧

### Xプロフィール用

```
https://note.com/takuhai_gogo/n/XXXXX?utm_source=x&utm_medium=profile&utm_campaign=amazon_delivery
```

- 貼る場所: Xプロフィールの「ウェブサイト」欄
- 追跡内容: Xプロフィール経由の流入

### X投稿用（将来リンクを貼る場合）

```
https://note.com/takuhai_gogo/n/XXXXX?utm_source=x&utm_medium=post&utm_campaign=amazon_delivery
```

- 用途: X投稿に直接リンクを貼る場合（フォロワー増加後）
- 追跡内容: X投稿からの直接流入

### 無料note記事からの誘導用

```
https://note.com/takuhai_gogo/n/XXXXX?utm_source=note&utm_medium=free_article_1&utm_campaign=amazon_delivery
```

```
https://note.com/takuhai_gogo/n/XXXXX?utm_source=note&utm_medium=free_article_2&utm_campaign=amazon_delivery
```

```
https://note.com/takuhai_gogo/n/XXXXX?utm_source=note&utm_medium=free_article_3&utm_campaign=amazon_delivery
```

- 貼る場所: 無料note記事3本それぞれの末尾CTA
- 追跡内容: どの無料記事からの購入が多いかを記事別に計測

### LitLink / リンクまとめ用

```
https://note.com/takuhai_gogo/n/XXXXX?utm_source=litlink&utm_medium=link&utm_campaign=amazon_delivery
```

- 用途: LitLinkやlit.linkなどプロフまとめサービスに貼る場合
- 追跡内容: リンクまとめ経由の流入

---

## UTMパラメータの見方

| パラメータ | 意味 | 例 |
|-----------|------|-----|
| utm_source | どのサービスから来たか | x, note, litlink |
| utm_medium | どの導線から来たか | profile, post, free_article_1 |
| utm_campaign | どのキャンペーンか | amazon_delivery（固定） |

---

## 計測方法

noteの標準ダッシュボードではUTMパラメータを確認できないため、以下のいずれかで計測します：

### 方法1: Bitlyで短縮（推奨・無料）

1. https://bitly.com でアカウント作成
2. 上記のUTM付きリンクをそれぞれBitlyで短縮
3. Bitlyのダッシュボードでクリック数を確認

| 用途 | Bitlyリンク（例） |
|------|-------------------|
| Xプロフィール用 | `https://bit.ly/takuhai-x-prof` |
| 無料記事1用 | `https://bit.ly/takuhai-free1` |
| 無料記事2用 | `https://bit.ly/takuhai-free2` |
| 無料記事3用 | `https://bit.ly/takuhai-free3` |

### 方法2: Googleアナリティクス（上級者向け）

- noteはGoogleアナリティクスを直接設置できないため、自前のLPを間に挟む必要がある
- 現段階では不要。Bitlyで十分

---

## 今すぐやること

1. [ ] noteの有料記事URLの `XXXXX` 部分を確認する
2. [ ] 上記リンクの `XXXXX` を実際の記事IDに置き換える
3. [ ] Bitlyでアカウント作成し、各リンクを短縮する
4. [ ] XプロフィールのURL欄にBitly短縮リンクを設置する
5. [ ] 無料note記事を公開する際、各記事末尾に対応するリンクを設置する
