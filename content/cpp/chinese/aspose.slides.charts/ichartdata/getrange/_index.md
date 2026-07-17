---
title: GetRange()
second_title: Aspose.Slides C++ API 参考
description: 获取图表数据范围。
type: docs
weight: 170
url: /zh/aspose.slides.charts/ichartdata/getrange/
---
## IChartData::GetRange() method


获取图表数据范围。

```cpp
virtual System::String Aspose::Slides::Charts::IChartData::GetRange()=0
```


### 返回值

单元格数据范围公式。例如："Sheet1!$A$1:$C$4"
## 备注




```cpp
auto pres = MakeObject<Presentation>();
auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(Charts::ChartType::PercentsStackedBar, 100.0f, 100.0f, 500.0f, 400.0f);
String result = (AsCast<Charts::ChartData>(chart->get_ChartData()))->GetRange();
```

## 另请参见

* 类 [String](../../../system/string/)
* 类 [IChartData](../)
* 命名空间 [Aspose::Slides::Charts](../../)
* 库 [Aspose.Slides](../../../)