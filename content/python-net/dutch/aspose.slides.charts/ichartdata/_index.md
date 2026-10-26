---
title: IChartData class
second_title: Aspose.Slides voor Python via .NET API Referentie
description: 
type: docs
url: /nl/aspose.slides.charts/ichartdata/
---
## IChartData klasse

Stelt gegevens voor die worden gebruikt voor het plotten van een diagram.

Het IChartData-type geeft de volgende leden weer:

## Eigenschappen

| Property | Beschrijving |
| :- | :- |
| [`chart_data_workbook`](/slides/python-net/nl/aspose.slides.charts/ichartdata/chart_data_workbook/) | Verkrijgt de cellenfactory om cellen te maken die worden gebruikt voor grafiekreeksen of categorieën.<br/>            Alleen-lezen [`IChartDataWorkbook`](/slides/python-net/nl/aspose.slides.charts/ichartdataworkbook). |
| [`series`](/slides/python-net/nl/aspose.slides.charts/ichartdata/series/) | Verkrijgt de series.<br/>            Alleen-lezen [`IChartSeriesCollection`](/slides/python-net/nl/aspose.slides.charts/ichartseriescollection). |
| [`series_groups`](/slides/python-net/nl/aspose.slides.charts/ichartdata/series_groups/) | Verkrijgt de groepen van series.<br/>            Alleen-lezen [`IChartSeriesGroupCollection`](/slides/python-net/nl/aspose.slides.charts/ichartseriesgroupcollection). |
| [`categories`](/slides/python-net/nl/aspose.slides.charts/ichartdata/categories/) | Verkrijgt de primaire categorieën (of zowel primaire als secundaire categorieën <br/>            als de eigenschap [`IChartData.use_secondary_categories`](/slides/python-net/nl/aspose.slides.charts/ichartdata/use_secondary_categories) onwaar is).<br/>            Alleen-lezen [`IChartCategoryCollection`](/slides/python-net/nl/aspose.slides.charts/ichartcategorycollection). |
| [`use_secondary_categories`](/slides/python-net/nl/aspose.slides.charts/ichartdata/use_secondary_categories/) | Als onwaar, retourneert de eigenschap [`IChartData.secondary_categories`](/slides/python-net/nl/aspose.slides.charts/ichartdata/secondary_categories) None en worden gegevens <br/>            in de eigenschap [`IChartData.categories`](/slides/python-net/nl/aspose.slides.charts/ichartdata/categories) gebruikt voor zowel primaire als secundaire series.<br/>            Als waar, worden gegevens in de eigenschap [`IChartData.secondary_categories`](/slides/python-net/nl/aspose.slides.charts/ichartdata/secondary_categories) gebruikt voor secundaire series en gegevens <br/>            in de eigenschap [`IChartData.categories`](/slides/python-net/nl/aspose.slides.charts/ichartdata/categories) gebruikt voor primaire series.<br/>            Lezen/Schrijven **bool**. |
| [`secondary_categories`](/slides/python-net/nl/aspose.slides.charts/ichartdata/secondary_categories/) | Verkrijgt de secundaire categorieën als de eigenschap [`IChartData.use_secondary_categories`](/slides/python-net/nl/aspose.slides.charts/ichartdata/use_secondary_categories) waar is.<br/>            Alleen-lezen [`IChartCategoryCollection`](/slides/python-net/nl/aspose.slides.charts/ichartcategorycollection). |
| [`data_source_type`](/slides/python-net/nl/aspose.slides.charts/ichartdata/data_source_type/) | Stelt de gegevensbron van het diagram voor |
| [`external_workbook_path`](/slides/python-net/nl/aspose.slides.charts/ichartdata/external_workbook_path/) | Stelt het pad naar een extern werkboek voor als de gegevensbron extern is, anders None |
| [`embedded_workbook_type`](/slides/python-net/nl/aspose.slides.charts/ichartdata/embedded_workbook_type/) | Verkrijgt het type van het ingebedde werkboek.<br/>            Retourneert [`WorkbookType.NOT_DEFINED`](/slides/python-net/nl/aspose.slides.charts/workbooktype/NOT_DEFINED) als [`IChartData.data_source_type`](/slides/python-net/nl/aspose.slides.charts/ichartdata/data_source_type) <br/>            [`ChartDataSourceType.EXTERNAL_WORKBOOK`](/slides/python-net/nl/aspose.slides.charts/chartdatasourcetype/EXTERNAL_WORKBOOK) is.<br/>            Alleen-lezen [`WorkbookType`](/slides/python-net/nl/aspose.slides.charts/workbooktype). |

## Methoden

| Method | Beschrijving |
| :- | :- |
| [`set_external_workbook(self, workbook_path)`](/slides/python-net/nl/aspose.slides.charts/ichartdata/set_external_workbook/#str) | Stelt een extern werkboek in als gegevensbron voor het diagram. Diagramgegevens worden bijgewerkt vanuit het doelwerkboek. |
| [`set_external_workbook(self, workbook_path, update_chart_data)`](/slides/python-net/nl/aspose.slides.charts/ichartdata/set_external_workbook/#str-bool) | Stelt een extern werkboek in als gegevensbron voor het diagram. |
| [`read_workbook_stream(self)`](/slides/python-net/nl/aspose.slides.charts/ichartdata/read_workbook_stream/#) | Schrijft het intern ingesloten Excel-werkboek naar een in-memory-stroom. |
| [`write_workbook_stream(self, ms)`](/slides/python-net/nl/aspose.slides.charts/ichartdata/write_workbook_stream/#iorawiobase) | Initialiseert het intern ingesloten Excel-werkboek met een door de gebruiker opgegeven waarde. |
| [`set_range(self, formula)`](/slides/python-net/nl/aspose.slides.charts/ichartdata/set_range/#str) | Stel het gegevensbereik van het diagram in. Series en categorieën worden bijgewerkt op basis van het nieuwe gegevensbereik.<br/>            Als het aantal series in het gegevensbereik groter is dan het aantal series in de diagramgegevens, dan worden extra series met hetzelfde type<br/>            als de laatste series in de huidige collectie aan het einde van de collectie toegevoegd. |
| [`get_range(self)`](/slides/python-net/nl/aspose.slides.charts/ichartdata/get_range/#) | Verkrijgt het gegevensbereik van het diagram. |
| [`switch_row_column(self)`](/slides/python-net/nl/aspose.slides.charts/ichartdata/switch_row_column/#) | Verwissel de gegevens over de as.<br/>            Gegevens die op de X-as worden geplot, worden verplaatst naar de Y-as en omgekeerd. |

### Zie ook
* module [`aspose.slides.charts`](/slides/python-net/nl/aspose.slides.charts)
* bibliotheek [`Aspose.Slides`](/slides/python-net)