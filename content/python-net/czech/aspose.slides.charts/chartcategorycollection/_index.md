---
title: ChartCategoryCollection class
second_title: Aspose.Slides pro Python přes .NET API Reference
description: 
type: docs
url: /cs/aspose.slides.charts/chartcategorycollection/
---
## ChartCategoryCollection třída

Reprezentuje kolekci [`ChartCategory`](/slides/python-net/cs/aspose.slides.charts/chartcategory)

Typ ChartCategoryCollection vystavuje následující členy:

## Vlastnosti

| Vlastnost | Popis |
| :- | :- |
| [`use_cells`](/slides/python-net/cs/aspose.slides.charts/chartcategorycollection/use_cells/) | Pokud je true, pak se list používá pro ukládání kategorií (tento případ podporuje víceúrovňové kategorie).<br/>            Pokud je false, pak se list NEpoužívá pro ukládání hodnot (a tento případ nepodporuje <br/>            víceúrovňové kategorie).<br/>            Čtení/zápis **bool**. |
| [`grouping_level_count`](/slides/python-net/cs/aspose.slides.charts/chartcategorycollection/grouping_level_count/) | Vrací počet úrovní seskupení kategorií použitých.<br/>            Je více než jedna pro víceúrovňové kategorie.<br/>            Pouze pro čtení **int**. |

Získá prvek na určeném indexu.

## Indexér

| Název | Popis |
| :- | :- |
| [`[index]`](/slides/python-net/cs/aspose.slides.charts/chartcategorycollection/__getitem__/) |  |

## Metody

| Metoda | Popis |
| :- | :- |
| [`add(self, chart_data_cell)`](/slides/python-net/cs/aspose.slides.charts/chartcategorycollection/add/#ichartdatacell) | Pokud kategorie existuje v kolekci, vrátí ji. Jinak vytvoří novou kategorii grafu z <br/>            [`IChartDataCell`](/slides/python-net/cs/aspose.slides.charts/ichartdatacell) a přidá ji do kolekce. |
| [`add(self, value)`](/slides/python-net/cs/aspose.slides.charts/chartcategorycollection/add/#any) | Vytvoří nový [`ChartCategory`](/slides/python-net/cs/aspose.slides.charts/chartcategory) z hodnoty a přidá jej do kolekce. |
| [`index_of(self, value)`](/slides/python-net/cs/aspose.slides.charts/chartcategorycollection/index_of/#ichartcategory) | Prohledá zadaný [`ChartCategory`](/slides/python-net/cs/aspose.slides.charts/chartcategory) a vrátí index (číslo od nuly) první výskyt v celé kolekci. |
| [`remove(self, value)`](/slides/python-net/cs/aspose.slides.charts/chartcategorycollection/remove/#ichartcategory) | Odstraní zadanou hodnotu. |
| [`remove_at(self, index)`](/slides/python-net/cs/aspose.slides.charts/chartcategorycollection/remove_at/#int) | Odstraní prvek na zadaném indexu. |
| [`clear(self)`](/slides/python-net/cs/aspose.slides.charts/chartcategorycollection/clear/#) | Odstraní všechny prvky z kolekce. |

### Viz také
* třída [`ChartCategory`](/slides/python-net/cs/aspose.slides.charts/chartcategory)
* modul [`aspose.slides.charts`](/slides/python-net/cs/aspose.slides.charts)
* knihovna [`Aspose.Slides`](/slides/python-net)