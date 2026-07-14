---
title: IStringOrDoubleChartValue
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: نمایش رشته یا مقدار double که می‌تواند به دو روش در سند ارائه pptx ذخیره شود: 1) در سلول/سلول‌های کتاب‌کار مرتبط با نمودار 2) به‌عنوان مقدار متنی.
type: docs
url: /fa/com.aspose.slides/istringordoublechartvalue/
---
**همهٔ رابط‌های پیاده‌سازی شده:**
[com.aspose.slides.ISingleCellChartValue](../../com.aspose.slides/isinglecellchartvalue)
```
public interface IStringOrDoubleChartValue extends ISingleCellChartValue
```

نمایش رشته یا مقدار double که می‌تواند به دو روش در سند ارائهٔ pptx ذخیره شود: 1) در سلول/سلول‌های کتاب‌کار مرتبط با نمودار؛ 2) به عنوان مقدار متنی.
## متدها

| متد | توضیح |
| --- | --- |
| [getAsLiteralString()](#getAsLiteralString--) | اگر ویژگی DataSourceType برابر DataSourceType.StringLiterals باشد، رشتهٔ متنی را برمی‌گرداند یا تنظیم می‌کند. |
| [setAsLiteralString(String value)](#setAsLiteralString-java.lang.String-) | اگر ویژگی DataSourceType برابر DataSourceType.StringLiterals باشد، رشتهٔ متنی را برمی‌گرداند یا تنظیم می‌کند. |
| [getAsLiteralDouble()](#getAsLiteralDouble--) | اگر ویژگی DataSourceType برابر DataSourceType.DoubleLiterals باشد، مقدار double را برمی‌گرداند یا تنظیم می‌کند. |
| [setAsLiteralDouble(double value)](#setAsLiteralDouble-double-) | اگر ویژگی DataSourceType برابر DataSourceType.DoubleLiterals باشد، مقدار double را برمی‌گرداند یا تنظیم می‌کند. |
| [toDouble()](#toDouble--) | مقدار را به double تبدیل می‌کند. |
### getAsLiteralString() {#getAsLiteralString--}
```
public abstract String getAsLiteralString()
```

اگر ویژگی DataSourceType برابر DataSourceType.StringLiterals باشد، رشتهٔ متنی را برمی‌گرداند یا تنظیم می‌کند. خواندنی/قابل نوشتن String.

**بازگشت:**
java.lang.String
### setAsLiteralString(String value) {#setAsLiteralString-java.lang.String-}
```
public abstract void setAsLiteralString(String value)
```

اگر ویژگی DataSourceType برابر DataSourceType.StringLiterals باشد، رشتهٔ متنی را برمی‌گرداند یا تنظیم می‌کند. خواندنی/قابل نوشتن String.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |
### getAsLiteralDouble() {#getAsLiteralDouble--}
```
public abstract double getAsLiteralDouble()
```

اگر ویژگی DataSourceType برابر DataSourceType.DoubleLiterals باشد، مقدار double را برمی‌گرداند یا تنظیم می‌کند. خواندنی/قابل نوشتن double.

**بازگشت:**
double
### setAsLiteralDouble(double value) {#setAsLiteralDouble-double-}
```
public abstract void setAsLiteralDouble(double value)
```

اگر ویژگی DataSourceType برابر DataSourceType.DoubleLiterals باشد، مقدار double را برمی‌گرداند یا تنظیم می‌کند. خواندنی/قابل نوشتن double.

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