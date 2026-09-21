---
title: pie_split_by property
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides.charts/chartseries/pie_split_by/
weight: 340
---
## pie_split_by eigenschap
Specificeert hoe te bepalen welke gegevenspunten zich in de tweede taart of balk bevinden op een pie-of-pie of bar-of-pie diagram.
Dit is de eigenschap niet alleen van deze reeks, maar van alle reeksen van de bovenliggende reeksgroep - dit is een projectie van de juiste groepseigenschap. En daarom is deze eigenschap alleen-lezen.
Gebruik de eigenschap ParentSeriesGroup voor toegang tot de bovenliggende reeksgroep.
Gebruik de eigenschap ParentSeriesGroup.PieSplitBy lees/schrijf om de waarde te wijzigen.
Alleen-lezen [`PieSplitType`](/slides/python-net/nl/aspose.slides.charts/piesplittype).

### Opmerkingen

1) Dit is de projectie van de eigenschap ParentSeriesGroup.PieSplitBy.
2) Als de eigenschapswaarde PieSplitType.Custom is, kun je aangepaste splitsingsinformatie definiëren met de eigenschap ParentSeriesGroup.PieSplitCustomPoints.

### Definitie:
```python
@property
def pie_split_by(self):
    ...
```

### Zie ook
* klasse [`ChartSeries`](/slides/python-net/nl/aspose.slides.charts/chartseries)
* enumeratie [`PieSplitType`](/slides/python-net/nl/aspose.slides.charts/piesplittype)
* module [`aspose.slides.charts`](/slides/python-net/nl/aspose.slides.charts)
* bibliotheek [`Aspose.Slides`](/slides/python-net)