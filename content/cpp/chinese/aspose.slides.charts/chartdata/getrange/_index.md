---
title: GetRange()
second_title: Aspose.Slides C++ API 参考
description: 获取图表数据范围。
type: docs
weight: 157
url: /zh/aspose.slides.charts/chartdata/getrange/
---
## ChartData::GetRange() 方法

获取图表数据范围。

```cpp
System::String Aspose::Slides::Charts::ChartData::GetRange() override
```

### 返回值

单元格数据范围公式。例如："Sheet1!$A$1:$C$4"

## 备注

```cpp
auto pres = MakeObject<Presentation>();
auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(Charts::ChartType::PercentsStackedBar, 0.0f, 0.0f, 100.0f, 100.0f);
String result = (AsCast<Charts::ChartData>(chart->get_ChartData()))->GetRange();
```

## 另请参见

* 类 [String](../../../system/string/)
* 类 [ChartData](../)
* 命名空间 [Aspose::Slides::Charts](../../)
* 库 [Aspose.Slides](../../../)