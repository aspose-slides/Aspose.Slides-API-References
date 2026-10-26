---
title: set_Separator()
second_title: Aspose.Slides für C++ API-Referenz
description: "Setzt oder gibt ein Variant zurück, das das Trennzeichen für die Datenbeschriftungen in einem Diagramm darstellt. Schreiben Sie System::String."
type: docs
weight: 339
url: /de/aspose.slides.charts/idatalabelformat/set_separator/
---
## IDataLabelFormat::set_Separator(System::String) Methode

Setzt oder gibt ein Variant zurück, das das Trennzeichen für die Datenbeschriftungen in einem Diagramm darstellt. Schreiben Sie [System::String](../../../system/string/).

```cpp
virtual void Aspose::Slides::Charts::IDataLabelFormat::set_Separator(System::String value)=0
```

## Anmerkungen

Wenn das übergeordnete Element dieses [DataLabelFormat](../../datalabelformat/)-Objekts eine [DataLabelCollection](../../datalabelcollection/)-Auflistung von Datenbeschriftungen ist, dann ruft diese Eigenschaft den Standardwert der Separator-Eigenschaft für die neuen Datenbeschriftungen in der [DataLabelCollection](../../datalabelcollection/)-Auflistung ab oder setzt ihn. Das Setzen dieser Eigenschaft mit einem Wert setzt diesen Wert außerdem für die Separator-Eigenschaft aller Datenbeschriftungen in der [DataLabelCollection](../../datalabelcollection/)-Auflistung (z. B. "DataLabels.DefaultDataLabelFormat.Separator = val;" bewirkt, dass alle DataLabels[i].Separator gleich val sind).

## Siehe auch

* Klasse [String](../../../system/string/)
* Klasse [IDataLabelFormat](../)
* Namensraum [Aspose::Slides::Charts](../../)
* Bibliothek [Aspose.Slides](../../../)