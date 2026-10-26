---
title: IDoubleChartValue
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: نمایش مقدار double که می‌تواند به دو روش در سند ارائه pptx ذخیره شود: ۱) در سلول/سلول‌های workbook مرتبط با نمودار ۲) به عنوان مقدار ثابت.
type: docs
url: /fa/com.aspose.slides/idoublechartvalue/
---
**تمام اینترفیس‌های پیاده‌سازی‌شده:**
[com.aspose.slides.ISingleCellChartValue](../../com.aspose.slides/isinglecellchartvalue)
```
public interface IDoubleChartValue extends ISingleCellChartValue
```

نمایش مقدار double که می‌تواند به دو شکل در سند ارائه pptx ذخیره شود: ۱) در سلول/سلول‌های workbook مرتبط با نمودار؛ ۲) به عنوان مقدار ثابت.

## Methods

| متد | توضیح |
| --- | --- |
| [getAsLiteralDouble()](#getAsLiteralDouble--) | مقدار double ثابت را برمی‌گرداند یا تنظیم می‌کند اگر DataSourceType = Charts.DataSourceType.DoubleLiterals. خواندنی/قابل نوشتن double. |
| [setAsLiteralDouble(double value)](#setAsLiteralDouble-double-) | مقدار double ثابت را برمی‌گرداند یا تنظیم می‌کند اگر DataSourceType = Charts.DataSourceType.DoubleLiterals. خواندنی/قابل نوشتن double. |
| [toDouble()](#toDouble--) | به double تبدیل می‌شود. |
### getAsLiteralDouble() {#getAsLiteralDouble--}
```
public abstract double getAsLiteralDouble()
```

مقدار double ثابت را برمی‌گرداند یا تنظیم می‌کند اگر DataSourceType = Charts.DataSourceType.DoubleLiterals. خواندنی/قابل نوشتن double.

**بازگشت:**  
double
### setAsLiteralDouble(double value) {#setAsLiteralDouble-double-}
```
public abstract void setAsLiteralDouble(double value)
```

مقدار double ثابت را برمی‌گرداند یا تنظیم می‌کند اگر DataSourceType = Charts.DataSourceType.DoubleLiterals. خواندنی/قابل نوشتن double.

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