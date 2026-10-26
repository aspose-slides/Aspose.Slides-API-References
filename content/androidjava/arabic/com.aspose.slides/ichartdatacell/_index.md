---
title: IChartDataCell
second_title: Aspose.Slides لأندرويد عبر مرجع Java API
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
| [getRow()](#getRow--) | إرجاع فهرس الصف في ورقة العمل التي توجد فيها الخلية. |
| [getColumn()](#getColumn--) | إرجاع فهرس العمود في ورقة العمل التي توجد فيها الخلية. |
| [getValue()](#getValue--) | الحصول على قيمة الخلية أو تعيينها. |
| [setValue(Object value)](#setValue-java.lang.Object-) | الحصول على قيمة الخلية أو تعيينها. |
| [getFormula()](#getFormula--) | الحصول على الصيغة أو تعيينها بنمط A1. |
| [setFormula(String value)](#setFormula-java.lang.String-) | الحصول على الصيغة أو تعيينها بنمط A1. |
| [getR1C1Formula()](#getR1C1Formula--) | الحصول على الصيغة أو تعيينها بنمط R1C1. |
| [setR1C1Formula(String value)](#setR1C1Formula-java.lang.String-) | الحصول على الصيغة أو تعيينها بنمط R1C1. |
| [getChartDataWorksheet()](#getChartDataWorksheet--) | الحصول على ورقة العمل. |
| [isHidden()](#isHidden--) | تحديد ما إذا كانت الخلية مخفية. |
| [getCustomNumberFormat()](#getCustomNumberFormat--) | الحصول على تنسيق العرض المخصص للأعداد والتواريخ أو تعيينه. |
| [setCustomNumberFormat(String value)](#setCustomNumberFormat-java.lang.String-) | الحصول على تنسيق العرض المخصّص للأعداد والتواريخ أو تعيينه. |
| [getPresetNumberFormat()](#getPresetNumberFormat--) | الحصول على تنسيق العرض المدمج للأعداد والتواريخ أو تعيينه. |
| [setPresetNumberFormat(byte value)](#setPresetNumberFormat-byte-) | الحصول على تنسيق العرض المدمج للأعداد والتواريخ أو تعيينه. |
| [calculate(boolean updateValues)](#calculate-boolean-) | إذا كانت الخلية تحتوي على صيغة، سيتم تحديث القيمة بناءً على هذه الصيغة. |
### getRow() {#getRow--}
```
public abstract int getRow()
```

إرجاع فهرس الصف في ورقة العمل التي توجد فيها الخلية. قراءة فقط int.

**الإرجاع:**
int
### getColumn() {#getColumn--}
```
public abstract int getColumn()
```

إرجاع فهرس العمود في ورقة العمل التي توجد فيها الخلية. قراءة فقط int.

**الإرجاع:**
int
### getValue() {#getValue--}
```
public abstract Object getValue()
```

الحصول على قيمة الخلية أو تعيينها. قراءة/كتابة Object.

--------------------

> ```
> workbook.getCell(0, "F2").setValue(-2.5f);
>  workbook.getCell(0, "G3").setValue(6.3f);
> ```


**الإرجاع:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public abstract void setValue(Object value)
```

الحصول على قيمة الخلية أو تعيينها. قراءة/كتابة Object.

--------------------

> ```
> workbook.getCell(0, "F2").setValue(-2.5f);
>  workbook.getCell(0, "G3").setValue(6.3f);
> ```


**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Object |  |
### getFormula() {#getFormula--}
```
public abstract String getFormula()
```

الحصول على الصيغة أو تعيينها بنمط A1.

--------------------

> ```
> IChartDataCell cell = workbook.getCell(0, "B2");
>  cell.setFormula("1 + SUM(F2:H5)");
> ```


**الإرجاع:**
java.lang.String
### setFormula(String value) {#setFormula-java.lang.String-}
```
public abstract void setFormula(String value)
```

الحصول على الصيغة أو تعيينها بنمط A1.

--------------------

> ```
> IChartDataCell cell = workbook.getCell(0, "B2");
>  cell.setFormula("1 + SUM(F2:H5)");
> ```


**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |
### getR1C1Formula() {#getR1C1Formula--}
```
public abstract String getR1C1Formula()
```

الحصول على الصيغة أو تعيينها بنمط R1C1.

--------------------

> ```
> IChartDataCell cell = workbook.getCell(0, "C2");
>  cell.setR1C1Formula("MAX(R2C6:R5C8) / 3");
> ```

**الإرجاع:**
java.lang.String
### setR1C1Formula(String value) {#setR1C1Formula-java.lang.String-}
```
public abstract void setR1C1Formula(String value)
```

الحصول على الصيغة أو تعيينها بنمط R1C1.

--------------------

> ```
> IChartDataCell cell = workbook.getCell(0, "C2");
>  cell.setR1C1Formula("MAX(R2C6:R5C8) / 3");
> ```


**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |
### getChartDataWorksheet() {#getChartDataWorksheet--}
```
public abstract IChartDataWorksheet getChartDataWorksheet()
```

الحصول على ورقة العمل. قراءة فقط [IChartDataWorksheet](../../com.aspose.slides/ichartdataworksheet).

**الإرجاع:**
[IChartDataWorksheet](../../com.aspose.slides/ichartdataworksheet)
### isHidden() {#isHidden--}
```
public abstract boolean isHidden()
```

تحديد ما إذا كانت الخلية مخفية. قراءة فقط boolean.

**الإرجاع:**
boolean
### getCustomNumberFormat() {#getCustomNumberFormat--}
```
public abstract String getCustomNumberFormat()
```

الحصول على تنسيق العرض المخصّص للأعداد والتواريخ أو تعيينه. إذا كان القيمة فارغة سيُستخدم PresetNumberFormat. قراءة/كتابة String.

**الإرجاع:**
java.lang.String
### setCustomNumberFormat(String value) {#setCustomNumberFormat-java.lang.String-}
```
public abstract void setCustomNumberFormat(String value)
```

الحصول على تنسيق العرض المخصّص للأعداد والتواريخ أو تعيينه. إذا كان القيمة فارغة سيُستخدم PresetNumberFormat. قراءة/كتابة String.

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |
### getPresetNumberFormat() {#getPresetNumberFormat--}
```
public abstract byte getPresetNumberFormat()
```

الحصول على تنسيق العرض المدمج للأعداد والتواريخ أو تعيينه. يجب أن يكون رقم Preset في النطاق [0..22] أو [37..49]. قراءة/كتابة byte.

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


**الإرجاع:**
byte
### setPresetNumberFormat(byte value) {#setPresetNumberFormat-byte-}
```
public abstract void setPresetNumberFormat(byte value)
```

الحصول على تنسيق العرض المدمج للأعداد والتواريخ أو تعيينه. يجب أن يكون رقم Preset في النطاق [0..22] أو [37..49]. قراءة/كتابة byte.

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

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |
### calculate(boolean updateValues) {#calculate-boolean-}
```
public abstract void calculate(boolean updateValues)
```

إذا كانت الخلية تحتوي على صيغة، سيتم تحديث القيمة بناءً على هذه الصيغة.

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| updateValues | boolean | إذا كان false، فلن يتم إجراء أي حساب فعلي. استخدم true للتحقق من الاستثناءات المحتملة. |