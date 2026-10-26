---
title: get_NumberFormat()
second_title: Aspose.Slides für C++ API-Referenz
description: "Stellt die Formatzeichenfolge für das DataLabels-Objekt dar. Siehe System::String."
type: docs
weight: 27
url: /de/aspose.slides.charts/datalabelformat/get_numberformat/
---
## DataLabelFormat::get_NumberFormat() Methode

Stellt die Formatzeichenfolge für das DataLabels-Objekt dar. Siehe [System::String](../../../system/string/).

```cpp
System::String Aspose::Slides::Charts::DataLabelFormat::get_NumberFormat() override
```

## Anmerkungen

```cpp
auto defaultDataLabelFormat = series->get_Labels()->get_DefaultDataLabelFormat();
defaultDataLabelFormat->set_ShowValue(true);
defaultDataLabelFormat->set_IsNumberFormatLinkedToSource(false);
defaultDataLabelFormat->set_NumberFormat(u"0.0%");
```

Wenn das übergeordnete [DataLabelFormat](../)-Objekt eine [DataLabelCollection](../../datalabelcollection/)-Sammlung von Datenbeschriftungen ist, dann ruft diese Eigenschaft den Standardwert der NumberFormat-Eigenschaft für die neuen Datenbeschriftungen in der [DataLabelCollection](../../datalabelcollection/)-Sammlung ab oder legt ihn fest. Wird diese Eigenschaft mit einem Wert gesetzt, wird dieser Wert auch für die NumberFormat-Eigenschaft aller Datenbeschriftungen in der [DataLabelCollection](../../datalabelcollection/)-Sammlung festgelegt (d. h. "DataLabels.DefaultDataLabelFormat.NumberFormat = val;" bewirkt, dass alle DataLabels[i].NumberFormat den Wert val erhalten).

## Siehe auch

* Klasse [String](../../../system/string/)
* Klasse [DataLabelFormat](../)
* Namensraum [Aspose::Slides::Charts](../../)
* Bibliothek [Aspose.Slides](../../../)