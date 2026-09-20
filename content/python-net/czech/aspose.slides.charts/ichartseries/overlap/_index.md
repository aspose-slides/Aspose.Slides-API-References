---
title: overlap property
second_title: Aspose.Slides pro Python přes .NET referenční příručku API
description: 
type: docs
url: /cs/aspose.slides.charts/ichartseries/overlap/
weight: 310
---
## overlap vlastnost
Určuje, o kolik se pruhy a sloupce překrývají v 2-D grafech, jako procento (from -100% to 100%). 
            Tato vlastnost není jen pro tuto řadu, ale pro všechny řady nadřazené skupiny řad. 
            Jedná se o projekci odpovídající vlastnosti v nadřazené skupině řad, a proto je tato vlastnost jen pro čtení.
            Chcete-li změnit hodnotu, použijte vlastnost ParentSeriesGroup.Overlap pro čtení/zápis.
            Pouze pro čtení **int**.


### Poznámky

Overlap určuje míru překrytí nebo mezery mezi pruhy a sloupci jako procento jejich šířky:
            - -100%: Maximální mezera (pruhy jsou zcela odděleny).
            - 0%: Pruhy jsou umístěny vedle sebe bez překrytí či mezery.
            - 100%: Maximální překrytí (pruhy se zcela překrývají).
            Jedná se o projekci vlastnosti ParentSeriesGroup.Overlap.

### Definice:
```python
@property
def overlap(self):
    ...
```


### Viz také
* třída [`IChartSeries`](/slides/python-net/cs/aspose.slides.charts/ichartseries)
* modul [`aspose.slides.charts`](/slides/python-net/cs/aspose.slides.charts)
* knihovna [`Aspose.Slides`](/slides/python-net)