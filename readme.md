# Name  
Docker-de-Note -ドッカー ド ノート-  
  
# Features  
「Docker」(docker-compose)でLEMP環境(PHP/nginx/MySQL)を構築し、開発。
Evernote風のメモアプリケーションです。
  
# Description  
ローカル環境で作成後、DockerでAWSにデプロイしました。 Dockerの学習のため取り組みましたが、運用まで見据えないと理解がしにくいと感じました。  
ただし、あくまでcomposeは開発環境用で、スケーリングやフェイルオーバーに対応していないため、  
そういった運用のために次はkubernetesやECSを組み込みたいと考えております。  
  
# Requirement  
### 使用技術  
#### 【フロントエンド】  
- HTML/CSS
- JavaScript
- Bootstrap  
  
#### 【バックエンド】  
- PHP 7.4.10
- mysql 5.7
  
#### 【インフラ】  
- nginx 1.19.1
- AWS VPC EC2(ホスティング)
- docker 19
- docker-compose 1.27
  
#### 【開発環境】  
- Windowsで開発後、AWS上にデプロイ
- VScodeでSSH接続
  
#### 【機能要件】
- ユーザー登録、ログイン機能
- 投稿機能
- コメント機能
- 編集・更新機能
  