# アプリケーション名
git clone 
docker-compose up -d --build

## 環境構築
- Dockerのビルドからマイグレーション、シーディングまでを記述する
docker-compose exec php bash
composer install
.env.exampleファイルから.envを作成し、環境変数を変更
php artisan key:generate
php artisan migrate

## 使用技術(実行環境)
Laravel 8.83.8

## ER図
< - - - 作成したER図の画像 - - - >

## URL
開発環境：http://localhost/
