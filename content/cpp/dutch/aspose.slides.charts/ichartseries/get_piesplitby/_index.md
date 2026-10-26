---
title: get_PieSplitBy()
second_title: Aspose.Slides voor C++ API-referentie
description: Specificeert hoe te bepalen welke gegevenspunten zich in de tweede taart of balk bevinden op een taart-in-taart- of balk-in-taart-diagram. Dit is de eigenschap niet alleen van deze serie maar van alle series van de bovenliggende seriesgroep - dit is een projectie van de overeenkomstige groeps-eigenschap. En dus is deze eigenschap alleen-lezen. Gebruik de ParentSeriesGroup-eigenschap voor toegang tot de bovenliggende seriesgroep. Gebruik get_ParentSeriesGroup()->get(set)_PieSplitBy() lees/schrijf-eigenschap om de waarde te wijzigen. Alleen-lezen PieSplitType.
type: docs
weight: 729
url: /nl/aspose.slides.charts/ichartseries/get_piesplitby/
---
## IChartSeries::get_PieSplitBy() method

Bepaalt hoe te bepalen welke gegevenspunten zich in de tweede taart of balk bevinden op een taart-in-taart- of balk-in-taart-diagram. Dit is de eigenschap niet alleen van deze serie maar van alle series van de bovenliggende seriesgroep – dit is een projectie van de overeenkomstige groeps-eigenschap. En dus is deze eigenschap alleen-lezen. Gebruik de ParentSeriesGroup-eigenschap voor toegang tot de bovenliggende seriesgroep. Gebruik [get_ParentSeriesGroup()](../get_parentseriesgroup/)->get(set)_PieSplitBy() lezen/schrijven-eigenschap om de waarde te wijzigen. Alleen-lezen [PieSplitType](../../piesplittype/).

```cpp
virtual PieSplitType Aspose::Slides::Charts::IChartSeries::get_PieSplitBy()=0
```

## Opmerkingen

1) Dit is de projectie van de eigenschap [get_ParentSeriesGroup()](../get_parentseriesgroup/)->get(set)_PieSplitBy(). 2) Als de eigenschapswaarde [PieSplitType::Custom](../../piesplittype/) is, kun je aangepaste splitsingsinformatie definiëren met de eigenschap [get_ParentSeriesGroup()](../get_parentseriesgroup/)->[get_PieSplitCustomPoints()](../get_piesplitcustompoints/).

## Zie ook

* Enum [PieSplitType](../../piesplittype/)
* Klasse [IChartSeries](../)
* Naamruimte [Aspose::Slides::Charts](../../)
* Bibliotheek [Aspose.Slides](../../../)