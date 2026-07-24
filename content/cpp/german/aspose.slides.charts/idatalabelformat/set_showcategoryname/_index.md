---
title: set_ShowCategoryName()
second_title: Aspose.Slides für C++ API-Referenz
description: Stellt das Anzeigeverhalten des Kategorienamens der Datenbeschriftung eines angegebenen Diagramms dar. True, um den Kategorienamen für die Datenbeschriftungen in einem Diagramm anzuzeigen. False, um ihn zu verbergen. Schreiben bool.
type: docs
weight: 157
url: /de/aspose.slides.charts/idatalabelformat/set_showcategoryname/
---
## IDataLabelFormat::set_ShowCategoryName(bool) Methode

Stellt das Anzeigeverhalten des Kategorienamens der Datenbeschriftung eines angegebenen Diagramms dar. True, um den Kategorienamen für die Datenbeschriftungen in einem Diagramm anzuzeigen. False, um ihn zu verbergen. Schreiben **bool**.

```cpp
virtual void Aspose::Slides::Charts::IDataLabelFormat::set_ShowCategoryName(bool value)=0
```

## Bemerkungen

Wenn der übergeordnete Container dieses [DataLabelFormat](../../datalabelformat/)-Objekts eine [DataLabelCollection](../../datalabelcollection/)-Sammlung von Datenbeschriftungen ist, ruft diese Eigenschaft den Standardwert der ShowCategoryName-Eigenschaft für die neuen Datenbeschriftungen in der [DataLabelCollection](../../datalabelcollection/)-Sammlung ab oder legt ihn fest. Das Setzen dieser Eigenschaft mit einem Wert legt diesen Wert auch für die ShowCategoryName-Eigenschaft aller Datenbeschriftungen in der [DataLabelCollection](../../datalabelcollection/)-Sammlung fest (d. h. "DataLabels.DefaultDataLabelFormat.ShowCategoryName = val;" bewirkt, dass alle DataLabels[i].ShowCategoryName gleich val ist).

## Siehe auch

* Klasse [IDataLabelFormat](../)
* Namensraum [Aspose::Slides::Charts](../../)
* Bibliothek [Aspose.Slides](../../../)