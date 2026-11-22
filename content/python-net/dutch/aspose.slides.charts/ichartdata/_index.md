---
title: IChartData class
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides.charts/ichartdata/
---
## IChartData klasse

Stelt gegevens voor die worden gebruikt voor het plotten van een diagram.

Het IChartData-type bevat de volgende leden:

## Eigenschappen

| Eigenschap | Beschrijving |
| :- | :- |
| [`chart_data_workbook`](/slides/python-net/nl/aspose.slides.charts/ichartdata/chart_data_workbook/) | Haalt de cellenfabriek op om cellen te maken die worden gebruikt voor diagramreeksen of -categorieën.<br/>            Alleen-lezen [`IChartDataWorkbook`](/slides/python-net/nl/aspose.slides.charts/ichartdataworkbook). |
| [`series`](/slides/python-net/nl/aspose.slides.charts/ichartdata/series/) | Haalt de reeksen op.<br/>            Alleen-lezen [`IChartSeriesCollection`](/slides/python-net/nl/aspose.slides.charts/ichartseriescollection). |
| [`series_groups`](/slides/python-net/nl/aspose.slides.charts/ichartdata/series_groups/) | Haalt de groepen van reeksen op.<br/>            Alleen-lezen [`IChartSeriesGroupCollection`](/slides/python-net/nl/aspose.slides.charts/ichartseriesgroupcollection). |
| [`categories`](/slides/python-net/nl/aspose.slides.charts/ichartdata/categories/) | Haalt de primaire categorieën op (of zowel primaire als secundaire categorieën <br/>            als eigenschap [`IChartData.use_secondary_categories`](/slides/python-net/nl/aspose.slides.charts/ichartdata/use_secondary_categories) false is).<br/>            Alleen-lezen [`IChartCategoryCollection`](/slides/python-net/nl/aspose.slides.charts/ichartcategorycollection). |
| [`use_secondary_categories`](/slides/python-net/nl/aspose.slides.charts/ichartdata/use_secondary_categories/) | Als false dan geeft eigenschap [`IChartData.secondary_categories`](/slides/python-net/nl/aspose.slides.charts/ichartdata/secondary_categories) None terug en worden gegevens <br/>            in eigenschap [`IChartData.categories`](/slides/python-net/nl/aspose.slides.charts/ichartdata/categories) zowel voor primaire als secundaire reeksen gebruikt.<br/>            Als true dan worden gegevens in eigenschap [`IChartData.secondary_categories`](/slides/python-net/nl/aspose.slides.charts/ichartdata/secondary_categories) gebruikt voor secundaire reeksen en gegevens <br/>            in eigenschap [`IChartData.categories`](/slides/python-net/nl/aspose.slides.charts/ichartdata/categories) voor primaire reeksen.<br/>            Lezen/Schrijven **bool**. |
| [`secondary_categories`](/slides/python-net/nl/aspose.slides.charts/ichartdata/secondary_categories/) | Haalt de secundaire categorieën op als eigenschap [`IChartData.use_secondary_categories`](/slides/python-net/nl/aspose.slides.charts/ichartdata/use_secondary_categories) true is.<br/>            Alleen-lezen [`IChartCategoryCollection`](/slides/python-net/nl/aspose.slides.charts/ichartcategorycollection). |
| [`data_source_type`](/slides/python-net/nl/aspose.slides.charts/ichartdata/data_source_type/) | Vertegenwoordigt de gegevensbron van het diagram |
| [`external_workbook_path`](/slides/python-net/nl/aspose.slides.charts/ichartdata/external_workbook_path/) | Vertegenwoordigt het pad naar een extern werkboek als gegevensbron extern is, anders None |
| [`embedded_workbook_type`](/slides/python-net/nl/aspose.slides.charts/ichartdata/embedded_workbook_type/) | Haalt het type van het ingesloten werkboek op.<br/>            Retourneert [`WorkbookType.NOT_DEFINED`](/slides/python-net/nl/aspose.slides.charts/workbooktype/NOT_DEFINED) als [`IChartData.data_source_type`](/slides/python-net/nl/aspose.slides.charts/ichartdata/data_source_type) is <br/>            [`ChartDataSourceType.EXTERNAL_WORKBOOK`](/slides/python-net/nl/aspose.slides.charts/chartdatasourcetype/EXTERNAL_WORKBOOK).<br/>            Alleen-lezen [`WorkbookType`](/slides/python-net/nl/aspose.slides.charts/workbooktype). |

## Methoden

| Methode | Beschrijving |
| :- | :- |
| [`set_external_workbook(self, workbook_path)`](/slides/python-net/nl/aspose.slides.charts/ichartdata/set_external_workbook/#str) | Stelt extern werkboek in als gegevensbron voor het diagram. Diagramgegevens worden bijgewerkt vanuit het doelwerkboek. |
| [`set_external_workbook(self, workbook_path, update_chart_data)`](/slides/python-net/nl/aspose.slides.charts/ichartdata/set_external_workbook/#str-bool) | Stelt extern werkboek in als gegevensbron voor het diagram. |
| [`read_workbook_stream(self)`](/slides/python-net/nl/aspose.slides.charts/ichartdata/read_workbook_stream/#) | Schrijft het intern aanwezige Excel-werkboek naar een in-memory-stream. |
| [`write_workbook_stream(self, ms)`](/slides/python-net/nl/aspose.slides.charts/ichartdata/write_workbook_stream/#iorawiobase) | Initialiseert het intern aanwezige Excel-werkboek met een door gebruiker opgegeven waarde. |
| [`set_range(self, formula)`](/slides/python-net/nl/aspose.slides.charts/ichartdata/set_range/#str) | Stel het diagramgegevensbereik in. Reeksen en categorieën worden bijgewerkt op basis van het nieuwe gegevensbereik.<br/>            Als het aantal reeksen in het gegevensbereik groter is dan het aantal reeksen in de diagramgegevens, dan worden extra reeksen met hetzelfde type<br/>            als de laatste reeks in de huidige collectie aan het einde van de collectie toegevoegd. |
| [`get_range(self)`](/slides/python-net/nl/aspose.slides.charts/ichartdata/get_range/#) | Haalt het diagramgegevensbereik op. |
| [`switch_row_column(self)`](/slides/python-net/nl/aspose.slides.charts/ichartdata/switch_row_column/#) | Verwissel de gegevens over de as.<br/>            Gegevens die op de X-as worden geplot, verplaatsen naar de Y-as en omgekeerd. |
| [`refresh_data(self)`](/slides/python-net/nl/aspose.slides.charts/ichartdata/refresh_data/#) | Vernieuwt de diagramgegevens door ze opnieuw te laden vanaf het bronwerkboek. |


### Zie ook
* module [`aspose.slides.charts`](/slides/python-net/nl/aspose.slides.charts)
* bibliotheek [`Aspose.Slides`](/slides/python-net)