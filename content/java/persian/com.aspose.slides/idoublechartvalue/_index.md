---
title: IDoubleChartValue
second_title: Aspose.Slides برای Java - مرجع API
description: نمایش مقدار double که می‌تواند به دو روش در سند ارائهٔ pptx ذخیره شود: 1) در سلول/سلول‌های کتاب‌کار مرتبط با نمودار؛ 2) به عنوان مقدار ثابت.
type: docs
url: /fa/com.aspose.slides/idoublechartvalue/
---
**تمام رابط‌های پیاده‌سازی شده:**
[com.aspose.slides.ISingleCellChartValue](../../com.aspose.slides/isinglecellchartvalue)
```
public interface IDoubleChartValue extends ISingleCellChartValue
```

مقدار double را نشان می‌دهد که می‌تواند به دو روش در سند ارائهٔ pptx ذخیره شود: 1) در سلول/سلول‌های کتاب‌کار مرتبط با نمودار؛ 2) به عنوان مقدار ثابت.
## روش‌ها

| متد | توضیح |
| --- | --- |
| [getAsLiteralDouble()](#getAsLiteralDouble--) | مقدار double ثابت را برمی‌گرداند یا تنظیم می‌کند اگر DataSourceType = Charts.DataSourceType.DoubleLiterals. |
| [setAsLiteralDouble(double value)](#setAsLiteralDouble-double-) | مقدار double ثابت را برمی‌گرداند یا تنظیم می‌کند اگر DataSourceType = Charts.DataSourceType.DoubleLiterals. |
| [toDouble()](#toDouble--) | به double تبدیل می‌شود. |
### getAsLiteralDouble() {#getAsLiteralDouble--}
```
public abstract double getAsLiteralDouble()
```

مقدار double ثابت را برمی‌گرداند یا تنظیم می‌کند اگر DataSourceType = Charts.DataSourceType.DoubleLiterals. خواندن/نوشتن double.

**بازگشت:**  
double
### setAsLiteralDouble(double value) {#setAsLiteralDouble-double-}
```
public abstract void setAsLiteralDouble(double value)
```

مقدار double ثابت را برمی‌گرداند یا تنظیم می‌کند اگر DataSourceType = Charts.DataSourceType.DoubleLiterals. خواندن/نوشتن double.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | double |  |
### toDouble() {#toDouble--}
```
public abstract double toDouble()
```

به double تبدیل می‌شود.

**بازگشت:**  
double - مقدار Double.