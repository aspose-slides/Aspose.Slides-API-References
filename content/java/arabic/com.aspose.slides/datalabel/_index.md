---
title: DataLabel
second_title: مرجع API لـ Aspose.Slides للغة Java
description: يمثل تسميات السلسلة.
type: docs
url: /ar/com.aspose.slides/datalabel/
---
**الوراثة:**
java.lang.Object

**جميع الواجهات المنفذة:**
[com.aspose.slides.IDataLabel](../../com.aspose.slides/idatalabel), com.aspose.slides.IDOMObject
```
public class DataLabel implements IDataLabel, IDOMObject
```

يمثل تسميات السلسلة.
## المنشئ

| المنشيء | الوصف |
| --- | --- |
| [DataLabel(IChartDataPoint parentImmediate)](#DataLabel-com.aspose.slides.IChartDataPoint-) | ينشئ مثالًا جديدًا من الفئة DataLabel. |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getChart()](#getChart--) | يعيد المخطط الأصلي. |
| [isVisible()](#isVisible--) | قيمة False تعني أن تسمية البيانات غير مرئية (وبالتالي كل أعلام Show*-flags (ShowValue, ...) تكون False). |
| [hide()](#hide--) | اجعل تسمية البيانات مخفية عن طريق ضبط جميع أعلام Show*-flags (ShowValue, ...) إلى الحالة False. |
| [getActualLabelText()](#getActualLabelText--) | يعيد النص الفعلي للتسمية بناءً على إعدادات DataLabelFormat أو قيمة TextFrameForOverriding.Text. |
| [addTextFrameForOverriding(String text)](#addTextFrameForOverriding-java.lang.String-) | تهيئة TextFrameForOverriding بالنص في المعامل "text". |
| [getTextFrameForOverriding()](#getTextFrameForOverriding--) | يمكن أن يحتوي على نص منسق غني. |
| [getTextFormat()](#getTextFormat--) | يعيد تنسيق النص. |
| [getX()](#getX--) | يعيد أو يحدد الإحداثي x للعنوان كنسبة من عرض المخطط. |
| [setX(float value)](#setX-float-) | يعيد أو يحدد الإحداثي x للعنوان كنسبة من عرض المخطط. |
| [getY()](#getY--) | يعيد أو يحدد الإحداثي y للعنوان كنسبة من ارتفاع المخطط. |
| [setY(float value)](#setY-float-) | يعيد أو يحدد الإحداثي y للعنوان كنسبة من ارتفاع المخطط. |
| [getWidth()](#getWidth--) | يعيد أو يحدد عرض العنوان كنسبة من عرض المخطط. |
| [setWidth(float value)](#setWidth-float-) | يعيد أو يحدد عرض العنوان كنسبة من عرض المخطط. |
| [getHeight()](#getHeight--) | يعيد أو يحدد ارتفاع العنوان كنسبة من ارتفاع المخطط. |
| [setHeight(float value)](#setHeight-float-) | يعيد أو يحدد ارتفاع العنوان كنسبة من ارتفاع المخطط. |
| [getRight()](#getRight--) | يمين. |
| [getBottom()](#getBottom--) | أسفل. |
| [getDataLabelFormat()](#getDataLabelFormat--) | يعيد تنسيق تسمية البيانات. |
| [getValueFromCell()](#getValueFromCell--) | يحصل أو يحدد خلية بيانات دفتر العمل. |
| [setValueFromCell(IChartDataCell value)](#setValueFromCell-com.aspose.slides.IChartDataCell-) | يحصل أو يحدد خلية بيانات دفتر العمل. |
| [getLabelShapeType()](#getLabelShapeType--) | يحصل أو يحدد نوع الشكل لتسمية البيانات. |
| [setLabelShapeType(int value)](#setLabelShapeType-int-) | يحصل أو يحدد نوع الشكل لتسمية البيانات. |
| [getActualX()](#getActualX--) | يحدد الموقع الفعلي x (اليسار) لعنصر المخطط بالنسبة إلى الزاوية اليسرى العليا للمخطط. |
| [getActualY()](#getActualY--) | يحدد أعلى عنصر المخطط الفعلي بالنسبة إلى الزاوية اليسرى العليا للمخطط. |
| [getActualWidth()](#getActualWidth--) | يحدد العرض الفعلي لعنصر المخطط. |
| [getActualHeight()](#getActualHeight--) | يحدد الارتفاع الفعلي لعنصر المخطط. |
| [getSlide()](#getSlide--) | يعيد الشريحة الأصلية لكائن FillFormat. |
| [getPresentation()](#getPresentation--) | يعيد العرض التقديمي الأصلي لكائن FillFormat. |

### DataLabel(IChartDataPoint parentImmediate) {#DataLabel-com.aspose.slides.IChartDataPoint-}
```
public DataLabel(IChartDataPoint parentImmediate)
```

ينشئ مثالًا جديدًا من الفئة DataLabel.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| parentImmediate | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | نقطة البيانات الأصلية للمخطط. |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

يعيد كائن Parent_Immediate. للقراءة فقط IDOMObject.

**القيمة المرجعة:**
com.aspose.slides.IDOMObject

### getChart() {#getChart--}
```
public final IChart getChart()
```

يعيد المخطط الأصلي. للقراءة فقط [IChart](../../com.aspose.slides/ichart).

**القيمة المرجعة:**
[IChart](../../com.aspose.slides/ichart)

### isVisible() {#isVisible--}
```
public final boolean isVisible()
```

قيمة False تعني أن تسمية البيانات غير مرئية (وبالتالي كل أعلام Show*-flags (ShowValue, ...) تكون False). للقراءة فقط boolean.

--------------------

إذا كانت تسمية البيانات مرئية يمكنك إخفاؤها باستخدام طريقة Hide(). ولكن إذا كانت غير مرئية (IsVisible هو false) يمكنك جعلها مرئية بتعيين أعلام Show*-flags (ShowValue, ...) إلى الحالة true.

**القيمة المرجعة:**
boolean

### hide() {#hide--}
```
public final void hide()
```

اجعل تسمية البيانات مخفية عن طريق ضبط جميع أعلام Show*-flags (ShowValue, ...) إلى الحالة False. ستكون IsVisible = false بعدها.

--------------------

إذا كانت تسمية البيانات غير مرئية (IsVisible هو false) يمكنك جعلها مرئية بتعيين أعلام Show*-flags (ShowValue, ...) إلى الحالة true.

### getActualLabelText() {#getActualLabelText--}
```
public final String getActualLabelText()
```

يعيد النص الفعلي للتسمية بناءً على إعدادات DataLabelFormat أو قيمة TextFrameForOverriding.Text.

**القيمة المرجعة:**
java.lang.String - كائن java.lang.String.

### addTextFrameForOverriding(String text) {#addTextFrameForOverriding-java.lang.String-}
```
public final ITextFrame addTextFrameForOverriding(String text)
```

تهيئة TextFrameForOverriding بالنص في المعامل "text". إذا كان TextFrameForOverriding مهيئًا مسبقًا فسيتم تعديل نصه فقط.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| text | java.lang.String | نص لإطار TextFrameForOverriding الجديد. |

**القيمة المرجعة:**
[ITextFrame](../../com.aspose.slides/itextframe)

### getTextFrameForOverriding() {#getTextFrameForOverriding--}
```
public final ITextFrame getTextFrameForOverriding()
```

يمكن أن يحتوي على نص منسق غني. إذا لم يكن هذا الخصائص null فإن قيمة النص المنسق تتجاوز النص المولد تلقائيًا لتسمية البيانات. النص المولد تلقائيًا لتسمية البيانات يعني النص الذي تُديره خصائص ShowSeriesName, ShowValue, … ويتم تنسيقه بخصائص TextFormatManager.TextFormat. للقراءة فقط [ITextFrame](../../com.aspose.slides/itextframe).

**القيمة المرجعة:**
[ITextFrame](../../com.aspose.slides/itextframe)

### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```

يعيد تنسيق النص. للقراءة فقط [IChartTextFormat](../../com.aspose.slides/icharttextformat).

**القيمة المرجعة:**
[IChartTextFormat](../../com.aspose.slides/icharttextformat)

### getX() {#getX--}
```
public final float getX()
```

يعيد أو يحدد الإحداثي x للعنوان كنسبة من عرض المخطط. للقراءة/الكتابة float.

**القيمة المرجعة:**
float

### setX(float value) {#setX-float-}
```
public final void setX(float value)
```

يعيد أو يحدد الإحداثي x للعنوان كنسبة من عرض المخطط. للقراءة/الكتابة float.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getY() {#getY--}
```
public final float getY()
```

يعيد أو يحدد الإحداثي y للعنوان كنسبة من ارتفاع المخطط. للقراءة/الكتابة float.

**القيمة المرجعة:**
float

### setY(float value) {#setY-float-}
```
public final void setY(float value)
```

يعيد أو يحدد الإحداثي y للعنوان كنسبة من ارتفاع المخطط. للقراءة/الكتابة float.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getWidth() {#getWidth--}
```
public final float getWidth()
```

يعيد أو يحدد عرض العنوان كنسبة من عرض المخطط. للقراءة/الكتابة float.

**القيمة المرجعة:**
float

### setWidth(float value) {#setWidth-float-}
```
public final void setWidth(float value)
```

يعيد أو يحدد عرض العنوان كنسبة من عرض المخطط. للقراءة/الكتابة float.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getHeight() {#getHeight--}
```
public final float getHeight()
```

يعيد أو يحدد ارتفاع العنوان كنسبة من ارتفاع المخطط. للقراءة/الكتابة float.

**القيمة المرجعة:**
float

### setHeight(float value) {#setHeight-float-}
```
public final void setHeight(float value)
```

يعيد أو يحدد ارتفاع العنوان كنسبة من ارتفاع المخطط. للقراءة/الكتابة float.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getRight() {#getRight--}
```
public final float getRight()
```

يمين. للقراءة فقط float.

**القيمة المرجعة:**
float

### getBottom() {#getBottom--}
```
public final float getBottom()
```

أسفل. للقراءة فقط float.

**القيمة المرجعة:**
float

### getDataLabelFormat() {#getDataLabelFormat--}
```
public final IDataLabelFormat getDataLabelFormat()
```

يعيد تنسيق تسمية البيانات. للقراءة فقط [IDataLabelFormat](../../com.aspose.slides/idatalabelformat).

**القيمة المرجعة:**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)

### getValueFromCell() {#getValueFromCell--}
```
public final IChartDataCell getValueFromCell()
```

يحصل أو يحدد خلية بيانات دفتر العمل. يُطبق إذا كانت الخاصية IDataLabelFormat.ShowLabelValueFromCell تساوي true.

**القيمة المرجعة:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)

### setValueFromCell(IChartDataCell value) {#setValueFromCell-com.aspose.slides.IChartDataCell-}
```
public final void setValueFromCell(IChartDataCell value)
```

يحصل أو يحدد خلية بيانات دفتر العمل. يُطبق إذا كانت الخاصية IDataLabelFormat.ShowLabelValueFromCell تساوي true.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |

### getLabelShapeType() {#getLabelShapeType--}
```
public final int getLabelShapeType()
```

يحصل أو يحدد نوع الشكل لتسمية البيانات. يرجع [ShapeType.NotDefined](../../com.aspose.slides/shapetype\#NotDefined) إذا لم يُحدد شكل.

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(1);
>      IChartSeries firstSeries = chart.getChartData().getSeries().get_Item(0);
>      // اضبط نوع الشكل للتسمية البيانات الأولى إلى Ellipse.
>      firstSeries.getLabels().get_Item(0).setLabelShapeType(ShapeType.Ellipse);
>      pres.save("ChartWithEllipseLabel.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**القيمة المرجعة:**
int

### setLabelShapeType(int value) {#setLabelShapeType-int-}
```
public final void setLabelShapeType(int value)
```

يحصل أو يحدد نوع الشكل لتسمية البيانات. يرجع [ShapeType.NotDefined](../../com.aspose.slides/shapetype\#NotDefined) إذا لم يُحدد شكل.

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(1);
>      IChartSeries firstSeries = chart.getChartData().getSeries().get_Item(0);
>      // اضبط نوع الشكل للتسمية البيانات الأولى إلى Ellipse.
>      firstSeries.getLabels().get_Item(0).setLabelShapeType(ShapeType.Ellipse);
>      pres.save("ChartWithEllipseLabel.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getActualX() {#getActualX--}
```
public final float getActualX()
```

يحدد الموقع الفعلي x (اليسار) لعنصر المخطط بالنسبة إلى الزاوية اليسرى العليا للمخطط. استدعِ الطريقة IChart.ValidateChartLayout() مسبقًا للحصول على القيم الفعلية. للقراءة float.

**القيمة المرجعة:**
float

### getActualY() {#getActualY--}
```
public final float getActualY()
```

يحدد أعلى عنصر المخطط الفعلي بالنسبة إلى الزاوية اليسرى العليا للمخطط. استدعِ الطريقة IChart.ValidateChartLayout() مسبقًا للحصول على القيم الفعلية. للقراءة float.

**القيمة المرجعة:**
float

### getActualWidth() {#getActualWidth--}
```
public final float getActualWidth()
```

يحدد العرض الفعلي لعنصر المخطط. استدعِ الطريقة IChart.ValidateChartLayout() مسبقًا للحصول على القيم الفعلية. للقراءة float.

**القيمة المرجعة:**
float

### getActualHeight() {#getActualHeight--}
```
public final float getActualHeight()
```

يحدد الارتفاع الفعلي لعنصر المخطط. استدعِ الطريقة IChart.ValidateChartLayout() مسبقًا للحصول على القيم الفعلية. للقراءة float.

**القيمة المرجعة:**
float

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

يعيد الشريحة الأصلية لكائن FillFormat. للقراءة فقط [BaseSlide](../../com.aspose.slides/baseslide).

**القيمة المرجعة:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

يعيد العرض التقديمي الأصلي لكائن FillFormat. للقراءة فقط [IPresentation](../../com.aspose.slides/ipresentation).

**القيمة المرجعة:**
[IPresentation](../../com.aspose.slides/ipresentation)