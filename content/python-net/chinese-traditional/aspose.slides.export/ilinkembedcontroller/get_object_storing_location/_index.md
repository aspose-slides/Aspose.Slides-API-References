---
title: get_object_storing_location method
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides.export/ilinkembedcontroller/get_object_storing_location/
weight: 10
---
## get_object_storing_location(self, id, entity_data, semantic_name, content_type, recomended_extension) {#int-bytes-str-str-str}
確定物件應存放的位置。
此方法對每個物件 id 只會被呼叫一次。
無法保證不會有兩個具有相同 data、semanticName 和 contentType 但 id 不同的物件。

### 回傳
決策



```python
def get_object_storing_location(self, id, entity_data, semantic_name, content_type, recomended_extension):
    ...
```


| 參數 | 類型 | 描述 |
| :- | :- | :- |
| id | **int** | 物件 id。此 id 在整個儲存操作中是唯一的。 |
| entity_data | **bytes** | 物件二進位資料。若尚未產生物件二進位資料，此參數可以為 None。 |
| semantic_name | **str** | 描述物件意義的簡短文字。Controller 可能會將此作為外部物件名稱的一部分，但名稱唯一性與僅含允許字元的保證須由 dispatcher 負責。 |
| content_type | **str** | 物件的 MIME 類型。 |
| recomended_extension | **str** | 對此 MIME 類型建議使用的檔案副檔名。 |



### 另請參閱
* 類別 [`ILinkEmbedController`](/slides/python-net/zh-hant/aspose.slides.export/ilinkembedcontroller)
* 列舉 [`LinkEmbedDecision`](/slides/python-net/zh-hant/aspose.slides.export/linkembeddecision)
* 模組 [`aspose.slides.export`](/slides/python-net/zh-hant/aspose.slides.export)
* 函式庫 [`Aspose.Slides`](/slides/python-net)