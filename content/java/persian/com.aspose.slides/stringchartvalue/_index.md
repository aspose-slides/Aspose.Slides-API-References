---
title: StringChartValue
second_title: مرجع API Aspose.Slides برای جاوا
description: نمایش مقدار رشته‌ای که می‌تواند در سند ارائهٔ pptx به دو روش ذخیره شود: 1) در سلول/سلول‌های workbook مربوط به نمودار؛ 2) به‌عنوان مقدار لغوی.
type: docs
url: /fa/com.aspose.slides/stringchartvalue/
---
**ارث‌بری:**
java.lang.Object, [com.aspose.slides.BaseChartValue](../../com.aspose.slides/basechartvalue)

**تمام اینترفیس‌های پیاده‌سازی شده:**
[com.aspose.slides.IStringChartValue](../../com.aspose.slides/istringchartvalue)
```
public class StringChartValue extends BaseChartValue implements IStringChartValue
```

نمایش مقدار رشته‌ای که می‌تواند در سند ارائهٔ pptx به دو روش ذخیره شود: 1) در سلول/سلول‌های workbook مربوط به نمودار؛ 2) به‌عنوان مقدار لغوی.
## متدها

| متد | توضیح |
| --- | --- |
| [getAsCells()](#getAsCells--) | تخصیص مقدار null مجاز نیست. |
| [setAsCells(IChartCellCollection value)](#setAsCells-com.aspose.slides.IChartCellCollection-) | تخصیص مقدار null مجاز نیست. |
| [getAsLiteralString()](#getAsLiteralString--) | مقدار را به عنوان رشتهٔ لغوی بر می‌گرداند یا تنظیم می‌کند. |
| [setAsLiteralString(String value)](#setAsLiteralString-java.lang.String-) | مقدار را به عنوان رشتهٔ لغوی بر می‌گرداند یا تنظیم می‌کند. |
| [getData()](#getData--) | شیء Data را بر می‌گرداند یا تنظیم می‌کند. |
| [setData(Object value)](#setData-java.lang.Object-) | شیء Data را بر می‌گرداند یا تنظیم می‌کند. |
| [toString()](#toString--) | دادهٔ مقدار رشته‌ای را بر می‌گرداند. |
| [setFromOneCell(IChartDataCell cell)](#setFromOneCell-com.aspose.slides.IChartDataCell-) | مقدار را از سلول مشخص شده تنظیم می‌کند. |
| [getCellsAddressInWorkbook()](#getCellsAddressInWorkbook--) | اگر ویژگی DataSourceType برابر DataSourceType.Worksheet باشد، این متد آدرس سلول‌های workbook را که دادهٔ رشته‌ای را نشان می‌دهند بر می‌گرداند. |

### getAsCells() {#getAsCells--}
```
public final IChartCellCollection getAsCells()
```

تخصیص مقدار null مجاز نیست. مقدار بازگردانده‌شده همواره غیر-null است. خواندنی/نوشتنی [IChartCellCollection](../../com.aspose.slides/ichartcellcollection).

**بازگرداندن:**
[IChartCellCollection](../../com.aspose.slides/ichartcellcollection)

### setAsCells(IChartCellCollection value) {#setAsCells-com.aspose.slides.IChartCellCollection-}
```
public final void setAsCells(IChartCellCollection value)
```

تخصیص مقدار null مجاز نیست. مقدار بازگردانده‌شده همواره غیر-null است. خواندنی/نوشتنی [IChartCellCollection](../../com.aspose.slides/ichartcellcollection).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IChartCellCollection](../../com.aspose.slides/ichartcellcollection) |  |

### getAsLiteralString() {#getAsLiteralString--}
```
public final String getAsLiteralString()
```

مقدار را به عنوان رشتهٔ لغوی بر می‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی String.

**بازگرداندن:**
java.lang.String

### setAsLiteralString(String value) {#setAsLiteralString-java.lang.String-}
```
public final void setAsLiteralString(String value)
```

مقدار را به عنوان رشتهٔ لغوی بر می‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی String.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |

### getData() {#getData--}
```
public Object getData()
```

شیء Data را بر می‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی Object.

**بازگرداندن:**
java.lang.Object

### setData(Object value) {#setData-java.lang.Object-}
```
public void setData(Object value)
```

شیء Data را بر می‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی Object.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.Object |  |

### toString() {#toString--}
```
public String toString()
```

دادهٔ مقدار رشته‌ای را بر می‌گرداند. اگر DataSourceType نادرست باشد و هیچ مقدار رشته‌ای اختصاص داده نشده باشد، null بر می‌گردد.

**بازگرداندن:**
java.lang.String

### setFromOneCell(IChartDataCell cell) {#setFromOneCell-com.aspose.slides.IChartDataCell-}
```
public final void setFromOneCell(IChartDataCell cell)
```

مقدار را از سلول مشخص شده تنظیم می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| cell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Cell. |

### getCellsAddressInWorkbook() {#getCellsAddressInWorkbook--}
```
public final String getCellsAddressInWorkbook()
```

اگر ویژگی DataSourceType برابر DataSourceType.Worksheet باشد، این متد آدرس سلول‌های workbook را که دادهٔ رشته‌ای را نشان می‌دهند بر می‌گرداند. در غیر این صورت رشتهٔ خالی بر می‌گردد.

**بازگرداندن:**
java.lang.String