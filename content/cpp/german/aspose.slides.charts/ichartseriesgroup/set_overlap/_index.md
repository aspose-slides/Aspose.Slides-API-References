---
title: set_Overlap()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt an, wie stark Balken und Säulen in 2-D-Diagrammen überlappen sollen, als Prozentsatz (von -100% bis 100%).
type: docs
weight: 196
url: /de/aspose.slides.charts/ichartseriesgroup/set_overlap/
---
## IChartSeriesGroup::set_Overlap(int8_t) Methode

Gibt an, wie stark Balken und Säulen in 2-D-Diagrammen überlappen sollen, als Prozentsatz (von -100% bis 100%).

```cpp
virtual void Aspose::Slides::Charts::IChartSeriesGroup::set_Overlap(int8_t value)=0
```

## Hinweise

* -100%: Maximaler Abstand (Balken sind vollständig getrennt).
* 0%: Balken werden nebeneinander ohne Überlappung oder Abstand platziert.
* 100%: Maximale Überlappung (Balken überlappen sich vollständig). Diese Eigenschaft ist les- und schreibbar **int8_t**.

Das folgende Beispiel zeigt, wie man die Überlappung für eine Diagramm-Seriengruppe festlegt und das resultierende Diagramm in einem Formular rendert: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::SharedPtr<ISlide> slide = pres->get_Slide(0);

System::SharedPtr<IChart> chart = slide->get_Shapes()->AddChart(ChartType::ClusteredColumn, 10.0f, 10.0f, 600.0f, 300.0f);
System::SharedPtr<IChartSeriesCollection> series = chart->get_ChartData()->get_Series();
series->idx_get(0)->get_ParentSeriesGroup()->set_Overlap(55); // Setzt die Überlappung auf 55%

auto image = slide->GetImage(1.0f, 1.0f);
image->Save(u"image.png", ImageFormat::Png);
```

## Siehe auch

* Klasse [IChartSeriesGroup](../)
* Namensraum [Aspose::Slides::Charts](../../)
* Bibliothek [Aspose.Slides](../../../)