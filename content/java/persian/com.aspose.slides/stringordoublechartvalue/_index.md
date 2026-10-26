---
title: StringOrDoubleChartValue
second_title: Aspose.Slides برای Java مرجع API
description: رشته یا مقدار double را که می‌تواند به دو روش در سند ارائهٔ pptx ذخیره شود، ۱ در سلول/سلول‌های کتاب‌کار مرتبط با نمودار و ۲ به عنوان مقدار ثابت، نمایندگی می‌کند.
type: docs
url: /fa/com.aspose.slides/stringordoublechartvalue/
---
**ارث بری:**
java.lang.Object, [com.aspose.slides.BaseChartValue](../../com.aspose.slides/basechartvalue)

**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue)
```
public class StringOrDoubleChartValue extends BaseChartValue implements IStringOrDoubleChartValue
```

نمایش رشته یا مقدار double که می‌تواند به دو روش در سند ارائه pptx ذخیره شود: 1) در سلول/سلول‌های کتاب‌کار مرتبط با نمودار؛ 2) به عنوان مقدار ثابت.
## متدها

| متد | توضیح |
| --- | --- |
| [getAsCell()](#getAsCell--) | سلول دادهٔ نمودار را برمی‌گرداند یا تنظیم می‌کند. |
| [setAsCell(IChartDataCell value)](#setAsCell-com.aspose.slides.IChartDataCell-) | سلول دادهٔ نمودار را برمی‌گرداند یا تنظیم می‌کند. |
| [getAsLiteralString()](#getAsLiteralString--) | مقدار را به عنوان رشتهٔ ثابت برمی‌گرداند یا تنظیم می‌کند. |
| [setAsLiteralString(String value)](#setAsLiteralString-java.lang.String-) | مقدار را به عنوان رشتهٔ ثابت برمی‌گرداند یا تنظیم می‌کند. |
| [getAsLiteralDouble()](#getAsLiteralDouble--) | مقدار را به عنوان double ثابت برمی‌گرداند یا تنظیم می‌کند. |
| [setAsLiteralDouble(double value)](#setAsLiteralDouble-double-) | مقدار را به عنوان double ثابت برمی‌گرداند یا تنظیم می‌کند. |
| [getData()](#getData--) | شیء Data را برمی‌گرداند یا تنظیم می‌کند. |
| [setData(Object value)](#setData-java.lang.Object-) | شیء Data را برمی‌گرداند یا تنظیم می‌کند. |
| [toDouble()](#toDouble--) | به double تبدیل می‌شود. |
### getAsCell() {#getAsCell--}
```
public final IChartDataCell getAsCell()
```

سلول دادهٔ نمودار را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**بازگشت:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setAsCell(IChartDataCell value) {#setAsCell-com.aspose.slides.IChartDataCell-}
```
public final void setAsCell(IChartDataCell value)
```

سلول دادهٔ نمودار را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |

### getAsLiteralString() {#getAsLiteralString--}
```
public final String getAsLiteralString()
```

مقدار را به عنوان رشتهٔ ثابت برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی String.

**بازگشت:**
java.lang.String
### setAsLiteralString(String value) {#setAsLiteralString-java.lang.String-}
```
public final void setAsLiteralString(String value)
```

مقدار را به عنوان رشتهٔ ثابت برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی String.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |

### getAsLiteralDouble() {#getAsLiteralDouble--}
```
public final double getAsLiteralDouble()
```

مقدار را به عنوان double ثابت برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی double.

**بازگشت:**
double
### setAsLiteralDouble(double value) {#setAsLiteralDouble-double-}
```
public final void setAsLiteralDouble(double value)
```

مقدار را به عنوان double ثابت برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی double.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | double |  |

### getData() {#getData--}
```
public Object getData()
```

شیء Data را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی Object.

**بازگشت:**
java.lang.Object
### setData(Object value) {#setData-java.lang.Object-}
```
public void setData(Object value)
```

شیء Data را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی Object.

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
double - مقدار Double.