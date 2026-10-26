---
title: IChartCategory
second_title: Aspose.Slides for Java API Reference
description: Represents chart categories.
type: docs
url: /fa/com.aspose.slides/ichartcategory/
---```
public interface IChartCategory
```

Represents chart categories.
## متدها

| متد | توضیح |
| --- | --- |
| [getUseCell()](#getUseCell--) | اگر مقدار true باشد، ویژگی AsCell واقعی است. |
| [getAsCell()](#getAsCell--) | شیء IChartDataCell را برمی‌گرداند یا تنظیم می‌کند. |
| [setAsCell(IChartDataCell value)](#setAsCell-com.aspose.slides.IChartDataCell-) | شیء IChartDataCell را برمی‌گرداند یا تنظیم می‌کند. |
| [getAsLiteral()](#getAsLiteral--) | اگر UseCell false باشد، AsLiteral را برمی‌گرداند یا تنظیم می‌کند. |
| [setAsLiteral(Object value)](#setAsLiteral-java.lang.Object-) | اگر UseCell false باشد، AsLiteral را برمی‌گرداند یا تنظیم می‌کند. |
| [getValue()](#getValue--) | اگر UseCell true باشد، این ویژگی نمایانگر ویژگی AsCell.Value است. |
| [setValue(Object value)](#setValue-java.lang.Object-) | اگر UseCell true باشد، این ویژگی نمایانگر ویژگی AsCell.Value است. |
| [getGroupingLevels()](#getGroupingLevels--) | محفظه مدیریت شدهٔ مقادیر سطوح گروه‌بندی دسته‌های نمودار. |
| [remove()](#remove--) | دسته را از نمودار حذف می‌کند. |
### getUseCell() {#getUseCell--}
```
public abstract boolean getUseCell()
```


اگر مقدار true باشد، ویژگی AsCell واقعی است. به عبارت دیگر، برگه کاری برای ذخیره‌سازی دسته استفاده می‌شود (این حالت از دسته‌بندی چندسطحی پشتیبانی می‌کند). اگر مقدار false باشد، ویژگی AsLiteral واقعی است. به عبارت دیگر، برگه کاری برای ذخیره‌سازی دسته استفاده نمی‌شود (و این حالت از دسته‌های چندسطحی پشتیبانی نمی‌کند). نوع boolean فقط-خواندنی.

--------------------

برای تغییر مقدار این ویژگی (برای همهٔ دسته‌ها در مجموعه) مقدار جدید را به ویژگی [ChartCategoryCollection.getUseCells()](../../com.aspose.slides/chartcategorycollection\#getUseCells--) تنظیم کنید.

**بازگشت:**
boolean
### getAsCell() {#getAsCell--}
```
public abstract IChartDataCell getAsCell()
```


شیء IChartDataCell را برمی‌گرداند یا تنظیم می‌کند. اگر دسته چندسطحی باشد، شیء IChartDataCell برای سطح "0" استفاده می‌شود. خواند/نوشتن [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**بازگشت:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setAsCell(IChartDataCell value) {#setAsCell-com.aspose.slides.IChartDataCell-}
```
public abstract void setAsCell(IChartDataCell value)
```


شیء IChartDataCell را برمی‌گرداند یا تنظیم می‌کند. اگر دسته چندسطحی باشد، شیء IChartDataCell برای سطح "0" استفاده می‌شود. خواند/نوشتن [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |

### getAsLiteral() {#getAsLiteral--}
```
public abstract Object getAsLiteral()
```


اگر UseCell false باشد، AsLiteral را برمی‌گرداند یا تنظیم می‌کند. خواند/نوشتن Object.

**بازگشت:**
java.lang.Object
### setAsLiteral(Object value) {#setAsLiteral-java.lang.Object-}
```
public abstract void setAsLiteral(Object value)
```


اگر UseCell false باشد، AsLiteral را برمی‌گرداند یا تنظیم می‌کند. خواند/نوشتن Object.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.Object |  |

### getValue() {#getValue--}
```
public abstract Object getValue()
```


اگر UseCell true باشد، این ویژگی نمایانگر ویژگی AsCell.Value است. اگر UseCell false باشد، این ویژگی نمایانگر ویژگی AsLiteral است. خواند/نوشتن Object.

**بازگشت:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public abstract void setValue(Object value)
```


اگر UseCell true باشد، این ویژگی نمایانگر ویژگی AsCell.Value است. اگر UseCell false باشد، این ویژگی نمایانگر ویژگی AsLiteral است. خواند/نوشتن Object.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.Object |  |

### getGroupingLevels() {#getGroupingLevels--}
```
public abstract IChartCategoryLevelsManager getGroupingLevels()
```


محفظه مدیریت شدهٔ مقادیر سطوح گروه‌بندی دسته‌های نمودار. دستهٔ چندسطحی بیش از یک سطح گروه‌بندی دارد. ایندکس‌گذاری سطوح گروه‌بندی از صفر آغاز می‌شود. فقط-خواندنی [IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager).

**بازگشت:**
[IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager)
### remove() {#remove--}
```
public abstract void remove()
```


دسته را از نمودار حذف می‌کند.