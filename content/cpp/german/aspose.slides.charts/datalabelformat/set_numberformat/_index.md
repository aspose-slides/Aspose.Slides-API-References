---
title: set_NumberFormat()
second_title: Aspose.Slides für C++ API-Referenz
description: "Stellt die Formatzeichenfolge für das DataLabels-Objekt dar. Schreiben Sie System::String."
type: docs
weight: 40
url: /de/aspose.slides.charts/datalabelformat/set_numberformat/
---
## DataLabelFormat::set_NumberFormat(System::String) Methode


Stellt die Formatzeichenfolge für das DataLabels-Objekt dar. Schreiben Sie [System::String](../../../system/string/).

```cpp
void Aspose::Slides::Charts::DataLabelFormat::set_NumberFormat(System::String value) override
```

## Anmerkungen



```cpp
auto defaultDataLabelFormat = series->get_Labels()->get_DefaultDataLabelFormat();
defaultDataLabelFormat->set_ShowValue(true);
defaultDataLabelFormat->set_IsNumberFormatLinkedToSource(false);
defaultDataLabelFormat->set_NumberFormat(u"0.0%");
```


Wenn der übergeordnete [DataLabelFormat](../)-Objekt ein [DataLabelCollection](../../datalabelcollection/)-Datensatz von Datenbeschriftungen ist, dann ruft diese Eigenschaft den Standardwert der NumberFormat-Eigenschaft für die neuen Datenbeschriftungen in der [DataLabelCollection](../../datalabelcollection/)-Sammlung ab oder legt ihn fest. Wird diese Eigenschaft mit einem Wert festgelegt, wird dieser Wert auch für die NumberFormat-Eigenschaft aller Datenbeschriftungen in der [DataLabelCollection](../../datalabelcollection/)-Sammlung gesetzt (d. h. "DataLabels.DefaultDataLabelFormat.NumberFormat = val;" bewirkt, dass alle DataLabels[i].NumberFormat den Wert val haben).

## Siehe auch

* Klasse [String](../../../system/string/)
* Klasse [DataLabelFormat](../)
* Namensraum [Aspose::Slides::Charts](../../)
* Bibliothek [Aspose.Slides](../../../)