---
title: set_ShowBubbleSize()
second_title: Aspose.Slides für C++ API-Referenz
description: Stellt das Anzeigeverhalten des Bubble-Größenwerts einer angegebenen Diagrammdatenbeschriftung dar. True zeigt den Bubble-Größenwert an. False blendet ihn aus. Schreiben bool.
type: docs
weight: 235
url: /de/aspose.slides.charts/idatalabelformat/set_showbubblesize/
---
## IDataLabelFormat::set_ShowBubbleSize(bool) Methode


Stellt das Anzeigeverhalten des Bubble-Größenwerts einer angegebenen Diagrammdatenbeschriftung dar. True zeigt den Bubble-Größenwert an. False blendet ihn aus. Schreiben **bool**.

```cpp
virtual void Aspose::Slides::Charts::IDataLabelFormat::set_ShowBubbleSize(bool value)=0
```

## Hinweise


Wenn der übergeordnete Teil dieses [DataLabelFormat](../../datalabelformat/)-Objekts eine [DataLabelCollection](../../datalabelcollection/)-Sammlung von Datenbeschriftungen ist, dann ruft diese Eigenschaft den Standardwert der ShowBubbleSize-Eigenschaft für die neuen Datenbeschriftungen in der [DataLabelCollection](../../datalabelcollection/)-Sammlung ab oder legt ihn fest. Das Setzen dieser Eigenschaft mit einem Wert legt diesen Wert auch für die ShowBubbleSize-Eigenschaft aller Datenbeschriftungen in der [DataLabelCollection](../../datalabelcollection/)-Sammlung fest (i.e. \"DataLabels.DefaultDataLabelFormat.ShowBubbleSize = val;\" bewirkt, dass alle DataLabels[i].ShowBubbleSize den Wert val haben).

## Siehe auch

* Klasse [IDataLabelFormat](../)
* Namensraum [Aspose::Slides::Charts](../../)
* Bibliothek [Aspose.Slides](../../../)