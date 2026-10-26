---
title: ChartSeriesGroup
second_title: Aspose.Slides لنظام Android عبر مرجع Java API
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

1) انظر الملخص والملاحظات للفئة ChartSeriesGroupCollection والعدد CombinableSeriesTypesGroup. 2) تحتوي مجموعة السلاسل على بعض خصائص السلسلة التي هي مشتركة لكل سلسلة في المجموعة ("خصائص مجموعة السلسلة"). "خصائص مجموعة السلسلة" في فئة ChartSeriesGroup هي للقراءة/الكتابة. كل من "خصائص مجموعة السلسلة" يمكن أن يكون لها إسقاط للقراءة فقط في فئة ChartSeries.

## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getType()](#getType--) | يرجع نوعًا لهذه المجموعة من السلاسل. |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | يشير إلى ما إذا كانت سلاسل هذه المجموعة مرسومة على المحور الثانوي. |
| [getSeries()](#getSeries--) | يرجع مجموعة من السلاسل. |
| [get_Item(int index)](#get-Item-int-) | يحصل على العنصر في الفهرس المحدد. |
| [getUpDownBars()](#getUpDownBars--) | يوفر وصولًا إلى أشرطة الصعود/النزول في مخطط خط أو مخطط سهم. |
| [getGapWidth()](#getGapWidth--) | يحدد المسافة بين مجموعات الأشرطة أو الأعمدة كنسبة مئوية من عرض الشريط أو العمود. |
| [setGapWidth(int value)](#setGapWidth-int-) | يحدد المسافة بين مجموعات الأشرطة أو الأعمدة كنسبة مئوية من عرض الشريط أو العمود. |
| [getGapDepth()](#getGapDepth--) | يرجع أو يعيّن المسافة كنسبة مئوية من عرض العلامة بين سلاسل البيانات في مخطط ثلاثي الأبعاد. |
| [setGapDepth(int value)](#setGapDepth-int-) | يرجع أو يعيّن المسافة كنسبة مئوية من عرض العلامة بين سلاسل البيانات في مخطط ثلاثي الأبعاد. |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | يحصل على أو يعيّن زاوية الشريحة الأولى في مخطط الفطيرة أو الدونات، بالدرجات (عقليًا من الأعلى، من 0 إلى 360 درجة). |
| [setFirstSliceAngle(int value)](#setFirstSliceAngle-int-) | يحصل على أو يعيّن زاوية الشريحة الأولى في مخطط الفطيرة أو الدونات، بالدرجات (عقليًا من الأعلى، من 0 إلى 360 درجة). |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | يحدد حجم الفتحة في مخطط الدونات (يمكن أن يكون بين 0 و 90 بالمائة من حجم مساحة الرسم). |
| [setDoughnutHoleSize(byte value)](#setDoughnutHoleSize-byte-) | يحدد حجم الفتحة في مخطط الدونات (يمكن أن يكون بين 0 و 90 بالمائة من حجم مساحة الرسم). |
| [getOverlap()](#getOverlap--) | يحدد مقدار التداخل بين الأشرطة والأعمدة في المخططات ثنائية الأبعاد كنسبة مئوية (من -100% إلى 100%). |
| [setOverlap(byte value)](#setOverlap-byte-) | يحدد مقدار التداخل بين الأشرطة والأعمدة في المخططات ثنائية الأبعاد كنسبة مئوية (من -100% إلى 100%). |
| [getSecondPieSize()](#getSecondPieSize--) | يحدد حجم الفطيرة أو الشريط الثاني في مخطط الفطيرة-من-فطيرة أو الشريط-من-فطيرة كنسبة مئوية من حجم الفطيرة الأولى (يمكن أن يكون بين 5 و 200 بالمائة). |
| [setSecondPieSize(int value)](#setSecondPieSize-int-) | يحدد حجم الفطيرة أو الشريط الثاني في مخطط الفطيرة-من-فطيرة أو الشريط-من-فطيرة كنسبة مئوية من حجم الفطيرة الأولى (يمكن أن يكون بين 5 و 200 بالمائة). |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | يحدد كيفية تمثيل قيم حجم الفقاعات في مخطط الفقاعات. |
| [setBubbleSizeRepresentation(int value)](#setBubbleSizeRepresentation-int-) | يحدد كيفية تمثيل قيم حجم الفقاعات في مخطط الفقاعات. |
| [getPieSplitPosition()](#getPieSplitPosition--) | يحدد قيمة تُستخدم لتحديد أي نقاط البيانات تكون في الفطيرة أو الشريط الثاني في مخطط الفطيرة-من-فطيرة أو الشريط-من-فطيرة. |
| [setPieSplitPosition(double value)](#setPieSplitPosition-double-) | يحدد قيمة تُستخدم لتحديد أي نقاط البيانات تكون في الفطيرة أو الشريط الثاني في مخطط الفطيرة-من-فطيرة أو الشريط-من-فطيرة. |
| [getPieSplitBy()](#getPieSplitBy--) | يحدد كيفية تحديد أي نقاط البيانات تكون في الفطيرة أو الشريط الثاني في مخطط الفطيرة-من-فطيرة أو الشريط-من-فطيرة. |
| [setPieSplitBy(int value)](#setPieSplitBy-int-) | يحدد كيفية تحديد أي نقاط البيانات تكون في الفطيرة أو الشريط الثاني في مخطط الفطيرة-من-فطيرة أو الشريط-من-فطيرة. |
| [isColorVaried()](#isColorVaried--) | يحدد أن كل علامة بيانات في السلسلة لها لون مختلف. |
| [setColorVaried(boolean value)](#setColorVaried-boolean-) | يحدد أن كل علامة بيانات في السلسلة لها لون مختلف. |
| [hasSeriesLines()](#hasSeriesLines--) | صحيح إذا كان المخطط يحتوي على خطوط السلسلة. |
| [setSeriesLines(boolean value)](#setSeriesLines-boolean-) | صحيح إذا كان المخطط يحتوي على خطوط السلسلة. |
| [getHiLowLinesFormat()](#getHiLowLinesFormat--) | يحدد تنسيق HiLowLines. |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | يحدد عامل المقياس لمخطط الفقاعات (يمكن أن يكون بين 0 و 300 بالمائة من الحجم الافتراضي). |
| [setBubbleSizeScale(int value)](#setBubbleSizeScale-int-) | يحدد عامل المقياس لمخطط الفقاعات (يمكن أن يكون بين 0 و 300 بالمائة من الحجم الافتراضي). |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | معلومات الانقسام المخصص لمخطط الفطيرة-من-فطيرة أو الشريط-من-فطيرة مع انقسام مخصص. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getChart()](#getChart--) | يرجع المخطط الأب. |
| [getSlide()](#getSlide--) | يرجع الشريحة الأب لـ FillFormat. |
| [getPresentation()](#getPresentation--) | يرجع العرض التقديمي الأب لـ FillFormat. |

### getType() {#getType--}
```
public final int getType()
```

يرجع نوعًا لهذه المجموعة من السلسلة. للقراءة فقط [CombinableSeriesTypesGroup](../../com.aspose.slides/combinableseriestypesgroup).

**القيمة المرجعة:**
int

### getPlotOnSecondAxis() {#getPlotOnSecondAxis--}
```
public final boolean getPlotOnSecondAxis()
```

يشير إلى ما إذا كانت سلاسل هذه المجموعة مرسومة على المحور الثانوي. للقراءة فقط boolean.

**القيمة المرجعة:**
boolean

### getSeries() {#getSeries--}
```
public final IChartSeriesReadonlyCollection getSeries()
```

يرجع مجموعة من السلاسل. للقراءة فقط [IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection).

**القيمة المرجعة:**
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

**القيمة المرجعة:**
[IChartSeries](../../com.aspose.slides/ichartseries)

### getUpDownBars() {#getUpDownBars--}
```
public final IUpDownBarsManager getUpDownBars()
```

يوفر وصولًا إلى أشرطة الصعود/النزول في مخطط خط أو مخطط سهم. للقراءة فقط [IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager).

**القيمة المرجعة:**
[IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager)

### getGapWidth() {#getGapWidth--}
```
public final int getGapWidth()
```

يحدد المسافة بين مجموعات الأشرطة أو الأعمدة كنسبة مئوية من عرض الشريط أو العمود. قابل للقراءة/الكتابة int.

**القيمة المرجعة:**
int

### setGapWidth(int value) {#setGapWidth-int-}
```
public final void setGapWidth(int value)
```

يحدد المسافة بين مجموعات الأشرطة أو الأعمدة كنسبة مئوية من عرض الشريط أو العمود. قابل للقراءة/الكتابة int.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getGapDepth() {#getGapDepth--}
```
public final int getGapDepth()
```

يرجع أو يعيّن المسافة كنسبة مئوية من عرض العلامة بين سلاسل البيانات في مخطط ثلاثي الأبعاد. قابل للقراءة/الكتابة int.

**القيمة المرجعة:**
int

### setGapDepth(int value) {#setGapDepth-int-}
```
public final void setGapDepth(int value)
```

يرجع أو يعيّن المسافة كنسبة مئوية من عرض العلامة بين سلاسل البيانات في مخطط ثلاثي الأبعاد. قابل للقراءة/الكتابة int.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public final int getFirstSliceAngle()
```

يحصل على أو يعيّن زاوية الشريحة الأولى في مخطط الفطيرة أو الدونات، بالدرجات (عقليًا من الأعلى، من 0 إلى 360 درجة). قابل للقراءة/الكتابة int.

**القيمة المرجعة:**
int

### setFirstSliceAngle(int value) {#setFirstSliceAngle-int-}
```
public final void setFirstSliceAngle(int value)
```

يحصل على أو يعيّن زاوية الشريحة الأولى في مخطط الفطيرة أو الدونات، بالدرجات (عقليًا من الأعلى، من 0 إلى 360 درجة). قابل للقراءة/الكتابة int.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public final byte getDoughnutHoleSize()
```

يحدد حجم الفتحة في مخطط الدونات (يمكن أن يكون بين 0 و 90 بالمائة من حجم مساحة الرسم). قابل للقراءة/الكتابة byte.

**القيمة المرجعة:**
byte

### setDoughnutHoleSize(byte value) {#setDoughnutHoleSize-byte-}
```
public final void setDoughnutHoleSize(byte value)
```

يحدد حجم الفتحة في مخطط الدونات (يمكن أن يكون بين 0 و 90 بالمائة من حجم مساحة الرسم). قابل للقراءة/الكتابة byte.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getOverlap() {#getOverlap--}
```
public final byte getOverlap()
```

يحدد مقدار التداخل بين الأشرطة والأعمدة في المخططات ثنائية الأبعاد كنسبة مئوية (من -100% إلى 100%). -100%: أقصى تباعد (الأشرطة مفصولة تمامًا). 0%: توضع الأشرطة جنبًا إلى جنب دون تداخل أو تباعد. 100%: أقصى تداخل (الأشرطة تتداخل تمامًا). هذه الخاصية قابلة للقراءة/الكتابة byte.

--------------------

> ```
> The following example demonstrates how to set the overlap for a chart series group 
>   and render the resulting chart on a form:
>   
>  Presentation pres = new Presentation();
>  try {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.ClusteredColumn, 10, 10, 600, 300);
>      IChartSeriesCollection series = chart.getChartData().getSeries();
>      series.get_Item(0).getParentSeriesGroup().setOverlap((byte)55); // Set overlap to 55%
>      pres.getSlides().get_Item(0).getImage(1, 1).save("chart.png", ImageFormat.Png);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**القيمة المرجعة:**
byte

### setOverlap(byte value) {#setOverlap-byte-}
```
public final void setOverlap(byte value)
```

يحدد مقدار التداخل بين الأشرطة والأعمدة في المخططات ثنائية الأبعاد كنسبة مئوية (من -100% إلى 100%). -100%: أقصى تباعد (الأشرطة مفصولة تمامًا). 0%: توضع الأشرطة جنبًا إلى جنب دون تداخل أو تباعد. 100%: أقصى تداخل (الأشرطة تتداخل تمامًا). هذه الخاصية قابلة للقراءة/الكتابة byte.

--------------------

> ```
> The following example demonstrates how to set the overlap for a chart series group 
>   and render the resulting chart on a form:
>   
>  Presentation pres = new Presentation();
>  try {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.ClusteredColumn, 10, 10, 600, 300);
>      IChartSeriesCollection series = chart.getChartData().getSeries();
>      series.get_Item(0).getParentSeriesGroup().setOverlap((byte)55); // Set overlap to 55%
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

يحدد حجم الفطيرة أو الشريط الثاني في مخطط الفطيرة-من-فطيرة أو الشريط-من-فطيرة كنسبة مئوية من حجم الفطيرة الأولى (يمكن أن يكون بين 5 و 200 بالمائة). قابل للقراءة/الكتابة int.

**القيمة المرجعة:**
int

### setSecondPieSize(int value) {#setSecondPieSize-int-}
```
public final void setSecondPieSize(int value)
```

يحدد حجم الفطيرة أو الشريط الثاني في مخطط الفطيرة-من-فطيرة أو الشريط-من-فطيرة كنسبة مئوية من حجم الفطيرة الأولى (يمكن أن يكون بين 5 و 200 بالمائة). قابل للقراءة/الكتابة int.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public final int getBubbleSizeRepresentation()
```

يحدد كيفية تمثيل قيم حجم الفقاعات في مخطط الفقاعات. قابل للقراءة/الكتابة [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**القيمة المرجعة:**
int

### setBubbleSizeRepresentation(int value) {#setBubbleSizeRepresentation-int-}
```
public final void setBubbleSizeRepresentation(int value)
```

يحدد كيفية تمثيل قيم حجم الفقاعات في مخطط الفقاعات. قابل للقراءة/الكتابة [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getPieSplitPosition() {#getPieSplitPosition--}
```
public final double getPieSplitPosition()
```

يحدد قيمة تُستخدم لتحديد أي نقاط البيانات تكون في الفطيرة أو الشريط الثاني في مخطط الفطيرة-من-فطيرة أو الشريط-من-فطيرة. تُستخدم مع خاصية PieSplitBy. قابل للقراءة/الكتابة double.

**القيمة المرجعة:**
double

### setPieSplitPosition(double value) {#setPieSplitPosition-double-}
```
public final void setPieSplitPosition(double value)
```

يحدد قيمة تُستخدم لتحديد أي نقاط البيانات تكون في الفطيرة أو الشريط الثاني في مخطط الفطيرة-من-فطيرة أو الشريط-من-فطيرة. تُستخدم مع خاصية PieSplitBy. قابل للقراءة/الكتابة double.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | double |  |

### getPieSplitBy() {#getPieSplitBy--}
```
public final int getPieSplitBy()
```

يحدد كيفية تحديد أي نقاط البيانات تكون في الفطيرة أو الشريط الثاني في مخطط الفطيرة-من-فطيرة أو الشريط-من-فطيرة. قابل للقراءة/الكتابة [PieSplitType](../../com.aspose.slides/piesplittype).

**القيمة المرجعة:**
int

### setPieSplitBy(int value) {#setPieSplitBy-int-}
```
public final void setPieSplitBy(int value)
```

يحدد كيفية تحديد أي نقاط البيانات تكون في الفطيرة أو الشريط الثاني في مخطط الفطيرة-من-فطيرة أو الشريط-من-فطيرة. قابل للقراءة/الكتابة [PieSplitType](../../com.aspose.slides/piesplittype).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### isColorVaried() {#isColorVaried--}
```
public final boolean isColorVaried()
```

يحدد أن كل علامة بيانات في السلسلة لها لون مختلف. قابل للقراءة/الكتابة boolean.

**القيمة المرجعة:**
boolean

### setColorVaried(boolean value) {#setColorVaried-boolean-}
```
public final void setColorVaried(boolean value)
```

يحدد أن كل علامة بيانات في السلسلة لها لون مختلف. قابل للقراءة/الكتابة boolean.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### hasSeriesLines() {#hasSeriesLines--}
```
public final boolean hasSeriesLines()
```

صحيح إذا كان المخطط يحتوي على خطوط السلسلة. يُطبّق على المخططات المكدسة من نوع Bar و OfPie. قابل للقراءة/الكتابة boolean.

**القيمة المرجعة:**
boolean

### setSeriesLines(boolean value) {#setSeriesLines-boolean-}
```
public final void setSeriesLines(boolean value)
```

صحيح إذا كان المخطط يحتوي على خطوط السلسلة. يُطبّق على المخططات المكدسة من نوع Bar و OfPie. قابل للقراءة/الكتابة boolean.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getHiLowLinesFormat() {#getHiLowLinesFormat--}
```
public final IChartLinesFormat getHiLowLinesFormat()
```

يحدد تنسيق HiLowLines. يُطبّق HiLowLines مع أنواع المخططات HiLowClose, OpenHiLowClose, VolumeHiLowClose و VolumeOpenHiLowClose.

**القيمة المرجعة:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)

### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public final int getBubbleSizeScale()
```

يحدد عامل المقياس لمخطط الفقاعات (يمكن أن يكون بين 0 و 300 بالمائة من الحجم الافتراضي). قابل للقراءة/الكتابة int.

**القيمة المرجعة:**
int

### setBubbleSizeScale(int value) {#setBubbleSizeScale-int-}
```
public final void setBubbleSizeScale(int value)
```

يحدد عامل المقياس لمخطط الفقاعات (يمكن أن يكون بين 0 و 300 بالمائة من الحجم الافتراضي). قابل للقراءة/الكتابة int.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public final IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

معلومات الانقسام المخصص لمخطط الفطيرة-من-فطيرة أو الشريط-من-فطيرة مع انقسام مخصص. يحتوي على نقاط بيانات تُرسم في الفطيرة أو الشريط الثاني في مخطط الفطيرة-من-فطيرة أو الشريط-من-فطيرة. للقراءة فقط [PieSplitCustomPointCollection](../../com.aspose.slides/piesplitcustompointcollection).

**القيمة المرجعة:**
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

يرجع كائن Parent_Immediate. للقراءة فقط IDOMObject.

**القيمة المرجعة:**
com.aspose.slides.IDOMObject

### getChart() {#getChart--}
```
public final IChart getChart()
```

يرجع المخطط الأب. للقراءة فقط [IChart](../../com.aspose.slides/ichart).

**القيمة المرجعة:**
[IChart](../../com.aspose.slides/ichart)

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

يرجع الشريحة الأب لـ FillFormat. للقراءة فقط [BaseSlide](../../com.aspose.slides/baseslide).

**القيمة المرجعة:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

يرجع العرض التقديمي الأب لـ FillFormat. للقراءة فقط [IPresentation](../../com.aspose.slides/ipresentation).

**القيمة المرجعة:**
[IPresentation](../../com.aspose.slides/ipresentation)