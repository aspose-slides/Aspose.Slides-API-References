---
title: StringChartValue class
second_title: Aspose.Slides pro Python přes .NET API Reference
description: 
type: docs
url: /cs/aspose.slides.charts/stringchartvalue/
---
## StringChartValue třída

Represent string value which can be stored in pptx presentation document in two ways:
            1) in cell/cells of workbook related to chart;
            2) as literal value.

**Dědičnost:**[`StringChartValue`](/slides/python-net/cs/aspose.slides.charts/stringchartvalue) → [`BaseChartValue`](/slides/python-net/cs/aspose.slides.charts/basechartvalue)

Typ StringChartValue poskytuje následující členy:

## Vlastnosti

| Vlastnost | Popis |
| :- | :- |
| [`data_source_type`](/slides/python-net/cs/aspose.slides.charts/stringchartvalue/data_source_type/) | Určuje, zda je vlastnost AsCell, AsCells, AsLiteralString nebo AsLiteralDouble <br/>            ve potomcích aktuální. Jinými slovy určuje typ <br/>            hodnoty vlastnosti Data.<br/>            Číst/zapisovat [`DataSourceType`](/slides/python-net/cs/aspose.slides.charts/datasourcetype). |
| [`data`](/slides/python-net/cs/aspose.slides.charts/stringchartvalue/data/) | Vrací nebo nastavuje objekt Data.<br/>            Číst/zapisovat **any**. |
| [`as_cells`](/slides/python-net/cs/aspose.slides.charts/stringchartvalue/as_cells/) | Přiřazení nulové hodnoty není povoleno.<br/>            Vrácená hodnota není nikdy None.<br/>            Číst/zapisovat [`IChartCellCollection`](/slides/python-net/cs/aspose.slides.charts/ichartcellcollection). |
| [`as_literal_string`](/slides/python-net/cs/aspose.slides.charts/stringchartvalue/as_literal_string/) | Vrací nebo nastavuje hodnotu jako literální řetězec.<br/>            Číst/zapisovat **str**. |

## Metody

| Metoda | Popis |
| :- | :- |
| [`set_from_one_cell(self, cell)`](/slides/python-net/cs/aspose.slides.charts/stringchartvalue/set_from_one_cell/#ichartdatacell) | Nastaví hodnotu ze specifikované buňky. |
| [`get_cells_address_in_workbook(self)`](/slides/python-net/cs/aspose.slides.charts/stringchartvalue/get_cells_address_in_workbook/#) | Pokud je vlastnost DataSourceType rovna DataSourceType.Worksheet, pak tato metoda vrátí adresu<br/>            buněk v sešitu, které představují řetězcová data. V opačném případě vrátí<br/>            prázdný řetězec. |

### Viz také
* třída [`BaseChartValue`](/slides/python-net/cs/aspose.slides.charts/basechartvalue)
* třída [`StringChartValue`](/slides/python-net/cs/aspose.slides.charts/stringchartvalue)
* modul [`aspose.slides.charts`](/slides/python-net/cs/aspose.slides.charts)
* knihovna [`Aspose.Slides`](/slides/python-net)