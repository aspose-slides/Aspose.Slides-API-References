---
title: GetCellCollection()
second_title: Aspose.Slides for C++ API 参考
description: 获取单元格集合。
type: docs
weight: 14
url: /zh/aspose.slides.charts/chartdataworkbook/getcellcollection/
---
## ChartDataWorkbook::GetCellCollection(System::String, bool) 方法

获取单元格集合。

```cpp
System::SharedPtr<IChartCellCollection> Aspose::Slides::Charts::ChartDataWorkbook::GetCellCollection(System::String formula, bool skipHiddenCells) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| formula | [System::String](../../../system/string/) | [Excel](../../../aspose.slides.excel/) 公式，类似 "Sheet1!$A$2:$A$5"。 |
| skipHiddenCells | **bool** | 如果为 true，则方法返回不含隐藏单元格的集合。 |

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IChartCellCollection](../../ichartcellcollection/)
* 类 [String](../../../system/string/)
* 类 [ChartDataWorkbook](../)
* 命名空间 [Aspose::Slides::Charts](../../)
* 库 [Aspose.Slides](../../../)