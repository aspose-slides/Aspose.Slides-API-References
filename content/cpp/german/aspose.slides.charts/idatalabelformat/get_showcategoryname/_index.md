---
title: get_ShowCategoryName()
second_title: Aspose.Slides für C++ API-Referenz
description: Stellt das Anzeigeverhalten des Kategorienamens von Datenbeschriftungen eines angegebenen Diagramms dar. True, um den Kategorienamen für die Datenbeschriftungen in einem Diagramm anzuzeigen. False, um ihn zu verbergen. Lesen bool.
type: docs
weight: 144
url: /de/aspose.slides.charts/idatalabelformat/get_showcategoryname/
---
## IDataLabelFormat::get_ShowCategoryName() Methode

Stellt das Anzeigeverhalten des Kategorienamens von Datenbeschriftungen eines angegebenen Diagramms dar. True, um den Kategorienamen für die Datenbeschriftungen in einem Diagramm anzuzeigen. False, um ihn zu verbergen. Lesen **bool**.

```cpp
virtual bool Aspose::Slides::Charts::IDataLabelFormat::get_ShowCategoryName()=0
```

## Anmerkungen

Wenn das übergeordnete Element dieses [DataLabelFormat](../../datalabelformat/)-Objekts eine [DataLabelCollection](../../datalabelcollection/)-Sammlung von Datenbeschriftungen ist, dann gibt diese Eigenschaft den Standardwert der ShowCategoryName-Eigenschaft für die neuen Datenbeschriftungen in der [DataLabelCollection](../../datalabelcollection/)-Sammlung zurück oder legt ihn fest. Das Setzen dieser Eigenschaft mit einem Wert legt diesen Wert auch für die ShowCategoryName-Eigenschaft aller Datenbeschriftungen in der [DataLabelCollection](../../datalabelcollection/)-Sammlung fest (d.h. "DataLabels.DefaultDataLabelFormat.ShowCategoryName = val;" bewirkt, dass für alle DataLabels[i].ShowCategoryName der Wert val gilt).

## Siehe auch

* Klasse [IDataLabelFormat](../)
* Namensraum [Aspose::Slides::Charts](../../)
* Bibliothek [Aspose.Slides](../../../)