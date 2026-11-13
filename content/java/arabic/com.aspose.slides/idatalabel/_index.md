---
title: IDataLabel
second_title: Aspose.Slides للغة Java مرجع API
description: يمثل ملصقات السلسلة.
type: docs
url: /ar/com.aspose.slides/idatalabel/
---
**كل الواجهات المنفذة:**
[com.aspose.slides.ILayoutable](../../com.aspose.slides/ilayoutable), [com.aspose.slides.IOverridableText](../../com.aspose.slides/ioverridabletext), [com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface IDataLabel extends ILayoutable, IOverridableText, IActualLayout
```

يمثل ملصقات السلسلة.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [isVisible()](#isVisible--) | False يعني أن ملصق البيانات غير مرئي (وبالتالي جميع Show*-flags (ShowValue, ...) تكون خاطئة). |
| [hide()](#hide--) | اجعل ملصق البيانات مخفيًا عن طريق ضبط جميع Show*-flags (ShowValue, ...) إلى الحالة false. |
| [getDataLabelFormat()](#getDataLabelFormat--) | يرجع تنسيق ملصق البيانات. |
| [getValueFromCell()](#getValueFromCell--) | يحصل أو يعيّن خلية بيانات المصنف. |
| [setValueFromCell(IChartDataCell value)](#setValueFromCell-com.aspose.slides.IChartDataCell-) | يحصل أو يعيّن خلية بيانات المصنف. |
| [getActualLabelText()](#getActualLabelText--) | يرجع نص الملصق الفعلي بناءً على إعدادات DataLabelFormat أو قيمة TextFrameForOverriding.Text. |
| [getLabelShapeType()](#getLabelShapeType--) | يحصل أو يعيّن نوع الشكل لملصق البيانات. |
| [setLabelShapeType(int value)](#setLabelShapeType-int-) | يحصل أو يعيّن نوع الشكل لملصق البيانات. |
### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```


False يعني أن ملصق البيانات غير مرئي (وبالتالي جميع Show*-flags (ShowValue, ...) تكون خاطئة). قيمة boolean للقراءة فقط.

--------------------

إذا كان ملصق البيانات مرئيًا يمكنك إخفاؤه باستخدام طريقة Hide(). ولكن إذا كان ملصق البيانات غير مرئي (IsVisible هو false) يمكنك جعل ملصق البيانات مرئيًا عن طريق ضبط Show*-flags (ShowValue, ...) إلى الحالة true.

**الإرجاع:**
boolean
### hide() {#hide--}
```
public abstract void hide()
```


اجعل ملصق البيانات مخفيًا عن طريق ضبط جميع Show*-flags (ShowValue, ...) إلى الحالة false. سيكون IsVisible هو false بعد ذلك.

--------------------

إذا كان ملصق البيانات غير مرئي (IsVisible هو false) يمكنك جعل ملصق البيانات مرئيًا عن طريق ضبط Show*-flags (ShowValue, ...) إلى الحالة true.

### getDataLabelFormat() {#getDataLabelFormat--}
```
public abstract IDataLabelFormat getDataLabelFormat()
```


يرجع تنسيق ملصق البيانات. للقراءة فقط [IDataLabelFormat](../../com.aspose.slides/idatalabelformat).

**الإرجاع:**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
### getValueFromCell() {#getValueFromCell--}
```
public abstract IChartDataCell getValueFromCell()
```


يحصل أو يعيّن خلية بيانات المصنف. يتم تطبيقه إذا كانت خاصية IDataLabelFormat.ShowLabelValueFromCell تساوي true.

**الإرجاع:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setValueFromCell(IChartDataCell value) {#setValueFromCell-com.aspose.slides.IChartDataCell-}
```
public abstract void setValueFromCell(IChartDataCell value)
```


يحصل أو يعيّن خلية بيانات المصنف. يتم تطبيقه إذا كانت خاصية IDataLabelFormat.ShowLabelValueFromCell تساوي true.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |

### getActualLabelText() {#getActualLabelText--}
```
public abstract String getActualLabelText()
```


يرجع نص الملصق الفعلي بناءً على إعدادات DataLabelFormat أو قيمة TextFrameForOverriding.Text.

**الإرجاع:**
java.lang.String - سلسلة نص الملصق الفعلي
### getLabelShapeType() {#getLabelShapeType--}
```
public abstract int getLabelShapeType()
```


يحصل أو يعيّن نوع الشكل لملصق البيانات. يرجع [ShapeType.NotDefined](../../com.aspose.slides/shapetype\#NotDefined) إذا لم يتم تعريف أي شكل.

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(1);
>      IChartSeries firstSeries = chart.getChartData().getSeries().get_Item(0);
>      // ضبط نوع الشكل للملصق الأول إلى Ellipse.
>      firstSeries.getLabels().get_Item(0).setLabelShapeType(ShapeType.Ellipse);
>      pres.save("ChartWithEllipseLabel.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**الإرجاع:**
int
### setLabelShapeType(int value) {#setLabelShapeType-int-}
```
public abstract void setLabelShapeType(int value)
```


يحصل أو يعيّن نوع الشكل لملصق البيانات. يرجع [ShapeType.NotDefined](../../com.aspose.slides/shapetype\#NotDefined) إذا لم يتم تعريف أي شكل.

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(1);
>      IChartSeries firstSeries = chart.getChartData().getSeries().get_Item(0);
>      // ضبط نوع الشكل للملصق الأول إلى Ellipse.
>      firstSeries.getLabels().get_Item(0).setLabelShapeType(ShapeType.Ellipse);
>      pres.save("ChartWithEllipseLabel.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |