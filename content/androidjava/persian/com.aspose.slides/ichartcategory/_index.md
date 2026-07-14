---
title: IChartCategory
second_title: Aspose.Slides for Android via Java API Reference
description: دسته‌بندی‌های نمودار را نمایش می‌دهد.
type: docs
url: /fa/com.aspose.slides/ichartcategory/
---```
public interface IChartCategory
```

دسته‌بندی‌های نمودار را نمایش می‌دهد.
## Methods

| متد | توضیح |
| --- | --- |
| [getUseCell()](#getUseCell--) | اگر مقدار true باشد، خصوصیت AsCell فعال است. |
| [getAsCell()](#getAsCell--) | مقدار یا تنظیم شی IChartDataCell. |
| [setAsCell(IChartDataCell value)](#setAsCell-com.aspose.slides.IChartDataCell-) | مقدار یا تنظیم شی IChartDataCell. |
| [getAsLiteral()](#getAsLiteral--) | مقدار یا تنظیم AsLiteral در صورت false بودن UseCell. |
| [setAsLiteral(Object value)](#setAsLiteral-java.lang.Object-) | مقدار یا تنظیم AsLiteral در صورت false بودن UseCell. |
| [getValue()](#getValue--) | اگر UseCell مقدار true باشد، این خصوصیت معرف خصوصیت AsCell.Value است. |
| [setValue(Object value)](#setValue-java.lang.Object-) | اگر UseCell مقدار true باشد، این خصوصیت معرف خصوصیت AsCell.Value است. |
| [getGroupingLevels()](#getGroupingLevels--) | محفظه مدیریت‌شدهٔ مقادیر سطوح گروه‌بندی دسته‌بندی نمودار. |
| [remove()](#remove--) | دسته‌بندی را از نمودار حذف می‌کند. |
### getUseCell() {#getUseCell--}
```
public abstract boolean getUseCell()
```

اگر مقدار true باشد، خصوصیت AsCell فعال است. به عبارت دیگر، worksheet برای ذخیره‌سازی دسته‌بندی استفاده می‌شود (در این حالت از دسته‌بندی چندسطحی پشتیبانی می‌کند). اگر مقدار false باشد، خصوصیت AsLiteral فعال است. به عبارت دیگر، worksheet برای ذخیره‌سازی دسته‌بندی استفاده نمی‌شود (و در این حالت از دسته‌بندی‌های چندسطحی پشتیبانی نمی‌کند). فقط خواندنی (boolean).

--------------------

برای تغییر مقدار این خصوصیت (برای همه دسته‌ها در مجموعه) مقدار جدید را در خصوصیت [ChartCategoryCollection.getUseCells()](../../com.aspose.slides/chartcategorycollection\#getUseCells--) تنظیم کنید.

**بازگشت:**  
boolean
### getAsCell() {#getAsCell--}
```
public abstract IChartDataCell getAsCell()
```

مقدار یا تنظیم شی IChartDataCell. اگر دسته‌بندی چندسطحی باشد، شی IChartDataCell برای سطح "0" استفاده می‌شود. خواندن/نوشتن [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**بازگشت:**  
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setAsCell(IChartDataCell value) {#setAsCell-com.aspose.slides.IChartDataCell-}
```
public abstract void setAsCell(IChartDataCell value)
```

مقدار یا تنظیم شی IChartDataCell. اگر دسته‌بندی چندسطحی باشد، شی IChartDataCell برای سطح "0" استفاده می‌شود. خواندن/نوشتن [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |

### getAsLiteral() {#getAsLiteral--}
```
public abstract Object getAsLiteral()
```

مقدار یا تنظیم AsLiteral در صورت false بودن UseCell. خواندن/نوشتن Object.

**بازگشت:**  
java.lang.Object
### setAsLiteral(Object value) {#setAsLiteral-java.lang.Object-}
```
public abstract void setAsLiteral(Object value)
```

مقدار یا تنظیم AsLiteral در صورت false بودن UseCell. خواندن/نوشتن Object.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.Object |  |

### getValue() {#getValue--}
```
public abstract Object getValue()
```

اگر UseCell مقدار true باشد، این خصوصیت معرف خصوصیت AsCell.Value است. اگر UseCell مقدار false باشد، این خصوصیت معرف خصوصیت AsLiteral است. خواندن/نوشتن Object.

**بازگشت:**  
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public abstract void setValue(Object value)
```

اگر UseCell مقدار true باشد، این خصوصیت معرف خصوصیت AsCell.Value است. اگر UseCell مقدار false باشد، این خصوصیت معرف خصوصیت AsLiteral است. خواندن/نوشتن Object.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.Object |  |

### getGroupingLevels() {#getGroupingLevels--}
```
public abstract IChartCategoryLevelsManager getGroupingLevels()
```

محفظه مدیریت‌شدهٔ مقادیر سطوح گروه‌بندی دسته‌بندی نمودار. دسته‌بندی چندسطحی بیش از یک سطح گروه‌بندی دارد. ایندکس‌گذاری سطوح گروه‌بندی از صفر شروع می‌شود. فقط خواندنی [IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager).

**بازگشت:**  
[IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager)
### remove() {#remove--}
```
public abstract void remove()
```

دسته‌بندی را از نمودار حذف می‌کند.