---
title: get_PieSplitBy()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt an, wie bestimmt wird, welche Datenpunkte im zweiten Kuchen oder Balken eines Kuchen-aus-Kuchen- oder Balken-aus-Kuchen-Diagramms liegen. Dies ist die Eigenschaft nicht nur dieser Serie, sondern aller Serien der übergeordneten Seriengruppe – dies ist die Projektion der entsprechenden Gruppeneigenschaft. Daher ist diese Eigenschaft schreibgeschützt. Verwenden Sie die ParentSeriesGroup-Eigenschaft, um auf die übergeordnete Seriengruppe zuzugreifen. Verwenden Sie get_ParentSeriesGroup()->get(set)_PieSplitBy() Lese-/Schreib-Eigenschaft, um den Wert zu ändern. Schreibgeschützter PieSplitType.
type: docs
weight: 729
url: /de/aspose.slides.charts/ichartseries/get_piesplitby/
---
## IChartSeries::get_PieSplitBy() Methode


Gibt an, wie bestimmt wird, welche Datenpunkte im zweiten Kuchen oder Balken eines Kuchen-aus-Kuchen- oder Balken-aus-Kuchen-Diagramms liegen. Dies ist die Eigenschaft nicht nur dieser Serie, sondern aller Serien der übergeordneten Seriengruppe – dies ist die Projektion der entsprechenden Gruppeneigenschaft. Und daher ist diese Eigenschaft schreibgeschützt. Verwenden Sie die ParentSeriesGroup-Eigenschaft, um auf die übergeordnete Seriengruppe zuzugreifen. Verwenden Sie [get_ParentSeriesGroup()](../get_parentseriesgroup/)->get(set)_PieSplitBy() Lese-/Schreib-Eigenschaft, um den Wert zu ändern. Nur-Lesen [PieSplitType](../../piesplittype/).

```cpp
virtual PieSplitType Aspose::Slides::Charts::IChartSeries::get_PieSplitBy()=0
```

## Hinweise


1) Dies ist die Projektion der Eigenschaft [get_ParentSeriesGroup()](../get_parentseriesgroup/)->get(set)_PieSplitBy(). 2) Wenn der Eigenschaftswert [PieSplitType::Custom](../../piesplittype/) ist, können Sie benutzerdefinierte Split-Informationen mit [get_ParentSeriesGroup()](../get_parentseriesgroup/)->[get_PieSplitCustomPoints()](../get_piesplitcustompoints/)-Eigenschaft definieren. 
## Siehe auch

* Enum [PieSplitType](../../piesplittype/)
* Klasse [IChartSeries](../)
* Namensraum [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)