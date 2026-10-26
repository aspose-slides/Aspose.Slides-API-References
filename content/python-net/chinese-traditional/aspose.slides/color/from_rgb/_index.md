---
title: from_rgb method
second_title: Aspose.Slides for Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides/color/from_rgb/
weight: 50
---
## from_rgb(r, g, b) {#int-int-int}
建立一個不透明的顏色（alpha 為 255），來源於指定的紅色、綠色和藍色數值。

### 回傳值

從指定的數值所建立的顏色。



```python
@staticmethod
def from_rgb(r, g, b):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| r | **int** | 紅色成分值。有效範圍為 0 到 255。 |
| g | **int** | 綠色成分值。有效範圍為 0 到 255。 |
| b | **int** | 藍色成分值。有效範圍為 0 到 255。 |

### 例外

| 例外 | 說明 |
| :- | :- |
| **ValueError** | 成分值小於 0 或大於 255。 |



### 另請參閱
* 類別 [`Color`](/slides/python-net/zh-hant/aspose.slides/color)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)