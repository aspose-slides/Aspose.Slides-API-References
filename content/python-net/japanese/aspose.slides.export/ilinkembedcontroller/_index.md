---
title: ILinkEmbedController class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.export/ilinkembedcontroller/
---
## ILinkEmbedController クラス

コールバックインターフェイスは、保存時にオブジェクトをどのように処理すべきかを決定するために使用されます。

ILinkEmbedController 型は以下のメンバーを公開します：

## メソッド

| メソッド | 説明 |
| :- | :- |
| [`get_object_storing_location(self, id, entity_data, semantic_name, content_type, recomended_extension)`](/slides/python-net/ja/aspose.slides.export/ilinkembedcontroller/get_object_storing_location/#int-bytes-str-str-str) | オブジェクトの保存場所を決定します。<br/>            このメソッドは各オブジェクト id ごとに一度呼び出されます。<br/>            同じ data、semanticName、contentType で異なる id を持つオブジェクトが存在する可能性があることは保証されません。 |
| [`get_url(self, id, referrer)`](/slides/python-net/ja/aspose.slides.export/ilinkembedcontroller/get_url/#int-int) | 外部オブジェクトへの URL を返します。<br/>            このメソッドは **Aspose.Slides.Export.ILinkEmbedController.GetObjectStoringLocation(System.Int32,System.Byte[],System.String,System.String,Syste** が [`LinkEmbedDecision.LINK`](/slides/python-net/ja/aspose.slides.export/linkembeddecision/LINK) を返した場合に常に呼び出され、**Aspose.Slides.Export.ILinkEmbedController.GetObjectStoringLocation(System.Int32,System.Byte[],System.String,System.String,Syste** が [`LinkEmbedDecision.EMBED`](/slides/python-net/ja/aspose.slides.export/linkembeddecision/EMBED) を返した場合に呼び出される可能性がありますが、埋め込みは不可能です。<br/>            同じオブジェクト id に対して複数回呼び出すことができます。 |
| [`save_external(self, id, entity_data)`](/slides/python-net/ja/aspose.slides.export/ilinkembedcontroller/save_external/#int-bytes) | 外部オブジェクトを保存します。 |


### 参照
* モジュール [`aspose.slides.export`](/slides/python-net/ja/aspose.slides.export)
* ライブラリ [`Aspose.Slides`](/slides/python-net)