---
title: IDataLabelCollection
second_title: مرجع API لـ Aspose.Slides للغة Java
description: يمثل تسميات السلسلة.
type: docs
url: /ar/com.aspose.slides/idatalabelcollection/
---
**جميع الواجهات المنفذة:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable, [com.aspose.slides.IChartComponent](../../com.aspose.slides/ichartcomponent)
```
public interface IDataLabelCollection extends System.Collections.Generic.IGenericEnumerable<IDataLabel>, IChartComponent
```

يمثل التسميات الخاصة بالسلسلة.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | يجلب ملصق البيانات للنقطة ذات الفهرس المحدد. |
| [getDefaultDataLabelFormat()](#getDefaultDataLabelFormat--) | يعيد التنسيق الافتراضي لجميع ملصقات البيانات في المجموعة. |
| [getLeaderLinesFormat()](#getLeaderLinesFormat--) | يمثل تنسيق خطوط القائد لملصقات البيانات. |
| [isVisible()](#isVisible--) | False يعني أن ملصق البيانات غير مرئي بشكل افتراضي (وبالتالي تكون جميع أعلام Show* (ShowValue, ...) الخاصة بخ属性 DefaultDataLabelFormat غير مفعلة). |
| [hide()](#hide--) | اجعل ملصق البيانات مخفيًا بشكل افتراضي عن طريق ضبط جميع أعلام Show* (ShowValue, ...) للخاصية DefaultDataLabelFormat على الحالة غير المفعلة. |
| [getCountOfVisibleDataLabels()](#getCountOfVisibleDataLabels--) | يجلب عدد ملصقات البيانات المرئية في المجموعة. |
| [getCount()](#getCount--) | يجلب عدد جميع ملصقات البيانات في المجموعة. |
| [getParentSeries()](#getParentSeries--) | يعيد سلسلة الرسم البياني الأصلية. |
| [indexOf(IDataLabel value)](#indexOf-com.aspose.slides.IDataLabel-) | يعيد فهرس DataLabel المحدد في المجموعة. |
| [getDefaultLabelShapeType()](#getDefaultLabelShapeType--) | يجلب أو يعيّن نوع الشكل الافتراضي لملصقات البيانات. |
| [setDefaultLabelShapeType(int value)](#setDefaultLabelShapeType-int-) | يجلب أو يعيّن نوع الشكل الافتراضي لملصقات البيانات. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IDataLabel get_Item(int index)
```

يجلب ملصق البيانات للنقطة ذات الفهرس المحدد.

--------------------

طريقة بديلة للوصول إلى ملصق البيانات هي: - getSeries().getDataPoints().get_Item(i).getLabel() - إدارة خصائص الملصق.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| index | int |  |

**الإرجاع:**
[IDataLabel](../../com.aspose.slides/idatalabel)
### getDefaultDataLabelFormat() {#getDefaultDataLabelFormat--}
```
public abstract IDataLabelFormat getDefaultDataLabelFormat()
```

يعيد التنسيق الافتراضي لجميع ملصقات البيانات في المجموعة. للقراءة فقط [IDataLabelFormat](../../com.aspose.slides/idatalabelformat).

**الإرجاع:**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
### getLeaderLinesFormat() {#getLeaderLinesFormat--}
```
public abstract IChartLinesFormat getLeaderLinesFormat()
```

يمثل تنسيق خطوط القائد لملصقات البيانات. للقراءة فقط [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

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
### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```

False يعني أن ملصق البيانات غير مرئي بشكل افتراضي (وبالتالي تكون جميع أعلام Show* (ShowValue, ...) الخاصة بخ属性 DefaultDataLabelFormat غير مفعلة). للقراءة فقط boolean .

إذا كان ملصق البيانات مرئيًا بشكل افتراضي يمكنك إخفاؤه باستخدام طريقة Hide(). ولكن إذا كان ملصق البيانات غير مرئي بشكل افتراضي (IsVisible هو false) يمكنك جعله "مرئيًا بشكل افتراضي" بضبط أعلام Show* (ShowValue, ...) للخاصية DefaultDataLabelFormat على الحالة المفعلة.

**الإرجاع:**
boolean
### hide() {#hide--}
```
public abstract void hide()
```

اجعل ملصق البيانات مخفيًا بشكل افتراضي عن طريق ضبط جميع أعلام Show* (ShowValue, ...) للخاصية DefaultDataLabelFormat على الحالة غير المفعلة. سيكون IsVisible هو false بعد ذلك.

إذا كان ملصق البيانات غير مرئي بشكل افتراضي (IsVisible هو false) يمكنك جعله "مرئيًا بشكل افتراضي" بضبط أعلام Show* (ShowValue, ...) للخاصية DefaultDataLabelFormat على الحالة المفعلة.

### getCountOfVisibleDataLabels() {#getCountOfVisibleDataLabels--}
```
public abstract int getCountOfVisibleDataLabels()
```

يحصل على عدد ملصقات البيانات المرئية في المجموعة. للقراءة فقط int .

**الإرجاع:**
int
### getCount() {#getCount--}
```
public abstract int getCount()
```

يحصل على عدد جميع ملصقات البيانات في المجموعة. للقراءة فقط int .

**الإرجاع:**
int
### getParentSeries() {#getParentSeries--}
```
public abstract IChartSeries getParentSeries()
```

يعيد سلسلة الرسم البياني الأصلية. للقراءة فقط [IChartSeries](../../com.aspose.slides/ichartseries).

**الإرجاع:**
[IChartSeries](../../com.aspose.slides/ichartseries)
### indexOf(IDataLabel value) {#indexOf-com.aspose.slides.IDataLabel-}
```
public abstract int indexOf(IDataLabel value)
```

يعيد فهرس DataLabel المحدد في المجموعة.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | [IDataLabel](../../com.aspose.slides/idatalabel) | DataLabel للبحث عنها. |

**الإرجاع:**
int - فهرس DataLabel أو -1 إذا لم يكن DataLabel من هذه المجموعة.
### getDefaultLabelShapeType() {#getDefaultLabelShapeType--}
```
public abstract int getDefaultLabelShapeType()
```

يجلب أو يعيّن نوع الشكل الافتراضي لملصقات البيانات. يعيد [ShapeType.NotDefined](../../com.aspose.slides/shapetype\#NotDefined) إذا لم يتم تعريف شكل.

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(1);
>      IChartSeries firstSeries = chart.getChartData().getSeries().get_Item(0);
>      // ضبط نوع الشكل لجميع ملصقات البيانات في السلسلة الأولى إلى Ellipse.
>      firstSeries.getLabels().setDefaultLabelShapeType(ShapeType.Ellipse);
>      pres.save("ChartWithEllipseLabels.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

ضبط هذه الخاصية يضبط أيضًا الخاصية IDataLabel.LabelShapeType ([IDataLabel.getLabelShapeType](../../com.aspose.slides/idatalabel\#getLabelShapeType)/[IDataLabel.setLabelShapeType(int)](../../com.aspose.slides/idatalabel\#setLabelShapeType-int-)) لجميع ملصقات البيانات في المجموعة إلى نفس القيمة.

**الإرجاع:**
int
### setDefaultLabelShapeType(int value) {#setDefaultLabelShapeType-int-}
```
public abstract void setDefaultLabelShapeType(int value)
```

يجلب أو يعيّن نوع الشكل الافتراضي لملصقات البيانات. يعيد [ShapeType.NotDefined](../../com.aspose.slides/shapetype\#NotDefined) إذا لم يتم تعريف شكل.

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(1);
>      IChartSeries firstSeries = chart.getChartData().getSeries().get_Item(0);
>      // ضبط نوع الشكل لجميع ملصقات البيانات في السلسلة الأولى إلى Ellipse.
>      firstSeries.getLabels().setDefaultLabelShapeType(ShapeType.Ellipse);
>      pres.save("ChartWithEllipseLabels.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

ضبط هذه الخاصية يضبط أيضًا الخاصية IDataLabel.LabelShapeType ([IDataLabel.getLabelShapeType](../../com.aspose.slides/idatalabel\#getLabelShapeType)/[IDataLabel.setLabelShapeType(int)](../../com.aspose.slides/idatalabel\#setLabelShapeType-int-)) لجميع ملصقات البيانات في المجموعة إلى نفس القيمة.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | int |  |