---
title: GetRange()
second_title: Aspose.Slides for C++ API 參考文件
description: 取得圖表資料範圍。
type: docs
weight: 170
url: /zh-hant/aspose.slides.charts/ichartdata/getrange/
---
## IChartData::GetRange() 方法

取得圖表資料範圍。

```cpp
virtual System::String Aspose::Slides::Charts::IChartData::GetRange()=0
```

### 回傳值

儲存格資料範圍公式。例如："Sheet1!$A$1:$C$4"
## 備註

```cpp
auto pres = MakeObject<Presentation>();
auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(Charts::ChartType::PercentsStackedBar, 100.0f, 100.0f, 500.0f, 400.0f);
String result = (AsCast<Charts::ChartData>(chart->get_ChartData()))->GetRange();
```

## 另請參閱

* 類別 [String](../../../system/string/)
* 類別 [IChartData](../)
* 命名空間 [Aspose::Slides::Charts](../../)
* 函式庫 [Aspose.Slides](../../../)