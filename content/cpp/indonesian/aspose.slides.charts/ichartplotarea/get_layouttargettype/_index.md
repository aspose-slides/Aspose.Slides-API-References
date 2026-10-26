---
title: get_LayoutTargetType()
second_title: Aspose.Slides untuk Referensi API C++
description: Jika tata letak area plot ditentukan secara manual, properti ini menentukan apakah tata letak area plot menggunakan bagian dalamnya (tidak termasuk sumbu dan label sumbu) atau bagian luarnya (termasuk sumbu dan label sumbu). Baca LayoutTargetType.
type: docs
weight: 14
url: /id/aspose.slides.charts/ichartplotarea/get_layouttargettype/
---
## IChartPlotArea::get_LayoutTargetType() metode


Jika tata letak area plot ditentukan secara manual, properti ini menentukan apakah tata letak area plot menggunakan bagian dalamnya (tidak termasuk sumbu dan label sumbu) atau bagian luar (termasuk sumbu dan label sumbu). Baca [LayoutTargetType](../../layouttargettype/).

```cpp
virtual Aspose::Slides::Charts::LayoutTargetType Aspose::Slides::Charts::IChartPlotArea::get_LayoutTargetType()=0
```

## Catatan



```cpp
auto presentation = MakeObject<Presentation>();
auto slide = presentation->get_Slides()->idx_get(0);
auto chart = slide->get_Shapes()->AddChart(ChartType::ClusteredColumn, 20.0f, 100.0f, 600.0f, 400.0f);

chart->get_PlotArea()->set_X(0.2f);
chart->get_PlotArea()->set_Y(0.2f);
chart->get_PlotArea()->set_Width(0.7f);
chart->get_PlotArea()->set_Height(0.7f);

chart->get_PlotArea()->set_LayoutTargetType(LayoutTargetType::Inner);
// ...
```

## Lihat Juga

* Enum [LayoutTargetType](../../layouttargettype/)
* Kelas [IChartPlotArea](../)
* Ruang Nama [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)