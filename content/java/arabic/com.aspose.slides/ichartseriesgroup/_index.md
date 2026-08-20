---
title: IChartSeriesGroup
second_title: مرجع واجهة برمجة تطبيقات Aspose.Slides للغة Java
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

1) راجع الملخص والملاحظات لفئة ChartSeriesGroupCollection و تعداد CombinableSeriesTypesGroup. 2) مجموعة السلاسل تحتوي على بعض خصائص السلسلة التي تكون مشتركة لكل سلسلة في المجموعة ("خصائص مجموعة السلسلة"). "خصائص مجموعة السلسلة" في فئة ChartSeriesGroup هي قراءة/كتابة. كل من "خصائص مجموعة السلسلة" يمكن أن يكون له تمثيل قراءة فقط في فئة ChartSeries.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getType()](#getType--) | يرجع نوعًا لمجموعة السلاسل هذه. |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | يشير إلى ما إذا كانت سلاسل هذه المجموعة مرسومة على المحور الثانوي. |
| [getSeries()](#getSeries--) | يرجع مجموعة قراءة فقط من سلاسل المخطط. |
| [get_Item(int index)](#get-Item-int-) | يحصل على العنصر عند الفهرس المحدد. |
| [getUpDownBars()](#getUpDownBars--) | يوفر وصولًا إلى أشرطة الصعود/الهبوط في مخطط الخط أو المخطط السهمي. |
| [getGapWidth()](#getGapWidth--) | يحدد المسافة بين مجموعات الأعمدة أو الشرائح كنسبة مئوية من عرض العمود أو الشريحة. |
| [setGapWidth(int value)](#setGapWidth-int-) | يحدد المسافة بين مجموعات الأعمدة أو الشرائح كنسبة مئوية من عرض العمود أو الشريحة. |
| [getGapDepth()](#getGapDepth--) | يرجع أو يضبط المسافة، كنسبة مئوية من عرض العلامة، بين سلاسل البيانات في مخطط ثلاثي الأبعاد. |
| [setGapDepth(int value)](#setGapDepth-int-) | يرجع أو يضبط المسافة، كنسبة مئوية من عرض العلامة، بين سلاسل البيانات في مخطط ثلاثي الأبعاد. |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | يحصل على أو يضبط زاوية الشريحة الأولى في مخطط الفطيرة أو الدونات، بالدرجات (في اتجاه عقارب الساعة من الأعلى، من 0 إلى 360 درجة). |
| [setFirstSliceAngle(int value)](#setFirstSliceAngle-int-) | يحصل على أو يضبط زاوية الشريحة الأولى في مخطط الفطيرة أو الدونات، بالدرجات (في اتجاه عقارب الساعة من الأعلى، من 0 إلى 360 درجة). |
| [isColorVaried()](#isColorVaried--) | يحدد أن كل علامة بيانات في السلسلة لها لون مختلف. |
| [setColorVaried(boolean value)](#setColorVaried-boolean-) | يحدد أن كل علامة بيانات في السلسلة لها لون مختلف. |
| [hasSeriesLines()](#hasSeriesLines--) | صحيح إذا كان المخطط يحتوي على خطوط السلسلة. |
| [setSeriesLines(boolean value)](#setSeriesLines-boolean-) | صحيح إذا كان المخطط يحتوي على خطوط السلسلة. |
| [getOverlap()](#getOverlap--) | يحدد مقدار تداخل الأعمدة والشرائح في المخططات ثنائية الأبعاد كنسبة مئوية (من -100% إلى 100%). |
| [setOverlap(byte value)](#setOverlap-byte-) | يحدد مقدار تداخل الأعمدة والشرائح في المخططات ثنائية الأبعاد كنسبة مئوية (من -100% إلى 100%). |
| [getSecondPieSize()](#getSecondPieSize--) | يحدد حجم الفطيرة أو الشريط الثاني في مخطط فطيرة-من-فطيرة أو شريط-من-فطيرة، كنسبة مئوية من حجم الفطيرة الأولى (يمكن أن يكون بين 5 و 200٪). |
| [setSecondPieSize(int value)](#setSecondPieSize-int-) | يحدد حجم الفطيرة أو الشريط الثاني في مخطط فطيرة-من-فطيرة أو شريط-من-فطيرة، كنسبة مئوية من حجم الفطيرة الأولى (يمكن أن يكون بين 5 و 200٪). |
| [getPieSplitPosition()](#getPieSplitPosition--) | يحدد قيمة تُستخدم لتحديد أي نقاط البيانات تكون في الفطيرة أو الشريط الثاني في مخطط فطيرة-من-فطيرة أو شريط-من-فطيرة. |
| [setPieSplitPosition(double value)](#setPieSplitPosition-double-) | يحدد قيمة تُستخدم لتحديد أي نقاط البيانات تكون في الفطيرة أو الشريط الثاني في مخطط فطيرة-من-فطيرة أو شريط-من-فطيرة. |
| [getPieSplitBy()](#getPieSplitBy--) | يحدد كيفية تحديد أي نقاط البيانات تكون في الفطيرة أو الشريط الثاني في مخطط فطيرة-من-فطيرة أو شريط-من-فطيرة. |
| [setPieSplitBy(int value)](#setPieSplitBy-int-) | يحدد كيفية تحديد أي نقاط البيانات تكون في الفطيرة أو الشريط الثاني في مخطط فطيرة-من-فطيرة أو شريط-من-فطيرة. |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | معلومات الانقسام المخصص لمخطط فطيرة-من-فطيرة أو شريط-من-فطيرة مع انقسام مخصص. |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | يحدد حجم الفتحة في مخطط الدونات (يمكن أن يكون بين 10 و 90٪ من حجم مساحة الرسم). |
| [setDoughnutHoleSize(byte value)](#setDoughnutHoleSize-byte-) | يحدد حجم الفتحة في مخطط الدونات (يمكن أن يكون بين 10 و 90٪ من حجم مساحة الرسم). |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | يحدد معامل المقياس لمخطط الفقاعات (يمكن أن يكون بين 0 و 300٪ من الحجم الافتراضي). |
| [setBubbleSizeScale(int value)](#setBubbleSizeScale-int-) | يحدد معامل المقياس لمخطط الفقاعات (يمكن أن يكون بين 0 و 300٪ من الحجم الافتراضي). |
| [getHiLowLinesFormat()](#getHiLowLinesFormat--) | يحدد تنسيق HiLowLines. |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | يحدد كيفية تمثيل قيم حجم الفقاعات على مخطط الفقاعات. |
| [setBubbleSizeRepresentation(int value)](#setBubbleSizeRepresentation-int-) | يحدد كيفية تمثيل قيم حجم الفقاعات على مخطط الفقاعات. |
### getType() {#getType--}
```
public abstract int getType()
```

يرجع نوعًا لمجموعة السلاسل هذه. قراءة فقط [CombinableSeriesTypesGroup](../../com.aspose.slides/combinableseriestypesgroup).

**القيم المرجعة:**
int
### getPlotOnSecondAxis() {#getPlotOnSecondAxis--}
```
public abstract boolean getPlotOnSecondAxis()
```

يشير إلى ما إذا كانت سلاسل هذه المجموعة مرسومة على المحور الثانوي. قراءة فقط boolean.

**القيم المرجعة:**
boolean
### getSeries() {#getSeries--}
```
public abstract IChartSeriesReadonlyCollection getSeries()
```

يرجع مجموعة قراءة فقط من سلاسل المخطط. قراءة فقط [IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection).

**القيم المرجعة:**
[IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection)
### get_Item(int index) {#get-Item-int-}
```
public abstract IChartSeries get_Item(int index)
```

يحصل على العنصر عند الفهرس المحدد.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int |  |

**القيم المرجعة:**
[IChartSeries](../../com.aspose.slides/ichartseries)
### getUpDownBars() {#getUpDownBars--}
```
public abstract IUpDownBarsManager getUpDownBars()
```

يوفر وصولًا إلى أشرطة الصعود/الهبوط في مخطط الخط أو المخطط السهمي. قراءة فقط [IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager).

**القيم المرجعة:**
[IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager)
### getGapWidth() {#getGapWidth--}
```
public abstract int getGapWidth()
```

يحدد المسافة بين مجموعات الأعمدة أو الشرائح كنسبة مئوية من عرض العمود أو الشريحة. قراءة/كتابة int.

**القيم المرجعة:**
int
### setGapWidth(int value) {#setGapWidth-int-}
```
public abstract void setGapWidth(int value)
```

يحدد المسافة بين مجموعات الأعمدة أو الشرائح كنسبة مئوية من عرض العمود أو الشريحة. قراءة/كتابة int.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |
### getGapDepth() {#getGapDepth--}
```
public abstract int getGapDepth()
```

يرجع أو يضبط المسافة، كنسبة مئوية من عرض العلامة، بين سلاسل البيانات في مخطط ثلاثي الأبعاد. قراءة/كتابة int.

**القيم المرجعة:**
int
### setGapDepth(int value) {#setGapDepth-int-}
```
public abstract void setGapDepth(int value)
```

يرجع أو يضبط المسافة، كنسبة مئوية من عرض العلامة، بين سلاسل البيانات في مخطط ثلاثي الأبعاد. قراءة/كتابة int.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |
### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public abstract int getFirstSliceAngle()
```

يحصل على أو يضبط زاوية الشريحة الأولى في مخطط الفطيرة أو الدونات، بالدرجات (في اتجاه عقارب الساعة من الأعلى، من 0 إلى 360 درجة). قراءة/كتابة int.

**القيم المرجعة:**
int
### setFirstSliceAngle(int value) {#setFirstSliceAngle-int-}
```
public abstract void setFirstSliceAngle(int value)
```

يحصل على أو يضبط زاوية الشريحة الأولى في مخطط الفطيرة أو الدونات، بالدرجات (في اتجاه عقارب الساعة من الأعلى، من 0 إلى 360 درجة). قراءة/كتابة int.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |
### isColorVaried() {#isColorVaried--}
```
public abstract boolean isColorVaried()
```

يحدد أن كل علامة بيانات في السلسلة لها لون مختلف. قراءة/كتابة boolean.

**القيم المرجعة:**
boolean
### setColorVaried(boolean value) {#setColorVaried-boolean-}
```
public abstract void setColorVaried(boolean value)
```

يحدد أن كل علامة بيانات في السلسلة لها لون مختلف. قراءة/كتابة boolean.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |
### hasSeriesLines() {#hasSeriesLines--}
```
public abstract boolean hasSeriesLines()
```

صحيح إذا كان المخطط يحتوي على خطوط السلسلة. ينطبق على المخططات المكدسة من النوع bar و OfPie. قراءة/كتابة boolean.

**القيم المرجعة:**
boolean
### setSeriesLines(boolean value) {#setSeriesLines-boolean-}
```
public abstract void setSeriesLines(boolean value)
```

صحيح إذا كان المخطط يحتوي على خطوط السلسلة. ينطبق على المخططات المكدسة من النوع bar و OfPie. قراءة/كتابة boolean.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |
### getOverlap() {#getOverlap--}
```
public abstract byte getOverlap()
```

يحدد مقدار تداخل الأعمدة والشرائح في المخططات ثنائية الأبعاد كنسبة مئوية (من -100% إلى 100%). - -100%: أقصى مسافة (الأعمدة منفصلة تمامًا). - 0%: الأعمدة موضوعة جنبًا إلى جنب دون تداخل أو مسافة. - 100%: أقصى تداخل (الأعمدة تتداخل تمامًا). هذه الخاصية قراءة/كتابة byte.

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
>      pres.getSlides().get_Item(0).getImage(1, 1).save("chart.png");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**القيم المرجعة:**
byte
### setOverlap(byte value) {#setOverlap-byte-}
```
public abstract void setOverlap(byte value)
```

يحدد مقدار تداخل الأعمدة والشرائح في المخططات ثنائية الأبعاد كنسبة مئوية (من -100% إلى 100%). - -100%: أقصى مسافة (الأعمدة منفصلة تمامًا). - 0%: الأعمدة موضوعة جنبًا إلى جنب دون تداخل أو مسافة. - 100%: أقصى تداخل (الأعمدة تتداخل تمامًا). هذه الخاصية قراءة/كتابة byte.

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
public abstract int getSecondPieSize()
```

يحدد حجم الفطيرة أو الشريط الثاني في مخطط فطيرة-من-فطيرة أو شريط-من-فطيرة، كنسبة مئوية من حجم الفطيرة الأولى (يمكن أن يكون بين 5 و 200٪). قراءة/كتابة int.

**القيم المرجعة:**
int
### setSecondPieSize(int value) {#setSecondPieSize-int-}
```
public abstract void setSecondPieSize(int value)
```

يحدد حجم الفطيرة أو الشريط الثاني في مخطط فطيرة-من-فطيرة أو شريط-من-فطيرة، كنسبة مئوية من حجم الفطيرة الأولى (يمكن أن يكون بين 5 و 200٪). قراءة/كتابة int.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |
### getPieSplitPosition() {#getPieSplitPosition--}
```
public abstract double getPieSplitPosition()
```

يحدد قيمة تُستخدم لتحديد أي نقاط البيانات تكون في الفطيرة أو الشريط الثاني في مخطط فطيرة-من-فطيرة أو شريط-من-فطيرة. يُستخدم مع خاصية PieSplitBy. قراءة/كتابة double.

**القيم المرجعة:**
double
### setPieSplitPosition(double value) {#setPieSplitPosition-double-}
```
public abstract void setPieSplitPosition(double value)
```

يحدد قيمة تُستخدم لتحديد أي نقاط البيانات تكون في الفطيرة أو الشريط الثاني في مخطط فطيرة-من-فطيرة أو شريط-من-فطيرة. يُستخدم مع خاصية PieSplitBy. قراءة/كتابة double.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | double |  |
### getPieSplitBy() {#getPieSplitBy--}
```
public abstract int getPieSplitBy()
```

يحدد كيفية تحديد أي نقاط البيانات تكون في الفطيرة أو الشريط الثاني في مخطط فطيرة-من-فطيرة أو شريط-من-فطيرة. قراءة/كتابة [PieSplitType](../../com.aspose.slides/piesplittype).

**القيم المرجعة:**
int
### setPieSplitBy(int value) {#setPieSplitBy-int-}
```
public abstract void setPieSplitBy(int value)
```

يحدد كيفية تحديد أي نقاط البيانات تكون في الفطيرة أو الشريط الثاني في مخطط فطيرة-من-فطيرة أو شريط-من-فطيرة. قراءة/كتابة [PieSplitType](../../com.aspose.slides/piesplittype).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |
### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public abstract IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

معلومات الانقسام المخصص لمخطط فطيرة-من-فطيرة أو شريط-من-فطيرة مع انقسام مخصص. يحتوي على نقاط البيانات التي يجب رسمها في الفطيرة أو الشريط الثاني في مخطط فطيرة-من-فطيرة أو شريط-من-فطيرة. قراءة فقط [IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection).

**القيم المرجعة:**
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)
### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public abstract byte getDoughnutHoleSize()
```

يحدد حجم الفتحة في مخطط الدونات (يمكن أن يكون بين 10 و 90٪ من حجم مساحة الرسم). قراءة/كتابة byte.

**القيم المرجعة:**
byte
### setDoughnutHoleSize(byte value) {#setDoughnutHoleSize-byte-}
```
public abstract void setDoughnutHoleSize(byte value)
```

يحدد حجم الفتحة في مخطط الدونات (يمكن أن يكون بين 10 و 90٪ من حجم مساحة الرسم). قراءة/كتابة byte.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |
### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public abstract int getBubbleSizeScale()
```

يحدد معامل المقياس لمخطط الفقاعات (يمكن أن يكون بين 0 و 300٪ من الحجم الافتراضي). قراءة/كتابة int.

**القيم المرجعة:**
int
### setBubbleSizeScale(int value) {#setBubbleSizeScale-int-}
```
public abstract void setBubbleSizeScale(int value)
```

يحدد معامل المقياس لمخطط الفقاعات (يمكن أن يكون بين 0 و 300٪ من الحجم الافتراضي). قراءة/كتابة int.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |
### getHiLowLinesFormat() {#getHiLowLinesFormat--}
```
public abstract IChartLinesFormat getHiLowLinesFormat()
```

يحدد تنسيق HiLowLines. يُطبق HiLowLines مع أنواع المخططات HiLowClose، OpenHiLowClose، VolumeHiLowClose و VolumeOpenHiLowClose.

**القيم المرجعة:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)
### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public abstract int getBubbleSizeRepresentation()
```

يحدد كيفية تمثيل قيم حجم الفقاعات على مخطط الفقاعات. قراءة/كتابة [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**القيم المرجعة:**
int
### setBubbleSizeRepresentation(int value) {#setBubbleSizeRepresentation-int-}
```
public abstract void setBubbleSizeRepresentation(int value)
```

يحدد كيفية تمثيل قيم حجم الفقاعات على مخطط الفقاعات. قراءة/كتابة [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |