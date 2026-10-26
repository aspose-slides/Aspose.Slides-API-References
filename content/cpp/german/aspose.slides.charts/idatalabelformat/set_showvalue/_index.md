---
title: set_ShowValue()
second_title: Aspose.Slides für C++ API Referenz
description: Stellt das Anzeigeverhalten des Prozentwerts einer angegebenen Diagrammdatenbeschriftung dar. True zeigt den Prozentwert an. False blendet ihn aus. Schreiben bool.
type: docs
weight: 131
url: /de/aspose.slides.charts/idatalabelformat/set_showvalue/
---
## IDataLabelFormat::set_ShowValue(bool) Methode

Stellt das Anzeigeverhalten des Prozentwerts eines angegebenen Diagramms für Datenbeschriftungen dar. True zeigt den Prozentwert an. False blendet ihn aus. Schreiben **bool**.

```cpp
virtual void Aspose::Slides::Charts::IDataLabelFormat::set_ShowValue(bool value)=0
```

## Bemerkungen

Wenn das übergeordnete Objekt dieses [DataLabelFormat](../../datalabelformat/) ein [DataLabelCollection](../../datalabelcollection/)-Sammlung von Datenbeschriftungen ist, dann legt diese Eigenschaft den Standardwert der ShowValue-Eigenschaft für die neuen Datenbeschriftungen in der [DataLabelCollection](../../datalabelcollection/)-Sammlung fest bzw. liest ihn aus. Das Setzen dieser Eigenschaft mit einem Wert legt diesen Wert ebenfalls für die ShowValue-Eigenschaft aller Datenbeschriftungen in der [DataLabelCollection](../../datalabelcollection/)-Sammlung fest (i.e. "DataLabels.DefaultDataLabelFormat.ShowValue = val;" bewirkt, dass alle DataLabels[i].ShowValue gleich val sind).

## Siehe auch

* Klasse [IDataLabelFormat](../)
* Namensraum [Aspose::Slides::Charts](../../)
* Bibliothek [Aspose.Slides](../../../)