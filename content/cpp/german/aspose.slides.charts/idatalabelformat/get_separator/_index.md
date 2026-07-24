---
title: get_Separator()
second_title: Aspose.Slides für C++ API-Referenz
description: "Legt einen Variant fest oder gibt ihn zurück, der das Trennzeichen für die Datenbeschriftungen in einem Diagramm darstellt. Lesen Sie System::String."
type: docs
weight: 326
url: /de/aspose.slides.charts/idatalabelformat/get_separator/
---
## IDataLabelFormat::get_Separator() Methode

Legt einen Variant fest oder gibt ihn zurück, der das Trennzeichen für die Datenbeschriftungen in einem Diagramm darstellt. Lesen Sie [System::String](../../../system/string/).

```cpp
virtual System::String Aspose::Slides::Charts::IDataLabelFormat::get_Separator()=0
```

## Anmerkungen

Wenn der übergeordnete Einstieg dieses [DataLabelFormat](../../datalabelformat/)-Objekts eine [DataLabelCollection](../../datalabelcollection/)-Sammlung von Datenbeschriftungen ist, dann ruft diese Eigenschaft den Standardwert der Separator-Eigenschaft für die neuen Datenbeschriftungen in der [DataLabelCollection](../../datalabelcollection/)-Sammlung ab oder legt ihn fest. Das Setzen dieser Eigenschaft mit einem Wert legt diesen Wert ebenfalls für die Separator-Eigenschaft aller Datenbeschriftungen in der [DataLabelCollection](../../datalabelcollection/)-Sammlung fest (z. B. "DataLabels.DefaultDataLabelFormat.Separator = val;" bewirkt, dass für alle DataLabels[i].Separator der Wert val ist).

## Siehe auch

* Klasse [String](../../../system/string/)
* Klasse [IDataLabelFormat](../)
* Namensraum [Aspose::Slides::Charts](../../)
* Bibliothek [Aspose.Slides](../../../)