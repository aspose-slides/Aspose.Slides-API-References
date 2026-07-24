---
title: get_ShowValue()
second_title: Aspose.Slides für C++ API Referenz
description: Stellt das Anzeigeverhalten des prozentualen Datenbeschriftungswerts eines angegebenen Diagramms dar. True zeigt den Prozentwert an. False versteckt ihn. Lese bool.
type: docs
weight: 118
url: /de/aspose.slides.charts/datalabelformat/get_showvalue/
---
## DataLabelFormat::get_ShowValue() Methode

Stellt das Anzeigeverhalten des prozentualen Datenbeschriftungswerts eines angegebenen Diagramms dar. True zeigt den Prozentwert an. False versteckt ihn. Lese **bool**.

```cpp
bool Aspose::Slides::Charts::DataLabelFormat::get_ShowValue() override
```

## Anmerkungen

Wenn das übergeordnete Element dieses [DataLabelFormat](../)-Objekts eine [DataLabelCollection](../../datalabelcollection/)-Sammlung von Datenbeschriftungen ist, dann bekommt diese Eigenschaft den Standardwert der ShowValue-Eigenschaft für die neuen Datenbeschriftungen in der [DataLabelCollection](../../datalabelcollection/)-Sammlung oder legt ihn fest. Das Setzen dieser Eigenschaft mit einem Wert setzt diesen Wert ebenfalls für die ShowValue-Eigenschaft aller Datenbeschriftungen in der [DataLabelCollection](../../datalabelcollection/)-Sammlung (d.h. "DataLabels.DefaultDataLabelFormat.ShowValue = val;" bewirkt, dass alle DataLabels[i].ShowValue gleich val sind).

## Siehe auch

* Klasse [DataLabelFormat](../)
* Namensraum [Aspose::Slides::Charts](../../)
* Bibliothek [Aspose.Slides](../../../)