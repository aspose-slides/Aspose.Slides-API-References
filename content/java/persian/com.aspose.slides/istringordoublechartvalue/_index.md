---
title: IStringOrDoubleChartValue
second_title: مرجع API Aspose.Slides برای جاوا
description: نمایش مقدار رشته یا double که می‌تواند به دو روش در سند ارائهٔ pptx ذخیره شود: 1) در سلول/سلول‌های کاربرگ مرتبط با نمودار؛ 2) به عنوان مقدار ثابت.
type: docs
url: /fa/com.aspose.slides/istringordoublechartvalue/
---
**تمام اینترفیس‌های پیاده‌سازی‌شده:**
[com.aspose.slides.ISingleCellChartValue](../../com.aspose.slides/isinglecellchartvalue)
```
public interface IStringOrDoubleChartValue extends ISingleCellChartValue
```

نمایش مقدار رشته یا double که می‌تواند به دو روش در سند ارائهٔ pptx ذخیره شود: 1) در سلول/سلول‌های کاربرگ مرتبط با نمودار؛ 2) به عنوان مقدار ثابت.
## متدها

| متد | توضیح |
| --- | --- |
| [getAsLiteralString()](#getAsLiteralString--) | Returns or sets the literal string if DataSourceType property is DataSourceType.StringLiterals. |
| [setAsLiteralString(String value)](#setAsLiteralString-java.lang.String-) | Returns or sets the literal string if DataSourceType property is DataSourceType.StringLiterals. |
| [getAsLiteralDouble()](#getAsLiteralDouble--) | Returns or sets the literal double if DataSourceType property is DataSourceType.DoubleLiterals. |
| [setAsLiteralDouble(double value)](#setAsLiteralDouble-double-) | Returns or sets the literal double if DataSourceType property is DataSourceType.DoubleLiterals. |
| [toDouble()](#toDouble--) | Converts value to double. |
### getAsLiteralString() {#getAsLiteralString--}
```
public abstract String getAsLiteralString()
```

مقدار رشتهٔ ثابت را برمی‌گرداند یا تنظیم می‌کند اگر ویژگی DataSourceType برابر DataSourceType.StringLiterals باشد. خواندنی/قابل‌نوشتن String.

**بازگشت:**
java.lang.String
### setAsLiteralString(String value) {#setAsLiteralString-java.lang.String-}
```
public abstract void setAsLiteralString(String value)
```

مقدار رشتهٔ ثابت را برمی‌گرداند یا تنظیم می‌کند اگر ویژگی DataSourceType برابر DataSourceType.StringLiterals باشد. خواندنی/قابل‌نوشتن String.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |
### getAsLiteralDouble() {#getAsLiteralDouble--}
```
public abstract double getAsLiteralDouble()
```

مقدار double ثابت را برمی‌گرداند یا تنظیم می‌کند اگر ویژگی DataSourceType برابر DataSourceType.DoubleLiterals باشد. خواندنی/قابل‌نوشتن double.

**بازگشت:**
double
### setAsLiteralDouble(double value) {#setAsLiteralDouble-double-}
```
public abstract void setAsLiteralDouble(double value)
```

مقدار double ثابت را برمی‌گرداند یا تنظیم می‌کند اگر ویژگی DataSourceType برابر DataSourceType.DoubleLiterals باشد. خواندنی/قابل‌نوشتن double.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | double |  |
### toDouble() {#toDouble--}
```
public abstract double toDouble()
```

مقدار را به double تبدیل می‌کند.

**بازگشت:**
double - Double value double