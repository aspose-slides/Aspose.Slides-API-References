---
title: ChartDataWorksheetCollection
second_title: Aspose.Slides لنظام Android عبر مرجع Java API
description: يمثل مجموعة أوراق العمل في دفتر بيانات المخطط.
type: docs
url: /ar/com.aspose.slides/chartdataworksheetcollection/
---
**الوراثة:**  
java.lang.Object

**جميع الواجهات المنفذة:**  
[com.aspose.slides.IChartDataWorksheetCollection](../../com.aspose.slides/ichartdataworksheetcollection), com.aspose.slides.IDOMObject
```
public final class ChartDataWorksheetCollection implements IChartDataWorksheetCollection, IDOMObject
```

يمثل مجموعة أوراق العمل في دفتر بيانات المخطط.

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
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | إرجاع ورقة العمل حسب الفهرس. |
| [size()](#size--) | إرجاع العدد. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [iteratorJava()](#iteratorJava--) | إرجاع مكرّر java للمجموعة بالكامل. |
| [iterator()](#iterator--) | إرجاع مُعدد يتنقل عبر المجموعة. |
| [copyTo(System.Array array, int arrayIndex)](#copyTo-com.aspose.ms.System.Array-int-) | نسخ إلى المصفوفة المحددة. |
| [isSynchronized()](#isSynchronized--) | إرجاع قيمة تشير إلى ما إذا كان الوصول إلى المجموعة متزامنًا (آمن للخيوط). |
| [getSyncRoot()](#getSyncRoot--) | إرجاع جذر المزامنة. |
### get_Item(int index) {#get-Item-int-}
```
public final IChartDataWorksheet get_Item(int index)
```

إرجاع ورقة العمل حسب الفهرس.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | فهرس ورقة العمل في المجموعة. |

**القيمة المرجعة:**
[IChartDataWorksheet](../../com.aspose.slides/ichartdataworksheet) - نسخة من IChartDataWorksheet.
### size() {#size--}
```
public final int size()
```

إرجاع العدد. int للقراءة فقط.

**القيمة المرجعة:**
int
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

إرجاع كائن Parent_Immediate. IDOMObject للقراءة فقط.

**القيمة المرجعة:**
com.aspose.slides.IDOMObject
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataWorksheet> iteratorJava()
```

إرجاع مكرّر java للمجموعة بالكامل.

**القيمة المرجعة:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataWorksheet> - IGenericEnumerator يمكن استخدامه للتنقل عبر المجموعة.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataWorksheet> iterator()
```

إرجاع مُعدد يتنقل عبر المجموعة.

**القيمة المرجعة:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataWorksheet> - IGenericEnumerator يمكن استخدامه للتنقل عبر المجموعة.
### copyTo(System.Array array, int arrayIndex) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int arrayIndex)
```

نسخ إلى المصفوفة المحددة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | المصفوفة التي سيتم النسخ إليها. |
| arrayIndex | int | الفهرس للبدء بالنسخ. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

إرجاع قيمة تشير إلى ما إذا كان الوصول إلى المجموعة متزامنًا (آمن للخيوط). boolean للقراءة فقط.

**القيمة المرجعة:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

إرجاع جذر المزامنة. Object للقراءة فقط.

**القيمة المرجعة:**
java.lang.Object