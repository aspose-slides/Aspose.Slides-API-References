---
title: get_ShowLeaderLines()
second_title: Aspose.Slides für C++ API-Referenz
description: Stellt das Anzeigeverhalten der Leitlinien von Datenbeschriftungen eines angegebenen Diagramms dar. True zeigt die Leitlinien an. False verbirgt sie. Lesen bool.
type: docs
weight: 248
url: /de/aspose.slides.charts/idatalabelformat/get_showleaderlines/
---
## IDataLabelFormat::get_ShowLeaderLines() Methode

Stellt das Anzeigeverhalten der Leitlinien von Datenbeschriftungen eines angegebenen Diagramms dar. True zeigt die Leitlinien an. False verbirgt sie. Lesen **bool**.

```cpp
virtual bool Aspose::Slides::Charts::IDataLabelFormat::get_ShowLeaderLines()=0
```

## Bemerkungen

Wenn der übergeordnete Teil dieses [DataLabelFormat](../../datalabelformat/)-Objekts eine [DataLabelCollection](../../datalabelcollection/)-Sammlung von Datenbeschriftungen ist, dann ruft diese Eigenschaft den Standardwert der ShowLeaderLines-Eigenschaft für die neuen Datenbeschriftungen in der [DataLabelCollection](../../datalabelcollection/)-Sammlung ab oder legt ihn fest. Das Setzen dieser Eigenschaft mit einem Wert legt diesen Wert auch für die ShowLeaderLines-Eigenschaft aller Datenbeschriftungen in der [DataLabelCollection](../../datalabelcollection/)-Sammlung fest (i.e. \"DataLabels.DefaultDataLabelFormat.ShowLeaderLines = val;\" bewirkt, dass alle DataLabels[i].ShowLeaderLines gleich val sind).

## Siehe auch

* Klasse [IDataLabelFormat](../)
* Namensraum [Aspose::Slides::Charts](../../)
* Bibliothek [Aspose.Slides](../../../)