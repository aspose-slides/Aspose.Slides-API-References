---
title: get_object_storing_location method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.export/ilinkembedcontroller/get_object_storing_location/
weight: 10
---
## get_object_storing_location(self, id, entity_data, semantic_name, content_type, recomended_extension) {#int-bytes-str-str-str}
オブジェクトを保存すべき場所を決定します。
            このメソッドは各オブジェクト id に対して一度呼び出されます。
            同一のデータ、semanticName、contentType を持ち、かつ異なる id のオブジェクトが二つ存在しないことは保証されません。

### 戻り値

決定



```python
def get_object_storing_location(self, id, entity_data, semantic_name, content_type, recomended_extension):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| id | **int** | オブジェクト id。この id は保存操作全体で一意です。 |
| entity_data | **bytes** | オブジェクトのバイナリデータ。このパラメータは、オブジェクトのバイナリデータがまだ生成されていない場合、None にできます。 |
| semantic_name | **str** | オブジェクトの意味を説明する短いテキスト。Controller はこれを外部オブジェクト名の一部として使用することがありますが、名前が一意で許可された文字のみを含むことを保証するのはdispatcher の役割です。 |
| content_type | **str** | オブジェクトの MIME タイプ。 |
| recomended_extension | **str** | この MIME タイプに推奨されるファイル拡張子。 |



### 参照
* クラス [`ILinkEmbedController`](/slides/python-net/ja/aspose.slides.export/ilinkembedcontroller)
* enumeration [`LinkEmbedDecision`](/slides/python-net/ja/aspose.slides.export/linkembeddecision)
* モジュール [`aspose.slides.export`](/slides/python-net/ja/aspose.slides.export)
* library [`Aspose.Slides`](/slides/python-net)