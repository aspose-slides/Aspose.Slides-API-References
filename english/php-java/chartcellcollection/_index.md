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
| [add](/php-java/chartcellcollection/add/)(IChartDataCell) | void | Add new cell to the collection. |
| [add](/php-java/chartcellcollection/add/)(Object) | void | Creates ChartDataCell from specified value and adds it to the collection. |
| [getCellsAddress](/php-java/chartcellcollection/getcellsaddress/)() | String | Returns address of the set of cells in workbook. |
| [getConcatenatedValuesFromCells](/php-java/chartcellcollection/getconcatenatedvaluesfromcells/)() | String | Concatenation string from all cells string values. |
| [getCount](/php-java/chartcellcollection/getcount/)() | int | Gets the count of cells in collection. Read-only int. |
| [get_Item](/php-java/chartcellcollection/get_item/)(int) | IChartDataCell | Returns a cell (IChartDataCell) by index. |
| [iterator](/php-java/chartcellcollection/iterator/)() | IGenericEnumerator | Returns an enumerator that iterates through the collection. |
| [iteratorJava](/php-java/chartcellcollection/iteratorjava/)() | IGenericEnumerator | Returns a java iterator for the entire collection. |
| [removeAt](/php-java/chartcellcollection/removeat/)(int) | void | Removes a cell from the collection by index. |
