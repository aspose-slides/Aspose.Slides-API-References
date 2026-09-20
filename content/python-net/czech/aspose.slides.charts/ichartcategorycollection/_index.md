---
title: IChartCategoryCollection class
second_title: Aspose.Slides pro Python prostřednictvím .NET API Reference
description: 
type: docs
url: /cs/aspose.slides.charts/ichartcategorycollection/
---
## IChartCategoryCollection třída

Představuje kolekci [`IChartCategory`](/slides/python-net/cs/aspose.slides.charts/ichartcategory)

Typ IChartCategoryCollection obsahuje následující členy:

## Vlastnosti

| Vlastnost | Popis |
| :- | :- |
| [`use_cells`](/slides/python-net/cs/aspose.slides.charts/ichartcategorycollection/use_cells/) | Pokud je true, pak se list použije k ukládání kategorií (tento případ podporuje víceúrovňové kategorie).<br/>            Pokud je false, pak se list NEpoužije k ukládání hodnot (a tento případ nepodporuje <br/>            víceúrovňové kategorie).<br/>            Čtení/zápis **bool**. |
| [`grouping_level_count`](/slides/python-net/cs/aspose.slides.charts/ichartcategorycollection/grouping_level_count/) | Vrací počet úrovní seskupování kategorií použitého.<br/>            Je více než jedna pro víceúrovňové kategorie.<br/>            Pouze pro čtení **int**. |

Získá prvek na zadaném indexu.

## Indexér

| Název | Popis |
| :- | :- |
| [`[index]`](/slides/python-net/cs/aspose.slides.charts/ichartcategorycollection/__getitem__/) |  |

## Metody

| Metoda | Popis |
| :- | :- |
| [`add(self, chart_data_cell)`](/slides/python-net/cs/aspose.slides.charts/ichartcategorycollection/add/#ichartdatacell) | Pokud kategorie v kolekci existuje, vrátí ji. Jinak vytvoří novou kategorii grafu z <br/>            [`IChartDataCell`](/slides/python-net/cs/aspose.slides.charts/ichartdatacell) a přidá ji do kolekce. |
| [`add(self, value)`](/slides/python-net/cs/aspose.slides.charts/ichartcategorycollection/add/#any) | Vytvoří nový [`IChartCategory`](/slides/python-net/cs/aspose.slides.charts/ichartcategory) z hodnoty a přidá jej do kolekce. |
| [`index_of(self, value)`](/slides/python-net/cs/aspose.slides.charts/ichartcategorycollection/index_of/#ichartcategory) | Vyhledá zadaný [`IChartCategory`](/slides/python-net/cs/aspose.slides.charts/ichartcategory) a vrátí nulový index první výskytu v celé kolekci |
| [`remove(self, value)`](/slides/python-net/cs/aspose.slides.charts/ichartcategorycollection/remove/#ichartcategory) | Odstraní zadanou hodnotu. |
| [`remove_at(self, index)`](/slides/python-net/cs/aspose.slides.charts/ichartcategorycollection/remove_at/#int) | Odstraní prvek na zadaném indexu. |
| [`clear(self)`](/slides/python-net/cs/aspose.slides.charts/ichartcategorycollection/clear/#) | Odstraní všechny prvky z kolekce. |

### Viz také
* třída [`IChartCategory`](/slides/python-net/cs/aspose.slides.charts/ichartcategory)
* modul [`aspose.slides.charts`](/slides/python-net/cs/aspose.slides.charts)
* knihovna [`Aspose.Slides`](/slides/python-net)