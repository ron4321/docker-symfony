```console
$ docker-compose up -d
$ docker-compose exec php pwd #カレントディレクトリのパスを確認
/var/www/html/myapp
$ docker-compose exec php composer create-project symfony/website-skeleton . #myappフォルダにsymfonyのプロジェクト作成
```

symfonyのバージョンを指定する場合は`composer create-project symfony/website-skeleton:^5.1 myapp`

http://localhost:8080/
