---
title: get_Overlap()
second_title: Aspose.Slides voor C++ API-referentie
description: Specificeert hoeveel balken en kolommen overlappen op 2-D-grafieken, als een percentage (van -100% tot 100%). Dit is de eigenschap niet alleen van deze reeks maar van alle reeksen van de bovenliggende reeksgroep. Het is een projectie van de overeenkomstige eigenschap in de bovenliggende reeksgroep, en daarom is deze eigenschap alleen-lezen. Om de waarde te wijzigen, gebruik de get_ParentSeriesGroup()->Overlap() lees/schrijf eigenschap. Alleen-lezen int8_t.
type: docs
weight: 690
url: /nl/aspose.slides.charts/chartseries/get_overlap/
---
## ChartSeries::get_Overlap() methode


Geeft aan hoeveel balken en kolommen overlappen op 2-D-grafieken, als een percentage (van -100% tot 100%). Dit is de eigenschap niet alleen van deze reeks maar van alle reeksen van de bovenliggende reeksgroep. Het is een projectie van de overeenkomstige eigenschap in de bovenliggende reeksgroep, en daarom is deze eigenschap alleen-lezen. Om de waarde te wijzigen, gebruik de [get_ParentSeriesGroup()->Overlap()](../get_parentseriesgroup/) lezen/schrijven eigenschap. Alleen-lezen **int8_t**.

```cpp
int8_t Aspose::Slides::Charts::ChartSeries::get_Overlap() override
```

## Opmerkingen


Overlap specificeert de mate van overlapping of afstand tussen balken en kolommen als een percentage van hun breedte:* -100%: Maximale afstand (balken zijn volledig gescheiden).
* 0%: Balken staan naast elkaar zonder overlapping of afstand.
* 100%: Maximale overlapping (balken overlappen elkaar volledig). Dit is een projectie van de eigenschap [get_ParentSeriesGroup()->Overlap()](../get_parentseriesgroup/).


## Zie ook

* Klasse [ChartSeries](../)
* Naamruimte [Aspose::Slides::Charts](../../)
* Bibliotheek [Aspose.Slides](../../../)