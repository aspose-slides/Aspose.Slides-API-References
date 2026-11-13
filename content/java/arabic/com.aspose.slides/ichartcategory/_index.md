---
title: IChartCategory
second_title: Aspose.Slides for Java API Reference
description: يمثل فئات المخطط.
type: docs
url: /ar/com.aspose.slides/ichartcategory/
---```
public interface IChartCategory
```

يمثل فئات المخطط.
## الطرق

| Method | Description |
| --- | --- |
| [getUseCell()](#getUseCell--) | إذا كان true فإن خاصية AsCell هي الفعلية. |
| [getAsCell()](#getAsCell--) | إرجاع أو تعيين كائن IChartDataCell. |
| [setAsCell(IChartDataCell value)](#setAsCell-com.aspose.slides.IChartDataCell-) | إرجاع أو تعيين كائن IChartDataCell. |
| [getAsLiteral()](#getAsLiteral--) | إرجاع أو تعيين AsLiteral إذا كان UseCell هو false. |
| [setAsLiteral(Object value)](#setAsLiteral-java.lang.Object-) | إرجاع أو تعيين AsLiteral إذا كان UseCell هو false. |
| [getValue()](#getValue--) | إذا كان UseCell true فإن هذه الخاصية تمثل خاصية AsCell.Value. |
| [setValue(Object value)](#setValue-java.lang.Object-) | إذا كان UseCell true فإن هذه الخاصية تمثل خاصية AsCell.Value. |
| [getCachedValue()](#getCachedValue--) | الحصول على القيمة المخزنة مؤقتًا لتصنيف المخطط. |
| [getGroupingLevels()](#getGroupingLevels--) | حاوية مُدارة للقيم التي تمثل مستويات تجميع فئة المخطط. |
| [remove()](#remove--) | إزالة الفئة من المخطط. |
### getUseCell() {#getUseCell--}
```
public abstract boolean getUseCell()
```

إذا كان true فإن خاصية AsCell هي الفعلية. بمعنى آخر، يتم استخدام ورقة العمل لتخزين الفئة (هذا الوضع يدعم فئة متعددة المستويات). إذا كان false فإن خاصية AsLiteral هي الفعلية. بمعنى آخر، لا يتم استخدام ورقة العمل لتخزين الفئة (وهذا الوضع لا يدعم فئات متعددة المستويات). قراءة فقط boolean.

--------------------

لتغيير قيمة هذه الخاصية (لكل الفئات في المجموعة) اضبط القيمة الجديدة إلى خاصية [ChartCategoryCollection.getUseCells()](../../com.aspose.slides/chartcategorycollection\#getUseCells--).

**إرجاع:**  
boolean
### getAsCell() {#getAsCell--}
```
public abstract IChartDataCell getAsCell()
```

إرجاع أو تعيين كائن IChartDataCell. إذا كانت الفئة متعددة المستويات فسيتم استخدام كائن IChartDataCell للمستوى "0". قراءة/كتابة [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**إرجاع:**  
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setAsCell(IChartDataCell value) {#setAsCell-com.aspose.slides.IChartDataCell-}
```
public abstract void setAsCell(IChartDataCell value)
```

إرجاع أو تعيين كائن IChartDataCell. إذا كانت الفئة متعددة المستويات فسيتم استخدام كائن IChartDataCell للمستوى "0". قراءة/كتابة [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |

### getAsLiteral() {#getAsLiteral--}
```
public abstract Object getAsLiteral()
```

إرجاع أو تعيين AsLiteral إذا كان UseCell هو false. قراءة/كتابة Object.

**إرجاع:**  
java.lang.Object
### setAsLiteral(Object value) {#setAsLiteral-java.lang.Object-}
```
public abstract void setAsLiteral(Object value)
```

إرجاع أو تعيين AsLiteral إذا كان UseCell هو false. قراءة/كتابة Object.

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Object |  |

### getValue() {#getValue--}
```
public abstract Object getValue()
```

إذا كان UseCell true فإن هذه الخاصية تمثل خاصية AsCell.Value. إذا كان UseCell false فإن هذه الخاصية تمثل خاصية AsLiteral. قراءة/كتابة Object.

**إرجاع:**  
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public abstract void setValue(Object value)
```

إذا كان UseCell true فإن هذه الخاصية تمثل خاصية AsCell.Value. إذا كان UseCell false فإن هذه الخاصية تمثل خاصية AsLiteral. قراءة/كتابة Object.

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Object |  |

### getCachedValue() {#getCachedValue--}
```
public abstract ICachedChartValue getCachedValue()
```

الحصول على القيمة المخزنة مؤقتًا لتصنيف المخطط. قراءة فقط [ICachedChartValue](../../com.aspose.slides/icachedchartvalue).

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
> 
>      // اطبع جميع القيم المخزنة مؤقتًا لفئات المخطط.
>      for (IChartCategory category : chart.getChartData().getCategories())
>          System.out.println(category.getCachedValue().toString());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**إرجاع:**  
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)
### getGroupingLevels() {#getGroupingLevels--}
```
public abstract IChartCategoryLevelsManager getGroupingLevels()
```

حاوية مُدارة للقيم التي تمثل مستويات تجميع فئة المخطط. الفئة متعددة المستويات تحتوي على أكثر من مستوى تجميع. فهرسة مستويات التجميع تبدأ من الصفر. قراءة فقط [IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager).

**إرجاع:**  
[IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager)
### remove() {#remove--}
```
public abstract void remove()
```

إزالة الفئة من المخطط.