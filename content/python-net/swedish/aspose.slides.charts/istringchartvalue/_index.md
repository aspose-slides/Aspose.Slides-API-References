---
title: IStringChartValue class
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.charts/istringchartvalue/
---
## IStringChartValue klass

Representerar strängvärde som kan lagras i pptx-presentationsdokument på två sätt:
1) i cell/er i arbetsbok relaterad till diagram;
2) som bokstavligt värde.

IStringChartValue-typen exponerar följande medlemmar:

## Egenskaper

| Egenskap | Beskrivning |
| :- | :- |
| [`as_literal_string`](/slides/python-net/sv/aspose.slides.charts/istringchartvalue/as_literal_string/) | Returnerar eller anger den bokstavliga strängen om egenskapen DataSourceType är DataSourceType.StringLiterals.<br/>Läsa/skriva **str**. |
| [`as_cells`](/slides/python-net/sv/aspose.slides.charts/istringchartvalue/as_cells/) |  |
| [`data_source_type`](/slides/python-net/sv/aspose.slides.charts/istringchartvalue/data_source_type/) |  |
| [`data`](/slides/python-net/sv/aspose.slides.charts/istringchartvalue/data/) |  |

## Metoder

| Metod | Beskrivning |
| :- | :- |
| [`to_string(self)`](/slides/python-net/sv/aspose.slides.charts/istringchartvalue/to_string/#) | Returnerar strängrepresentation. |
| [`set_from_one_cell(self, cell)`](/slides/python-net/sv/aspose.slides.charts/istringchartvalue/set_from_one_cell/#ichartdatacell) | Anger värdet från angiven cell. |
| [`get_cells_address_in_workbook(self)`](/slides/python-net/sv/aspose.slides.charts/istringchartvalue/get_cells_address_in_workbook/#) | Om egenskapen DataSourceType är DataSourceType.Worksheet returnerar denna metod adressen till cellerna i arbetsboken som representerar strängdata.<br/>Annars returneras en tom sträng. |

### Se även
* modul [`aspose.slides.charts`](/slides/python-net/sv/aspose.slides.charts)
* bibliotek [`Aspose.Slides`](/slides/python-net)