---
title: get_ShowSeriesName()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt ein Boolean zurück, um das Anzeigeverhalten des Seriennamens für die Datenbeschriftungen in einem Diagramm anzugeben. True, um den Seriennamen anzuzeigen. False, um zu verbergen. Lesen bool.
type: docs
weight: 170
url: /de/aspose.slides.charts/idatalabelformat/get_showseriesname/
---
## IDataLabelFormat::get_ShowSeriesName() Methode


Gibt ein Boolean zurück, um das Anzeigeverhalten des Seriennamens für die Datenbeschriftungen in einem Diagramm anzugeben. True, um den Seriennamen anzuzeigen. False, um zu verbergen. Lesen **bool**.

```cpp
virtual bool Aspose::Slides::Charts::IDataLabelFormat::get_ShowSeriesName()=0
```

## Bemerkungen


Wenn das übergeordnete [DataLabelFormat](../../datalabelformat/)-Objekt ein [DataLabelCollection](../../datalabelcollection/)-Sammlung von Datenbeschriftungen ist, dann ruft diese Eigenschaft den Standardwert der ShowSeriesName-Eigenschaft für die neuen Datenbeschriftungen in der [DataLabelCollection](../../datalabelcollection/)-Sammlung ab oder legt ihn fest. Das Setzen dieser Eigenschaft mit einem Wert legt diesen Wert außerdem für die ShowSeriesName-Eigenschaft aller Datenbeschriftungen in der [DataLabelCollection](../../datalabelcollection/)-Sammlung fest (z. B. \"DataLabels.DefaultDataLabelFormat.ShowSeriesName = val;\" bewirkt, dass für alle DataLabels[i].ShowSeriesName der Wert val gilt). 


## Siehe auch

* Klasse [IDataLabelFormat](../)
* Namensraum [Aspose::Slides::Charts](../../)
* Bibliothek [Aspose.Slides](../../../)