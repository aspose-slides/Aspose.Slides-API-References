---
title: get_object_storing_location method
second_title: Aspose.Slides 用于 Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.export/ilinkembedcontroller/get_object_storing_location/
weight: 10
---
## get_object_storing_location(self, id, entity_data, semantic_name, content_type, recomended_extension) {#int-bytes-str-str-str}
确定对象应该存储的位置。
            此方法针对每个对象 id 调用一次。
            不能保证不会存在两个具有相同数据、semanticName 和 contentType，但 id 不同的对象。

### 返回

决定



```python
def get_object_storing_location(self, id, entity_data, semantic_name, content_type, recomended_extension):
    ...
```


| 参数 | 类型 | 描述 |
| :- | :- | :- |
| id | **int** | 对象 id。此 id 在整个保存操作中唯一。 |
| entity_data | **bytes** | 对象二进制数据。如果对象二进制数据尚未生成，此参数可以为 None。 |
| semantic_name | **str** | 描述对象含义的简短文本。控制器可以将其作为外部对象名称的一部分，但由调度器确保名称唯一且仅包含允许的字符。 |
| content_type | **str** | 对象的 MIME 类型。 |
| recomended_extension | **str** | 文件扩展名，推荐用于此 MIME 类型。 |



### 另请参见
* 类 [`ILinkEmbedController`](/slides/python-net/zh/aspose.slides.export/ilinkembedcontroller)
* 枚举 [`LinkEmbedDecision`](/slides/python-net/zh/aspose.slides.export/linkembeddecision)
* 模块 [`aspose.slides.export`](/slides/python-net/zh/aspose.slides.export)
* 库 [`Aspose.Slides`](/slides/python-net)