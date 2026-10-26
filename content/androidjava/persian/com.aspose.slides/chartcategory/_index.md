---
title: ChartCategory
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: دسته‌بندی‌های نمودار را نمایندگی می‌کند.
type: docs
url: /fa/com.aspose.slides/chartcategory/
---
**ارث‌بری:**
java.lang.Object

**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IChartCategory](../../com.aspose.slides/ichartcategory), com.aspose.slides.IDOMObject
```
public class ChartCategory implements IChartCategory, IDOMObject
```

دسته‌بندی‌های نمودار را نمایش می‌دهد.
## متدها

| Method | Description |
| --- | --- |
| [getUseCell()](#getUseCell--) | اگر مقدار true باشد، ویژگی AsCell معتبر است. |
| [getAsCell()](#getAsCell--) | مقدار IChartDataCell را باز می‌گرداند یا تنظیم می‌کند. |
| [setAsCell(IChartDataCell value)](#setAsCell-com.aspose.slides.IChartDataCell-) | مقدار IChartDataCell را باز می‌گرداند یا تنظیم می‌کند. |
| [getAsLiteral()](#getAsLiteral--) | مقدار AsLiteral را باز می‌گرداند یا تنظیم می‌کند. |
| [setAsLiteral(Object value)](#setAsLiteral-java.lang.Object-) | مقدار AsLiteral را باز می‌گرداند یا تنظیم می‌کند. |
| [getValue()](#getValue--) | اگر UseCell برابر true باشد، این ویژگی نمایانگر ویژگی AsCell.Value است. |
| [setValue(Object value)](#setValue-java.lang.Object-) | اگر UseCell برابر true باشد، این ویژگی نمایانگر ویژگی AsCell.Value است. |
| [getGroupingLevels()](#getGroupingLevels--) | محفظه مدیریت‌شده‌ای برای مقادیر سطوح گروه‌بندی دسته‌بندهای نمودار. |
| [remove()](#remove--) | دسته‌بندی را از نمودار حذف می‌کند. |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### getUseCell() {#getUseCell--}
```
public final boolean getUseCell()
```

اگر مقدار true باشد، ویژگی AsCell معتبر است. به عبارت دیگر، ورک‌شیت برای ذخیره‌سازی دسته‌بندی استفاده می‌شود (این حالت از دسته‌بندی چندسطحه‌ای پشتیبانی می‌کند). اگر مقدار false باشد، ویژگی AsLiteral معتبر است. به عبارت دیگر، ورک‌شیت برای ذخیره‌سازی دسته‌بندی استفاده نمی‌شود (و این حالت از دسته‌بندی‌های چندسطحه‌ای پشتیبانی نمی‌کند). فقط‌خواندنی (boolean).

--------------------

برای تغییر مقدار این ویژگی (برای تمام دسته‌بندها در مجموعه) مقدار جدید را در ویژگی ChartCategoryCollection.UseCells تنظیم کنید.

**بازگشت:**
boolean

### getAsCell() {#getAsCell--}
```
public final IChartDataCell getAsCell()
```

مقدار IChartDataCell را باز می‌گرداند یا تنظیم می‌کند. اگر دسته‌بندی چندسطحه‌ای باشد، از شیء IChartDataCell برای سطح "0" استفاده می‌شود. قابل‌خواندن/نوشتن [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**بازگشت:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)

### setAsCell(IChartDataCell value) {#setAsCell-com.aspose.slides.IChartDataCell-}
```
public final void setAsCell(IChartDataCell value)
```

مقدار IChartDataCell را باز می‌گرداند یا تنظیم می‌کند. اگر دسته‌بندی چندسطحه‌ای باشد، از شیء IChartDataCell برای سطح "0" استفاده می‌شود. قابل‌خواندن/نوشتن [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |

### getAsLiteral() {#getAsLiteral--}
```
public final Object getAsLiteral()
```

مقدار AsLiteral را باز می‌گرداند یا تنظیم می‌کند. قابل‌خواندن/نوشتن Object.

**بازگشت:**
java.lang.Object

### setAsLiteral(Object value) {#setAsLiteral-java.lang.Object-}
```
public final void setAsLiteral(Object value)
```

مقدار AsLiteral را باز می‌گرداند یا تنظیم می‌کند. قابل‌خواندن/نوشتن Object.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Object |  |

### getValue() {#getValue--}
```
public final Object getValue()
```

اگر UseCell برابر true باشد، این ویژگی نمایانگر ویژگی AsCell.Value است. اگر UseCell برابر false باشد، این ویژگی نمایانگر ویژگی AsLiteral است. قابل‌خواندن/نوشتن Object.

**بازگشت:**
java.lang.Object

### setValue(Object value) {#setValue-java.lang.Object-}
```
public final void setValue(Object value)
```

اگر UseCell برابر true باشد، این ویژگی نمایانگر ویژگی AsCell.Value است. اگر UseCell برابر false باشد، این ویژگی نمایانگر ویژگی AsLiteral است. قابل‌خواندن/نوشتن Object.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Object |  |

### getGroupingLevels() {#getGroupingLevels--}
```
public final IChartCategoryLevelsManager getGroupingLevels()
```

محفظه مدیریت‌شده‌ای برای مقادیر سطوح گروه‌بندی دسته‌بندهای نمودار. دسته‌بندهای چندسطحه‌ای بیش از یک سطح گروه‌بندی دارند. ایندکس‌گذاری سطوح گروه‌بندی از صفر شروع می‌شود. فقط‌خواندنی [IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager).

**بازگشت:**
[IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager)

### remove() {#remove--}
```
public final void remove()
```

دسته‌بندی را از نمودار حذف می‌کند.

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

شیء Parent_Immediate را باز می‌گرداند. فقط‌خواندنی IDOMObject.

**بازگشت:**
com.aspose.slides.IDOMObject