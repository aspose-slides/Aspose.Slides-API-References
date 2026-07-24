---
title: set_ShowLabelValueFromCell()
second_title: Aspose.Slides für C++ API-Referenz
description: Stellt das Anzeigeverhalten des Zellenwerts von Datenbeschriftungen eines bestimmten Diagramms dar. True zeigt den Zellenwert an. False blendet ihn aus. Schreiben bool.
type: docs
weight: 313
url: /de/aspose.slides.charts/idatalabelformat/set_showlabelvaluefromcell/
---
## IDataLabelFormat::set_ShowLabelValueFromCell(bool) Methode


Stellt das Anzeigeverhalten des Zellenwerts von Datenbeschriftungen eines bestimmten Diagramms dar. True zeigt den Zellenwert an. False blendet ihn aus. Schreiben **bool**.

```cpp
virtual void Aspose::Slides::Charts::IDataLabelFormat::set_ShowLabelValueFromCell(bool value)=0
```

## Hinweise


Wenn der Elternelement dieser [DataLabelFormat](../../datalabelformat/)-Objekts eine [DataLabelCollection](../../datalabelcollection/)-Sammlung von Datenbeschriftungen ist, dann ruft diese Eigenschaft den Standardwert der ShowLabelValueFromCell-Eigenschaft für die neuen Datenbeschriftungen in der [DataLabelCollection](../../datalabelcollection/)-Sammlung ab oder legt ihn fest. Das Setzen dieser Eigenschaft mit einem Wert legt diesen Wert auch für die ShowLabelValueFromCell-Eigenschaft aller Datenbeschriftungen in der [DataLabelCollection](../../datalabelcollection/)-Sammlung fest (z. B. "DataLabels.DefaultDataLabelFormat.ShowLabelValueFromCell = val;" bewirkt, dass alle DataLabels[i].ShowLabelValueFromCell den Wert val haben).

## Siehe Auch

* Klasse [IDataLabelFormat](../)
* Namensraum [Aspose::Slides::Charts](../../)
* Bibliothek [Aspose.Slides](../../../)