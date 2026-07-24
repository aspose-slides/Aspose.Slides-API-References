---
title: get_Overlap()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt an, wie stark Balken und Spalten in 2-D-Diagrammen überlappen sollen, als Prozentsatz (von -100% bis 100%).
type: docs
weight: 183
url: /de/aspose.slides.charts/ichartseriesgroup/get_overlap/
---
## IChartSeriesGroup::get_Overlap() Methode


Gibt an, wie stark Balken und Spalten in 2-D-Diagrammen überlappen sollen, als Prozentsatz (von -100% bis 100%).

```cpp
virtual int8_t Aspose::Slides::Charts::IChartSeriesGroup::get_Overlap()=0
```

## Hinweise

* -100%: Maximaler Abstand (Balken sind vollständig getrennt).
* 0%: Balken werden nebeneinander ohne Überlappung oder Abstand positioniert.
* 100%: Maximale Überlappung (Balken überlappen sich vollständig). Diese Eigenschaft ist lesbar/schreibbar **int8_t**.



Das folgende Beispiel zeigt, wie die Überlappung für eine Diagramm-Seriengruppe festgelegt und das resultierende Diagramm in einem Formular dargestellt wird: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::SharedPtr<ISlide> slide = pres->get_Slide(0);

System::SharedPtr<IChart> chart = slide->get_Shapes()->AddChart(ChartType::ClusteredColumn, 10.0f, 10.0f, 600.0f, 300.0f);
System::SharedPtr<IChartSeriesCollection> series = chart->get_ChartData()->get_Series();
series->idx_get(0)->get_ParentSeriesGroup()->set_Overlap(55); // Setze die Überlappung auf 55%

auto image = slide->GetImage(1.0f, 1.0f);
image->Save(u"image.png", ImageFormat::Png);
```


## Siehe auch

* Klasse [IChartSeriesGroup](../)
* Namensraum [Aspose::Slides::Charts](../../)
* Bibliothek [Aspose.Slides](../../../)