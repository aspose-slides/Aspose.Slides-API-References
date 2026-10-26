---
title: set_Overlap()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt an, um wie viel Balken und Spalten bei 2-D-Diagrammen überlappen sollen, als Prozentsatz (von -100% bis 100%).
type: docs
weight: 170
url: /de/aspose.slides.charts/chartseriesgroup/set_overlap/
---
## ChartSeriesGroup::set_Overlap(int8_t) method


Gibt an, um wie viel Balken und Spalten bei 2-D-Diagrammen überlappen sollen, als Prozentsatz (von -100% bis 100%).

```cpp
void Aspose::Slides::Charts::ChartSeriesGroup::set_Overlap(int8_t value) override
```

## Remarks


* -100%: Maximaler Abstand (Balken sind vollständig getrennt).
* 0%: Balken werden nebeneinander ohne Überlappung oder Abstand platziert.
* 100%: Maximale Überlappung (Balken überlappen einander vollständig). Diese Eigenschaft ist lesbar/schreibbar **int8_t**.



Das folgende Beispiel zeigt, wie die Überlappung für eine ChartSeriesGroup festgelegt und das resultierende Diagramm in einem Formular gerendert wird: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::SharedPtr<ISlide> slide = pres->get_Slide(0);

System::SharedPtr<IChart> chart = slide->get_Shapes()->AddChart(ChartType::ClusteredColumn, 10.0f, 10.0f, 600.0f, 300.0f);
System::SharedPtr<IChartSeriesCollection> series = chart->get_ChartData()->get_Series();
series->idx_get(0)->get_ParentSeriesGroup()->set_Overlap(55); // Überlappung auf 55% setzen

auto image = slide->GetImage(1.0f, 1.0f);
image->Save(u"image.png", ImageFormat::Png);
```


## See Also

* Class [ChartSeriesGroup](../)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)