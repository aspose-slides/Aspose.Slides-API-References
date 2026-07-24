---
title: get_Overlap()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt an, wie stark Balken und Säulen in 2-D Diagrammen überlappen, als Prozentsatz (von -100% bis 100%). Dies ist die Eigenschaft nicht nur dieser Datenreihe, sondern aller Datenreihen der übergeordneten Seriengruppe. Sie ist eine Projektion der entsprechenden Eigenschaft in der übergeordneten Seriengruppe, daher ist diese Eigenschaft schreibgeschützt. Um den Wert zu ändern, verwenden Sie die get_ParentSeriesGroup()->get(set)_Overlap() Lese/Schreib-Eigenschaft. Schreibgeschützt int8_t.
type: docs
weight: 690
url: /de/aspose.slides.charts/ichartseries/get_overlap/
---
## IChartSeries::get_Overlap() Methode

Gibt an, wie stark Balken und Säulen in 2-D-Diagrammen überlappen, als Prozentsatz (von -100 % bis 100 %). Dies ist die Eigenschaft nicht nur dieser Datenreihe, sondern aller Datenreihen der übergeordneten Seriengruppe. Sie ist eine Projektion der entsprechenden Eigenschaft in der übergeordneten Seriengruppe und daher ist diese Eigenschaft schreibgeschützt. Um den Wert zu ändern, verwenden Sie die [get_ParentSeriesGroup()](../get_parentseriesgroup/)->get(set)_Overlap() Lese/Schreib-Eigenschaft. Schreibgeschützt **int8_t**.

```cpp
virtual int8_t Aspose::Slides::Charts::IChartSeries::get_Overlap()=0
```

## Anmerkungen

Overlap gibt den Grad der Überlappung oder des Abstands zwischen Balken und Säulen als Prozentsatz ihrer Breite an:
* -100 %: Maximaler Abstand (Balken sind vollständig getrennt).
* 0 %: Balken werden nebeneinander ohne Überlappung oder Abstand platziert.
* 100 %: Maximale Überlappung (Balken überlappen sich vollständig). Dies ist eine Projektion der Eigenschaft [get_ParentSeriesGroup()](../get_parentseriesgroup/)->get(set)_Overlap().

## Siehe auch

* Klasse [IChartSeries](../)
* Namensraum [Aspose::Slides::Charts](../../)
* Bibliothek [Aspose.Slides](../../../)