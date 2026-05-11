# BLUEMOUSEタイムカード - Claude指示書

## パスワードを変更したいと言われたとき

### 打刻ページのパスワード
`docs/index.html` の以下の行を変更する：
```javascript
const STAFF_PASSWORD = '変更後のパスワード';
```

### 管理者ページのパスワード
`docs/admin.html` の以下の行を変更する：
```javascript
const ADMIN_PASSWORD = '変更後のパスワード';
```

## サイトを更新したいと言われたとき

変更後は必ず以下でGitHubにpushする：
```bash
cd /Users/otokoushigaeru/Desktop/合同会社BLUEMOUSE/timecard
git add docs/
git commit -m "サイト更新"
git push origin main
```

push後、1〜2分でサイトに反映される。

## プロジェクト情報
- サイトURL: https://tratssai71-create.github.io/BLUEMOUSE-timecard/
- GitHubリポジトリ: https://github.com/tratssai71-create/BLUEMOUSE-timecard
- Firebase プロジェクト: bluemouse-dfd31
- 打刻ページ: index.html
- 管理者ページ: admin.html（パスワード: admin2024）
- スタッフ登録ページ: register.html
