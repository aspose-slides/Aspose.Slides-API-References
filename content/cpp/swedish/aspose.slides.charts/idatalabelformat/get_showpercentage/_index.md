---
title: get_ShowPercentage()
second_title: Aspose.Slides för C++ API-referens
description: Representerar ett specificerat diagrammets datamärkningsprocentvärdes visningsbeteende. True visar procentvärdet. False döljer det. Läs bool.
type: docs
weight: 196
url: /sv/aspose.slides.charts/idatalabelformat/get_showpercentage/
---
## IDataLabelFormat::get_ShowPercentage() metod

Representerar ett specificerat diagrammets datamärkningsprocentvärdes visningsbeteende. True visar procentvärdet. False döljer det. Läs **bool**.

```cpp
virtual bool Aspose::Slides::Charts::IDataLabelFormat::get_ShowPercentage()=0
```

## Anmärkningar

Om föräldern till detta [DataLabelFormat](../../datalabelformat/)-objekt är en [DataLabelCollection](../../datalabelcollection/)-samling av datamärkningar så får denna egenskap eller sätter standardvärdet för ShowPercentage-egenskapen för de nya datamärkningarna i [DataLabelCollection](../../datalabelcollection/)-samlingen. Att sätta denna egenskap med ett värde sätter också detta värde till ShowPercentage-egenskapen för alla datamärkningar i [DataLabelCollection](../../datalabelcollection/)-samlingen (dvs. "DataLabels.DefaultDataLabelFormat.ShowPercentage = val;" vilket gör att alla DataLabels[i].ShowPercentage är lika med val).

## Se även

* Klass [IDataLabelFormat](../)
* Namnrymd [Aspose::Slides::Charts](../../)
* Bibliotek [Aspose.Slides](../../../)