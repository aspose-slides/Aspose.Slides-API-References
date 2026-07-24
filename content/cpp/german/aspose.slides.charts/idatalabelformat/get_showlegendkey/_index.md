---
title: get_ShowLegendKey()
second_title: Aspose.Slides für C++ API-Referenz
description: Stellt das Anzeigeverhalten des Legenden-Schlüssels einer angegebenen Diagrammdatennbeschriftung dar. True, wenn der Legenden-Schlüssel der Datenbeschriftung sichtbar ist. Lesen bool.
type: docs
weight: 92
url: /de/aspose.slides.charts/idatalabelformat/get_showlegendkey/
---
## IDataLabelFormat::get_ShowLegendKey() Methode


Stellt das Anzeigeverhalten des Legenden-Schlüssels eines angegebenen Diagramms für Datenbeschriftungen dar. True, wenn der Legenden-Schlüssel der Datenbeschriftung sichtbar ist. Lesen **bool**.

```cpp
virtual bool Aspose::Slides::Charts::IDataLabelFormat::get_ShowLegendKey()=0
```

## Hinweise


Wenn der übergeordnete [DataLabelFormat](../../datalabelformat/)-Objekt ein [DataLabelCollection](../../datalabelcollection/)-Sammlung von Datenbeschriftungen ist, dann ruft diese Eigenschaft den Standardwert der ShowLegendKey-Eigenschaft für die neuen Datenbeschriftungen in der [DataLabelCollection](../../datalabelcollection/)-Sammlung ab oder setzt ihn. Das Setzen dieser Eigenschaft mit einem Wert ändert diesen Wert auch für die ShowLegendKey-Eigenschaft aller Datenbeschriftungen in der [DataLabelCollection](../../datalabelcollection/)-Sammlung (z. B. "DataLabels.DefaultDataLabelFormat.ShowLegendKey = val;" bewirkt, dass für alle DataLabels[i].ShowLegendKey der Wert val gilt).  



## Siehe auch

* Klasse [IDataLabelFormat](../)
* Namensraum [Aspose::Slides::Charts](../../)
* Bibliothek [Aspose.Slides](../../../)