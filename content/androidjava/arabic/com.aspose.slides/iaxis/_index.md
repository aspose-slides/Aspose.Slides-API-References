---
title: IAxis
second_title: Aspose.Slides لنظام Android عبر مرجع API لجافا
description: يغلف الكائن الذي يمثل محور المخطط.
type: docs
url: /ar/com.aspose.slides/iaxis/
---
**جميع الواجهات المنفذة:**
[com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer)
```
public interface IAxis extends IFormattedTextContainer
```

يغلف الكائن الذي يمثل محور المخطط.

## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getAxisBetweenCategories()](#getAxisBetweenCategories--) | يمثل ما إذا كان محور القيم يعبر محور الفئة بين الفئات. |
| [setAxisBetweenCategories(boolean value)](#setAxisBetweenCategories-boolean-) | يمثل ما إذا كان محور القيم يعبر محور الفئة بين الفئات. |
| [getCrossAt()](#getCrossAt--) | يمثل النقطة على المحور حيث يعبر المحور المتعامد عليه. |
| [setCrossAt(float value)](#setCrossAt-float-) | يمثل النقطة على المحور حيث يعبر المحور المتعامد عليه. |
| [getDisplayUnit()](#getDisplayUnit--) | يحدد قيمة التحجيم لوحدات العرض لمحور القيم. |
| [setDisplayUnit(int value)](#setDisplayUnit-int-) | يحدد قيمة التحجيم لوحدات العرض لمحور القيم. |
| [getActualMaxValue()](#getActualMaxValue--) | يحدد القيمة القصوى الفعلية على المحور. |
| [getActualMinValue()](#getActualMinValue--) | يحدد القيمة الدنيا الفعلية على المحور. |
| [getActualMajorUnit()](#getActualMajorUnit--) | يحدد الوحدة الرئيسية الفعلية للمحور. |
| [getActualMinorUnit()](#getActualMinorUnit--) | يحدد الوحدة الفرعية الفعلية للمحور. |
| [getActualMajorUnitScale()](#getActualMajorUnitScale--) | يحدد مقياس الوحدة الرئيسية الفعلية للمحور. |
| [getActualMinorUnitScale()](#getActualMinorUnitScale--) | يحدد مقياس الوحدة الفرعية الفعلية للمحور. |
| [isAutomaticMaxValue()](#isAutomaticMaxValue--) | يشير إلى ما إذا كانت القيمة القصوى تُعيّن تلقائيًا. |
| [setAutomaticMaxValue(boolean value)](#setAutomaticMaxValue-boolean-) | يشير إلى ما إذا كانت القيمة القصوى تُعيّن تلقائيًا. |
| [getMaxValue()](#getMaxValue--) | يمثل القيمة القصوى على محور القيم. |
| [setMaxValue(double value)](#setMaxValue-double-) | يمثل القيمة القصوى على محور القيم. |
| [getMinorUnit()](#getMinorUnit--) | يمثل الوحدات الفرعية لمحور التاريخ أو القيمة. |
| [setMinorUnit(double value)](#setMinorUnit-double-) | يمثل الوحدات الفرعية لمحور التاريخ أو القيمة. |
| [isAutomaticMinorUnit()](#isAutomaticMinorUnit--) | يشير إلى ما إذا كانت الوحدة الفرعية للمحور تُعيّن تلقائيًا. |
| [setAutomaticMinorUnit(boolean value)](#setAutomaticMinorUnit-boolean-) | يشير إلى ما إذا كانت الوحدة الفرعية للمحور تُعيّن تلقائيًا. |
| [getMajorUnit()](#getMajorUnit--) | يمثل الوحدات الرئيسية لمحور التاريخ أو القيمة. |
| [setMajorUnit(double value)](#setMajorUnit-double-) | يمثل الوحدات الرئيسية لمحور التاريخ أو القيمة. |
| [isAutomaticMajorUnit()](#isAutomaticMajorUnit--) | يشير إلى ما إذا كانت الوحدة الرئيسية للمحور تُعيّن تلقائيًا. |
| [setAutomaticMajorUnit(boolean value)](#setAutomaticMajorUnit-boolean-) | يشير إلى ما إذا كانت الوحدة الرئيسية للمحور تُعيّن تلقائيًا. |
| [isAutomaticMinValue()](#isAutomaticMinValue--) | يشير إلى ما إذا كانت القيمة الدنيا تُعيّن تلقائيًا. |
| [setAutomaticMinValue(boolean value)](#setAutomaticMinValue-boolean-) | يشير إلى ما إذا كانت القيمة الدنيا تُعيّن تلقائيًا. |
| [getMinValue()](#getMinValue--) | يمثل القيمة الدنيا على محور القيم. |
| [setMinValue(double value)](#setMinValue-double-) | يمثل القيمة الدنيا على محور القيم. |
| [isLogarithmic()](#isLogarithmic--) | يمثل ما إذا كان نوع مقياس محور القيم لوغاريتميًا أم لا. |
| [setLogarithmic(boolean value)](#setLogarithmic-boolean-) | يمثل ما إذا كان نوع مقياس محور القيم لوغاريتميًا أم لا. |
| [getLogBase()](#getLogBase--) | يمثل القاعدة اللوغاريتمية. |
| [setLogBase(double value)](#setLogBase-double-) | يمثل القاعدة اللوغاريتمية. |
| [isPlotOrderReversed()](#isPlotOrderReversed--) | يمثل ما إذا كان MS PowerPoint يرسم نقاط البيانات من الأخير إلى الأول. |
| [setPlotOrderReversed(boolean value)](#setPlotOrderReversed-boolean-) | يمثل ما إذا كان MS PowerPoint يرسم نقاط البيانات من الأخير إلى الأول. |
| [isVisible()](#isVisible--) | يمثل ما إذا كان المحور مرئيًا. |
| [setVisible(boolean value)](#setVisible-boolean-) | يمثل ما إذا كان المحور مرئيًا. |
| [getMajorTickMark()](#getMajorTickMark--) | يمثل نوع العلامة الرئيسية للمحور المحدد. |
| [setMajorTickMark(int value)](#setMajorTickMark-int-) | يمثل نوع العلامة الرئيسية للمحور المحدد. |
| [getMinorTickMark()](#getMinorTickMark--) | يمثل نوع العلامة الفرعية للمحور المحدد. |
| [setMinorTickMark(int value)](#setMinorTickMark-int-) | يمثل نوع العلامة الفرعية للمحور المحدد. |
| [getTickLabelPosition()](#getTickLabelPosition--) | يمثل موضع تسميات العلامات على المحور المحدد. |
| [setTickLabelPosition(int value)](#setTickLabelPosition-int-) | يمثل موضع تسميات العلامات على المحور المحدد. |
| [getMajorUnitScale()](#getMajorUnitScale--) | يمثل مقياس الوحدة الرئيسية لمحور التاريخ. |
| [setMajorUnitScale(int value)](#setMajorUnitScale-int-) | يمثل مقياس الوحدة الرئيسية لمحور التاريخ. |
| [getMinorUnitScale()](#getMinorUnitScale--) | يمثل مقياس الوحدة الرئيسية لمحور التاريخ. |
| [setMinorUnitScale(int value)](#setMinorUnitScale-int-) | يمثل مقياس الوحدة الرئيسية لمحور التاريخ. |
| [getBaseUnitScale()](#getBaseUnitScale--) | يحدد أصغر وحدة زمنية ممثلة على محور التاريخ. |
| [setBaseUnitScale(int value)](#setBaseUnitScale-int-) | يحدد أصغر وحدة زمنية ممثلة على محور التاريخ. |
| [getMinorGridLinesFormat()](#getMinorGridLinesFormat--) | يمثل تنسيق خطوط الشبكة الفرعية على محور المخطط. |
| [getMajorGridLinesFormat()](#getMajorGridLinesFormat--) | يمثل تنسيق خطوط الشبكة الرئيسية على محور المخطط. |
| [getShowMinorGridLines()](#getShowMinorGridLines--) | يمثل ما إذا كانت خطوط الشبكة الفرعية معروضة. |
| [getShowMajorGridLines()](#getShowMajorGridLines--) | يمثل ما إذا كانت خطوط الشبكة الرئيسية معروضة. |
| [getFormat()](#getFormat--) | يمثل تنسيق المحور. |
| [getTitle()](#getTitle--) | يحصل على عنوان المحور. |
| [getCrossType()](#getCrossType--) | يمثل نوع التقاطع على المحور المحدد حيث يعبر المحور الآخر. |
| [setCrossType(int value)](#setCrossType-int-) | يمثل نوع التقاطع على المحور المحدد حيث يعبر المحور الآخر. |
| [getPosition()](#getPosition--) | يمثل موضع المحور. |
| [setPosition(int value)](#setPosition-int-) | يمثل موضع المحور. |
| [hasTitle()](#hasTitle--) | يحدد ما إذا كان للمحور عنوان مرئي. |
| [setTitle(boolean value)](#setTitle-boolean-) | يحدد ما إذا كان للمحور عنوان مرئي. |
| [getNumberFormat()](#getNumberFormat--) | يمثل سلسلة التنسيق لتسميات المحور. |
| [setNumberFormat(String value)](#setNumberFormat-java.lang.String-) | يمثل سلسلة التنسيق لتسميات المحور. |
| [isNumberFormatLinkedToSource()](#isNumberFormatLinkedToSource--) | يشير إلى ما إذا كان التنسيق مرتبطًا ببيانات المصدر. |
| [setNumberFormatLinkedToSource(boolean value)](#setNumberFormatLinkedToSource-boolean-) | يشير إلى ما إذا كان التنسيق مرتبطًا ببيانات المصدر. |
| [getTickLabelRotationAngle()](#getTickLabelRotationAngle--) | يمثل زاوية دوران تسميات العلامات. قابل للقراءة والكتابة Float. |
| [setTickLabelRotationAngle(float value)](#setTickLabelRotationAngle-float-) | يمثل زاوية دوران تسميات العلامات. قابل للقراءة والكتابة Float. |
| [getTickLabelSpacing()](#getTickLabelSpacing--) | يحدد عدد تسميات العلامات التي يجب تخطيها بين كل تسمية مرسومة. |
| [setTickLabelSpacing(long value)](#setTickLabelSpacing-long-) | يحدد عدد تسميات العلامات التي يجب تخطيها بين كل تسمية مرسومة. |
| [isAutomaticTickLabelSpacing()](#isAutomaticTickLabelSpacing--) | يحدد قيمة تباعد تسميات العلامات التلقائي. |
| [setAutomaticTickLabelSpacing(boolean value)](#setAutomaticTickLabelSpacing-boolean-) | يحدد قيمة تباعد تسميات العلامات التلقائي. |
| [getTickMarksSpacing()](#getTickMarksSpacing--) | يحدد عدد علامات العظام التي يجب تخطيها قبل رسم العلامة التالية. |
| [setTickMarksSpacing(long value)](#setTickMarksSpacing-long-) | يحدد عدد علامات العظام التي يجب تخطيها قبل رسم العلامة التالية. |
| [isAutomaticTickMarksSpacing()](#isAutomaticTickMarksSpacing--) | يحدد قيمة تباعد علامات العظام التلقائي. |
| [setAutomaticTickMarksSpacing(boolean value)](#setAutomaticTickMarksSpacing-boolean-) | يحدد قيمة تباعد علامات العظام التلقائي. |
| [getLabelOffset()](#getLabelOffset--) | يحدد المسافة بين التسميات والمحور. |
| [setLabelOffset(int value)](#setLabelOffset-int-) | يحدد المسافة بين التسميات والمحور. |
| [getCategoryAxisType()](#getCategoryAxisType--) | يحدد نوع محور الفئة. |
| [setCategoryAxisType(int value)](#setCategoryAxisType-int-) | يحدد نوع محور الفئة. |
| [setCategoryAxisTypeAutomatically()](#setCategoryAxisTypeAutomatically--) | يضبط خاصية IAxis.CategoryAxisType بقيمة يتم تحديدها تلقائيًا بناءً على بيانات المحور. |
| [getAggregationType()](#getAggregationType--) | يمثل نوع التجميع لمحور الفئة (التجميع إلى صناديق). |
| [setAggregationType(int value)](#setAggregationType-int-) | يمثل نوع التجميع لمحور الفئة (التجميع إلى صناديق). |
| [getBinWidth()](#getBinWidth--) | يحدد عرض الصندوق عندما تكون قيمة خاصية AggregationType مضبوطة على AxisAggregationType.ByBinWidth. |
| [setBinWidth(double value)](#setBinWidth-double-) | يحدد عرض الصندوق عندما تكون قيمة خاصية AggregationType مضبوطة على AxisAggregationType.ByBinWidth. |
| [getNumberOfBins()](#getNumberOfBins--) | يحدد عدد الصناديق عندما تكون قيمة خاصية AggregationType مضبوطة على AxisAggregationType.ByNumberOfBins. |
| [setNumberOfBins(long value)](#setNumberOfBins-long-) | يحدد عدد الصناديق عندما تكون قيمة خاصية AggregationType مضبوطة على AxisAggregationType.ByNumberOfBins. |
| [isOverflowBin()](#isOverflowBin--) | يحدد ما إذا تم تطبيق صندوق الفائض. |
| [setOverflowBin(boolean value)](#setOverflowBin-boolean-) | يحدد ما إذا تم تطبيق صندوق الفائض. |
| [isAutomaticOverflowBin()](#isAutomaticOverflowBin--) | يحدد قيمة صندوق الفائض التلقائي. |
| [setAutomaticOverflowBin(boolean value)](#setAutomaticOverflowBin-boolean-) | يحدد قيمة صندوق الفائض التلقائي. |
| [getOverflowBin()](#getOverflowBin--) | يحدد قيمة مخصصة لصندوق الفائض. |
| [setOverflowBin(double value)](#setOverflowBin-double-) | يحدد قيمة مخصصة لصندوق الفائض. |
| [isUnderflowBin()](#isUnderflowBin--) | يحدد ما إذا تم تطبيق صندوق النقص. |
| [setUnderflowBin(boolean value)](#setUnderflowBin-boolean-) | يحدد ما إذا تم تطبيق صندوق النقص. |
| [isAutomaticUnderflowBin()](#isAutomaticUnderflowBin--) | يحدد قيمة صندوق النقص التلقائي. |
| [setAutomaticUnderflowBin(boolean value)](#setAutomaticUnderflowBin-boolean-) | يحدد قيمة صندوق النقص التلقائي. |
| [getUnderflowBin()](#getUnderflowBin--) | يحدد قيمة مخصصة لصندوق النقص. |
| [setUnderflowBin(double value)](#setUnderflowBin-double-) | يحدد قيمة مخصصة لصندوق النقص. |

### getAxisBetweenCategories() {#getAxisBetweenCategories--}
```
public abstract boolean getAxisBetweenCategories()
```

يمثل ما إذا كان محور القيم يعبر محور الفئة بين الفئات. تنطبق هذه الخاصية فقط على محاور الفئة، ولا تنطبق على المخططات ثلاثية الأبعاد. قابل للقراءة والكتابة Boolean.

**القيمة المرجعة:**
boolean

### setAxisBetweenCategories(boolean value) {#setAxisBetweenCategories-boolean-}
```
public abstract void setAxisBetweenCategories(boolean value)
```

يمثل ما إذا كان محور القيم يعبر محور الفئة بين الفئات. تنطبق هذه الخاصية فقط على محاور الفئة، ولا تنطبق على المخططات ثلاثية الأبعاد. قابل للقراءة والكتابة Boolean.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getCrossAt() {#getCrossAt--}
```
public abstract float getCrossAt()
```

يمثل النقطة على المحور حيث يعبر المحور المتعامد عليه. قابل للقراءة والكتابة Float.

**القيمة المرجعة:**
float

### setCrossAt(float value) {#setCrossAt-float-}
```
public abstract void setCrossAt(float value)
```

يمثل النقطة على المحور حيث يعبر المحور المتعامد عليه. قابل للقراءة والكتابة Float.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getDisplayUnit() {#getDisplayUnit--}
```
public abstract int getDisplayUnit()
```

يحدد قيمة التحجيم لوحدات العرض لمحور القيم. قابل للقراءة والكتابة [DisplayUnitType](../../com.aspose.slides/displayunittype).

**القيمة المرجعة:**
int

### setDisplayUnit(int value) {#setDisplayUnit-int-}
```
public abstract void setDisplayUnit(int value)
```

يحدد قيمة التحجيم لوحدات العرض لمحور القيم. قابل للقراءة والكتابة [DisplayUnitType](../../com.aspose.slides/displayunittype).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getActualMaxValue() {#getActualMaxValue--}
```
public abstract double getActualMaxValue()
```

يحدد القيمة القصوى الفعلية على المحور. استدعِ طريقة IChart.ValidateChartLayout() مسبقًا للحصول على القيمة الفعلية.

**القيمة المرجعة:**
double

### getActualMinValue() {#getActualMinValue--}
```
public abstract double getActualMinValue()
```

يحدد القيمة الدنيا الفعلية على المحور. استدعِ طريقة IChart.ValidateChartLayout() مسبقًا للحصول على القيمة الفعلية.

**القيمة المرجعة:**
double

### getActualMajorUnit() {#getActualMajorUnit--}
```
public abstract double getActualMajorUnit()
```

يحدد الوحدة الرئيسية الفعلية للمحور. استدعِ طريقة IChart.ValidateChartLayout() مسبقًا للحصول على القيمة الفعلية.

**القيمة المرجعة:**
double

### getActualMinorUnit() {#getActualMinorUnit--}
```
public abstract double getActualMinorUnit()
```

يحدد الوحدة الفرعية الفعلية للمحور. استدعِ طريقة IChart.ValidateChartLayout() مسبقًا للحصول على القيمة الفعلية.

**القيمة المرجعة:**
double

### getActualMajorUnitScale() {#getActualMajorUnitScale--}
```
public abstract int getActualMajorUnitScale()
```

يحدد مقياس الوحدة الرئيسية الفعلية للمحور. استدعِ طريقة IChart.ValidateChartLayout() مسبقًا للحصول على القيمة الفعلية.

**القيمة المرجعة:**
int

### getActualMinorUnitScale() {#getActualMinorUnitScale--}
```
public abstract int getActualMinorUnitScale()
```

يحدد مقياس الوحدة الفرعية الفعلية للمحور. استدعِ طريقة IChart.ValidateChartLayout() مسبقًا للحصول على القيمة الفعلية.

**القيمة المرجعة:**
int

### isAutomaticMaxValue() {#isAutomaticMaxValue--}
```
public abstract boolean isAutomaticMaxValue()
```

يشير إلى ما إذا كانت القيمة القصوى تُعيّن تلقائيًا. قابل للقراءة والكتابة Boolean.

**القيمة المرجعة:**
boolean

### setAutomaticMaxValue(boolean value) {#setAutomaticMaxValue-boolean-}
```
public abstract void setAutomaticMaxValue(boolean value)
```

يشير إلى ما إذا كانت القيمة القصوى تُعيّن تلقائيًا. قابل للقراءة والكتابة Boolean.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getMaxValue() {#getMaxValue--}
```
public abstract double getMaxValue()
```

يمثل القيمة القصوى على محور القيم. قابل للقراءة والكتابة double.

**القيمة المرجعة:**
double

### setMaxValue(double value) {#setMaxValue-double-}
```
public abstract void setMaxValue(double value)
```

يمثل القيمة القصوى على محور القيم. قابل للقراءة والكتابة double.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | double |  |

### getMinorUnit() {#getMinorUnit--}
```
public abstract double getMinorUnit()
```

يمثل الوحدات الفرعية لمحور التاريخ أو القيمة. قابل للقراءة والكتابة double.

**القيمة المرجعة:**
double

### setMinorUnit(double value) {#setMinorUnit-double-}
```
public abstract void setMinorUnit(double value)
```

يمثل الوحدات الفرعية لمحور التاريخ أو القيمة. قابل للقراءة والكتابة double.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | double |  |

### isAutomaticMinorUnit() {#isAutomaticMinorUnit--}
```
public abstract boolean isAutomaticMinorUnit()
```

يشير إلى ما إذا كانت الوحدة الفرعية للمحور تُعيّن تلقائيًا. قابل للقراءة والكتابة Boolean.

**القيمة المرجعة:**
boolean

### setAutomaticMinorUnit(boolean value) {#setAutomaticMinorUnit-boolean-}
```
public abstract void setAutomaticMinorUnit(boolean value)
```

يشير إلى ما إذا كانت الوحدة الفرعية للمحور تُعيّن تلقائيًا. قابل للقراءة والكتابة Boolean.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getMajorUnit() {#getMajorUnit--}
```
public abstract double getMajorUnit()
```

يمثل الوحدات الرئيسية لمحور التاريخ أو القيمة. قابل للقراءة والكتابة double.

**القيمة المرجعة:**
double

### setMajorUnit(double value) {#setMajorUnit-double-}
```
public abstract void setMajorUnit(double value)
```

يمثل الوحدات الرئيسية لمحور التاريخ أو القيمة. قابل للقراءة والكتابة double.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | double |  |

### isAutomaticMajorUnit() {#isAutomaticMajorUnit--}
```
public abstract boolean isAutomaticMajorUnit()
```

يشير إلى ما إذا كانت الوحدة الرئيسية للمحور تُعيّن تلقائيًا. قابل للقراءة والكتابة Boolean.

**القيمة المرجعة:**
boolean

### setAutomaticMajorUnit(boolean value) {#setAutomaticMajorUnit-boolean-}
```
public abstract void setAutomaticMajorUnit(boolean value)
```

يشير إلى ما إذا كانت الوحدة الرئيسية للمحور تُعيّن تلقائيًا. قابل للقراءة والكتابة Boolean.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticMinValue() {#isAutomaticMinValue--}
```
public abstract boolean isAutomaticMinValue()
```

يشير إلى ما إذا كانت القيمة الدنيا تُعيّن تلقائيًا. قابل للقراءة والكتابة Boolean.

**القيمة المرجعة:**
boolean

### setAutomaticMinValue(boolean value) {#setAutomaticMinValue-boolean-}
```
public abstract void setAutomaticMinValue(boolean value)
```

يشير إلى ما إذا كانت القيمة الدنيا تُعيّن تلقائيًا. قابل للقراءة والكتابة Boolean.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getMinValue() {#getMinValue--}
```
public abstract double getMinValue()
```

يمثل القيمة الدنيا على محور القيم. قابل للقراءة والكتابة double.

**القيمة المرجعة:**
double

### setMinValue(double value) {#setMinValue-double-}
```
public abstract void setMinValue(double value)
```

يمثل القيمة الدنيا على محور القيم. قابل للقراءة والكتابة double.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | double |  |

### isLogarithmic() {#isLogarithmic--}
```
public abstract boolean isLogarithmic()
```

يمثل ما إذا كان نوع مقياس محور القيم لوغاريتميًا أم لا. قابل للقراءة والكتابة Boolean.

**القيمة المرجعة:**
boolean

### setLogarithmic(boolean value) {#setLogarithmic-boolean-}
```
public abstract void setLogarithmic(boolean value)
```

يمثل ما إذا كان نوع مقياس محور القيم لوغاريتميًا أم لا. قابل للقراءة والكتابة Boolean.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getLogBase() {#getLogBase--}
```
public abstract double getLogBase()
```

يمثل القاعدة اللوغاريتمية. القيمة الافتراضية هي 10. قابل للقراءة والكتابة double.

**القيمة المرجعة:**
double

### setLogBase(double value) {#setLogBase-double-}
```
public abstract void setLogBase(double value)
```

يمثل القاعدة اللوغاريتمية. القيمة الافتراضية هي 10. قابل للقراءة والكتابة double.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | double |  |

### isPlotOrderReversed() {#isPlotOrderReversed--}
```
public abstract boolean isPlotOrderReversed()
```

يمثل ما إذا كان MS PowerPoint يرسم نقاط البيانات من الأخير إلى الأول. قابل للقراءة والكتابة Boolean.

**القيمة المرجعة:**
boolean

### setPlotOrderReversed(boolean value) {#setPlotOrderReversed-boolean-}
```
public abstract void setPlotOrderReversed(boolean value)
```

يمثل ما إذا كان MS PowerPoint يرسم نقاط البيانات من الأخير إلى الأول. قابل للقراءة والكتابة Boolean.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```

يمثل ما إذا كان المحور مرئيًا. قابل للقراءة والكتابة Boolean.

**القيمة المرجعة:**
boolean

### setVisible(boolean value) {#setVisible-boolean-}
```
public abstract void setVisible(boolean value)
```

يمثل ما إذا كان المحور مرئيًا. قابل للقراءة والكتابة Boolean.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getMajorTickMark() {#getMajorTickMark--}
```
public abstract int getMajorTickMark()
```

يمثل نوع العلامة الرئيسية للمحور المحدد. قابل للقراءة والكتابة [TickMarkType](../../com.aspose.slides/tickmarktype).

**القيمة المرجعة:**
int

### setMajorTickMark(int value) {#setMajorTickMark-int-}
```
public abstract void setMajorTickMark(int value)
```

يمثل نوع العلامة الرئيسية للمحور المحدد. قابل للقراءة والكتابة [TickMarkType](../../com.aspose.slides/tickmarktype).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getMinorTickMark() {#getMinorTickMark--}
```
public abstract int getMinorTickMark()
```

يمثل نوع العلامة الفرعية للمحور المحدد. قابل للقراءة والكتابة [TickMarkType](../../com.aspose.slides/tickmarktype).

**القيمة المرجعة:**
int

### setMinorTickMark(int value) {#setMinorTickMark-int-}
```
public abstract void setMinorTickMark(int value)
```

يمثل نوع العلامة الفرعية للمحور المحدد. قابل للقراءة والكتابة [TickMarkType](../../com.aspose.slides/tickmarktype).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getTickLabelPosition() {#getTickLabelPosition--}
```
public abstract int getTickLabelPosition()
```

يمثل موضع تسميات العلامات على المحور المحدد. قابل للقراءة والكتابة [TickLabelPositionType](../../com.aspose.slides/ticklabelpositiontype).

**القيمة المرجعة:**
int

### setTickLabelPosition(int value) {#setTickLabelPosition-int-}
```
public abstract void setTickLabelPosition(int value)
```

يمثل موضع تسميات العلامات على المحور المحدد. قابل للقراءة والكتابة [TickLabelPositionType](../../com.aspose.slides/ticklabelpositiontype).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getMajorUnitScale() {#getMajorUnitScale--}
```
public abstract int getMajorUnitScale()
```

يمثل مقياس الوحدة الرئيسية لمحور التاريخ. قابل للقراءة والكتابة [TimeUnitType](../../com.aspose.slides/timeunittype).

**القيمة المرجعة:**
int

### setMajorUnitScale(int value) {#setMajorUnitScale-int-}
```
public abstract void setMajorUnitScale(int value)
```

يمثل مقياس الوحدة الرئيسية لمحور التاريخ. قابل للقراءة والكتابة [TimeUnitType](../../com.aspose.slides/timeunittype).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getMinorUnitScale() {#getMinorUnitScale--}
```
public abstract int getMinorUnitScale()
```

يمثل مقياس الوحدة الرئيسية لمحور التاريخ. قابل للقراءة والكتابة [TimeUnitType](../../com.aspose.slides/timeunittype).

**القيمة المرجعة:**
int

### setMinorUnitScale(int value) {#setMinorUnitScale-int-}
```
public abstract void setMinorUnitScale(int value)
```

يمثل مقياس الوحدة الرئيسية لمحور التاريخ. قابل للقرابة والكتابة [TimeUnitType](../../com.aspose.slides/timeunittype).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getBaseUnitScale() {#getBaseUnitScale--}
```
public abstract int getBaseUnitScale()
```

يحدد أصغر وحدة زمنية ممثلة على محور التاريخ. قابل للقراءة والكتابة [TimeUnitType](../../com.aspose.slides/timeunittype).

**القيمة المرجعة:**
int

### setBaseUnitScale(int value) {#setBaseUnitScale-int-}
```
public abstract void setBaseUnitScale(int value)
```

يحدد أصغر وحدة زمنية ممثلة على محور التاريخ. قابل للقراءة والكتابة [TimeUnitType](../../com.aspose.slides/timeunittype).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getMinorGridLinesFormat() {#getMinorGridLinesFormat--}
```
public abstract IChartLinesFormat getMinorGridLinesFormat()
```

يمثل تنسيق خطوط الشبكة الفرعية على محور المخطط. للقراءة فقط [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

**القيمة المرجعة:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)

### getMajorGridLinesFormat() {#getMajorGridLinesFormat--}
```
public abstract IChartLinesFormat getMajorGridLinesFormat()
```

يمثل تنسيق خطوط الشبكة الرئيسية على محور المخطط. للقراءة فقط [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

**القيمة المرجعة:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)

### getShowMinorGridLines() {#getShowMinorGridLines--}
```
public abstract boolean getShowMinorGridLines()
```

يمثل ما إذا كانت خطوط الشبكة الفرعية معروضة. للقراءة فقط Boolean.

**القيمة المرجعة:**
boolean

### getShowMajorGridLines() {#getShowMajorGridLines--}
```
public abstract boolean getShowMajorGridLines()
```

يمثل ما إذا كانت خطوط الشبكة الرئيسية معروضة. للقراءة فقط Boolean.

**القيمة المرجعة:**
boolean

### getFormat() {#getFormat--}
```
public abstract IAxisFormat getFormat()
```

يمثل تنسيق المحور. للقراءة فقط [IAxisFormat](../../com.aspose.slides/iaxisformat).

**القيمة المرجعة:**
[IAxisFormat](../../com.aspose.slides/iaxisformat)

### getTitle() {#getTitle--}
```
public abstract IChartTitle getTitle()
```

يحصل على عنوان المحور. للقراءة فقط [IChartTitle](../../com.aspose.slides/icharttitle).

**القيمة المرجعة:**
[IChartTitle](../../com.aspose.slides/icharttitle)

### getCrossType() {#getCrossType--}
```
public abstract int ... ...
```

يمثل نوع التقاطع على المحور المحدد حيث يعبر المحور الآخر. قابل للقراءة والكتابة [CrossesType](../../com.aspose.slides/crossestype).

**القيمة المرجعة:**
int

### setCrossType(int value) {#setCrossType-int-}
```
public abstract void setCrossType(int value)
```

يمثل نوع التقاطع على المحور المحدد حيث يعبر المحور الآخر. قابل للقراءة والكتابة [CrossesType](../../com.aspose.slides/crossestype).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getPosition() {#getPosition--}
```
public abstract int getPosition()
```

يمثل موضع المحور. قابل للقراءة والكتابة [AxisPositionType](../../com.aspose.slides/axispositiontype).

**القيمة المرجعة:**
int

### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```

يمثل موضع المحور. قابل للقراءة والكتابة [AxisPositionType](../../com.aspose.slides/axispositiontype).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### hasTitle() {#hasTitle--}
```
public abstract boolean hasTitle()
```

يحدد ما إذا كان للمحور عنوان مرئي. قابل للقراءة والكتابة Boolean.

**القيمة المرجعة:**
boolean

### setTitle(boolean value) {#setTitle-boolean-}
```
public abstract void setTitle(boolean value)
```

يحدد ما إذا كان للمحور عنوان مرئي. قابل للقراءة والكتابة Boolean.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getNumberFormat() {#getNumberFormat--}
```
public abstract String getNumberFormat()
```

يمثل سلسلة التنسيق لتسميات المحور. قابل للقراءة والكتابة String.

**القيمة المرجعة:**
java.lang.String

### setNumberFormat(String value) {#setNumberFormat-java.lang.String-}
```
public abstract void setNumberFormat(String value)
```

يمثل سلسلة التنسيق لتسميات المحور. قابل للقراءة والكتابة String.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### isNumberFormatLinkedToSource() {#isNumberFormatLinkedToSource--}
```
public abstract boolean isNumberFormatLinkedToSource()
```

يشير إلى ما إذا كان التنسيق مرتبطًا ببيانات المصدر. قابل للقراءة والكتابة Boolean.

**القيمة المرجعة:**
boolean

### setNumberFormatLinkedToSource(boolean value) {#setNumberFormatLinkedToSource-boolean-}
```
public abstract void setNumberFormatLinkedToSource(boolean value)
```

يشير إلى ما إذا كان التنسيق مرتبطًا ببيانات المصدر. قابل للقراءة والكتابة Boolean.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getTickLabelRotationAngle() {#getTickLabelRotationAngle--}
```
public abstract float getTickLabelRotationAngle()
```

يمثل زاوية دوران تسميات العلامات. قابل للقراءة والكتابة Float.

**القيمة المرجعة:**
float

### setTickLabelRotationAngle(float value) {#setTickLabelRotationAngle-float-}
```
public abstract void setTickLabelRotationAngle(float value)
```

يمثل زاوية دوران تسميات العلامات. قابل للقراءة والكتابة Float.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getTickLabelSpacing() {#getTickLabelSpacing--}
```
public abstract long getTickLabelSpacing()
```

يحدد عدد تسميات العلامات التي يجب تخطيها بين كل تسمية مرسومة. قابل للقراءة والكتابة long.

**القيمة المرجعة:**
long

### setTickLabelSpacing(long value) {#setTickLabelSpacing-long-}
```
public abstract void setTickLabelSpacing(long value)
```

يحدد عدد تسميات العلامات التي يجب تخطيها بين كل تسمية مرسومة. قابل للقراءة والكتابة long.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | long |  |

### isAutomaticTickLabelSpacing() {#isAutomaticTickLabelSpacing--}
```
public abstract boolean isAutomaticTickLabelSpacing()
```

يحدد قيمة تباعد تسميات العلامات التلقائي. إذا كان false: يستخدم خاصية TickLabelSpacing. قابل للقراءة والكتابة Boolean.

**القيمة المرجعة:**
boolean

### setAutomaticTickLabelSpacing(boolean value) {#setAutomaticTickLabelSpacing-boolean-}
```
public abstract void setAutomaticTickLabelSpacing(boolean value)
```

يحدد قيمة تباعد تسميات العلامات التلقائي. إذا كان false: يستخدم خاصية TickLabelSpacing. قابل للقراءة والكتابة Boolean.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getTickMarksSpacing() {#getTickMarksSpacing--}
```
public abstract long getTickMarksSpacing()
```

يحدد عدد علامات العظام التي يجب تخطيها قبل رسم العلامة التالية. يُطبق على محور الفئة أو السلسلة. قابل للقراءة والكتابة int.

**القيمة المرجعة:**
long

### setTickMarksSpacing(long value) {#setTickMarksSpacing-long-}
```
public abstract void setTickMarksSpacing(long value)
```

يحدد عدد علامات العظام التي يجب تخطيها قبل رسم العلامة التالية. يُطبق على محور الفئة أو السلسلة. قابل للقراءة والكتابة int.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | long |  |

### isAutomaticTickMarksSpacing() {#isAutomaticTickMarksSpacing--}
```
public abstract boolean isAutomaticTickMarksSpacing()
```

يحدد قيمة تباعد علامات العظام التلقائي. إذا كان false: يستخدم خاصية TickMarksSpacing. قابل للقراءة والكتابة Boolean.

**القيمة المرجعة:**
boolean

### setAutomaticTickMarksSpacing(boolean value) {#setAutomaticTickMarksSpacing-boolean-}
```
public abstract void setAutomaticTickMarksSpacing(boolean value)
```

يحدد قيمة تباعد علامات العظام التلقائي. إذا كان false: يستخدم خاصية TickMarksSpacing. قابل للقراءة والكتابة Boolean.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getLabelOffset() {#getLabelOffset--}
```
public abstract int getLabelOffset()
```

يحدد المسافة بين التسميات والمحور. يُطبق على محور الفئة أو التاريخ. يجب أن تكون القيمة بين 0% و 1000%. قابل للقراءة والكتابة int.

**القيمة المرجعة:**
int

### setLabelOffset(int value) {#setLabelOffset-int-}
```
public abstract void setLabelOffset(int value)
```

يحدد المسافة بين التسميات والمحور. يُطبق على محور الفئة أو التاريخ. يجب أن تكون القيمة بين 0% و 1000%. قابل للقراءة والكتابة int.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getCategoryAxisType() {#getCategoryAxisType--}
```
public abstract int getCategoryAxisType()
```

يحدد نوع محور الفئة. قابل للقراءة والكتابة [CategoryAxisType](../../com.aspose.slides/categoryaxistype)(\#getCategoryAxisType.getCategoryAxisType/\#setCategoryAxisType(int).setCategoryAxisType(int)).

**القيمة المرجعة:**
int

### setCategoryAxisType(int value) {#setCategoryAxisType-int-}
```
public abstract void setCategoryAxisType(int value)
```

يحدد نوع محور الفئة. قابل للقراءة والكتابة [CategoryAxisType](../../com.aspose.slides/categoryaxistype)(\#getCategoryAxisType.getCategoryAxisType/\#setCategoryAxisType(int).setCategoryAxisType(int)).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### setCategoryAxisTypeAutomatically() {#setCategoryAxisTypeAutomatically--}
```
public abstract void setCategoryAxisTypeAutomatically()
```

يضبط خاصية IAxis.CategoryAxisType بقيمة يتم تحديدها تلقائيًا بناءً على بيانات المحور.

### getAggregationType() {#getAggregationType--}
```
public abstract int getAggregationType()
```

يمثل نوع التجميع لمحور الفئة (التجميع إلى صناديق). يُطبق على الفئة. يستخدم مع سلسلة Histogram أو HistogramPareto فقط.

**القيمة المرجعة:**
int

### setAggregationType(int value) {#setAggregationType-int-}
```
public abstract void setAggregationType(int value)
```

يمثل نوع التجميع لمحور الفئة (التجميع إلى صناديق). يُطبق على الفئة. يستخدم مع سلسلة Histogram أو HistogramPareto فقط.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getBinWidth() {#getBinWidth--}
```
public abstract double getBinWidth()
```

يحدد عرض الصندوق عندما تكون قيمة خاصية AggregationType مضبوطة على AxisAggregationType.ByBinWidth. يُطبق على محاور الفئة. يستخدم مع سلسلة Histogram أو HistogramPareto فقط.

**القيمة المرجعة:**
double

### setBinWidth(double value) {#setBinWidth-double-}
```
public abstract void setBinWidth(double value)
```

يحدد عرض الصندوق عندما تكون قيمة خاصية AggregationType مضبوطة على AxisAggregationType.ByBinWidth. يُطبق على محاور الفئة. يستخدم مع سلسلة Histogram أو HistogramPareto فقط.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | double |  |

### getNumberOfBins() {#getNumberOfBins--}
```
public abstract long getNumberOfBins()
```

يحدد عدد الصناديق عندما تكون قيمة خاصية AggregationType مضبوطة على AxisAggregationType.ByNumberOfBins. يُطبق على محاور الفئة. يستخدم مع سلسلة Histogram أو HistogramPareto فقط.

**القيمة المرجعة:**
long

### setNumberOfBins(long value) {#setNumberOfBins-long-}
```
public abstract void setNumberOfBins(long value)
```

يحدد عدد الصناديق عندما تكون قيمة خاصية AggregationType مضبوطة على AxisAggregationType.ByNumberOfBins. يُطبق على محاور الفئة. يستخدم مع سلسلة Histogram أو HistogramPareto فقط.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | long |  |

### isOverflowBin() {#isOverflowBin--}
```
public abstract boolean isOverflowBin()
```

يحدد ما إذا تم تطبيق صندوق الفائض. استخدم IsAutomaticOverflowBin و OverflowBin لضبط قيمة صندوق الفائض.

**القيمة المرجعة:**
boolean

### setOverflowBin(boolean value) {#setOverflowBin-boolean-}
```
public abstract void setOverflowBin(boolean value)
```

يحدد ما إذا تم تطبيق صندوق الفائض. استخدم IsAutomaticOverflowBin و OverflowBin لضبط قيمة صندوق الفائض.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticOverflowBin() {#isAutomaticOverflowBin--}
```
public abstract boolean isAutomaticOverflowBin()
```

يحدد قيمة صندوق الفائض التلقائي. إذا كان false: يستخدم خاصية OverflowBin.

**القيمة المرجعة:**
boolean

### setAutomaticOverflowBin(boolean value) {#setAutomaticOverflowBin-boolean-}
```
public abstract void setAutomaticOverflowBin(boolean value)
```

يحدد قيمة صندوق الفائض التلقائي. إذا كان false: يستخدم خاصية OverflowBin.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getOverflowBin() {#getOverflowBin--}
```
public abstract double getOverflowBin()
```

يحدد قيمة مخصصة لصندوق الفائض. يُطبق عندما تكون خاصية IsAutomaticOverflowBin مضبوطة على false وخاصية IsOverflowBin تساوي true.

**القيمة المرجعة:**
double

### setOverflowBin(double value) {#setOverflowBin-double-}
```
public abstract void setOverflowBin(double value)
```

يحدد قيمة مخصصة لصندوق الفائض. يُطبق عندما تكون خاصية IsAutomaticOverflowBin مضبوطة على false وخاصية IsOverflowBin تساوي true.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | double |  |

### isUnderflowBin() {#isUnderflowBin--}
```
public abstract boolean isUnderflowBin()
```

يحدد ما إذا تم تطبيق صندوق النقص. استخدم IsAutomaticUnderflowBin و UnderflowBin لضبط قيمة صندوق النقص.

**القيمة المرجعة:**
boolean

### setUnderflowBin(boolean value) {#setUnderflowBin-boolean-}
```
public abstract void setUnderflowBin(boolean value)
```

يحدد ما إذا تم تطبيق صندوق النقص. استخدم IsAutomaticUnderflowBin و UnderflowBin لضبط قيمة صندوق النقص.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticUnderflowBin() {#isAutomaticUnderflowBin--}
```
public abstract boolean isAutomaticUnderflowBin()
```

يحدد قيمة صندوق النقص التلقائي. إذا كان false: يستخدم خاصية UnderflowBin.

**القيمة المرجعة:**
boolean

### setAutomaticUnderflowBin(boolean value) {#setAutomaticUnderflowBin-boolean-}
```
public abstract void setAutomaticUnderflowBin(boolean value)
```

يحدد قيمة صندوق النقص التلقائي. إذا كان false: يستخدم خاصية UnderflowBin.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getUnderflowBin() {#getUnderflowBin--}
```
public abstract double getUnderflowBin()
```

يحدد قيمة مخصصة لصندوق النقص. يُطبق عندما تكون خاصية IsAutomaticUnderflowBin مضبوطة على false وخاصية IsUnderflowBin تساوي true.

**القيمة المرجعة:**
double

### setUnderflowBin(double value) {#setUnderflowBin-double-}
```
public abstract void setUnderflowBin(double value)
```

يحدد قيمة مخصصة لصندوق النقص. يُطبق عندما تكون خاصية IsAutomaticUnderflowBin مضبوطة على false وخاصية IsUnderflowBin تساوي true.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | double |  |