---
title: get_Overlap()
second_title: Aspose.Slides voor C++ API-referentie
description: Specificeert hoeveel balken en kolommen overlappen op 2-D-diagrammen, als een percentage (van -100% tot 100%). Dit is de eigenschap niet alleen van deze serie, maar van alle series van de bovenliggende seriegroep. Het is een projectie van de overeenkomstige eigenschap in de bovenliggende seriegroep, en daarom is deze eigenschap alleen-lezen. Om de waarde te wijzigen, gebruik de get_ParentSeriesGroup()->get(set)_Overlap() lezen/schrijven eigenschap. Alleen-lezen int8_t.
type: docs
weight: 690
url: /nl/aspose.slides.charts/ichartseries/get_overlap/
---
## IChartSeries::get_Overlap() methode


Specificeert hoeveel balken en kolommen overlappen op 2-D-diagrammen, als een percentage (van -100% tot 100%). Dit is de eigenschap niet alleen van deze serie, maar van alle series van de bovenliggende seriegroep. Het is een projectie van de overeenkomstige eigenschap in de bovenliggende seriegroep, en dus is deze eigenschap alleen-lezen. Om de waarde te wijzigen, gebruik de [get_ParentSeriesGroup()](../get_parentseriesgroup/)->get(set)_Overlap() lezen/schrijven eigenschap. Alleen-lezen **int8_t**.

```cpp
virtual int8_t Aspose::Slides::Charts::IChartSeries::get_Overlap()=0
```

## Opmerkingen


Overlap specificeert de mate van overlap of afstand tussen balken en kolommen als een percentage van hun breedte:* -100%: Maximale afstand (balken zijn volledig gescheiden). * 0%: Balken staan naast elkaar zonder overlap of afstand. * 100%: Maximale overlap (balken overlappen elkaar volledig). Dit is een projectie van de eigenschap [get_ParentSeriesGroup()](../get_parentseriesgroup/)->get(set)_Overlap().


## Zie ook

* Klasse [IChartSeries](../)
* Naamruimte [Aspose::Slides::Charts](../../)
* Bibliotheek [Aspose.Slides](../../../)