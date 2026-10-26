---
title: get_DataSourceType()
second_title: Aspose.Slides C++ API 参考
description: "指定在派生类中实际使用的是 AsCell、AsCells、AsLiteralString 或 AsLiteralDouble 属性。换句话说，它指定 Data 属性的值的类型。阅读 Charts::DataSourceType。"
type: docs
weight: 1
url: /zh/aspose.slides.charts/basechartvalue/get_datasourcetype/
---
## BaseChartValue::get_DataSourceType() 方法

指定在派生类中实际使用的是 AsCell、AsCells、AsLiteralString 或 AsLiteralDouble 属性。换句话说，它指定 Data 属性的值的类型。阅读 [Charts::DataSourceType](../../datasourcetype/)。

```cpp
Aspose::Slides::Charts::DataSourceType Aspose::Slides::Charts::BaseChartValue::get_DataSourceType() override
```

## 备注

对于 [ChartDataPointCollection](../../chartdatapointcollection/) 中的点，此属性为只读。在这种情况下，要更改此属性的值，您可以使用 ChartDataPointCollection.DataSourceTypeFor<...> 属性之一。

## 另见

* 枚举 [DataSourceType](../../datasourcetype/)
* 类 [BaseChartValue](../)
* 命名空间 [Aspose::Slides::Charts](../../)
* 库 [Aspose.Slides](../../../)