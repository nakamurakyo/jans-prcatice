# jans-prcatice
正直ベース使い物にならない

## Setup
1. docker-composeの取得
    $ curl -O https://raw.githubusercontent.com/JanssenProject/jans/main/docker-jans-monolith/jans-mysql-compose.yml 

    元: wget https://raw.githubusercontent.com/JanssenProject/jans/main/docker-jans-monolith/jans-mysql-compose.yml 

2. docker-composeの起動
    $ docker compose -f jans-mysql-compose.yml up -d

3. 実行中のコンテナを表示
    $ docker compose -f jans-mysql-compose.yml ps

4. Janssen サーバーの構成
    $ docker compose -f jans-mysql-compose.yml exec jans sh


