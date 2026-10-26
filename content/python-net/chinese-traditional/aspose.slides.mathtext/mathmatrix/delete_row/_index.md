---
title: delete_row method
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides.mathtext/mathmatrix/delete_row/
weight: 50
---
## delete_row(self, row_index) {#int}
刪除指定的行


```python
def delete_row(self, row_index):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| row_index | **int** | 要刪除的行的零基索引。 |

### 例外

| 例外 | 說明 |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | 嘗試刪除矩陣中最後唯一一行時 |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | 如果 rowIndex 小於零或大於等於 RowCount |



### 另請參閱
* 類別 [`MathMatrix`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathmatrix)
* 模組 [`aspose.slides.mathtext`](/slides/python-net/zh-hant/aspose.slides.mathtext)
* 函式庫 [`Aspose.Slides`](/slides/python-net)