---
title: IChartData class
second_title: Aspose.Slides pro Python přes .NET API Reference
description: 
type: docs
url: /cs/aspose.slides.charts/ichartdata/
---
## IChartData třída

Reprezentuje data používaná pro vykreslování grafu.

Typ IChartData poskytuje následující členy:

## Vlastnosti

| Vlastnost | Popis |
| :- | :- |
| [`chart_data_workbook`](/slides/python-net/cs/aspose.slides.charts/ichartdata/chart_data_workbook/) | Získá továrnu na buňky pro vytváření buněk používaných pro řady grafu nebo kategorie.<br/> Pouze pro čtení [`IChartDataWorkbook`](/slides/python-net/cs/aspose.slides.charts/ichartdataworkbook). |
| [`series`](/slides/python-net/cs/aspose.slides.charts/ichartdata/series/) | Získá řady.<br/> Pouze pro čtení [`IChartSeriesCollection`](/slides/python-net/cs/aspose.slides.charts/ichartseriescollection). |
| [`series_groups`](/slides/python-net/cs/aspose.slides.charts/ichartdata/series_groups/) | Získá skupiny řad.<br/> Pouze pro čtení [`IChartSeriesGroupCollection`](/slides/python-net/cs/aspose.slides.charts/ichartseriesgroupcollection). |
| [`categories`](/slides/python-net/cs/aspose.slides.charts/ichartdata/categories/) | Získá primární kategorie (nebo jak primární, tak sekundární kategorie <br/> pokud je vlastnost [`IChartData.use_secondary_categories`](/slides/python-net/cs/aspose.slides.charts/ichartdata/use_secondary_categories) false).<br/> Pouze pro čtení [`IChartCategoryCollection`](/slides/python-net/cs/aspose.slides.charts/ichartcategorycollection). |
| [`use_secondary_categories`](/slides/python-net/cs/aspose.slides.charts/ichartdata/use_secondary_categories/) | Pokud je false, pak vlastnost [`IChartData.secondary_categories`](/slides/python-net/cs/aspose.slides.charts/ichartdata/secondary_categories) vrátí None a data <br/> ve vlastnosti [`IChartData.categories`](/slides/python-net/cs/aspose.slides.charts/ichartdata/categories) jsou použita jak pro primární, tak pro sekundární řady.<br/> Pokud je true, pak data ve vlastnosti [`IChartData.secondary_categories`](/slides/python-net/cs/aspose.slides.charts/ichartdata/secondary_categories) jsou použita pro sekundární řady a data <br/> ve vlastnosti [`IChartData.categories`](/slides/python-net/cs/aspose.slides.charts/ichartdata/categories) jsou použita pro primární řady.<br/> Čtení/Zápis **bool**. |
| [`secondary_categories`](/slides/python-net/cs/aspose.slides.charts/ichartdata/secondary_categories/) | Získá sekundární kategorie, pokud je vlastnost [`IChartData.use_secondary_categories`](/slides/python-net/cs/aspose.slides.charts/ichartdata/use_secondary_categories) true.<br/> Pouze pro čtení [`IChartCategoryCollection`](/slides/python-net/cs/aspose.slides.charts/ichartcategorycollection). |
| [`data_source_type`](/slides/python-net/cs/aspose.slides.charts/ichartdata/data_source_type/) | Reprezentuje zdroj dat grafu |
| [`external_workbook_path`](/slides/python-net/cs/aspose.slides.charts/ichartdata/external_workbook_path/) | Reprezentuje cestu k externímu sešitu, pokud je zdroj dat externí, jinak None |
| [`embedded_workbook_type`](/slides/python-net/cs/aspose.slides.charts/ichartdata/embedded_workbook_type/) | Získá typ vloženého sešitu.<br/> Vrací [`WorkbookType.NOT_DEFINED`](/slides/python-net/cs/aspose.slides.charts/workbooktype/NOT_DEFINED) pokud je [`IChartData.data_source_type`](/slides/python-net/cs/aspose.slides.charts/ichartdata/data_source_type) <br/> [`ChartDataSourceType.EXTERNAL_WORKBOOK`](/slides/python-net/cs/aspose.slides.charts/chartdatasourcetype/EXTERNAL_WORKBOOK).<br/> Pouze pro čtení [`WorkbookType`](/slides/python-net/cs/aspose.slides.charts/workbooktype). |

## Metody

| Metoda | Popis |
| :- | :- |
| [`set_external_workbook(self, workbook_path)`](/slides/python-net/cs/aspose.slides.charts/ichartdata/set_external_workbook/#str) | Nastaví externí sešit jako zdroj dat pro graf. Data grafu budou aktualizována z cílového sešitu. |
| [`set_external_workbook(self, workbook_path, update_chart_data)`](/slides/python-net/cs/aspose.slides.charts/ichartdata/set_external_workbook/#str-bool) | Nastaví externí sešit jako zdroj dat pro graf. |
| [`read_workbook_stream(self)`](/slides/python-net/cs/aspose.slides.charts/ichartdata/read_workbook_stream/#) | Zapíše interně obsažený Excel sešit do paměťového proudu. |
| [`write_workbook_stream(self, ms)`](/slides/python-net/cs/aspose.slides.charts/ichartdata/write_workbook_stream/#iorawiobase) | Inicializuje interně obsažený Excel sešit uživatelem zadanou hodnotou. |
| [`set_range(self, formula)`](/slides/python-net/cs/aspose.slides.charts/ichartdata/set_range/#str) | Nastaví rozsah dat grafu. Řady a kategorie budou aktualizovány na základě nového rozsahu dat.<br/> Pokud je počet řad v rozsahu dat větší než počet řad v datech grafu, pak budou přidány další řady se stejným typem<br/> jako poslední řada v aktuální kolekci na konec kolekce. |
| [`get_range(self)`](/slides/python-net/cs/aspose.slides.charts/ichartdata/get_range/#) | Získá rozsah dat grafu. |
| [`switch_row_column(self)`](/slides/python-net/cs/aspose.slides.charts/ichartdata/switch_row_column/#) | Prohodí data podél osy.<br/> Data zobrazovaná na ose X se přesunou na osu Y a naopak. |

### Viz také
* modul [`aspose.slides.charts`](/slides/python-net/cs/aspose.slides.charts)
* knihovna [`Aspose.Slides`](/slides/python-net)