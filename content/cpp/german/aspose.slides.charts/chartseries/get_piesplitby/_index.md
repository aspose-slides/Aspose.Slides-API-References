---
title: get_PieSplitBy()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt an, wie bestimmt wird, welche Datenpunkte im zweiten Kuchen oder Balken eines Kuchen-im-Kuchen- oder Balken-im-Kuchen-Diagramms liegen. Dies ist nicht nur die Eigenschaft dieser Serie, sondern von allen Serien der übergeordneten Seriengruppe – dies ist die Projektion der entsprechenden Gruppeneigenschaft. Und daher ist diese Eigenschaft schreibgeschützt. Verwenden Sie die ParentSeriesGroup-Eigenschaft, um auf die übergeordnete Seriengruppe zuzugreifen. Verwenden Sie get_ParentSeriesGroup()->get(set)_PieSplitBy() Lese/Schreib-Eigenschaft, um den Wert zu ändern. Schreibgeschützt PieSplitType.
type: docs
weight: 755
url: /de/aspose.slides.charts/chartseries/get_piesplitby/
---
## ChartSeries::get_PieSplitBy() Methode

Gibt an, wie bestimmt wird, welche Datenpunkte im zweiten Kuchen oder Balken eines Kuchen-im-Kuchen- oder Balken-im-Kuchen-Diagramms liegen. Dies ist nicht nur die Eigenschaft dieser Serie, sondern von allen Serien der übergeordneten Seriengruppe – dies ist die Projektion der entsprechenden Gruppeneigenschaft. Und daher ist diese Eigenschaft schreibgeschützt. Verwenden Sie die ParentSeriesGroup-Eigenschaft, um auf die übergeordnete Seriengruppe zuzugreifen. Verwenden Sie [get_ParentSeriesGroup()](../get_parentseriesgroup/)->get(set)_PieSplitBy() Lese/Schreib-Eigenschaft, um den Wert zu ändern. Schreibgeschützt [PieSplitType](../../piesplittype/).

```cpp
PieSplitType Aspose::Slides::Charts::ChartSeries::get_PieSplitBy() override
```

## Hinweise

1) Dies ist die Projektion der Eigenschaft [get_ParentSeriesGroup()](../get_parentseriesgroup/)->get(set)_PieSplitBy().
2) Wenn der Eigenschaftswert [PieSplitType::Custom](../../piesplittype/) ist, können Sie benutzerdefinierte Split-Informationen mit der [get_ParentSeriesGroup()](../get_parentseriesgroup/)->[get_PieSplitCustomPoints()](../get_piesplitcustompoints/)-Eigenschaft festlegen.

## Siehe auch

* Enum [PieSplitType](../../piesplittype/)
* Klasse [ChartSeries](../)
* Namensraum [Aspose::Slides::Charts](../../)
* Bibliothek [Aspose.Slides](../../../)