# KLEC-02 "Gravity-36"

https://x.com/Hottyhottea/status/1843859533871058982
<img src = "https://github.com/user-attachments/assets/21ff8abf-b528-4509-ae43-0f3b31ae8f68" width = "600px" />

# 部品リスト


|画像|部品名|個数|備考|
|:--|:--|:--|:--|
|<img src = "https://pbs.twimg.com/media/GavF5efaAAE2fpr?format=jpg" width = "1200px" />|KLEC-02 PCB|1||
|<img src = "https://github.com/takashicompany/rookey/assets/4215759/1fe9f782-f64b-4291-b03c-e1532b05013b" width = "1200px" />|[Pro Micro](https://shop.yushakobo.jp/products/21)|2|どれを買っていいか分からない場合は[コンスルー付きのセット](https://shop.yushakobo.jp/products/21)の購入を推奨します。|
|<img src = "https://github.com/takashicompany/rookey/raw/master/images/build/IMG_6635.jpg?raw=true" width = "1200px" />|[タクトスイッチ](https://shop.yushakobo.jp/products/a0800ts-01-1)|2||
|<img src = "https://github.com/takashicompany/rookey/assets/4215759/131d8bc9-4716-4d8d-8934-5a90197babb9" width = "1200px" />|[コンスルー](https://shop.yushakobo.jp/products/31)|4|PCBとPro Microを接続する端子です。Pro Microに付属するピンヘッダでの取り付けも可能ですが、作業ミスや故障した際の取り替えが容易になりますので、**コンスルーの使用を強く推奨します。ピンヘッダでの取り付けは当キーボードと当ビルドガイドではサポートしません。** コンスルーの必要な高さはPro Microによって異なりますので、販売元にご確認ください。コンスルーについての詳細な説明は[こちら](https://scrapbox.io/self-made-kbds-ja/%E3%82%B3%E3%83%B3%E3%82%B9%E3%83%AB%E3%83%BC)をご一読ください。併せて[取り付け方の説明](https://yushakobo.zendesk.com/hc/ja/articles/360044233974-%E3%82%B3%E3%83%B3%E3%82%B9%E3%83%AB%E3%83%BC-%E3%82%B9%E3%83%97%E3%83%AA%E3%83%B3%E3%82%B0%E3%83%94%E3%83%B3%E3%83%98%E3%83%83%E3%83%80-%E3%81%AE%E5%8F%96%E3%82%8A%E4%BB%98%E3%81%91%E6%96%B9%E3%82%92%E6%95%99%E3%81%88%E3%81%A6%E4%B8%8B%E3%81%95%E3%81%84)も目を通しておくと作業がスムーズに進められます。|
|<img src = "https://github.com/user-attachments/assets/b8442f5d-aad8-4d54-b0ac-93cd9ae487b5" width = "1200px" />|[スイッチソケット MX用](https://shop.yushakobo.jp/products/a01ps)|36|使用せずとも、PCBとキースイッチをハンダ付けすることで取り付けは可能ですが、メンテナンス性と組み立て手順を間違えた際のリカバリーを考慮すると、スイッチソケットを使用することを推奨します。|
|<img src = "https://github.com/takashicompany/rookey/blob/master/images/build/IMG_6653.jpg?raw=true" width = "1200px" />|[MX互換キースイッチ](https://shop.yushakobo.jp/collections/all-switches)|36||
|<img src = "https://github.com/takashicompany/rookey/assets/4215759/eafcac57-31fe-4c3a-829c-3cbf697e00ff" width = "1200px" />|[MX互換キーキャップ](https://shop.yushakobo.jp/collections/keycaps)|36|[こちら](https://www.keyboard-layout-editor.com/#/gists/d532e57cda0be36ffc0e33e7f8f69d8d)から各キーのサイズを確認できます。|
|<img src = "https://github.com/takashicompany/rookey/raw/master/images/build/IMG_6672.jpg?raw=true" width = "1200px" />|[ウレタンクッション](https://shop.yushakobo.jp/products/a0800ur-01-6)|12|数はお好みで増減させてください。|
|<img src = "https://github.com/user-attachments/assets/2839aab1-40ae-45c5-82e6-39dc394a1ebe" width = "1200px" />|アクリルケース|1|[こちらのデータ](https://github.com/takashicompany/klec_02/blob/master/case/klec_02_a4_yushakobo.ai)を遊舎工房の[レーザー加工サービス](https://shop.yushakobo.jp/products/lasercut?variant=48787700744423)にてカット依頼するなどして製造してください。後日に[キーボードアクリルプレート](https://shop.yushakobo.jp/products/keyboard_acrylic_plate)に追加予定です。|
|<img src = "https://github.com/user-attachments/assets/37b49dd3-f27d-4e82-a113-1393d0518370" width = "1200px" />|[M2スペーサー](https://shop.yushakobo.jp/products/a0800c2?variant=37665435222177)|12|長さはお好みで調整してください。Pro Microなどにもよりますが、7mm~10mmぐらいがオススメです。|
|<img src = "https://github.com/user-attachments/assets/26e37e8a-66b7-4fd7-8255-90451c3960d4" width = "1200px" />|[M2ネジ 5mm](https://shop.yushakobo.jp/products/a0800n2?variant=37665432993953)|24||

# ファームウェア
QMK Firmwareへの[プルリクエストはこちら](https://github.com/qmk/qmk_firmware/pull/24559)です。

VIAに対応したファームウェアは[こちら](https://github.com/takashicompany/klec_02/blob/master/via/takashicompany_klec_02_via.hex)です。ソースコードは[こちら](https://github.com/takashicompany/qmk_firmware/tree/master/keyboards/takashicompany/klec_02/keymaps/via)になります。

[RemapからWebブラウザを用いたファームウェアの書き込み](https://remap-keys.app/keyboards/jiZA8wP7nL4qwY1EUZ8j)とキーマップの変更が可能です。

~2024年11月5日現在、Remapの審査中ですのでRemapでキーマップを変更したい場合は[こちらのjsonファイル](https://github.com/takashicompany/klec_02/blob/master/via/via.json)をアップロードしてご利用ください。~

