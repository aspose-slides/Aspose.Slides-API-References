---
title: get_font_embedding_level method
second_title: Aspose.Slides 用于 Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/fontsmanager/get_font_embedding_level/
weight: 40
---
## get_font_embedding_level(self, font_bytes, font_name) {#bytes-str}
确定给定字节数组和字体名称的字体的嵌入级别。

### 返回

指定字体的嵌入级别。



```python
def get_font_embedding_level(self, font_bytes, font_name):
    ...
```


| 参数 | 类型 | 描述 |
| :- | :- | :- |
| font_bytes | **bytes** | 包含字体数据的字节数组。 |
| font_name | **str** | 字体的名称。 |

### 异常

| 异常 | 描述 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | 当 `font_bytes` 为 None 时抛出。 |



### 参见
* 枚举 [`EmbeddingLevel`](/slides/python-net/zh/aspose.slides/embeddinglevel)
* 类 [`FontsManager`](/slides/python-net/zh/aspose.slides/fontsmanager)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)