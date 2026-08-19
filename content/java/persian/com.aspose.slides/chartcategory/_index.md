---
title: ChartCategory
second_title: مرجع API Aspose.Slides برای Java
description: دسته‌های نمودار را نشان می‌دهد.
type: docs
url: /fa/com.aspose.slides/chartcategory/
---
**ارث‌بری:**
java.lang.Object

**تمام رابط‌های پیاده‌سازی شده:**
[com.aspose.slides.IChartCategory](../../com.aspose.slides/ichartcategory), com.aspose.slides.IDOMObject
```
public class ChartCategory implements IChartCategory, IDOMObject
```

دسته‌های نمودار را نشان می‌دهد.
## متدها

| متد | توضیح |
| --- | --- |
| [getUseCell()](#getUseCell--) | اگر true باشد، ویژگی AsCell فعال است. |
| [getAsCell()](#getAsCell--) | شیء IChartDataCell را برمی‌گرداند یا تنظیم می‌کند. |
| [setAsCell(IChartDataCell value)](#setAsCell-com.aspose.slides.IChartDataCell-) | شیء IChartDataCell را برمی‌گرداند یا تنظیم می‌کند. |
| [getAsLiteral()](#getAsLiteral--) | شیء AsLiteral را برمی‌گرداند یا تنظیم می‌کند. |
| [setAsLiteral(Object value)](#setAsLiteral-java.lang.Object-) | شیء AsLiteral را برمی‌گرداند یا تنظیم می‌کند. |
| [getValue()](#getValue--) | اگر UseCell برابر true باشد، این ویژگی نمایانگر ویژگی AsCell.Value است. |
| [setValue(Object value)](#setValue-java.lang.Object-) | اگر UseCell برابر true باشد، این ویژگی نمایانگر ویژگی AsCell.Value است. |
| [getGroupingLevels()](#getGroupingLevels--) | محفظه مدیریت شده مقادیر سطوح گروه‌بندی دسته نمودار. |
| [remove()](#remove--) | دسته را از نمودار حذف می‌کند. |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### getUseCell() {#getUseCell--}
```
public final boolean getUseCell()
```

اگر مقدار true باشد، ویژگی AsCell فعال است. به عبارت دیگر، Worksheet برای ذخیره‌سازی دسته استفاده می‌شود (این حالت از دسته چندسطحی پشتیبانی می‌کند). اگر مقدار false باشد، ویژگی AsLiteral فعال است. به عبارت دیگر، Worksheet برای ذخیره‌سازی دسته استفاده نمی‌شود (و این حالت از دسته‌های چندسطحی پشتیبانی نمی‌کند). boolean فقط خواندنی.

--------------------

برای تغییر مقدار این ویژگی (برای تمام دسته‌ها در مجموعه) مقدار جدید را به ویژگی ChartCategoryCollection.UseCells تنظیم کنید.

**بازگشت:**
boolean

### getAsCell() {#getAsCell--}
```
public final IChartDataCell getAsCell()
```

شیء IChartDataCell را برمی‌گرداند یا تنظیم می‌کند. اگر دسته چندسطحی باشد، شیء IChartDataCell برای سطح "0" استفاده می‌شود. خواندنی/نوشتنی [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**بازگشت:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)

### setAsCell(IChartDataCell value) {#setAsCell-com.aspose.slides.IChartDataCell-}
```
public final void setAsCell(IChartDataCell value)
```

شیء IChartDataCell را برمی‌گرداند یا تنظیم می‌کند. اگر دسته چندسطحی باشد، شیء IChartDataCell برای سطح "0" استفاده می‌شود. خواندنی/نوشتنی [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |

### getAsLiteral() {#getAsLiteral--}
```
public final Object getAsLiteral()
```

شیء AsLiteral را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی Object.

**بازگشت:**
java.lang.Object

### setAsLiteral(Object value) {#setAsLiteral-java.lang.Object-}
```
public final void setAsLiteral(Object value)
```

شیء AsLiteral را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی Object.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.Object |  |

### getValue() {#getValue--}
```
public final Object getValue()
```

اگر UseCell برابر true باشد، این ویژگی نمایانگر ویژگی AsCell.Value است. اگر UseCell برابر false باشد، این ویژگی نمایانگر ویژگی AsLiteral است. خواندنی/نوشتنی Object.

**بازگشت:**
java.lang.Object

### setValue(Object value) {#setValue-java.lang.Object-}
```
public final void setValue(Object value)
```

اگر UseCell برابر true باشد، این ویژگی نمایانگر ویژگی AsCell.Value است. اگر UseCell برابر false باشد، این ویژگی نمایانگر ویژگی AsLiteral است. خواندنی/نوشتنی Object.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.Object |  |

### getGroupingLevels() {#getGroupingLevels--}
```
public final IChartCategoryLevelsManager getGroupingLevels()
```

محفظه مدیریت شده مقادیر سطوح گروه‌بندی دسته نمودار. دسته چندسطحی دارای بیش از یک سطح گروه‌بندی است. ایندکس‌گذاری سطوح گروه‌بندی از صفر شروع می‌شود. فقط خواندنی [IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager).

**بازگشت:**
[IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager)

### remove() {#remove--}
```
public final void remove()
```

دسته را از نمودار حذف می‌کند.

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

شیء Parent_Immediate را برمی‌گرداند. فقط خواندنی IDOMObject.

**بازگشت:**
com.aspose.slides.IDOMObject