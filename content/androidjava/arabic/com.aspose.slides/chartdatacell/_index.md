---
title: ChartDataCell
second_title: Aspose.Slides لنظام Android عبر مرجع API لجافا
description: يمثل خلية لبيانات المخطط.
type: docs
url: /ar/com.aspose.slides/chartdatacell/
---
**الوراثة:**  
java.lang.Object

**جميع الواجهات المطبقة:**  
[com.aspose.slides.IChartDataCell](../../com.aspose.slides/ichartdatacell)  
```
public class ChartDataCell implements IChartDataCell
```

يمثل خلية لبيانات المخطط.

## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getRow()](#getRow--) | يرجع فهرس الصف في ورقة العمل التي توجد فيها الخلية. |
| [getColumn()](#getColumn--) | يرجع فهرس العمود في ورقة العمل التي توجد فيها الخلية. |
| [getValue()](#getValue--) | يحصل أو يضبط قيمة الخلية. |
| [setValue(Object value)](#setValue-java.lang.Object-) | يحصل أو يضبط قيمة الخلية. |
| [getFormula()](#getFormula--) | يحصل أو يضبط الصيغة بنمط A1. |
| [setFormula(String value)](#setFormula-java.lang.String-) | يحصل أو يضبط الصيغة بنمط A1. |
| [getR1C1Formula()](#getR1C1Formula--) | يحصل أو يضبط الصيغة بنمط R1C1. |
| [setR1C1Formula(String value)](#setR1C1Formula-java.lang.String-) | يحصل أو يضبط الصيغة بنمط R1C1. |
| [getChartDataWorksheet()](#getChartDataWorksheet--) | يحصل على ورقة العمل. |
| [isHidden()](#isHidden--) | يحدد ما إذا كانت الخلية مخفية. |
| [getCustomNumberFormat()](#getCustomNumberFormat--) | يحصل أو يضبط تنسيق العرض المخصص للأرقام والتواريخ. |
| [setCustomNumberFormat(String value)](#setCustomNumberFormat-java.lang.String-) | يحصل أو يضبط تنسيق العرض المخصص للأرقام والتواريخ. |
| [getPresetNumberFormat()](#getPresetNumberFormat--) | يحصل أو يضبط تنسيق العرض المدمج للأرقام والتواريخ. |
| [setPresetNumberFormat(byte value)](#setPresetNumberFormat-byte-) | يحصل أو يضبط تنسيق العرض المدمج للأرقام والتواريخ. |
| [calculate(boolean updateValues)](#calculate-boolean-) | إذا كانت الخلية تحتوي على صيغة، ستُحدّث القيمة بناءً على تلك الصيغة. |

### getRow() {#getRow--}
```
public final int getRow()
```

يرجع فهرس الصف في ورقة العمل التي توجد فيها الخلية. قراءة فقط int.

**إرجاع:**  
int

### getColumn() {#getColumn--}
```
public final int getColumn()
```

يرجع فهرس العمود في ورقة العمل التي توجد فيها الخلية. قراءة فقط int.

**إرجاع:**  
int

### getValue() {#getValue--}
```
public final Object getValue()
```

يحصل أو يضبط قيمة الخلية. قراءة/كتابة Object .

--------------------

> ```
> workbook.getCell(0, "F2").setValue(-2.5f);
>  workbook.getCell(0, "G3").setValue(6.3f);
> ```


**إرجاع:**  
java.lang.Object

### setValue(Object value) {#setValue-java.lang.Object-}
```
public final void setValue(Object value)
```

يحصل أو يضبط قيمة الخلية. قراءة/كتابة Object .

--------------------

> ```
> workbook.getCell(0, "F2").setValue(-2.5f);
>  workbook.getCell(0, "G3").setValue(6.3f);
> ```


**المعلمات:**  
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.Object |  |

### getFormula() {#getFormula--}
```
public final String getFormula()
```

يحصل أو يضبط الصيغة بنمط A1.

--------------------

> ```
> IChartDataCell cell = workbook.getCell(0, "B2");
>  cell.setFormula("1 + SUM(F2:H5)");
> ```


**إرجاع:**  
java.lang.String

### setFormula(String value) {#setFormula-java.lang.String-}
```
public final void setFormula(String value)
```

يحصل أو يضبط الصيغة بنمط A1.

--------------------

> ```
> IChartDataCell cell = workbook.getCell(0, "B2");
>  cell.setFormula("1 + SUM(F2:H5)");
> ```


**المعلمات:**  
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getR1C1Formula() {#getR1C1Formula--}
```
public final String getR1C1Formula()
```

يحصل أو يضبط الصيغة بنمط R1C1.

--------------------

> ```
> IChartDataCell cell = workbook.getCell(0, "C2");
>  cell.setR1C1Formula("MAX(R2C6:R5C8) / 3");
> ```


**إرجاع:**  
java.lang.String

### setR1C1Formula(String value) {#setR1C1Formula-java.lang.String-}
```
public final void setR1C1Formula(String value)
```

يحصل أو يضبط الصيغة بنمط R1C1.

--------------------

> ```
> IChartDataCell cell = workbook.getCell(0, "C2");
>  cell.setR1C1Formula("MAX(R2C6:R5C8) / 3");
> ```


**المعلمات:**  
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getChartDataWorksheet() {#getChartDataWorksheet--}
```
public final IChartDataWorksheet getChartDataWorksheet()
```

يحصل على ورقة العمل. قراءة فقط [IChartDataWorksheet](../../com.aspose.slides/ichartdataworksheet).

**إرجاع:**  
[IChartDataWorksheet](../../com.aspose.slides/ichartdataworksheet)

### isHidden() {#isHidden--}
```
public final boolean isHidden()
```

يحدد ما إذا كانت الخلية مخفية. قراءة فقط boolean.

**إرجاع:**  
boolean

### getCustomNumberFormat() {#getCustomNumberFormat--}
```
public final String getCustomNumberFormat()
```

يحصل أو يضبط تنسيق العرض المخصص للأرقام والتواريخ. إذا كان القيمة فارغة سيُستخدم قيمة PresetNumberFormat. قراءة/كتابة String.

**إرجاع:**  
java.lang.String

### setCustomNumberFormat(String value) {#setCustomNumberFormat-java.lang.String-}
```
public final void setCustomNumberFormat(String value)
```

يحصل أو يضبط تنسيق العرض المخصص للأرقام والتواريخ. إذا كان القيمة فارغة سيُستخدم قيمة PresetNumberFormat. قراءة/كتابة String.

**المعلمات:**  
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getPresetNumberFormat() {#getPresetNumberFormat--}
```
public final byte getPresetNumberFormat()
```

يحصل أو يضبط تنسيق العرض المدمج للأرقام والتواريخ. يجب أن يكون رقم Preset بين [0..22] أو [37..49]. قراءة/كتابة byte.

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

**إرجاع:**  
byte

### setPresetNumberFormat(byte value) {#setPresetNumberFormat-byte-}
```
public final void setPresetNumberFormat(byte value)
```

يحصل أو يضبط تنسيق العرض المدمج للأرقام والتواريخ. يجب أن يكون رقم Preset بين [0..22] أو [37..49]. قراءة/كتابة byte.

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

**المعلمات:**  
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### calculate(boolean updateValues) {#calculate-boolean-}
```
public final void calculate(boolean updateValues)
```

إذا كانت الخلية تحتوي على صيغة، ستُحدّث القيمة بناءً على تلك الصيغة.

**المعلمات:**  
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| updateValues | boolean | إذا كان false، لن يتم إجراء حساب فعلي. استخدم true للتحقق من الاستثناءات المحتملة. |