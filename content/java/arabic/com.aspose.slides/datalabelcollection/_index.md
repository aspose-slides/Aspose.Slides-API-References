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
## الأساليب

| الطريقة | الوصف |
| --- | --- |
| [getChart()](#getChart--) | يعيد المخطط الأصلي. |
| [iterator()](#iterator--) | يعيد عدادًا يتجول عبر المجموعة. |
| [iteratorJava()](#iteratorJava--) | يعيد مؤشرات جافا للمجموعة بأكملها. |
| [isVisible()](#isVisible--) | False يعني أن تسمية البيانات غير مرئية افتراضيًا (وبالتالي جميع أعلام Show*-flags (ShowValue, ...) من خاصية DefaultDataLabelFormat هي false). |
| [hide()](#hide--) | اجعل تسمية البيانات مخفية افتراضيًا عن طريق تعيين جميع أعلام Show*-flags (ShowValue, ...) من خاصية DefaultDataLabelFormat إلى الحالة false. |
| [getCountOfVisibleDataLabels()](#getCountOfVisibleDataLabels--) | يحصل على عدد تسميات البيانات المرئية في المجموعة. |
| [getCount()](#getCount--) | يحصل على عدد جميع تسميات البيانات في المجموعة. |
| [getDefaultDataLabelFormat()](#getDefaultDataLabelFormat--) | يحصل على تنسيق تسمية البيانات الافتراضي. |
| [getLeaderLinesFormat()](#getLeaderLinesFormat--) | يمثل تنسيق خطوط القادة لتسميات البيانات. |
| [getParentSeries()](#getParentSeries--) | يحصل على السلسلة الأصل. |
| [indexOf(IDataLabel value)](#indexOf-com.aspose.slides.IDataLabel-) | يعيد فهرس لتسمية البيانات المحددة في المجموعة. |
| [get_Item(int index)](#get-Item-int-) | يحصل على تسمية البيانات للنقطة ذات الفهرس المحدد. |
| [getDefaultLabelShapeType()](#getDefaultLabelShapeType--) | يحصل أو يضع نوع الشكل الافتراضي لتسميات البيانات. |
| [setDefaultLabelShapeType(int value)](#setDefaultLabelShapeType-int-) | يحصل أو يضع نوع الشكل الافتراضي لتسميات البيانات. |
| [getSlide()](#getSlide--) | يعيد الشريحة الأصلية لتنسيق FillFormat. |
| [getPresentation()](#getPresentation--) | يعيد العرض الأصلي لتنسيق FillFormat. |

### getChart() {#getChart--}
```
public final IChart getChart()
```

يعيد المخطط الأصلي. للقراءة فقط [IChart](../../com.aspose.slides/ichart).

**الإرجاع:**
[IChart](../../com.aspose.slides/ichart)

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IDataLabel> iterator()
```

يعيد عدادًا يتجول عبر المجموعة.

**الإرجاع:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDataLabel> - A IGenericEnumerator يمكن استخدامه لتجول عبر المجموعة.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IDataLabel> iteratorJava()
```

يعيد مؤشرات جافا للمجموعة بأكملها.

**الإرجاع:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDataLabel> - An java.util.Iterator للمجموعة بأكملها.

### isVisible() {#isVisible--}
```
public final boolean isVisible()
```

False يعني أن تسمية البيانات غير مرئية افتراضيًا (وبالتالي جميع أعلام Show*-flags (ShowValue, ...) من خاصية DefaultDataLabelFormat هي false). للقراءة فقط boolean.

--------------------

إذا كانت تسمية البيانات مرئية افتراضيًا يمكنك إخفاؤها افتراضيًا باستخدام الطريقة Hide(). ولكن إذا كانت تسمية البيانات غير مرئية افتراضيًا (IsVisible هو false) يمكنك جعل التسمية "مرئية افتراضيًا" عن طريق تعيين أعلام Show*-flags (ShowValue, ...) من خاصية DefaultDataLabelFormat إلى الحالة true.

**الإرجاع:**
boolean

### hide() {#hide--}
```
public final void hide()
```

اجعل تسمية البيانات مخفية افتراضيًا عن طريق تعيين جميع أعلام Show*-flags (ShowValue, ...) من خاصية DefaultDataLabelFormat إلى الحالة false. سيكون IsVisible false بعد ذلك.

--------------------

إذا كانت تسمية البيانات غير مرئية افتراضيًا (IsVisible هو false) يمكنك جعل التسمية "مرئية افتراضيًا" عن طريق تعيين أعلام Show*-flags (ShowValue, ...) من خاصية DefaultDataLabelFormat إلى الحالة true.

### getCountOfVisibleDataLabels() {#getCountOfVisibleDataLabels--}
```
public final int getCountOfVisibleDataLabels()
```

يحصل على عدد تسميات البيانات المرئية في المجموعة. للقراءة فقط int.

**الإرجاع:**
int

### getCount() {#getCount--}
```
public final int getCount()
```

يحصل على عدد جميع تسميات البيانات في المجموعة. للقراءة فقط int.

**الإرجاع:**
int

### getDefaultDataLabelFormat() {#getDefaultDataLabelFormat--}
```
public final IDataLabelFormat getDefaultDataLabelFormat()
```

يحصل على تنسيق تسمية البيانات الافتراضي. للقراءة فقط [IDataLabelFormat](../../com.aspose.slides/idatalabelformat).

**الإرجاع:**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)

### getLeaderLinesFormat() {#getLeaderLinesFormat--}
```
public final IChartLinesFormat getLeaderLinesFormat()
```

يمثل تنسيق خطوط القادة لتسميات البيانات. للقراءة فقط [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

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

يحصل على السلسلة الأصل. للقراءة فقط [IChartSeries](../../com.aspose.slides/ichartseries).

**الإرجاع:**
[IChartSeries](../../com.aspose.slides/ichartseries)

### indexOf(IDataLabel value) {#indexOf-com.aspose.slides.IDataLabel-}
```
public final int indexOf(IDataLabel value)
```

يعيد فهرس لتسمية البيانات المحددة في المجموعة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IDataLabel](../../com.aspose.slides/idatalabel) | تسمية البيانات للبحث عنها. |

**الإرجاع:**
int - فهرس لتسمية البيانات أو -1 إذا لم تكن التسمية من هذه المجموعة.

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

**الإرجاع:**
[IDataLabel](../../com.aspose.slides/idatalabel)

### getDefaultLabelShapeType() {#getDefaultLabelShapeType--}
```
public final int getDefaultLabelShapeType()
```

يحصل أو يضع نوع الشكل الافتراضي لتسميات البيانات. يعيد [ShapeType.NotDefined](../../com.aspose.slides/shapetype\#NotDefined) إذا لم يتم تعريف أي شكل.

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(1);
>      IChartSeries firstSeries = chart.getChartData().getSeries().get_Item(0);
>      // ضبط نوع الشكل لجميع تسميات البيانات في السلسلة الأولى إلى Ellipse.
>      firstSeries.getLabels().setDefaultLabelShapeType(ShapeType.Ellipse);
>      pres.save("ChartWithEllipseLabels.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

تعيين هذه الخاصية يضبط أيضًا خاصية IDataLabel.LabelShapeType ([IDataLabel.getLabelShapeType](../../com.aspose.slides/idatalabel\#getLabelShapeType)/[IDataLabel.setLabelShapeType(int)](../../com.aspose.slides/idatalabel\#setLabelShapeType-int-)) لجميع تسميات البيانات في المجموعة على نفس القيمة.

**الإرجاع:**
int

### setDefaultLabelShapeType(int value) {#setDefaultLabelShapeType-int-}
```
public final void setDefaultLabelShapeType(int value)
```

يحصل أو يضع نوع الشكل الافتراضي لتسميات البيانات. يعيد [ShapeType.NotDefined](../../com.aspose.slides/shapetype\#NotDefined) إذا لم يتم تعريف أي شكل.

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(1);
>      IChartSeries firstSeries = chart.getChartData().getSeries().get_Item(0);
>      // ضبط نوع الشكل لجميع تسميات البيانات في السلسلة الأولى إلى Ellipse.
>      firstSeries.getLabels().setDefaultLabelShapeType(ShapeType.Ellipse);
>      pres.save("ChartWithEllipseLabels.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

تعيين هذه الخاصية يضبط أيضًا خاصية IDataLabel.LabelShapeType ([IDataLabel.getLabelShapeType](../../com.aspose.slides/idatalabel\#getLabelShapeType)/[IDataLabel.setLabelShapeType(int)](../../com.aspose.slides/idatalabel\#setLabelShapeType-int-)) لجميع تسميات البيانات في المجموعة على نفس القيمة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

يعيد الشريحة الأصلية لتنسيق FillFormat. للقراءة فقط [BaseSlide](../../com.aspose.slides/baseslide).

**الإرجاع:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

يعيد العرض الأصلي لتنسيق FillFormat. للقراءة فقط [IPresentation](../../com.aspose.slides/ipresentation).

**الإرجاع:**
[IPresentation](../../com.aspose.slides/ipresentation)