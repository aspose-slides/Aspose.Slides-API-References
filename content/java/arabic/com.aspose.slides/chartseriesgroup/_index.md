---
title: ChartSeriesGroup
second_title: مرجع API Aspose.Slides للـ Java
description: يمثل مجموعة من السلاسل.
type: docs
url: /ar/com.aspose.slides/chartseriesgroup/
---
**الوراثة:**
java.lang.Object

**جميع الواجهات المنفذة:**
[com.aspose.slides.IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup), com.aspose.slides.IDOMObject
```
public class ChartSeriesGroup implements IChartSeriesGroup, IDOMObject
```

يمثل مجموعة من السلاسل.

--------------------

1) انظر الملخص والملاحظات لفئة ChartSeriesGroupCollection والعدد CombinableSeriesTypesGroup enum. 2) تحتوي مجموعة السلاسل على بعض خصائص السلاسل التي تكون مشتركة لكل سلسلة في المجموعة ("خصائص مجموعة السلاسل"). "خصائص مجموعة السلاسل" في فئة ChartSeriesGroup هي قراءة/كتابة. كل من "خصائص مجموعة السلاسل" يمكن أن تكون لديها إسقاط قراءة فقط في فئة ChartSeries.

## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getType()](#getType--) | إرجاع نوع من مجموعة السلاسل هذه. |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | يوضح ما إذا كانت سلاسل هذه المجموعة مرسومة على المحور الثانوي. |
| [getSeries()](#getSeries--) | إرجاع مجموعة من السلاسل. |
| [get_Item(int index)](#get-Item-int-) | يحصل على العنصر في الفهرس المحدد. |
| [getUpDownBars()](#getUpDownBars--) | يوفر وصولاً إلى أشرطة الصعود/الهبوط في مخطط خط أو مخطط أسهم. |
| [getGapWidth()](#getGapWidth--) | يحدد المسافة بين مجموعات الشرائط أو الأعمدة كنسبة مئوية من عرض الشريط أو العمود. |
| [setGapWidth(int value)](#setGapWidth-int-) | يحدد المسافة بين مجموعات الشرائط أو الأعمدة كنسبة مئوية من عرض الشريط أو العمود. |
| [getGapDepth()](#getGapDepth--) | إرجاع أو ضبط المسافة، كنسبة مئوية من عرض العلامة، بين سلاسل البيانات في مخطط ثلاثي الأبعاد. |
| [setGapDepth(int value)](#setGapDepth-int-) | إرجاع أو ضبط المسافة، كنسبة مئوية من عرض العلامة، بين سلاسل البيانات في مخطط ثلاثي الأبعاد. |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | يحصل أو يضبط زاوية قطعة الفطيرة أو المخطط الدائري الأولى بالدرجات (في اتجاه عقرب الساعة من الأعلى، من 0 إلى 360 درجة). |
| [setFirstSliceAngle(int value)](#setFirstSliceAngle-int-) | يحصل أو يضبط زاوية قطعة الفطيرة أو المخطط الدائري الأولى بالدرجات (في اتجاه عقرب الساعة من الأعلى، من 0 إلى 360 درجة). |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | يحدد حجم الثقب في مخطط مقلوب (يمكن أن يكون بين 0 و 90٪ من حجم منطقة الرسم). |
| [setDoughnutHoleSize(byte value)](#setDoughnutHoleSize-byte-) | يحدد حجم الثقب في مخطط مقلوب (يمكن أن يكون بين 0 و 90٪ من حجم منطقة الرسم). |
| [getOverlap()](#getOverlap--) | يحدد مقدار تداخل الشرائط والأعمدة في المخططات ثنائية الأبعاد، كنسبة مئوية (من -100٪ إلى 100٪). |
| [setOverlap(byte value)](#setOverlap-byte-) | يحدد مقدار تداخل الشرائط والأعمدة في المخططات ثنائية الأبعاد، كنسبة مئوية (من -100٪ إلى 100٪). |
| [getSecondPieSize()](#getSecondPieSize--) | يحدد حجم الفطيرة أو الشريط الثاني في مخطط الفطيرة-على-فطيرة أو شريط-على-فطيرة، كنسبة مئوية من حجم الفطيرة الأولى (يمكن أن يكون بين 5 و 200٪). |
| [setSecondPieSize(int value)](#setSecondPieSize-int-) | يحدد حجم الفطيرة أو الشريط الثاني في مخطط الفطيرة-على-فطيرة أو شريط-على-فطيرة، كنسبة مئوية من حجم الفطيرة الأولى (يمكن أن يكون بين 5 و 200٪). |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | يحدد كيفية تمثيل قيم حجم الفقاعات في مخطط الفقاعات. |
| [setBubbleSizeRepresentation(int value)](#setBubbleSizeRepresentation-int-) | يحدد كيفية تمثيل قيم حجم الفقاعات في مخطط الفقاعات. |
| [getPieSplitPosition()](#getPieSplitPosition--) | يحدد قيمة ستُستخدم لتحديد أي نقاط البيانات تكون في الفطيرة أو الشريط الثاني في مخطط الفطيرة-على-فطيرة أو شريط-على-فطيرة. |
| [setPieSplitPosition(double value)](#setPieSplitPosition-double-) | يحدد قيمة ستُستخدم لتحديد أي نقاط البيانات تكون في الفطيرة أو الشريط الثاني في مخطط الفطيرة-على-فطيرة أو شريط-على-فطيرة. |
| [getPieSplitBy()](#getPieSplitBy--) | يحدد طريقة تحديد أي نقاط البيانات تكون في الفطيرة أو الشريط الثاني في مخطط الفطيرة-على-فطيرة أو شريط-على-فطيرة. |
| [setPieSplitBy(int value)](#setPieSplitBy-int-) | يحدد طريقة تحديد أي نقاط البيانات تكون في الفطيرة أو الشريط الثاني في مخطط الفطيرة-على-فطيرة أو شريط-على-فطيرة. |
| [isColorVaried()](#isColorVaried--) | يحدد أن كل علامة بيانات في السلسلة لها لون مختلف. |
| [setColorVaried(boolean value)](#setColorVaried-boolean-) | يحدد أن كل علامة بيانات في السلسلة لها لون مختلف. |
| [hasSeriesLines()](#hasSeriesLines--) | صحيح إذا كان المخطط يحتوي على خطوط السلسلة. |
| [setSeriesLines(boolean value)](#setSeriesLines-boolean-) | صحيح إذا كان المخطط يحتوي على خطوط السلسلة. |
| [getHiLowLinesFormat()](#getHiLowLinesFormat--) | يحدد تنسيق HiLowLines. |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | يحدد عامل المقياس لمخطط الفقاعات (يمكن أن يكون بين 0 و 300٪ من الحجم الافتراضي). |
| [setBubbleSizeScale(int value)](#setBubbleSizeScale-int-) | يحدد عامل المقياس لمخطط الفقاعات (يمكن أن يكون بين 0 و 300٪ من الحجم الافتراضي). |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | معلومات التقسيم المخصص لمخطط الفطيرة-على-فطيرة أو شريط-على-فطيرة مع تقسيم مخصص. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getChart()](#getChart--) | يرجع المخطط الأب. |
| [getSlide()](#getSlide--) | يرجع شريحة الأبوية لـ FillFormat. |
| [getPresentation()](#getPresentation--) | يرجع العرض التقديمي الأب لـ FillFormat. |

### getType() {#getType--}
```
public final int getType()
```

إرجاع نوع من مجموعة السلاسل هذه. قراءة فقط [CombinableSeriesTypesGroup](../../com.aspose.slides/combinableseriestypesgroup).

**الإرجاع:**
int

### getPlotOnSecondAxis() {#getPlotOnSecondAxis--}
```
public final boolean getPlotOnSecondAxis()
```

يوضح ما إذا كانت سلاسل هذه المجموعة مرسومة على المحور الثانوي. قراءة فقط boolean.

**الإرجاع:**
boolean

### getSeries() {#getSeries--}
```
public final IChartSeriesReadonlyCollection getSeries()
```

إرجاع مجموعة من السلاسل. قراءة فقط [IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection).

**الإرجاع:**
[IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection)

### get_Item(int index) {#get-Item-int-}
```
public final IChartSeries get_Item(int index)
```

يحصل على العنصر في الفهرس المحدد.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int |  |

**الإرجاع:**
[IChartSeries](../../com.aspose.slides/ichartseries)

### getUpDownBars() {#getUpDownBars--}
```
public final IUpDownBarsManager getUpDownBars()
```

يوفر وصولاً إلى أشرطة الصعود/الهبوط في مخطط خط أو مخطط أسهم. قراءة فقط [IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager).

**الإرجاع:**
[IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager)

### getGapWidth() {#getGapWidth--}
```
public final int getGapWidth()
```

يحدد المسافة بين مجموعات الشرائط أو الأعمدة كنسبة مئوية من عرض الشريط أو العمود. قراءة/كتابة int.

**الإرجاع:**
int

### setGapWidth(int value) {#setGapWidth-int-}
```
public final void setGapWidth(int value)
```

يحدد المسافة بين مجموعات الشرائط أو الأعمدة كنسبة مئوية من عرض الشريط أو العمود. قراءة/كتابة int.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getGapDepth() {#getGapDepth--}
```
public final int getGapDepth()
```

إرجاع أو ضبط المسافة، كنسبة مئوية من عرض العلامة، بين سلاسل البيانات في مخطط ثلاثي الأبعاد. قراءة/كتابة int.

**الإرجاع:**
int

### setGapDepth(int value) {#setGapDepth-int-}
```
public final void setGapDepth(int value)
```

إرجاع أو ضبط المسافة، كنسبة مئوية من عرض العلامة، بين سلاسل البيانات في مخطط ثلاثي الأبعاد. قراءة/كتابة int.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public final int getFirstSliceAngle()
```

يحصل أو يضبط زاوية قطعة الفطيرة أو المخطط الدائري الأولى بالدرجات (في اتجاه عقرب الساعة من الأعلى، من 0 إلى 360 درجة). قراءة/كتابة int.

**الإرجاع:**
int

### setFirstSliceAngle(int value) {#setFirstSliceAngle-int-}
```
public final void setFirstSliceAngle(int value)
```

يحصل أو يضبط زاوية قطعة الفطيرة أو المخطط الدائري الأولى بالدرجات (في اتجاه عقرب الساعة من الأعلى، من 0 إلى 360 درجة). قراءة/كتابة int.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public final byte getDoughnutHoleSize()
```

يحدد حجم الثقب في مخطط مقلوب (يمكن أن يكون بين 0 و 90٪ من حجم منطقة الرسم). قراءة/كتابة byte.

**الإرجاع:**
byte

### setDoughnutHoleSize(byte value) {#setDoughnutHoleSize-byte-}
```
public final void setDoughnutHoleSize(byte value)
```

يحدد حجم الثقب في مخطط مقلوب (يمكن أن يكون بين 0 و 90٪ من حجم منطقة الرسم). قراءة/كتابة byte.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getOverlap() {#getOverlap--}
```
public final byte getOverlap()
```

يحدد مقدار تداخل الشرائط والأعمدة في المخططات ثنائية الأبعاد، كنسبة مئوية (من -100٪ إلى 100٪). - -100٪: أقصى مسافة (الشرائط منفصلة تمامًا). - 0٪: توضع الشرائط جنبًا إلى جنب دون تداخل أو مسافة. - 100٪: أقصى تداخل (الشرائط تتداخل تمامًا). هذه الخاصية قراءة/كتابة byte.

--------------------

> ```
> The following example demonstrates how to set the overlap for a chart series group 
>   and render the resulting chart on a form:
>   
>  Presentation pres = new Presentation();
>  try {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.ClusteredColumn, 10, 10, 600, 300);
>      IChartSeriesCollection series = chart.getChartData().getSeries();
>      series.get_Item(0).getParentSeriesGroup().setOverlap((byte)55); // ضبط التداخل إلى 55%
>      pres.getSlides().get_Item(0).getImage(1, 1).save("chart.png", ImageFormat.Png);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**الإرجاع:**
byte

### setOverlap(byte value) {#setOverlap-byte-}
```
public final void setOverlap(byte value)
```

يحدد مقدار تداخل الشرائط والأعمدة في المخططات ثنائية الأبعاد، كنسبة مئوية (من -100٪ إلى 100٪). - -100٪: أقصى مسافة (الشرائط منفصلة تمامًا). - 0٪: توضع الشرائط جنبًا إلى جنب دون تداخل أو مسافة. - 100٪: أقصى تداخل (الشرائط تتداخل تمامًا). هذه الخاصية قراءة/كتابة byte.

--------------------

> ```
> The following example demonstrates how to set the overlap for a chart series group 
>   and render the resulting chart on a form:
>   
>  Presentation pres = new Presentation();
>  try {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.ClusteredColumn, 10, 10, 600, 300);
>      IChartSeriesCollection series = chart.getChartData().getSeries();
>      series.get_Item(0).getParentSeriesGroup().setOverlap((byte)55); // ضبط التداخل إلى 55%
>      pres.getSlides().get_Item(0).getImage(1, 1).save("chart.png", ImageFormat.Png);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getSecondPieSize() {#getSecondPieSize--}
```
public final int getSecondPieSize()
```

يحدد حجم الفطيرة أو الشريط الثاني في مخطط الفطيرة-على-فطيرة أو شريط-على-فطيرة، كنسبة مئوية من حجم الفطيرة الأولى (يمكن أن يكون بين 5 و 200٪). قراءة/كتابة int.

**الإرجاع:**
int

### setSecondPieSize(int value) {#setSecondPieSize-int-}
```
public final void setSecondPieSize(int value)
```

يحدد حجم الفطيرة أو الشريط الثاني في مخطط الفطيرة-على-فطيرة أو شريط-على-فطيرة، كنسبة مئوية من حجم الفطيرة الأولى (يمكن أن يكون بين 5 و 200٪). قراءة/كتابة int.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public final int getBubbleSizeRepresentation()
```

يحدد كيفية تمثيل قيم حجم الفقاعات في مخطط الفقاعات. قراءة/كتابة [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**الإرجاع:**
int

### setBubbleSizeRepresentation(int value) {#setBubbleSizeRepresentation-int-}
```
public final void setBubbleSizeRepresentation(int value)
```

يحدد كيفية تمثيل قيم حجم الفقاعات في مخطط الفقاعات. قراءة/كتابة [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getPieSplitPosition() {#getPieSplitPosition--}
```
public final double getPieSplitPosition()
```

يحدد قيمة ستُستخدم لتحديد أي نقاط البيانات تكون في الفطيرة أو الشريط الثاني في مخطط الفطيرة-على-فطيرة أو شريط-على-فطيرة. تُستخدم مع خاصية PieSplitBy. قراءة/كتابة double.

**الإرجاع:**
double

### setPieSplitPosition(double value) {#setPieSplitPosition-double-}
```
public final void setPieSplitPosition(double value)
```

يحدد قيمة ستُستخدم لتحديد أي نقاط البيانات تكون في الفطيرة أو الشريط الثاني في مخطط الفطيرة-على-فطيرة أو شريط-على-فطيرة. تُستخدم مع خاصية PieSplitBy. قراءة/كتابة double.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | double |  |

### getPieSplitBy() {#getPieSplitBy--}
```
public final int getPieSplitBy()
```

يحدد طريقة تحديد أي نقاط البيانات تكون في الفطيرة أو الشريط الثاني في مخطط الفطيرة-على-فطيرة أو شريط-على-فطيرة. قراءة/كتابة [PieSplitType](../../com.aspose.slides/piesplittype).

**الإرجاع:**
int

### setPieSplitBy(int value) {#setPieSplitBy-int-}
```
public final void setPieSplitBy(int value)
```

يحدد طريقة تحديد أي نقاط البيانات تكون في الفطيرة أو الشريط الثاني في مخطط الفطيرة-على-فطيرة أو شريط-على-فطيرة. قراءة/كتابة [PieSplitType](../../com.aspose.slides/piesplittype).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### isColorVaried() {#isColorVaried--}
```
public final boolean isColorVaried()
```

يحدد أن كل علامة بيانات في السلسلة لها لون مختلف. قراءة/كتابة boolean.

**الإرجاع:**
boolean

### setColorVaried(boolean value) {#setColorVaried-boolean-}
```
public final void setColorVaried(boolean value)
```

يحدد أن كل علامة بيانات في السلسلة لها لون مختلف. قراءة/كتابة boolean.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### hasSeriesLines() {#hasSeriesLines--}
```
public final boolean hasSeriesLines()
```

صحيح إذا كان المخطط يحتوي على خطوط السلسلة. يُطبق على مخططات الأعمدة المكدسة ومخططات OfPie. قراءة/كتابة boolean.

**الإرجاع:**
boolean

### setSeriesLines(boolean value) {#setSeriesLines-boolean-}
```
public final void setSeriesLines(boolean value)
```

صحيح إذا كان المخطط يحتوي على خطوط السلسلة. يُطبق على مخططات الأعمدة المكدسة ومخططات OfPie. قراءة/كتابة boolean.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getHiLowLinesFormat() {#getHiLowLinesFormat--}
```
public final IChartLinesFormat getHiLowLinesFormat()
```

يحدد تنسيق HiLowLines. يُطبق HiLowLines مع أنواع المخططات HiLowClose، OpenHiLowClose، VolumeHiLowClose و VolumeOpenHiLowClose.

**الإرجاع:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)

### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public final int getBubbleSizeScale()
```

يحدد عامل المقياس لمخطط الفقاعات (يمكن أن يكون بين 0 و 300٪ من الحجم الافتراضي). قراءة/كتابة int.

**الإرجاع:**
int

### setBubbleSizeScale(int value) {#setBubbleSizeScale-int-}
```
public final void setBubbleSizeScale(int value)
```

يحدد عامل المقياس لمخطط الفقاعات (يمكن أن يكون بين 0 و 300٪ من الحجم الافتراضي). قراءة/كتابة int.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public final IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

معلومات التقسيم المخصص لمخطط الفطيرة-على-فطيرة أو شريط-على-فطيرة مع تقسيم مخصص. يحتوي على نقاط البيانات التي يجب رسمها في الفطيرة أو الشريط الثاني. قراءة فقط [PieSplitCustomPointCollection](../../com.aspose.slides/piesplitcustompointcollection).

**الإرجاع:**
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

يرجع كائن Parent_Immediate. قراءة فقط IDOMObject.

**الإرجاع:**
com.aspose.slides.IDOMObject

### getChart() {#getChart--}
```
public final IChart getChart()
```

يرجع المخطط الأب. قراءة فقط [IChart](../../com.aspose.slides/ichart).

**الإرجاع:**
[IChart](../../com.aspose.slides/ichart)

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

يرجع شريحة الأبوية لـ FillFormat. قراءة فقط [BaseSlide](../../com.aspose.slides/baseslide).

**الإرجاع:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

يرجع العرض التقديمي الأب لـ FillFormat. قراءة فقط [IPresentation](../../com.aspose.slides/ipresentation).

**الإرجاع:**
[IPresentation](../../com.aspose.slides/ipresentation)