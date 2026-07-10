---
title: ChartDataCell
second_title: 适用于 Android 的 Aspose.Slides via Java API 参考
description: 表示图表数据的单元格。
type: docs
url: /zh/com.aspose.slides/chartdatacell/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IChartDataCell](../../com.aspose.slides/ichartdatacell)
```
public class ChartDataCell implements IChartDataCell
```

表示图表数据的单元格。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getRow()](#getRow--) | 返回单元格所在工作表的行索引。 |
| [getColumn()](#getColumn--) | 返回单元格所在工作表的列索引。 |
| [getValue()](#getValue--) | 获取或设置单元格的值。 |
| [setValue(Object value)](#setValue-java.lang.Object-) | 获取或设置单元格的值。 |
| [getFormula()](#getFormula--) | 获取或设置 A1 样式的公式。 |
| [setFormula(String value)](#setFormula-java.lang.String-) | 获取或设置 A1 样式的公式。 |
| [getR1C1Formula()](#getR1C1Formula--) | 获取或设置 R1C1 样式的公式。 |
| [setR1C1Formula(String value)](#setR1C1Formula-java.lang.String-) | 获取或设置 R1C1 样式的公式。 |
| [getChartDataWorksheet()](#getChartDataWorksheet--) | 获取工作表。 |
| [isHidden()](#isHidden--) | 确定单元格是否隐藏。 |
| [getCustomNumberFormat()](#getCustomNumberFormat--) | 获取或设置数字和日期的自定义显示格式。 |
| [setCustomNumberFormat(String value)](#setCustomNumberFormat-java.lang.String-) | 获取或设置数字和日期的自定义显示格式。 |
| [getPresetNumberFormat()](#getPresetNumberFormat--) | 获取或设置数字和日期的内置显示格式。 |
| [setPresetNumberFormat(byte value)](#setPresetNumberFormat-byte-) | 获取或设置数字和日期的内置显示格式。 |
| [calculate(boolean updateValues)](#calculate-boolean-) | 如果单元格包含公式，值将基于该公式进行更新。 |

### getRow() {#getRow--}
```
public final int getRow()
```

返回单元格所在工作表的行索引。只读 int。

**返回：**
int

### getColumn() {#getColumn--}
```
public final int getColumn()
```

返回单元格所在工作表的列索引。只读 int。

**返回：**
int

### getValue() {#getValue--}
```
public final Object getValue()
```

获取或设置单元格的值。读/写 Object 。

--------------------

> ```
> workbook.getCell(0, "F2").setValue(-2.5f);
>  workbook.getCell(0, "G3").setValue(6.3f);
> ```

**Returns:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public final void setValue(Object value)
```

Gets or sets the value of a cell. Read/write  Object .

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
public final String getFormula()
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
public final void setFormula(String value)
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
public final String getR1C1Formula()
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
public final void setR1C1Formula(String value)
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
public final IChartDataWorksheet getChartDataWorksheet()
```

Gets the worksheet. Read-only [IChartDataWorksheet](../../com.aspose.slides/ichartdataworksheet).

**Returns:**
[IChartDataWorksheet](../../com.aspose.slides/ichartdataworksheet)
### isHidden() {#isHidden--}
```
public final boolean isHidden()
```

Determines whether the cell is hidden. Read-only boolean.

**Returns:**
boolean
### getCustomNumberFormat() {#getCustomNumberFormat--}
```
public final String getCustomNumberFormat()
```

Gets or sets the custom display format of numbers and dates. If value is empty will be used PresetNumberFormat value. Read/write String.

**Returns:**
java.lang.String
### setCustomNumberFormat(String value) {#setCustomNumberFormat-java.lang.String-}
```
public final void setCustomNumberFormat(String value)
```

Gets or sets the custom display format of numbers and dates. If value is empty will be used PresetNumberFormat value. Read/write String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getPresetNumberFormat() {#getPresetNumberFormat--}
```
public final byte getPresetNumberFormat()
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
>  44	_("$"* # ##0,00_);_("$"* (# ##0,00);_("$"* "-"??_);_(@_)
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
public final void setPresetNumberFormat(byte value)
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
>  44	_("$"* # ##0,00_);_("$"* (# ##0,00);_("$"* "-"??_);_(@_)
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
public final void calculate(boolean updateValues)

如果单元格包含公式，值将基于该公式进行更新。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| updateValues | boolean | 如果为 false，则不会执行实际计算。使用 true 可检查可能的异常。 |