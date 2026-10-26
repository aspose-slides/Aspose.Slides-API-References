---
title: set_NumberFormat()
second_title: Aspose.Slides für C++ API-Referenz
description: "Stellt die Formatzeichenfolge für das DataLabels-Objekt dar. Schreiben Sie System::String."
type: docs
weight: 40
url: /de/aspose.slides.charts/idatalabelformat/set_numberformat/
---
## IDataLabelFormat::set_NumberFormat(System::String) Methode

Stellt die Formatzeichenfolge für das DataLabels-Objekt dar. Schreiben Sie [System::String](../../../system/string/).

```cpp
virtual void Aspose::Slides::Charts::IDataLabelFormat::set_NumberFormat(System::String value)=0
```

## Hinweise



```cpp
auto defaultDataLabelFormat = series->get_Labels()->get_DefaultDataLabelFormat();
defaultDataLabelFormat->set_ShowValue(true);
defaultDataLabelFormat->set_IsNumberFormatLinkedToSource(false);
defaultDataLabelFormat->set_NumberFormat(u"0.0%");
```





Wenn der übergeordnete [DataLabelFormat](../../datalabelformat/)-Objekt ein [DataLabelCollection](../../datalabelcollection/)-Sammlung von Datenbeschriftungen ist, dann gibt diese Eigenschaft den Standardwert der NumberFormat-Eigenschaft für die neuen Datenbeschriftungen in der [DataLabelCollection](../../datalabelcollection/)-Sammlung zurück oder setzt ihn. Wird diese Eigenschaft mit einem Wert gesetzt, wird dieser Wert auch für die NumberFormat-Eigenschaft aller Datenbeschriftungen in der [DataLabelCollection](../../datalabelcollection/)-Sammlung gesetzt (d. h. „DataLabels.DefaultDataLabelFormat.NumberFormat = val;“ bewirkt, dass alle DataLabels[i].NumberFormat den Wert val erhalten).

## Siehe auch

* Klasse [String](../../../system/string/)
* Klasse [IDataLabelFormat](../)
* Namensraum [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)