---
title: IAxis
second_title: مرجع API Aspose.Slides for Java
description: يغلف الكائن الذي يمثل محور الرسم البياني.
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
| [getAxisBetweenCategories()](#getAxisBetweenCategories--) | يمثل ما إذا كان محور القيمة يعبر محور الفئة بين الفئات. |
| [setAxisBetweenCategories(boolean value)](#setAxisBetweenCategories-boolean-) | يمثل ما إذا كان محور القيمة يعبر محور الفئة بين الفئات. |
| [getCrossAt()](#getCrossAt--) | يمثل النقطة على المحور التي يعبرها المحور المتعامد. |
| [setCrossAt(float value)](#setCrossAt-float-) | يمثل النقطة على المحور التي يعبرها المحور المتعامد. |
| [getDisplayUnit()](#getDisplayUnit--) | يحدد قيمة التحجيم للوحدات المعروضة لمحور القيمة. |
| [setDisplayUnit(int value)](#setDisplayUnit-int-) | يحدد قيمة التحجيم للوحدات المعروضة لمحور القيمة. |
| [getActualMaxValue()](#getActualMaxValue--) | يحدد القيمة القصوى الفعلية على المحور. |
| [getActualMinValue()](#getActualMinValue--) | يحدد القيمة الدنيا الفعلية على المحور. |
| [getActualMajorUnit()](#getActualMajorUnit--) | يحدد الوحدة الرئيسية الفعلية للمحور. |
| [getActualMinorUnit()](#getActualMinorUnit--) | يحدد الوحدة الثانوية الفعلية للمحور. |
| [getActualMajorUnitScale()](#getActualMajorUnitScale--) | يحدد مقياس الوحدة الرئيسية الفعلية للمحور. |
| [getActualMinorUnitScale()](#getActualMinorUnitScale--) | يحدد مقياس الوحدة الثانوية الفعلية للمحور. |
| [isAutomaticMaxValue()](#isAutomaticMaxValue--) | يشير إلى ما إذا كانت القيمة القصوى تُعيّن تلقائيًا. |
| [setAutomaticMaxValue(boolean value)](#setAutomaticMaxValue-boolean-) | يشير إلى ما إذا كانت القيمة القصوى تُعيّن تلقائيًا. |
| [getMaxValue()](#getMaxValue--) | يمثل القيمة القصوى على محور القيمة. |
| [setMaxValue(double value)](#setMaxValue-double-) | يمثل القيمة القصوى على محور القيمة. |
| [getMinorUnit()](#getMinorUnit--) | يمثل الوحدات الثانوية للمحور الزمني أو محور القيمة. |
| [setMinorUnit(double value)](#setMinorUnit-double-) | يمثل الوحدات الثانوية للمحور الزمني أو محور القيمة. |
| [isAutomaticMinorUnit()](#isAutomaticMinorUnit--) | يشير إلى ما إذا كانت الوحدة الثانوية للمحور تُعيّن تلقائيًا. |
| [setAutomaticMinorUnit(boolean value)](#setAutomaticMinorUnit-boolean-) | يشير إلى ما إذا كانت الوحدة الثانوية للمحور تُعيّن تلقائيًا. |
| [getMajorUnit()](#getMajorUnit--) | يمثل الوحدات الرئيسية للمحور الزمني أو محور القيمة. |
| [setMajorUnit(double value)](#setMajorUnit-double-) | يمثل الوحدات الرئيسية للمحور الزمني أو محور القيمة. |
| [isAutomaticMajorUnit()](#isAutomaticMajorUnit--) | يشير إلى ما إذا كانت الوحدة الرئيسية للمحور تُعيّن تلقائيًا. |
| [setAutomaticMajorUnit(boolean value)](#setAutomaticMajorUnit-boolean-) | يشير إلى ما إذا كانت الوحدة الرئيسية للمحور تُعيّن تلقائيًا. |
| [isAutomaticMinValue()](#isAutomaticMinValue--) | يشير إلى ما إذا كانت القيمة الدنيا تُعيّن تلقائيًا. |
| [setAutomaticMinValue(boolean value)](#setAutomaticMinValue-boolean-) | يشير إلى ما إذا كانت القيمة الدنيا تُعيّن تلقائيًا. |
| [getMinValue()](#getMinValue--) | يمثل القيمة الدنيا على محور القيمة. |
| [setMinValue(double value)](#setMinValue-double-) | يمثل القيمة الدنيا على محور القيمة. |
| [isLogarithmic()](#isLogarithmic--) | يمثل ما إذا كان نوع مقياس محور القيمة لوغاريتميًا أم لا. |
| [setLogarithmic(boolean value)](#setLogarithmic-boolean-) | يمثل ما إذا كان نوع مقياس محور القيمة لوغاريتميًا أم لا. |
| [getLogBase()](#getLogBase--) | يمثل الأساس اللوغاريتمي. |
| [setLogBase(double value)](#setLogBase-double-) | يمثل الأساس اللوغاريتمي. |
| [isPlotOrderReversed()](#isPlotOrderReversed--) | يمثل ما إذا كان برنامج MS PowerPoint يرسم نقاط البيانات من الأخير إلى الأول. |
| [setPlotOrderReversed(boolean value)](#setPlotOrderReversed-boolean-) | يمثل ما إذا كان برنامج MS PowerPoint يرسم نقاط البيانات من الأخير إلى الأول. |
| [isVisible()](#isVisible--) | يمثل ما إذا كان المحور مرئيًا. |
| [setVisible(boolean value)](#setVisible-boolean-) | يمثل ما إذا كان المحور مرئيًا. |
| [getMajorTickMark()](#getMajorTickMark--) | يمثل نوع العلامة الرئيسية للمحور المحدد. |
| [setMajorTickMark(int value)](#setMajorTickMark-int-) | يمثل نوع العلامة الرئيسية للمحور المحدد. |
| [getMinorTickMark()](#getMinorTickMark--) | يمثل نوع العلامة الثانوية للمحور المحدد. |
| [setMinorTickMark(int value)](#setMinorTickMark-int-) | يمثل نوع العلامة الثانوية للمحور المحدد. |
| [getTickLabelPosition()](#getTickLabelPosition--) | يمثل موضع تسميات العلامات على المحور المحدد. |
| [setTickLabelPosition(int value)](#setTickLabelPosition-int-) | يمثل موضع تسميات العلامات على المحور المحدد. |
| [getMajorUnitScale()](#getMajorUnitScale--) | يمثل مقياس الوحدة الرئيسية للمحور الزمني. |
| [setMajorUnitScale(int value)](#setMajorUnitScale-int-) | يمثل مقياس الوحدة الرئيسية للمحور الزمني. |
| [getMinorUnitScale()](#getMinorUnitScale--) | يمثل مقياس الوحدة الرئيسية للمحور الزمني. |
| [setMinorUnitScale(int value)](#setMinorUnitScale-int-) | يمثل مقياس الوحدة الرئيسية للمحور الزمني. |
| [getBaseUnitScale()](#getBaseUnitScale--) | يحدد أصغر وحدة زمنية ممثلة على المحور الزمني. |
| [setBaseUnitScale(int value)](#setBaseUnitScale-int-) | يحدد أصغر وحدة زمنية ممثلة على المحور الزمني. |
| [getMinorGridLinesFormat()](#getMinorGridLinesFormat--) | يمثل تنسيق الخطوط الشبكية الثانوية على محور المخطط. |
| [getMajorGridLinesFormat()](#getMajorGridLinesFormat--) | يمثل تنسيق الخطوط الشبكية الرئيسية على محور المخطط. |
| [getShowMinorGridLines()](#getShowMinorGridLines--) | يمثل ما إذا كانت الخطوط الشبكية الثانوية مُظهَرة. |
| [getShowMajorGridLines()](#getShowMajorGridLines--) | يمثل ما إذا كانت الخطوط الشبكية الرئيسية مُظهَرة. |
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
| [getTickLabelRotationAngle()](#getTickLabelRotationAngle--) | يمثل زاوية دوران تسميات العلامات قراءة/كتابة float. |
| [setTickLabelRotationAngle(float value)](#setTickLabelRotationAngle-float-) | يمثل زاوية دوران تسميات العلامات قراءة/كتابة float. |
| [getTickLabelSpacing()](#getTickLabelSpacing--) | يحدد عدد تسميات العلامات التي تُجتاز بين كل تسمية تُرسم. |
| [setTickLabelSpacing(long value)](#setTickLabelSpacing-long-) | يحدد عدد تسميات العلامات التي تُجتاز بين كل تسمية تُرسم. |
| [isAutomaticTickLabelSpacing()](#isAutomaticTickLabelSpacing--) | يحدد قيمة التباعد التلقائي لتسميات العلامات. |
| [setAutomaticTickLabelSpacing(boolean value)](#setAutomaticTickLabelSpacing-boolean-) | يحدد قيمة التباعد التلقائي لتسميات العلامات. |
| [getTickMarksSpacing()](#getTickMarksSpacing--) | يحدد عدد العلامات التي تُجتاز قبل رسم العلامة التالية. |
| [setTickMarksSpacing(long value)](#setTickMarksSpacing-long-) | يحدد عدد العلامات التي تُجتاز قبل رسم العلامة التالية. |
| [isAutomaticTickMarksSpacing()](#isAutomaticTickMarksSpacing--) | يحدد قيمة التباعد التلقائي للعلامات. |
| [setAutomaticTickMarksSpacing(boolean value)](#setAutomaticTickMarksSpacing-boolean-) | يحدد قيمة التباعد التلقائي للعلامات. |
| [getLabelOffset()](#getLabelOffset--) | يحدد المسافة بين التسميات والمحور. |
| [setLabelOffset(int value)](#setLabelOffset-int-) | يحدد المسافة بين التسميات والمحور. |
| [getCategoryAxisType()](#getCategoryAxisType--) | يحدد نوع محور الفئة. |
| [setCategoryAxisType(int value)](#setCategoryAxisType-int-) | يحدد نوع محور الفئة. |
| [setCategoryAxisTypeAutomatically()](#setCategoryAxisTypeAutomatically--) | يضبط خاصية IAxis.CategoryAxisType بقيمة تُحدد تلقائيًا بناءً على بيانات المحور. |
| [getAggregationType()](#getAggregationType--) | يمثل نوع التجميع لمحور الفئة (تقسيم إلى فئات). |
| [setAggregationType(int value)](#setAggregationType-int-) | يمثل نوع التجميع لمحور الفئة (تقسيم إلى فئات). |
| [getBinWidth()](#getBinWidth--) | يحدد عرض الحاوية عندما تكون قيمة خاصية AggregationType مضبوطة على AxisAggregationType.ByBinWidth. |
| [setBinWidth(double value)](#setBinWidth-double-) | يحدد عرض الحاوية عندما تكون قيمة خاصية AggregationType مضبوطة على AxisAggregationType.ByBinWidth. |
| [getNumberOfBins()](#getNumberOfBins--) | يحدد عدد الحاويات عندما تكون قيمة خاصية AggregationType مضبوطة على AxisAggregationType.ByNumberOfBins. |
| [setNumberOfBins(long value)](#setNumberOfBins-long-) | يحدد عدد الحاويات عندما تكون قيمة خاصية AggregationType مضبوطة على AxisAggregationType.ByNumberOfBins. |
| [isOverflowBin()](#isOverflowBin--) | يمثل ما إذا تم تطبيق حاوية الفائض. |
| [setOverflowBin(boolean value)](#setOverflowBin-boolean-) | يمثل ما إذا تم تطبيق حاوية الفائض. |
| [isAutomaticOverflowBin()](#isAutomaticOverflowBin--) | يحدد قيمة حاوية الفائض التلقائية. |
| [setAutomaticOverflowBin(boolean value)](#setAutomaticOverflowBin-boolean-) | يحدد قيمة حاوية الفائض التلقائية. |
| [getOverflowBin()](#getOverflowBin--) | يحدد قيمة مخصصة لحاوية الفائض. |
| [setOverflowBin(double value)](#setOverflowBin-double-) | يحدد قيمة مخصصة لحاوية الفائض. |
| [isUnderflowBin()](#isUnderflowBin--) | يمثل ما إذا تم تطبيق حاوية النقص. |
| [setUnderflowBin(boolean value)](#setUnderflowBin-boolean-) | يمثل ما إذا تم تطبيق حاوية النقص. |
| [isAutomaticUnderflowBin()](#isAutomaticUnderflowBin--) | يحدد قيمة حاوية النقص التلقائية. |
| [setAutomaticUnderflowBin(boolean value)](#setAutomaticUnderflowBin-boolean-) | يحدد قيمة حاوية النقص التلقائية. |
| [getUnderflowBin()](#getUnderflowBin--) | يحدد قيمة مخصصة لحاوية النقص. |
| [setUnderflowBin(double value)](#setUnderflowBin-double-) | يحدد قيمة مخصصة لحاوية النقص. |

### getAxisBetweenCategories() {#getAxisBetweenCategories--}
```
public abstract boolean getAxisBetweenCategories()
```

يمثل ما إذا كان محور القيمة يعبر محور الفئة بين الفئات. هذه الخاصية تنطبق فقط على محاور الفئة، ولا تنطبق على المخططات ثلاثية الأبعاد. قراءة/كتابة boolean.

**القيمة المرجعة:**
boolean

### setAxisBetweenCategories(boolean value) {#setAxisBetweenCategories-boolean-}
```
public abstract void setAxisBetweenCategories(boolean value)
```

يمثل ما إذا كان محور القيمة يعبر محور الفئة بين الفئات. هذه الخاصية تنطبق فقط على محاور الفئة، ولا تنطبق على المخططات ثلاثية الأبعاد. قراءة/كتابة boolean.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getCrossAt() {#getCrossAt--}
```
public abstract float getCrossAt()
```

يمثل النقطة على المحور التي يعبرها المحور المتعامد. قراءة/كتابة float.

**القيمة المرجية:**
float

### setCrossAt(float value) {#setCrossAt-float-}
```
public abstract void setCrossAt(float value)
```

يمثل النقطة على المحور التي يعبرها المحور المتعامد. قراءة/كتابة float.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getDisplayUnit() {#getDisplayUnit--}
```
public abstract int getDisplayUnit()
```

يحدد قيمة التحجيم للوحدات المعروضة لمحور القيمة. قراءة/كتابة [DisplayUnitType](../../com.aspose.slides/displayunittype).

**القيمة المرجعة:**
int

### setDisplayUnit(int value) {#setDisplayUnit-int-}
```
public abstract void setDisplayUnit(int value)
```

يحدد قيمة التحجيم للوحدات المعروضة لمحور القيمة. قراءة/كتابة [DisplayUnitType](../../com.aspose.slides/displayunittype).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getActualMaxValue() {#getActualMaxValue--}
```
public abstract double getActualMaxValue()
```

يحدد القيمة القصوى الفعلية على المحور. استدعِ الطريقة IChart.ValidateChartLayout() مسبقًا للحصول على القيمة الفعلية.

**القيمة المرجعة:**
double

### getActualMinValue() {#getActualMinValue--}
```
public abstract double getActualMinValue()
```

يحدد القيمة الدنيا الفعلية على المحور. استدعِ الطريقة IChart.ValidateChartLayout() مسبقًا للحصول على القيمة الفعلية.

**القيمة المرجعة:**
double

### getActualMajorUnit() {#getActualMajorUnit--}
```
public abstract double getActualMajorUnit()
```

يحدد الوحدة الرئيسية الفعلية للمحور. استدعِ الطريقة IChart.ValidateChartLayout() مسبقًا للحصول على القيمة الفعلية.

**القيمة المرجعة:**
double

### getActualMinorUnit() {#getActualMinorUnit--}
```
public abstract double getActualMinorUnit()
```

يحدد الوحدة الثانوية الفعلية للمحور. استدعِ الطريقة IChart.ValidateChartLayout() مسبقًا للحصول على القيمة الفعلية.

**القيمة المرجعة:**
double

### getActualMajorUnitScale() {#getActualMajorUnitScale--}
```
public abstract int getActualMajorUnitScale()
```

يحدد مقياس الوحدة الرئيسية الفعلية للمحور. استدعِ الطريقة IChart.ValidateChartLayout() مسبقًا للحصول على القيمة الفعلية.

**القيمة المرجعة:**
int

### getActualMinorUnitScale() {#getActualMinorUnitScale--}
```
public abstract int getActualMinorUnitScale()
```

يحدد مقياس الوحدة الثانوية الفعلية للمحور. استدعِ الطريقة IChart.ValidateChartLayout() مسبقًا للحصول على القيمة الفعلية.

**القيمة المرجعة:**
int

### isAutomaticMaxValue() {#isAutomaticMaxValue--}
```
public abstract boolean isAutomaticMaxValue()
```

يشير إلى ما إذا كانت القيمة القصوى تُعيّن تلقائيًا. قراءة/كتابة boolean.

**القيمة المرجعة:**
boolean

### setAutomaticMaxValue(boolean value) {#setAutomaticMaxValue-boolean-}
```
public abstract void setAutomaticMaxValue(boolean value)
```

يشير إلى ما إذا كانت القيمة القصوى تُعيّن تلقائيًا. قراءة/كتابة boolean.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getMaxValue() {#getMaxValue--}
```
public abstract double getMaxValue()
```

يمثل القيمة القصوى على محور القيمة. قراءة/كتابة double.

**القيمة المرجعة:**
double

### setMaxValue(double value) {#setMaxValue-double-}
```
public abstract void setMaxValue(double value)
```

يمثل القيمة القصوى على محور القيمة. قراءة/كتابة double.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | double |  |

### getMinorUnit() {#getMinorUnit--}
```
public abstract double getMinorUnit()
```

يمثل الوحدات الثانوية للمحور الزمني أو محور القيمة. قراءة/كتابة double.

**القيمة المرجعة:**
double

### setMinorUnit(double value) {#setMinorUnit-double-}
```
public abstract void setMinorUnit(double value)
```

يمثل الوحدات الثانوية للمحور الزمني أو محور القيمة. قراءة/كتابة double.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | double |  |

### isAutomaticMinorUnit() {#isAutomaticMinorUnit--}
```
public abstract boolean isAutomaticMinorUnit()
```

يشير إلى ما إذا كانت الوحدة الثانوية للمحور تُعيّن تلقائيًا. قراءة/كتابة boolean.

**القيمة المرجعة:**
boolean

### setAutomaticMinorUnit(boolean value) {#setAutomaticMinorUnit-boolean-}
```
public abstract void setAutomaticMinorUnit(boolean value)
```

يشير إلى ما إذا كانت الوحدة الثانوية للمحور تُعيّن تلقائيًا. قراءة/كتابة boolean.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getMajorUnit() {#getMajorUnit--}
```
public abstract double getMajorUnit()
```

يمثل الوحدات الرئيسية للمحور الزمني أو محور القيمة. قراءة/كتابة double.

**القيمة المرجعة:**
double

### setMajorUnit(double value) {#setMajorUnit-double-}
```
public abstract void setMajorUnit(double value)
```

يمثل الوحدات الرئيسية للمحور الزمني أو محور القيمة. قراءة/كتابة double.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | double |  |

### isAutomaticMajorUnit() {#isAutomaticMajorUnit--}
```
public abstract boolean isAutomaticMajorUnit()
```

يشير إلى ما إذا كانت الوحدة الرئيسية للمحور تُعيّن تلقائيًا. قراءة/كتابة boolean.

**القيمة المرجعة:**
boolean
### setAutomaticMajorUnit(boolean value) {#setAutomaticMajorUnit-boolean-}
```
public abstract void setAutomaticMajorUnit(boolean value)
```

يشير إلى ما إذا كانت الوحدة الرئيسية للمحور يتم تعيينها تلقائيًا. قابل للقراءة/الكتابة boolean.

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticMinValue() {#isAutomaticMinValue--}
```
public abstract boolean isAutomaticMinValue()
```

يشير إلى ما إذا كانت القيمة الدنيا يتم تعيينها تلقائيًا. قابل للقراءة/الكتابة boolean.

**القيمة المرجعة:**
boolean
### setAutomaticMinValue(boolean value) {#setAutomaticMinValue-boolean-}
```
public abstract void setAutomaticMinValue(boolean value)
```

يشير إلى ما إذا كانت القيمة الدنيا يتم تعيينها تلقائيًا. قابل للقراءة/الكتابة boolean.

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getMinValue() {#getMinValue--}
```
public abstract double getMinValue()
```

يمثل القيمة الدنيا على محور القيم. قابل للقراءة/الكتابة double.

**القيمة المرجعة:**
double
### setMinValue(double value) {#setMinValue-double-}
```
public abstract void setMinValue(double value)
```

يمثل القيمة الدنيا على محور القيم. قابل للقراءة/الكتابة double.

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### isLogarithmic() {#isLogarithmic--}
```
public abstract boolean isLogarithmic()
```

يمثل ما إذا كان نوع مقياس محور القيم لوغاريتميًا أم لا. قابل للقراءة/الكتابة boolean.

**القيمة المرجعة:**
boolean
### setLogarithmic(boolean value) {#setLogarithmic-boolean-}
```
public abstract void setLogarithmic(boolean value)
```

يمثل ما إذا كان نوع مقياس محور القيم لوغاريتميًا أم لا. قابل للقراءة/الكتابة boolean.

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getLogBase() {#getLogBase--}
```
public abstract double getLogBase()
```

يمثل القاعدة اللوغاريتمية. القيمة الافتراضية هي 10. قابل للقراءة/الكتابة double.

**القيمة المرجعة:**
double
### setLogBase(double value) {#setLogBase-double-}
```
public abstract void setLogBase(double value)
```

يمثل القاعدة اللوغاريتمية. القيمة الافتراضية هي 10. قابل للقراءة/الكتابة double.

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### isPlotOrderReversed() {#isPlotOrderReversed--}
```
public abstract boolean isPlotOrderReversed()
```

يمثل ما إذا كان PowerPoint يرسم نقاط البيانات من الأخير إلى الأول. قابل للقراءة/الكتابة boolean.

**القيمة المرجعة:**
boolean
### setPlotOrderReversed(boolean value) {#setPlotOrderReversed-boolean-}
```
public abstract void setPlotOrderReversed(boolean value)
```

يمثل ما إذا كان PowerPoint يرسم نقاط البيانات من الأخير إلى الأول. قابل للقراءة/الكتابة boolean.

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```

يمثل ما إذا كان المحور مرئيًا. قابل للقراءة/الكتابة boolean.

**القيمة المرجعة:**
boolean
### setVisible(boolean value) {#setVisible-boolean-}
```
public abstract void setVisible(boolean value)
```

يمثل ما إذا كان المحور مرئيًا. قابل للقراءة/الكتابة boolean.

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getMajorTickMark() {#getMajorTickMark--}
```
public abstract int getMajorTickMark()
```

يمثل نوع علامة الفاصل الرئيسية للمحور المحدد. قابل للقراءة/الكتابة [TickMarkType](../../com.aspose.slides/tickmarktype).

**القيمة المرجعة:**
int
### setMajorTickMark(int value) {#setMajorTickMark-int-}
```
public abstract void setMajorTickMark(int value)
```

يمثل نوع علامة الفاصل الرئيسية للمحور المحدد. قابل للقراءة/الكتابة [TickMarkType](../../com.aspose.slides/tickmarktype).

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getMinorTickMark() {#getMinorTickMark--}
```
public abstract int getMinorTickMark()
```

يمثل نوع علامة الفاصل الفرعية للمحور المحدد. قابل للقراءة/الكتابة [TickMarkType](../../com.aspose.slides/tickmarktype).

**القيمة المرجعة:**
int
### setMinorTickMark(int value) {#setMinorTickMark-int-}
```
public abstract void setMinorTickMark(int value)
```

يمثل نوع علامة الفاصل الفرعية للمحور المحدد. قابل للقراءة/الكتابة [TickMarkType](../../com.aspose.slides/tickmarktype).

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getTickLabelPosition() {#getTickLabelPosition--}
```
public abstract int getTickLabelPosition()
```

يمثل موضع تسميات علامات الفواصل على المحور المحدد. قابل للقراءة/الكتابة [TickLabelPositionType](../../com.aspose.slides/ticklabelpositiontype).

**القيمة المرجعة:**
int
### setTickLabelPosition(int value) {#setTickLabelPosition-int-}
```
public abstract void setTickLabelPosition(int value)
```

يمثل موضع تسميات علامات الفواصل على المحور المحدد. قابل للقراءة/الكتابة [TickLabelPositionType](../../com.aspose.slides/ticklabelpositiontype).

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getMajorUnitScale() {#getMajorUnitScale--}
```
public abstract int getMajorUnitScale()
```

يمثل مقياس الوحدة الرئيسية لمحور التاريخ. قابل للقراءة/الكتابة [TimeUnitType](../../com.aspose.slides/timeunittype).

**القيمة المرجعة:**
int
### setMajorUnitScale(int value) {#setMajorUnitScale-int-}
```
public abstract void setMajorUnitScale(int value)
```

يمثل مقياس الوحدة الرئيسية لمحور التاريخ. قابل للقراءة/الكتابة [TimeUnitType](../../com.aspose.slides/timeunittype).

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getMinorUnitScale() {#getMinorUnitScale--}
```
public abstract int getMinorUnitScale()
```

يمثل مقياس الوحدة الرئيسية لمحور التاريخ. قابل للقراءة/الكتابة [TimeUnitType](../../com.aspose.slides/timeunittype).

**القيمة المرجعة:**
int
### setMinorUnitScale(int value) {#setMinorUnitScale-int-}
```
public abstract void setMinorUnitScale(int value)
```

يمثل مقياس الوحدة الرئيسية لمحور التاريخ. قابل للقراءة/الكتابة [TimeUnitType](../../com.aspose.slides/timeunittype).

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getBaseUnitScale() {#getBaseUnitScale--}
```
public abstract int getBaseUnitScale()
```

يحدد أصغر وحدة زمنية يتم تمثيلها على محور التاريخ. قابل للقراءة/الكتابة [TimeUnitType](../../com.aspose.slides/timeunittype).

**القيمة المرجعة:**
int
### setBaseUnitScale(int value) {#setBaseUnitScale-int-}
```
public abstract void setBaseUnitScale(int value)
```

يحدد أصغر وحدة زمنية يتم تمثيلها على محور التاريخ. قابل للقراءة/الكتابة [TimeUnitType](../../com.aspose.slides/timeunittype).

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getMinorGridLinesFormat() {#getMinorGridLinesFormat--}
```
public abstract IChartLinesFormat getMinorGridLinesFormat()
```

يمثل تنسيق خطوط الشبكة الفرعية على محور المخطط. قابل للقراءة فقط [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

**القيمة المرجعة:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)
### getMajorGridLinesFormat() {#getMajorGridLinesFormat--}
```
public abstract IChartLinesFormat getMajorGridLinesFormat()
```

يمثل تنسيق خطوط الشبكة الرئيسية على محور المخطط. قابل للقراءة فقط [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

**القيمة المرجعة:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)
### getShowMinorGridLines() {#getShowMinorGridLines--}
```
public abstract boolean getShowMinorGridLines()
```

يمثل ما إذا كانت خطوط الشبكة الفرعية معروضة. قابل للقراءة فقط boolean.

**القيمة المرجعة:**
boolean
### getShowMajorGridLines() {#getShowMajorGridLines--}
```
public abstract boolean getShowMajorGridLines()
```

يمثل ما إذا كانت خطوط الشبكة الرئيسية معروضة. قابل للقراءة فقط boolean.

**القيمة المرجعة:**
boolean
### getFormat() {#getFormat--}
```
public abstract IAxisFormat getFormat()
```

يمثل تنسيق المحور. قابل للقراءة فقط [IAxisFormat](../../com.aspose.slides/iaxisformat).

**القيمة المرجعة:**
[IAxisFormat](../../com.aspose.slides/iaxisformat)
### getTitle() {#getTitle--}
```
public abstract IChartTitle getTitle()
```

يحصل على عنوان المحور. قابل للقراءة فقط [IChartTitle](../../com.aspose.slides/icharttitle).

**القيمة المرجعة:**
[IChartTitle](../../com.aspose.slides/icharttitle)
### getCrossType() {#getCrossType--}
```
public abstract int getCrossType()
```

يمثل نوع التقاطع على المحور المحدد حيث يعبر المحور الآخر. قابل للقراءة/الكتابة [CrossesType](../../com.aspose.slides/crossestype).

**القيمة المرجعة:**
int
### setCrossType(int value) {#setCrossType-int-}
```
public abstract void setCrossType(int value)
```

يمثل نوع التقاطع على المحور المحدد حيث يعبر المحور الآخر. قابل للقراءة/الكتابة [CrossesType](../../com.aspose.slides/crossestype).

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getPosition() {#getPosition--}
```
public abstract int getPosition()
```

يمثل موضع المحور. قابل للقراءة/الكتابة [AxisPositionType](../../com.aspose.slides/axispositiontype).

**القيمة المرجعة:**
int
### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```

يمثل موضع المحور. قابل للقراءة/الكتابة [AxisPositionType](../../com.aspose.slides/axispositiontype).

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### hasTitle() {#hasTitle--}
```
public abstract boolean hasTitle()
```

يحدد ما إذا كان للمحور عنوان مرئي. قابل للقراءة/الكتابة boolean.

**القيمة المرجعة:**
boolean
### setTitle(boolean value) {#setTitle-boolean-}
```
public abstract void setTitle(boolean value)
```

يحدد ما إذا كان للمحور عنوان مرئي. قابل للقراءة/الكتابة boolean.

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getNumberFormat() {#getNumberFormat--}
```
public abstract String getNumberFormat()
```

يمثل سلسلة التنسيق لتسميات المحور. قابل للقراءة/الكتابة String.

**القيمة المرجعة:**
java.lang.String
### setNumberFormat(String value) {#setNumberFormat-java.lang.String-}
```
public abstract void setNumberFormat(String value)
```

يمثل سلسلة التنسيق لتسميات المحور. قابل للقراءة/الكتابة String.

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### isNumberFormatLinkedToSource() {#isNumberFormatLinkedToSource--}
```
public abstract boolean isNumberFormatLinkedToSource()
```

يشير إلى ما إذا كان التنسيق مرتبطًا ببيانات المصدر. قابل للقراءة/الكتابة boolean.

**القيمة المرجعة:**
boolean
### setNumberFormatLinkedToSource(boolean value) {#setNumberFormatLinkedToSource-boolean-}
```
public abstract void setNumberFormatLinkedToSource(boolean value)
```

يشير إلى ما إذا كان التنسيق مرتبطًا ببيانات المصدر. قابل للقراءة/الكتابة boolean.

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getTickLabelRotationAngle() {#getTickLabelRotationAngle--}
```
public abstract float getTickLabelRotationAngle()
```

يمثل زاوية تدوير تسميات الفواصل. قابل للقراءة/الكتابة float.

**القيمة المرجعة:**
float
### setTickLabelRotationAngle(float value) {#setTickLabelRotationAngle-float-}
```
public abstract void setTickLabelRotationAngle(float value)
```

يمثل زاوية تدوير تسميات الفواصل. قابل للقراءة/الكتابة float.

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getTickLabelSpacing() {#getTickLabelSpacing--}
```
public abstract long getTickLabelSpacing()
```

يحدد عدد تسميات الفواصل التي يتم تخطيها بين كل تسمية مرسومة. قابل للقراءة/الكتابة long.

**القيمة المرجعة:**
long
### setTickLabelSpacing(long value) {#setTickLabelSpacing-long-}
```
public abstract void setTickLabelSpacing(long value)
```

يحدد عدد تسميات الفواصل التي يتم تخطيها بين كل تسمية مرسومة. قابل للقراءة/الكتابة long.

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

### isAutomaticTickLabelSpacing() {#isAutomaticTickLabelSpacing--}
```
public abstract boolean isAutomaticTickLabelSpacing()
```

يحدد قيمة تلقائية لتباعد تسميات الفواصل. إذا كان false: يستخدم خاصية TickLabelSpacing. قابل للقراءة/الكتابة boolean.

**القيمة المرجعة:**
boolean
### setAutomaticTickLabelSpacing(boolean value) {#setAutomaticTickLabelSpacing-boolean-}
```
public abstract void setAutomaticTickLabelSpacing(boolean value)
```

يحدد قيمة تلقائية لتباعد تسميات الفواصل. إذا كان false: يستخدم خاصية TickLabelSpacing. قابل للقراءة/الكتابة boolean.

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getTickMarksSpacing() {#getTickMarksSpacing--}
```
public abstract long getTickMarksSpacing()
```

يحدد عدد علامات الفواصل التي يتم تخطيها قبل رسم العلامة التالية. يُطبق على محور الفئة أو المحور المتسلسل. قابل للقراءة/الكتابة int.

**القيمة المرجعة:**
long
### setTickMarksSpacing(long value) {#setTickMarksSpacing-long-}
```
public abstract void setTickMarksSpacing(long value)
```

يحدد عدد علامات الفواصل التي يتم تخطيها قبل رسم العلامة التالية. يُطبق على محور الفئة أو المحور المتسلسل. قابل للقراءة/الكتابة int.

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

### isAutomaticTickMarksSpacing() {#isAutomaticTickMarksSpacing--}
```
public abstract boolean isAutomaticTickMarksSpacing()
```

يحدد قيمة تلقائية لتباعد علامات الفواصل. إذا كان false: يستخدم خاصية TickMarksSpacing. قابل للقراءة/الكتابة boolean.

**القيمة المرجعة:**
boolean
### setAutomaticTickMarksSpacing(boolean value) {#setAutomaticTickMarksSpacing-boolean-}
```
public abstract void setAutomaticTickMarksSpacing(boolean value)
```

يحدد قيمة تلقائية لتباعد علامات الفواصل. إذا كان false: يستخدم خاصية TickMarksSpacing. قابل للقراءة/الكتابة boolean.

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getLabelOffset() {#getLabelOffset--}
```
public abstract int getLabelOffset()
```

يحدد مسافة التسميات عن المحور. يُطبق على محور الفئة أو محور التاريخ. يجب أن تكون القيمة بين 0% و1000%. قابل للقراءة/الكتابة int.

**القيمة المرجعة:**
int
### setLabelOffset(int value) {#setLabelOffset-int-}
```
public abstract void setLabelOffset(int value)
```

يحدد مسافة التسميات عن المحور. يُطبق على محور الفئة أو محور التاريخ. يجب أن تكون القيمة بين 0% و1000%. قابل للقراءة/الكتابة int.

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getCategoryAxisType() {#getCategoryAxisType--}
```
public abstract int getCategoryAxisType()
```

يحدد نوع محور الفئة. قابل للقراءة/الكتابة [CategoryAxisType](../../com.aspose.slides/categoryaxistype)(\#getCategoryAxisType.getCategoryAxisType/\#setCategoryAxisType(int).setCategoryAxisType(int)).

**القيمة المرجعة:**
int
### setCategoryAxisType(int value) {#setCategoryAxisType-int-}
```
public abstract void setCategoryAxisType(int value)
```

يحدد نوع محور الفئة. قابل للقراءة/الكتابة [CategoryAxisType](../../com.aspose.slides/categoryaxistype)(\#getCategoryAxisType.getCategoryAxisType/\#setCategoryAxisType(int).setCategoryAxisType(int)).

**المعلمات:**
| Parameter | Type | Description |
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

يمثل نوع التجميع لمحور الفئة (التجميع). يُطبق على الفئة. يُستخدم مع سلاسل Histogram أو HistogramPareto فقط.

**القيمة المرجعة:**
int
### setAggregationType(int value) {#setAggregationType-int-}
```
public abstract void setAggregationType(int value)
```

يمثل نوع التجميع لمحور الفئة (التجميع). يُطبق على الفئة. يُستخدم مع سلاسل Histogram أو HistogramPareto فقط.

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### getBinWidth() {#getBinWidth--}
```
public abstract double getBinWidth()
```

يحدد عرض الحاوية عندما تكون قيمة خاصية AggregationType مضبوطة على AxisAggregationType.ByBinWidth. يُطبق على محاور الفئة. يُستخدم مع سلسلة Histogram أو HistogramPareto فقط.

**القيمة المرجعة:**
double
### setBinWidth(double value) {#setBinWidth-double-}
```
public abstract void setBinWidth(double value)
```

يحدد عرض الحاوية عندما تكون قيمة خاصية AggregationType مضبوطة على AxisAggregationType.ByBinWidth. يُطبق على محاور الفئة. يُستخدم مع سلسلة Histogram أو HistogramPareto فقط.

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |
### getNumberOfBins() {#getNumberOfBins--}
```
public abstract long getNumberOfBins()
```

يحدد عدد الحاويات عندما تكون قيمة خاصية AggregationType مضبوطة على AxisAggregationType.ByNumberOfBins. يُطبق على محاور الفئة. يُستخدم مع سلسلة Histogram أو HistogramPareto فقط.

**القيمة المرجعة:**
long
### setNumberOfBins(long value) {#setNumberOfBins-long-}
```
public abstract void setNumberOfBins(long value)
```

يحدد عدد الحاويات عندما تكون قيمة خاصية AggregationType مضبوطة على AxisAggregationType.ByNumberOfBins. يُطبق على محاور الفئة. يُستخدم مع سلسلة Histogram أو HistogramPareto فقط.

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |
### isOverflowBin() {#isOverflowBin--}
```
public abstract boolean isOverflowBin()
```

يحدد ما إذا كان حاوية الفائض مفعّلة. استخدم IsAutomaticOverflowBin و OverflowBin لضبط قيمة حاوية الفائض.

**القيمة المرجعة:**
boolean
### setOverflowBin(boolean value) {#setOverflowBin-boolean-}
```
public abstract void setOverflowBin(boolean value)
```

يحدد ما إذا كان حاوية الفائض مفعّلة. استخدم IsAutomaticOverflowBin و OverflowBin لضبط قيمة حاوية الفائض.

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### isAutomaticOverflowBin() {#isAutomaticOverflowBin--}
```
public abstract boolean isAutomaticOverflowBin()
```

يحدد قيمة حاوية الفائض الآلية. إذا كان false: استخدم خاصية OverflowBin.

**القيمة المرجعة:**
boolean
### setAutomaticOverflowBin(boolean value) {#setAutomaticOverflowBin-boolean-}
```
public abstract void setAutomaticOverflowBin(boolean value)
```

يحدد قيمة حاوية الفائض الآلية. إذا كان false: استخدم خاصية OverflowBin.

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getOverflowBin() {#getOverflowBin--}
```
public abstract double getOverflowBin()
```

يحدد قيمة مخصصة لحاوية الفائض. يُطبّق عندما تكون خاصية IsAutomaticOverflowBin مضبوطة على false وتكون خاصية IsOverflowBin مساوية true.

**القيمة المرجعة:**
double
### setOverflowBin(double value) {#setOverflowBin-double-}
```
public abstract void setOverflowBin(double value)
```

يحدد قيمة مخصصة لحاوية الفائض. يُطبّق عندما تكون خاصية IsAutomaticOverflowBin مضبوطة على false وتكون خاصية IsOverflowBin مساوية true.

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |
### isUnderflowBin() {#isUnderflowBin--}
```
public abstract boolean isUnderflowBin()
```

يحدد ما إذا كان حاوية النقص مفعّلة. استخدم IsAutomaticUnderflowBin و UnderflowBin لضبط قيمة حاوية النقص.

**القيمة المرجعة:**
boolean
### setUnderflowBin(boolean value) {#setUnderflowBin-boolean-}
```
public abstract void setUnderflowBin(boolean value)
```

يحدد ما إذا كان حاوية النقص مفعّلة. استخدم IsAutomaticUnderflowBin و UnderflowBin لضبط قيمة حاوية النقص.

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### isAutomaticUnderflowBin() {#isAutomaticUnderflowBin--}
```
public abstract boolean isAutomaticUnderflowBin()
```

يحدد قيمة حاوية النقص الآلية. إذا كان false: استخدم خاصية UnderflowBin.

**القيمة المرجعة:**
boolean
### setAutomaticUnderflowBin(boolean value) {#setAutomaticUnderflowBin-boolean-}
```
public abstract void setAutomaticUnderflowBin(boolean value)
```

يحدد قيمة حاوية النقص الآلية. إذا كان false: استخدم خاصية UnderflowBin.

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getUnderflowBin() {#getUnderflowBin--}
```
public abstract double getUnderflowBin()
```

يحدد قيمة مخصصة لحاوية النقص. يُطبّق عندما تكون خاصية IsAutomaticUnderflowBin مضبوطة على false وتكون خاصية IsUnderflowBin مساوية true.

**القيمة المرجعة:**
double
### setUnderflowBin(double value) {#setUnderflowBin-double-}
```
public abstract void setUnderflowBin(double value)
```

يحدد قيمة مخصصة لحاوية النقص. يُطبّق عندما تكون خاصية IsAutomaticUnderflowBin مضبوطة على false وتكون خاصية IsUnderflowBin مساوية true.

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |