---
title: IChartData class
second_title: Aspose.Slides pro Python přes .NET API Reference
description: 
type: docs
url: /cs/aspose.slides.charts/ichartdata/
---
## IChartData třída

Represents data used for a chart plotting.

The IChartData type exposes the following members:

## Properties

| Vlastnost | Popis |
| :- | :- |
| [`chart_data_workbook`](/slides/python-net/cs/aspose.slides.charts/ichartdata/chart_data_workbook/) | Získává továrnu na buňky pro vytváření buněk používaných pro řady nebo kategorie grafu.<br/>Pouze pro čtení [`IChartDataWorkbook`](/slides/python-net/cs/aspose.slides.charts/ichartdataworkbook). |
| [`series`](/slides/python-net/cs/aspose.slides.charts/ichartdata/series/) | Získává řady.<br/>Pouze pro čtení [`IChartSeriesCollection`](/slides/python-net/cs/aspose.slides.charts/ichartseriescollection). |
| [`series_groups`](/slides/python-net/cs/aspose.slides.charts/ichartdata/series_groups/) | Získává skupiny řad.<br/>Pouze pro čtení [`IChartSeriesGroupCollection`](/slides/python-net/cs/aspose.slides.charts/ichartseriesgroupcollection). |
| [`categories`](/slides/python-net/cs/aspose.slides.charts/ichartdata/categories/) | Získává primární kategorie (nebo jak primární, tak sekundární kategorie, pokud je vlastnost [`IChartData.use_secondary_categories`](/slides/python-net/cs/aspose.slides.charts/ichartdata/use_secondary_categories) false).<br/>Pouze pro čtení [`IChartCategoryCollection`](/slides/python-net/cs/aspose.slides.charts/ichartcategorycollection). |
| [`use_secondary_categories`](/slides/python-net/cs/aspose.slides.charts/ichartdata/use_secondary_categories/) | Pokud je false, pak vlastnost [`IChartData.secondary_categories`](/slides/python-net/cs/aspose.slides.charts/ichartdata/secondary_categories) vrací None a data v vlastnosti [`IChartData.categories`](/slides/python-net/cs/aspose.slides.charts/ichartdata/categories) jsou použita jak pro primární, tak sekundární řady.<br/>Pokud je true, pak data ve vlastnosti [`IChartData.secondary_categories`](/slides/python-net/cs/aspose.slides.charts/ichartdata/secondary_categories) jsou použita pro sekundární řady a data ve vlastnosti [`IChartData.categories`](/slides/python-net/cs/aspose.slides.charts/ichartdata/categories) jsou použita pro primární řady.<br/>Čtení/zápis **bool**. |
| [`secondary_categories`](/slides/python-net/cs/aspose.slides.charts/ichartdata/secondary_categories/) | Získává sekundární kategorie, pokud je vlastnost [`IChartData.use_secondary_categories`](/slides/python-net/cs/aspose.slides.charts/ichartdata/use_secondary_categories) true.<br/>Pouze pro čtení [`IChartCategoryCollection`](/slides/python-net/cs/aspose.slides.charts/ichartcategorycollection). |
| [`data_source_type`](/slides/python-net/cs/aspose.slides.charts/ichartdata/data_source_type/) | Reprezentuje zdroj dat grafu |
| [`external_workbook_path`](/slides/python-net/cs/aspose.slides.charts/ichartdata/external_workbook_path/) | Reprezentuje cestu k externímu sešitu, pokud je zdroj dat externí, jinak None |
| [`embedded_workbook_type`](/slides/python-net/cs/aspose.slides.charts/ichartdata/embedded_workbook_type/) | Získává typ vloženého sešitu.<br/>Vrací [`WorkbookType.NOT_DEFINED`](/slides/python-net/cs/aspose.slides.charts/workbooktype/NOT_DEFINED), pokud je [`IChartData.data_source_type`](/slides/python-net/cs/aspose.slides.charts/ichartdata/data_source_type) [`ChartDataSourceType.EXTERNAL_WORKBOOK`](/slides/python-net/cs/aspose.slides.charts/chartdatasourcetype/EXTERNAL_WORKBOOK).<br/>Pouze pro čtení [`WorkbookType`](/slides/python-net/cs/aspose.slides.charts/workbooktype). |

## Metody

| Metoda | Popis |
| :- | :- |
| [`set_external_workbook(self, workbook_path)`](/slides/python-net/cs/aspose.slides.charts/ichartdata/set_external_workbook/#str) | Nastaví externí sešit jako zdroj dat pro graf. Data grafu budou aktualizována z cílového sešitu. |
| [`set_external_workbook(self, workbook_path, update_chart_data)`](/slides/python-net/cs/aspose.slides.charts/ichartdata/set_external_workbook/#str-bool) | Nastaví externí sešit jako zdroj dat pro graf. |
| [`read_workbook_stream(self)`](/slides/python-net/cs/aspose.slides.charts/ichartdata/read_workbook_stream/#) | Zapíše interně obsažený sešit Excel do paměťového proudu. |
| [`write_workbook_stream(self, ms)`](/slides/python-net/cs/aspose.slides.charts/ichartdata/write_workbook_stream/#iorawiobase) | Inicializuje interně obsažený sešit Excel hodnotou zadanou uživatelem. |
| [`set_range(self, formula)`](/slides/python-net/cs/aspose.slides.charts/ichartdata/set_range/#str) | Nastaví rozsah dat grafu. Řady a kategorie budou aktualizovány na základě nového rozsahu dat.<br/>Pokud je počet řad v rozsahu dat větší než počet řad v datech grafu, budou přidány další řady se stejným typem jako poslední řada v aktuální kolekci, a to na konec kolekce. |
| [`get_range(self)`](/slides/python-net/cs/aspose.slides.charts/ichartdata/get_range/#) | Získává rozsah dat grafu. |
| [`switch_row_column(self)`](/slides/python-net/cs/aspose.slides.charts/ichartdata/switch_row_column/#) | Prohodí data podél osy.<br/>Data zobrazovaná na ose X se přesunou na osu Y a naopak. |
| [`refresh_data(self)`](/slides/python-net/cs/aspose.slides.charts/ichartdata/refresh_data/#) | Obnoví data grafu načtením z původního sešitu. |


### Viz také
* modul [`aspose.slides.charts`](/slides/python-net/cs/aspose.slides.charts)
* knihovna [`Aspose.Slides`](/slides/python-net)