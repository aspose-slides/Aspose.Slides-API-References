---
title: GetRange()
second_title: Aspose.Slides for C++ API 參考
description: 取得圖表資料範圍。
type: docs
weight: 157
url: /zh-hant/aspose.slides.charts/chartdata/getrange/
---
## ChartData::GetRange() 方法


Gets chart data range.

```cpp
System::String Aspose::Slides::Charts::ChartData::GetRange() override
```


### 返回值

儲存格資料範圍公式。例如：\"Sheet1!$A$1:$C$4\"
## 備註




```cpp
auto pres = MakeObject<Presentation>();
auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(Charts::ChartType::PercentsStackedBar, 0.0f, 0.0f, 100.0f, 100.0f);
String result = (AsCast<Charts::ChartData>(chart->get_ChartData()))->GetRange();
```

## 另見

* 類別 [String](../../../system/string/)
* 類別 [ChartData](../)
* 命名空間 [Aspose::Slides::Charts](../../)
* 函式庫 [Aspose.Slides](../../../)