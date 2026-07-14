---
title: DataLabelCollection
second_title: Aspose.Slides لنظام Android عبر مرجع واجهة برمجة التطبيقات Java
description: يمثل تسميات السلسلة.
type: docs
url: /ar/com.aspose.slides/datalabelcollection/
---
**الوراثة:**  
java.lang.Object, com.aspose.slides.DomObject

**جميع الواجهات المنفذة:**  
[com.aspose.slides.IDataLabelCollection](../../com.aspose.slides/idatalabelcollection)  
```
public class DataLabelCollection extends DomObject<ChartSeries> implements IDataLabelCollection
```

يمثل تسميات السلسلة.  
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getChart()](#getChart--) | يعيد المخطط الأصل. |
| [iterator()](#iterator--) | يعيد مُؤَدًِّر يمر عبر المجموعة. |
| [iteratorJava()](#iteratorJava--) | يعيد مكرّر جافا للمجموعة بالكامل. |
| [isVisible()](#isVisible--) | القيمة false تعني أن تسمية البيانات غير مرئية بشكل افتراضي (وبالتالي جميع علامات Show*-flags (ShowValue, ...) لخاصية DefaultDataLabelFormat هي false). |
| [hide()](#hide--) | اجعل تسمية البيانات مخفية بشكل افتراضي عن طريق ضبط جميع علامات Show*-flags (ShowValue, ...) لخاصية DefaultDataLabelFormat إلى الحالة false. |
| [getCountOfVisibleDataLabels()](#getCountOfVisibleDataLabels--) | يحصل على عدد تسميات البيانات المرئية في المجموعة. |
| [getCount()](#getCount--) | يحصل على عدد جميع تسميات البيانات في المجموعة. |
| [getDefaultDataLabelFormat()](#getDefaultDataLabelFormat--) | يحصل على تنسيق تسمية البيانات الافتراضي. |
| [getLeaderLinesFormat()](#getLeaderLinesFormat--) | يمثل تنسيق خطوط القائد لتسميات البيانات. |
| [getParentSeries()](#getParentSeries--) | يحصل على السلسلة الأصل. |
| [indexOf(IDataLabel value)](#indexOf-com.aspose.slides.IDataLabel-) | يعيد فهرس DataLabel المحدد في المجموعة. |
| [get_Item(int index)](#get-Item-int-) | يحصل على تسمية البيانات للنقطة ذات الفهرس المحدد. |
| [getSlide()](#getSlide--) | يعيد الشريحة الأصلية لـ FillFormat. |
| [getPresentation()](#getPresentation--) | يعيد العرض الأصلي لـ FillFormat. |

### getChart() {#getChart--}
```
public final IChart getChart()
```

يعيد المخطط الأصل. للقراءة فقط [IChart](../../com.aspose.slides/ichart).

**القيمة المرجعة:**
[IChart](../../com.aspose.slides/ichart)

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IDataLabel> iterator()
```

يعيد مُؤَدًِّر يمر عبر المجموعة.

**القيمة المرجعة:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDataLabel> - A IGenericEnumerator that can be used to iterate through the collection.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IDataLabel> iteratorJava()
```

يعيد مكرّر جافا للمجموعة بالكامل.

**القيمة المرجعة:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDataLabel> - An java.util.Iterator for the entire collection.

### isVisible() {#isVisible--}
```
public final boolean isVisible()
```

القيمة false تعني أن تسمية البيانات غير مرئية بشكل افتراضي (وبالتالي جميع علامات Show*-flags (ShowValue, ...) لخاصية DefaultDataLabelFormat هي false). للقراءة فقط boolean.

--------------------

إذا كانت تسمية البيانات مرئية بشكل افتراضي يمكنك جعلها مخفية بشكل افتراضي باستخدام طريقة Hide(). ولكن إذا كانت تسمية البيانات غير مرئية بشكل افتراضي (IsVisible هو false) يمكنك جعلها "مرئية بشكل افتراضي" عن طريق ضبط علامات Show*-flags (ShowValue, ...) لخاصية DefaultDataLabelFormat إلى الحالة true.

**القيمة المرجعة:**
boolean

### hide() {#hide--}
```
public final void hide()
```

اجعل تسمية البيانات مخفية بشكل افتراضي عن طريق ضبط جميع علامات Show*-flags (ShowValue, ...) لخاصية DefaultDataLabelFormat إلى الحالة false. سيكون IsVisible هو false بعد ذلك.

--------------------

إذا كانت تسمية البيانات غير مرئية بشكل افتراضي (IsVisible هو false) يمكنك جعلها "مرئية بشكل افتراضي" عن طريق ضبط علامات Show*-flags (ShowValue, ...) لخاصية DefaultDataLabelFormat إلى الحالة true.

### getCountOfVisibleDataLabels() {#getCountOfVisibleDataLabels--}
```
public final int getCountOfVisibleDataLabels()
```

يحصل على عدد تسميات البيانات المرئية في المجموعة. للقراءة فقط int.

**القيمة المرجعة:**
int

### getCount() {#getCount--}
```
public final int getCount()
```

يحصل على عدد جميع تسميات البيانات في المجموعة. للقراءة فقط int.

**القيمة المرجعة:**
int

### getDefaultDataLabelFormat() {#getDefaultDataLabelFormat--}
```
public final IDataLabelFormat getDefaultDataLabelFormat()
```

يحصل على تنسيق تسمية البيانات الافتراضي. للقراءة فقط [IDataLabelFormat](../../com.aspose.slides/idatalabelformat).

**القيمة المرجعة:**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)

### getLeaderLinesFormat() {#getLeaderLinesFormat--}
```
public final IChartLinesFormat getLeaderLinesFormat()
```

يمثل تنسيق خطوط القائد لتسميات البيانات. للقراءة فقط [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IChart chart = (IChart) pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IChartSeriesCollection series = chart.getChartData().getSeries();
>      IDataLabelCollection labels = series.get_Item(0).getLabels();
>      labels.getLeaderLinesFormat().getLine().getFillFormat().setFillType(FillType.Solid);
>      labels.getLeaderLinesFormat().getLine().getFillFormat().getSolidFillColor().setColor(Color.RED);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**القيمة المرجعة:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)

### getParentSeries() {#getParentSeries--}
```
public final IChartSeries getParentSeries()
```

يحصل على السلسلة الأصل. للقراءة فقط [IChartSeries](../../com.aspose.slides/ichartseries).

**القيمة المرجعة:**
[IChartSeries](../../com.aspose.slides/ichartseries)

### indexOf(IDataLabel value) {#indexOf-com.aspose.slides.IDataLabel-}
```
public final int indexOf(IDataLabel value)
```

يعيد فهرس DataLabel المحدد في المجموعة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IDataLabel](../../com.aspose.slides/idatalabel) | DataLabel للعثور عليه. |

**القيمة المرجعة:**
int - فهرس DataLabel أو -1 إذا لم يكن DataLabel من هذه المجموعة.

### get_Item(int index) {#get-Item-int-}
```
public final IDataLabel get_Item(int index)
```

يحصل على تسمية البيانات للنقطة ذات الفهرس المحدد.

--------------------

طريقة بديلة للوصول إلى تسمية البيانات هي: - series.getDataPoints().get_Item(i).getLabel() - إدارة خصائص التسمية.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int |  |

**القيمة المرجعة:**
[IDataLabel](../../com.aspose.slides/idatalabel)

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

يعيد الشريحة الأصلية لـ FillFormat. للقراءة فقط [BaseSlide](../../com.aspose.slides/baseslide).

**القيمة المرجعة:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

يعيد العرض الأصلي لـ FillFormat. للقراءة فقط [IPresentation](../../com.aspose.slides/ipresentation).

**القيمة المرجعة:**
[IPresentation](../../com.aspose.slides/ipresentation)