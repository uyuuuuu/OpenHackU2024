# FitTime
「忙しい朝にフィットした生活を送ろう」というテーマで、簡単かつ短時間で明日起きるべき時刻を把握するためのwebアプリです。  

FitTimeは、電車の時間やオンライン会議の開始時刻などの「目標時刻」と、朝に行うタスクの所要時間を登録することで、起きるべき時刻を自動で逆算します。  
初回は質問形式で朝のルーティンを登録でき、登録したタスクや時刻はプリセットとして再利用できます。

## 担当
バックエンド、ロゴデザイン

## デモ動画
[デモ動画](https://drive.google.com/file/d/1H64Aj0nMbJy6F5bPEZMQyvjba8ALBYqq/view?usp=sharing)

## スライド
https://docs.google.com/presentation/d/10tC75CjFfhjdNAZVlh6kAbKRyCqYLx690gSc_KRhkKY/edit?usp=sharing

<img width=60% alt="FitTime_Slide" src="https://github.com/user-attachments/assets/14f67e7a-6e57-455b-8191-09b7de276589" />
<img width=60%  alt="FitTime_Slide (1)" src="https://github.com/user-attachments/assets/a2adc4d3-5ae1-4f10-9297-a2a0fc1e2920" />
<img width=60%  alt="FitTime_Slide (2)" src="https://github.com/user-attachments/assets/2dc1d481-a0aa-4d4c-af09-09fbf3928002" />
<img width=60%  alt="FitTime_Slide (3)" src="https://github.com/user-attachments/assets/79e75340-70e6-44ce-b02b-1ae2ab5d603a" />
<img width=60%  alt="FitTime_Slide (4)" src="https://github.com/user-attachments/assets/90fb9731-5f92-40ec-9ae9-c745e7c9b2cb" />
<img width=60%  alt="FitTime_Slide (5)" src="https://github.com/user-attachments/assets/7bacef69-ea93-4345-822c-b1be064f52fb" />
<img width=60%  alt="FitTime_Slide (6)" src="https://github.com/user-attachments/assets/5af710f5-da2a-40d1-9da6-f76ffee3e14d" />
<img width=60%  alt="FitTime_Slide (7)" src="https://github.com/user-attachments/assets/5c4f0e71-8518-43ac-a85a-0735fe2796ed" />
<img width=60%  alt="FitTime_Slide (8)" src="https://github.com/user-attachments/assets/1adbed65-d1bc-45bc-a1d2-02a81232bde2" />


## 実行方法
```.env```を作成、環境変数を登録  
```npm install```  
```npm run db:push```  
```npm run dev```  
http:/localhost:3000に接続

## Prisma
```npx prisma studio```  
http:/localhost:5555に接続  
→データベースの中身が見れる、GUIでテーブル書き換え可能  

## ブランチ命名規則
基本的には<個人名>/<作業名>で統一  

## コミットメッセージ
○○: 海画面に遷移するめんだこボタンを追加

fix：バグ修正
add：新規ファイル追加  
remove：ファイル削除  
feat：新規機能実装  
update：機能修正（バグではない）  
change：仕様変更  
ref：リファクタリング  
style：空白とか改行とかコメントとか  
docs：ボタンの文字を変えたとか  
revert：変更取り消し  
