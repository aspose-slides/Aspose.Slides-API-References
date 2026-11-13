---
title: ChartCategory
second_title: مرجع API Aspose.Slides برای جاوا
description: دسته‌های نمودار را نشان می‌دهد.
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

دسته‌های نمودار را نمایش می‌دهد.

## متدها

| متد | توضیح |
| --- | --- |
| [getUseCell()](#getUseCell--) | اگر مقدار true باشد، خاصیت AsCell واقعی است. |
| [getAsCell()](#getAsCell--) | شی IChartDataCell را بازمی‌گرداند یا تنظیم می‌کند. |
| [setAsCell(IChartDataCell value)](#setAsCell-com.aspose.slides.IChartDataCell-) | شی IChartDataCell را بازمی‌گرداند یا تنظیم می‌کند. |
| [getAsLiteral()](#getAsLiteral--) | شی AsLiteral را بازمی‌گرداند یا تنظیم می‌کند. |
| [setAsLiteral(Object value)](#setAsLiteral-java.lang.Object-) | شی AsLiteral را بازمی‌گرداند یا تنظیم می‌کند. |
| [getValue()](#getValue--) | اگر UseCell true باشد، این خاصیت نشان‌دهندهٔ خاصیت AsCell.Value است. |
| [setValue(Object value)](#setValue-java.lang.Object-) | اگر UseCell true باشد، این خاصیت نشان‌دهندهٔ خاصیت AsCell.Value است. |
| [getGroupingLevels()](#getGroupingLevels--) | ظرف مدیریت‌شدهٔ مقادیر سطوح گروه‌بندی دسته‌های نمودار. |
| [getCachedValue()](#getCachedValue--) | مقدار cached دستهٔ نمودار را دریافت می‌کند. |
| [remove()](#remove--) | دسته را از نمودار حذف می‌کند. |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### getUseCell() {#getUseCell--}
```
public final boolean getUseCell()
```

اگر مقدار true باشد، خاصیت AsCell واقعی است. به عبارت دیگر، worksheet برای ذخیره‌سازی دسته استفاده می‌شود (این حالت از دسته چندسطحی پشتیبانی می‌کند). اگر false باشد، خاصیت AsLiteral واقعی است. به عبارت دیگر، worksheet برای ذخیره‌سازی دسته استفاده نمی‌شود (و این حالت از دسته‌های چندسطحی پشتیبانی نمی‌کند). فقط‌خواندنی boolean.

--------------------

برای تغییر مقدار این خاصیت (برای تمام دسته‌ها در مجموعه) مقدار جدید را به خاصیت ChartCategoryCollection.UseCells تنظیم کنید.

**بازگشت:**  
boolean

### getAsCell() {#getAsCell--}
```
public final IChartDataCell getAsCell()
```

شی IChartDataCell را بازمی‌گرداند یا تنظیم می‌کند. اگر دسته چندسطحی باشد، شی IChartDataCell برای سطح «0» مورد استفاده قرار می‌گیرد. قابل‌خواندن‌نوشتن [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**بازگشت:**  
[IChartDataCell](../../com.aspose.slides/ichartdatacell)

### setAsCell(IChartDataCell value) {#setAsCell-com.aspose.slides.IChartDataCell-}
```
public final void setAsCell(IChartDataCell value)
```

شی IChartDataCell را بازمی‌گرداند یا تنظیم می‌کند. اگر دسته چندسطحی باشد، شی IChartDataCell برای سطح «0» مورد استفاده قرار می‌گیرد. قابل‌خواندن‌نوشتن [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |

### getAsLiteral() {#getAsLiteral--}
```
public final Object getAsLiteral()
```

شی AsLiteral را بازمی‌گرداند یا تنظیم می‌کند. قابل‌خواندن‌نوشتن Object.

**بازگشت:**  
java.lang.Object

### setAsLiteral(Object value) {#setAsLiteral-java.lang.Object-}
```
public final void setAsLiteral(Object value)
```

شی AsLiteral را بازمی‌گرداند یا تنظیم می‌کند. قابل‌خواندن‌نوشتن Object.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.Object |  |

### getValue() {#getValue--}
```
public final Object getValue()
```

اگر UseCell true باشد، این خاصیت نشان‌دهندهٔ خاصیت AsCell.Value است. اگر UseCell false باشد، این خاصیت نشان‌دهندهٔ خاصیت AsLiteral است. قابل‌خواندن‌نوشتن Object.

**بازگشت:**  
java.lang.Object

### setValue(Object value) {#setValue-java.lang.Object-}
```
public final void setValue(Object value)
```

اگر UseCell true باشد، این خاصیت نشان‌دهندهٔ خاصیت AsCell.Value است. اگر UseCell false باشد، این خاصیت نشان‌دهندهٔ خاصیت AsLiteral است. قابل‌خواندن‌نوشتن Object.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.Object |  |

### getGroupingLevels() {#getGroupingLevels--}
```
public final IChartCategoryLevelsManager getGroupingLevels()
```

ظرف مدیریت‌شدهٔ مقادیر سطوح گروه‌بندی دسته‌های نمودار. دسته چندسطحی بیش از یک سطح گروه‌بندی دارد. ایندکس‌بندی سطوح از صفر آغاز می‌شود. فقط‌خواندنی [IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager).

**بازگشت:**  
[IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager)

### getCachedValue() {#getCachedValue--}
```
public final ICachedChartValue getCachedValue()
```

مقدار cached دستهٔ نمودار را دریافت می‌کند. فقط‌خواندنی [ICachedChartValue](../../com.aspose.slides/icachedchartvalue).

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx")
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
> 
>      // تمام مقادیر ذخیره‌شدهٔ دستهٔ نمودار را چاپ می‌کند.
>      for (IChartCategory category : chart.getChartData().getCategories())
>          System.out.println(category.getCachedValue().toString());
>  } finally {
>      pres.dispose();
>  }
> ```


**بازگشت:**  
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)

### remove() {#remove--}
```
public final void remove()
```

دسته را از نمودار حذف می‌کند.

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

شی Parent_Immediate را بازمی‌گرداند. فقط‌خواندنی IDOMObject.

**بازگشت:**  
com.aspose.slides.IDOMObject