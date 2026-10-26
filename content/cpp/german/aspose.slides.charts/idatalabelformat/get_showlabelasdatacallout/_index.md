---
title: get_ShowLabelAsDataCallout()
second_title: Aspose.Slides für C++ API-Referenz
description: Bestimmt, ob die Datenbeschriftung des angegebenen Diagramms als Daten-Callout oder als Datenbeschriftung angezeigt wird.
type: docs
weight: 274
url: /de/aspose.slides.charts/idatalabelformat/get_showlabelasdatacallout/
---
## IDataLabelFormat::get_ShowLabelAsDataCallout() Methode

Bestimmt, ob die Datenbeschriftung des angegebenen Diagramms als Daten-Callout oder als Datenbeschriftung angezeigt wird.

```cpp
virtual bool Aspose::Slides::Charts::IDataLabelFormat::get_ShowLabelAsDataCallout()=0
```

## Anmerkungen

Wenn der übergeordnete [DataLabelFormat](../../datalabelformat/)-Objekt ein [DataLabelCollection](../../datalabelcollection/)-Sammlung von Datenbeschriftungen ist, dann ruft diese Eigenschaft den Standardwert der ShowLabelAsDataCallout-Eigenschaft für die neuen Datenbeschriftungen in der [DataLabelCollection](../../datalabelcollection/)-Sammlung ab oder setzt ihn. Das Setzen dieser Eigenschaft mit einem Wert setzt diesen Wert auch für die ShowLabelAsDataCallout-Eigenschaft aller Datenbeschriftungen in der [DataLabelCollection](../../datalabelcollection/)-Sammlung (z. B. \"DataLabels.DefaultDataLabelFormat.ShowLabelAsDataCallout = val;\" bewirkt, dass alle DataLabels[i].ShowLabelAsDataCallout gleich val ist).

## Siehe auch

* Klasse [IDataLabelFormat](../)
* Namensraum [Aspose::Slides::Charts](../../)
* Bibliothek [Aspose.Slides](../../../)