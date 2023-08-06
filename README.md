Re:dashをローカルでいじり倒す用

.env適当に設定後コンテナ立ち上げ

```shell
$ docker compose run --rm server create_db
$ docker compose up -d
```

[http://localhost:8080](http://localhost:8080) でアカウント作成