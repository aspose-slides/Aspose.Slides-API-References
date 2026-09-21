---
title: get_font_embedding_level method
second_title: Aspose.Slides for Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides/fontsmanager/get_font_embedding_level/
weight: 40
---
## get_font_embedding_level(self, font_bytes, font_name) {#bytes-str}
判斷字型在給定的位元組陣列和字型名稱之下的嵌入層級。

### Returns
指定字型的嵌入層級。

```python
def get_font_embedding_level(self, font_bytes, font_name):
    ...
```

| 參數 | 類型 | 描述 |
| :- | :- | :- |
| font_bytes | **bytes** | 包含字型資料的位元組陣列。 |
| font_name | **str** | 字型的名稱。 |

### Exceptions

| 例外 | 描述 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | 當 `font_bytes` 為 None 時拋出。 |

### See Also
* 列舉 [`EmbeddingLevel`](/slides/python-net/zh-hant/aspose.slides/embeddinglevel)
* 類別 [`FontsManager`](/slides/python-net/zh-hant/aspose.slides/fontsmanager)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)