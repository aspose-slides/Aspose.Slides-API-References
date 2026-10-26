---
title: Axis
second_title: Aspose.Slides لنظام Android عبر مرجع API لجافا
description: يغلف الكائن الذي يمثل محور المخطط.
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
| [getChart()](#getChart--) | يعيد المخطط الأب. |
| [getAxisBetweenCategories()](#getAxisBetweenCategories--) | يمثل ما إذا كان محور القيم يعترض محور الفئة بين الفئات. |
| [setAxisBetweenCategories(boolean value)](#setAxisBetweenCategories-boolean-) | يمثل ما إذا كان محور القيم يعترض محور الفئة بين الفئات. |
| [getCategoryAxisType()](#getCategoryAxisType--) | يحدد نوع محور الفئة. |
| [setCategoryAxisType(int value)](#setCategoryAxisType-int-) | يحدد نوع محور الفئة. |
| [setCategoryAxisTypeAutomatically()](#setCategoryAxisTypeAutomatically--) | يضبط خاصية IAxis.CategoryAxisType بقيمة يتم تحديدها تلقائيًا بناءً على بيانات المحور. |
| [getCrossAt()](#getCrossAt--) | يمثل النقطة على المحور التي يتقاطع فيها المحور المتعامد معه. |
| [setCrossAt(float value)](#setCrossAt-float-) | يمثل النقطة على المحور التي يتقاطع فيها المحور المتعامد معه. |
| [getDisplayUnit()](#getDisplayUnit--) | يحدد قيمة التحجيم لوحدات العرض لمحور القيم. |
| [setDisplayUnit(int value)](#setDisplayUnit-int-) | يحدد قيمة التحجيم لوحدات العرض لمحور القيم. |
| [getActualMaxValue()](#getActualMaxValue--) | يحدد القيمة القصوى الفعلية على المحور. |
| [getActualMinValue()](#getActualMinValue--) | يحدد القيمة الدنيا الفعلية على المحور. |
| [getActualMajorUnit()](#getActualMajorUnit--) | يحدد الوحدة الرئيسية الفعلية للمحور. |
| [getActualMinorUnit()](#getActualMinorUnit--) | يحدد الوحدة الفرعية الفعلية للمحور. |
| [getActualMajorUnitScale()](#getActualMajorUnitScale--) | يحدد مقياس الوحدة الرئيسية الفعلية للمحور. |
| [getActualMinorUnitScale()](#getActualMinorUnitScale--) | يحدد مقياس الوحدة الفرعية الفعلية للمحور. |
| [isAutomaticMaxValue()](#isAutomaticMaxValue--) | يشير إلى ما إذا كانت القيمة العظمى تُحدد تلقائيًا. |
| [setAutomaticMaxValue(boolean value)](#setAutomaticMaxValue-boolean-) | يشير إلى ما إذا كانت القيمة العظمى تُحدد تلقائيًا. |
| [getMaxValue()](#getMaxValue--) | يمثل القيمة العظمى على محور القيم. |
| [setMaxValue(double value)](#setMaxValue-double-) | يمثل القيمة العظمى على محور القيم. |
| [getMinorUnit()](#getMinorUnit--) | يمثل الوحدات الفرعية لمحور التاريخ أو القيم. |
| [setMinorUnit(double value)](#setMinorUnit-double-) | يمثل الوحدات الفرعية لمحور التاريخ أو القيم. |
| [isAutomaticMinorUnit()](#isAutomaticMinorUnit--) | يشير إلى ما إذا كانت الوحدة الفرعية للمحور تُحدد تلقائيًا. |
| [setAutomaticMinorUnit(boolean value)](#setAutomaticMinorUnit-boolean-) | يشير إلى ما إذا كانت الوحدة الفرعية للمحور تُحدد تلقائيًا. |
| [getMajorUnit()](#getMajorUnit--) | يمثل الوحدات الرئيسية لمحور التاريخ أو القيم. |
| [setMajorUnit(double value)](#setMajorUnit-double-) | يمثل الوحدات الرئيسية لمحور التاريخ أو القيم. |
| [isAutomaticMajorUnit()](#isAutomaticMajorUnit--) | يشير إلى ما إذا كانت الوحدة الرئيسية للمحور تُحدد تلقائيًا. |
| [setAutomaticMajorUnit(boolean value)](#setAutomaticMajorUnit-boolean-) | يشير إلى ما إذا كانت الوحدة الرئيسية للمحور تُحدد تلقائيًا. |
| [isAutomaticMinValue()](#isAutomaticMinValue--) | يشير إلى ما إذا كانت القيمة الصغرى تُحدد تلقائيًا. |
| [setAutomaticMinValue(boolean value)](#setAutomaticMinValue-boolean-) | يشير إلى ما إذا كانت القيمة الصغرى تُحدد تلقائيًا. |
| [getMinValue()](#getMinValue--) | يمثل القيمة الصغرى على محور القيم. |
| [setMinValue(double value)](#setMinValue-double-) | يمثل القيمة الصغرى على محور القيم. |
| [isLogarithmic()](#isLogarithmic--) | يمثل ما إذا كان نوع مقياس محور القيم لوغاريتميًا أم لا. |
| [setLogarithmic(boolean value)](#setLogarithmic-boolean-) | يمثل ما إذا كان نوع مقياس محور القيم لوغاريتميًا أم لا. |
| [getLogBase()](#getLogBase--) | يمثل القاعدة اللوغاريتمية. |
| [setLogBase(double value)](#setLogBase-double-) | يمثل القاعدة اللوغاريتمية. |
| [isPlotOrderReversed()](#isPlotOrderReversed--) | يمثل ما إذا كان برنامج MS PowerPoint يرسم نقاط البيانات من الأخير إلى الأول. |
| [setPlotOrderReversed(boolean value)](#setPlotOrderReversed-boolean-) | يمثل ما إذا كان برنامج MS PowerPoint يرسم نقاط البيانات من الأخير إلى الأول. |
| [isVisible()](#isVisible--) | يمثل ما إذا كان المحور مرئيًا. |
| [setVisible(boolean value)](#setVisible-boolean-) | يمثل ما إذا كان المحور مرئيًا. |
| [getMajorTickMark()](#getMajorTickMark--) | يمثل نوع علامة التقسيم الرئيسية للمحور المحدد. |
| [setMajorTickMark(int value)](#setMajorTickMark-int-) | يمثل نوع علامة التقسيم الرئيسية للمحور المحدد. |
| [getMinorTickMark()](#getMinorTickMark--) | يمثل نوع علامة التقسيم الفرعية للمحور المحدد. |
| [setMinorTickMark(int value)](#setMinorTickMark-int-) | يمثل نوع علامة التقسيم الفرعية للمحور المحدد. |
| [getTickLabelPosition()](#getTickLabelPosition--) | يمثل موضع تسميات علامات التقسيم على المحور المحدد. |
| [setTickLabelPosition(int value)](#setTickLabelPosition-int-) | يمثل موضع تسميات علامات التقسيم على المحور المحدد. |
| [getMajorUnitScale()](#getMajorUnitScale--) | يمثل مقياس الوحدة الرئيسية لمحور التاريخ. |
| [setMajorUnitScale(int value)](#setMajorUnitScale-int-) | يمثل مقياس الوحدة الرئيسية لمحور التاريخ. |
| [getMinorUnitScale()](#getMinorUnitScale--) | يمثل مقياس الوحدة الرئيسية لمحور التاريخ. |
| [setMinorUnitScale(int value)](#setMinorUnitScale-int-) | يمثل مقياس الوحدة الرئيسية لمحور التاريخ. |
| [getBaseUnitScale()](#getBaseUnitScale--) | يحدد أصغر وحدة زمنية يتم تمثيلها على محور التاريخ. |
| [setBaseUnitScale(int value)](#setBaseUnitScale-int-) | يحدد أصغر وحدة زمنية يتم تمثيلها على محور التاريخ. |
| [getMinorGridLinesFormat()](#getMinorGridLinesFormat--) | يمثل تنسيق خطوط الشبكة الفرعية على محور المخطط. |
| [getMajorGridLinesFormat()](#getMajorGridLinesFormat--) | يمثل تنسيق خطوط الشبكة الرئيسية على محور المخطط. |
| [getShowMinorGridLines()](#getShowMinorGridLines--) | لإخفاء الخط الشبكي الفرعي اضبط MinorGridLinesFormat.Line.FillFormat.FillType إلى FillType.NoFill. |
| [getShowMajorGridLines()](#getShowMajorGridLines--) | لإخفاء الخط الشبكي الرئيسي اضبط MajorGridLinesFormat.Line.FillFormat.FillType إلى FillType.NoFill. |
| [getFormat()](#getFormat--) | يمثل تنسيق المحور. |
| [getTextFormat()](#getTextFormat--) | يمثل تنسيق النص. |
| [getTitle()](#getTitle--) | يحصل على عنوان المحور. |
| [getCrossType()](#getCrossType--) | يمثل نوع التقاطع (CrossType) على المحور المحدد حيث يعبر المحور الآخر. |
| [setCrossType(int value)](#setCrossType-int-) | يمثل نوع التقاطع (CrossType) على المحور المحدد حيث يعبر المحور الآخر. |
| [getPosition()](#getPosition--) | يمثل موقع المحور. |
| [setPosition(int value)](#setPosition-int-) | يمثل موقع المحور. |
| [hasTitle()](#hasTitle--) | يحدد ما إذا كان للمحور عنوان مرئي. |
| [setTitle(boolean value)](#setTitle-boolean-) | يحدد ما إذا كان للمحور عنوان مرئي. |
| [getNumberFormat()](#getNumberFormat--) | يمثل سلسلة تنسيق تسميات المحور. |
| [setNumberFormat(String value)](#setNumberFormat-java.lang.String-) | يمثل سلسلة تنسيق تسميات المحور. |
| [isNumberFormatLinkedToSource()](#isNumberFormatLinkedToSource--) | يشير إلى ما إذا كان التنسيق مرتبطًا ببيانات المصدر. |
| [setNumberFormatLinkedToSource(boolean value)](#setNumberFormatLinkedToSource-boolean-) | يشير إلى ما إذا كان التنسيق مرتبطًا ببيانات المصدر. |
| [getTickLabelRotationAngle()](#getTickLabelRotationAngle--) | يمثل زاوية دوران تسميات علامات التقسيم. |
| [setTickLabelRotationAngle(float value)](#setTickLabelRotationAngle-float-) | يمثل زاوية دوران تسميات علامات التقسيم. |
| [getTickLabelSpacing()](#getTickLabelSpacing--) | يحدد عدد تسميات العلامات التي يتم تخطيها بين كل تسمية مرسومة. |
| [setTickLabelSpacing(long value)](#setTickLabelSpacing-long-) | يحدد عدد تسميات العلامات التي يتم تخطيها بين كل تسمية مرسومة. |
| [isAutomaticTickLabelSpacing()](#isAutomaticTickLabelSpacing--) | يحدد قيمة التباعد التلقائي لتسميات العلامات. |
| [setAutomaticTickLabelSpacing(boolean value)](#setAutomaticTickLabelSpacing-boolean-) | يحدد قيمة التباعد التلقائي لتسميات العلامات. |
| [getTickMarksSpacing()](#getTickMarksSpacing--) | يحدد عدد علامات التقسيم التي يجب تخطيها قبل رسم العلامة التالية. |
| [setTickMarksSpacing(long value)](#setTickMarksSpacing-long-) | يحدد عدد علامات التقسيم التي يجب تخطيها قبل رسم العلامة التالية. |
| [isAutomaticTickMarksSpacing()](#isAutomaticTickMarksSpacing--) | يحدد قيمة التباعد التلقائي لعلامات التقسيم. |
| [setAutomaticTickMarksSpacing(boolean value)](#setAutomaticTickMarksSpacing-boolean-) | يحدد قيمة التباعد التلقائي لعلامات التقسيم. |
| [getLabelOffset()](#getLabelOffset--) | يحدد المسافة بين التسميات والمحور. |
| [setLabelOffset(int value)](#setLabelOffset-int-) | يحدد المسافة بين التسميات والمحور. |
| [getAggregationType()](#getAggregationType--) | يمثل نوع التجميع لمحور الفئة (التجزئة). |
| [setAggregationType(int value)](#setAggregationType-int-) | يمثل نوع التجميع لمحور الفئة (التجزئة). |
| [getBinWidth()](#getBinWidth--) | يحدد عرض الصندوق عندما تكون قيمة خاصية AggregationType مضبوطة على AxisAggregationType.ByBinWidth. |
| [setBinWidth(double value)](#setBinWidth-double-) | يحدد عرض الصندوق عندما تكون قيمة خاصية AggregationType مضبوطة على AxisAggregationType.ByBinWidth. |
| [getNumberOfBins()](#getNumberOfBins--) | يحدد عدد الصناديق عندما تكون قيمة خاصية AggregationType مضبوطة على AxisAggregationType.ByNumberOfBins. |
| [setNumberOfBins(long value)](#setNumberOfBins-long-) | يحدد عدد الصناديق عندما تكون قيمة خاصية AggregationType مضبوطة على AxisAggregationType.ByNumberOfBins. |
| [isOverflowBin()](#isOverflowBin--) | يمثل ما إذا تم تطبيق صندوق الفائض. |
| [setOverflowBin(boolean value)](#setOverflowBin-boolean-) | يمثل ما إذا تم تطبيق صندوق الفائض. |
| [isAutomaticOverflowBin()](#isAutomaticOverflowBin--) | يحدد قيمة صندوق الفائض التلقائي. |
| [setAutomaticOverflowBin(boolean value)](#setAutomaticOverflowBin-boolean-) | يحدد قيمة صندوق الفائض التلقائي. |
| [getOverflowBin()](#getOverflowBin--) | يحدد قيمة مخصصة لصندوق الفائض. |
| [setOverflowBin(double value)](#setOverflowBin-double-) | يحدد قيمة مخصصة لصندوق الفائض. |
| [isUnderflowBin()](#isUnderflowBin--) | يمثل ما إذا تم تطبيق صندوق النقص. |
| [setUnderflowBin(boolean value)](#setUnderflowBin-boolean-) | يمثل ما إذا تم تطبيق صندوق النقص. |
| [isAutomaticUnderflowBin()](#isAutomaticUnderflowBin--) | يحدد قيمة صندوق النقص التلقائي. |
| [setAutomaticUnderflowBin(boolean value)](#setAutomaticUnderflowBin-boolean-) | يحدد قيمة صندوق النقص التلقائي. |
| [getUnderflowBin()](#getUnderflowBin--) | يحدد قيمة مخصصة لصندوق النقص. |
| [setUnderflowBin(double value)](#setUnderflowBin-double-) | يحدد قيمة مخصصة لصندوق النقص. |
| [getSlide()](#getSlide--) | إرجاع الشريحة الأم لـ FillFormat. |
| [getPresentation()](#getPresentation--) | إرجاع العرض (presentation) الأم لـ FillFormat. |

### getChart() {#getChart--}
```
public final IChart getChart()
```

يعيد المخطط الأب. للقراءة فقط [IChart](../../com.aspose.slides/ichart).

**الإرجاع:**  
[IChart](../../com.aspose.slides/ichart)

### getAxisBetweenCategories() {#getAxisBetweenCategories--}
```
public final boolean getAxisBetweenCategories()
```

يمثل ما إذا كان محور القيم يعترض محور الفئة بين الفئات. تنطبق هذه الخاصية فقط على محاور الفئة، ولا تنطبق على المخططات ثلاثية الأبعاد. قراءة/كتابة boolean.

**الإرجاع:**  
boolean

### setAxisBetweenCategories(boolean value) {#setAxisBetweenCategories-boolean-}
```
public final void setAxisBetweenCategories(boolean value)
```

يمثل ما إذا كان محور القيم يعترض محور الفئة بين الفئات. تنطبق هذه الخاصية فقط على محاور الفئة، ولا تنطبق على المخططات ثلاثية الأبعاد. قراءة/كتابة boolean.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getCategoryAxisType() {#getCategoryAxisType--}
```
public final int getCategoryAxisType()
```

يحدد نوع محور الفئة. قراءة/كتابة [CategoryAxisType](../../com.aspose.slides/categoryaxistype).

**الإرجاع:**  
int

### setCategoryAxisType(int value) {#setCategoryAxisType-int-}
```
public final void setCategoryAxisType(int value)
```

يحدد نوع محور الفئة. قراءة/كتابة [CategoryAxisType](../../com.aspose.slides/categoryaxistype).

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

يمثل النقطة على المحور التي يتقاطع فيها المحور المتعامد معه. قراءة/كتابة float.

**الإرجاع:**  
float

### setCrossAt(float value) {#setCrossAt-float-}
```
public final void setCrossAt(float value)
```

يمثل النقطة على المحور التي يتقاطع فيها المحور المتعامد معه. قراءة/كتابة float.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getDisplayUnit() {#getDisplayUnit--}
```
public final int getDisplayUnit()
```

يحدد قيمة التحجيم لوحدات العرض لمحور القيم. قراءة/كتابة [DisplayUnitType](../../com.aspose.slides/displayunittype).

**الإرجاع:**  
int

### setDisplayUnit(int value) {#setDisplayUnit-int-}
```
public final void setDisplayUnit(int value)
```

يحدد قيمة التحجيم لوحدات العرض لمحور القيم. قراءة/كتابة [DisplayUnitType](../../com.aspose.slides/displayunittype).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getActualMaxValue() {#getActualMaxValue--}
```
public final double getActualMaxValue()
```

يحدد القيمة القصوى الفعلية على المحور. استدعِ طريقة IChart.ValidateChartLayout() مسبقًا للحصول على القيمة الفعلية.

**الإرجاع:**  
double

### getActualMinValue() {#getActualMinValue--}
```
public final double getActualMinValue()
```

يحدد القيمة الدنيا الفعلية على المحور. استدعِ طريقة IChart.ValidateChartLayout() مسبقًا للحصول على القيمة الفعلية.

**الإرجاع:**  
double

### getActualMajorUnit() {#getActualMajorUnit--}
```
public final double getActualMajorUnit()
```

يحدد الوحدة الرئيسية الفعلية للمحور. استدعِ طريقة IChart.ValidateChartLayout() مسبقًا للحصول على القيمة الفعلية.

**الإرجاع:**  
double

### getActualMinorUnit() {#getActualMinorUnit--}
```
public final double getActualMinorUnit()
```

يحدد الوحدة الفرعية الفعلية للمحور. استدعِ طريقة IChart.ValidateChartLayout() مسبقًا للحصول على القيمة الفعلية.

**الإرجاع:**  
double

### getActualMajorUnitScale() {#getActualMajorUnitScale--}
```
public final int getActualMajorUnitScale()
```

يحدد مقياس الوحدة الرئيسية الفعلية للمحور. استدعِ طريقة IChart.ValidateChartLayout() مسبقًا للحصول على القيمة الفعلية.

**الإرجاع:**  
int

### getActualMinorUnitScale() {#getActualMinorUnitScale--}
```
public final int getActualMinorUnitScale()
```

يحدد مقياس الوحدة الفرعية الفعلية للمحور. استدعِ طريقة IChart.ValidateChartLayout() مسبقًا للحصول على القيمة الفعلية.

**الإرجاع:**  
int

### isAutomaticMaxValue() {#isAutomaticMaxValue--}
```
public final boolean isAutomaticMaxValue()
```

يشير إلى ما إذا كانت القيمة العظمى تُحدد تلقائيًا. قراءة/كتابة boolean.

**الإرجاع:**  
boolean

### setAutomaticMaxValue(boolean value) {#setAutomaticMaxValue-boolean-}
```
public final void setAutomaticMaxValue(boolean value)
```

يشير إلى ما إذا كانت القيمة العظمى تُحدد تلقائيًا. قراءة/كتابة boolean.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getMaxValue() {#getMaxValue--}
```
public final double getMaxValue()
```

يمثل القيمة العظمى على محور القيم. قراءة/كتابة double.

**الإرجاع:**  
double

### setMaxValue(double value) {#setMaxValue-double-}
```
public final void setMaxValue(double value)
```

يمثل القيمة العظمى على محور القيم. قراءة/كتابة double.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | double |  |

### getMinorUnit() {#getMinorUnit--}
```
public final double getMinorUnit()
```

يمثل الوحدات الفرعية لمحور التاريخ أو القيم. قراءة/كتابة double.

**الإرجاع:**  
double

### setMinorUnit(double value) {#setMinorUnit-double-}
```
public final void setMinorUnit(double value)
```

يمثل الوحدات الفرعية لمحور التاريخ أو القيم. قراءة/كتابة double.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | double |  |

### isAutomaticMinorUnit() {#isAutomaticMinorUnit--}
```
public final boolean isAutomaticMinorUnit()
```

يشير إلى ما إذا كانت الوحدة الفرعية للمحور تُحدد تلقائيًا. قراءة/كتابة boolean.

**الإرجاع:**  
boolean

### setAutomaticMinorUnit(boolean value) {#setAutomaticMinorUnit-boolean-}
```
public final void setAutomaticMinorUnit(boolean value)
```

يشير إلى ما إذا كانت الوحدة الفرعية للمحور تُحدد تلقائيًا. قراءة/كتابة boolean.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getMajorUnit() {#getMajorUnit--}
```
public final double getMajorUnit()
```

يمثل الوحدات الرئيسية لمحور التاريخ أو القيم. قراءة/كتابة double.

**الإرجاع:**  
double

### setMajorUnit(double value) {#setMajorUnit-double-}
```
public final void setMajorUnit(double value)
```

يمثل الوحدات الرئيسية لمحور التاريخ أو القيم. قراءة/كتابة double.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | double |  |

### isAutomaticMajorUnit() {#isAutomaticMajorUnit--}
```
public final boolean isAutomaticMajorUnit()
```

يشير إلى ما إذا كانت الوحدة الرئيسية للمحور تُحدد تلقائيًا. قراءة/كتابة boolean.

**الإرجاع:**  
boolean

### setAutomaticMajorUnit(boolean value) {#setAutomaticMajorUnit-boolean-}
```
public final void setAutomaticMajorUnit(boolean value)
```

يشير إلى ما إذا كانت الوحدة الرئيسية للمحور تُحدد تلقائيًا. قراءة/كتابة boolean.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticMinValue() {#isAutomaticMinValue--}
```
public final boolean isAutomaticMinValue()
```

يشير إلى ما إذا كانت القيمة الصغرى تُحدد تلقائيًا. قراءة/كتابة boolean.

**الإرجاع:**  
boolean

### setAutomaticMinValue(boolean value) {#setAutomaticMinValue-boolean-}
```
public final void setAutomaticMinValue(boolean value)
```

يشير إلى ما إذا كانت القيمة الصغرى تُحدد تلقائيًا. قراءة/كتابة boolean.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getMinValue() {#getMinValue--}
```
public final double getMinValue()
```

يمثل القيمة الصغرى على محور القيم. قراءة/كتابة double.

**الإرجاع:**  
double

### setMinValue(double value) {#setMinValue-double-}
```
public final void setMinValue(double value)
```

يمثل القيمة الصغرى على محور القيم. قراءة/كتابة double.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | double |  |

### isLogarithmic() {#isLogarithmic--}
```
public final boolean isLogarithmic()
```

يمثل ما إذا كان نوع مقياس محور القيم لوغاريتميًا أم لا. قراءة/كتابة boolean.

**الإرجاع:**  
boolean

### setLogarithmic(boolean value) {#setLogarithmic-boolean-}
```
public final void setLogarithmic(boolean value)
```

يمثل ما إذا كان نوع مقياس محور القيم لوغاريتميًا أم لا. قراءة/كتابة boolean.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getLogBase() {#getLogBase--}
```
public final double getLogBase()
```

يمثل القاعدة اللوغاريتمية. القيمة الافتراضية هي 10. قراءة/كتابة double.

**الإرجاع:**  
double

### setLogBase(double value) {#setLogBase-double-}
```
public final void setLogBase(double value)
```

يمثل القاعدة اللوغاريتمية. القيمة الافتراضية هي 10. قراءة/كتابة double.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | double |  |

### isPlotOrderReversed() {#isPlotOrderReversed--}
```
public final boolean isPlotOrderReversed()
```

يمثل ما إذا كان برنامج MS PowerPoint يرسم نقاط البيانات من الأخير إلى الأول. قراءة/كتابة boolean.

**الإرجاع:**  
boolean

### setPlotOrderReversed(boolean value) {#setPlotOrderReversed-boolean-}
```
public final void setPlotOrderReversed(boolean value)
```

يمثل ما إذا كان برنامج MS PowerPoint يرسم نقاط البيانات من الأخير إلى الأول. قراءة/كتابة boolean.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### isVisible() {#isVisible--}
```
public final boolean isVisible()
```

يمثل ما إذا كان المحور مرئيًا. قراءة/كتابة boolean.

**الإرجاع:**  
boolean

### setVisible(boolean value) {#setVisible-boolean-}
```
public final void setVisible(boolean value)
```

يمثل ما إذا كان المحور مرئيًا. قراءة/كتابة boolean.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getMajorTickMark() {#getMajorTickMark--}
```
public final int getMajorTickMark()
```

يمثل نوع علامة التقسيم الرئيسية للمحور المحدد. قراءة/كتابة [TickMarkType](../../com.aspose.slides/tickmarktype).

**الإرجاع:**  
int

### setMajorTickMark(int value) {#setMajorTickMark-int-}
```
public final void setMajorTickMark(int value)
```

يمثل نوع علامة التقسيم الرئيسية للمحور المحدد. قراءة/كتابة [TickMarkType](../../com.aspose.slides/tickmarktype).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getMinorTickMark() {#getMinorTickMark--}
```
public final int getMinorTickMark()
```

يمثل نوع علامة التقسيم الفرعية للمحور المحدد. قراءة/كتابة [TickMarkType](../../com.aspose.slides/tickmarktype).

**الإرجاع:**  
int

### setMinorTickMark(int value) {#setMinorTickMark-int-}
```
public final void setMinorTickMark(int value)
```

يمثل نوع علامة التقسيم الفرعية للمحور المحدد. قراءة/كتابة [TickMarkType](../../com.aspose.slides/tickmarktype).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getTickLabelPosition() {#getTickLabelPosition--}
```
public final int getTickLabelPosition()
```

يمثل موضع تسميات علامات التقسيم على المحور المحدد. قراءة/كتابة [TickLabelPositionType](../../com.aspose.slides/ticklabelpositiontype).

**الإرجاع:**  
int

### setTickLabelPosition(int value) {#setTickLabelPosition-int-}
```
public final void setTickLabelPosition(int value)
```

يمثل موضع تسميات علامات التقسيم على المحور المحدد. قراءة/كتابة [TickLabelPositionType](../../com.aspose.slides/ticklabelpositiontype).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getMajorUnitScale() {#getMajorUnitScale--}
```
public final int getMajorUnitScale()
```

يمثل مقياس الوحدة الرئيسية لمحور التاريخ. قراءة/كتابة [TimeUnitType](../../com.aspose.slides/timeunittype).

**الإرجاع:**  
int

### setMajorUnitScale(int value) {#setMajorUnitScale-int-}
```
public final void setMajorUnitScale(int value)
```

يمثل مقياس الوحدة الرئيسية لمحور التاريخ. قراءة/كتابة [TimeUnitType](../../com.aspose.slides/timeunittype).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getMinorUnitScale() {#getMinorUnitScale--}
```
public final int getMinorUnitScale()
```

يمثل مقياس الوحدة الرئيسية لمحور التاريخ. قراءة/كتابة [TimeUnitType](../../com.aspose.slides/timeunittype).

**الإرجاع:**  
int

### setMinorUnitScale(int value) {#setMinorUnitScale-int-}
```
public final void setMinorUnitScale(int value)
```

يمثل مقياس الوحدة الرئيسية لمحور التاريخ. قراءة/كتابة [TimeUnitType](../../com.aspose.slides/timeunittype).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getBaseUnitScale() {#getBaseUnitScale--}
```
public final int getBaseUnitScale()
```

يحدد أصغر وحدة زمنية يتم تمثيلها على محور التاريخ. قراءة/كتابة [TimeUnitType](../../com.aspose.slides/timeunittype).

**الإرجاع:**  
int

### setBaseUnitScale(int value) {#setBaseUnitScale-int-}
```
public final void setBaseUnitScale(int value)
```

يحدد أصغر وحدة زمنية يتم تمثيلها على محور التاريخ. قراءة/كتابة [TimeUnitType](../../com.aspose.slides/timeunittype).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getMinorGridLinesFormat() {#getMinorGridLinesFormat--}
```
public final IChartLinesFormat getMinorGridLinesFormat()
```

يمثل تنسيق خطوط الشبكة الفرعية على محور المخطط. للقراءة فقط [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

**الإرجاع:**  
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)

### getMajorGridLinesFormat() {#getMajorGridLinesFormat--}
```
public final IChartLinesFormat getMajorGridLinesFormat()
```

يمثل تنسيق خطوط الشبكة الرئيسية على محور المخطط. للقراءة فقط [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

**الإرجاع:**  
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)

### getShowMinorGridLines() {#getShowMinorGridLines--}
```
public final boolean getShowMinorGridLines()
```

لإخفاء الخط الشبكي الفرعي اضبط MinorGridLinesFormat.Line.FillFormat.FillType إلى FillType.NoFill. للقراءة فقط boolean.

**الإرجاع:**  
boolean

### getShowMajorGridLines() {#getShowMajorGridLines--}
```
public final boolean getShowMajorGridLines()
```

لإخفاء الخط الشبكي الرئيسي اضبط MajorGridLinesFormat.Line.FillFormat.FillType إلى FillType.NoFill. للقراءة فقط boolean.

**الإرجاع:**  
boolean

### getFormat() {#getFormat--}
```
public final IAxisFormat getFormat()
```

يمثل تنسيق المحور. للقراءة فقط [IAxisFormat](../../com.aspose.slides/iaxisformat).

**الإرجاع:**  
[IAxisFormat](../../com.aspose.slides/iaxisformat)

### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```

يمثل تنسيق النص. للقراءة فقط [IChartTextFormat](../../com.aspose.slides/icharttextformat).

**الإرجاع:**  
[IChartTextFormat](../../com.aspose.slides/icharttextformat)

### getTitle() {#getTitle--}
```
public final IChartTitle getTitle()
```

يحصل على عنوان المحور. للقراءة فقط [IChartTitle](../../com.aspose.slides/icharttitle).

**الإرجاع:**  
[IChartTitle](../../com.aspose.slides/icharttitle)

### getCrossType() {#getCrossType--}
```
public final int getCrossType()
```

يمثل نوع التقاطع (CrossType) على المحور المحدد حيث يعبر المحور الآخر. قراءة/كتابة [CrossesType](../../com.aspose.slides/crossestype).

**الإرجاع:**  
int

### setCrossType(int value) {#setCrossType-int-}
```
public final void setCrossType(int value)
```

يمثل نوع التقاطع (CrossType) على المحور المحدد حيث يعبر المحور الآخر. قراءة/كتابة [CrossesType](../../com.aspose.slides/crossestype).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getPosition() {#getPosition--}
```
public



```

يمثل موقع المحور. قراءة/كتابة [AxisPositionType](../../com.aspose.slides/axispositiontype).

**الإرجاع:**  
int

### setPosition(int value) {#setPosition-int-}
```
public final void setPosition(int value)
```

يمثل موقع المحور. قراءة/كتابة [AxisPositionType](../../com.aspose.slides/axispositiontype).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### hasTitle() {#hasTitle--}
```
public final boolean hasTitle()
```

يحدد ما إذا كان للمحور عنوان مرئي. قراءة/كتابة boolean.

**الإرجاع:**  
boolean

### setTitle(boolean value) {#setTitle-boolean-}
```
public final void setTitle(boolean value)
```

يحدد ما إذا كان للمحور عنوان مرئي. قراءة/كتابة boolean.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getNumberFormat() {#getNumberFormat--}
```
public final String getNumberFormat()
```

يمثل سلسلة تنسيق تسميات المحور. قراءة/كتابة String.

**الإرجاع:**  
java.lang.String

### setNumberFormat(String value) {#setNumberFormat-java.lang.String-}
```
public final void setNumberFormat(String value)
```

يمثل سلسلة تنسيق تسميات المحور. قراءة/كتابة String.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### isNumberFormatLinkedToSource() {#isNumberFormatLinkedToSource--}
```
public final boolean isNumberFormatLinkedToSource()
```

يشير إلى ما إذا كان التنسيق مرتبطًا ببيانات المصدر. قراءة/كتابة boolean.

**الإرجاع:**  
boolean

### setNumberFormatLinkedToSource(boolean value) {#setNumberFormatLinkedToSource-boolean-}
```
public final void setNumberFormatLinkedToSource(boolean value)
```

يشير إلى ما إذا كان التنسيق مرتبطًا ببيانات المصدر. قراءة/كتابة boolean.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getTickLabelRotationAngle() {#getTickLabelRotationAngle--}
```
public final float getTickLabelRotationAngle()
```

يمثل زاوية دوران تسميات العلامات. قراءة/كتابة float.

**الإرجاع:**  
float

### setTickLabelRotationAngle(float value) {#setTickLabelRotationAngle-float-}
```
public final void setTickLabelRotationAngle(float value)
```

يمثل زاوية دوران تسميات العلامات. قراءة/كتابة float.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getTickLabelSpacing() {#getTickLabelSpacing--}
```
public final long getTickLabelSpacing()
```

يحدد عدد تسميات العلامات التي يتم تخطيها بين كل تسمية مرسومة. يتم تطبيقه على محور الفئة أو السلسلة. قراءة/كتابة long.

**الإرجاع:**  
long

### setTickLabelSpacing(long value) {#setTickLabelSpacing-long-}
```
public final void setTickLabelSpacing(long value)
```

يحدد عدد تسميات العلامات التي يتم تخطيها بين كل تسمية مرسومة. يتم تطبيقه على محور الفئة أو السلسلة. قراءة/كتابة long.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | long |  |

### isAutomaticTickLabelSpacing() {#isAutomaticTickLabelSpacing--}
```
public final boolean isAutomaticTickLabelSpacing()
```

يحدد قيمة التباعد التلقائي لتسميات العلامات. إذا كان false: استخدم خاصية TickLabelSpacing. قراءة/كتابة boolean.

**الإرجاع:**  
boolean

### setAutomaticTickLabelSpacing(boolean value) {#setAutomaticTickLabelSpacing-boolean-}
```
public final void setAutomaticTickLabelSpacing(boolean value)
```

يحدد قيمة التباعد التلقائي لتسميات العلامات. إذا كان false: استخدم خاصية TickLabelSpacing. قراءة/كتابة boolean.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getTickMarksSpacing() {#getTickMarksSpacing--}
```
public final long getTickMarksSpacing()
```

يحدد عدد علامات التقسيم التي يجب تخطيها قبل رسم العلامة التالية. يتم تطبيقه على محور الفئة أو السلسلة. قراءة/كتابة int.

**الإرجاع:**  
long

### setTickMarksSpacing(long value) {#setTickMarksSpacing-long-}
```
public final void setTickMarksSpacing(long value)
```

يحدد عدد علامات التقسيم التي يجب تخطيها قبل رسم العلامة التالية. يتم تطبيقه على محور الفئة أو السلسلة. قراءة/كتابة int.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | long |  |

### isAutomaticTickMarksSpacing() {#isAutomaticTickMarksSpacing--}
```
public final boolean isAutomaticTickMarksSpacing()
```

يحدد قيمة التباعد التلقائي لعلامات التقسيم. إذا كان false: استخدم خاصية TickMarksSpacing. قراءة/كتابة boolean.

**الإرجاع:**  
boolean

### setAutomaticTickMarksSpacing(boolean value) {#setAutomaticTickMarksSpacing-boolean-}
```
public final void setAutomaticTickMarksSpacing(boolean value)
```

يحدد قيمة التباعد التلقائي لعلامات التقسيم. إذا كان false: استخدم خاصية TickMarksSpacing. قراءة/كتابة boolean.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getLabelOffset() {#getLabelOffset--}
```
public final int getLabelOffset()
```

يحدد المسافة بين التسميات والمحور. يتم تطبيقه على محور الفئة أو التاريخ. القيمة يجب أن تكون بين 0% و1000%. قراءة/كتابة int.

**الإرجاع:**  
int

### setLabelOffset(int value) {#setLabelOffset-int-}
```
public
```

يحدد المسافة بين التسميات والمحور. يتم تطبيقه على محور الفئة أو التاريخ. القيمة يجب أن تكون بين 0% و1000%. قراءة/كتابة int.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getAggregationType() {#getAggregationType--}
```
public final int getAggregationType()
```

يمثل نوع التجميع لمحور الفئة (التجزئة). يتم تطبيقه على الفئة. يستخدم مع سلسلة Histogram أو HistogramPareto فقط.

**الإرجاع:**  
int

### setAggregationType(int value) {#setAggregationType-int-}
```
public final void setAggregationType(int value)
```

يمثل نوع التجميع لمحور الفئة (التجزئة). يتم تطبيقه على الفئة. يستخدم مع سلسلة Histogram أو HistogramPareto فقط.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getBinWidth() {#getBinWidth--}
```
public final double getBinWidth()
```

يحدد عرض الصندوق عندما تكون قيمة خاصية AggregationType مضبوطة على AxisAggregationType.ByBinWidth. يتم تطبيقه على محاور الفئة. يستخدم مع سلسلة Histogram أو HistogramPareto فقط.

**الإرجاع:**  
double

### setBinWidth(double value) {#setBinWidth-double-}
```
public final void setBinWidth(double value)
```

يحدد عرض الصندوق عندما تكون قيمة خاصية AggregationType مضبوطة على AxisAggregationType.ByBinWidth. يتم تطبيقه على محاور الفئة. يستخدم مع سلسلة Histogram أو HistogramPareto فقط.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | double |  |

### getNumberOfBins() {#getNumberOfBins--}
```
public final long getNumberOfBins()
```

يحدد عدد الصناديق عندما تكون قيمة خاصية AggregationType مضبوطة على AxisAggregationType.ByNumberOfBins. يتم تطبيقه على محاور الفئة. يستخدم مع سلسلة Histogram أو HistogramPareto فقط.

**الإرجاع:**  
long

### setNumberOfBins(long value) {#setNumberOfBins-long-}
```
public final void setNumberOfBins(long value)
```

يحدد عدد الصناديق عندما تكون قيمة خاصية AggregationType مضبوطة على AxisAggregationType.ByNumberOfBins. يتم تطبيقه على محاور الفئة. يستخدم مع سلسلة Histogram أو HistogramPareto فقط.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | long |  |

### isOverflowBin() {#isOverflowBin--}
```
public final boolean isOverflowBin()
```

يمثل ما إذا تم تطبيق صندوق الفائض. استخدم IsAutomaticOverflowBin وOverflowBin لضبط قيمة صندوق الفائض.

**الإرجاع:**  
boolean

### setOverflowBin(boolean value) {#setOverflowBin-boolean-}
```
public final void setOverflowBin(boolean value)
```

يمثل ما إذا تم تطبيق صندوق الفائض. استخدم IsAutomaticOverflowBin وOverflowBin لضبط قيمة صندوق الفائض.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticOverflowBin() {#isAutomaticOverflowBin--}
```
public final boolean isAutomaticOverflowBin()
```

يحدد قيمة صندوق الفائض التلقائي. إذا كان false: استخدم خاصية OverflowBin.

**الإرجاع:**  
boolean

### setAutomaticOverflowBin(boolean value) {#setAutomaticOverflowBin-boolean-}
```
public final void setAutomaticOverflowBin(boolean value)
```

يحدد قيمة صندوق الفائض التلقائي. إذا كان false: استخدم خاصية OverflowBin.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getOverflowBin() {#getOverflowBin--}
```
public final double getOverflowBin()
```

يحدد قيمة مخصصة لصندوق الفائض. يتم تطبيقه عندما تكون خاصية IsAutomaticOverflowBin مضبوطة على false وتكون خاصية IsOverflowBin مساوية true.

**الإرجاع:**  
double

### setOverflowBin(double value) {#setOverflowBin-double-}
```
public final void setOverflowBin(double value)
```

يحدد قيمة مخصصة لصندوق الفائض. يتم تطبيقه عندما تكون خاصية IsAutomaticOverflowBin مضبوطة على false وتكون خاصية IsOverflowBin مساوية true.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | double |  |

### isUnderflowBin() {#isUnderflowBin--}
```
public final boolean isUnderflowBin()
```

يمثل ما إذا تم تطبيق صندوق النقص. استخدم IsAutomaticUnderflowBin وUnderflowBin لضبط قيمة صندوق النقص.

**الإرجاع:**  
boolean

### setUnderflowBin(boolean value) {#setUnderflowBin-boolean-}
```
public final void setUnderflowBin(boolean value)
```

يمثل ما إذا تم تطبيق صندوق النقص. استخدم IsAutomaticUnderflowBin وUnderflowBin لضبط قيمة صندوق النقص.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticUnderflowBin() {#isAutomaticUnderflowBin--}
```
public final boolean isAutomaticUnderflowBin()
```

يحدد قيمة صندوق النقص التلقائي. إذا كان false: استخدم خاصية UnderflowBin.

**الإرجاع:**  
boolean

### setAutomaticUnderflowBin(boolean value) {#setAutomaticUnderflowBin-boolean-}
```
public final void setAutomaticUnderflowBin(boolean value)
```

يحدد قيمة صندوق النقص التلقائي. إذا كان false: استخدم خاصية UnderflowBin.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getUnderflowBin() {#getUnderflowBin--}
```
public final double getUnderflowBin()
```

يحدد قيمة مخصصة لصندوق النقص. يتم تطبيقه عندما تكون خاصية IsAutomaticUnderflowBin مضبوطة على false وتكون خاصية IsUnderflowBin مساوية true.

**الإرجاع:**  
double

### setUnderflowBin(double value) {#setUnderflowBin-double-}
```
public final void setUnderflowBin(double value)
```

يحدد قيمة مخصصة لصندوق النقص. يتم تطبيقه عندما تكون خاصية IsAutomaticUnderflowBin مضبوطة على false وتكون خاصية IsUnderflowBin مساوية true.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | double |  |

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

إرجاع الشريحة الأم لـ FillFormat. للقراءة فقط [BaseSlide](../../com.aspose.slides/baseslide).

**الإرجاع:**  
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

إرجاع العرض (presentation) الأم لـ FillFormat. للقراءة فقط [IPresentation](../../com.aspose.slides/ipresentation).

**الإرجاع:**  
[IPresentation](../../com.aspose.slides/ipresentation)