セットアップ

1. /etc/hosts に下記をセット

```
127.0.0.1 account.foobar.com
127.0.0.1 service1.foobar.com
```

2. account/index.html のFirebaseAuthの認証情報を入力

3. docker-compose up する

4. service1.foobar.com へアクセスして FirebaseAuth のログイン情報を入力.

5. FirebaseAuthのログイン情報を共有できている確認をする.また画面リロードやブラウザの停止などいろんなシナリオをお試しください
