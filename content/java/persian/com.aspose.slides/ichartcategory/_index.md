---
title: IChartCategory
second_title: Aspose.Slides for Java API Reference
description: Represents chart categories.
type: docs
url: /fa/com.aspose.slides/ichartcategory/
---```
public interface IChartCategory
```

دسته‌های نمودار را نشان می‌دهد.
## متدها

| متد | توضیح |
| --- | --- |
| [getUseCell()](#getUseCell--) | اگر مقدار true باشد، ویژگی AsCell معتبر است. |
| [getAsCell()](#getAsCell--) | شیء IChartDataCell را برمی‌گرداند یا تنظیم می‌کند. |
| [setAsCell(IChartDataCell value)](#setAsCell-com.aspose.slides.IChartDataCell-) | شیء IChartDataCell را برمی‌گرداند یا تنظیم می‌کند. |
| [getAsLiteral()](#getAsLiteral--) | اگر UseCell برابر false باشد، AsLiteral را برمی‌گرداند یا تنظیم می‌کند. |
| [setAsLiteral(Object value)](#setAsLiteral-java.lang.Object-) | اگر UseCell برابر false باشد، AsLiteral را برمی‌گرداند یا تنظیم می‌کند. |
| [getValue()](#getValue--) | اگر UseCell برابر true باشد، این ویژگی نمایانگر ویژگی AsCell.Value است. |
| [setValue(Object value)](#setValue-java.lang.Object-) | اگر UseCell برابر true باشد، این ویژگی نمایانگر ویژگی AsCell.Value است. |
| [getCachedValue()](#getCachedValue--) | مقدار ذخیره‌شده‌ی یک دستهٔ نمودار را دریافت می‌کند. |
| [getGroupingLevels()](#getGroupingLevels--) | محفظه‌ای مدیریت‌شده برای مقادیر سطوح گروه‌بندی دستهٔ نمودار. |
| [remove()](#remove--) | دسته را از نمودار حذف می‌کند. |
### getUseCell() {#getUseCell--}
```
public abstract boolean getUseCell()
```


اگر مقدار true باشد، ویژگی AsCell معتبر است. به عبارت دیگر، worksheet برای ذخیره‌سازی دسته استفاده می‌شود (این حالت از دسته‌بندی چندسطحی پشتیبانی می‌کند). اگر مقدار false باشد، ویژگی AsLiteral معتبر است. به عبارت دیگر، worksheet برای ذخیره‌سازی دسته استفاده نمی‌شود (و این حالت از دسته‌بندی چندسطحی پشتیبانی نمی‌کند). بولی فقط‌خواندنی.

--------------------

برای تغییر مقدار این ویژگی (برای تمام دسته‌ها در مجموعه) مقدار جدید را به ویژگی [ChartCategoryCollection.getUseCells()](../../com.aspose.slides/chartcategorycollection\#getUseCells--) اختصاص دهید.

**بازگشت:**
boolean
### getAsCell() {#getAsCell--}
```
public abstract IChartDataCell getAsCell()
```


شیء IChartDataCell را برمی‌گرداند یا تنظیم می‌کند. اگر دسته چندسطحی باشد، از شیء IChartDataCell برای سطح «0» استفاده می‌شود. قابل‌نوشتن [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**بازگشت:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setAsCell(IChartDataCell value) {#setAsCell-com.aspose.slides.IChartDataCell-}
```
public abstract void setAsCell(IChartDataCell value)
```


شیء IChartDataCell را برمی‌گرداند یا تنظیم می‌کند. اگر دسته چندسطحی باشد، از شیء IChartDataCell برای سطح «0» استفاده می‌شود. قابل‌نوشتن [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |

### getAsLiteral() {#getAsLiteral--}
```
public abstract Object getAsLiteral()
```


اگر UseCell برابر false باشد، AsLiteral را برمی‌گرداند یا تنظیم می‌کند. قابل‌نوشتن Object.

**بازگشت:**
java.lang.Object
### setAsLiteral(Object value) {#setAsLiteral-java.lang.Object-}
```
public abstract void setAsLiteral(Object value)
```


اگر UseCell برابر false باشد، AsLiteral را برمی‌گرداند یا تنظیم می‌کند. قابل‌نوشتن Object.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.Object |  |

### getValue() {#getValue--}
```
public abstract Object getValue()
```


اگر UseCell برابر true باشد، این ویژگی نمایانگر ویژگی AsCell.Value است. اگر UseCell برابر false باشد، این ویژگی نمایانگر ویژگی AsLiteral است. قابل‌نوشتن Object.

**بازگشت:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public abstract void setValue(Object value)
```


اگر UseCell برابر true باشد، این ویژگی نمایانگر ویژگی AsCell.Value است. اگر UseCell برابر false باشد، این ویژگی نمایانگر ویژگی AsLiteral است. قابل‌نوشتن Object.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.Object |  |

### getCachedValue() {#getCachedValue--}
```
public abstract ICachedChartValue getCachedValue()
```


مقدار ذخیره‌شده‌ی یک دستهٔ نمودار را دریافت می‌کند. فقط‌خواندنی [ICachedChartValue](../../com.aspose.slides/icachedchartvalue).

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
> 
>      // تمام مقادیر ذخیره‌شدهٔ دسته‌های نمودار را چاپ کنید.
>      for (IChartCategory category : chart.getChartData().getCategories())
>          System.out.println(category.getCachedValue().toString());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**بازگشت:**
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)
### getGroupingLevels() {#getGroupingLevels--}
```
public abstract IChartCategoryLevelsManager getGroupingLevels()
```


محفظه‌ای مدیریت‌شده برای مقادیر سطوح گروه‌بندی دستهٔ نمودار. دسته‌بندی چندسطحی بیش از یک سطح گروه‌بندی دارد. ایندکس‌گذاری سطوح گروه‌بندی صفر-پایه است. فقط‌خواندنی [IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager).

**بازگشت:**
[IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager)
### remove() {#remove--}
```
public abstract void remove()
```


دسته را از نمودار حذف می‌کند.