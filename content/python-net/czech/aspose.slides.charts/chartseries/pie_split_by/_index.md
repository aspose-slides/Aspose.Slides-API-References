---
title: pie_split_by property
second_title: Aspose.Slides pro Python via .NET API Reference
description: 
type: docs
url: /cs/aspose.slides.charts/chartseries/pie_split_by/
weight: 340
---
## pie_split_by vlastnost
Určuje, jak určit, které datové body jsou ve druhém výsečí nebo pruhu 
            na diagramu výseč-z-výsečí nebo pruh-z-pruhem.
            Jedná se o vlastnost nejen tohoto řady, ale všech řad nadřazené skupiny řad – jedná se o projekci příslušné skupinové vlastnosti. Tato vlastnost je tedy pouze pro čtení.
            Pro přístup k nadřazené skupině řad použijte vlastnost ParentSeriesGroup.
            Pro změnu hodnoty použijte vlastnost ParentSeriesGroup.PieSplitBy s možností čtení i zápisu.
            Pouze pro čtení [`PieSplitType`](/slides/python-net/cs/aspose.slides.charts/piesplittype).


### Poznámky

1) Jedná se o projekci vlastnosti ParentSeriesGroup.PieSplitBy.
            2) Pokud je hodnota vlastnosti PieSplitType.Custom, můžete definovat vlastní rozdělení pomocí vlastnosti ParentSeriesGroup.PieSplitCustomPoints.


### Definice:
```python
@property
def pie_split_by(self):
    ...
```


### Viz také
* třída [`ChartSeries`](/slides/python-net/cs/aspose.slides.charts/chartseries)
* enumerace [`PieSplitType`](/slides/python-net/cs/aspose.slides.charts/piesplittype)
* modul [`aspose.slides.charts`](/slides/python-net/cs/aspose.slides.charts)
* knihovna [`Aspose.Slides`](/slides/python-net)