# mysql-container

MySQL on Docker container

## ターミナルで起動する

```sh
$ docker-compose -f .\docker-compose.yml -f .\.devcontainer\docker-compose.yml up -d
# 停止
$ docker-compose stop db
```

## Visual Studio Codeで起動する

- コマンドパレットで、下記を実行する。
  - `>Remote-Containers: Reopen in Container`

## 接続情報

- Host: `localhost`
- Port: `3306`
- User: `root`
- Password: `{.\docker-compose.ymlに設定している環境変数MYSQL_ROOT_PASSWORDの値}`
- Database: `test`
