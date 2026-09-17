---
title: Metered class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/metered/
---
## Metered クラス

メータードキーを設定するためのメソッドを提供します。

Metered 型は以下のメンバーを公開します。

## コンストラクタ

| コンストラクタ | 説明 |
| :- | :- |
| [`__init__(self)`](/slides/python-net/ja/aspose.slides/metered/__init__/#) | このクラスの新しいインスタンスを初期化します。 |

## メソッド

| メソッド | 説明 |
| :- | :- |
| [`set_metered_key(self, public_key, private_key)`](/slides/python-net/ja/aspose.slides/metered/set_metered_key/#str-str) | メータードの公開キーと秘密キーを設定します。<br/>            メーターライセンスを購入した場合、アプリケーション起動時にこの API を呼び出す必要があり、通常はこれだけで十分です。<br/>            ただし、消費データのアップロードが常に失敗し、24 時間を超えると、ライセンスは評価ステータスに設定されます。<br/>            このような事態を回避するには、ライセンスステータスを定期的に確認し、評価ステータスである場合は再度この API を呼び出してください。 |
| [`get_consumption_quantity()`](/slides/python-net/ja/aspose.slides/metered/get_consumption_quantity/#) | 消費ファイルサイズを取得します |
| [`get_consumption_credit()`](/slides/python-net/ja/aspose.slides/metered/get_consumption_credit/#) | 消費クレジットを取得します |
| [`get_product_name(self)`](/slides/python-net/ja/aspose.slides/metered/get_product_name/#) |  |
| [`is_metered_licensed()`](/slides/python-net/ja/aspose.slides/metered/is_metered_licensed/#) | メータードがライセンスされているかどうかを確認します |


### 参照
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)