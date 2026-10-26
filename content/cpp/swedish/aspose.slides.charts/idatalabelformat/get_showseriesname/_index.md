---
title: get_ShowSeriesName()
second_title: Aspose.Slides för C++ API-referens
description: Returnerar en Boolean för att ange hur serienamnet visas för dataetiketterna i ett diagram. True för att visa serienamnet. False för att dölja. Läs bool.
type: docs
weight: 170
url: /sv/aspose.slides.charts/idatalabelformat/get_showseriesname/
---
## IDataLabelFormat::get_ShowSeriesName() metod

Returnerar en Boolean för att ange hur serienamnet visas för dataetiketterna i ett diagram. True för att visa serienamnet. False för att dölja. Läs **bool**.

```cpp
virtual bool Aspose::Slides::Charts::IDataLabelFormat::get_ShowSeriesName()=0
```

## Anmärkningar

Om föräldern till detta [DataLabelFormat](../../datalabelformat/)-objekt är en [DataLabelCollection](../../datalabelcollection/)-samling av dataetiketter så får denna egenskap eller sätter standardvärdet för ShowSeriesName-egenskapen för de nya dataetiketterna i [DataLabelCollection](../../datalabelcollection/)-samlingen. Att sätta denna egenskap med ett värde sätter också detta värde för ShowSeriesName-egenskapen för alla dataetiketter i [DataLabelCollection](../../datalabelcollection/)-samlingen (dvs. "DataLabels.DefaultDataLabelFormat.ShowSeriesName = val;" gör så att alla DataLabels[i].ShowSeriesName är lika med val). 


## Se även

* Klass [IDataLabelFormat](../)
* Namnutrymme [Aspose::Slides::Charts](../../)
* Bibliotek [Aspose.Slides](../../../)