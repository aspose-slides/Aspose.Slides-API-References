---
title: IChartDataCell
second_title: Aspose.Slides for Android via Java API Reference
description: Represents cell for chart data.
type: docs
weight: 694
url: /androidjava/com.aspose.slides/ichartdatacell/
---```
public interface IChartDataCell
```

Represents cell for chart data.
## Methods

| Method | Description |
| --- | --- |
| [getRow()](#getRow--) | Returns the index of the row of worksheet in which the cell is located. |
| [getColumn()](#getColumn--) | Returns the index of the column of worksheet in which the cell is located. |
| [getValue()](#getValue--) | Gets or sets the value of a cell. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Gets or sets the value of a cell. |
| [getFormula()](#getFormula--) | Gets or sets the formula in A1-style. |
| [setFormula(String value)](#setFormula-java.lang.String-) | Gets or sets the formula in A1-style. |
| [getR1C1Formula()](#getR1C1Formula--) | Gets or sets the formula in R1C1-style. |
| [setR1C1Formula(String value)](#setR1C1Formula-java.lang.String-) | Gets or sets the formula in R1C1-style. |
| [getChartDataWorksheet()](#getChartDataWorksheet--) | Gets the worksheet. |
| [isHidden()](#isHidden--) | Determines whether the cell is hidden. |
| [getCustomNumberFormat()](#getCustomNumberFormat--) | Gets or sets the custom display format of numbers and dates. |
| [setCustomNumberFormat(String value)](#setCustomNumberFormat-java.lang.String-) | Gets or sets the custom display format of numbers and dates. |
| [getPresetNumberFormat()](#getPresetNumberFormat--) | Gets or sets the built-in display format of numbers and dates. |
| [setPresetNumberFormat(byte value)](#setPresetNumberFormat-byte-) | Gets or sets the built-in display format of numbers and dates. |
| [calculate(boolean updateValues)](#calculate-boolean-) | If the cell contains a formula, the value will be updated base on that formula. |
### getRow() {#getRow--}
```
public abstract int getRow()
```


Returns the index of the row of worksheet in which the cell is located. Read-only int.

**Returns:**
int
### getColumn() {#getColumn--}
```
public abstract int getColumn()
```


Returns the index of the column of worksheet in which the cell is located. Read-only int.

**Returns:**
int
### getValue() {#getValue--}
```
public abstract Object getValue()
```


Gets or sets the value of a cell. Read/write Object.

--------------------

> ```
> workbook.getCell(0, "F2").setValue(-2.5f);
>  workbook.getCell(0, "G3").setValue(6.3f);
> ```

**Returns:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public abstract void setValue(Object value)
```


Gets or sets the value of a cell. Read/write Object.

--------------------

> ```
> workbook.getCell(0, "F2").setValue(-2.5f);
>  workbook.getCell(0, "G3").setValue(6.3f);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Object |  |

### getFormula() {#getFormula--}
```
public abstract String getFormula()
```


Gets or sets the formula in A1-style.

--------------------

> ```
> IChartDataCell cell = workbook.getCell(0, "B2");
>  cell.setFormula("1 + SUM(F2:H5)");
> ```

**Returns:**
java.lang.String
### setFormula(String value) {#setFormula-java.lang.String-}
```
public abstract void setFormula(String value)
```


Gets or sets the formula in A1-style.

--------------------

> ```
> IChartDataCell cell = workbook.getCell(0, "B2");
>  cell.setFormula("1 + SUM(F2:H5)");
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getR1C1Formula() {#getR1C1Formula--}
```
public abstract String getR1C1Formula()
```


Gets or sets the formula in R1C1-style.

--------------------

> ```
> IChartDataCell cell = workbook.getCell(0, "C2");
>  cell.setR1C1Formula("MAX(R2C6:R5C8) / 3");
> ```

**Returns:**
java.lang.String
### setR1C1Formula(String value) {#setR1C1Formula-java.lang.String-}
```
public abstract void setR1C1Formula(String value)
```


Gets or sets the formula in R1C1-style.

--------------------

> ```
> IChartDataCell cell = workbook.getCell(0, "C2");
>  cell.setR1C1Formula("MAX(R2C6:R5C8) / 3");
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getChartDataWorksheet() {#getChartDataWorksheet--}
```
public abstract IChartDataWorksheet getChartDataWorksheet()
```


Gets the worksheet. Read-only [IChartDataWorksheet](../../com.aspose.slides/ichartdataworksheet).

**Returns:**
[IChartDataWorksheet](../../com.aspose.slides/ichartdataworksheet)
### isHidden() {#isHidden--}
```
public abstract boolean isHidden()
```


Determines whether the cell is hidden. Read-only boolean.

**Returns:**
boolean
### getCustomNumberFormat() {#getCustomNumberFormat--}
```
public abstract String getCustomNumberFormat()
```


Gets or sets the custom display format of numbers and dates. If value is empty will be used PresetNumberFormat value. Read/write String.

**Returns:**
java.lang.String
### setCustomNumberFormat(String value) {#setCustomNumberFormat-java.lang.String-}
```
public abstract void setCustomNumberFormat(String value)
```


Gets or sets the custom display format of numbers and dates. If value is empty will be used PresetNumberFormat value. Read/write String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getPresetNumberFormat() {#getPresetNumberFormat--}
```
public abstract byte getPresetNumberFormat()
```


Gets or sets the built-in display format of numbers and dates. Preset number must be in [0..22] or [37..49]. Read/write byte.

--------------------

> ```
> 0	General
>  1	0
>  2	0.00
>  3	#,##0
>  4	#,##0.00
>  5	$#,##0;$-#,##0
>  6	$#,##0;[Red]$-#,##0
>  7	$#,##0.00;$-#,##0.00
>  8	$#,##0.00;[Red]$-#,##0.00
>  9	0%
>  10	0.00%
>  11	0.00E+00
>  12	# ?/?
>  13	# /
>  14	m/d/yy
>  15	d-mmm-yy
>  16	d-mmm
>  17	mmm-yy
>  18	h:mm AM/PM
>  19	h:mm:ss AM/PM
>  20	h:mm
>  21	h:mm:ss
>  22	m/d/yy h:mm
>  37	#,##0;-#,##0
>  38	#,##0;[Red]-#,##0
>  39	#,##0.00;-#,##0.00
>  40	#,##0.00;[Red]-#,##0.00
>  41	_ * #,##0_ ;_ * "_ ;_ @_
>  42	_ $* #,##0_ ;_ $* "_ ;_ @_
>  43	_ * #,##0.00_ ;_ * "??_ ;_ @_
>  44	_ $* #,##0.00_ ;_ $* "??_ ;_ @_
>  45	mm:ss
>  46	h :mm:ss
>  47	mm:ss.0
>  48	##0.0E+00
>  49	@
> ```

**Returns:**
byte
### setPresetNumberFormat(byte value) {#setPresetNumberFormat-byte-}
```
public abstract void setPresetNumberFormat(byte value)
```


Gets or sets the built-in display format of numbers and dates. Preset number must be in [0..22] or [37..49]. Read/write byte.

--------------------

> ```
> 0	General
>  1	0
>  2	0.00
>  3	#,##0
>  4	#,##0.00
>  5	$#,##0;$-#,##0
>  6	$#,##0;[Red]$-#,##0
>  7	$#,##0.00;$-#,##0.00
>  8	$#,##0.00;[Red]$-#,##0.00
>  9	0%
>  10	0.00%
>  11	0.00E+00
>  12	# ?/?
>  13	# /
>  14	m/d/yy
>  15	d-mmm-yy
>  16	d-mmm
>  17	mmm-yy
>  18	h:mm AM/PM
>  19	h:mm:ss AM/PM
>  20	h:mm
>  21	h:mm:ss
>  22	m/d/yy h:mm
>  37	#,##0;-#,##0
>  38	#,##0;[Red]-#,##0
>  39	#,##0.00;-#,##0.00
>  40	#,##0.00;[Red]-#,##0.00
>  41	_ * #,##0_ ;_ * "_ ;_ @_
>  42	_ $* #,##0_ ;_ $* "_ ;_ @_
>  43	_ * #,##0.00_ ;_ * "??_ ;_ @_
>  44	_ $* #,##0.00_ ;_ $* "??_ ;_ @_
>  45	mm:ss
>  46	h :mm:ss
>  47	mm:ss.0
>  48	##0.0E+00
>  49	@
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### calculate(boolean updateValues) {#calculate-boolean-}
```
public abstract void calculate(boolean updateValues)
```


If the cell contains a formula, the value will be updated base on that formula.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| updateValues | boolean | If false, no actual calculation will be performed. Use true for possible exceptions check. |

