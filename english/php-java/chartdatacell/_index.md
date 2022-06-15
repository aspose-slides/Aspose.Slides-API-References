---
title: ChartDataCell
type: docs
weight: 0
url: /php-java/chartdatacell/
---

# ChartDataCell class

 Represents cell for chart data.
 

## Methods

| name | return type | description |
| --- | --- | --- |
| [calculate](/slides/php-java/chartdatacell/calculate/)(boolean) | void | If the cell contains a formula, the value will be updated base on that formula. |
| [getChartDataWorksheet](/slides/php-java/chartdatacell/getchartdataworksheet/)() | IChartDataWorksheet | Gets the worksheet. Read-only IChartDataWorksheet. |
| [getColumn](/slides/php-java/chartdatacell/getcolumn/)() | int | Returns the index of the column of worksheet in which the cell is located. Read-only int. |
| [getCustomNumberFormat](/slides/php-java/chartdatacell/getcustomnumberformat/)() | String | Gets or sets the custom display format of numbers and dates. If value is empty will be used PresetNumberFormat value. Read/write String. |
| [getFormula](/slides/php-java/chartdatacell/getformula/)() | String | Gets or sets the formula in A1-style. |
| [getPresetNumberFormat](/slides/php-java/chartdatacell/getpresetnumberformat/)() | byte | Gets or sets the built-in display format of numbers and dates. Preset number must be in [0..22] or [37..49]". Read/write byte. |
| [getR1C1Formula](/slides/php-java/chartdatacell/getr1c1formula/)() | String | Gets or sets the formula in R1C1-style. |
| [getRow](/slides/php-java/chartdatacell/getrow/)() | int | Returns the index of the row of worksheet in which the cell is located. Read-only int. |
| [getValue](/slides/php-java/chartdatacell/getvalue/)() | Object | Gets or sets the value. Read/write Object. |
| [isHidden](/slides/php-java/chartdatacell/ishidden/)() | boolean | Determines whether the cell is hidden. Read-only boolean. |
| [setCustomNumberFormat](/slides/php-java/chartdatacell/setcustomnumberformat/)(String) | void | Gets or sets the custom display format of numbers and dates. If value is empty will be used PresetNumberFormat value. Read/write String. |
| [setFormula](/slides/php-java/chartdatacell/setformula/)(String) | void | Gets or sets the formula in A1-style. |
| [setPresetNumberFormat](/slides/php-java/chartdatacell/setpresetnumberformat/)(byte) | void | Gets or sets the built-in display format of numbers and dates. Preset number must be in [0..22] or [37..49]". Read/write byte. |
| [setR1C1Formula](/slides/php-java/chartdatacell/setr1c1formula/)(String) | void | Gets or sets the formula in R1C1-style. |
| [setValue](/slides/php-java/chartdatacell/setvalue/)(Object) | void | Gets or sets the value. Read/write Object. |
