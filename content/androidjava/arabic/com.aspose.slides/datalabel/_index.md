---
title: DataLabel
second_title: Aspose.Slides لنظام Android عبر مرجع API لجافا
description: يمثل تسميات السلسلة.
type: docs
url: /ar/com.aspose.slides/datalabel/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IDataLabel](../../com.aspose.slides/idatalabel), com.aspose.slides.IDOMObject
```
public class DataLabel implements IDataLabel, IDOMObject
```

يمثل تسميات السلسلة.
## Constructors

| Constructor | Description |
| --- | --- |
| [DataLabel(IChartDataPoint parentImmediate)](#DataLabel-com.aspose.slides.IChartDataPoint-) | ينشئ مثيلاً جديداً من الفئة DataLabel. |
## Methods

| Method | Description |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getChart()](#getChart--) | يرجع المخطط الأب. |
| [isVisible()](#isVisible--) | يعني False أن تسمية البيانات غير مرئية (وبالتالي جميع علامات Show\*-flags (ShowValue, ...) تكون False). |
| [hide()](#hide--) | يجعل تسمية البيانات مخفية عن طريق ضبط جميع علامات Show\*-flags (ShowValue, ...) إلى الحالة False. |
| [getActualLabelText()](#getActualLabelText--) | يرجع نص التسمية الفعلي بناءً على إعدادات DataLabelFormat أو قيمة TextFrameForOverriding.Text. |
| [addTextFrameForOverriding(String text)](#addTextFrameForOverriding-java.lang.String-) | يهيئ TextFrameForOverriding بالنص الموجود في المعامل "text". |
| [getTextFrameForOverriding()](#getTextFrameForOverriding--) | يمكن أن يحتوي على نص منسق غني. |
| [getTextFormat()](#getTextFormat--) | يرجع تنسيق النص. |
| [getX()](#getX--) | يرجع أو يحدد إحداثي x للعنوان كنسبة من عرض المخطط. |
| [setX(float value)](#setX-float-) | يرجع أو يحدد إحداثي x للعنوان كنسبة من عرض المخطط. |
| [getY()](#getY--) | يرجع أو يحدد إحداثي y للعنوان كنسبة من ارتفاع المخطط. |
| [setY(float value)](#setY-float-) | يرجع أو يحدد إحداثي y للعنوان كنسبة من ارتفاع المخطط. |
| [getWidth()](#getWidth--) | يرجع أو يحدد عرض العنوان كنسبة من عرض المخطط. |
| [setWidth(float value)](#setWidth-float-) | يرجع أو يحدد عرض العنوان كنسبة من عرض المخطط. |
| [getHeight()](#getHeight--) | يرجع أو يحدد ارتفاع العنوان كنسبة من ارتفاع المخطط. |
| [setHeight(float value)](#setHeight-float-) | يرجع أو يحدد ارتفاع العنوان كنسبة من ارتفاع المخطط. |
| [getRight()](#getRight--) | يمين. |
| [getBottom()](#getBottom--) | أسفل. |
| [getDataLabelFormat()](#getDataLabelFormat--) | يرجع تنسيق تسمية البيانات. |
| [getValueFromCell()](#getValueFromCell--) | يحصل أو يضبط خلية بيانات المصنف. |
| [setValueFromCell(IChartDataCell value)](#setValueFromCell-com.aspose.slides.IChartDataCell-) | يحصل أو يضبط خلية بيانات المصنف. |
| [getActualX()](#getActualX--) | يحدد الموقع الفعلي للإحداثي x (اليسار) لعنصر المخطط نسبةً إلى الزاوية اليسرى العليا للمخطط. |
| [getActualY()](#getActualY--) | يحدد الجزء العلوي الفعلي لعنصر المخطط نسبةً إلى الزاوية اليسرى العليا للمخطط. |
| [getActualWidth()](#getActualWidth--) | يحدد العرض الفعلي لعنصر المخطط. |
| [getActualHeight()](#getActualHeight--) | يحدد الارتفاع الفعلي لعنصر المخطط. |
| [getSlide()](#getSlide--) | يرجع الشريحة الأب لملء الشكل FillFormat. |
| [getPresentation()](#getPresentation--) | يرجع العرض التقديمي الأب لملء الشكل FillFormat. |
### DataLabel(IChartDataPoint parentImmediate) {#DataLabel-com.aspose.slides.IChartDataPoint-}
```
public DataLabel(IChartDataPoint parentImmediate)
```

ينشئ مثيلاً جديداً من الفئة DataLabel.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| parentImmediate | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | نقطة بيانات المخطط الأب. |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

يرجع كائن Parent_Immediate. قراءة فقط IDOMObject.

**Returns:**
com.aspose.slides.IDOMObject
### getChart() {#getChart--}
```
public final IChart getChart()
```

يرجع المخطط الأب. قراءة فقط [IChart](../../com.aspose.slides/ichart).

**Returns:**
[IChart](../../com.aspose.slides/ichart)
### isVisible() {#isVisible--}
```
public final boolean isVisible()
```

يعني False أن تسمية البيانات غير مرئية (وبالتالي جميع علامات Show\*-flags (ShowValue, ...) تكون False). قراءة فقط boolean.

--------------------

إذا كانت تسمية البيانات مرئية يمكنك إخفاؤها باستخدام الطريقة hide(). أما إذا كانت غير مرئية (IsVisible هو False) يمكنك جعلها مرئية عن طريق ضبط علامات Show\*-flags (ShowValue, ...) إلى الحالة True.

**Returns:**
boolean
### hide() {#hide--}
```
public final void hide()
```

يجعل تسمية البيانات مخفية عن طريق ضبط جميع علامات Show\*-flags (ShowValue, ...) إلى الحالة False. سيكون IsVisible هو False بعد ذلك.

--------------------

إذا كانت تسمية البيانات غير مرئية (IsVisible هو False) يمكنك جعلها مرئية عن طريق ضبط علامات Show\*-flags (ShowValue, ...) إلى الحالة True.

### getActualLabelText() {#getActualLabelText--}
```
public final String getActualLabelText()
```

يرجع نص التسمية الفعلي بناءً على إعدادات DataLabelFormat أو قيمة TextFrameForOverriding.Text.

**Returns:**
java.lang.String - كائن java.lang.String.
### addTextFrameForOverriding(String text) {#addTextFrameForOverriding-java.lang.String-}
```
public final ITextFrame addTextFrameForOverriding(String text)
```

يهيئ TextFrameForOverriding بالنص الموجود في المعامل "text". إذا كان TextFrameForOverriding مهيئاً مسبقاً فستغير نصه فقط.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | النص لإطار النص الجديد TextFrameForOverriding. |

**Returns:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getTextFrameForOverriding() {#getTextFrameForOverriding--}
```
public final ITextFrame getTextFrameForOverriding()
```

يمكن أن يحتوي على نص منسق غني. إذا لم تكن هذه الخاصية null فإن قيمة النص المنسق تتجاوز النص المولد تلقائياً لتسمية البيانات. النص المولد تلقائياً لتسمية البيانات هو النص الذي تديره خصائص ShowSeriesName و ShowValue ... ويتم تنسيقه باستخدام خاصية TextFormatManager.TextFormat. قراءة فقط [ITextFrame](../../com.aspose.slides/itextframe).

**Returns:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```

يرجع تنسيق النص. قراءة فقط [IChartTextFormat](../../com.aspose.slides/icharttextformat).

**Returns:**
[IChartTextFormat](../../com.aspose.slides/icharttextformat)
### getX() {#getX--}
```
public final float getX()
```

يرجع أو يحدد إحداثي x للعنوان كنسبة من عرض المخطط. قراءة/كتابة float.

**Returns:**
float
### setX(float value) {#setX-float-}
```
public final void setX(float value)
```

يرجع أو يحدد إحداثي x للعنوان كنسبة من عرض المخطط. قراءة/كتابة float.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getY() {#getY--}
```
public final float getY()
```

يرجع أو يحدد إحداثي y للعنوان كنسبة من ارتفاع المخطط. قراءة/كتابة float.

**Returns:**
float
### setY(float value) {#setY-float-}
```
public final void setY(float value)
```

يرجع أو يحدد إحداثي y للعنوان كنسبة من ارتفاع المخطط. قراءة/كتابة float.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getWidth() {#getWidth--}
```
public final float getWidth()
```

يرجع أو يحدد عرض العنوان كنسبة من عرض المخطط. قراءة/كتابة float.

**Returns:**
float
### setWidth(float value) {#setWidth-float-}
```
public final void setWidth(float value)
```

يرجع أو يحدد عرض العنوان كنسبة من عرض المخطط. قراءة/كتابة float.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getHeight() {#getHeight--}
```
public final float getHeight()
```

يرجع أو يحدد ارتفاع العنوان كنسبة من ارتفاع المخطط. قراءة/كتابة float.

**Returns:**
float
### setHeight(float value) {#setHeight-float-}
```
public final void setHeight(float value)
```

يرجع أو يحدد ارتفاع العنوان كنسبة من ارتفاع المخطط. قراءة/كتابة float.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getRight() {#getRight--}
```
public final float getRight()
```

يمين. قراءة فقط float.

**Returns:**
float
### getBottom() {#getBottom--}
```
public final float getBottom()
```

أسفل. قراءة فقط float.

**Returns:**
float
### getDataLabelFormat() {#getDataLabelFormat--}
```
public final IDataLabelFormat getDataLabelFormat()
```

يرجع تنسيق تسمية البيانات. قراءة فقط [IDataLabelFormat](../../com.aspose.slides/idatalabelformat).

**Returns:**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
### getValueFromCell() {#getValueFromCell--}
```
public final IChartDataCell getValueFromCell()
```

يحصل أو يضبط خلية بيانات المصنف. يُطبق إذا كانت الخاصية IDataLabelFormat.ShowLabelValueFromCell تساوي true.

**Returns:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setValueFromCell(IChartDataCell value) {#setValueFromCell-com.aspose.slides.IChartDataCell-}
```
public final void setValueFromCell(IChartDataCell value)
```

يحصل أو يضبط خلية بيانات المصنف. يُطبق إذا كانت الخاصية IDataLabelFormat.ShowLabelValueFromCell تساوي true.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |

### getActualX() {#getActualX--}
```
public final float getActualX()
```

يحدد الموقع الفعلي للإحداثي x (اليسار) لعنصر المخطط نسبةً إلى الزاوية اليسرى العليا للمخطط. استدعِ الطريقة IChart.ValidateChartLayout() مسبقاً للحصول على القيم الفعلية. قراءة float.

**Returns:**
float
### getActualY() {#getActualY--}
```
public final float getActualY()
```

يحدد الجزء العلوي الفعلي لعنصر المخطط نسبةً إلى الزاوية اليسرى العليا للمخطط. استدعِ الطريقة IChart.ValidateChartLayout() مسبقاً للحصول على القيم الفعلية. قراءة float.

**Returns:**
float
### getActualWidth() {#getActualWidth--}
```
public final float getActualWidth()
```

يحدد العرض الفعلي لعنصر المخطط. استدعِ الطريقة IChart.ValidateChartLayout() مسبقاً للحصول على القيم الفعلية. قراءة float.

**Returns:**
float
### getActualHeight() {#getActualHeight--}
```
public final float getActualHeight()
```

يحدد الارتفاع الفعلي لعنصر المخطط. استدعِ الطريقة IChart.ValidateChartLayout() مسبقاً للحصول على القيم الفعلية. قراءة float.

**Returns:**
float
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

يرجع الشريحة الأب لملء الشكل FillFormat. قراءة فقط [BaseSlide](../../com.aspose.slides/baseslide).

**Returns:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

يرجع العرض التقديمي الأب لملء الشكل FillFormat. قراءة فقط [IPresentation](../../com.aspose.slides/ipresentation).

**Returns:**
[IPresentation](../../com.aspose.slides/ipresentation)