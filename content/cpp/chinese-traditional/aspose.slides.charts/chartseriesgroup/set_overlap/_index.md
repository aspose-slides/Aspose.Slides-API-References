---
title: set_Overlap()
second_title: Aspose.Slides for C++ API 參考文件
description: 指定在 2-D 圖表上，條形和柱形的重疊程度，以百分比表示（從 -100% 到 100%）。
type: docs
weight: 170
url: /zh-hant/aspose.slides.charts/chartseriesgroup/set_overlap/
---
## ChartSeriesGroup::set_Overlap(int8_t) 方法


指定在 2-D 圖表上，條形和柱形的重疊程度，以百分比表示（從 -100% 到 100%）。

```cpp
void Aspose::Slides::Charts::ChartSeriesGroup::set_Overlap(int8_t value) override
```

## 備註


* -100%：最大間距（條形完全分開）。
* 0%：條形並排放置，沒有重疊或間距。
* 100%：最大重疊（條形完全相互重疊）。此屬性為可讀寫 **int8_t**。



以下範例示範如何為圖表系列群組設定重疊，並在表單上呈現產生的圖表： 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::SharedPtr<ISlide> slide = pres->get_Slide(0);

System::SharedPtr<IChart> chart = slide->get_Shapes()->AddChart(ChartType::ClusteredColumn, 10.0f, 10.0f, 600.0f, 300.0f);
System::SharedPtr<IChartSeriesCollection> series = chart->get_ChartData()->get_Series();
series->idx_get(0)->get_ParentSeriesGroup()->set_Overlap(55); // 設定重疊為 55%

auto image = slide->GetImage(1.0f, 1.0f);
image->Save(u"image.png", ImageFormat::Png);
```


## 另請參閱

* 類別 [ChartSeriesGroup](../)
* 命名空間 [Aspose::Slides::Charts](../../)
* 函式庫 [Aspose.Slides](../../../)