---
title: ChartDataWorkbook
type: docs
weight: 0
url: /php-java/chartdataworkbook/
---

# ChartDataWorkbook class

 Provides access to embedded Excel workbook
 

## Methods

| name | return type | description |
| --- | --- | --- |
| [calculateFormulas](/php-java/chartdataworkbook/calculateformulas/)() | void | Calculates all formulas in the workbook and updates corresponding cells values. |
| [clear](/php-java/chartdataworkbook/clear/)(int) | void | Clear all cells values on sheet |
| [getCell](/php-java/chartdataworkbook/getcell/)(String, int, int) | IChartDataCell | Gets the cell that can be used for chart series or categories |
| [getCell](/php-java/chartdataworkbook/getcell/)(int, int, int) | IChartDataCell | Gets the cell that can be used for chart series or categories |
| [getCell](/php-java/chartdataworkbook/getcell/)(int, String) | IChartDataCell | Gets the cell that can be used for chart series or categories |
| [getCell](/php-java/chartdataworkbook/getcell/)(int, String, Object) | IChartDataCell | Gets the cell that can be used for chart series or categories |
| [getCell](/php-java/chartdataworkbook/getcell/)(int, int, int, Object) | IChartDataCell | Gets the cell that can be used for chart series or categories |
| [getCellCollection](/php-java/chartdataworkbook/getcellcollection/)(String, boolean) | IChartCellCollection | Gets the set of cells. |
| [getWorksheets](/php-java/chartdataworkbook/getworksheets/)() | IChartDataWorksheetCollection | Gets a collection of worksheets. |
