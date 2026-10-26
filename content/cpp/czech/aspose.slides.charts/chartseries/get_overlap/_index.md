---
title: get_Overlap()
second_title: Aspose.Slides pro C++ referenční příručka API
description: Určuje, jak moc se pruhy a sloupce překrývají na 2-D grafech, jako procento (od -100% do 100%). Jedná se o vlastnost nejen této řady, ale všech řad v nadřazené skupině řad. Je to projekce odpovídající vlastnosti v nadřazené skupině řad, a proto je tato vlastnost jen pro čtení. Pro změnu hodnoty použijte get_ParentSeriesGroup()->Overlap() vlastnost s možností čtení i zápisu. Pouze pro čtení int8_t.
type: docs
weight: 690
url: /cs/aspose.slides.charts/chartseries/get_overlap/
---
## ChartSeries::get_Overlap() metoda

Určuje, jak moc se pruhy a sloupce překrývají na 2-D grafech, vyjádřeno v procentech (od -100% do 100%). Jedná se o vlastnost nejen této řady, ale všech řad v nadřazené skupině řad. Je to projekce odpovídající vlastnosti v nadřazené skupině řad, a proto je tato vlastnost jen pro čtení. Pro změnu hodnoty použijte vlastnost [get_ParentSeriesGroup()->Overlap()](../get_parentseriesgroup/) s možností čtení i zápisu. Pouze pro čtení **int8_t**.

```cpp
int8_t Aspose::Slides::Charts::ChartSeries::get_Overlap() override
```

## Poznámky

Překrytí určuje míru překrytí nebo mezery mezi pruhy a sloupci jako procento jejich šířky:
* -100%: Maximální mezera (pruhy jsou zcela odděleny).
* 0%: Pruhy jsou umístěny vedle sebe bez překrytí nebo mezery.
* 100%: Maximální překrytí (pruhy se zcela překrývají). Jedná se o projekci vlastnosti [get_ParentSeriesGroup()->Overlap()](../get_parentseriesgroup/).

## Viz také

* Třída [ChartSeries](../)
* Jmenný prostor [Aspose::Slides::Charts](../../)
* Knihovna [Aspose.Slides](../../../)