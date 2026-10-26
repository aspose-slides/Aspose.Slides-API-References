---
title: set_LayoutTargetType()
second_title: Referensi API Aspose.Slides untuk C++
description: Jika tata letak area plot ditentukan secara manual, properti ini menentukan apakah menata area plot berdasarkan bagian dalamnya (tidak termasuk sumbu dan label sumbu) atau bagian luar (termasuk sumbu dan label sumbu). Tulis LayoutTargetType.
type: docs
weight: 183
url: /id/aspose.slides.charts/chartplotarea/set_layouttargettype/
---
## ChartPlotArea::set_LayoutTargetType(Aspose::Slides::Charts::LayoutTargetType) metode


Jika tata letak area plot ditentukan secara manual, properti ini menentukan apakah menata area plot berdasarkan bagian dalamnya (tidak termasuk sumbu dan label sumbu) atau bagian luar (termasuk sumbu dan label sumbu). Tuliskan [LayoutTargetType](../../layouttargettype/).

```cpp
void Aspose::Slides::Charts::ChartPlotArea::set_LayoutTargetType(Aspose::Slides::Charts::LayoutTargetType value) override
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
* Kelas [ChartPlotArea](../)
* Ruang Nama [Aspose::Slides::Charts](../../)
* Perpustakaan [Aspose.Slides](../../../)