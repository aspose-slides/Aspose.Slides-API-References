---
title: copy_to method
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides/paragraphcollection/copy_to/
weight: 50
---
## copy_to(self, array, array_index) {#listiparagraph-int}
將 **System.Collections.Generic.ICollection`1** 的元素複製到 **System.Array**，從特定的 **System.Array** 索引開始。


```python
def copy_to(self, array, array_index):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| array | **List[IParagraph]** | 一維的 **System.Array**，作為從 **System.Collections.Generic.ICollection`1** 複製過來的元素的目的地。**System.Array** 必須使用零基索引。 |
| array_index | **int** | 在 `array` 中開始複製的零基索引。 |

### 例外

| 例外 | 說明 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | `array` 為 None。 |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | `array_index` 小於 0。 |
| **RuntimeError(Proxy error(ArgumentException))** | 來源 **System.Collections.Generic.ICollection`1** 中的元素數量大於從 `array_index` 到目標 `array` 結尾的可用空間。 |



### 另請參閱
* 類別 [`ParagraphCollection`](/slides/python-net/zh-hant/aspose.slides/paragraphcollection)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)