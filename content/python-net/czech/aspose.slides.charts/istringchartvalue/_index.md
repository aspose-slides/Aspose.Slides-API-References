---
title: IStringChartValue class
second_title: Aspose.Slides pro Python přes .NET API referenci
description: 
type: docs
url: /cs/aspose.slides.charts/istringchartvalue/
---
## IStringChartValue třída

Reprezentuje řetězcovou hodnotu, která může být uložena v dokumentu prezentace pptx dvěma způsoby:
            1) v buňce/buňkách sešitu souvisejícího s grafem;
            2) jako doslovná hodnota.

Typ IStringChartValue exponuje následující členy:

## Vlastnosti

| Property | Popis |
| :- | :- |
| [`as_literal_string`](/slides/python-net/cs/aspose.slides.charts/istringchartvalue/as_literal_string/) | Vrací nebo nastavuje doslovný řetězec, pokud je vlastnost DataSourceType rovna DataSourceType.StringLiterals.<br/>            Číst/zapisovat **str**. |
| [`as_cells`](/slides/python-net/cs/aspose.slides.charts/istringchartvalue/as_cells/) |  |
| [`data_source_type`](/slides/python-net/cs/aspose.slides.charts/istringchartvalue/data_source_type/) |  |
| [`data`](/slides/python-net/cs/aspose.slides.charts/istringchartvalue/data/) |  |

## Metody

| Method | Popis |
| :- | :- |
| [`to_string(self)`](/slides/python-net/cs/aspose.slides.charts/istringchartvalue/to_string/#) | Vrací řetězcovou reprezentaci. |
| [`set_from_one_cell(self, cell)`](/slides/python-net/cs/aspose.slides.charts/istringchartvalue/set_from_one_cell/#ichartdatacell) | Nastavuje hodnotu z určené buňky. |
| [`get_cells_address_in_workbook(self)`](/slides/python-net/cs/aspose.slides.charts/istringchartvalue/get_cells_address_in_workbook/#) | Pokud je vlastnost DataSourceType rovna DataSourceType.Worksheet, tato metoda vrací adresu buněk v sešitu, které představují řetězcová data. Jinak vrátí prázdný řetězec. |

### Viz také
* modul [`aspose.slides.charts`](/slides/python-net/cs/aspose.slides.charts)
* knihovna [`Aspose.Slides`](/slides/python-net)