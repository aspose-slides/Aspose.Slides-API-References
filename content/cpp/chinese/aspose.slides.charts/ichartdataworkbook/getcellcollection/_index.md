---
title: GetCellCollection()
second_title: Aspose.Slides C++ API 参考
description: 获取单元格集合。
type: docs
weight: 27
url: /zh/aspose.slides.charts/ichartdataworkbook/getcellcollection/
---
## IChartDataWorkbook::GetCellCollection(System::String, bool) 方法

获取单元格集合。

```cpp
virtual System::SharedPtr<IChartCellCollection> Aspose::Slides::Charts::IChartDataWorkbook::GetCellCollection(System::String formula, bool skipHiddenCells)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| formula | [System::String](../../../system/string/) | [Excel](../../../aspose.slides.excel/) formula 如 "Sheet1!$A$2:$A$5". |
| skipHiddenCells | **bool** | 如果为 true，则方法返回不包含隐藏单元格的集合。 |

### 返回值

单元格集合 [IChartCellCollection](../../ichartcellcollection/)

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IChartCellCollection](../../ichartcellcollection/)
* 类 [String](../../../system/string/)
* 类 [IChartDataWorkbook](../)
* 命名空间 [Aspose::Slides::Charts](../../)
* 库 [Aspose.Slides](../../../)