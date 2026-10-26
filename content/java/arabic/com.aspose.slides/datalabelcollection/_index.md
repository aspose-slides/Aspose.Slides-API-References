---
title: DataLabelCollection
second_title: مرجع API لـ Aspose.Slides للغة Java
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
| [getChart()](#getChart--) | يرجع المخطط الأصلي. |
| [iterator()](#iterator--) | يرجع كائن تعداد يتنقل عبر المجموعة. |
| [iteratorJava()](#iteratorJava--) | يرجع مكرّر Java لكامل المجموعة. |
| [isVisible()](#isVisible--) | False يعني أن تسمية البيانات غير مرئية افتراضيًا (وبالتالي جميع أعلام Show*-flags (ShowValue, ...) لخاصية DefaultDataLabelFormat هي false). |
| [hide()](#hide--) | اجعل تسمية البيانات مخفية افتراضيًا عن طريق ضبط جميع أعلام Show*-flags (ShowValue, ...) لخاصية DefaultDataLabelFormat إلى الحالة false. |
| [getCountOfVisibleDataLabels()](#getCountOfVisibleDataLabels--) | يحصل على عدد تسميات البيانات المرئية في المجموعة. |
| [getCount()](#getCount--) | يحصل على عدد جميع تسميات البيانات في المجموعة. |
| [getDefaultDataLabelFormat()](#getDefaultDataLabelFormat--) | يحصل على تنسيق تسمية البيانات الافتراضي. |
| [getLeaderLinesFormat()](#getLeaderLinesFormat--) | يمثل تنسيق خطوط القائد لتسميات البيانات. |
| [getParentSeries()](#getParentSeries--) | يحصل على السلسلة الأصلية. |
| [indexOf(IDataLabel value)](#indexOf-com.aspose.slides.IDataLabel-) | يرجع فهرس DataLabel المحدد في المجموعة. |
| [get_Item(int index)](#get-Item-int-) | يحصل على تسمية البيانات للنقطة ذات الفهرس المحدد. |
| [getSlide()](#getSlide--) | يرجع الشريحة الأصلية لـ FillFormat. |
| [getPresentation()](#getPresentation--) | يرجع العرض التقديمي الأصلي لـ FillFormat. |
### getChart() {#getChart--}
```
public final IChart getChart()
```

يرجع المخطط الأصلي. قراءة فقط [IChart](../../com.aspose.slides/ichart).

**الإرجاع:**
[IChart](../../com.aspose.slides/ichart)
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IDataLabel> iterator()
```

يرجع كائن تعداد يتنقل عبر المجموعة.

**الإرجاع:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDataLabel> - يمكن استخدام IGenericEnumerator للتنقل عبر المجموعة.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IDataLabel> iteratorJava()
```

يرجع مكرّر Java لكامل المجموعة.

**الإرجاع:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDataLabel> - java.util.Iterator لكامل المجموعة.
### isVisible() {#isVisible--}
```
public final boolean isVisible()
```

False يعني أن تسمية البيانات غير مرئية افتراضيًا (وبالتالي جميع أعلام Show*-flags (ShowValue, ...) لخاصية DefaultDataLabelFormat هي false). قراءة فقط boolean.

--------------------

إذا كانت تسمية البيانات مرئية افتراضيًا يمكنك جعلها مخفية افتراضيًا باستخدام طريقة Hide(). ولكن إذا كانت تسمية البيانات غير مرئية افتراضيًا (IsVisible هو false) يمكنك جعل تسمية البيانات "مرئية افتراضيًا" عن طريق ضبط أعلام Show*-flags (ShowValue, ...) لخاصية DefaultDataLabelFormat إلى الحالة true.

**الإرجاع:**
boolean
### hide() {#hide--}
```
public final void hide()
```

اجعل تسمية البيانات مخفية افتراضيًا عن طريق ضبط جميع أعلام Show*-flags (ShowValue, ...) لخاصية DefaultDataLabelFormat إلى الحالة false. سيكون IsVisible هو false بعد ذلك.

--------------------

إذا كانت تسمية البيانات غير مرئية افتراضيًا (IsVisible هو false) يمكنك جعل تسمية البيانات "مرئية افتراضيًا" عن طريق ضبط أعلام Show*-flags (ShowValue, ...) لخاصية DefaultDataLabelFormat إلى الحالة true.
### getCountOfVisibleDataLabels() {#getCountOfVisibleDataLabels--}
```
public final int getCountOfVisibleDataLabels()
```

يحصل على عدد تسميات البيانات المرئية في المجموعة. قراءة فقط int.

**الإرجاع:**
int
### getCount() {#getCount--}
```
public final int getCount()
```

يحصل على عدد جميع تسميات البيانات في المجموعة. قراءة فقط int.

**الإرجاع:**
int
### getDefaultDataLabelFormat() {#getDefaultDataLabelFormat--}
```
public final IDataLabelFormat getDefaultDataLabelFormat()
```

يحصل على تنسيق تسمية البيانات الافتراضي. قراءة فقط [IDataLabelFormat](../../com.aspose.slides/idatalabelformat).

**الإرجاع:**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
### getLeaderLinesFormat() {#getLeaderLinesFormat--}
```
public final IChartLinesFormat getLeaderLinesFormat()
```

يمثل تنسيق خطوط القائد لتسميات البيانات. قراءة فقط [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

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
>      labels.getLeaderLinesFormat().getLine().getFillFormat().getSolidFillColor().setColor(new java.awt.Color(255, 0, 0, 255));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**الإرجاع:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)
### getParentSeries() {#getParentSeries--}
```
public final IChartSeries getParentSeries()
```

يحصل على السلسلة الأصلية. قراءة فقط [IChartSeries](../../com.aspose.slides/ichartseries).

**الإرجاع:**
[IChartSeries](../../com.aspose.slides/ichartseries)
### indexOf(IDataLabel value) {#indexOf-com.aspose.slides.IDataLabel-}
```
public final int indexOf(IDataLabel value)
```

يرجع فهرس DataLabel المحدد في المجموعة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IDataLabel](../../com.aspose.slides/idatalabel) | DataLabel للبحث عنه. |

**الإرجاع:**
int - فهرس DataLabel أو -1 إذا كان DataLabel ليس من هذه المجموعة.
### get_Item(int index) {#get-Item-int-}
```
public final IDataLabel get_Item(int index)
```

يحصل على تسمية البيانات للنقطة ذات الفهرس المحدد.

--------------------

طريقة بديلة للوصول إلى تسمية البيانات هي: - series.getDataPoints().get_Item(i).getLabel() - إدارة خصائص التسمية.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int |  |

**الإرجاع:**
[IDataLabel](../../com.aspose.slides/idatalabel)
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

يرجع الشريحة الأصلية لـ FillFormat. قراءة فقط [BaseSlide](../../com.aspose.slides/baseslide).

**الإرجاع:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

يرجع العرض التقديمي الأصلي لـ FillFormat. قراءة فقط [IPresentation](../../com.aspose.slides/ipresentation).

**الإرجاع:**
[IPresentation](../../com.aspose.slides/ipresentation)