---
title: get_cells method
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.excel/exceldataworkbook/get_cells/
weight: 30
---
## get_cells(self, formula, skip_hidden_cells) {#str-bool}
检索工作簿中与指定公式匹配的单元格集合。

### 返回

一个只读的单元格列表，匹配指定的公式。

```python
def get_cells(self, formula, skip_hidden_cells):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| formula | **str** | 用于标识目标单元格的公式或范围表达式（例如 "Sheet1!A1:B3"）。 |
| skip_hidden_cells | **bool** | 如果 `true`，隐藏的单元格（例如隐藏的行或列中）将从结果中排除。 |

### 另请参阅
* 类 [`ExcelDataWorkbook`](/slides/python-net/zh/aspose.slides.excel/exceldataworkbook)
* 模块 [`aspose.slides.excel`](/slides/python-net/zh/aspose.slides.excel)
* 库 [`Aspose.Slides`](/slides/python-net)