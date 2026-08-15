---
title: get_Overlap()
second_title: Aspose.Slides for C++ API 參考文件
description: 指定條形圖和柱狀圖在 2-D 圖表上重疊的程度，以百分比表示（從 -100% 到 100%）。
type: docs
weight: 183
url: /zh-hant/aspose.slides.charts/ichartseriesgroup/get_overlap/
---
## IChartSeriesGroup::get_Overlap() 方法

指定條形圖和柱狀圖在 2-D 圖表上重疊的程度，以百分比表示（介於 -100% 到 100% 之間）。

```cpp
virtual int8_t Aspose::Slides::Charts::IChartSeriesGroup::get_Overlap()=0
```

## 備註

* -100%：最大間距（條形圖完全分離）。
* 0%：條形圖並排放置，沒有重疊或間距。
* 100%：最大重疊（條形圖彼此完全重疊）。此屬性為可讀寫 **int8_t**。

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

* 類別 [IChartSeriesGroup](../)
* 命名空間 [Aspose::Slides::Charts](../../)
* 函式庫 [Aspose.Slides](../../../)