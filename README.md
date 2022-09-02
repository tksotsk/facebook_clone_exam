# 友だちつながりアプリケーション
- Ruby on Railsを使ったアプリケーションであること
- HTML,CSS,bootstrapを使用して、現実のFacebookに似せたデザインにすること（任意　詳しくは後述）
- pictureの投稿・投稿確認・編集・一覧表示・詳細画面・削除機能があること（CRUD機能）
- ログイン機能があること
- UserとPictureをひも付けて誰がPictureを投稿したか分かるようにすること
- 画像と文章を投稿できるようにすること
- Githubにソースコードを送信し、そのリポジトリのURLを提出すること
- Herokuにアップロードしてある状態であること
- 404,500のエラーページを実装すること
- 変数名やアソシエーション名は具体的で、一目見て概ね理解できる名前にすること
- Gitのコミットメッセージが、一目見てそのコミットで何をしたかがわかるものであること
- 一つの機能を作成したら、一つのコミットをするようにすること（下記ヒントあり）
- インデントは半角スペース二つで揃えること
- Gemfileはコメント行をあらかじめ消しておくこと
- 改行は意味のある単位で行なった方がみやすいため、そうすること
- 意味のない空行は消しておく
- 古いロケット記法は使わないこと
- 変数やアソシエーション名は、機能に関連した名前づけを心がけ、good_answersのようにスネークケースできちんと単語を分けること
- 変数やアソシエーション名に省略した名称は基本的に使わない(意味を予測しづらいため)
- privateより下の行はprivateと同じレベルのインデントにする
- updateなどの記述の際、バリデーションが発火した時の処理も考慮しておくこと。（レンダリングするviewが見つけられなくてエラーになったりしないように注意する）
- 追加するライブラリは、bootstrap、jquery-rails、bcrypt、carrier_wave、デバック関係のみに限定すること




***

```mermaid
erDiagram
    USER ||--o{ TASK
    CUSTOMER {
        string name
        string custNumber
        string sector
    }
    
    TASK {
        int orderNumber
        string deliveryAddress
    }
   
```
```mermaid
graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
```

```geojson
{
  "type": "FeatureCollection",
  "features": [
    {
      "type": "Feature",
      "id": 1,
      "properties": {
        "ID": 0
      },
      "geometry": {
        "type": "Polygon",
        "coordinates": [
          [
              [-90,35],
              [-90,30],
              [-85,30],
              [-85,35],
              [-90,35]
          ]
        ]
      }
    }
  ]
}
```

