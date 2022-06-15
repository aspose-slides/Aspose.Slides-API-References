---
title: ChartCellCollection
type: docs
weight: 0
url: /php-java/chartcellcollection/
---

# ChartCellCollection class

 Represents collection of a cells with data.
 

## Methods

| name | return type | description |
| --- | --- | --- |
| [add](/slides/php-java/chartcellcollection/add/)(IChartDataCell) | void | Add new cell to the collection. |
| [add](/slides/php-java/chartcellcollection/add/)(Object) | void | Creates ChartDataCell from specified value and adds it to the collection. |
| [getCellsAddress](/slides/php-java/chartcellcollection/getcellsaddress/)() | String | Returns address of the set of cells in workbook. |
| [getConcatenatedValuesFromCells](/slides/php-java/chartcellcollection/getconcatenatedvaluesfromcells/)() | String | Concatenation string from all cells string values. |
| [getCount](/slides/php-java/chartcellcollection/getcount/)() | int | Gets the count of cells in collection. Read-only int. |
| [get_Item](/slides/php-java/chartcellcollection/get_item/)(int) | IChartDataCell | Returns a cell (IChartDataCell) by index. |
| [iterator](/slides/php-java/chartcellcollection/iterator/)() | IGenericEnumerator | Returns an enumerator that iterates through the collection. |
| [iteratorJava](/slides/php-java/chartcellcollection/iteratorjava/)() | IGenericEnumerator | Returns a java iterator for the entire collection. |
| [removeAt](/slides/php-java/chartcellcollection/removeat/)(int) | void | Removes a cell from the collection by index. |
