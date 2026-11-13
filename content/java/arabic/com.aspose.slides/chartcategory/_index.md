---
title: ChartCategory
second_title: مرجع API لـ Aspose.Slides for Java
description: يمثل فئات المخطط.
type: docs
url: /ar/com.aspose.slides/chartcategory/
---
**الوراثة:**  
java.lang.Object

**جميع الواجهات المنفذة:**  
[com.aspose.slides.IChartCategory](../../com.aspose.slides/ichartcategory), com.aspose.slides.IDOMObject  
```
public class ChartCategory implements IChartCategory, IDOMObject
```

يمثل فئات المخطط.  
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getUseCell()](#getUseCell--) | إذا كان true فإن خاصية AsCell هي الفعلية. |
| [getAsCell()](#getAsCell--) | إرجاع أو تعيين كائن IChartDataCell. |
| [setAsCell(IChartDataCell value)](#setAsCell-com.aspose.slides.IChartDataCell-) | إرجاع أو تعيين كائن IChartDataCell. |
| [getAsLiteral()](#getAsLiteral--) | إرجاع أو تعيين كائن AsLiteral. |
| [setAsLiteral(Object value)](#setAsLiteral-java.lang.Object-) | إرجاع أو تعيين كائن AsLiteral. |
| [getValue()](#getValue--) | إذا كان UseCell true فإن هذه الخاصية تمثل خاصية AsCell.Value. |
| [setValue(Object value)](#setValue-java.lang.Object-) | إذا كان UseCell true فإن هذه الخاصية تمثل خاصية AsCell.Value. |
| [getGroupingLevels()](#getGroupingLevels--) | حاوية مُدارة لقيم مستويات تجميع فئات المخطط. |
| [getCachedValue()](#getCachedValue--) | يحصل على القيمة المخزنة مؤقتًا لفئة المخطط. |
| [remove()](#remove--) | يزيل الفئة من المخطط. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getUseCell() {#getUseCell--}
```
public final boolean getUseCell()
```

إذا كان true فإن خاصية AsCell هي الفعلية. بمعنى آخر، تُستخدم ورقة العمل لتخزين الفئة (هذه الحالة تدعم فئة متعددة المستويات). إذا كان false فإن خاصية AsLiteral هي الفعلية. بمعنى آخر، لا تُستخدم ورقة العمل لتخزين الفئة (وهذه الحالة لا تدعم فئات متعددة المستويات). قيمة منطقية للقراءة فقط.

--------------------

لتغيير قيمة هذه الخاصية (لكل الفئات في المجموعة) اضبط القيمة الجديدة إلى خاصية ChartCategoryCollection.UseCells.

**الإرجاع:**  
boolean
### getAsCell() {#getAsCell--}
```
public final IChartDataCell getAsCell()
```

إرجاع أو تعيين كائن IChartDataCell. إذا كانت الفئة متعددة المستويات فسيتم استخدام كائن IChartDataCell للمستوى "0". قراءة/كتابة [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**الإرجاع:**  
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setAsCell(IChartDataCell value) {#setAsCell-com.aspose.slides.IChartDataCell-}
```
public final void setAsCell(IChartDataCell value)
```

إرجاع أو تعيين كائن IChartDataCell. إذا كانت الفئة متعددة المستويات فسيتم استخدام كائن IChartDataCell للمستوى "0". قراءة/كتابة [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**المعاملات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |
### getAsLiteral() {#getAsLiteral--}
```
public final Object getAsLiteral()
```

إرجاع أو تعيين كائن AsLiteral. قراءة/كتابة Object.

**الإرجاع:**  
java.lang.Object
### setAsLiteral(Object value) {#setAsLiteral-java.lang.Object-}
```
public final void setAsLiteral(Object value)
```

إرجاع أو تعيين كائن AsLiteral. قراءة/كتابة Object.

**المعاملات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.Object |  |
### getValue() {#getValue--}
```
public final Object getValue()
```

إذا كان UseCell true فإن هذه الخاصية تمثل خاصية AsCell.Value. إذا كان UseCell false فإن هذه الخاصية تمثل خاصية AsLiteral. قراءة/كتابة Object.

**الإرجاع:**  
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public final void setValue(Object value)
```

إذا كان UseCell true فإن هذه الخاصية تمثل خاصية AsCell.Value. إذا كان UseCell false فإن هذه الخاصية تمثل خاصية AsLiteral. قراءة/كتابة Object.

**المعاملات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.Object |  |
### getGroupingLevels() {#getGroupingLevels--}
```
public final IChartCategoryLevelsManager getGroupingLevels()
```

حاوية مُدارة لقيم مستويات تجميع فئة المخطط. الفئة متعددة المستويات تحتوي على أكثر من مستوى تجميع واحد. فهرسة مستويات التجميع تبدأ من الصفر. للقراءة فقط [IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager).

**الإرجاع:**  
[IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager)
### getCachedValue() {#getCachedValue--}
```
public final ICachedChartValue getCachedValue()
```

يحصل على القيمة المخزنة مؤقتًا لفئة المخطط. للقراءة فقط [ICachedChartValue](../../com.aspose.slides/icachedchartvalue).

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx")
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
> 
>      // اطبع جميع القيم المخزنة مؤقتًا لفئات المخطط.
>      for (IChartCategory category : chart.getChartData().getCategories())
>          System.out.println(category.getCachedValue().toString());
>  } finally {
>      pres.dispose();
>  }
> ```


**الإرجاع:**  
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)
### remove() {#remove--}
```
public final void remove()
```

يزيل الفئة من المخطط.

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

إرجاع كائن Parent_Immediate. للقراءة فقط IDOMObject.

**الإرجاع:**  
com.aspose.slides.IDOMObject