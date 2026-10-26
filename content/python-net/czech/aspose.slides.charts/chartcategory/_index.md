---
title: ChartCategory class
second_title: Aspose.Slides pro Python přes .NET API Reference
description: 
type: docs
url: /cs/aspose.slides.charts/chartcategory/
---
## ChartCategory třída

Představuje kategorie grafu.

Typ ChartCategory vystavuje následující členy:

## Vlastnosti

| Vlastnost | Popis |
| :- | :- |
| [`use_cell`](/slides/python-net/cs/aspose.slides.charts/chartcategory/use_cell/) | Pokud je true, je vlastnost AsCell aktuální. Jinými slovy, worksheet je použit pro <br/>            storing category (tento případ podporuje víceúrovňovou kategorii).<br/>            Pokud je false, je vlastnost AsLiteral aktuální. Jinými slovy, worksheet NENÍ použit <br/>            pro storing category (a tento případ nepodporuje víceúrovňové kategorie).<br/>            Pouze pro čtení **bool**. |
| [`as_cell`](/slides/python-net/cs/aspose.slides.charts/chartcategory/as_cell/) | Vrací nebo nastavuje objekt IChartDataCell.<br/>            Pokud je kategorie víceúrovňová, pak se používá objekt IChartDataCell pro úroveň "0".<br/>            Čtení/zápis [`IChartDataCell`](/slides/python-net/cs/aspose.slides.charts/ichartdatacell). |
| [`as_literal`](/slides/python-net/cs/aspose.slides.charts/chartcategory/as_literal/) | Vrací nebo nastavuje objekt AsLiteral.<br/>            Čtení/zápis **any**. |
| [`value`](/slides/python-net/cs/aspose.slides.charts/chartcategory/value/) | Pokud je UseCell true, tato vlastnost představuje vlastnost AsCell.Value.<br/>            Pokud je UseCell false, tato vlastnost představuje vlastnost AsLiteral.<br/>            Čtení/zápis **any**. |
| [`grouping_levels`](/slides/python-net/cs/aspose.slides.charts/chartcategory/grouping_levels/) | Spravovaný kontejner hodnot úrovní seskupování kategorií grafu.<br/>            Víceúrovňová kategorie obsahuje více než jednu úroveň seskupování.<br/>            Indexování úrovní seskupování je nulové-založené.<br/>            Pouze pro čtení [`IChartCategoryLevelsManager`](/slides/python-net/cs/aspose.slides.charts/ichartcategorylevelsmanager). |

## Metody

| Metoda | Popis |
| :- | :- |
| [`remove(self)`](/slides/python-net/cs/aspose.slides.charts/chartcategory/remove/#) | Odstraňuje kategorii z grafu. |


### Viz také
* modul [`aspose.slides.charts`](/slides/python-net/cs/aspose.slides.charts)
* knihovna [`Aspose.Slides`](/slides/python-net)