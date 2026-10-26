---
title: IStringChartValue
second_title: Aspose.Slides برای اندروید از طریق مرجع API جاوا
description: نمایش مقدار رشته‌ای که می‌تواند در سند ارائه pptx به دو روش ذخیره شود: 1 در سلول/سلول‌های کتاب کار مرتبط با نمودار 2 به عنوان مقدار صریح.
type: docs
url: /fa/com.aspose.slides/istringchartvalue/
---
**تمام واسط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IMultipleCellChartValue](../../com.aspose.slides/imultiplecellchartvalue)
```
public interface IStringChartValue extends IMultipleCellChartValue
```

نمایش مقدار رشته‌ای که می‌تواند در سند ارائهٔ pptx به دو روش ذخیره شود: 1) در سلول/سلول‌های کتاب کار مرتبط با نمودار؛ 2) به‌عنوان مقدار صریح.
## متدها

| متد | توضیح |
| --- | --- |
| [getAsLiteralString()](#getAsLiteralString--) | اگر ویژگی DataSourceType برابر DataSourceType.StringLiterals باشد، رشتهٔ صریح را برمی‌گرداند یا تنظیم می‌کند. |
| [setAsLiteralString(String value)](#setAsLiteralString-java.lang.String-) | اگر ویژگی DataSourceType برابر DataSourceType.StringLiterals باشد، رشتهٔ صریح را برمی‌گرداند یا تنظیم می‌کند. |
| [toString()](#toString--) | نمایش رشته‌ای را برمی‌گرداند. |
| [setFromOneCell(IChartDataCell cell)](#setFromOneCell-com.aspose.slides.IChartDataCell-) | مقدار را از سلول مشخص‌شده تنظیم می‌کند. |
| [getCellsAddressInWorkbook()](#getCellsAddressInWorkbook--) | اگر ویژگی DataSourceType برابر DataSourceType.Worksheet باشد، این متد آدرس سلول‌های کتاب‌کار که دادهٔ رشته‌ای را نشان می‌دهند برمی‌گرداند. |

### getAsLiteralString() {#getAsLiteralString--}
```
public abstract String getAsLiteralString()
```

اگر ویژگی DataSourceType برابر DataSourceType.StringLiterals باشد، رشتهٔ صریح را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی String.

**باز می‌گرداند:**
java.lang.String

### setAsLiteralString(String value) {#setAsLiteralString-java.lang.String-}
```
public abstract void setAsLiteralString(String value)
```

اگر ویژگی DataSourceType برابر DataSourceType.StringLiterals باشد، رشتهٔ صریح را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی String.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |

### toString() {#toString--}
```
public abstract String toString()
```

نمایش رشته‌ای را برمی‌گرداند.

**باز می‌گرداند:**
java.lang.String - نمایش رشته‌ای از مقدار String

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

اگر ویژگی DataSourceType برابر DataSourceType.Worksheet باشد، این متد آدرس سلول‌های کتاب‌کار که دادهٔ رشته‌ای را نشان می‌دهند برمی‌گرداند. در غیر این صورت رشتهٔ خالی برمی‌گردد.

**باز می‌گرداند:**
java.lang.String - مقدار رشته‌ای String