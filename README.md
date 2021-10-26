# about PWA
  
### ios　の　safariの場合、別途設定する必要がある件について  
→<head>タグ内にios専用のコードを記載  
▼参考サイト  
-[初心者がつまづいた、PWAアプリSafari版でホームボタンのアイコンが読み込まれない件](https://qiita.com/bonkeenu/items/0c8766e5f3e94c0e68c9)  
-[ReactでSPA+PWAを作ってみた](https://takashinoda.hatenablog.com/entry/2020/01/03/000503)  
-[Use Apple Touch Icon](https://web.dev/install-criteria/)  
    
### サービスワーカーの設定
memo  
・サービスワーカーはdevモードでは更新されない。hotreload使えないので毎回コンパイラしなおす必要がある
・サービスワーカー更新時は、ブラウザ上で一旦unRegisterする。更新されないから。
  
-[サーバーからブラウザを通じてデスクトップ通知する方法](https://laboradian.com/web-push/)  
-[Service Workerとは](https://yasunari-fujieda.hatenablog.com/entry/2016/08/31/163800)  
-[僕の考えた最強のService Workerキャッシュ戦略で爆速サービスを作った](https://qiita.com/tiwu_dev/items/47e8a7c3e6f2d57816d7)  
-[公式：Service Worker の紹介](https://developers.google.com/web/fundamentals/primers/service-workers/?hl=ja)  
-[Lab: Integrating Web Push ](https://developers.google.com/web/ilt/pwa/lab-integrating-web-push)  
-[プログレッシブウェブアプリで通知をプッシュするための8分間のガイド](https://ichi.pro/puroguresshibuwhebuapuri-de-tsuchi-o-pusshusuru-tame-no-8-funkan-no-gaido-71402859693769)  
 
### カスタムワーカー  
-[next-pwa - custom worker example](https://github.com/shadowwalker/next-pwa/tree/master/examples/custom-worker)  
-[next-pwa - web push example](https://github.com/shadowwalker/next-pwa/tree/master/examples/web-push)  
  
  
## PUSH通知
-[【PWA】シリーズPWA (6) プッシュ通知を送ってみる](https://shinimae.hatenablog.com/entry/2019/08/15/194051)
  
## 通知  
-[通知をオンまたはオフにする chrome公式の通知の仕組み](https://support.google.com/chrome/answer/3220216?hl=ja&co=GENIE.Platform%3DAndroid)
