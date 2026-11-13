---
title: ChartSeriesGroup
second_title: مرجع API لـ Aspose.Slides للـ Java
description: يمثل مجموعة من السلاسل.
type: docs
url: /ar/com.aspose.slides/chartseriesgroup/
---
**الوراثة:**  
java.lang.Object

**جميع الواجهات المُنفذة:**  
[com.aspose.slides.IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup), com.aspose.slides.IDOMObject  
```
public class ChartSeriesGroup implements IChartSeriesGroup, IDOMObject
```

يمثل مجموعة من السلاسل.

--------------------

1) راجع الملخص والملاحظات لفئة ChartSeriesGroupCollection والعدد CombinableSeriesTypesGroup. 2) تحتوي مجموعة السلاسل على بعض خصائص السلسلة التي هي مشتركة لكل سلسلة في المجموعة ("series group properties"). "Series group properties" في فئة ChartSeriesGroup هي قراءة/كتابة. يمكن لكل من "series group properties" أن يكون لها تمثيل للقراءة فقط في فئة ChartSeries.

## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getType()](#getType--) | يُرجع نوعًا لمجموعة السلاسل هذه. |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | يُشير إلى ما إذا كانت سلاسل هذه المجموعة مرسومة على محور ثانوي. |
| [getSeries()](#getSeries--) | يُرجع مجموعة من السلاسل. |
| [get_Item(int index)](#get-Item-int-) | يحصل على العنصر في الفهرس المحدد. |
| [getUpDownBars()](#getUpDownBars--) | يوفر الوصول إلى أشرطة الصعود/الهبوط في مخطط الخط أو المخطط السهمي. |
| [getGapWidth()](#getGapWidth--) | يحصل أو يحدد المسافة بين مجموعات الأعمدة أو الأشرطة كنسبة مئوية من عرض العمود أو الشريط. |
| [setGapWidth(int value)](#setGapWidth-int-) | يحصل أو يحدد المسافة بين مجموعات الأعمدة أو الأشرطة كنسبة مئوية من عرض العمود أو الشريط. |
| [getGapDepth()](#getGapDepth--) | يحصل أو يحدد المسافة بين سلاسل البيانات في مخطط ثلاثي الأبعاد كنسبة مئوية من عرض العلامة. |
| [setGapDepth(int value)](#setGapDepth-int-) | يحصل أو يحدد المسافة بين سلاسل البيانات في مخطط ثلاثي الأبعاد كنسبة مئوية من عرض العلامة. |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | يحصل أو يحدد زاوية الشريحة الأولى في مخطط الفطيرة أو المخطط الإسطواني، بالدرجات (مع اتجاه عقارب الساعة من الأعلى، من 0 إلى 360 درجة). |
| [setFirstSliceAngle(int value)](#setFirstSliceAngle-int-) | يحصل أو يحدد زاوية الشريحة الأولى في مخطط الفطيرة أو المخطط الإسطواني، بالدرجات (مع اتجاه عقارب الساعة من الأعلى، من 0 إلى 360 درجة). |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | يحدد حجم الفتحة في مخطط الإسطواني (يمكن أن يكون بين 0 و90 بالمائة من حجم مساحة الرسم). |
| [setDoughnutHoleSize(byte value)](#setDoughnutHoleSize-byte-) | يحدد حجم الفتحة في مخطط الإسطواني (يمكن أن يكون بين 0 و90 بالمائة من حجم مساحة الرسم). |
| [getOverlap()](#getOverlap--) | يحدد مقدار تداخل الأعمدة والأشرطة في المخططات ثنائية الأبعاد كنسبة مئوية (من -100% إلى 100%). |
| [setOverlap(byte value)](#setOverlap-byte-) | يحدد مقدار تداخل الأعمدة والأشرطة في المخططات ثنائية الأبعاد كنسبة مئوية (من -100% إلى 100%). |
| [getSecondPieSize()](#getSecondPieSize--) | يحدد حجم الفطيرة أو الشريط الثاني في مخطط الفطيرة داخل الفطيرة أو مخطط الشريط داخل الفطيرة كنسبة مئوية من حجم الفطيرة الأولى (يمكن أن يكون بين 5 و200 بالمائة). |
| [setSecondPieSize(int value)](#setSecondPieSize-int-) | يحدد حجم الفطيرة أو الشريط الثاني في مخطط الفطيرة داخل الفطيرة أو مخطط الشريط داخل الفطيرة كنسبة مئوية من حجم الفطيرة الأولى (يمكن أن يكون بين 5 و200 بالمائة). |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | يحدد كيفية تمثيل قيم حجم الفقاعات في مخطط الفقاعات. |
| [setBubbleSizeRepresentation(int value)](#setBubbleSizeRepresentation-int-) | يحدد كيفية تمثيل قيم حجم الفقاعات في مخطط الفقاعات. |
| [getPieSplitPosition()](#getPieSplitPosition--) | يحدد قيمة تُستخدم لتحديد أي نقاط البيانات تكون في الفطيرة أو الشريط الثاني في مخطط الفطيرة داخل الفطيرة أو مخطط الشريط داخل الفطيرة. |
| [setPieSplitPosition(double value)](#setPieSplitPosition-double-) | يحدد قيمة تُستخدم لتحديد أي نقاط البيانات تكون في الفطيرة أو الشريط الثاني في مخطط الفطيرة داخل الفطيرة أو مخطط الشريط داخل الفطيرة. |
| [getPieSplitBy()](#getPieSplitBy--) | يحدد كيفية تحديد أي نقاط البيانات تكون في الفطيرة أو الشريط الثاني في مخطط الفطيرة داخل الفطيرة أو مخطط الشريط داخل الفطيرة. |
| [setPieSplitBy(int value)](#setPieSplitBy-int-) | يحدد كيفية تحديد أي نقاط البيانات تكون في الفطيرة أو الشريط الثاني في مخطط الفطيرة داخل الفطيرة أو مخطط الشريط داخل الفطيرة. |
| [isColorVaried()](#isColorVaried--) | يحدد أن كل علامة بيانات في السلسلة لها لون مختلف. |
| [setColorVaried(boolean value)](#setColorVaried-boolean-) | يحدد أن كل علامة بيانات في السلسلة لها لون مختلف. |
| [hasSeriesLines()](#hasSeriesLines--) | True إذا كان المخطط يحتوي على خطوط السلسلة. |
| [setSeriesLines(boolean value)](#setSeriesLines-boolean-) | True إذا كان المخطط يحتوي على خطوط السلسلة. |
| [getHiLowLinesFormat()](#getHiLowLinesFormat--) | يحدد تنسيق HiLowLines. |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | يحدد معامل المقياس لمخطط الفقاعات (يمكن أن يكون بين 0 و300 بالمائة من الحجم الافتراضي). |
| [setBubbleSizeScale(int value)](#setBubbleSizeScale-int-) | يحدد معامل المقياس لمخطط الفقاعات (يمكن أن يكون بين 0 و300 بالمائة من الحجم الافتراضي). |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | معلومات الانقسام المخصص لمخطط الفطيرة داخل الفطيرة أو مخطط الشريط داخل الفطيرة مع انقسام مخصص. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getChart()](#getChart--) | يُرجع المخطط الأب. |
| [getSlide()](#getSlide--) | يُرجع الشريحة الأب لتنسيق التعبئة. |
| [getPresentation()](#getPresentation--) | يُرجع العرض التقديمي الأب لتنسيق التعبئة. |

### getType() {#getType--}
```
public final int getType()
```

يُرجع نوعًا لمجموعة السلاسل هذه. للقراءة فقط [CombinableSeriesTypesGroup](../../com.aspose.slides/combinableseriestypesgroup).

**الإرجاع:**  
int

### getPlotOnSecondAxis() {#getPlotOnSecondAxis--}
```
public final boolean getPlotOnSecondAxis()
```

يُشير إلى ما إذا كانت سلاسل هذه المجموعة مرسومة على محور ثانوي. للقراءة فقط boolean.

**الإرجاع:**  
boolean

### getSeries() {#getSeries--}
```
public final IChartSeriesReadonlyCollection getSeries()
```

يُرجع مجموعة من السلاسل. للقراءة فقط [IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection).

**الإرجاع:**  
[IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection)

### get_Item(int index) {#get-Item-int-}
```
public final IChartSeries get_Item(int index)
```

يحصل على العنصر في الفهرس المحدد.

**المعلمات:**  
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| index | int |  |

**الإرجاع:**  
[IChartSeries](../../com.aspose.slides/ichartseries)

### getUpDownBars() {#getUpDownBars--}
```
public final IUpDownBarsManager getUpDownBars()
```

يوفر الوصول إلى أشرطة الصعود/الهبوط في مخطط الخط أو المخطط السهمي. للقراءة فقط [IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager).

**الإرجاع:**  
[IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager)

### getGapWidth() {#getGapWidth--}
```
public final int getGapWidth()
```

يحصل أو يحدد المسافة بين مجموعات الأعمدة أو الأشرطة كنسبة مئوية من عرض العمود أو الشريط. يجب أن تكون القيمة بين 0 و 500. قراءة/كتابة int.

--------------------

تنطبق هذه الخاصية على سلاسل الأنواع التالية: الأنواع الفرعية Bar (انظر أيضًا طريقة [ChartTypeCharacterizer.isChartTypeBar(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBar-int-))، الأنواع الفرعية Column (انظر أيضًا طريقة [ChartTypeCharacterizer.isChartTypeColumn(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeColumn-int-))، [ChartType.BarOfPie](../../com.aspose.slides/charttype\#BarOfPie)، [ChartType.PieOfPie](../../com.aspose.slides/charttype\#PieOfPie)، [ChartType.BoxAndWhisker](../../com.aspose.slides/charttype\#BoxAndWhisker)، [ChartType.Funnel](../../com.aspose.slides/charttype\#Funnel)، [ChartType.Histogram](../../com.aspose.slides/charttype\#Histogram)، [ChartType.Waterfall](../../com.aspose.slides/charttype\#Waterfall).

**الإرجاع:**  
int

### setGapWidth(int value) {#setGapWidth-int-}
```
public final void setGapWidth(int value)
```

يحصل أو يحدد المسافة بين مجموعات الأعمدة أو الأشرطة كنسبة مئوية من عرض العمود أو الشريط. يجب أن تكون القيمة بين 0 و 500. قراءة/كتابة int.

--------------------

تنطبق هذه الخاصية على سلاسل الأنواع التالية: الأنواع الفرعية Bar (انظر أيضًا طريقة [ChartTypeCharacterizer.isChartTypeBar(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBar-int-))، الأنواع الفرعية Column (انظر أيضًا طريقة [ChartTypeCharacterizer.isChartTypeColumn(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeColumn-int-))، [ChartType.BarOfPie](../../com.aspose.slides/charttype\#BarOfPie)، [ChartType.PieOfPie](../../com.aspose.slides/charttype\#PieOfPie)، [ChartType.BoxAndWhisker](../../com.aspose.slides/charttype\#BoxAndWhisker)، [ChartType.Funnel](../../com.aspose.slides/charttype\#Funnel)، [ChartType.Histogram](../../com.aspose.slides/charttype\#Histogram)، [ChartType.Waterfall](../../com.aspose.slides/charttype\#Waterfall).

**المعلمات:**  
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getGapDepth() {#getGapDepth--}
```
public final int getGapDepth()
```

يحصل أو يحدد المسافة بين سلاسل البيانات في مخطط ثلاثي الأبعاد كنسبة مئوية من عرض العلامة. يجب أن تكون القيمة بين 0 و 500. قراءة/كتابة int.

--------------------

تنطبق هذه الخاصية على سلاسل الأنواع التالية: الأنواع الفرعية Bar و Column ثلاثية الأبعاد (انظر أيضًا طريقة [ChartTypeCharacterizer.isBar3DChart(int)](../../com.aspose.slides/charttypecharacterizer\#isBar3DChart-int-))، [ChartType.Line3D](../../com.aspose.slides/charttype\#Line3D)، [ChartType.Area3D](../../com.aspose.slides/charttype\#Area3D)، [ChartType.StackedArea3D](../../com.aspose.slides/charttype\#StackedArea3D)، [ChartType.PercentsStackedArea3D](../../com.aspose.slides/charttype\#PercentsStackedArea3D).

**الإرجاع:**  
int

### setGapDepth(int value) {#setGapDepth-int-}
```
public final void setGapDepth(int value)
```

يحصل أو يحدد المسافة بين سلاسل البيانات في مخطط ثلاثي الأبعاد كنسبة مئوية من عرض العلامة. يجب أن تكون القيمة بين 0 و 500. قراءة/كتابة int.

--------------------

تنطبق هذه الخاصية على سلاسل الأنواع التالية: الأنواع الفرعية Bar و Column ثلاثية الأبعاد (انظر أيضًا طريقة [ChartTypeCharacterizer.isBar3DChart(int)](../../com.aspose.slides/charttypecharacterizer\#isBar3DChart-int-))، [ChartType.Line3D](../../com.aspose.slides/charttype\#Line3D)، [ChartType.Area3D](../../com.aspose.slides/charttype\#Area3D)، [ChartType.StackedArea3D](../../com.aspose.slides/charttype\#StackedArea3D)، [ChartType.PercentsStackedArea3D](../../com.aspose.slides/charttype\#PercentsStackedArea3D).

**المعلمات:**  
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public final int getFirstSliceAngle()
```

يحصل أو يحدد زاوية الشريحة الأولى في مخطط الفطيرة أو المخطط الإسطواني، بالدرجات (مع اتجاه عقارب الساعة من الأعلى، من 0 إلى 360 درجة). قراءة/كتابة int.

**الإرجاع:**  
int

### setFirstSliceAngle(int value) {#setFirstSliceAngle-int-}
```
public final void setFirstSliceAngle(int value)
```

يحصل أو يحدد زاوية الشريحة الأولى في مخطط الفطيرة أو المخطط الإسطواني، بالدرجات (مع اتجاه عقارب الساعة من الأعلى، من 0 إلى 360 درجة). قراءة/كتابة int.

**المعلمات:**  
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public final byte getDoughnutHoleSize()
```

يحدد حجم الفتحة في مخطط الإسطواني (يمكن أن يكون بين 0 و90 بالمائة من حجم مساحة الرسم). قراءة/كتابة byte.

**الإرجاع:**  
byte

### setDoughnutHoleSize(byte value) {#setDoughnutHoleSize-byte-}
```
public final void setDoughnutHoleSize(byte value)
```

يحدد حجم الفتحة في مخطط الإسطواني (يمكن أن يكون بين 0 و90 بالمائة من حجم مساحة الرسم). قراءة/كتابة byte.

**المعلمات:**  
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getOverlap() {#getOverlap--}
```
public final byte getOverlap()
```

يحدد مقدار تداخل الأعمدة والأشرطة في المخططات ثنائية الأبعاد كنسبة مئوية (من -100% إلى 100%). -100%: أقصى مساحة بين الأعمدة (مفصولة بالكامل). 0%: الأعمدة موضوعة جنبًا إلى جنب دون تداخل أو مساحة. 100%: أقصى تداخل (الأعمدة تتداخل تمامًا). هذه الخاصية قراءة/كتابة byte.

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

**الإرجاع:**  
byte

### setOverlap(byte value) {#setOverlap-byte-}
```
public final void setOverlap(byte value)
```

يحدد مقدار تداخل الأعمدة والأشرطة في المخططات ثنائية الأبعاد كنسبة مئوية (من -100% إلى 100%). -100%: أقصى مساحة بين الأعمدة (مفصولة بالكامل). 0%: الأعمدة موضوعة جنبًا إلى جنب دون تداخل أو مساحة. 100%: أقصى تداخل (الأعمدة تتداخل تمامًا). هذه الخاصية قراءة/كتابة byte.

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
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getSecondPieSize() {#getSecondPieSize--}
```
public final int getSecondPieSize()
```

يحدد حجم الفطيرة أو الشريط الثاني في مخطط الفطيرة داخل الفطيرة أو مخطط الشريط داخل الفطيرة كنسبة مئوية من حجم الفطيرة الأولى (يمكن أن يكون بين 5 و200 بالمائة). قراءة/كتابة int.

**الإرجاع:**  
int

### setSecondPieSize(int value) {#setSecondPieSize-int-}
```
public final void setSecondPieSize(int value)
```

يحدد حجم الفطيرة أو الشريط الثاني في مخطط الفطيرة داخل الفطيرة أو مخطط الشريط داخل الفطيرة كنسبة مئوية من حجم الفطيرة الأولى (يمكن أن يكون بين 5 و200 بالمائة). قراءة/كتابة int.

**المعلمات:**  
| المعلمة | النوع | الوصف |
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

**المعلمات:**  
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getPieSplitPosition() {#getPieSplitPosition--}
```
public final double getPieSplitPosition()
```

يحدد قيمة تُستخدم لتحديد أي نقاط البيانات تكون في الفطيرة أو الشريط الثاني في مخطط الفطيرة داخل الفطيرة أو مخطط الشريط داخل الفطيرة. يُستخدم مع الخاصية PieSplitBy. قراءة/كتابة double.

**الإرجاع:**  
double

### setPieSplitPosition(double value) {#setPieSplitPosition-double-}
```
public final void setPieSplitPosition(double value)
```

يحدد قيمة تُستخدم لتحديد أي نقاط البيانات تكون في الفطيرة أو الشريط الثاني في مخطط الفطيرة داخل الفطيرة أو مخطط الشريط داخل الفطيرة. يُستخدم مع الخاصية PieSplitBy. قراءة/كتابة double.

**المعلمات:**  
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | double |  |

### getPieSplitBy() {#getPieSplitBy--}
```
public final int getPieSplitBy()
```

يحدد كيفية تحديد أي نقاط البيانات تكون في الفطيرة أو الشريط الثاني في مخطط الفطيرة داخل الفطيرة أو مخطط الشريط داخل الفطيرة. قراءة/كتابة [PieSplitType](../../com.aspose.slides/piesplittype).

**الإرجاع:**  
int

### setPieSplitBy(int value) {#setPieSplitBy-int-}
```
public final void setPieSplitBy(int value)
```

يحدد كيفية تحديد أي نقاط البيانات تكون في الفطيرة أو الشريط الثاني في مخطط الفطيرة داخل الفطيرة أو مخطط الشريط داخل الفطيرة. قراءة/كتابة [PieSplitType](../../com.aspose.slides/piesplittype).

**المعلمات:**  
| المعلمة | النوع | الوصف |
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

**المعلمات:**  
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### hasSeriesLines() {#hasSeriesLines--}
```
public final boolean hasSeriesLines()
```

True إذا كان المخطط يحتوي على خطوط السلسلة. يطبق على مخططات Bar المتراصة ومخططات OfPie. قراءة/كتابة boolean.

**الإرجاع:**  
boolean

### setSeriesLines(boolean value) {#setSeriesLines-boolean-}
```
public final void setSeriesLines(boolean value)
```

True إذا كان المخطط يحتوي على خطوط السلسلة. يطبق على مخططات Bar المتراصة ومخططات OfPie. قراءة/كتابة boolean.

**المعلمات:**  
| المعلمة | النوع | الوصف |
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

يحدد معامل المقياس لمخطط الفقاعات (يمكن أن يكون بين 0 و300 بالمائة من الحجم الافتراضي). قراءة/كتابة int.

**الإرجاع:**  
int

### setBubbleSizeScale(int value) {#setBubbleSizeScale-int-}
```
public final void setBubbleSizeScale(int value)
```

يحدد معامل المقياس لمخطط الفقاعات (يمكن أن يكون بين 0 و300 بالمائة من الحجم الافتراضي). قراءة/كتابة int.

**المعلمات:**  
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public final IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

معلومات الانقسام المخصص لمخطط الفطيرة داخل الفطيرة أو مخطط الشريط داخل الفطيرة مع انقسام مخصص. يحتوي على نقاط البيانات التي تُرسم في الفطيرة أو الشريط الثاني. للقراءة فقط [PieSplitCustomPointCollection](../../com.aspose.slides/piesplitcustompointcollection).

**الإرجاع:**  
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

يُرجع كائن Parent_Immediate. للقراءة فقط IDOMObject.

**الإرجاع:**  
com.aspose.slides.IDOMObject

### getChart() {#getChart--}
```
public final IChart getChart()
```

يُرجع المخطط الأب. للقراءة فقط [IChart](../../com.aspose.slides/ichart).

**الإرجاع:**  
[IChart](../../com.aspose.slides/ichart)

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

يُرجع الشريحة الأب لتنسيق التعبئة. للقراءة فقط [BaseSlide](../../com.aspose.slides/baseslide).

**الإرجاع:**  
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

يُرجع العرض التقديمي الأب لتنسيق التعبئة. للقراءة فقط [IPresentation](../../com.aspose.slides/ipresentation).

**الإرجاع:**  
[IPresentation](../../com.aspose.slides/ipresentation)