---
title: get_Separator()
second_title: Aspose.Slides för C++ API-referens
description: "Ställer in eller returnerar en Variant som representerar separatorn som används för dataetiketterna i ett diagram. Läs System::String."
type: docs
weight: 326
url: /sv/aspose.slides.charts/idatalabelformat/get_separator/
---
## IDataLabelFormat::get_Separator() metod

Ställer in eller returnerar en Variant som representerar Separator som används för dataetiketterna i ett diagram. Läs [System::String](../../../system/string/).

```cpp
virtual System::String Aspose::Slides::Charts::IDataLabelFormat::get_Separator()=0
```

## Anmärkningar

Om föräldern till detta [DataLabelFormat](../../datalabelformat/)-objekt är en [DataLabelCollection](../../datalabelcollection/)-samling av dataetiketter så får eller sätter denna egenskap standardvärdet för Separator-egenskapen för de nya dataetiketterna i [DataLabelCollection](../../datalabelcollection/)-samlingen. Att sätta denna egenskap med ett värde sätter också detta värde till Separator-egenskapen för alla dataetiketter i [DataLabelCollection](../../datalabelcollection/)-samlingen (dvs. \"DataLabels.DefaultDataLabelFormat.Separator = val;\" gör att alla DataLabels[i].Separator är lika med val).

## Se även

* Klass [String](../../../system/string/)
* Klass [IDataLabelFormat](../)
* Namnrymd [Aspose::Slides::Charts](../../)
* Bibliotek [Aspose.Slides](../../../)