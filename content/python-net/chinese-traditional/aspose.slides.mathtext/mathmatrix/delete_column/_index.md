---
title: delete_column method
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides.mathtext/mathmatrix/delete_column/
weight: 40
---
## delete_column(self, column_index) {#int}
刪除指定的欄位


```python
def delete_column(self, column_index):
    ...
```


| 參數 | 類型 | 描述 |
| :- | :- | :- |
| column_index | **int** | 要刪除的欄位的零基索引。 |

### 例外

| 例外 | 描述 |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | 當您嘗試刪除矩陣中最後唯一的欄位時 |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | 如果 columnIndex 小於零或大於或等於 ColumnCount |



### 參見
* 類別 [`MathMatrix`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathmatrix)
* 模組 [`aspose.slides.mathtext`](/slides/python-net/zh-hant/aspose.slides.mathtext)
* 函式庫 [`Aspose.Slides`](/slides/python-net)