---
title: ChartCategory class
second_title: Aspose.Slides pro Python prostřednictvím .NET API Reference
description: 
type: docs
url: /cs/aspose.slides.charts/chartcategory/
---
## ChartCategory třída

Representuje kategorie grafu.

Typ ChartCategory vystavuje následující členy:

## Vlastnosti

| Vlastnost | Popis |
| :- | :- |
| [`use_cell`](/slides/python-net/cs/aspose.slides.charts/chartcategory/use_cell/) | Pokud je true, pak je vlastnost AsCell aktuální. Jinými slovy, list se používá pro <br/>            ukládání kategorie (tento případ podporuje vícestupňovou kategorii).<br/>            Pokud je false, pak je vlastnost AsLiteral aktuální. Jinými slovy, list NENÍ použit <br/>            pro ukládání kategorie (a tento případ nepodporuje vícestupňové kategorie).<br/>            Pouze pro čtení **bool**. |
| [`as_cell`](/slides/python-net/cs/aspose.slides.charts/chartcategory/as_cell/) | Vrací nebo nastavuje objekt IChartDataCell.<br/>            Pokud je kategorie vícestupňová, pak se používá objekt IChartDataCell pro úroveň "0".<br/>            Čtení/zápis [`IChartDataCell`](/slides/python-net/cs/aspose.slides.charts/ichartdatacell). |
| [`as_literal`](/slides/python-net/cs/aspose.slides.charts/chartcategory/as_literal/) | Vrací nebo nastavuje objekt AsLiteral.<br/>            Čtení/zápis **any**. |
| [`value`](/slides/python-net/cs/aspose.slides.charts/chartcategory/value/) | Pokud je UseCell true, pak tato vlastnost představuje vlastnost AsCell.Value.<br/>            Pokud je UseCell false, pak tato vlastnost představuje vlastnost AsLiteral.<br/>            Čtení/zápis **any**. |
| [`grouping_levels`](/slides/python-net/cs/aspose.slides.charts/chartcategory/grouping_levels/) | Spravovaný kontejner hodnot úrovní seskupení kategorií grafu.<br/>            Víceúrovňová kategorie obsahuje více než jednu úroveň seskupení.<br/>            Indexování úrovní seskupení je nulové.<br/>            Pouze pro čtení [`IChartCategoryLevelsManager`](/slides/python-net/cs/aspose.slides.charts/ichartcategorylevelsmanager). |
| [`cached_value`](/slides/python-net/cs/aspose.slides.charts/chartcategory/cached_value/) | Získá uloženou hodnotu kategorie grafu.<br/>            Pouze pro čtení [`ICachedChartValue`](/slides/python-net/cs/aspose.slides.charts/icachedchartvalue). |

## Metody

| Metoda | Popis |
| :- | :- |
| [`remove(self)`](/slides/python-net/cs/aspose.slides.charts/chartcategory/remove/#) | Odstraní kategorii z grafu. |

### Viz také
* modul [`aspose.slides.charts`](/slides/python-net/cs/aspose.slides.charts)
* knihovna [`Aspose.Slides`](/slides/python-net)