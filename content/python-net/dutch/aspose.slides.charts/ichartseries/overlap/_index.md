---
title: overlap property
second_title: Aspose.Slides voor Python via .NET API Referentie
description: 
type: docs
url: /nl/aspose.slides.charts/ichartseries/overlap/
weight: 310
---
## overlap eigenschap
Specificeert hoeveel balken en kolommen overlappen op 2-D-grafieken, als een percentage (van -100 % tot 100 %).
            Dit is de eigenschap niet alleen van deze reeks maar van alle reeksen van de bovenliggende seriesgroep.
            Het is een projectie van de juiste eigenschap in de bovenliggende seriesgroep, en daarom is deze eigenschap alleen-lezen.
            Om de waarde te wijzigen, gebruik de ParentSeriesGroup.Overlap lezen/schrijven eigenschap.
            Alleen-lezen **int**.


### Opmerkingen

Overlap specificeert de mate van overlapping of spatiëring tussen balken en kolommen als een percentage van hun breedte:
            - -100%: Maximale spatiëring (balken zijn volledig gescheiden).
            - 0%: Balken worden naast elkaar geplaatst zonder overlapping of spatiëring.
            - 100%: Maximale overlapping (balken overlappen elkaar volledig).
            Dit is een projectie van de eigenschap ParentSeriesGroup.Overlap.

### Definitie:
```python
@property
def overlap(self):
    ...
```


### Zie ook
* klasse [`IChartSeries`](/slides/python-net/nl/aspose.slides.charts/ichartseries)
* module [`aspose.slides.charts`](/slides/python-net/nl/aspose.slides.charts)
* bibliotheek [`Aspose.Slides`](/slides/python-net)