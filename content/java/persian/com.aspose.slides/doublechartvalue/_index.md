---
title: DoubleChartValue
second_title: مرجع API Aspose.Slides برای Java
description: نمایانگر مقدار double است که می‌تواند به دو شکل در سند ارائه pptx ذخیره شود: 1) در سلول/سلول‌های کاربرگ مرتبط با نمودار؛ 2) به عنوان مقدار ثابت.
type: docs
url: /fa/com.aspose.slides/doublechartvalue/
---
**ارث‌بری:**
java.lang.Object, [com.aspose.slides.BaseChartValue](../../com.aspose.slides/basechartvalue)

**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
```
public class DoubleChartValue extends BaseChartValue implements IDoubleChartValue
```

نمایش مقدار double که می‌تواند به دو صورت در سند ارائه pptx ذخیره شود: 1) در سلول/سلول‌های کاربرگ مرتبط با نمودار؛ 2) به عنوان مقدار ثابت.
## متدها

| متد | توضیح |
| --- | --- |
| [getAsCell()](#getAsCell--) | دریافت یا تنظیم سلول داده نمودار. |
| [setAsCell(IChartDataCell value)](#setAsCell-com.aspose.slides.IChartDataCell-) | دریافت یا تنظیم سلول داده نمودار. |
| [getAsLiteralDouble()](#getAsLiteralDouble--) | دریافت یا تنظیم مقدار به صورت double ثابت. |
| [setAsLiteralDouble(double value)](#setAsLiteralDouble-double-) | دریافت یا تنظیم مقدار به صورت double ثابت. |
| [getData()](#getData--) | دریافت یا تنظیم شیء Data. |
| [setData(Object value)](#setData-java.lang.Object-) | دریافت یا تنظیم شیء Data. |
| [toDouble()](#toDouble--) | تبدیل به double. |
### getAsCell() {#getAsCell--}
```
public final IChartDataCell getAsCell()
```

دریافت یا تنظیم سلول داده نمودار. خواندنی/نوشتنی [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**بازگشت:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setAsCell(IChartDataCell value) {#setAsCell-com.aspose.slides.IChartDataCell-}
```
public final void setAsCell(IChartDataCell value)
```

دریافت یا تنظیم سلول داده نمودار. خواندنی/نوشتنی [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |
### getAsLiteralDouble() {#getAsLiteralDouble--}
```
public final double getAsLiteralDouble()
```

دریافت یا تنظیم مقدار به صورت double ثابت. خواندنی/نوشتنی double.

**بازگشت:**
double
### setAsLiteralDouble(double value) {#setAsLiteralDouble-double-}
```
public final void setAsLiteralDouble(double value)
```

دریافت یا تنظیم مقدار به صورت double ثابت. خواندنی/نوشتنی double.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | double |  |
### getData() {#getData--}
```
public Object getData()
```

دریافت یا تنظیم شیء Data. خواندنی/نوشتنی Object.

**بازگشت:**
java.lang.Object
### setData(Object value) {#setData-java.lang.Object-}
```
public void setData(Object value)
```

دریافت یا تنظیم شیء Data. خواندنی/نوشتنی Object.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.Object |  |
### toDouble() {#toDouble--}
```
public final double toDouble()
```

به double تبدیل می‌شود.

**بازگشت:**
double - اگر DataSourceType برابر DoubleLiterals باشد LiteralDouble را برمی‌گرداند. اگر DataSourceType برابر Worksheet باشد مقدار سلول تبدیل‌شده به double را برمی‌گرداند، در غیر اینصورت NaN را برمی‌گرداند.