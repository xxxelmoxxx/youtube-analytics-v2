# YouTube Analytics V2 OAuth site

Google OAuth の本番公開用に必要な
ホームページ / プライバシーポリシー / 利用規約を含む静的サイトです。

## 使い方

1. 3つのHTML内にある `YOUR_SUPPORT_EMAIL` を自分の連絡先メールアドレスへ置換します。
2. このフォルダを GitHub リポジトリに置きます。
3. Vercel でそのリポジトリを Import して Deploy します。
4. 公開URLを Google Auth Platform のブランディングに設定します。
   - ホームページ: `/`
   - プライバシーポリシー: `/privacy.html`
   - 利用規約: `/terms.html`
5. Google Search Console でサイト所有権を確認します。
6. Google Auth Platform の「対象」でアプリを本番環境へ公開します。

## 推奨

- ソース管理: GitHub
- 公開ホスティング: Vercel
- Google のブランド確認まで行うなら、可能であれば独自ドメインを使用
