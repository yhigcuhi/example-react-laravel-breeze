# example-react-laravel-breeze
Laravel Breezeによる react vite tsのサンプル
## 環境構築時の手順
1. Docker 用意
1. コンテナ起動
1. appコンテナ起動
1. composer create-project laravel/laravel .
1. composer require laravel/breeze --dev
1. curl https://www.toptal.com/developers/gitignore/api/vim,react,node,linux,macos,laravel,windows,composer,intellij,sublimetext,visualstudio,visualstudiocode >> .gitignore

## Laravel Breeze bladeとしての環境構築 (他でも作業できるように ここから別ブランチ作業)
1. php artisan breeze:install react --typescript
