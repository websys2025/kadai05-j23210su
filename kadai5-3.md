## 外部APIの呼び出しのミニレポート
### Q3-1. 郵便番号APIについて説明せよ。
* エンドポイントと機能`https://zipcloud.ibsnet.co.jp/api/search`
* リクエストとレスポンスのフォーマット1000001   `address1: 東京都`, `address2: 千代田区`, `address3: 千代田`

### Q3-2. 各自で調査したAPIについて説明せよ。
* APIの名称と参照URL  簡易天気サービス  `https://wttr.in/<都市>?format=j1`
* エンドポイントと機能   現在の天気と気温
* リクエストとレスポンスのフォーマット   `https://wttr.in/Tokyo?format=j1`  `weatherDesc: "Partly cloudy"`, `temp_C: 22`
### Q3-3. 感想
URLとパラメータを組み合わせるだけで外部データを簡単に取れる。
fetch が非同期という仕組みを理解するまで時間がかかった。
