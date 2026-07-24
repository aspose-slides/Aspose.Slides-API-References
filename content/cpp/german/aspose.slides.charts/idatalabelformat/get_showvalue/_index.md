---
title: get_ShowValue()
second_title: Aspose.Slides für C++ API-Referenz
description: Stellt das Anzeigeverhalten des prozentualen Datenbeschriftungswerts eines angegebenen Diagramms dar. True zeigt den Prozentwert an. False versteckt ihn. Lesen bool.
type: docs
weight: 118
url: /de/aspose.slides.charts/idatalabelformat/get_showvalue/
---
## IDataLabelFormat::get_ShowValue() Methode

Stellt das Anzeigeverhalten des prozentualen Datenbeschriftungswerts eines angegebenen Diagramms dar. True zeigt den Prozentwert an. False versteckt ihn. Lesen **bool**.

```cpp
virtual bool Aspose::Slides::Charts::IDataLabelFormat::get_ShowValue()=0
```

## Anmerkungen

Wenn das Elternelement dieses [DataLabelFormat](../../datalabelformat/) Objekts eine [DataLabelCollection](../../datalabelcollection/) Sammlung von Datenbeschriftungen ist, dann ruft diese Eigenschaft den Standardwert der ShowValue-Eigenschaft für die neuen Datenbeschriftungen in der [DataLabelCollection](../../datalabelcollection/) Sammlung ab oder setzt ihn. Das Setzen dieser Eigenschaft mit einem Wert legt diesen Wert auch für die ShowValue-Eigenschaft aller Datenbeschriftungen in der [DataLabelCollection](../../datalabelcollection/) Sammlung fest (z. B. "DataLabels.DefaultDataLabelFormat.ShowValue = val;" bewirkt, dass alle DataLabels[i].ShowValue den Wert val haben).

## Siehe auch

* Klasse [IDataLabelFormat](../)
* Namensraum [Aspose::Slides::Charts](../../)
* Bibliothek [Aspose.Slides](../../../)