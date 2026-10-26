---
title: IChartDataCell
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: نمایانگر سلول برای داده‌های نمودار.
type: docs
url: /fa/com.aspose.slides/ichartdatacell/
---```
public interface IChartDataCell
```

نمایانگر سلول برای داده‌های نمودار.
## روش‌ها

| متد | توضیح |
| --- | --- |
| [getRow()](#getRow--) | اندیس سطر ورک‌شیت که سلول در آن قرار دارد را بر می‌گرداند. |
| [getColumn()](#getColumn--) | اندیس ستون ورک‌شیت که سلول در آن قرار دارد را بر می‌گرداند. |
| [getValue()](#getValue--) | مقدار یک سلول را دریافت یا تنظیم می‌کند. |
| [setValue(Object value)](#setValue-java.lang.Object-) | مقدار یک سلول را دریافت یا تنظیم می‌کند. |
| [getFormula()](#getFormula--) | فرمول را به سبک A1 دریافت یا تنظیم می‌کند. |
| [setFormula(String value)](#setFormula-java.lang.String-) | فرمول را به سبک A1 دریافت یا تنظیم می‌کند. |
| [getR1C1Formula()](#getR1C1Formula--) | فرمول را به سبک R1C1 دریافت یا تنظیم می‌کند. |
| [setR1C1Formula(String value)](#setR1C1Formula-java.lang.String-) | فرمول را به سبک R1C1 دریافت یا تنظیم می‌کند. |
| [getChartDataWorksheet()](#getChartDataWorksheet--) | ورک‌شیت را دریافت می‌کند. |
| [isHidden()](#isHidden--) | تعیین می‌کند آیا سلول مخفی است یا خیر. |
| [getCustomNumberFormat()](#getCustomNumberFormat--) | قالب نمایش سفارشی اعداد و تاریخ‌ها را دریافت یا تنظیم می‌کند. |
| [setCustomNumberFormat(String value)](#setCustomNumberFormat-java.lang.String-) | قالب نمایش سفارشی اعداد و تاریخ‌ها را دریافت یا تنظیم می‌کند. |
| [getPresetNumberFormat()](#getPresetNumberFormat--) | قالب نمایش پیش‌ساخته اعداد و تاریخ‌ها را دریافت یا تنظیم می‌کند. |
| [setPresetNumberFormat(byte value)](#setPresetNumberFormat-byte-) | قالب نمایش پیش‌ساخته اعداد و تاریخ‌ها را دریافت یا تنظیم می‌کند. |
| [calculate(boolean updateValues)](#calculate-boolean-) | اگر سلول شامل فرمول باشد، مقدار بر اساس آن فرمول به‌روزرسانی می‌شود. |
### getRow() {#getRow--}
```
public abstract int getRow()
```


اندیس سطر ورک‌شیت که سلول در آن قرار دارد را بر می‌گرداند. فقط‌خواندنی int.

**بازگرداندن:**
int
### getColumn() {#getColumn--}
```
public abstract int getColumn()
```


اندیس ستون ورک‌شیت که سلول در آن قرار دارد را بر می‌گرداند. فقط‌خواندنی int.

**بازگرداندن:**
int
### getValue() {#getValue--}
```
public abstract Object getValue()
```


مقدار یک سلول را دریافت یا تنظیم می‌کند. قابل‌خواندن‌و‌نوشتن Object.

--------------------

> ```
> workbook.getCell(0, "F2").setValue(-2.5f);
>  workbook.getCell(0, "G3").setValue(6.3f);
> ```


**بازگرداندن:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public abstract void setValue(Object value)
```


مقدار یک سلول را دریافت یا تنظیم می‌کند. قابل‌خواندن‌و‌نوشتن Object.

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
public abstract String getFormula()
```


فرمول را به سبک A1 دریافت یا تنظیم می‌کند.

--------------------

> ```
> IChartDataCell cell = workbook.getCell(0, "B2");
>  cell.setFormula("1 + SUM(F2:H5)");
> ```


**بازگرداندن:**
java.lang.String
### setFormula(String value) {#setFormula-java.lang.String-}
```
public abstract void setFormula(String value)
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
public abstract String getR1C1Formula()
```


فرمول را به سبک R1C1 دریافت یا تنظیم می‌کند.

--------------------

> ```
> IChartDataCell cell = workbook.getCell(0, "C2");
>  cell.setR1C1Formula("MAX(R2C6:R5C8) / 3");
> ```


**بازگرداندن:**
java.lang.String
### setR1C1Formula(String value) {#setR1C1Formula-java.lang.String-}
```
public abstract void setR1C1Formula(String value)
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
public abstract IChartDataWorksheet getChartDataWorksheet()
```


ورک‌شیت را دریافت می‌کند. فقط‌خواندنی [IChartDataWorksheet](../../com.aspose.slides/ichartdataworksheet).

**بازگرداندن:**
[IChartDataWorksheet](../../com.aspose.slides/ichartdataworksheet)
### isHidden() {#isHidden--}
```
public abstract boolean isHidden()
```


تعیین می‌کند آیا سلول مخفی است یا خیر. فقط‌خواندنی boolean.

**بازگرداندن:**
boolean
### getCustomNumberFormat() {#getCustomNumberFormat--}
```
public abstract String getCustomNumberFormat()
```


قالب نمایش سفارشی اعداد و تاریخ‌ها را دریافت یا تنظیم می‌کند. اگر مقدار خالی باشد، مقدار PresetNumberFormat استفاده می‌شود. قابل‌خواندن‌و‌نوشتن String.

**بازگرداندن:**
java.lang.String
### setCustomNumberFormat(String value) {#setCustomNumberFormat-java.lang.String-}
```
public abstract void setCustomNumberFormat(String value)
```


قالب نمایش سفارشی اعداد و تاریخ‌ها را دریافت یا تنظیم می‌کند. اگر مقدار خالی باشد، مقدار PresetNumberFormat استفاده می‌شود. قابل‌خواندن‌و‌نوشتن String.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |
### getPresetNumberFormat() {#getPresetNumberFormat--}
```
public abstract byte getPresetNumberFormat()
```


قالب نمایش پیش‌ساخته اعداد و تاریخ‌ها را دریافت یا تنظیم می‌کند. عدد پیش‌تنظیم باید در بازه‌های [0..22] یا [37..49] باشد. قابل‌خواندن‌و‌نوشتن byte.

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

**بازگرداندن:**
byte
### setPresetNumberFormat(byte value) {#setPresetNumberFormat-byte-}
```
public abstract void setPresetNumberFormat(byte value)
```


قالب نمایش پیش‌ساخته اعداد و تاریخ‌ها را دریافت یا تنظیم می‌کند. عدد پیش‌تنظیم باید در بازه‌های [0..22] یا [37..49] باشد. قابل‌خواندن‌و‌نوشتن byte.

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

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |
### calculate(boolean updateValues) {#calculate-boolean-}
```
public abstract void calculate(boolean updateValues)
```


اگر سلول شامل فرمول باشد، مقدار بر اساس آن فرمول به‌روزرسانی می‌شود.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| updateValues | boolean | اگر false باشد، هیچ محاسبه واقعی انجام نمی‌شود. برای بررسی احتمالات استثناها از true استفاده کنید. |