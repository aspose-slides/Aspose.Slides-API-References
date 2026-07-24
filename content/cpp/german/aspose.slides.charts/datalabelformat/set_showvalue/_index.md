---
title: set_ShowValue()
second_title: Aspose.Slides für C++ API-Referenz
description: Stellt das Anzeigeverhalten des prozentualen Datenbeschriftungswerts eines angegebenen Diagramms dar. True zeigt den Prozentwert an. False verbirgt ihn. Schreiben bool.
type: docs
weight: 131
url: /de/aspose.slides.charts/datalabelformat/set_showvalue/
---
## DataLabelFormat::set_ShowValue(bool) Methode


Stellt das Anzeigeverhalten des prozentualen Datenbeschriftungswerts eines angegebenen Diagramms dar. True zeigt den Prozentwert an. False verbirgt ihn. Schreiben **bool**.

```cpp
void Aspose::Slides::Charts::DataLabelFormat::set_ShowValue(bool value) override
```

## Anmerkungen


Wenn der übergeordnete [DataLabelFormat](../)-Objekt ein [DataLabelCollection](../../datalabelcollection/)-Sammlung von Datenbeschriftungen ist, dann ruft diese Eigenschaft den Standardwert der ShowValue-Eigenschaft für die neuen Datenbeschriftungen in der [DataLabelCollection](../../datalabelcollection/)-Sammlung ab oder legt ihn fest. Setzt man diese Eigenschaft mit einem Wert, wird dieser Wert auch für die ShowValue-Eigenschaft aller Datenbeschriftungen in der [DataLabelCollection](../../datalabelcollection/)-Sammlung gesetzt (z. B. "DataLabels.DefaultDataLabelFormat.ShowValue = val;" bewirkt, dass alle DataLabels[i].ShowValue gleich val sind).


## Siehe auch

* Klasse [DataLabelFormat](../)
* Namensraum [Aspose::Slides::Charts](../../)
* Bibliothek [Aspose.Slides](../../../)