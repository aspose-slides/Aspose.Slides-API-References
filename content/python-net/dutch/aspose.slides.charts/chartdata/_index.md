---
title: ChartData class
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides.charts/chartdata/
---
## ChartData klasse

Stelt gegevens voor die worden gebruikt voor het plotten van een grafiek.

Het ChartData-type maakt de volgende leden beschikbaar:

## Eigenschappen

| Eigenschap | Beschrijving |
| :- | :- |
| [`chart_data_workbook`](/slides/python-net/nl/aspose.slides.charts/chartdata/chart_data_workbook/) | Haalt de cellenfactory op om cellen te maken die worden gebruikt voor grafiekreeksen of -categorieën.<br/>            Alleen-lezen [`IChartDataWorkbook`](/slides/python-net/nl/aspose.slides.charts/ichartdataworkbook). |
| [`series`](/slides/python-net/nl/aspose.slides.charts/chartdata/series/) | Haalt de series op.<br/>            Alleen-lezen [`IChartSeriesCollection`](/slides/python-net/nl/aspose.slides.charts/ichartseriescollection). |
| [`series_groups`](/slides/python-net/nl/aspose.slides.charts/chartdata/series_groups/) | Haalt de groepen van series op.<br/>            Alleen-lezen [`IChartSeriesGroupCollection`](/slides/python-net/nl/aspose.slides.charts/ichartseriesgroupcollection). |
| [`categories`](/slides/python-net/nl/aspose.slides.charts/chartdata/categories/) | Haalt de primaire categorieën op (of zowel primaire als secundaire categorieën als de eigenschap [`ChartData.use_secondary_categories`](/slides/python-net/nl/aspose.slides.charts/chartdata/use_secondary_categories) onwaar is).<br/>            Alleen-lezen [`IChartCategoryCollection`](/slides/python-net/nl/aspose.slides.charts/ichartcategorycollection). |
| [`use_secondary_categories`](/slides/python-net/nl/aspose.slides.charts/chartdata/use_secondary_categories/) | Als onwaar dan retourneert de eigenschap [`ChartData.secondary_categories`](/slides/python-net/nl/aspose.slides.charts/chartdata/secondary_categories) None en worden de gegevens in de eigenschap [`ChartData.categories`](/slides/python-net/nl/aspose.slides.charts/chartdata/categories) zowel voor primaire als secundaire series gebruikt.<br/>            Als waar dan worden de gegevens in de eigenschap [`ChartData.secondary_categories`](/slides/python-net/nl/aspose.slides.charts/chartdata/secondary_categories) gebruikt voor secundaire series en de gegevens in de eigenschap [`ChartData.categories`](/slides/python-net/nl/aspose.slides.charts/chartdata/categories) worden gebruikt voor primaire series.<br/>            Lezen/Schrijven **bool**. |
| [`secondary_categories`](/slides/python-net/nl/aspose.slides.charts/chartdata/secondary_categories/) | Haalt de secundaire categorieën op als de eigenschap [`ChartData.use_secondary_categories`](/slides/python-net/nl/aspose.slides.charts/chartdata/use_secondary_categories) waar is.<br/>            Alleen-lezen [`IChartCategoryCollection`](/slides/python-net/nl/aspose.slides.charts/ichartcategorycollection). |
| [`data_source_type`](/slides/python-net/nl/aspose.slides.charts/chartdata/data_source_type/) | Geeft het externe werkmappad weer als externe gegevensbron, anders None |
| [`external_workbook_path`](/slides/python-net/nl/aspose.slides.charts/chartdata/external_workbook_path/) | Geeft de gegevensbron van de grafiek weer |
| [`embedded_workbook_type`](/slides/python-net/nl/aspose.slides.charts/chartdata/embedded_workbook_type/) | Haalt het type van de ingesloten werkmap op.<br/>            Retourneert [`WorkbookType.NOT_DEFINED`](/slides/python-net/nl/aspose.slides.charts/workbooktype/NOT_DEFINED) als [`ChartData.data_source_type`](/slides/python-net/nl/aspose.slides.charts/chartdata/data_source_type) is <br/>            [`ChartDataSourceType.EXTERNAL_WORKBOOK`](/slides/python-net/nl/aspose.slides.charts/chartdatasourcetype/EXTERNAL_WORKBOOK).<br/>            Alleen-lezen [`WorkbookType`](/slides/python-net/nl/aspose.slides.charts/workbooktype). |

## Methoden

| Methode | Beschrijving |
| :- | :- |
| [`set_external_workbook(self, workbook_path)`](/slides/python-net/nl/aspose.slides.charts/chartdata/set_external_workbook/#str) | Stelt de externe werkmap in als gegevensbron voor de grafiek. Grafiekgegevens worden bijgewerkt vanuit de doelwerkmap. |
| [`set_external_workbook(self, workbook_path, update_chart_data)`](/slides/python-net/nl/aspose.slides.charts/chartdata/set_external_workbook/#str-bool) | Stelt de externe werkmap in als gegevensbron voor de grafiek. |
| [`read_workbook_stream(self)`](/slides/python-net/nl/aspose.slides.charts/chartdata/read_workbook_stream/#) | Schrijft de intern aanwezige Excel-werkmap naar een stream. |
| [`write_workbook_stream(self, ms)`](/slides/python-net/nl/aspose.slides.charts/chartdata/write_workbook_stream/#iorawiobase) | Initialiseert de intern aanwezige Excel-werkmap met een door de gebruiker opgegeven waarde. |
| [`get_range(self)`](/slides/python-net/nl/aspose.slides.charts/chartdata/get_range/#) | Haalt het gegevensbereik van de grafiek op. |
| [`set_range(self, formula)`](/slides/python-net/nl/aspose.slides.charts/chartdata/set_range/#str) | Stel het gegevensbereik van de grafiek in. Series en categorieën worden bijgewerkt op basis van het nieuwe gegevensbereik.<br/>            Als het aantal series in het gegevensbereik groter is dan het aantal series in de grafiekgegevens, dan worden extra series met hetzelfde type als de laatste serie in de huidige collectie aan het einde van de collectie toegevoegd. |
| [`refresh_data(self)`](/slides/python-net/nl/aspose.slides.charts/chartdata/refresh_data/#) | Ververs de grafiekgegevens door ze opnieuw te laden vanuit de bronwerkmap. |
| [`switch_row_column(self)`](/slides/python-net/nl/aspose.slides.charts/chartdata/switch_row_column/#) | Wissel de gegevens over de assen.<br/>            Gegevens die op de X-as worden geplot, worden verplaatst naar de Y-as en omgekeerd. |


### Zie ook
* module [`aspose.slides.charts`](/slides/python-net/nl/aspose.slides.charts)
* library [`Aspose.Slides`](/slides/python-net)