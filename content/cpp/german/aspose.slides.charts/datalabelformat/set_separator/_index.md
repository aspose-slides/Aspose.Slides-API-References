---
title: set_Separator()
second_title: Aspose.Slides für C++ API-Referenz
description: "Setzt oder gibt ein Variant zurück, das das Trennzeichen für die Datenbeschriftungen in einem Diagramm darstellt. Schreiben Sie System::String."
type: docs
weight: 339
url: /de/aspose.slides.charts/datalabelformat/set_separator/
---
## DataLabelFormat::set_Separator(System::String) Methode

Setzt oder gibt ein Variant zurück, das das Trennzeichen repräsentiert, das für die Datenbeschriftungen in einem Diagramm verwendet wird. Schreiben Sie [System::String](../../../system/string/).

```cpp
void Aspose::Slides::Charts::DataLabelFormat::set_Separator(System::String value) override
```

## Hinweise

Wenn das übergeordnete Element dieses [DataLabelFormat](../)-Objekts eine [DataLabelCollection](../../datalabelcollection/)-Sammlung von Datenbeschriftungen ist, dann ruft diese Eigenschaft den Standardwert der Separator-Eigenschaft für die neuen Datenbeschriftungen in der [DataLabelCollection](../../datalabelcollection/)-Sammlung ab oder legt ihn fest. Das Setzen dieser Eigenschaft mit einem Wert setzt diesen Wert ebenfalls für die Separator-Eigenschaft aller Datenbeschriftungen in der [DataLabelCollection](../../datalabelcollection/)-Sammlung (i.e. \"DataLabels.DefaultDataLabelFormat.Separator = val;\" cause to all DataLabels[i].Separator is equal to val).

## Siehe auch

* Klasse [String](../../../system/string/)
* Klasse [DataLabelFormat](../)
* Namensraum [Aspose::Slides::Charts](../../)
* Bibliothek [Aspose.Slides](../../../)