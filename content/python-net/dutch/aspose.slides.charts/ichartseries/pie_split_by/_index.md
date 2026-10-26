---
title: pie_split_by property
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides.charts/ichartseries/pie_split_by/
weight: 340
---
## pie_split_by eigenschap
Specificeert hoe te bepalen welke gegevenspunten zich in de tweede taart of balk bevinden op een pie-of-pie of bar-of-pie diagram.
Dit is de eigenschap niet alleen van deze serie, maar van alle series van de bovenliggende serie-groep – dit is een projectie van de overeenkomstige groeps-eigenschap. En dus is deze eigenschap alleen-lees.
Gebruik de eigenschap ParentSeriesGroup voor toegang tot de bovenliggende serie-groep.
Gebruik de eigenschap ParentSeriesGroup.PieSplitBy lezen/schrijven om de waarde te wijzigen.
Alleen-lees [`PieSplitType`](/slides/python-net/nl/aspose.slides.charts/piesplittype).

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
* klasse [`IChartSeries`](/slides/python-net/nl/aspose.slides.charts/ichartseries)
* enumeratie [`PieSplitType`](/slides/python-net/nl/aspose.slides.charts/piesplittype)
* module [`aspose.slides.charts`](/slides/python-net/nl/aspose.slides.charts)
* bibliotheek [`Aspose.Slides`](/slides/python-net)