---
title: get_PieSplitBy()
second_title: Aspose.Slides voor C++ API-referentie
description: Specificeert hoe te bepalen welke gegevenspunten zich in de tweede taart of balk bevinden op een taart-in-taart- of balk-in-taart-diagram. Dit is de eigenschap niet alleen van deze serie, maar van alle series van de bovenliggende seriesgroep – dit is een projectie van de juiste groepeigenschap. En dus is deze eigenschap read-only. Gebruik de ParentSeriesGroup eigenschap voor toegang tot de bovenliggende seriesgroep. Gebruik get_ParentSeriesGroup()->get(set)_PieSplitBy() read/write eigenschap om de waarde te wijzigen. Read-only PieSplitType.
type: docs
weight: 755
url: /nl/aspose.slides.charts/chartseries/get_piesplitby/
---
## ChartSeries::get_PieSplitBy() methode

Specificeert hoe te bepalen welke gegevenspunten zich in de tweede taart of balk bevinden op een taart-in-taart of balk-in-taart diagram. Dit is de eigenschap niet alleen van deze serie, maar van alle series van de bovenliggende seriesgroep - dit is een projectie van de juiste groepeigenschap. En dus is deze eigenschap read-only. Gebruik de ParentSeriesGroup eigenschap voor toegang tot de bovenliggende seriesgroep. Gebruik [get_ParentSeriesGroup()](../get_parentseriesgroup/)->get(set)_PieSplitBy() read/write eigenschap om de waarde te wijzigen. Read-only [PieSplitType](../../piesplittype/).

```cpp
PieSplitType Aspose::Slides::Charts::ChartSeries::get_PieSplitBy() override
```

## Opmerkingen

1) Dit is de projectie van de eigenschap [get_ParentSeriesGroup()](../get_parentseriesgroup/)->get(set)_PieSplitBy(). 2) Als de eigenschapswaarde [PieSplitType::Custom](../../piesplittype/) is, kunt u aangepaste split-informatie definiëren met de [get_ParentSeriesGroup()](../get_parentseriesgroup/)->[get_PieSplitCustomPoints()](../get_piesplitcustompoints/) eigenschap.

## Zie ook

* Enum [PieSplitType](../../piesplittype/)
* Klasse [ChartSeries](../)
* Naamruimte [Aspose::Slides::Charts](../../)
* Bibliotheek [Aspose.Slides](../../../)