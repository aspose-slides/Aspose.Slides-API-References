---
title: set_ShowLabelValueFromCell()
second_title: Aspose.Slides für C++ API Referenz
description: Stellt das Anzeigeverhalten des Zellenwerts einer bestimmten Diagrammdatenbeschriftung dar. True zeigt den Zellenwert an. False verbirgt ihn. Schreiben bool.
type: docs
weight: 287
url: /de/aspose.slides.charts/datalabelformat/set_showlabelvaluefromcell/
---
## DataLabelFormat::set_ShowLabelValueFromCell(bool) Methode


Stellt das Anzeigeverhalten des Datenbeschriftungszellenwerts eines bestimmten Diagramms dar. True zeigt den Zellenwert an. False verbirgt ihn. Schreiben **bool**.

```cpp
void Aspose::Slides::Charts::DataLabelFormat::set_ShowLabelValueFromCell(bool value) override
```

## Anmerkungen


Wenn das übergeordnete Element dieses [DataLabelFormat](../)-Objekts eine [DataLabelCollection](../../datalabelcollection/)-Auflistung von Datenbeschriftungen ist, dann gibt diese Eigenschaft den Standardwert der ShowLabelValueFromCell-Eigenschaft für die neuen Datenbeschriftungen in der [DataLabelCollection](../../datalabelcollection/)-Auflistung zurück oder setzt ihn. Das Setzen dieser Eigenschaft mit einem Wert setzt diesen Wert auch für die ShowLabelValueFromCell-Eigenschaft aller Datenbeschriftungen in der [DataLabelCollection](../../datalabelcollection/)-Auflistung (z. B. \"DataLabels.DefaultDataLabelFormat.ShowLabelValueFromCell = val;\" bewirkt, dass alle DataLabels[i].ShowLabelValueFromCell gleich val sind).

## Siehe auch

* Klasse [DataLabelFormat](../)
* Namensraum [Aspose::Slides::Charts](../../)
* Bibliothek [Aspose.Slides](../../../)