---
title: StringOrDoubleChartValue
second_title: Aspose.Slides for .NET API 参考
description: 表示字符串或双精度值可以通过两种方式存储在 pptx 演示文档中 1 在与图表相关的工作簿的单元格中 2 作为文字值
type: docs
weight: 2280
url: /zh/aspose.slides.charts/stringordoublechartvalue/
---
## StringOrDoubleChartValue class

表示字符串或双精度值，可以通过两种方式存储在 pptx 演示文档中: 1) 在与图表相关的工作簿的单元格中; 2) 作为文字值。

```csharp
public class StringOrDoubleChartValue : BaseChartValue, IStringOrDoubleChartValue
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| [AsCell](../../aspose.slides.charts/stringordoublechartvalue/ascell) { get; set; } | 返回或设置图表数据单元格。 读/写[`IChartDataCell`](../ichartdatacell)。 |
| [AsLiteralDouble](../../aspose.slides.charts/stringordoublechartvalue/asliteraldouble) { get; set; } | 以字面双精度返回或设置值。 读/写Double。 |
| [AsLiteralString](../../aspose.slides.charts/stringordoublechartvalue/asliteralstring) { get; set; } | 将值返回或设置为文字字符串。 读/写String。 |
| override [Data](../../aspose.slides.charts/stringordoublechartvalue/data) { get; set; } | 返回或设置数据对象。 读/写Object。 |
| [DataSourceType](../../aspose.slides.charts/basechartvalue/datasourcetype) { get; set; } | 指定 AsCell、AsCells、AsLiteralString 或 AsLiteralDouble 属性是否在后代中是实际的。换句话说，它指定了 Data 属性值的类型 。 读/写[`DataSourceType`](../datasourcetype)。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [ToDouble](../../aspose.slides.charts/stringordoublechartvalue/todouble)() | 转换为双精度。 |

### 也可以看看

* class [BaseChartValue](../basechartvalue)
* interface [IStringOrDoubleChartValue](../istringordoublechartvalue)
* 命名空间 [Aspose.Slides.Charts](../../aspose.slides.charts)
* 部件 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
