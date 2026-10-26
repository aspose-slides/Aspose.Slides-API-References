---
title: get_Overlap()
second_title: Aspose.Slides pro C++ – referenční dokumentace API
description: Určuje, jak moc se pruhy a sloupce překrývají v 2-D grafech, jako procento (od -100% do 100%). Jedná se o vlastnost nejen této řady, ale o všechny řady v nadřazené skupině řad. Jedná se o projekci odpovídající vlastnosti v nadřazené skupině řad, a proto je tato vlastnost pouze pro čtení. Pro změnu hodnoty použijte get_ParentSeriesGroup()->get(set)_Overlap() vlastnost pro čtení a zápis. Pouze pro čtení int8_t.
type: docs
weight: 690
url: /cs/aspose.slides.charts/ichartseries/get_overlap/
---
## IChartSeries::get_Overlap() metoda


Určuje, jak moc se pruhy a sloupce překrývají v 2-D grafech, jako procento (od -100% do 100%). Jedná se o vlastnost nejen této řady, ale o všechny řady v nadřazené skupině řad. Je to projekce odpovídající vlastnosti v nadřazené skupině řad a tato vlastnost je pouze ke čtení. Pro změnu hodnoty použijte [get_ParentSeriesGroup()](../get_parentseriesgroup/)->get(set)_Overlap() vlastnost pro čtení/zápis. Pouze ke čtení **int8_t**.

```cpp
virtual int8_t Aspose::Slides::Charts::IChartSeries::get_Overlap()=0
```

## Poznámky


Překrytí určuje míru překrytí nebo mezery mezi pruhy a sloupcemi jako procento jejich šířky:* -100%: Maximální mezera (pruhy jsou zcela oddělené).
* 0%: Pruhy jsou umístěny vedle sebe bez překrytí nebo mezery.
* 100%: Maximální překrytí (pruhy se navzájem zcela překrývají). Jedná se o projekci vlastnosti [get_ParentSeriesGroup()](../get_parentseriesgroup/)->get(set)_Overlap().


## Viz také

* Třída [IChartSeries](../)
* Jmenný prostor [Aspose::Slides::Charts](../../)
* Knihovna [Aspose.Slides](../../../)