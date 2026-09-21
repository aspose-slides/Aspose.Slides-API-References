---
title: copy_to method
second_title: Aspose.Slides for Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides.animation/behaviorcollection/copy_to/
weight: 40
---
## copy_to(self, array, array_index) {#listibehavior-int}
將 **System.Collections.Generic.ICollection`1** 的元素複製到 **System.Array**，從特定的 **System.Array** 索引開始。

```python
def copy_to(self, array, array_index):
    ...
```

| 參數 | 類型 | 說明 |
| :- | :- | :- |
| array | **List[IBehavior]** | 目標為 **System.Array** 的單維陣列，接收從 **System.Collections.Generic.ICollection`1** 複製的元素。**System.Array** 必須使用零基索引。 |
| array_index | **int** | 在 `array` 中開始複製的零基索引。 |

### 例外情況

| 例外 | 說明 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | `array` 為 None。 |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | `array_index` 小於 0。 |
| **RuntimeError(Proxy error(ArgumentException))** | 來源 **System.Collections.Generic.ICollection`1** 的元素數量大於從 `array_index` 到目的地 `array` 結尾的可用空間。 |

### 另請參閱
* 類別 [`BehaviorCollection`](/slides/python-net/zh-hant/aspose.slides.animation/behaviorcollection)
* 模組 [`aspose.slides.animation`](/slides/python-net/zh-hant/aspose.slides.animation)
* 函式庫 [`Aspose.Slides`](/slides/python-net)