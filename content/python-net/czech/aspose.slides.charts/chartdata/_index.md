---
title: ChartData class
second_title: Aspose.Slides pro Python přes .NET API Reference
description: 
type: docs
url: /cs/aspose.slides.charts/chartdata/
---
## Třída ChartData

Reprezentuje data používaná pro vykreslování grafu.

Typ ChartData vystavuje následující členy:

## Vlastnosti

| Vlastnost | Popis |
| :- | :- |
| [`chart_data_workbook`](/slides/python-net/cs/aspose.slides.charts/chartdata/chart_data_workbook/) | Získává továrnu na buňky pro vytvoření buněk používaných pro řady grafu nebo kategorie.<br/>            Pouze pro čtení [`IChartDataWorkbook`](/slides/python-net/cs/aspose.slides.charts/ichartdataworkbook). |
| [`series`](/slides/python-net/cs/aspose.slides.charts/chartdata/series/) | Získává řady.<br/>            Pouze pro čtení [`IChartSeriesCollection`](/slides/python-net/cs/aspose.slides.charts/ichartseriescollection). |
| [`series_groups`](/slides/python-net/cs/aspose.slides.charts/chartdata/series_groups/) | Získává skupiny řad.<br/>            Pouze pro čtení [`IChartSeriesGroupCollection`](/slides/python-net/cs/aspose.slides.charts/ichartseriesgroupcollection). |
| [`categories`](/slides/python-net/cs/aspose.slides.charts/chartdata/categories/) | Získává primární kategorie (nebo jak primární tak sekundární kategorie <br/>            pokud je vlastnost [`ChartData.use_secondary_categories`](/slides/python-net/cs/aspose.slides.charts/chartdata/use_secondary_categories) false).<br/>            Pouze pro čtení [`IChartCategoryCollection`](/slides/python-net/cs/aspose.slides.charts/ichartcategorycollection). |
| [`use_secondary_categories`](/slides/python-net/cs/aspose.slides.charts/chartdata/use_secondary_categories/) | Pokud je false, pak vlastnost [`ChartData.secondary_categories`](/slides/python-net/cs/aspose.slides.charts/chartdata/secondary_categories) vrátí None a data <br/>            ve vlastnosti [`ChartData.categories`](/slides/python-net/cs/aspose.slides.charts/chartdata/categories) jsou použita jak pro primární, tak sekundární řady.<br/>            Pokud je true, pak data ve vlastnosti [`ChartData.secondary_categories`](/slides/python-net/cs/aspose.slides.charts/chartdata/secondary_categories) jsou použita pro sekundární řady a data <br/>            ve vlastnosti [`ChartData.categories`](/slides/python-net/cs/aspose.slides.charts/chartdata/categories) jsou použita pro primární řady.<br/>            Čtení/Zápis **bool**. |
| [`secondary_categories`](/slides/python-net/cs/aspose.slides.charts/chartdata/secondary_categories/) | Získává sekundární kategorie, pokud je vlastnost [`ChartData.use_secondary_categories`](/slides/python-net/cs/aspose.slides.charts/chartdata/use_secondary_categories) true.<br/>            Pouze pro čtení [`IChartCategoryCollection`](/slides/python-net/cs/aspose.slides.charts/ichartcategorycollection). |
| [`data_source_type`](/slides/python-net/cs/aspose.slides.charts/chartdata/data_source_type/) | Reprezentuje cestu k externímu sešitu, pokud je externí zdroj dat, jinak None |
| [`external_workbook_path`](/slides/python-net/cs/aspose.slides.charts/chartdata/external_workbook_path/) | Reprezentuje zdroj dat grafu |
| [`embedded_workbook_type`](/slides/python-net/cs/aspose.slides.charts/chartdata/embedded_workbook_type/) | Získává typ vloženého sešitu.<br/>            Vrací [`WorkbookType.NOT_DEFINED`](/slides/python-net/cs/aspose.slides.charts/workbooktype/NOT_DEFINED) pokud je [`ChartData.data_source_type`](/slides/python-net/cs/aspose.slides.charts/chartdata/data_source_type) <br/>            [`ChartDataSourceType.EXTERNAL_WORKBOOK`](/slides/python-net/cs/aspose.slides.charts/chartdatasourcetype/EXTERNAL_WORKBOOK).<br/>            Pouze pro čtení [`WorkbookType`](/slides/python-net/cs/aspose.slides.charts/workbooktype). |

## Metody

| Metoda | Popis |
| :- | :- |
| [`set_external_workbook(self, workbook_path)`](/slides/python-net/cs/aspose.slides.charts/chartdata/set_external_workbook/#str) | Nastavuje externí sešit jako zdroj dat pro graf. Data grafu budou aktualizována z cílového sešitu. |
| [`set_external_workbook(self, workbook_path, update_chart_data)`](/slides/python-net/cs/aspose.slides.charts/chartdata/set_external_workbook/#str-bool) | Nastavuje externí sešit jako zdroj dat pro graf. |
| [`read_workbook_stream(self)`](/slides/python-net/cs/aspose.slides.charts/chartdata/read_workbook_stream/#) | Zapíše interně obsažený Excel sešit do proudu. |
| [`write_workbook_stream(self, ms)`](/slides/python-net/cs/aspose.slides.charts/chartdata/write_workbook_stream/#iorawiobase) | Inicializuje interně obsažený Excel sešit s uživatelem specifikovanou hodnotou. |
| [`get_range(self)`](/slides/python-net/cs/aspose.slides.charts/chartdata/get_range/#) | Získává rozsah dat grafu. |
| [`set_range(self, formula)`](/slides/python-net/cs/aspose.slides.charts/chartdata/set_range/#str) | Nastaví rozsah dat grafu. Řady a kategorie budou aktualizovány na základě nového rozsahu dat.<br/>            Pokud je počet řad v rozsahu dat větší než počet řad v datech grafu, budou přidány další řady se stejným typem<br/>            jako poslední řada v aktuální kolekci, na konec kolekce. |
| [`switch_row_column(self)`](/slides/python-net/cs/aspose.slides.charts/chartdata/switch_row_column/#) | Prohodí data po osách.<br/>            Data zobrazovaná na ose X se přesunou na osu Y a naopak. |


### Viz také
* modul [`aspose.slides.charts`](/slides/python-net/cs/aspose.slides.charts)
* knihovna [`Aspose.Slides`](/slides/python-net)