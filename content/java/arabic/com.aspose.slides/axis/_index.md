---
title: Axis
second_title: "مرجع API لـ Aspose.Slides للغة Java"
description: "يحتوي على الكائن الذي يمثل محور الرسم البياني."
type: docs
url: /ar/com.aspose.slides/axis/
---
**الوراثة:**  
java.lang.Object, com.aspose.slides.DomObject

**جميع الواجهات المنفذة:**  
[com.aspose.slides.IAxis](../../com.aspose.slides/iaxis)  
```
public class Axis extends DomObject<AxesManager> implements IAxis
```

يغلف الكائن الذي يمثل محور المخطط.

## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getChart()](#getChart--) | إرجاع المخطط الأب. |
| [getAxisBetweenCategories()](#getAxisBetweenCategories--) | يوضح ما إذا كان محور القيم يتقاطع مع محور الفئة بين الفئات. |
| [setAxisBetweenCategories(boolean value)](#setAxisBetweenCategories-boolean-) | يوضح ما إذا كان محور القيم يتقاطع مع محور الفئة بين الفئات. |
| [getCategoryAxisType()](#getCategoryAxisType--) | يحدد نوع محور الفئة. |
| [setCategoryAxisType(int value)](#setCategoryAxisType-int-) | يحدد نوع محور الفئة. |
| [setCategoryAxisTypeAutomatically()](#setCategoryAxisTypeAutomatically--) | يضبط خاصية IAxis.CategoryAxisType بقيمة يتم تحديدها تلقائيًا بناءً على بيانات المحور. |
| [getCrossAt()](#getCrossAt--) | يوضح النقطة على المحور حيث يتقاطع المحور العمودي معه. |
| [setCrossAt(float value)](#setCrossAt-float-) | يوضح النقطة على المحور حيث يتقاطع المحور العمودي معه. |
| [getDisplayUnit()](#getDisplayUnit--) | يحدد قيمة مقياس وحدات العرض لمحور القيم. |
| [setDisplayUnit(int value)](#setDisplayUnit-int-) | يحدد قيمة مقياس وحدات العرض لمحور القيم. |
| [getActualMaxValue()](#getActualMaxValue--) | يحدد القيمة القصوى الفعلية على المحور. |
| [getActualMinValue()](#getActualMinValue--) | يحدد القيمة الدنيا الفعلية على المحور. |
| [getActualMajorUnit()](#getActualMajorUnit--) | يحدد الوحدة الرئيسية الفعلية للمحور. |
| [getActualMinorUnit()](#getActualMinorUnit--) | يحدد الوحدة الفرعية الفعلية للمحور. |
| [getActualMajorUnitScale()](#getActualMajorUnitScale--) | يحدد مقياس الوحدة الرئيسية الفعلية للمحور. |
| [getActualMinorUnitScale()](#getActualMinorUnitScale--) | يحدد مقياس الوحدة الفرعية الفعلية للمحور. |
| [isAutomaticMaxValue()](#isAutomaticMaxValue--) | يحدد ما إذا كان يتم تعيين القيمة القصوى تلقائيًا. |
| [setAutomaticMaxValue(boolean value)](#setAutomaticMaxValue-boolean-) | يحدد ما إذا كان يتم تعيين القيمة القصوى تلقائيًا. |
| [getMaxValue()](#getMaxValue--) | يوضح القيمة القصوى على محور القيم. |
| [setMaxValue(double value)](#setMaxValue-double-) | يوضح القيمة القصوى على محور القيم. |
| [getMinorUnit()](#getMinorUnit--) | يوضح الوحدات الفرعية لتاريخ أو محور القيم. |
| [setMinorUnit(double value)](#setMinorUnit-double-) | يوضح الوحدات الفرعية لتاريخ أو محور القيم. |
| [isAutomaticMinorUnit()](#isAutomaticMinorUnit--) | يحدد ما إذا كان يتم تعيين الوحدة الفرعية للمحور تلقائيًا. |
| [setAutomaticMinorUnit(boolean value)](#setAutomaticMinorUnit-boolean-) | يحدد ما إذا كان يتم تعيين الوحدة الفرعية للمحور تلقائيًا. |
| [getMajorUnit()](#getMajorUnit--) | يوضح الوحدات الرئيسية لتاريخ أو محور القيم. |
| [setMajorUnit(double value)](#setMajorUnit-double-) | يوضح الوحدات الرئيسية لتاريخ أو محور القيم. |
| [isAutomaticMajorUnit()](#isAutomaticMajorUnit--) | يحدد ما إذا كان يتم تعيين الوحدة الرئيسية للمحور تلقائيًا. |
| [setAutomaticMajorUnit(boolean value)](#setAutomaticMajorUnit-boolean-) | يحدد ما إذا كان يتم تعيين الوحدة الرئيسية للمحور تلقائيًا. |
| [isAutomaticMinValue()](#isAutomaticMinValue--) | يحدد ما إذا كان يتم تعيين القيمة الدنيا تلقائيًا. |
| [setAutomaticMinValue(boolean value)](#setAutomaticMinValue-boolean-) | يحدد ما إذا كان يتم تعيين القيمة الدنيا تلقائيًا. |
| [getMinValue()](#getMinValue--) | يوضح القيمة الدنيا على محور القيم. |
| [setMinValue(double value)](#setMinValue-double-) | يوضح القيمة الدنيا على محور القيم. |
| [isLogarithmic()](#isLogarithmic--) | يوضح ما إذا كان نوع مقياس محور القيم لوغاريتمي أم لا. |
| [setLogarithmic(boolean value)](#setLogarithmic-boolean-) | يوضح ما إذا كان نوع مقياس محور القيم لوغاريتمي أم لا. |
| [getLogBase()](#getLogBase--) | يوضح القاعدة اللوغاريتمية. |
| [setLogBase(double value)](#setLogBase-double-) | يوضح القاعدة اللوغاريتمية. |
| [isPlotOrderReversed()](#isPlotOrderReversed--) | يوضح ما إذا كان MS PowerPoint يرسم نقاط البيانات من الأخير إلى الأول. |
| [setPlotOrderReversed(boolean value)](#setPlotOrderReversed-boolean-) | يوضح ما إذا كان MS PowerPoint يرسم نقاط البيانات من الأخير إلى الأول. |
| [isVisible()](#isVisible--) | يوضح ما إذا كان المحور مرئيًا. |
| [setVisible(boolean value)](#setVisible-boolean-) | يوضح ما إذا كان المحور مرئيًا. |
| [getMajorTickMark()](#getMajorTickMark--) | يوضح نوع علامة الفاصل الرئيسية للمحور المحدد. |
| [setMajorTickMark(int value)](#setMajorTickMark-int-) | يوضح نوع علامة الفاصل الرئيسية للمحور المحدد. |
| [getMinorTickMark()](#getMinorTickMark--) | يوضح نوع علامة الفاصل الفرعية للمحور المحدد. |
| [setMinorTickMark(int value)](#setMinorTickMark-int-) | يوضح نوع علامة الفاصل الفرعية للمحور المحدد. |
| [getTickLabelPosition()](#getTickLabelPosition--) | يوضح موضع تسميات علامات الفواصل على المحور المحدد. |
| [setTickLabelPosition(int value)](#setTickLabelPosition-int-) | يوضح موضع تسميات علامات الفواصل على المحور المحدد. |
| [getMajorUnitScale()](#getMajorUnitScale--) | يوضح مقياس الوحدة الرئيسية لمحور التاريخ. |
| [setMajorUnitScale(int value)](#setMajorUnitScale-int-) | يوضح مقياس الوحدة الرئيسية لمحور التاريخ. |
| [getMinorUnitScale()](#getMinorUnitScale--) | يوضح مقياس الوحدة الرئيسية لمحور التاريخ. |
| [setMinorUnitScale(int value)](#setMinorUnitScale-int-) | يوضح مقياس الوحدة الرئيسية لمحور التاريخ. |
| [getBaseUnitScale()](#getBaseUnitScale--) | يحدد أصغر وحدة زمنية ممثلة على محور التاريخ. |
| [setBaseUnitScale(int value)](#setBaseUnitScale-int-) | يحدد أصغر وحدة زمنية ممثلة على محور التاريخ. |
| [getMinorGridLinesFormat()](#getMinorGridLinesFormat--) | يوضح تنسيق خطوط الشبكة الفرعية على محور المخطط. |
| [getMajorGridLinesFormat()](#getMajorGridLinesFormat--) | يوضح تنسيق خطوط الشبكة الرئيسية على محور المخطط. |
| [getShowMinorGridLines()](#getShowMinorGridLines--) | لإخفاء خط الشبكة الفرعي اضبط MinorGridLinesFormat.Line.FillFormat.FillType إلى FillType.NoFill. |
| [getShowMajorGridLines()](#getShowMajorGridLines--) | لإخفاء خط الشبكة الرئيسي اضبط MajorGridLinesFormat.Line.FillFormat.FillType إلى FillType.NoFill. |
| [getFormat()](#getFormat--) | يوضح تنسيق المحور. |
| [getTextFormat()](#getTextFormat--) | يوضح تنسيق النص. |
| [getTitle()](#getTitle--) | يحصل على عنوان المحور. |
| [getCrossType()](#getCrossType--) | يوضح نوع تقاطع (CrossType) على المحور المحدد حيث يعبر المحور الآخر. |
| [setCrossType(int value)](#setCrossType-int-) | يوضح نوع تقاطع (CrossType) على المحور المحدد حيث يعبر المحور الآخر. |
| [getPosition()](#getPosition--) | يوضح موضع المحور. |
| [setPosition(int value)](#setPosition-int-) | يوضح موضع المحور. |
| [hasTitle()](#hasTitle--) | يحدد ما إذا كان للمحور عنوان مرئي. |
| [setTitle(boolean value)](#setTitle-boolean-) | يحدد ما إذا كان للمحور عنوان مرئي. |
| [getNumberFormat()](#getNumberFormat--) | يوضح سلسلة التنسيق لتسميات المحور. |
| [setNumberFormat(String value)](#setNumberFormat-java.lang.String-) | يوضح سلسلة التنسيق لتسميات المحور. |
| [isNumberFormatLinkedToSource()](#isNumberFormatLinkedToSource--) | يحدد ما إذا كان التنسيق مرتبطًا ببيانات المصدر. |
| [setNumberFormatLinkedToSource(boolean value)](#setNumberFormatLinkedToSource-boolean-) | يحدد ما إذا كان التنسيق مرتبطًا ببيانات المصدر. |
| [getTickLabelRotationAngle()](#getTickLabelRotationAngle--) | يوضح زاوية دوران تسميات العلامات. |
| [setTickLabelRotationAngle(float value)](#setTickLabelRotationAngle-float-) | يوضح زاوية دوران تسميات العلامات. |
| [getTickLabelSpacing()](#getTickLabelSpacing--) | يحدد عدد تسميات العلامات التي تُتخطى بين كل تسمية مرسومة. |
| [setTickLabelSpacing(long value)](#setTickLabelSpacing-long-) | يحدد عدد تسميات العلامات التي تُتخطى بين كل تسمية مرسومة. |
| [isAutomaticTickLabelSpacing()](#isAutomaticTickLabelSpacing--) | يحدد قيمة التباعد التلقائي لتسميات العلامات. |
| [setAutomaticTickLabelSpacing(boolean value)](#setAutomaticTickLabelSpacing-boolean-) | يحدد قيمة التباعد التلقائي لتسميات العلامات. |
| [getTickMarksSpacing()](#getTickMarksSpacing--) | يحدد عدد علامات الفاصل التي يجب تخطيها قبل رسم العلامة التالية. |
| [setTickMarksSpacing(long value)](#setTickMarksSpacing-long-) | يحدد عدد علامات الفاصل التي يجب تخطيها قبل رسم العلامة التالية. |
| [isAutomaticTickMarksSpacing()](#isAutomaticTickMarksSpacing--) | يحدد قيمة التباعد التلقائي لعلامات الفواصل. |
| [setAutomaticTickMarksSpacing(boolean value)](#setAutomaticTickMarksSpacing-boolean-) | يحدد قيمة التباعد التلقائي لعلامات الفواصل. |
| [getLabelOffset()](#getLabelOffset--) | يحدد مسافة التسميات من المحور. |
| [setLabelOffset(int value)](#setLabelOffset-int-) | يحدد مسافة التسميات من المحور. |
| [getAggregationType()](#getAggregationType--) | يوضح نوع التجميع لمحور الفئة (تجميع). |
| [setAggregationType(int value)](#setAggregationType-int-) | يوضح نوع التجميع لمحور الفئة (تجميع). |
| [getBinWidth()](#getBinWidth--) | يحدد عرض الحاوية عندما تكون قيمة خاصية AggregationType مضبوطة على AxisAggregationType.ByBinWidth. |
| [setBinWidth(double value)](#setBinWidth-double-) | يحدد عرض الحاوية عندما تكون قيمة خاصية AggregationType مضبوطة على AxisAggregationType.ByBinWidth. |
| [getNumberOfBins()](#getNumberOfBins--) | يحدد عدد الحاويات عندما تكون قيمة خاصية AggregationType مضبوطة على AxisAggregationType.ByNumberOfBins. |
| [setNumberOfBins(long value)](#setNumberOfBins-long-) | يحدد عدد الحاويات عندما تكون قيمة خاصية AggregationType مضبوطة على AxisAggregationType.ByNumberOfBins. |
| [isOverflowBin()](#isOverflowBin--) | يحدد ما إذا تم تطبيق حاوية الفائض. |
| [setOverflowBin(boolean value)](#setOverflowBin-boolean-) | يحدد ما إذا تم تطبيق حاوية الفائض. |
| [isAutomaticOverflowBin()](#isAutomaticOverflowBin--) | يحدد قيمة حاوية الفائض التلقائية. |
| [setAutomaticOverflowBin(boolean value)](#setAutomaticOverflowBin-boolean-) | يحدد قيمة حاوية الفائض التلقائية. |
| [getOverflowBin()](#getOverflowBin--) | يحدد قيمة مخصصة لحاوية الفائض. |
| [setOverflowBin(double value)](#setOverflowBin-double-) | يحدد قيمة مخصصة لحاوية الفائض. |
| [isUnderflowBin()](#isUnderflowBin--) | يحدد ما إذا تم تطبيق حاوية النقص. |
| [setUnderflowBin(boolean value)](#setUnderflowBin-boolean-) | يحدد ما إذا تم تطبيق حاوية النقص. |
| [isAutomaticUnderflowBin()](#isAutomaticUnderflowBin--) | يحدد قيمة حاوية النقص التلقائية. |
| [setAutomaticUnderflowBin(boolean value)](#setAutomaticUnderflowBin-boolean-) | يحدد قيمة حاوية النقص التلقائية. |
| [getUnderflowBin()](#getUnderflowBin--) | يحدد قيمة مخصصة لحاوية النقص. |
| [setUnderflowBin(double value)](#setUnderflowBin-double-) | يحدد قيمة مخصصة لحاوية النقص. |
| [getSlide()](#getSlide--) | إرجاع الشريحة الأب لتنسيق التعبئة (FillFormat). |
| [getPresentation()](#getPresentation--) | إرجاع العرض التقديمي الأب لتنسيق التعبئة (FillFormat). |

### getChart() {#getChart--}
```
public final IChart getChart()
```

إرجاع المخطط الأب. للقراءة فقط [IChart](../../com.aspose.slides/ichart).

**الإرجاع:**  
[IChart](../../com.aspose.slides/ichart)

### getAxisBetweenCategories() {#getAxisBetweenCategories--}
```
public final boolean getAxisBetweenCategories()
```

يظهر ما إذا كان محور القيم يتقاطع مع محور الفئة بين الفئات. تنطبق هذه الخاصية فقط على محاور الفئة، ولا تنطبق على المخططات ثلاثية الأبعاد. قابل للقراءة والكتابة من نوع boolean.

**الإرجاع:**  
boolean

### setAxisBetweenCategories(boolean value) {#setAxisBetweenCategories-boolean-}
```
public final void setAxisBetweenCategories(boolean value)
```

يظهر ما إذا كان محور القيم يتقاطع مع محور الفئة بين الفئات. تنطبق هذه الخاصية فقط على محاور الفئة، ولا تنطبق على المخططات ثلاثية الأبعاد. قابل للقراءة والكتابة من نوع boolean.

**المعلمات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getCategoryAxisType() {#getCategoryAxisType--}
```
public final int getCategoryAxisType()
```

يحدد نوع محور الفئة. قابل للقراءة والكتابة [CategoryAxisType](../../com.aspose.slides/categoryaxistype).

**الإرجاع:**  
int

### setCategoryAxisType(int value) {#setCategoryAxisType-int-}
```
public final void setCategoryAxisType(int value)
```

يحدد نوع محور الفئة. قابل للقراءة والكتابة [CategoryAxisType](../../com.aspose.slides/categoryaxistype).

**المعلمات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### setCategoryAxisTypeAutomatically() {#setCategoryAxisTypeAutomatically--}
```
public final void setCategoryAxisTypeAutomatically()
```

يضبط خاصية IAxis.CategoryAxisType بقيمة يتم تحديدها تلقائيًا بناءً على بيانات المحور.

### getCrossAt() {#getCrossAt--}
```
public final float getCrossAt()
```

يظهر النقطة على المحور حيث يتقاطع المحور العمودي معه. قابل للقراءة والكتابة من نوع float.

**الإرجاع:**  
float

### setCrossAt(float value) {#setCrossAt-float-}
```
public final void setCrossAt(float value)
```

يظهر النقطة على المحور حيث يتقاطع المحور العمودي معه. قابل للقراءة والكتابة من نوع float.

**المعلمات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getDisplayUnit() {#getDisplayUnit--}
```
public final int getDisplayUnit()
```

يحدد قيمة مقياس وحدات العرض لمحور القيم. قابل للقراءة والكتابة [DisplayUnitType](../../com.aspose.slides/displayunittype).

**الإرجاع:**  
int

### setDisplayUnit(int value) {#setDisplayUnit-int-}
```
public final void setDisplayUnit(int value)
```

يحدد قيمة مقياس وحدات العرض لمحور القيم. قابل للقراءة والكتابة [DisplayUnitType](../../com.aspose.slides/displayunittype).

**المعلمات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getActualMaxValue() {#getActualMaxValue--}
```
public final double getActualMaxValue()
```

يحدد القيمة القصوى الفعلية على المحور. استدعِ الدالة IChart.ValidateChartLayout() مسبقًا للحصول على القيمة الفعلية.

**الإرجاع:**  
double

### getActualMinValue() {#getActualMinValue--}
```
public final double getActualMinValue()
```

يحدد القيمة الدنيا الفعلية على المحور. استدعِ الدالة IChart.ValidateChartLayout() مسبقًا للحصول على القيمة الفعلية.

**الإرجاع:**  
double

### getActualMajorUnit() {#getActualMajorUnit--}
```
public final double getActualMajorUnit()
```

يحدد الوحدة الرئيسية الفعلية للمحور. استدعِ الدالة IChart.ValidateChartLayout() مسبقًا للحصول على القيمة الفعلية.

**الإرجاع:**  
double

### getActualMinorUnit() {#getActualMinorUnit--}
```
public final double getActualMinorUnit()
```

يحدد الوحدة الفرعية الفعلية للمحور. استدعِ الدالة IChart.ValidateChartLayout() مسبقًا للحصول على القيمة الفعلية.

**الإرجاع:**  
double

### getActualMajorUnitScale() {#getActualMajorUnitScale--}
```
public final int getActualMajorUnitScale()
```

يحدد مقياس الوحدة الرئيسية الفعلية للمحور. استدعِ الدالة IChart.ValidateChartLayout() مسبقًا للحصول على القيمة الفعلية.

**الإرجاع:**  
int

### getActualMinorUnitScale() {#getActualMinorUnitScale--}
```
public final int getActualMinorUnitScale()
```

يحدد مقياس الوحدة الفرعية الفعلية للمحور. استدعِ الدالة IChart.ValidateChartLayout() مسبقًا للحصول على القيمة الفعلية.

**الإرجاع:**  
int

### isAutomaticMaxValue() {#isAutomaticMaxValue--}
```
public final boolean isAutomaticMaxValue()
```

يحدد ما إذا كان يتم تعيين القيمة القصوى تلقائيًا. قابل للقراءة والكتابة من نوع boolean.

**الإرجاع:**  
boolean

### setAutomaticMaxValue(boolean value) {#setAutomaticMaxValue-boolean-}
```
public final void setAutomaticMaxValue(boolean value)
```

يحدد ما إذا كان يتم تعيين القيمة القصوى تلقائيًا. قابل للقراءة والكتابة من نوع boolean.

**المعلمات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getMaxValue() {#getMaxValue--}
```
public final double getMaxValue()
```

يوضح القيمة القصوى على محور القيم. قابل للقراءة والكتابة من نوع double.

**الإرجاع:**  
double

### setMaxValue(double value) {#setMaxValue-double-}
```
public final void setMaxValue(double value)
```

يوضح القيمة القصوى على محور القيم. قابل للقراءة والكتابة من نوع double.

**المعلمات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | double |  |

### getMinorUnit() {#getMinorUnit--}
```
public final double getMinorUnit()
```

يظهر الوحدات الفرعية لتاريخ أو محور القيم. قابل للقراءة والكتابة من نوع double.

**الإرجاع:**  
double

### setMinorUnit(double value) {#setMinorUnit-double-}
```
public final void setMinorUnit(double value)
```

يظهر الوحدات الفرعية لتاريخ أو محور القيم. قابل للقراءة والكتابة من نوع double.

**المعلمات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | double |  |

### isAutomaticMinorUnit() {#isAutomaticMinorUnit--}
```
public final boolean isAutomaticMinorUnit()
```
Indicates whether the minor unit of the axis is automatically assigned. قراءة/كتابة boolean.

**الإرجاع:**
boolean
### setAutomaticMinorUnit(boolean value) {#setAutomaticMinorUnit-boolean-}
```
public final void setAutomaticMinorUnit(boolean value)
```


Indicates whether the minor unit of the axis is automatically assigned. قراءة/كتابة boolean.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getMajorUnit() {#getMajorUnit--}
```
public final double getMajorUnit()
```


Represents the major units for the date or value axis. قراءة/كتابة double.

**الإرجاع:**
double
### setMajorUnit(double value) {#setMajorUnit-double-}
```
public final void setMajorUnit(double value)
```


Represents the major units for the date or value axis. قراءة/كتابة double.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | double |  |

### isAutomaticMajorUnit() {#isAutomaticMajorUnit--}
```
public final boolean isAutomaticMajorUnit()
```


Indicates whether the major unit of the axis is automatically assigned. قراءة/كتابة boolean.

**الإرجاع:**
boolean
### setAutomaticMajorUnit(boolean value) {#setAutomaticMajorUnit-boolean-}
```
public final void setAutomaticMajorUnit(boolean value)
```


Indicates whether the major unit of the axis is automatically assigned. قراءة/كتابة boolean.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticMinValue() {#isAutomaticMinValue--}
```
public final boolean isAutomaticMinValue()
```


Indicates whether the min value is automatically assigned. قراءة/كتابة boolean.

**الإرجاع:**
boolean
### setAutomaticMinValue(boolean value) {#setAutomaticMinValue-boolean-}
```
public final void setAutomaticMinValue(boolean value)
```


Indicates whether the min value is automatically assigned. قراءة/كتابة boolean.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getMinValue() {#getMinValue--}
```
public final double getMinValue()
```


Represents the minimum value on the value axis. قراءة/كتابة double.

**الإرجاع:**
double
### setMinValue(double value) {#setMinValue-double-}
```
public final void setMinValue(double value)
```


Represents the minimum value on the value axis. قراءة/كتابة double.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | double |  |

### isLogarithmic() {#isLogarithmic--}
```
public final boolean isLogarithmic()
```


Represents if the value axis scale type is logarithmic or not. قراءة/كتابة boolean.

**الإرجاع:**
boolean
### setLogarithmic(boolean value) {#setLogarithmic-boolean-}
```
public final void setLogarithmic(boolean value)
```


Represents if the value axis scale type is logarithmic or not. قراءة/كتابة boolean.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getLogBase() {#getLogBase--}
```
public final double getLogBase()
```


Represents the logarithmic base. Default value is 10. قراءة/كتابة double.

**الإرجاع:**
double
### setLogBase(double value) {#setLogBase-double-}
```
public final void setLogBase(double value)
```


Represents the logarithmic base. Default value is 10. قراءة/كتابة double.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | double |  |

### isPlotOrderReversed() {#isPlotOrderReversed--}
```
public final boolean isPlotOrderReversed()
```


Represents if MS PowerPoint plots data points from last to first. قراءة/كتابة boolean.

**الإرجاع:**
boolean
### setPlotOrderReversed(boolean value) {#setPlotOrderReversed-boolean-}
```
public final void setPlotOrderReversed(boolean value)
```


Represents if MS PowerPoint plots data points from last to first. قراءة/كتابة boolean.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### isVisible() {#isVisible--}
```
public final boolean isVisible()
```


Represents if the axis is visible. قراءة/كتابة boolean.

**الإرجاع:**
boolean
### setVisible(boolean value) {#setVisible-boolean-}
```
public final void setVisible(boolean value)
```


Represents if the axis is visible. قراءة/كتابة boolean.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getMajorTickMark() {#getMajorTickMark--}
```
public final int getMajorTickMark()
```


Represents the type of major tick mark for the specified axis. قراءة/كتابة [TickMarkType](../../com.aspose.slides/tickmarktype).

**الإرجاع:**
int
### setMajorTickMark(int value) {#setMajorTickMark-int-}
```
public final void setMajorTickMark(int value)
```


Represents the type of major tick mark for the specified axis. قراءة/كتابة [TickMarkType](../../com.aspose.slides/tickmarktype).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getMinorTickMark() {#getMinorTickMark--}
```
public final int getMinorTickMark()
```


Represents the type of minor tick mark for the specified axis. قراءة/كتابة [TickMarkType](../../com.aspose.slides/tickmarktype).

**الإرجاع:**
int
### setMinorTickMark(int value) {#setMinorTickMark-int-}
```
public final void setMinorTickMark(int value)
```


Represents the type of minor tick mark for the specified axis. قراءة/كتابة [TickMarkType](../../com.aspose.slides/tickmarktype).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getTickLabelPosition() {#getTickLabelPosition--}
```
public final int getTickLabelPosition()
```


Represents the position of tick-mark labels on the specified axis. قراءة/كتابة [TickLabelPositionType](../../com.aspose.slides/ticklabelpositiontype).

**الإرجاع:**
int
### setTickLabelPosition(int value) {#setTickLabelPosition-int-}
```
public final void setTickLabelPosition(int value)
```


Represents the position of tick-mark labels on the specified axis. قراءة/كتابة [TickLabelPositionType](../../com.aspose.slides/ticklabelpositiontype).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getMajorUnitScale() {#getMajorUnitScale--}
```
public final int getMajorUnitScale()
```


Represents the major unit scale for the date axis. قراءة/كتابة [TimeUnitType](../../com.aspose.slides/timeunittype).

**الإرجاع:**
int
### setMajorUnitScale(int value) {#setMajorUnitScale-int-}
```
public final void setMajorUnitScale(int value)
```


Represents the major unit scale for the date axis. قراءة/كتابة [TimeUnitType](../../com.aspose.slides/timeunittype).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getMinorUnitScale() {#getMinorUnitScale--}
```
public final int getMinorUnitScale()
```


Represents the major unit scale for the date axis. قراءة/كتابة [TimeUnitType](../../com.aspose.slides/timeunittype).

**الإرجاع:**
int
### setMinorUnitScale(int value) {#setMinorUnitScale-int-}
```
public final void setMinorUnitScale(int value)
```


Represents the major unit scale for the date axis. قراءة/كتابة [TimeUnitType](../../com.aspose.slides/timeunittype).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getBaseUnitScale() {#getBaseUnitScale--}
```
public final int getBaseUnitScale()
```


Specifies the smallest time unit that is represented on the date axis. قراءة/كتابة [TimeUnitType](../../com.aspose.slides/timeunittype).

**الإرجاع:**
int
### setBaseUnitScale(int value) {#setBaseUnitScale-int-}
```
public final void setBaseUnitScale(int value)
```


Specifies the smallest time unit that is represented on the date axis. قراءة/كتابة [TimeUnitType](../../com.aspose.slides/timeunittype).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getMinorGridLinesFormat() {#getMinorGridLinesFormat--}
```
public final IChartLinesFormat getMinorGridLinesFormat()
```


Represents minor gridlines format on a chart axis. قراءة فقط [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

**الإرجاع:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)
### getMajorGridLinesFormat() {#getMajorGridLinesFormat--}
```
public final IChartLinesFormat getMajorGridLinesFormat()
```


Represents major gridlines format on a chart axis. قراءة فقط [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

**الإرجاع:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)
### getShowMinorGridLines() {#getShowMinorGridLines--}
```
public final boolean getShowMinorGridLines()
```


To hide minor gridline set MinorGridLinesFormat.Line.FillFormat.FillType to FillType.NoFill. قراءة فقط boolean.

**الإرجاع:**
boolean
### getShowMajorGridLines() {#getShowMajorGridLines--}
```
public final boolean getShowMajorGridLines()
```


To hide major gridline set MajorGridLinesFormat.Line.FillFormat.FillType to FillType.NoFill. قراءة فقط boolean.

**الإرجاع:**
boolean
### getFormat() {#getFormat--}
```
public final IAxisFormat getFormat()
```


Represents format of axis. قراءة فقط [IAxisFormat](../../com.aspose.slides/iaxisformat).

**الإرجاع:**
[IAxisFormat](../../com.aspose.slides/iaxisformat)
### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```


Represents format of text. قراءة فقط [IChartTextFormat](../../com.aspose.slides/icharttextformat).

**الإرجاع:**
[IChartTextFormat](../../com.aspose.slides/icharttextformat)
### getTitle() {#getTitle--}
```
public final IChartTitle getTitle()
```


Gets the axis' title. قراءة فقط [IChartTitle](../../com.aspose.slides/icharttitle).

**الإرجاع:**
[IChartTitle](../../com.aspose.slides/icharttitle)
### getCrossType() {#getCrossType--}
```
public final int getCrossType()
```


Represents the CrossType on the specified axis where the other axis crosses. قراءة/كتابة [CrossesType](../../com.aspose.slides/crossestype).

**الإرجاع:**
int
### setCrossType(int value) {#setCrossType-int-}
```
public final void setCrossType(int value)
```


Represents the CrossType on the specified axis where the other axis crosses. قراءة/كتابة [CrossesType](../../com.aspose.slides/crossestype).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getPosition() {#getPosition--}
```
public final int getPosition()
```


Represents position of axis. قراءة/كتابة [AxisPositionType](../../com.aspose.slides/axispositiontype).

**الإرجاع:**
int
### setPosition(int value) {#setPosition-int-}
```
public final void setPosition(int value)
```


Represents position of axis. قراءة/كتابة [AxisPositionType](../../com.aspose.slides/axispositiontype).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### hasTitle() {#hasTitle--}
```
public final boolean hasTitle()
```


Determines whether a axis has a visible title. قراءة/كتابة boolean.

**الإرجاع:**
boolean
### setTitle(boolean value) {#setTitle-boolean-}
```
public final void setTitle(boolean value)
```


Determines whether a axis has a visible title. قراءة/كتابة boolean.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getNumberFormat() {#getNumberFormat--}
```
public final String getNumberFormat()
```


Represents the format string for the Axis Labels. قراءة/كتابة String.

**الإرجاع:**
java.lang.String
### setNumberFormat(String value) {#setNumberFormat-java.lang.String-}
```
public final void setNumberFormat(String value)
```


Represents the format string for the Axis Labels. قراءة/كتابة String.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### isNumberFormatLinkedToSource() {#isNumberFormatLinkedToSource--}
```
public final boolean isNumberFormatLinkedToSource()
```


Indicates whether the format is linked source data. قراءة/كتابة boolean.

**الإرجاع:**
boolean
### setNumberFormatLinkedToSource(boolean value) {#setNumberFormatLinkedToSource-boolean-}
```
public final void setNumberFormatLinkedToSource(boolean value)
```


Indicates whether the format is linked source data. قراءة/كتابة boolean.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getTickLabelRotationAngle() {#getTickLabelRotationAngle--}
```
public final float getTickLabelRotationAngle()
```


Represents the rotation angle of tick labels. قراءة/كتابة float.

**الإرجاع:**
float
### setTickLabelRotationAngle(float value) {#setTickLabelRotationAngle-float-}
```
public final void setTickLabelRotationAngle(float value)
```


Represents the rotation angle of tick labels. قراءة/كتابة float.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getTickLabelSpacing() {#getTickLabelSpacing--}
```
public final long getTickLabelSpacing()
```


Specifies how many tick labels to skip between label that is drawn. Applied to category or series axis. قراءة/كتابة long.

**الإرجاع:**
long
### setTickLabelSpacing(long value) {#setTickLabelSpacing-long-}
```
public final void setTickLabelSpacing(long value)
```


Specifies how many tick labels to skip between label that is drawn. Applied to category or series axis. قراءة/كتابة long.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | long |  |

### isAutomaticTickLabelSpacing() {#isAutomaticTickLabelSpacing--}
```
public final boolean isAutomaticTickLabelSpacing()
```


Specifies automatic tick label spacing value. If false: use TickLabelSpacing property. قراءة/كتابة boolean.

**الإرجاع:**
boolean
### setAutomaticTickLabelSpacing(boolean value) {#setAutomaticTickLabelSpacing-boolean-}
```
public final void setAutomaticTickLabelSpacing(boolean value)
```


Specifies automatic tick label spacing value. If false: use TickLabelSpacing property. قراءة/كتابة boolean.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getTickMarksSpacing() {#getTickMarksSpacing--}
```
public final long getTickMarksSpacing()
```


Specifies how many tick marks shall be skipped before the next one shall be drawn. Applied to category or series axis. قراءة/كتابة int.

**الإرجاع:**
long
### setTickMarksSpacing(long value) {#setTickMarksSpacing-long-}
```
public final void setTickMarksSpacing(long value)
```


Specifies how many tick marks shall be skipped before the next one shall be drawn. Applied to category or series axis. قراءة/كتابة int.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | long |  |

### isAutomaticTickMarksSpacing() {#isAutomaticTickMarksSpacing--}
```
public final boolean isAutomaticTickMarksSpacing()
```


Specifies automatic tick marks spacing value. If false: use TickMarksSpacing property. قراءة/كتابة boolean.

**الإرجاع:**
boolean
### setAutomaticTickMarksSpacing(boolean value) {#setAutomaticTickMarksSpacing-boolean-}
```
public final void setAutomaticTickMarksSpacing(boolean value)
```


Specifies automatic tick marks spacing value. If false: use TickMarksSpacing property. قراءة/كتابة boolean.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getLabelOffset() {#getLabelOffset--}
```
public final int getLabelOffset()
```


Specifies the distance of labels from the axis. Applied to category or date axis. Value must be between 0% and 1000%. قراءة/كتابة int.

**الإرجاع:**
int
### setLabelOffset(int value) {#setLabelOffset-int-}
```
public final void setLabelOffset(int value)
```


Specifies the distance of labels from the axis. Applied to category or date axis. Value must be between 0% and 1000%. قراءة/كتابة int.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |
### getAggregationType() {#getAggregationType--}
```
public final int getAggregationType()
```

يمثل نوع التجميع لمحور الفئات (التجميع إلى سلات). يُطبق على الفئة. يُستخدم مع سلاسل Histogram أو HistogramPareto فقط.

**Returns:**
int
### setAggregationType(int value) {#setAggregationType-int-}
```
public final void setAggregationType(int value)
```

يمثل نوع التجميع لمحور الفئات (التجميع إلى سلات). يُطبق على الفئة. يُستخدم مع سلاسل Histogram أو HistogramPareto فقط.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getBinWidth() {#getBinWidth--}
```
public final double getBinWidth()
```

يحدد عرض السلة عندما تكون قيمة خاصية AggregationType معينة إلى AxisAggregationType.ByBinWidth. يُطبق على محاور الفئات. يُستخدم مع سلاسل Histogram أو HistogramPareto فقط.

**Returns:**
double
### setBinWidth(double value) {#setBinWidth-double-}
```
public final void setBinWidth(double value)
```

يحدد عرض السلة عندما تكون قيمة خاصية AggregationType معينة إلى AxisAggregationType.ByBinWidth. يُطبق على محاور الفئات. يُستخدم مع سلاسل Histogram أو HistogramPareto فقط.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getNumberOfBins() {#getNumberOfBins--}
```
public final long getNumberOfBins()
```

يحدد عدد السلات عندما تكون قيمة خاصية AggregationType معينة إلى AxisAggregationType.ByNumberOfBins. يُطبق على محاور الفئات. يُستخدم مع سلاسل Histogram أو HistogramPareto فقط.

**Returns:**
long
### setNumberOfBins(long value) {#setNumberOfBins-long-}
```
public final void setNumberOfBins(long value)
```

يحدد عدد السلات عندما تكون قيمة خاصية AggregationType معينة إلى AxisAggregationType.ByNumberOfBins. يُطبق على محاور الفئات. يُستخدم مع سلاسل Histogram أو HistogramPareto فقط.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

### isOverflowBin() {#isOverflowBin--}
```
public final boolean isOverflowBin()
```

يحدد ما إذا تم تطبيق سلة الفائض. استخدم IsAutomaticOverflowBin و OverflowBin لضبط قيمة سلة الفائض.

**Returns:**
boolean
### setOverflowBin(boolean value) {#setOverflowBin-boolean-}
```
public final void setOverflowBin(boolean value)
```

يحدد ما إذا تم تطبيق سلة الفائض. استخدم IsAutomaticOverflowBin و OverflowBin لضبط قيمة سلة الفائض.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticOverflowBin() {#isAutomaticOverflowBin--}
```
public final boolean isAutomaticOverflowBin()
```

يحدد قيمة سلة الفائض التلقائية. إذا كان false: استخدم خاصية OverflowBin.

**Returns:**
boolean
### setAutomaticOverflowBin(boolean value) {#setAutomaticOverflowBin-boolean-}
```
public final void setAutomaticOverflowBin(boolean value)
```

يحدد قيمة سلة الفائض التلقائية. إذا كان false: استخدم خاصية OverflowBin.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getOverflowBin() {#getOverflowBin--}
```
public final double getOverflowBin()
```

يحدد قيمة مخصصة لسلة الفائض. يُطبق عندما تكون خاصية IsAutomaticOverflowBin معينة إلى false وتكون خاصية IsOverflowBin تساوي true.

**Returns:**
double
### setOverflowBin(double value) {#setOverflowBin-double-}
```
public final void setOverflowBin(double value)
```

يحدد قيمة مخصصة لسلة الفائض. يُطبق عندما تكون خاصية IsAutomaticOverflowBin معينة إلى false وتكون خاصية IsOverflowBin تساوي true.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### isUnderflowBin() {#isUnderflowBin--}
```
public final boolean isUnderflowBin()
```

يحدد ما إذا تم تطبيق سلة النقص. استخدم IsAutomaticUnderflowBin و UnderflowBin لضبط قيمة سلة النقص.

**Returns:**
boolean
### setUnderflowBin(boolean value) {#setUnderflowBin-boolean-}
```
public final void setUnderflowBin(boolean value)
```

يحدد ما إذا تم تطبيق سلة النقص. استخدم IsAutomaticUnderflowBin و UnderflowBin لضبط قيمة سلة النقص.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticUnderflowBin() {#isAutomaticUnderflowBin--}
```
public final boolean isAutomaticUnderflowBin()
```

يحدد قيمة سلة النقص التلقائية. إذا كان false: استخدم خاصية UnderflowBin.

**Returns:**
boolean
### setAutomaticUnderflowBin(boolean value) {#setAutomaticUnderflowBin-boolean-}
```
public final void setAutomaticUnderflowBin(boolean value)
```

يحدد قيمة سلة النقص التلقائية. إذا كان false: استخدم خاصية UnderflowBin.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getUnderflowBin() {#getUnderflowBin--}
```
public final double getUnderflowBin()
```

يحدد قيمة مخصصة لسلة النقص. يُطبق عندما تكون خاصية IsAutomaticUnderflowBin معينة إلى false وتكون خاصية IsUnderflowBin تساوي true.

**Returns:**
double
### setUnderflowBin(double value) {#setUnderflowBin-double-}
```
public final void setUnderflowBin(double value)
```

يحدد قيمة مخصصة لسلة النقص. يُطبق عندما تكون خاصية IsAutomaticUnderflowBin معينة إلى false وتكون خاصية IsUnderflowBin تساوي true.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

يرجع الشريحة الأصلية لـ FillFormat. للقراءة فقط [BaseSlide](../../com.aspose.slides/baseslide).

**Returns:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

يرجع العرض التقديمي الأصلية لـ FillFormat. للقراءة فقط [IPresentation](../../com.aspose.slides/ipresentation).

**Returns:**
[IPresentation](../../com.aspose.slides/ipresentation)