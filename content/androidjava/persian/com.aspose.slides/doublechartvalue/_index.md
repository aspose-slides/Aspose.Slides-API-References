---
title: DoubleChartValue
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: نمایش مقدار double که می‌تواند به دو روش در سند ارائه pptx ذخیره شود: 1 در سلول/سلول‌های ورک‌بوک مربوط به نمودار 2 به‌عنوان مقدار صریح.
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

نمایش مقدار double که می‌تواند به دو روش در سند ارائه pptx ذخیره شود: 1) در سلول/سلول‌های ورک‌بوک مربوط به نمودار؛ 2) به‌عنوان مقدار صریح.
## متدها

| روش | توضیح |
| --- | --- |
| [getAsCell()](#getAsCell--) | مقدار سلول داده نمودار را بر می‌گرداند یا تنظیم می‌کند. |
| [setAsCell(IChartDataCell value)](#setAsCell-com.aspose.slides.IChartDataCell-) | مقدار سلول داده نمودار را بر می‌گرداند یا تنظیم می‌کند. |
| [getAsLiteralDouble()](#getAsLiteralDouble--) | مقدار را به عنوان double صریح بر می‌گرداند یا تنظیم می‌کند. |
| [setAsLiteralDouble(double value)](#setAsLiteralDouble-double-) | مقدار را به عنوان double صریح بر می‌گرداند یا تنظیم می‌کند. |
| [getData()](#getData--) | شی Data را بر می‌گرداند یا تنظیم می‌کند. |
| [setData(Object value)](#setData-java.lang.Object-) | شی Data را بر می‌گرداند یا تنظیم می‌کند. |
| [toDouble()](#toDouble--) | به double تبدیل می‌کند. |
### getAsCell() {#getAsCell--}
```
public final IChartDataCell getAsCell()
```

مقدار سلول داده نمودار را بر می‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**بازگشت:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setAsCell(IChartDataCell value) {#setAsCell-com.aspose.slides.IChartDataCell-}
```
public final void setAsCell(IChartDataCell value)
```

مقدار سلول داده نمودار را بر می‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |

### getAsLiteralDouble() {#getAsLiteralDouble--}
```
public final double getAsLiteralDouble()
```

مقدار را به عنوان double صریح بر می‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی double.

**بازگشت:**
double
### setAsLiteralDouble(double value) {#setAsLiteralDouble-double-}
```
public final void setAsLiteralDouble(double value)
```

مقدار را به عنوان double صریح بر می‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی double.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | double |  |

### getData() {#getData--}
```
public Object getData()
```

شی Data را بر می‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی Object.

**بازگشت:**
java.lang.Object
### setData(Object value) {#setData-java.lang.Object-}
```
public void setData(Object value)
```

شی Data را بر می‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی Object.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.Object |  |

### toDouble() {#toDouble--}
```
public final double toDouble()
```

به double تبدیل می‌کند.

**بازگشت:**
double - اگر DataSourceType برابر DoubleLiterals باشد LiteralDouble را برمی‌گرداند. اگر DataSourceType برابر Worksheet باشد، مقدار سلول تبدیل‌شده به double را با موفقیت برمی‌گرداند، در غیر این صورت NaN را برمی‌گرداند.