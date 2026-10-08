# TubeMirror

プライバシー重視のYouTube代替ビューア。Invidious APIとyoutube-nocookieを使用して、広告なしでYouTube動画を視聴できます。

## 機能

- 🔍 **動画検索** - Invidious APIを使用した高速検索
- 📺 **複数インスタンス対応** - 複数のInvidiousインスタンスを自動切り替え
- 🍪 **No-Cookie対応** - youtube-nocookie.comへのフォールバック
- 📋 **プレイリスト** - ローカルストレージで管理（シャッフル再生対応）
- 🌓 **ダークモード** - ライト/ダークテーマ切り替え
- 📱 **レスポンシブ** - モバイル対応

## デプロイ方法

### Vercelでデプロイ

1. GitHubにコードをプッシュ
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin https://github.com/YOUR_USERNAME/tubemirror.git
   git push -u origin main
