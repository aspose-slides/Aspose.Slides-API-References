---
title: IChartSeriesGroup
second_title: مرجع API لجافا عبر Aspose.Slides لأندرويد
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

1) راجع الملخص والملاحظات لفئة ChartSeriesGroupCollection وعدد CombinableSeriesTypesGroup. 2) مجموعة السلاسل تحتوي على بعض خصائص السلسلة التي تكون مشتركة لكل سلسلة في المجموعة ("series group properties"). "Series group properties" في فئة ChartSeriesGroup هي قراءة/كتابة. يمكن لكل من "series group properties" أن يكون لها إسقاط للقراءة فقط في فئة ChartSeries.

## الأساليب

| الطريقة | الوصف |
| --- | --- |
| [getType()](#getType--) | إرجاع نوع مجموعة السلسلة هذه. |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | يشير ما إذا تم رسم سلاسل هذه المجموعة على محور ثانوي. |
| [getSeries()](#getSeries--) | إرجاع مجموعة قراءة فقط من سلاسل المخطط. |
| [get_Item(int index)](#get-Item-int-) | الحصول على العنصر في الفهرس المحدد. |
| [getUpDownBars()](#getUpDownBars--) | توفير الوصول إلى أشرطة الصعود/الهبوط في مخطط الخط أو مخطط الأسهم. |
| [getGapWidth()](#getGapWidth--) | تحديد المسافة بين مجموعات الأعمدة أو الأشرطة كنسبة مئوية من عرض العمود أو الشريط. |
| [setGapWidth(int value)](#setGapWidth-int-) | تحديد المسافة بين مجموعات الأعمدة أو الأشرطة كنسبة مئوية من عرض العمود أو الشريط. |
| [getGapDepth()](#getGapDepth--) | إرجاع أو تعيين المسافة، كنسبة مئوية من عرض العلامة، بين سلاسل البيانات في مخطط ثلاثي الأبعاد. |
| [setGapDepth(int value)](#setGapDepth-int-) | إرجاع أو تعيين المسافة، كنسبة مئوية من عرض العلامة، بين سلاسل البيانات في مخطط ثلاثي الأبعاد. |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | الحصول على أو تعيين زاوية الشريحة الأولى من مخطط الفطيرة أو الدونات، بالدرجات (في اتجاه عقارب الساعة من الأعلى، من 0 إلى 360 درجة). |
| [setFirstSliceAngle(int value)](#setFirstSliceAngle-int-) | الحصول على أو تعيين زاوية الشريحة الأولى من مخطط الفطيرة أو الدونات، بالدرجات (في اتجاه عقارب الساعة من الأعلى، من 0 إلى 360 درجة). |
| [isColorVaried()](#isColorVaried--) | تحديد أن كل علامة بيانات في السلسلة لديها لون مختلف. |
| [setColorVaried(boolean value)](#setColorVaried-boolean-) | تحديد أن كل علامة بيانات في السلسلة لديها لون مختلف. |
| [hasSeriesLines()](#hasSeriesLines--) | صحيح إذا كان المخطط يحتوي على خطوط السلسلة. |
| [setSeriesLines(boolean value)](#setSeriesLines-boolean-) | صحيح إذا كان المخطط يحتوي على خطوط السلسلة. |
| [getOverlap()](#getOverlap--) | تحديد مقدار تداخل الأشرطة والأعمدة في المخططات ثنائية الأبعاد كنسبة مئوية (من -100% إلى 100%). |
| [setOverlap(byte value)](#setOverlap-byte-) | تحديد مقدار تداخل الأشرطة والأعمدة في المخططات ثنائية الأبعاد كنسبة مئوية (من -100% إلى 100%). |
| [getSecondPieSize()](#getSecondPieSize--) | تحديد حجم الفطيرة أو العمود الثاني في مخطط فطيرة-من-فطيرة أو عمود-من-فطيرة، كنسبة مئوية من حجم الفطيرة الأولى (يمكن أن تكون بين 5 و200 في المئة). |
| [setSecondPieSize(int value)](#setSecondPieSize-int-) | تحديد حجم الفطيرة أو العمود الثاني في مخطط فطيرة-من-فطيرة أو عمود-من-فطيرة، كنسبة مئوية من حجم الفطيرة الأولى (يمكن أن تكون بين 5 و200 في المئة). |
| [getPieSplitPosition()](#getPieSplitPosition--) | تحديد قيمة تُستخدم لتحديد أي نقاط البيانات تكون في الفطيرة أو العمود الثاني في مخطط فطيرة-من-فطيرة أو عمود-من-فطيرة. |
| [setPieSplitPosition(double value)](#setPieSplitPosition-double-) | تحديد قيمة تُستخدم لتحديد أي نقاط البيانات تكون في الفطيرة أو العمود الثاني في مخطط فطيرة-من-فطيرة أو عمود-من-فطيرة. |
| [getPieSplitBy()](#getPieSplitBy--) | تحديد كيفية تحديد أي نقاط البيانات تكون في الفطيرة أو العمود الثاني في مخطط فطيرة-من-فطيرة أو عمود-من-فطيرة. |
| [setPieSplitBy(int value)](#setPieSplitBy-int-) | تحديد كيفية تحديد أي نقاط البيانات تكون في الفطيرة أو العمود الثاني في مخطط فطيرة-من-فطيرة أو عمود-من-فطيرة. |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | معلومات الانقسام المخصص لمخطط فطيرة-من-فطيرة أو عمود-من-فطيرة مع انقسام مخصص. |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | تحديد حجم الفتحة في مخطط الدونات (يمكن أن تكون بين 10 و90 في المئة من حجم مساحة الرسم). |
| [setDoughnutHoleSize(byte value)](#setDoughnutHoleSize-byte-) | تحديد حجم الفتحة في مخطط الدونات (يمكن أن تكون بين 10 و90 في المئة من حجم مساحة الرسم). |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | تحديد معامل المقياس لمخطط الفقاعات (يمكن أن يكون بين 0 و300 في المئة من الحجم الافتراضي). |
| [setBubbleSizeScale(int value)](#setBubbleSizeScale-int-) | تحديد معامل المقياس لمخطط الفقاعات (يمكن أن يكون بين 0 و300 في المئة من الحجم الافتراضي). |
| [getHiLowLinesFormat()](#getHiLowLinesFormat--) | تحديد تنسيق HiLowLines. |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | تحديد كيفية تمثيل قيم حجم الفقاعات في مخطط الفقاعات. |
| [setBubbleSizeRepresentation(int value)](#setBubbleSizeRepresentation-int-) | تحديد كيفية تمثيل قيم حجم الفقاعات في مخطط الفقاعات. |

### getType() {#getType--}
```
public abstract int getType()
```

إرجاع نوع مجموعة السلسلة هذه. قراءة فقط [CombinableSeriesTypesGroup](../../com.aspose.slides/combinableseriestypesgroup).

**الإرجاع:**
int

### getPlotOnSecondAxis() {#getPlotOnSecondAxis--}
```
public abstract boolean getPlotOnSecondAxis()
```

يشير ما إذا تم رسم سلاسل هذه المجموعة على محور ثانوي. قراءة فقط boolean.

**الإرجاع:**
boolean

### getSeries() {#getSeries--}
```
public abstract IChartSeriesReadonlyCollection getSeries()
```

إرجاع مجموعة قراءة فقط من سلاسل المخطط. قراءة فقط [IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection).

**الإرجاع:**
[IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection)

### get_Item(int index) {#get-Item-int-}
```
public abstract IChartSeries get_Item(int index)
```

الحصول على العنصر في الفهرس المحدد.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| index | int |  |

**الإرجاع:**
[IChartSeries](../../com.aspose.slides/ichartseries)

### getUpDownBars() {#getUpDownBars--}
```
public abstract IUpDownBarsManager getUpDownBars()
```

توفر الوصول إلى أشرطة الصعود/الهبوط في مخطط الخط أو مخطط الأسهم. قراءة فقط [IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager).

**الإرجاع:**
[IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager)

### getGapWidth() {#getGapWidth--}
```
public abstract int getGapWidth()
```

تحديد المسافة بين مجموعات الأعمدة أو الأشرطة كنسبة مئوية من عرض العمود أو الشريط. قراءة/كتابة int.

**الإرجاع:**
int

### setGapWidth(int value) {#setGapWidth-int-}
```
public abstract void setGapWidth(int value)
```

تحديد المسافة بين مجموعات الأعمدة أو الأشرطة كنسبة مئوية من عرض العمود أو الشريط. قراءة/كتابة int.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getGapDepth() {#getGapDepth--}
```
public abstract int getGapDepth()
```

إرجاع أو تعيين المسافة، كنسبة مئوية من عرض العلامة، بين سلاسل البيانات في مخطط ثلاثي الأبعاد. قراءة/كتابة int.

**الإرجاع:**
int

### setGapDepth(int value) {#setGapDepth-int-}
```
public abstract void setGapDepth(int value)
```

إرجاع أو تعيين المسافة، كنسبة مئوية من عرض العلامة، بين سلاسل البيانات في مخطط ثلاثي الأبعاد. قراءة/كتابة int.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public abstract int getFirstSliceAngle()
```

الحصول على أو تعيين زاوية الشريحة الأولى من مخطط الفطيرة أو الدونات، بالدرجات (في اتجاه عقارب الساعة من الأعلى، من 0 إلى 360 درجة). قراءة/كتابة int.

**الإرجاع:**
int

### setFirstSliceAngle(int value) {#setFirstSliceAngle-int-}
```
public abstract void setFirstSliceAngle(int value)
```

الحصول على أو تعيين زاوية الشريحة الأولى من مخطط الفطيرة أو الدونات، بالدرجات (في اتجاه عقارب الساعة من الأعلى، من 0 إلى 360 درجة). قراءة/كتابة int.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### isColorVaried() {#isColorVaried--}
```
public abstract boolean isColorVaried()
```

تحديد أن كل علامة بيانات في السلسلة لديها لون مختلف. قراءة/كتابة boolean.

**الإرجاع:**
boolean

### setColorVaried(boolean value) {#setColorVaried-boolean-}
```
public abstract void setColorVaried(boolean value)
```

تحديد أن كل علامة بيانات في السلسلة لديها لون مختلف. قراءة/كتابة boolean.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### hasSeriesLines() {#hasSeriesLines--}
```
public abstract boolean hasSeriesLines()
```

صحيح إذا كان المخطط يحتوي على خطوط السلسلة. يُطبّق على مخططات الأعمدة المكدسة ومخططات OfPie. قراءة/كتابة boolean.

**الإرجاع:**
boolean

### setSeriesLines(boolean value) {#setSeriesLines-boolean-}
```
public abstract void setSeriesLines(boolean value)
```

صحيح إذا كان المخطط يحتوي على خطوط السلسلة. يُطبّق على مخططات الأعمدة المكدسة ومخططات OfPie. قراءة/كتابة boolean.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getOverlap() {#getOverlap--}
```
public abstract byte getOverlap()
```

تحديد مقدار تداخل الأشرطة والأعمدة في المخططات ثنائية الأبعاد كنسبة مئوية (من -100% إلى 100%). -100%: أقصى مسافة (الأشرطة مفصولة تمامًا). -0%: تُوضع الأشرطة جانبًا دون تداخل أو مسافة. -100%: أقصى تداخل (الأشرطة تتداخل تمامًا). هذه الخاصية قراءة/كتابة byte.

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

تحديد مقدار تداخل الأشرطة والأعمدة في المخططات ثنائية الأبعاد كنسبة مئوية (من -100% إلى 100%). -100%: أقصى مسافة (الأشرطة مفصولة تمامًا). -0%: تُوضع الأشرطة جانبًا دون تداخل أو مسافة. -100%: أقصى تداخل (الأشرطة تتداخل تمامًا). هذه الخاصية قراءة/كتابة byte.

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
public abstract int getSecondPieSize()
```

تحديد حجم الفطيرة أو العمود الثاني في مخطط فطيرة-من-فطيرة أو عمود-من-فطيرة، كنسبة مئوية من حجم الفطيرة الأولى (يمكن أن تكون بين 5 و200 في المئة). قراءة/كتابة int.

**الإرجاع:**
int

### setSecondPieSize(int value) {#setSecondPieSize-int-}
```
public abstract void setSecondPieSize(int value)
```

تحديد حجم الفطيرة أو العمود الثاني في مخطط فطيرة-من-فطيرة أو عمود-من-فطيرة، كنسبة مئوية من حجم الفطيرة الأولى (يمكن أن تكون بين 5 و200 في المئة). قراءة/كتابة int.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getPieSplitPosition() {#getPieSplitPosition--}
```
public abstract double getPieSplitPosition()
```

تحديد قيمة تُستخدم لتحديد أي نقاط البيانات تكون في الفطيرة أو العمود الثاني في مخطط فطيرة-من-فطيرة أو عمود-من-فطيرة. تُستخدم مع خاصية PieSplitBy. قراءة/كتابة double.

**الإرجاع:**
double

### setPieSplitPosition(double value) {#setPieSplitPosition-double-}
```
public abstract void setPieSplitPosition(double value)
```

تحديد قيمة تُستخدم لتحديد أي نقاط البيانات تكون في الفطيرة أو العمود الثاني في مخطط فطيرة-من-فطيرة أو عمود-من-فطيرة. تُستخدم مع خاصية PieSplitBy. قراءة/كتابة double.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | double |  |

### getPieSplitBy() {#getPieSplitBy--}
```
public abstract int getPieSplitBy()
```

تحديد كيفية تحديد أي نقاط البيانات تكون في الفطيرة أو العمود الثاني في مخطط فطيرة-من-فطيرة أو عمود-من-فطيرة. قراءة/كتابة [PieSplitType](../../com.aspose.slides/piesplittype).

**الإرجاع:**
int

### setPieSplitBy(int value) {#setPieSplitBy-int-}
```
public abstract void setPieSplitBy(int value)
```

تحديد كيفية تحديد أي نقاط البيانات تكون في الفطيرة أو العمود الثاني في مخطط فطيرة-من-فطيرة أو عمود-من-فطيرة. قراءة/كتابة [PieSplitType](../../com.aspose.slides/piesplittype).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public abstract IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

معلومات الانقسام المخصص لمخطط فطيرة-من-فطيرة أو عمود-من-فطيرة مع انقسام مخصص. يحتوي على نقاط البيانات التي تُرسم في الفطيرة أو العمود الثاني في مخطط فطيرة-من-فطيرة أو عمود-من-فطيرة. قراءة فقط [IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection).

**الإرجاع:**
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)

### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public abstract byte getDoughnutHoleSize()
```

تحديد حجم الفتحة في مخطط الدونات (يمكن أن تكون بين 10 و90 في المئة من حجم مساحة الرسم). قراءة/كتابة byte.

**الإرجاع:**
byte

### setDoughnutHoleSize(byte value) {#setDoughnutHoleSize-byte-}
```
public abstract void setDoughnutHoleSize(byte value)
```

تحديد حجم الفتحة في مخطط الدونات (يمكن أن تكون بين 10 و90 في المئة من حجم مساحة الرسم). قراءة/كتابة byte.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public abstract int getBubbleSizeScale()
```

تحديد معامل المقياس لمخطط الفقاعات (يمكن أن يكون بين 0 و300 في المئة من الحجم الافتراضي). قراءة/كتابة int.

**الإرجاع:**
int

### setBubbleSizeScale(int value) {#setBubbleSizeScale-int-}
```
public abstract void setBubbleSizeScale(int value)
```

تحديد معامل المقياس لمخطط الفقاعات (يمكن أن يكون بين 0 و300 في المئة من الحجم الافتراضي). قراءة/كتابة int.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getHiLowLinesFormat() {#getHiLowLinesFormat--}
```
public abstract IChartLinesFormat getHiLowLinesFormat()
```

تحديد تنسيق HiLowLines. تُطبّق HiLowLines مع أنواع المخططات HiLowClose و OpenHiLowClose و VolumeHiLowClose و VolumeOpenHiLowClose.

**الإرجاع:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)

### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public abstract int getBubbleSizeRepresentation()
```

تحديد كيفية تمثيل قيم حجم الفقاعات في مخطط الفقاعات. قراءة/كتابة [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**الإرجاع:**
int

### setBubbleSizeRepresentation(int value) {#setBubbleSizeRepresentation-int-}
```
public abstract void setBubbleSizeRepresentation(int value)
```

تحديد كيفية تمثيل قيم حجم الفقاعات في مخطط الفقاعات. قراءة/كتابة [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | int |  |