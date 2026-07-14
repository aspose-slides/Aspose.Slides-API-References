---
title: StringChartValue
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: نمایش مقدار رشته‌ای که می‌تواند به دو شکل در سند ارائه pptx ذخیره شود: 1 در سلول/سلول‌های کتاب کار مرتبط با نمودار 2 به عنوان مقدار صریح.
type: docs
url: /fa/com.aspose.slides/stringchartvalue/
---
**Inheritance:**  
ارث‌بری:

[com.aspose.slides.BaseChartValue](../../com.aspose.slides/basechartvalue)

**All Implemented Interfaces:**  
تمام رابط‌های پیاده‌سازی‌شده:

[com.aspose.slides.IStringChartValue](../../com.aspose.slides/istringchartvalue)
```
public class StringChartValue extends BaseChartValue implements IStringChartValue
```

یک مقدار رشته‌ای را که می‌تواند به دو شکل در سند ارائهٔ pptx ذخیره شود، نمایش می‌دهد: 1) در سلول/سلول‌های کتاب کاری مرتبط با نمودار؛ 2) به عنوان مقدار صریح.
## متدها

| متد | توضیح |
| --- | --- |
| [getAsCells()](#getAsCells--) | انتساب مقدار null مجاز نیست. |
| [setAsCells(IChartCellCollection value)](#setAsCells-com.aspose.slides.IChartCellCollection-) | انتساب مقدار null مجاز نیست. |
| [getAsLiteralString()](#getAsLiteralString--) | مقدار را به عنوان رشتهٔ صریح بازمی‌گرداند یا تعیین می‌کند. |
| [setAsLiteralString(String value)](#setAsLiteralString-java.lang.String-) | مقدار را به عنوان رشتهٔ صریح بازمی‌گرداند یا تعیین می‌کند. |
| [getData()](#getData--) | شیء Data را بازمی‌گرداند یا تعیین می‌کند. |
| [setData(Object value)](#setData-java.lang.Object-) | شیء Data را بازمی‌گرداند یا تعیین می‌کند. |
| [toString()](#toString--) | دادهٔ مقدار رشته‌ای را بازمی‌گرداند. |
| [setFromOneCell(IChartDataCell cell)](#setFromOneCell-com.aspose.slides.IChartDataCell-) | مقدار را از سلول مشخص‌شده تنظیم می‌کند. |
| [getCellsAddressInWorkbook()](#getCellsAddressInWorkbook--) | اگر ویژگی DataSourceType برابر DataSourceType.Worksheet باشد، این متد آدرس سلول‌های موجود در کتاب کار که دادهٔ رشته‌ای را نمایان می‌کنند، برمی‌گرداند. |

### getAsCells() {#getAsCells--}
```
public final IChartCellCollection getAsCells()
```

انتساب مقدار null مجاز نیست. مقدار بازگشتی همیشه null نیست. خواندن/نوشتن [IChartCellCollection](../../com.aspose.slides/ichartcellcollection).

**بازگرداندن:**  
[IChartCellCollection](../../com.aspose.slides/ichartcellcollection)

### setAsCells(IChartCellCollection value) {#setAsCells-com.aspose.slides.IChartCellCollection-}
```
public final void setAsCells(IChartCellCollection value)
```

انتساب مقدار null مجاز نیست. مقدار بازگشتی همیشه null نیست. خواندن/نوشتن [IChartCellCollection](../../com.aspose.slides/ichartcellcollection).

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IChartCellCollection](../../com.aspose.slides/ichartcellcollection) |  |

### getAsLiteralString() {#getAsLiteralString--}
```
public final String getAsLiteralString()
```

مقدار را به عنوان رشتهٔ صریح بازمی‌گرداند یا تعیین می‌کند. خواندن/نوشتن String.

**بازگرداندن:**  
java.lang.String

### setAsLiteralString(String value) {#setAsLiteralString-java.lang.String-}
```
public final void setAsLiteralString(String value)
```

مقدار را به عنوان رشتهٔ صریح بازمی‌گرداند یا تعیین می‌کند. خواندن/نوشتن String.

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |

### getData() {#getData--}
```
public Object getData()
```

شیء Data را بازمی‌گرداند یا تعیین می‌کند. خواندن/نوشتن Object.

**بازگرداندن:**  
java.lang.Object

### setData(Object value) {#setData-java.lang.Object-}
```
public void setData(Object value)
```

شیء Data را بازمی‌گرداند یا تعیین می‌کند. خواندن/نوشتن Object.

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.Object |  |

### toString() {#toString--}
```
public String toString()
```

دادهٔ مقدار رشته‌ای را بازمی‌گرداند. اگر DataSourceType نادرست باشد و هیچ مقدار رشته‌ای تعیین نشده باشد، null برمی‌گرداند.

**بازگرداندن:**  
java.lang.String

### setFromOneCell(IChartDataCell cell) {#setFromOneCell-com.aspose.slides.IChartDataCell-}
```
public final void setFromOneCell(IChartDataCell cell)
```

مقدار را از سلول مشخص‌شده تنظیم می‌کند.

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| cell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Cell. |

### getCellsAddressInWorkbook() {#getCellsAddressInWorkbook--}
```
public final String getCellsAddressInWorkbook()
```

اگر ویژگی DataSourceType برابر DataSourceType.Worksheet باشد، این متد آدرس سلول‌های موجود در کتاب کار که دادهٔ رشته‌ای را نمایان می‌کنند، برمی‌گرداند. در غیر این صورت رشتهٔ خالی برمی‌گرداند.

**بازگرداندن:**  
java.lang.String