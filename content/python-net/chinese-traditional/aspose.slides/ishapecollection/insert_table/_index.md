---
title: insert_table method
second_title: Aspose.Slides 用於 Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides/ishapecollection/insert_table/
weight: 320
---
## insert_table(self, index, x, y, column_widths, row_heights) {#int-float-float-listfloat-listfloat}
在指定索引處建立新表格，並將其插入形狀集合中。

### 返回值
新建立的 [`ITable`](/slides/python-net/zh-hant/aspose.slides/itable)。

```python
def insert_table(self, index, x, y, column_widths, row_heights):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| index | **int** | The zero-based index at which to insert the table. |
| x | **float** | The x-coordinate of the table, in points. |
| y | **float** | The y-coordinate of the table, in points. |
| column_widths | **List[float]** | 一個雙精度陣列，表示表格的<br/><br/>            欄寬（以點為單位）。 |
| row_heights | **List[float]** | 一個雙精度陣列，表示表格的<br/><br/>            列高（以點為單位）。 |

### 另見
* 類別 [`IShapeCollection`](/slides/python-net/zh-hant/aspose.slides/ishapecollection)
* 類別 [`ITable`](/slides/python-net/zh-hant/aspose.slides/itable)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)