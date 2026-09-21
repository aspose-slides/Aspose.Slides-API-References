---
title: get_font_embedding_level method
second_title: Aspose.Slides for Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides/ifontsmanager/get_font_embedding_level/
weight: 40
---
## get_font_embedding_level(self, font_bytes, font_name) {#bytes-str}
根據給定的位元組陣列和字體名稱判斷字體的嵌入等級。

### 返回

指定字體的嵌入等級。

```python
def get_font_embedding_level(self, font_bytes, font_name):
    ...
```

| 參數 | 類型 | 說明 |
| :- | :- | :- |
| font_bytes | **bytes** | 包含字體資料的位元組陣列。 |
| font_name | **str** | 字體的名稱。 |

### 例外

| 例外 | 說明 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | 當 `font_bytes` 為 None 時拋出。 |

### 另見
* 列舉 [`EmbeddingLevel`](/slides/python-net/zh-hant/aspose.slides/embeddinglevel)
* 類別 [`IFontsManager`](/slides/python-net/zh-hant/aspose.slides/ifontsmanager)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)