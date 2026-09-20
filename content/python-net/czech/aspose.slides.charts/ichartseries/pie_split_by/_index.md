---
title: pie_split_by property
second_title: Aspose.Slides pro Python přes .NET - referenční příručka API
description: 
type: docs
url: /cs/aspose.slides.charts/ichartseries/pie_split_by/
weight: 340
---
## vlastnost pie_split_by
Určuje, jak určit, které datové body jsou ve druhém výseku nebo sloupci v grafu typu koláč-v-koláči nebo sloupec-v-koláči.  
Jedná se o vlastnost nejen této řady, ale všech řad nadřazené skupiny řad – jedná se o projekci odpovídající skupiny vlastností. Tato vlastnost je tedy pouze pro čtení.  
Použijte vlastnost ParentSeriesGroup pro přístup k nadřazené skupině řad.  
Použijte vlastnost ParentSeriesGroup.PieSplitBy pro čtení/zápis k změně hodnoty.  
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
* třída [`IChartSeries`](/slides/python-net/cs/aspose.slides.charts/ichartseries)
* výčtový typ [`PieSplitType`](/slides/python-net/cs/aspose.slides.charts/piesplittype)
* modul [`aspose.slides.charts`](/slides/python-net/cs/aspose.slides.charts)
* knihovna [`Aspose.Slides`](/slides/python-net)