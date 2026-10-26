---
title: get_Overlap()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt an, wie stark Balken und Säulen in 2-D-Diagrammen überlappen, als Prozentsatz (von -100% bis 100%). Dies ist die Eigenschaft nicht nur dieser Serie, sondern aller Serien der übergeordneten Seriengruppe. Sie ist eine Projektion der entsprechenden Eigenschaft in der übergeordneten Seriengruppe und daher ist diese Eigenschaft schreibgeschützt. Um den Wert zu ändern, verwenden Sie die Lese-/Schreib-Eigenschaft get_ParentSeriesGroup()->Overlap(). Nur lesbar int8_t.
type: docs
weight: 690
url: /de/aspose.slides.charts/chartseries/get_overlap/
---
## ChartSeries::get_Overlap() Methode

Gibt an, wie stark Balken und Säulen in 2-D-Diagrammen überlappen, als Prozentsatz (von -100% bis 100%). Dies ist die Eigenschaft nicht nur dieser Serie, sondern aller Serien der übergeordneten Seriengruppe. Sie ist eine Projektion der entsprechenden Eigenschaft in der übergeordneten Seriengruppe und daher ist diese Eigenschaft schreibgeschützt. Um den Wert zu ändern, verwenden Sie die [get_ParentSeriesGroup()->Overlap()](../get_parentseriesgroup/) lesbar/schreibbar Eigenschaft. Schreibgeschützt **int8_t**.

```cpp
int8_t Aspose::Slides::Charts::ChartSeries::get_Overlap() override
```

## Hinweise

Overlap gibt den Grad der Überlappung oder des Abstands zwischen Balken und Säulen als Prozentsatz ihrer Breite an:
* -100%: Maximaler Abstand (Balken sind vollständig getrennt).
* 0%: Balken werden nebeneinander ohne Überlappung oder Abstand platziert.
* 100%: Maximale Überlappung (Balken überlappen sich vollständig). Dies ist eine Projektion der Eigenschaft [get_ParentSeriesGroup()->Overlap()](../get_parentseriesgroup/).

## Siehe auch

* Klasse [ChartSeries](../)
* Namensraum [Aspose::Slides::Charts](../../)
* Bibliothek [Aspose.Slides](../../../)