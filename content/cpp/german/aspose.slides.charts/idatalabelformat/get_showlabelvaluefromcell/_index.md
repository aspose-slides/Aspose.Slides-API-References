---
title: get_ShowLabelValueFromCell()
second_title: Aspose.Slides für C++ API-Referenz
description: Stellt das Anzeigeverhalten des Zellenwerts einer Datenbeschriftung eines angegebenen Diagramms dar. True zeigt den Zellenwert an. False verbirgt ihn. Lese bool.
type: docs
weight: 300
url: /de/aspose.slides.charts/idatalabelformat/get_showlabelvaluefromcell/
---
## IDataLabelFormat::get_ShowLabelValueFromCell() Methode


Stellt das Anzeigeverhalten des Zellenwerts einer Datenbeschriftung eines angegebenen Diagramms dar. True zeigt den Zellenwert an. False verbirgt ihn. Lesen **bool**.

```cpp
virtual bool Aspose::Slides::Charts::IDataLabelFormat::get_ShowLabelValueFromCell()=0
```

## Anmerkungen


Wenn das übergeordnete Element dieses [DataLabelFormat](../../datalabelformat/)-Objekts eine [DataLabelCollection](../../datalabelcollection/)-Sammlung von Datenbeschriftungen ist, dann holt oder setzt diese Eigenschaft den Standardwert der ShowLabelValueFromCell-Eigenschaft für die neuen Datenbeschriftungen in der [DataLabelCollection](../../datalabelcollection/)-Sammlung. Das Setzen dieser Eigenschaft mit einem Wert legt diesen Wert ebenfalls für die ShowLabelValueFromCell-Eigenschaft aller Datenbeschriftungen in der [DataLabelCollection](../../datalabelcollection/)-Sammlung fest (i.e. \"DataLabels.DefaultDataLabelFormat.ShowLabelValueFromCell = val;\" bewirkt, dass für alle DataLabels[i].ShowLabelValueFromCell der Wert val ist). 
## Siehe auch

* Klasse [IDataLabelFormat](../)
* Namensraum [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)