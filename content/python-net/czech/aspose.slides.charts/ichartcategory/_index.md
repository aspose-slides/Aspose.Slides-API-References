---
title: IChartCategory class
second_title: Aspose.Slides pro Python prostřednictvím .NET API reference
description: 
type: docs
url: /cs/aspose.slides.charts/ichartcategory/
---
## IChartCategory třída

Představuje kategorie grafu.

Typ IChartCategory vystavuje následující členy:

## Vlastnosti

| Vlastnost | Popis |
| :- | :- |
| [`use_cell`](/slides/python-net/cs/aspose.slides.charts/ichartcategory/use_cell/) | Pokud je true, pak je vlastnost AsCell aktuální. Jinak řečeno, sešit je používán k <br/>            ukládání kategorie (tento případ podporuje víceúrovňovou kategorii).<br/>            Pokud je false, pak je vlastnost AsLiteral aktuální. Jinak řečeno, sešit NENÍ používán <br/>            k ukládání kategorie (a tento případ nepodporuje víceúrovňové kategorie).<br/>            Pouze pro čtení **bool**. |
| [`as_cell`](/slides/python-net/cs/aspose.slides.charts/ichartcategory/as_cell/) | Vrací nebo nastavuje objekt IChartDataCell.<br/>            Pokud je kategorie víceúrovňová, pak je použit objekt IChartDataCell pro úroveň "0".<br/>            Čtení/Zápis [`IChartDataCell`](/slides/python-net/cs/aspose.slides.charts/ichartdatacell). |
| [`as_literal`](/slides/python-net/cs/aspose.slides.charts/ichartcategory/as_literal/) | Vrací nebo nastavuje AsLiteral, pokud je UseCell false.<br/>            Čtení/Zápis **any**. |
| [`value`](/slides/python-net/cs/aspose.slides.charts/ichartcategory/value/) | Pokud je UseCell true, pak tato vlastnost představuje vlastnost AsCell.Value.<br/>            Pokud je UseCell false, pak tato vlastnost představuje vlastnost AsLiteral.<br/>            Čtení/Zápis **any**. |
| [`cached_value`](/slides/python-net/cs/aspose.slides.charts/ichartcategory/cached_value/) | Získá kešovanou hodnotu kategorie grafu.<br/>            Pouze pro čtení [`ICachedChartValue`](/slides/python-net/cs/aspose.slides.charts/icachedchartvalue). |
| [`grouping_levels`](/slides/python-net/cs/aspose.slides.charts/ichartcategory/grouping_levels/) | Spravovaný kontejner hodnot úrovní seskupování kategorií grafu.<br/>            Víceúrovňová kategorie obsahuje více než jednu úroveň seskupování.<br/>            Indexování úrovní seskupování je nulové.<br/>            Pouze pro čtení [`IChartCategoryLevelsManager`](/slides/python-net/cs/aspose.slides.charts/ichartcategorylevelsmanager). |

## Metody

| Metoda | Popis |
| :- | :- |
| [`remove(self)`](/slides/python-net/cs/aspose.slides.charts/ichartcategory/remove/#) | Odstraní kategorii z grafu. |

### Viz také
* modul [`aspose.slides.charts`](/slides/python-net/cs/aspose.slides.charts)
* knihovna [`Aspose.Slides`](/slides/python-net)