---
title: ChartData class
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides.charts/chartdata/
---
## ChartData klasse

Stelt de gegevens voor die worden gebruikt voor het plotten van een diagram.

Het type ChartData stelt de volgende leden beschikbaar:

## Eigenschappen

| Eigenschap | Beschrijving |
| :- | :- |
| [`chart_data_workbook`](/slides/python-net/nl/aspose.slides.charts/chartdata/chart_data_workbook/) | Verkrijgt de cellenfabriek om cellen te maken die worden gebruikt voor diagramreeksen of categorieën.<br/>            Alleen-lezen [`IChartDataWorkbook`](/slides/python-net/nl/aspose.slides.charts/ichartdataworkbook). |
| [`series`](/slides/python-net/nl/aspose.slides.charts/chartdata/series/) | Verkrijgt de reeksen.<br/>            Alleen-lezen [`IChartSeriesCollection`](/slides/python-net/nl/aspose.slides.charts/ichartseriescollection). |
| [`series_groups`](/slides/python-net/nl/aspose.slides.charts/chartdata/series_groups/) | Verkrijgt de groepen van reeksen.<br/>            Alleen-lezen [`IChartSeriesGroupCollection`](/slides/python-net/nl/aspose.slides.charts/ichartseriesgroupcollection). |
| [`categories`](/slides/python-net/nl/aspose.slides.charts/chartdata/categories/) | Verkrijgt de primaire categorieën (of zowel primaire als secundaire categorieën <br/>            als de eigenschap [`ChartData.use_secondary_categories`](/slides/python-net/nl/aspose.slides.charts/chartdata/use_secondary_categories) onwaar is).<br/>            Alleen-lezen [`IChartCategoryCollection`](/slides/python-net/nl/aspose.slides.charts/ichartcategorycollection). |
| [`use_secondary_categories`](/slides/python-net/nl/aspose.slides.charts/chartdata/use_secondary_categories/) | Als onwaar dan retourneert de eigenschap [`ChartData.secondary_categories`](/slides/python-net/nl/aspose.slides.charts/chartdata/secondary_categories) None en worden gegevens <br/>            in de eigenschap [`ChartData.categories`](/slides/python-net/nl/aspose.slides.charts/chartdata/categories) gebruikt voor zowel primaire als secundaire reeksen.<br/>            Als waar dan worden gegevens in de eigenschap [`ChartData.secondary_categories`](/slides/python-net/nl/aspose.slides.charts/chartdata/secondary_categories) gebruikt voor secundaire reeksen en gegevens <br/>            in de eigenschap [`ChartData.categories`](/slides/python-net/nl/aspose.slides.charts/chartdata/categories) gebruikt voor primaire reeksen.<br/>            Lezen/Schrijven **bool**. |
| [`secondary_categories`](/slides/python-net/nl/aspose.slides.charts/chartdata/secondary_categories/) | Verkrijgt de secundaire categorieën als de eigenschap [`ChartData.use_secondary_categories`](/slides/python-net/nl/aspose.slides.charts/chartdata/use_secondary_categories) waar is.<br/>            Alleen-lezen [`IChartCategoryCollection`](/slides/python-net/nl/aspose.slides.charts/ichartcategorycollection). |
| [`data_source_type`](/slides/python-net/nl/aspose.slides.charts/chartdata/data_source_type/) | Stelt het pad naar extern werkboek voor als externe gegevensbron, anders None |
| [`external_workbook_path`](/slides/python-net/nl/aspose.slides.charts/chartdata/external_workbook_path/) | Stelt de gegevensbron van het diagram voor |
| [`embedded_workbook_type`](/slides/python-net/nl/aspose.slides.charts/chartdata/embedded_workbook_type/) | Verkrijgt het type van het ingebedde werkboek.<br/>            Retourneert [`WorkbookType.NOT_DEFINED`](/slides/python-net/nl/aspose.slides.charts/workbooktype/NOT_DEFINED) als [`ChartData.data_source_type`](/slides/python-net/nl/aspose.slides.charts/chartdata/data_source_type) <br/>            [`ChartDataSourceType.EXTERNAL_WORKBOOK`](/slides/python-net/nl/aspose.slides.charts/chartdatasourcetype/EXTERNAL_WORKBOOK).<br/>            Alleen-lezen [`WorkbookType`](/slides/python-net/nl/aspose.slides.charts/workbooktype). |

## Methoden

| Methode | Beschrijving |
| :- | :- |
| [`set_external_workbook(self, workbook_path)`](/slides/python-net/nl/aspose.slides.charts/chartdata/set_external_workbook/#str) | Stelt extern werkboek in als gegevensbron voor het diagram. Diagramgegevens worden bijgewerkt vanuit het doelwerkboek. |
| [`set_external_workbook(self, workbook_path, update_chart_data)`](/slides/python-net/nl/aspose.slides.charts/chartdata/set_external_workbook/#str-bool) | Stelt extern werkboek in als gegevensbron voor het diagram. |
| [`read_workbook_stream(self)`](/slides/python-net/nl/aspose.slides.charts/chartdata/read_workbook_stream/#) | Schrijft het intern ingesloten Excel-werkboek naar een stream. |
| [`write_workbook_stream(self, ms)`](/slides/python-net/nl/aspose.slides.charts/chartdata/write_workbook_stream/#iorawiobase) | Initialiseert het intern ingesloten Excel-werkboek met door de gebruiker gespecificeerde waarde. |
| [`get_range(self)`](/slides/python-net/nl/aspose.slides.charts/chartdata/get_range/#) | Verkrijgt het gegevensbereik van het diagram. |
| [`set_range(self, formula)`](/slides/python-net/nl/aspose.slides.charts/chartdata/set_range/#str) | Stel het gegevensbereik van het diagram in. Reeksen en categorieën worden bijgewerkt op basis van het nieuwe gegevensbereik.<br/>            Als het aantal reeksen in het gegevensbereik groter is dan het aantal reeksen in de diagramgegevens, dan worden extra reeksen met hetzelfde type<br/>            als de laatste reeks in de huidige collectie aan het einde van de collectie toegevoegd. |
| [`switch_row_column(self)`](/slides/python-net/nl/aspose.slides.charts/chartdata/switch_row_column/#) | Wissel de gegevens over de as.<br/>            Gegevens die op de X-as worden geplot, verplaatsen zich naar de Y-as en omgekeerd. |

### Zie ook
* module [`aspose.slides.charts`](/slides/python-net/nl/aspose.slides.charts)
* bibliotheek [`Aspose.Slides`](/slides/python-net)