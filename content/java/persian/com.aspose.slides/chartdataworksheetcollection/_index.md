---
title: ChartDataWorksheetCollection
second_title: مرجع API Aspose.Slides برای جاوا
description: نمایانگر مجموعه کاربرگ‌های کتاب‌کار داده‌های نمودار.
type: docs
url: /fa/com.aspose.slides/chartdataworksheetcollection/
---
**ارث برداری:**  
java.lang.Object

**تمام رابط‌های پیاده‌سازی شده:**  
[com.aspose.slides.IChartDataWorksheetCollection](../../com.aspose.slides/ichartdataworksheetcollection), com.aspose.slides.IDOMObject  
```
public final class ChartDataWorksheetCollection implements IChartDataWorksheetCollection, IDOMObject
```

نماینده مجموعه کاربرگ‌های کتاب‌کار داده‌های نمودار.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.Pie, 50, 50, 400, 500);
>      IChartDataWorkbook workbook =  chart.getChartData().getChartDataWorkbook();
>      for (IChartDataWorksheet worksheet : workbook.getWorksheets())
>      {
>          String worksheetName = worksheet.getName();
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## متدها

| متد | توضیح |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Returns the worksheet by index. |
| [size()](#size--) | Returns the count. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [iteratorJava()](#iteratorJava--) | Returns a java iterator for the entire collection. |
| [iterator()](#iterator--) | Returns an enumerator that iterates through the collection. |
| [copyTo(System.Array array, int arrayIndex)](#copyTo-com.aspose.ms.System.Array-int-) | Copy to specified array. |
| [isSynchronized()](#isSynchronized--) | Returns a value indicating whether access to the collection is synchronized (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Returns a synchronization root. |
### get_Item(int index) {#get-Item-int-}
```
public final IChartDataWorksheet get_Item(int index)
```

کاربرگ را بر اساس شاخص برمی‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | شاخص کاربرگ در مجموعه. |

**مقدار بازگشتی:**
[IChartDataWorksheet](../../com.aspose.slides/ichartdataworksheet) - Instance of the IChartDataWorksheet.
### size() {#size--}
```
public final int size()
```

تعداد را برمی‌گرداند. فقط خواندنی int.

**مقدار بازگشتی:**
int
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

شیء Parent_Immediate را برمی‌گرداند. فقط خواندنی IDOMObject.

**مقدار بازگشتی:**
com.aspose.slides.IDOMObject
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataWorksheet> iteratorJava()
```

یک iterator جاوا برای کل مجموعه برمی‌گرداند.

**مقدار بازگشتی:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataWorksheet> - A IGenericEnumerator that can be used to iterate through the collection.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataWorksheet> iterator()
```

یک enumerator که در مجموعه پیمایش می‌کند را برمی‌گرداند.

**مقدار بازگشتی:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataWorksheet> - A IGenericEnumerator that can be used to iterate through the collection.
### copyTo(System.Array array, int arrayIndex) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int arrayIndex)
```

کپی به آرایه مشخص شده.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | آرایه برای کپی. |
| arrayIndex | int | شاخص شروع کپی. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

مقداری را برمی‌گرداند که نشان می‌دهد دسترسی به مجموعه همگام‌سازی شده (thread-safe) است. فقط خواندنی boolean.

**مقدار بازگشتی:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

ریشه همگام‌سازی را برمی‌گرداند. فقط خواندنی Object.

**مقدار بازگشتی:**
java.lang.Object