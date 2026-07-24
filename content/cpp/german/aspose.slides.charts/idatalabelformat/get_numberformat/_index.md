---
title: get_NumberFormat()
second_title: Aspose.Slides für C++ API-Referenz
description: "Stellt die Formatzeichenfolge für das DataLabels-Objekt dar. Lesen Sie System::String."
type: docs
weight: 27
url: /de/aspose.slides.charts/idatalabelformat/get_numberformat/
---
## IDataLabelFormat::get_NumberFormat() Methode


Stellt die Formatzeichenfolge für das DataLabels-Objekt dar. Lesen Sie [System::String](../../../system/string/).

```cpp
virtual System::String Aspose::Slides::Charts::IDataLabelFormat::get_NumberFormat()=0
```

## Bemerkungen



```cpp
auto defaultDataLabelFormat = series->get_Labels()->get_DefaultDataLabelFormat();
defaultDataLabelFormat->set_ShowValue(true);
defaultDataLabelFormat->set_IsNumberFormatLinkedToSource(false);
defaultDataLabelFormat->set_NumberFormat(u"0.0%");
```





Wenn der übergeordnete [DataLabelFormat](../../datalabelformat/) dieses Objekts eine [DataLabelCollection](../../datalabelcollection/)-Sammlung von Datenbeschriftungen ist, dann ruft diese Eigenschaft den Standardwert der NumberFormat-Eigenschaft für die neuen Datenbeschriftungen in der [DataLabelCollection](../../datalabelcollection/)-Sammlung ab oder legt ihn fest. Wenn diese Eigenschaft mit einem Wert gesetzt wird, wird dieser Wert ebenfalls für die NumberFormat-Eigenschaft aller Datenbeschriftungen in der [DataLabelCollection](../../datalabelcollection/)-Sammlung gesetzt (z. B. "DataLabels.DefaultDataLabelFormat.NumberFormat = val;" bewirkt, dass alle DataLabels[i].NumberFormat den Wert val haben). 
## Siehe Auch

* Class [String](../../../system/string/)
* Class [IDataLabelFormat](../)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)