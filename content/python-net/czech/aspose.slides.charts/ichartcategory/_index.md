---
title: IChartCategory class
second_title: Aspose.Slides pro Python přes .NET API Referenci
description: 
type: docs
url: /cs/aspose.slides.charts/ichartcategory/
---
## IChartCategory třída

Reprezentuje kategorie grafu.

Typ IChartCategory vystavuje následující členy:

## Vlastnosti

| Property | Description |
| :- | :- |
| [`use_cell`](/slides/python-net/cs/aspose.slides.charts/ichartcategory/use_cell/) | Pokud je true, pak je platná vlastnost AsCell. Jinak řečeno, list se používá pro ukládání kategorie (tento případ podporuje vícestupňovou kategorii).<br/>            Pokud je false, pak je platná vlastnost AsLiteral. Jinak řečeno, list NENÍ používán pro ukládání kategorie (a tento případ nepodporuje vícestupňové kategorie).<br/>            Pouze pro čtení **bool**. |
| [`as_cell`](/slides/python-net/cs/aspose.slides.charts/ichartcategory/as_cell/) | Vrací nebo nastavuje objekt IChartDataCell.<br/>            Pokud je kategorie vícestupňová, používá se objekt IChartDataCell pro úroveň "0".<br/>            Čtení/zápis [`IChartDataCell`](/slides/python-net/cs/aspose.slides.charts/ichartdatacell). |
| [`as_literal`](/slides/python-net/cs/aspose.slides.charts/ichartcategory/as_literal/) | Vrací nebo nastavuje AsLiteral, pokud je UseCell false.<br/>            Čtení/zápis **any**. |
| [`value`](/slides/python-net/cs/aspose.slides.charts/ichartcategory/value/) | Pokud je UseCell true, pak tato vlastnost představuje vlastnost AsCell.Value.<br/>            Pokud je UseCell false, pak tato vlastnost představuje vlastnost AsLiteral.<br/>            Čtení/zápis **any**. |
| [`grouping_levels`](/slides/python-net/cs/aspose.slides.charts/ichartcategory/grouping_levels/) | Spravovaný kontejner hodnot úrovní seskupování kategorií grafu.<br/>            Vícestupňová kategorie obsahuje více než jednu úroveň seskupování.<br/>            Indexování úrovní seskupování je založeno na nule.<br/>            Pouze pro čtení [`IChartCategoryLevelsManager`](/slides/python-net/cs/aspose.slides.charts/ichartcategorylevelsmanager). |

## Metody

| Method | Description |
| :- | :- |
| [`remove(self)`](/slides/python-net/cs/aspose.slides.charts/ichartcategory/remove/#) | Odstraní kategorii z grafu. |


### Viz také
* modul [`aspose.slides.charts`](/slides/python-net/cs/aspose.slides.charts)
* knihovna [`Aspose.Slides`](/slides/python-net)