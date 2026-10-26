---
title: DataLabel
second_title: مرجع API Aspose.Slides للغة Java
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
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [DataLabel(IChartDataPoint parentImmediate)](#DataLabel-com.aspose.slides.IChartDataPoint-) | ينشئ مثالًا جديدًا من فئة DataLabel. |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getChart()](#getChart--) | يعيد المخطط الأب. |
| [isVisible()](#isVisible--) | خطأ يعني أن تسمية البيانات غير مرئية (وبالتالي جميع علامات Show\*-flags (ShowValue, ...) تكون خاطئة). |
| [hide()](#hide--) | اجعل تسمية البيانات مخفية عن طريق ضبط جميع علامات Show\*-flags (ShowValue, ...) إلى الحالة الخاطئة. |
| [getActualLabelText()](#getActualLabelText--) | يعيد نص التسمية الفعلي بناءً على إعدادات DataLabelFormat أو قيمة TextFrameForOverriding.Text. |
| [addTextFrameForOverriding(String text)](#addTextFrameForOverriding-java.lang.String-) | تهيئ TextFrameForOverriding بالنص في المعامل "text". |
| [getTextFrameForOverriding()](#getTextFrameForOverriding--) | يمكن أن يحتوي على نص منسق غني. |
| [getTextFormat()](#getTextFormat--) | يعيد تنسيق النص. |
| [getX()](#getX--) | يعيد أو يضبط إحداثي x للعنوان كنسبة من عرض المخطط. |
| [setX(float value)](#setX-float-) | يعيد أو يضبط إحداثي x للعنوان كنسبة من عرض المخطط. |
| [getY()](#getY--) | يعيد أو يضبط إحداثي y للعنوان كنسبة من ارتفاع المخطط. |
| [setY(float value)](#setY-float-) | يعيد أو يضبط إحداثي y للعنوان كنسبة من ارتفاع المخطط. |
| [getWidth()](#getWidth--) | يعيد أو يضبط عرض العنوان كنسبة من عرض المخطط. |
| [setWidth(float value)](#setWidth-float-) | يعيد أو يضبط عرض العنوان كنسبة من عرض المخطط. |
| [getHeight()](#getHeight--) | يعيد أو يضبط ارتفاع العنوان كنسبة من ارتفاع المخطط. |
| [setHeight(float value)](#setHeight-float-) | يعيد أو يضبط ارتفاع العنوان كنسبة من ارتفاع المخطط. |
| [getRight()](#getRight--) | يمين. |
| [getBottom()](#getBottom--) | أسفل. |
| [getDataLabelFormat()](#getDataLabelFormat--) | يعيد تنسيق تسمية البيانات. |
| [getValueFromCell()](#getValueFromCell--) | يحصل أو يضبط خلية بيانات دفتر العمل. |
| [setValueFromCell(IChartDataCell value)](#setValueFromCell-com.aspose.slides.IChartDataCell-) | يحصل أو يضبط خلية بيانات دفتر العمل. |
| [getActualX()](#getActualX--) | يحدد الموقع الفعلي x (اليسار) لعناصر المخطط نسبة إلى الزاوية العليا اليسرى للمخطط. |
| [getActualY()](#getActualY--) | يحدد أعلى العنصر الفعلي للمخطط نسبة إلى الزاوية العليا اليسرى للمخطط. |
| [getActualWidth()](#getActualWidth--) | يحدد العرض الفعلي لعنصر المخطط. |
| [getActualHeight()](#getActualHeight--) | يحدد الارتفاع الفعلي لعنصر المخطط. |
| [getSlide()](#getSlide--) | يعيد الشريحة الأب لتنسيق التعبئة FillFormat. |
| [getPresentation()](#getPresentation--) | يعيد العرض الأب لتنسيق التعبئة FillFormat. |
### DataLabel(IChartDataPoint parentImmediate) {#DataLabel-com.aspose.slides.IChartDataPoint-}
```
public DataLabel(IChartDataPoint parentImmediate)
```

ينشئ مثالًا جديدًا من فئة DataLabel.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| parentImmediate | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | ChartDataPoint الأب. |

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

يعيد المخطط الأب. للقراءة فقط [IChart](../../com.aspose.slides/ichart).

**القيمة المرجعة:**
[IChart](../../com.aspose.slides/ichart)
### isVisible() {#isVisible--}
```
public final boolean isVisible()
```

خطأ يعني أن تسمية البيانات غير مرئية (وبالتالي جميع علامات Show\*-flags (ShowValue, ...) تكون خاطئة). للقراءة فقط boolean .

--------------------

إذا كانت تسمية البيانات مرئية يمكنك إخفاؤها باستخدام طريقة hide(). ولكن إذا كانت غير مرئية (IsVisible هو false) يمكنك جعلها مرئية بتعيين علامات Show\*-flags (ShowValue, ...) إلى الحالة true.

**القيمة المرجعة:**
boolean
### hide() {#hide--}
```
public final void hide()
```

اجعل تسمية البيانات مخفية عن طريق ضبط جميع علامات Show\*-flags (ShowValue, ...) إلى الحالة الخاطئة. سيكون IsVisible false بعد ذلك.

--------------------

إذا كانت تسمية البيانات غير مرئية (IsVisible هو false) يمكنك جعلها مرئية بتعيين علامات Show\*-flags (ShowValue, ...) إلى الحالة true.

### getActualLabelText() {#getActualLabelText--}
```
public final String getActualLabelText()
```

يعيد نص التسمية الفعلي بناءً على إعدادات DataLabelFormat أو قيمة TextFrameForOverriding.Text.

**القيمة المرجعة:**
java.lang.String - كائن java.lang.String.
### addTextFrameForOverriding(String text) {#addTextFrameForOverriding-java.lang.String-}
```
public final ITextFrame addTextFrameForOverriding(String text)
```

تهيئ TextFrameForOverriding بالنص في المعامل "text". إذا كان TextFrameForOverriding مهيئًا مسبقًا فسيتم فقط تعديل نصه.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| text | java.lang.String | نص لإطار النص الجديد TextFrameForOverriding. |

**القيمة المرجعة:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getTextFrameForOverriding() {#getTextFrameForOverriding--}
```
public final ITextFrame getTextFrameForOverriding()
```

يمكن أن يحتوي على نص منسق غني. إذا لم تكن هذه الخاصية فارغة فسيحل النص المنسق هذا محل النص المُولد تلقائيًا لتسمية البيانات. النص المُولد تلقائيًا لتسمية البيانات يعني النص الذي يديره خصائص ShowSeriesName, ShowValue, ... ويتم تنسيقه باستخدام الخاصية TextFormatManager.TextFormat. للقراءة فقط [ITextFrame](../../com.aspose.slides/itextframe).

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

يعيد أو يضبط إحداثي x للعنوان كنسبة من عرض المخطط. قراءة/كتابة float .

**القيمة المرجعة:**
float
### setX(float value) {#setX-float-}
```
public final void setX(float value)
```

يعيد أو يضبط إحداثي x للعنوان كنسبة من عرض المخطط. قراءة/كتابة float .

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getY() {#getY--}
```
public final float getY()
```

يعيد أو يضبط إحداثي y للعنوان كنسبة من ارتفاع المخطط. قراءة/كتابة float .

**القيمة المرجعة:**
float
### setY(float value) {#setY-float-}
```
public final void setY(float value)
```

يعيد أو يضبط إحداثي y للعنوان كنسبة من ارتفاع المخطط. قراءة/كتابة float .

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getWidth() {#getWidth--}
```
public final float getWidth()
```

يعيد أو يضبط عرض العنوان كنسبة من عرض المخطط. قراءة/كتابة float .

**القيمة المرجعة:**
float
### setWidth(float value) {#setWidth-float-}
```
public final void setWidth(float value)
```

يعيد أو يضبط عرض العنوان كنسبة من عرض المخطط. قراءة/كتابة float .

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getHeight() {#getHeight--}
```
public final float getHeight()
```

يعيد أو يضبط ارتفاع العنوان كنسبة من ارتفاع المخطط. قراءة/كتابة float .

**القيمة المرجعة:**
float
### setHeight(float value) {#setHeight-float-}
```
public final void setHeight(float value)
```

يعيد أو يضبط ارتفاع العنوان كنسبة من ارتفاع المخطط. قراءة/كتابة float .

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getRight() {#getRight--}
```
public final float getRight()
```

يمين. للقراءة فقط float .

**القيمة المرجعة:**
float
### getBottom() {#getBottom--}
```
public final float getBottom()
```

أسفل. للقراءة فقط float .

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

يحصل أو يضبط خلية بيانات دفتر العمل. يُطبق إذا كانت الخاصية IDataLabelFormat.ShowLabelValueFromCell تساوي true.

**القيمة المرجعة:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setValueFromCell(IChartDataCell value) {#setValueFromCell-com.aspose.slides.IChartDataCell-}
```
public final void setValueFromCell(IChartDataCell value)
```

يحصل أو يضبط خلية بيانات دفتر العمل. يُطبق إذا كانت الخاصية IDataLabelFormat.ShowLabelValueFromCell تساوي true.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |

### getActualX() {#getActualX--}
```
public final float getActualX()
```

يحدد الموقع الفعلي x (اليسار) لعنصر المخطط نسبة إلى الزاوية العليا اليسرى للمخطط. استدعِ الطريقة IChart.ValidateChartLayout() مسبقًا للحصول على القيم الفعلية. قراءة float .

**القيمة المرجعة:**
float
### getActualY() {#getActualY--}
```
public final float getActualY()
```

يحدد أعلى العنصر الفعلي للمخطط نسبة إلى الزاوية العليا اليسرى للمخطط. استدعِ الطريقة IChart.ValidateChartLayout() مسبقًا للحصول على القيم الفعلية. قراءة float .

**القيمة المرجعة:**
float
### getActualWidth() {#getActualWidth--}
```
public final float getActualWidth()
```

يحدد العرض الفعلي لعنصر المخطط. استدعِ الطريقة IChart.ValidateChartLayout() مسبقًا للحصول على القيم الفعلية. قراءة float .

**القيمة المرجعة:**
float
### getActualHeight() {#getActualHeight--}
```
public final float getActualHeight()
```

يحدد الارتفاع الفعلي لعنصر المخطط. استدعِ الطريقة IChart.ValidateChartLayout() مسبقًا للحصول على القيم الفعلية. قراءة float .

**القيمة المرجعة:**
float
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

يعيد الشريحة الأب لتنسيق التعبئة FillFormat. للقراءة فقط [BaseSlide](../../com.aspose.slides/baseslide).

**القيمة المرجعة:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

يعيد العرض الأب لتنسيق التعبئة FillFormat. للقراءة فقط [IPresentation](../../com.aspose.slides/ipresentation).

**القيمة المرجعة:**
[IPresentation](../../com.aspose.slides/ipresentation)