---
title: overlap property
second_title: Aspose.Slides pro Python přes .NET API Reference
description: 
type: docs
url: /cs/aspose.slides.charts/chartseries/overlap/
weight: 310
---
## overlap vlastnost
Specifikuje, jak moc se pruhy a sloupce překrývají v 2-D grafech, jako procento (od -100 % do 100 %). 
            Toto není pouze vlastnost této řady, ale všech řad v nadřazené skupině řad. 
            Jedná se o projekci odpovídající vlastnosti v nadřazené skupině řad, a proto je tato vlastnost jen pro čtení.
            Pro změnu hodnoty použijte **ParentSeriesGroup.Overlap** vlastnost pro čtení/zápis.
            Pouze pro čtení **int**.


### Poznámky

Overlap určuje stupeň překrytí nebo mezery mezi pruhy a sloupci jako procento jejich šířky:
            - -100 %: Maximální mezera (pruhy jsou zcela oddělené).
            - 0 %: Pruhy jsou umístěny vedle sebe bez překrytí i mezery.
            - 100 %: Maximální překrytí (pruhy se zcela překrývají).
            Jedná se o projekci vlastnosti **ParentSeriesGroup.Overlap**.

### Definice:
```python
@property
def overlap(self):
    ...
```


### Viz také
* třída [`ChartSeries`](/slides/python-net/cs/aspose.slides.charts/chartseries)
* modul [`aspose.slides.charts`](/slides/python-net/cs/aspose.slides.charts)
* knihovna [`Aspose.Slides`](/slides/python-net)