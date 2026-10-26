---
title: get_url method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.export/ilinkembedcontroller/get_url/
weight: 20
---
## get_url(self, id, referrer) {#int-int}
外部オブジェクトへの URL を返します。
            このメソッドは、**Aspose.Slides.Export.ILinkEmbedController.GetObjectStoringLocation(System.Int32,System.Byte[],System.String,System.String,Syste** が [`LinkEmbedDecision.LINK`](/slides/python-net/ja/aspose.slides.export/linkembeddecision/LINK) を返した場合に常に呼び出され、**Aspose.Slides.Export.ILinkEmbedController.GetObjectStoringLocation(System.Int32,System.Byte[],System.String,System.String,Syste** が [`LinkEmbedDecision.EMBED`](/slides/python-net/ja/aspose.slides.export/linkembeddecision/EMBED) を返した場合にも呼び出される可能性がありますが、埋め込みは不可能です。
            同じオブジェクト ID に対して複数回呼び出すことができます。

### 戻り値

外部オブジェクトの URL、またはこのオブジェクトを無視すべき場合は None を返します.



```python
def get_url(self, id, referrer):
    ...
```


| パラメーター | 型 | 説明 |
| :- | :- | :- |
| id | **int** | オブジェクト ID。この ID は操作全体で一意です。 |
| referrer | **int** | 参照オブジェクトの ID、または 0（ルートドキュメントがオブジェクトを参照している場合）。相対リンク生成に使用できる場合があります。 |



### 参照
* クラス [`ILinkEmbedController`](/slides/python-net/ja/aspose.slides.export/ilinkembedcontroller)
* モジュール [`aspose.slides.export`](/slides/python-net/ja/aspose.slides.export)
* ライブラリ [`Aspose.Slides`](/slides/python-net)