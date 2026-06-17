# M's Planning リニューアルサイト

M's Planning コーポレートサイト（リニューアル版）の静的サイト。**全12ページのマルチページ構成**。

## 構成
- `index.html` — トップ
- `higedansyaku.html` / `monsterlounge.html` / `o2room.html` — 各店舗
- `nuketoru.html` / `koritoru.html` / `yasetoru.html` / `yaketoru.html` — 各サービス
- `print.html` — 広告・印刷の実績
- `garage.html` — ガレージ
- `company.html` — 会社情報
- `contact.html` — お問い合わせ
- `assets/` — 画像（全10枚）。元サイトが https 非対応のため、画像はリポジトリに取り込みローカル参照にしている

## 公開
GitHub 組織 `nuworks-intern` のリポジトリを Netlify に連携して自動デプロイ。
`main` ブランチへの push でデプロイが走る。各ページは相対リンクで遷移する。
