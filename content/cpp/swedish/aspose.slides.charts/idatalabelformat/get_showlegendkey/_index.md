---
title: get_ShowLegendKey()
second_title: Aspose.Slides för C++ API-referens
description: Representerar ett specificerat diagrammets datamärkes förklaringsnyckelvisningsbeteende. True om förklaringsnyckeln för datamärket är synlig. Läs bool.
type: docs
weight: 92
url: /sv/aspose.slides.charts/idatalabelformat/get_showlegendkey/
---
## IDataLabelFormat::get_ShowLegendKey() metod

Representerar ett specificerat diagrammets datamärkes förklaringsnyckels visningsbeteende. True om förklaringsnyckeln för datamärket är synlig. Läs **bool**.

```cpp
virtual bool Aspose::Slides::Charts::IDataLabelFormat::get_ShowLegendKey()=0
```

## Anmärkningar

Om föräldern till detta [DataLabelFormat](../../datalabelformat/)-objekt är en [DataLabelCollection](../../datalabelcollection/)-samling av datamärken så får eller sätter denna egenskap standardvärdet för egenskapen ShowLegendKey för de nya datamärkena i [DataLabelCollection](../../datalabelcollection/)-samlingen. Att sätta denna egenskap med ett värde sätter också detta värde på ShowLegendKey-egenskapen för alla datamärken i [DataLabelCollection](../../datalabelcollection/)-samlingen (dvs. "DataLabels.DefaultDataLabelFormat.ShowLegendKey = val;" vilket gör att alla DataLabels[i].ShowLegendKey är lika med val).

## Se även

* Klass [IDataLabelFormat](../)
* Namnrymd [Aspose::Slides::Charts](../../)
* Bibliotek [Aspose.Slides](../../../)