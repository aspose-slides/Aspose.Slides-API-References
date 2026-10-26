---
title: IStringChartValue
second_title: مرجع API Aspose.Slides برای جاوا
description: نمایش مقدار رشته‌ای که می‌تواند به دو روش در سند ارائهٔ pptx ذخیره شود: 1) در سلول/سلول‌های کتاب‌کار مرتبط با نمودار 2) به عنوان مقدار literal.
type: docs
url: /fa/com.aspose.slides/istringchartvalue/
---
**All Implemented Interfaces:**  
[com.aspose.slides.IMultipleCellChartValue](../../com.aspose.slides/imultiplecellchartvalue)
```
public interface IStringChartValue extends IMultipleCellChartValue
```

نمایش مقدار رشته‌ای که می‌تواند به دو روش در سند ارائهٔ pptx ذخیره شود: 1) در سلول/سلول‌های کتاب‌کار مربوط به نمودار؛ 2) به عنوان مقدار literal.

## متدها

| متد | توضیح |
| --- | --- |
| [getAsLiteralString()](#getAsLiteralString--) | اگر ویژگی DataSourceType مقدار DataSourceType.StringLiterals باشد، رشتهٔ literal را برمی‌گرداند یا تنظیم می‌کند. |
| [setAsLiteralString(String value)](#setAsLiteralString-java.lang.String-) | اگر ویژگی DataSourceType مقدار DataSourceType.StringLiterals باشد، رشتهٔ literal را برمی‌گرداند یا تنظیم می‌کند. |
| [toString()](#toString--) | نمایش رشته‌ای را برمی‌گرداند. |
| [setFromOneCell(IChartDataCell cell)](#setFromOneCell-com.aspose.slides.IChartDataCell-) | مقدار را از سلول مشخص‌شده تنظیم می‌کند. |
| [getCellsAddressInWorkbook()](#getCellsAddressInWorkbook--) | اگر ویژگی DataSourceType مقدار DataSourceType.Worksheet باشد، این متد آدرس سلول‌های موجود در کتاب‌کار که داده‌های رشته‌ای را نمایش می‌دهند، برمی‌گرداند. |

### getAsLiteralString() {#getAsLiteralString--}
```
public abstract String getAsLiteralString()
```

در صورتی که ویژگی DataSourceType مقدار DataSourceType.StringLiterals باشد، رشتهٔ literal را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی String.

**بازگشت:**  
java.lang.String

### setAsLiteralString(String value) {#setAsLiteralString-java.lang.String-}
```
public abstract void setAsLiteralString(String value)
```

در صورتی که ویژگی DataSourceType مقدار DataSourceType.StringLiterals باشد، رشتهٔ literal را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی String.

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |

### toString() {#toString--}
```
public abstract String toString()
```

نمایش رشته‌ای را برمی‌گرداند.

**بازگشت:**  
java.lang.String - نمایش رشته‌ای یک مقدار String

### setFromOneCell(IChartDataCell cell) {#setFromOneCell-com.aspose.slides.IChartDataCell-}
```
public abstract void setFromOneCell(IChartDataCell cell)
```

مقدار را از سلول مشخص‌شده تنظیم می‌کند.

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| cell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Cell. |

### getCellsAddressInWorkbook() {#getCellsAddressInWorkbook--}
```
public abstract String getCellsAddressInWorkbook()
```

اگر ویژگی DataSourceType مقدار DataSourceType.Worksheet باشد، این متد آدرس سلول‌های موجود در کتاب‌کار که داده‌های رشته‌ای را نمایش می‌دهند، برمی‌گرداند. در غیر این صورت رشتهٔ خالی را برمی‌گرداند.

**بازگشت:**  
java.lang.String - مقدار رشته‌ای String