---
title: IChartDataCell
second_title: Aspose.Slides for Java API Reference
description: يمثل خلية لبيانات المخطط.
type: docs
url: /ar/com.aspose.slides/ichartdatacell/
---```
public interface IChartDataCell
```

يمثل خلية لبيانات المخطط.
## Methods

| Method | Description |
| --- | --- |
| [getRow()](#getRow--) | يرجع فهرس الصف في ورقة العمل التي تقع فيها الخلية. |
| [getColumn()](#getColumn--) | يرجع فهرس العمود في ورقة العمل التي تقع فيها الخلية. |
| [getValue()](#getValue--) | يحصل على قيمة الخلية أو يحددها. |
| [setValue(Object value)](#setValue-java.lang.Object-) | يحصل على قيمة الخلية أو يحددها. |
| [getFormula()](#getFormula--) | يحصل على الصيغة أو يحددها بنمط A1. |
| [setFormula(String value)](#setFormula-java.lang.String-) | يحصل على الصيغة أو يحددها بنمط A1. |
| [getR1C1Formula()](#getR1C1Formula--) | يحصل على الصيغة أو يحددها بنمط R1C1. |
| [setR1C1Formula(String value)](#setR1C1Formula-java.lang.String-) | يحصل على الصيغة أو يحددها بنمط R1C1. |
| [getChartDataWorksheet()](#getChartDataWorksheet--) | يحصل على ورقة العمل. |
| [isHidden()](#isHidden--) | يحدد ما إذا كانت الخلية مخفية. |
| [getCustomNumberFormat()](#getCustomNumberFormat--) | يحصل على تنسيق العرض المخصص للأرقام والتواريخ أو يحدده. |
| [setCustomNumberFormat(String value)](#setCustomNumberFormat-java.lang.String-) | يحصل على تنسيق العرض المخصص للأرقام والتواريخ أو يحدده. |
| [getPresetNumberFormat()](#getPresetNumberFormat--) | يحصل على تنسيق العرض المدمج للأرقام والتواريخ أو يحدده. |
| [setPresetNumberFormat(byte value)](#setPresetNumberFormat-byte-) | يحصل على تنسيق العرض المدمج للأرقام والتواريخ أو يحدده. |
| [calculate(boolean updateValues)](#calculate-boolean-) | إذا كانت الخلية تحتوي على صيغة، سيتم تحديث القيمة بناءً على تلك الصيغة. |
### getRow() {#getRow--}
```
public abstract int getRow()
```


يرجع فهرس الصف في ورقة العمل التي تقع فيها الخلية. لقراءة فقط int.

**Returns:**
int
### getColumn() {#getColumn--}
```
public abstract int getColumn()
```


يرجع فهرس العمود في ورقة العمل التي تقع فيها الخلية. لقراءة فقط int.

**Returns:**
int
### getValue() {#getValue--}
```
public abstract Object getValue()
```


يحصل على قيمة الخلية أو يحددها. للقراءة والكتابة Object.

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


يحصل على قيمة الخلية أو يحددها. للقراءة والكتابة Object.

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


يحصل على الصيغة أو يحددها بنمط A1.

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


يحصل على الصيغة أو يحددها بنمط A1.

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


يحصل على الصيغة أو يحددها بنمط R1C1.

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


يحصل على الصيغة أو يحددها بنمط R1C1.

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


يحصل على ورقة العمل. لقراءة فقط [IChartDataWorksheet](../../com.aspose.slides/ichartdataworksheet).

**Returns:**
[IChartDataWorksheet](../../com.aspose.slides/ichartdataworksheet)
### isHidden() {#isHidden--}
```
public abstract boolean isHidden()
```


يحدد ما إذا كانت الخلية مخفية. لقراءة فقط boolean.

**Returns:**
boolean
### getCustomNumberFormat() {#getCustomNumberFormat--}
```
public abstract String getCustomNumberFormat()
```


يحصل على تنسيق العرض المخصص للأرقام والتواريخ أو يحدده. إذا كان القيمة فارغة سيُستخدم PresetNumberFormat. للقراءة والكتابة String.

**Returns:**
java.lang.String
### setCustomNumberFormat(String value) {#setCustomNumberFormat-java.lang.String-}
```
public abstract void setCustomNumberFormat(String value)
```


يحصل على تنسيق العرض المخصص للأرقام والتواريخ أو يحدده. إذا كان القيمة فارغة سيُستخدم PresetNumberFormat. للقراءة والكتابة String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getPresetNumberFormat() {#getPresetNumberFormat--}
```
public abstract byte getPresetNumberFormat()
```


يحصل على تنسيق العرض المدمج للأرقام والتواريخ أو يحدده. يجب أن يكون رقم التنسيق المسبق في [0..22] أو [37..49]. للقراءة والكتابة byte.

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


يحصل على تنسيق العرض المدمج للأرقام والتواريخ أو يحدده. يجب أن يكون رقم التنسيق المسبق في [0..22] أو [37..49]. للقراءة والكتابة byte.

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


إذا كانت الخلية تحتوي على صيغة، سيتم تحديث القيمة بناءً على تلك الصيغة.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| updateValues | boolean | إذا كان false، لن يتم إجراء حساب فعلي. استخدم true للتحقق من الاستثناءات المحتملة. |