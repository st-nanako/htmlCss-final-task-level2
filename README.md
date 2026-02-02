# 概要

## サイト名
**GameHub** - ゲーム情報総合サイト

## ページ構成（9ページ）

| ページ | ファイル名 | 主な内容 |
|--------|-----------|---------|
| ホーム | `index.html` | トップページ、新作ゲーム紹介、人気ゲーム一覧 |
| ゲーム一覧 | `games-list.html` | ゲームの一覧表示、フィルター・検索機能 |
| ゲーム詳細 | `game-detail.html` | 個別ゲームの詳細情報、レビュー、評価 |
| 制作会社一覧 | `game-companies.html` | ゲーム開発会社の一覧表示 |
| 制作会社詳細 | `company-detail.html` | 開発会社の詳細情報、リリースゲーム一覧 |
| ゲーム購入 | `game-purchase.html` | 購入手続きページ、ステップ式購入フロー |
| マイゲーム | `game-mygame.html` | プレイ中・プレイ履歴・ウィッシュリスト管理 |
| ログイン | `login.html` | ユーザーログイン画面 |
| 新規登録 | `register.html` | 新規ユーザー登録画面 |

## 主要な機能
1. **レスポンシブデザイン** - モバイル、タブレット、デスクトップに対応
2. **タブ機能** - マイゲームページでプレイ中/履歴/ウィッシュリストを切替
3. **フィルター機能** - ゲーム一覧でジャンル、プラットフォーム、価格帯での絞り込み
4. **カード型UI** - ゲームや制作会社を視覚的に魅力的に表示
5. **グラデーション** - 統一感のあるカラーデザイン（紫、ピンク、青系）


### 使用しているBootstrapコンポーネント
```
- **Navbar** - ナビゲーションバー
- **Card** - ゲーム/会社情報カード
- **Grid System** - レスポンシブレイアウト
- **Tab** - タブ切り替え（マイゲームページ）
- **Form** - ログイン/登録フォーム
- **Button** - 各種ボタン
- **Badge** - ステータス表示
- **Pagination** - ページネーション

```
### ディレクトリ構造

.
├── index.html              # トップページ  
├── games-list.html         # ゲーム一覧  
├── game-detail.html        # ゲーム詳細  
├── game-companies.html     # 制作会社一覧  
├── company-detail.html     # 制作会社詳細  
├── game-purchase.html      # 購入ページ  
├── game-mygame.html        # マイゲーム  
├── login.html              # ログイン  
├── register.html           # 新規登録  
├── base.css                # 共通スタイルシート  
├── img/                    # 画像フォルダ  
│   ├── favicon.ico         # ファビコン  
│   ├── gameneon-top-bac.jpg # トップページ背景  
│   └── games/              # ゲーム画像  
│       ├── REANIMAL.png  
│       ├── EldenRing.png  
│       ├── Minecraft.png  
│       ├── UNDERTALE.png  
│       └── その他...  
└── README.md               # このファイル
