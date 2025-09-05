# json-readme-format
jsonの説明書フォーマットです

# 使い方
readme.jsonのmetaオブジェクトやcreditsオブジェクトにキーと中身を追加します
## 例
[
    {
        "meta":{
          "ver":"1.0.0"
        }
    },
    {
        "readme":{
          "説明":"このように使います"
        }
    },
    {
        "credits":{
          "クレジット":"wiikun"
        }
    },
    {
        "more":{
          "追記":"いつかパーサーも作りたい"
        }
    }
]
