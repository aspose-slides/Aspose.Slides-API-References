---
title: get_ShowLabelAsDataCallout()
second_title: Aspose.Slides für C++ API-Referenz
description: Bestimmt, ob die Datenbeschriftung des angegebenen Diagramms als Datencallout oder als Datenbeschriftung angezeigt wird.
type: docs
weight: 300
url: /de/aspose.slides.charts/datalabelformat/get_showlabelasdatacallout/
---
## DataLabelFormat::get_ShowLabelAsDataCallout() Methode

Bestimmt, ob das Datenbeschriftungsfeld des angegebenen Diagramms als Datencallout oder als Datenbeschriftung angezeigt wird.

```cpp
bool Aspose::Slides::Charts::DataLabelFormat::get_ShowLabelAsDataCallout() override
```

## Hinweise

Wenn das übergeordnete Element dieses [DataLabelFormat](../)-Objekts eine [DataLabelCollection](../../datalabelcollection/)-Sammlung von Datenbeschriftungen ist, dann ruft diese Eigenschaft den Standardwert der ShowLabelAsDataCallout-Eigenschaft für die neuen Datenbeschriftungen in der [DataLabelCollection](../../datalabelcollection/)-Sammlung ab oder legt ihn fest. Das Setzen dieser Eigenschaft mit einem Wert legt diesen Wert außerdem für die ShowLabelAsDataCallout-Eigenschaft aller Datenbeschriftungen in der [DataLabelCollection](../../datalabelcollection/)-Sammlung fest (i.e. "DataLabels.DefaultDataLabelFormat.ShowLabelAsDataCallout = val;" führt dazu, dass alle DataLabels[i].ShowLabelAsDataCallout den Wert val haben).

## Siehe auch

* Klasse [DataLabelFormat](../)
* Namensraum [Aspose::Slides::Charts](../../)
* Bibliothek [Aspose.Slides](../../../)