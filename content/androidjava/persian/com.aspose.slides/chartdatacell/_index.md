---
title: ChartDataCell
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: نمایندهٔ سلول برای داده‌های نمودار.
type: docs
url: /fa/com.aspose.slides/chartdatacell/
---
**ارث‌بری:**
java.lang.Object

**تمام رابط‌های پیاده‌سازی شده:**
[com.aspose.slides.IChartDataCell](../../com.aspose.slides/ichartdatacell)
```
public class ChartDataCell implements IChartDataCell
```

نمایندهٔ سلول برای داده‌های نمودار.
## متدها

| متد | توضیح |
| --- | --- |
| [getRow()](#getRow--) | شاخص ردیف برگه کاری که سلول در آن قرار دارد را برمی‌گرداند. |
| [getColumn()](#getColumn--) | شاخص ستون برگه کاری که سلول در آن قرار دارد را برمی‌گرداند. |
| [getValue()](#getValue--) | مقدار یک سلول را دریافت یا تنظیم می‌کند. |
| [setValue(Object value)](#setValue-java.lang.Object-) | مقدار یک سلول را دریافت یا تنظیم می‌کند. |
| [getFormula()](#getFormula--) | فرمول را به سبک A1 دریافت یا تنظیم می‌کند. |
| [setFormula(String value)](#setFormula-java.lang.String-) | فرمول را به سبک A1 دریافت یا تنظیم می‌کند. |
| [getR1C1Formula()](#getR1C1Formula--) | فرمول را به سبک R1C1 دریافت یا تنظیم می‌کند. |
| [setR1C1Formula(String value)](#setR1C1Formula-java.lang.String-) | فرمول را به سبک R1C1 دریافت یا تنظیم می‌کند. |
| [getChartDataWorksheet()](#getChartDataWorksheet--) | برگه کاری را دریافت می‌کند. |
| [isHidden()](#isHidden--) | مشخص می‌کند که آیا سلول مخفی است یا نه. |
| [getCustomNumberFormat()](#getCustomNumberFormat--) | قالب نمایش سفارشی اعداد و تاریخ‌ها را دریافت یا تنظیم می‌کند. |
| [setCustomNumberFormat(String value)](#setCustomNumberFormat-java.lang.String-) | قالب نمایش سفارشی اعداد و تاریخ‌ها را دریافت یا تنظیم می‌کند. |
| [getPresetNumberFormat()](#getPresetNumberFormat--) | قالب نمایش پیش‌فرض اعداد و تاریخ‌ها را دریافت یا تنظیم می‌کند. |
| [setPresetNumberFormat(byte value)](#setPresetNumberFormat-byte-) | قالب نمایش پیش‌فرض اعداد و تاریخ‌ها را دریافت یا تنظیم می‌کند. |
| [calculate(boolean updateValues)](#calculate-boolean-) | اگر سلول حاوی فرمول باشد، مقدار بر اساس آن فرمول به‌روز می‌شود. |

### getRow() {#getRow--}
```
public final int getRow()
```

شاخص ردیف برگه کاری که سلول در آن قرار دارد را برمی‌گرداند. فقط‌خواندنی int.

**بازگشت:**
int

### getColumn() {#getColumn--}
```
public final int getColumn()
```

شاخص ستون برگه کاری که سلول در آن قرار دارد را برمی‌گرداند. فقط‌خواندنی int.

**بازگشت:**
int

### getValue() {#getValue--}
```
public final Object getValue()
```

مقدار یک سلول را دریافت یا تنظیم می‌کند. خواندنی/نوشتنی Object .

--------------------

> ```
> workbook.getCell(0, "F2").setValue(-2.5f);
>  workbook.getCell(0, "G3").setValue(6.3f);
> ```


**بازگشت:**
java.lang.Object

### setValue(Object value) {#setValue-java.lang.Object-}
```
public final void setValue(Object value)
```

مقدار یک سلول را دریافت یا تنظیم می‌کند. خواندنی/نوشتنی Object .

--------------------

> ```
> workbook.getCell(0, "F2").setValue(-2.5f);
>  workbook.getCell(0, "G3").setValue(6.3f);
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.Object |  |

### getFormula() {#getFormula--}
```
public final String getFormula()
```

فرمول را به سبک A1 دریافت یا تنظیم می‌کند.

--------------------

> ```
> IChartDataCell cell = workbook.getCell(0, "B2");
>  cell.setFormula("1 + SUM(F2:H5)");
> ```

**بازگشت:**
java.lang.String

### setFormula(String value) {#setFormula-java.lang.String-}
```
public final void setFormula(String value)
```

فرمول را به سبک A1 دریافت یا تنظیم می‌کند.

--------------------

> ```
> IChartDataCell cell = workbook.getCell(0, "B2");
>  cell.setFormula("1 + SUM(F2:H5)");
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |

### getR1C1Formula() {#getR1C1Formula--}
```
public final String getR1C1Formula()
```

فرمول را به سبک R1C1 دریافت یا تنظیم می‌کند.

--------------------

> ```
> IChartDataCell cell = workbook.getCell(0, "C2");
>  cell.setR1C1Formula("MAX(R2C6:R5C8) / 3");
> ```


**بازگشت:**
java.lang.String

### setR1C1Formula(String value) {#setR1C1Formula-java.lang.String-}
```
public final void setR1C1Formula(String value)
```

فرمول را به سبک R1C1 دریافت یا تنظیم می‌کند.

--------------------

> ```
> IChartDataCell cell = workbook.getCell(0, "C2");
>  cell.setR1C1Formula("MAX(R2C6:R5C8) / 3");
> ```


**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |

### getChartDataWorksheet() {#getChartDataWorksheet--}
```
public final IChartDataWorksheet getChartDataWorksheet()
```

برگه کاری را دریافت می‌کند. فقط‌خواندنی [IChartDataWorksheet](../../com.aspose.slides/ichartdataworksheet).

**بازگشت:**
[IChartDataWorksheet](../../com.aspose.slides/ichartdataworksheet)

### isHidden() {#isHidden--}
```
public final boolean isHidden()
```

مشخص می‌کند که آیا سلول مخفی است یا نه. فقط‌خواندنی boolean.

**بازگشت:**
boolean

### getCustomNumberFormat() {#getCustomNumberFormat--}
```
public final String getCustomNumberFormat()
```

قالب نمایش سفارشی اعداد و تاریخ‌ها را دریافت یا تنظیم می‌کند. اگر مقدار خالی باشد، مقدار PresetNumberFormat استفاده می‌شود. خواندنی/نوشتنی String.

**بازگشت:**
java.lang.String

### setCustomNumberFormat(String value) {#setCustomNumberFormat-java.lang.String-}
```
public final void setCustomNumberFormat(String value)
```

قالب نمایش سفارشی اعداد و تاریخ‌ها را دریافت یا تنظیم می‌کند. اگر مقدار خالی باشد، مقدار PresetNumberFormat استفاده می‌شود. خواندنی/نوشتنی String.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |

### getPresetNumberFormat() {#getPresetNumberFormat--}
```
public final byte getPresetNumberFormat()
```

قالب نمایش پیش‌فرض اعداد و تاریخ‌ها را دریافت یا تنظیم می‌کند. عدد پیش‌فرض باید در بازهٔ [0..22] یا [37..49] باشد. خواندنی/نوشتنی byte.

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

**بازگشت:**
byte

### setPresetNumberFormat(byte value) {#setPresetNumberFormat-byte-}
```
public final void setPresetNumberFormat(byte value)
```

قالب نمایش پیش‌فرض اعداد و تاریخ‌ها را دریافت یا تنظیم می‌کند. عدد پیش‌فرض باید در بازهٔ [0..22] یا [37..49] باشد. خواندنی/نوشتنی byte.

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

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |

### calculate(boolean updateValues) {#calculate-boolean-}
```
public final void calculate(boolean updateValues)
```

اگر سلول حاوی فرمول باشد، مقدار بر اساس آن فرمول به‌روز می‌شود.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| updateValues | boolean | اگر false باشد، هیچ محاسبه واقعی انجام نمی‌شود. برای بررسی احتمالی استثناها از true استفاده کنید. |