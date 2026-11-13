---
title: IChartSeriesGroup
second_title: مرجع API لـ Aspose.Slides للـ Java
description: يمثل مجموعة من السلاسل.
type: docs
url: /ar/com.aspose.slides/ichartseriesgroup/
---
**جميع الواجهات المنفذة:**
[com.aspose.slides.IChartComponent](../../com.aspose.slides/ichartcomponent)
```
public interface IChartSeriesGroup extends IChartComponent
```

يمثل مجموعة من السلاسل.

--------------------

1) راجع الملخص والملاحظات لفئة ChartSeriesGroupCollection والعدد CombinableSeriesTypesGroup. 2) مجموعة السلاسل تحتوي على بعض خصائص السلسلة التي هي مشتركة لكل سلسلة في المجموعة ("series group properties"). "Series group properties" في فئة ChartSeriesGroup هي قراءة/كتابة. كل من "series group properties" يمكن أن يكون له تمثيل قراءة فقط في فئة ChartSeries.

## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getType()](#getType--) | يعيد نوعًا لهذه المجموعة من السلاسل. |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | يشير إلى ما إذا كانت سلاسل هذه المجموعة مرسومة على المحور الثانوي. |
| [getSeries()](#getSeries--) | يعيد مجموعة قراءة فقط من سلاسل المخطط. |
| [get_Item(int index)](#get-Item-int-) | يحصل على العنصر عند الفهرس المحدد. |
| [getUpDownBars()](#getUpDownBars--) | يوفر وصولًا إلى أشرطة الصعود/الهبوط لمخطط الخط أو المخطط السهمي. |
| [getGapWidth()](#getGapWidth--) | يحصل أو يعيّن المسافة بين مجموعات الأعمدة أو الشرائح، كنسبة مئوية من عرض العمود أو الشريحة. |
| [setGapWidth(int value)](#setGapWidth-int-) | يحصل أو يعيّن المسافة بين مجموعات الأعمدة أو الشرائح، كنسبة مئوية من عرض العمود أو الشريحة. |
| [getGapDepth()](#getGapDepth--) | يحصل أو يعيّن المسافة بين سلاسل البيانات في مخطط ثلاثي الأبعاد، كنسبة مئوية من عرض العلامة. |
| [setGapDepth(int value)](#setGapDepth-int-) | يحصل أو يعيّن المسافة بين سلاسل البيانات في مخطط ثلاثي الأبعاد، كنسبة مئوية من عرض العلامة. |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | يحصل أو يعيّن زاوية أول قطعة من مخطط الفطيرة أو الدونات، بالدرجات (مع عقارب الساعة من الأعلى، من 0 إلى 360 درجة). |
| [setFirstSliceAngle(int value)](#setFirstSliceAngle-int-) | يحصل أو يعيّن زاوية أول قطعة من مخطط الفطيرة أو الدونات، بالدرجات (مع عقارب الساعة من الأعلى، من 0 إلى 360 درجة). |
| [isColorVaried()](#isColorVaried--) | يحدد أن كل علامة بيانات في السلسلة لها لون مختلف. |
| [setColorVaried(boolean value)](#setColorVaried-boolean-) | يحدد أن كل علامة بيانات في السلسلة لها لون مختلف. |
| [hasSeriesLines()](#hasSeriesLines--) | صحيح إذا كان المخطط يحتوي على خطوط السلسلة. |
| [setSeriesLines(boolean value)](#setSeriesLines-boolean-) | صحيح إذا كان المخطط يحتوي على خطوط السلسلة. |
| [getOverlap()](#getOverlap--) | يحدد مقدار تداخل الشرائط والأعمدة على المخططات الثنائية الأبعاد، كنسبة مئوية (من -100% إلى 100%). |
| [setOverlap(byte value)](#setOverlap-byte-) | يحدد مقدار تداخل الشرائط والأعمدة على المخططات الثنائية الأبعاد، كنسبة مئوية (من -100% إلى 100%). |
| [getSecondPieSize()](#getSecondPieSize--) | يحدد حجم الفطيرة أو الشريط الثاني في مخطط فطيرة-من-فطيرة أو شريط-من-فطيرة، كنسبة مئوية من حجم الفطيرة الأولى (يمكن أن يكون بين 5 و 200 في المئة). |
| [setSecondPieSize(int value)](#setSecondPieSize-int-) | يحدد حجم الفطيرة أو الشريط الثاني في مخطط فطيرة-من-فطيرة أو شريط-من-فطيرة، كنسبة مئوية من حجم الفطيرة الأولى (يمكن أن يكون بين 5 و 200 في المئة). |
| [getPieSplitPosition()](#getPieSplitPosition--) | يحدد قيمة تُستخدم لتحديد أي نقاط البيانات تكون في الفطيرة أو الشريط الثاني على مخطط فطيرة-من-فطيرة أو شريط-من-فطيرة. |
| [setPieSplitPosition(double value)](#setPieSplitPosition-double-) | يحدد قيمة تُستخدم لتحديد أي نقاط البيانات تكون في الفطيرة أو الشريط الثاني على مخطط فطيرة-من-فطيرة أو شريط-من-فطيرة. |
| [getPieSplitBy()](#getPieSplitBy--) | يحدد كيفية تحديد أي نقاط البيانات تكون في الفطيرة أو الشريط الثاني على مخطط فطيرة-من-فطيرة أو شريط-من-فطيرة. |
| [setPieSplitBy(int value)](#setPieSplitBy-int-) | يحدد كيفية تحديد أي نقاط البيانات تكون في الفطيرة أو الشريط الثاني على مخطط فطيرة-من-فطيرة أو شريط-من-فطيرة. |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | معلومات الانقسام المخصص لمخطط فطيرة-من-فطيرة أو شريط-من-فطيرة مع انقسام مخصص. |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | يحدد حجم الفتحة في مخطط الدونات (يمكن أن يكون بين 10 و 90 في المئة من حجم منطقة الرسم). |
| [setDoughnutHoleSize(byte value)](#setDoughnutHoleSize-byte-) | يحدد حجم الفتحة في مخطط الدونات (يمكن أن يكون بين 10 و 90 في المئة من حجم منطقة الرسم). |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | يحدد معامل المقياس لمخطط الفقاعات (يمكن أن يكون بين 0 و 300 في المئة من الحجم الافتراضي). |
| [setBubbleSizeScale(int value)](#setBubbleSizeScale-int-) | يحدد معامل المقياس لمخطط الفقاعات (يمكن أن يكون بين 0 و 300 في المئة من الحجم الافتراضي). |
| [getHiLowLinesFormat()](#getHiLowLinesFormat--) | يحدد تنسيق HiLowLines. |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | يحدد كيفية تمثيل قيم حجم الفقاعات على مخطط الفقاعات. |
| [setBubbleSizeRepresentation(int value)](#setBubbleSizeRepresentation-int-) | يحدد كيفية تمثيل قيم حجم الفقاعات على مخطط الفقاعات. |

### getType() {#getType--}
```
public abstract int getType()
```

يعيد نوعًا لهذه المجموعة من السلاسل. قراءة فقط [CombinableSeriesTypesGroup](../../com.aspose.slides/combinableseriestypesgroup).

**الإرجاع:**
int

### getPlotOnSecondAxis() {#getPlotOnSecondAxis--}
```
public abstract boolean getPlotOnSecondAxis()
```

يشير إلى ما إذا كانت سلاسل هذه المجموعة مرسومة على المحور الثانوي. قراءة فقط boolean.

**الإرجاع:**
boolean

### getSeries() {#getSeries--}
```
public abstract IChartSeriesReadonlyCollection getSeries()
```

يعيد مجموعة قراءة فقط من سلاسل المخطط. قراءة فقط [IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection).

**الإرجاع:**
[IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection)

### get_Item(int index) {#get-Item-int-}
```
public abstract IChartSeries get_Item(int index)
```

يحصل على العنصر عند الفهرس المحدد.

**المعلمات:**
| المُعامل | النوع | الوصف |
| --- | --- | --- |
| index | int |  |

**الإرجاع:**
[IChartSeries](../../com.aspose.slides/ichartseries)

### getUpDownBars() {#getUpDownBars--}
```
public abstract IUpDownBarsManager getUpDownBars()
```

يوفر وصولًا إلى أشرطة الصعود/الهبوط لمخطط الخط أو المخطط السهمي. قراءة فقط [IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager).

**الإرجاع:**
[IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager)

### getGapWidth() {#getGapWidth--}
```
public abstract int getGapWidth()
```

يحصل أو يعيّن المسافة بين مجموعات الشرائح أو الأعمدة، كنسبة مئوية من عرض الشريحة أو العمود. يجب أن تكون القيمة بين 0 و 500. قراءة/كتابة int.

--------------------

ينطبق هذا الخاصية على سلاسل الأنواع التالية: جميع الأنواع الفرعية للأعمدة والشرائح، [ChartType.BarOfPie](../../com.aspose.slides/charttype\#BarOfPie), [ChartType.PieOfPie](../../com.aspose.slides/charttype\#PieOfPie), [ChartType.BoxAndWhisker](../../com.aspose.slides/charttype\#BoxAndWhisker), [ChartType.Funnel](../../com.aspose.slides/charttype\#Funnel), [ChartType.Histogram](../../com.aspose.slides/charttype\#Histogram), [ChartType.Waterfall](../../com.aspose.slides/charttype\#Waterfall).

**الإرجاع:**
int

### setGapWidth(int value) {#setGapWidth-int-}
```
public abstract void setGapWidth(int value)
```

يحصل أو يعيّن المسافة بين مجموعات الشرائح أو الأعمدة، كنسبة مئوية من عرض الشريحة أو العمود. يجب أن تكون القيمة بين 0 و 500. قراءة/كتابة int.

--------------------

ينطبق هذا الخاصية على سلاسل الأنواع التالية: جميع الأنواع الفرعية للأعمدة والشرائح، [ChartType.BarOfPie](../../com.aspose.slides/charttype\#BarOfPie), [ChartType.PieOfPie](../../com.aspose.slides/charttype\#PieOfPie), [ChartType.BoxAndWhisker](../../com.aspose.slides/charttype\#BoxAndWhisker), [ChartType.Funnel](../../com.aspose.slides/charttype\#Funnel), [ChartType.Histogram](../../com.aspose.slides/charttype\#Histogram), [ChartType.Waterfall](../../com.aspose.slides/charttype\#Waterfall).

**المعلمات:**
| المُعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getGapDepth() {#getGapDepth--}
```
public abstract int getGapDepth()
```

يحصل أو يعيّن المسافة بين سلاسل البيانات في مخطط ثلاثي الأبعاد، كنسبة مئوية من عرض العلامة. يجب أن تكون القيمة بين 0 و 500. قراءة/كتابة int.

--------------------

ينطبق هذا الخاصية على سلاسل الأنواع التالية: الأنواع الفرعية للأعمدة والشرائح ثلاثية الأبعاد، [ChartType.Line3D](../../com.aspose.slides/charttype\#Line3D), [ChartType.Area3D](../../com.aspose.slides/charttype\#Area3D), [ChartType.StackedArea3D](../../com.aspose.slides/charttype\#StackedArea3D), [ChartType.PercentsStackedArea3D](../../com.aspose.slides/charttype\#PercentsStackedArea3D).

**الإرجاع:**
int

### setGapDepth(int value) {#setGapDepth-int-}
```
public abstract void setGapDepth(int value)
```

يحصل أو يعيّن المسافة بين سلاسل البيانات في مخطط ثلاثي الأبعاد، كنسبة مئوية من عرض العلامة. يجب أن تكون القيمة بين 0 و 500. قراءة/كتابة int.

--------------------

ينطبق هذا الخاصية على سلاسل الأنواع التالية: الأنواع الفرعية للأعمدة والشرائط ثلاثية الأبعاد، [ChartType.Line3D](../../com.aspose.slides/charttype\#Line3D), [ChartType.Area3D](../../com.aspose.slides/charttype\#Area3D), [ChartType.StackedArea3D](../../com.aspose.slides/charttype\#StackedArea3D), [ChartType.PercentsStackedArea3D](../../com.aspose.slides/charttype\#PercentsStackedArea3D).

**المعلمات:**
| المُعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public abstract int getFirstSliceAngle()
```

يحصل أو يعيّن زاوية أول قطعة من مخطط الفطيرة أو الدونات، بالدرجات (مع عقارب الساعة من الأعلى، من 0 إلى 360 درجة). قراءة/كتابة int.

**الإرجاع:**
int

### setFirstSliceAngle(int value) {#setFirstSliceAngle-int-}
```
public abstract void setFirstSliceAngle(int value)
```

يحصل أو يعيّن زاوية أول قطعة من مخطط الفطيرة أو الدونات، بالدرجات (مع عقارب الساعة من الأعلى، من 0 إلى 360 درجة). قراءة/كتابة int.

**المعلمات:**
| المُعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### isColorVaried() {#isColorVaried--}
```
public abstract boolean isColorVaried()
```

يحدد أن كل علامة بيانات في السلسلة لها لون مختلف. قراءة/كتابة boolean.

**الإرجاع:**
boolean

### setColorVaried(boolean value) {#setColorVaried-boolean-}
```
public abstract void setColorVaried(boolean value)
```

يحدد أن كل علامة بيانات في السلسلة لها لون مختلف. قراءة/كتابة boolean.

**المعلمات:**
| المُعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### hasSeriesLines() {#hasSeriesLines--}
```
public abstract boolean hasSeriesLines()
```

صحيح إذا كان المخطط يحتوي على خطوط السلسلة. يُطبق على مخططات الأعمدة المتراصة ومخططات OfPie. قراءة/كتابة boolean.

**الإرجاع:**
boolean

### setSeriesLines(boolean value) {#setSeriesLines-boolean-}
```
public abstract void setSeriesLines(boolean value)
```

صحيح إذا كان المخطط يحتوي على خطوط السلسلة. يُطبق على مخططات الأعمدة المتراصة ومخططات OfPie. قراءة/كتابة boolean.

**المعلمات:**
| المُعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getOverlap() {#getOverlap--}
```
public abstract byte getOverlap()
```

يحدد مقدار تداخل الشرائط والأعمدة على المخططات الثنائية الأبعاد، كنسبة مئوية (من -100% إلى 100%). - -100%: أقصى مسافة (الشرائط منفصلة تمامًا). - 0%: تُوضع الشرائط جنبًا إلى جنب دون تداخل أو مسافة. - 100%: أقصى تداخل (الشرائط تتداخل تمامًا). الخاصية قراءة/كتابة byte.

--------------------

> ```
> The following example demonstrates how to set the overlap for a chart series group 
>   and render the resulting chart on a form:
>   
>  Presentation pres = new Presentation();
>  try {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.ClusteredColumn, 10, 10, 600, 300);
>      IChartSeriesCollection series = chart.getChartData().getSeries();
>      series.get_Item(0).getParentSeriesGroup().setOverlap((byte)55); // تعيين التداخل إلى 55%
>      pres.getSlides().get_Item(0).getImage(1, 1).save("chart.png");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**الإرجاع:**
byte

### setOverlap(byte value) {#setOverlap-byte-}
```
public abstract void setOverlap(byte value)
```

يحدد مقدار تداخل الشرائط والأعمدة على المخططات الثنائية الأبعاد، كنسبة مئوية (من -100% إلى 100%). - -100%: أقصى مسافة (الشرائط منفصلة تمامًا). - 0%: تُوضع الشرائط جنبًا إلى جنب دون تداخل أو مسافة. - 100%: أقصى تداخل (الشرائط تتداخل تمامًا). الخاصية قراءة/كتابة byte.

--------------------

> ```
> The following example demonstrates how to set the overlap for a chart series group 
>   and render the resulting chart on a form:
>   
>  Presentation pres = new Presentation();
>  try {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.ClusteredColumn, 10, 10, 600, 300);
>      IChartSeriesCollection series = chart.getChartData().getSeries();
>      series.get_Item(0).getParentSeriesGroup().setOverlap((byte)55); // تعيين التداخل إلى 55%
>      pres.getSlides().get_Item(0).getImage(1, 1).save("chart.png", ImageFormat.Png);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**المعلمات:**
| المُعامل | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getSecondPieSize() {#getSecondPieSize--}
```
public abstract int getSecondPieSize()
```

يحدد حجم الفطيرة أو الشريط الثاني في مخطط فطيرة-من-فطيرة أو شريط-من-فطيرة، كنسبة مئوية من حجم الفطيرة الأولى (يمكن أن يكون بين 5 و 200 في المئة). قراءة/كتابة int.

**الإرجاع:**
int

### setSecondPieSize(int value) {#setSecondPieSize-int-}
```
public abstract void setSecondPieSize(int value)
```

يحدد حجم الفطيرة أو الشريط الثاني في مخطط فطيرة-من-فطيرة أو شريط-من-فطيرة، كنسبة مئوية من حجم الفطيرة الأولى (يمكن أن يكون بين 5 و 200 في المئة). قراءة/كتابة int.

**المعلمات:**
| المُعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getPieSplitPosition() {#getPieSplitPosition--}
```
public abstract double getPieSplitPosition()
```

يحدد قيمة تُستخدم لتحديد أي نقاط البيانات تكون في الفطيرة أو الشريط الثاني على مخطط فطيرة-من-فطيرة أو شريط-من-فطيرة. تُستخدم مع خاصية PieSplitBy. قراءة/كتابة double.

**الإرجاع:**
double

### setPieSplitPosition(double value) {#setPieSplitPosition-double-}
```
public abstract void setPieSplitPosition(double value)
```

يحدد قيمة تُستخدم لتحديد أي نقاط البيانات تكون في الفطيرة أو الشريط الثاني على مخطط فطيرة-من-فطيرة أو شريط-من-فطيرة. تُستخدم مع خاصية PieSplitBy. قراءة/كتابة double.

**المعلمات:**
| المُعامل | النوع | الوصف |
| --- | --- | --- |
| value | double |  |

### getPieSplitBy() {#getPieSplitBy--}
```
public abstract int getPieSplitBy()
```

يحدد كيفية تحديد أي نقاط البيانات تكون في الفطيرة أو الشريط الثاني على مخطط فطيرة-من-فطيرة أو شريط-من-فطيرة. قراءة/كتابة [PieSplitType](../../com.aspose.slides/piesplittype).

**الإرجاع:**
int

### setPieSplitBy(int value) {#setPieSplitBy-int-}
```
public abstract void setPieSplitBy(int value)
```

يحدد كيفية تحديد أي نقاط البيانات تكون في الفطيرة أو الشريط الثاني على مخطط فطيرة-من-فطيرة أو شريط-من-فطيرة. قراءة/كتابة [PieSplitType](../../com.aspose.slides/piesplittype).

**المعلمات:**
| المُعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public abstract IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

معلومات الانقسام المخصص لمخطط فطيرة-من-فطيرة أو شريط-من-فطيرة مع انقسام مخصص. يحتوي على نقاط البيانات التي تُرسم في الفطيرة أو الشريط الثاني في مخطط فطيرة-من-فطيرة أو شريط-من-فطيرة. قراءة فقط [IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection).

**الإرجاع:**
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)

### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public abstract byte getDoughnutHoleSize()
```

يحدد حجم الفتحة في مخطط الدونات (يمكن أن يكون بين 10 و 90 في المئة من حجم منطقة الرسم). قراءة/كتابة byte.

**الإرجاع:**
byte

### setDoughnutHoleSize(byte value) {#setDoughnutHoleSize-byte-}
```
public abstract void setDoughnutHoleSize(byte value)
```

يحدد حجم الفتحة في مخطط الدونات (يمكن أن يكون بين 10 و 90 في المئة من حجم منطقة الرسم). قراءة/كتابة byte.

**المعلمات:**
| المُعامل | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public abstract int getBubbleSizeScale()
```

يحدد معامل المقياس لمخطط الفقاعات (يمكن أن يكون بين 0 و 300 في المئة من الحجم الافتراضي). قراءة/كتابة int.

**الإرجاع:**
int

### setBubbleSizeScale(int value) {#setBubbleSizeScale-int-}
```
public abstract void setBubbleSizeScale(int value)
```

يحدد معامل المقياس لمخطط الفقاعات (يمكن أن يكون بين 0 و 300 في المئة من الحجم الافتراضي). قراءة/كتابة int.

**المعلمات:**
| المُعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getHiLowLinesFormat() {#getHiLowLinesFormat--}
```
public abstract IChartLinesFormat getHiLowLinesFormat()
```

يحدد تنسيق HiLowLines. يتم تطبيق HiLowLines مع أنواع المخططات HiLowClose, OpenHiLowClose, VolumeHiLowClose و VolumeOpenHiLowClose.

**الإرجاع:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)

### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public abstract int getBubbleSizeRepresentation()
```

يحدد كيفية تمثيل قيم حجم الفقاعات على مخطط الفقاعات. قراءة/كتابة [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**الإرجاع:**
int

### setBubbleSizeRepresentation(int value) {#setBubbleSizeRepresentation-int-}
```
public abstract void setBubbleSizeRepresentation(int value)
```

يحدد كيفية تمثيل قيم حجم الفقاعات على مخطط الفقاعات. قراءة/كتابة [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**المعلمات:**
| المُعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |