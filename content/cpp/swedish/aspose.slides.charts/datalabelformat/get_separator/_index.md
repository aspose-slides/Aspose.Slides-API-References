---
title: get_Separator()
second_title: Aspose.Slides för C++ API-referens
description: "Anger eller returnerar en Variant som representerar avgränsaren som används för datamärkningarna i ett diagram. Läs System::String."
type: docs
weight: 326
url: /sv/aspose.slides.charts/datalabelformat/get_separator/
---
## DataLabelFormat::get_Separator() metod

Anger eller returnerar en Variant som representerar avgränsaren som används för datamärkningarna i ett diagram. Läs [System::String](../../../system/string/).

```cpp
System::String Aspose::Slides::Charts::DataLabelFormat::get_Separator() override
```

## Anmärkningar

Om föräldern till detta [DataLabelFormat](../)-objekt är en [DataLabelCollection](../../datalabelcollection/)-samling av datamärkningar, får den här egenskapen eller sätter standardvärdet för Separator-egenskapen för de nya datamärkningarna i [DataLabelCollection](../../datalabelcollection/)-samlingen. Att sätta denna egenskap med ett värde sätter också detta värde på Separator-egenskapen för alla datamärkningar i [DataLabelCollection](../../datalabelcollection/)-samlingen (t.ex. "DataLabels.DefaultDataLabelFormat.Separator = val;" vilket gör att alla DataLabels[i].Separator blir lika med val). 

## Se även

* Klass [String](../../../system/string/)
* Klass [DataLabelFormat](../)
* Namnrymd [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)