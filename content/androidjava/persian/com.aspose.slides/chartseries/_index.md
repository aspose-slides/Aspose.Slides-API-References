---
title: ChartSeries
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: یک سری نمودار را نشان می‌دهد.
type: docs
url: /fa/com.aspose.slides/chartseries/
---
**ارث‌بری:**
java.lang.Object

**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IChartSeries](../../com.aspose.slides/ichartseries), com.aspose.slides.IDOMObject
```
public class ChartSeries implements IChartSeries, IDOMObject
```

یک سری نمودار را نشان می‌دهد.
## متدها

| متد | شرح |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getChart()](#getChart--) | نمودار والد را برمی‌گرداند. |
| [getExplosion()](#getExplosion--) | فاصله یک برش پیت باز از مرکز نمودار پای چرخان به‌صورت درصدی از قطر پای چرخان بیان می‌شود. |
| [setExplosion(int value)](#setExplosion-int-) | فاصله یک برش پیت باز از مرکز نمودار پای چرخان به‌صورت درصدی از قطر پای چرخان بیان می‌شود. |
| [getSmooth()](#getSmooth--) | نرمی منحنی را نشان می‌دهد. |
| [setSmooth(boolean value)](#setSmooth-boolean-) | نرمی منحنی را نشان می‌دهد. |
| [getName()](#getName--) | نام سری را برمی‌گرداند. |
| [getDataPoints()](#getDataPoints--) | مجموعه‌ای از نقاط داده این سری را برمی‌گرداند. |
| [getType()](#getType--) | یک نوع از این سری را برمی‌گرداند. |
| [setType(int value)](#setType-int-) | یک نوع از این سری را برمی‌گرداند. |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | نشان می‌دهد که آیا این سری بر روی محور دوم رسم می‌شود یا خیر. |
| [setPlotOnSecondAxis(boolean value)](#setPlotOnSecondAxis-boolean-) | نشان می‌دهد که آیا این سری بر روی محور دوم رسم می‌شود یا خیر. |
| [getParentSeriesGroup()](#getParentSeriesGroup--) | ParentSeriesGroup. |
| [getFormat()](#getFormat--) | قالب یک سری را برمی‌گرداند. |
| [getOrder()](#getOrder--) | ترتیب یک سری را برمی‌گرداند. |
| [setOrder(int value)](#setOrder-int-) | ترتیب یک سری را برمی‌گرداند. |
| [getLabels()](#getLabels--) | برچسب‌های یک سری را برمی‌گرداند. |
| [getTrendLines()](#getTrendLines--) | مجموعه خطوط روند سری‌ها. |
| [getErrorBarsXFormat()](#getErrorBarsXFormat--) | نمایانگر ErrorBars از سری با جهت X. |
| [getErrorBarsYFormat()](#getErrorBarsYFormat--) | نمایانگر ErrorBars از سری با جهت Y. |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | نمایانگر ورودی افسانه مرتبط با این سری (فقط-خواندنی) [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties). |
| [getNumberFormatOfValues()](#getNumberFormatOfValues--) | NumberFormatOfValues. |
| [setNumberFormatOfValues(String value)](#setNumberFormatOfValues-java.lang.String-) | NumberFormatOfValues. |
| [getNumberFormatOfXValues()](#getNumberFormatOfXValues--) | NumberFormatOfXValues. |
| [setNumberFormatOfXValues(String value)](#setNumberFormatOfXValues-java.lang.String-) | NumberFormatOfXValues. |
| [getNumberFormatOfYValues()](#getNumberFormatOfYValues--) | NumberFormatOfYValues. |
| [setNumberFormatOfYValues(String value)](#setNumberFormatOfYValues-java.lang.String-) | NumberFormatOfYValues. |
| [getNumberFormatOfBubbleSizes()](#getNumberFormatOfBubbleSizes--) | NumberFormatOfBubbleSizes. |
| [setNumberFormatOfBubbleSizes(String value)](#setNumberFormatOfBubbleSizes-java.lang.String-) | NumberFormatOfBubbleSizes. |
| [getMarker()](#getMarker--) | Marker. |
| [getBar3DShape()](#getBar3DShape--) | شکل یک سری از نمودار میله‌ ای 3-بعدی را مشخص می‌کند. |
| [setBar3DShape(int value)](#setBar3DShape-int-) | شکل یک سری از نمودار میله‌ ای 3-بعدی را مشخص می‌کند. |
| [getInvertIfNegative()](#getInvertIfNegative--) | مشخص می‌کند که سری میله، ستون یا حباب رنگ‌های خود را در صورت مقدار منفی معکوس کند. |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | مشخص می‌کند که سری میله، ستون یا حباب رنگ‌های خود را در صورت مقدار منفی معکوس کند. |
| [getInvertedSolidFillColor()](#getInvertedSolidFillColor--) | رنگ جامد معکوس را برای سری مشخص می‌کند. |
| [getAutomaticSeriesColor()](#getAutomaticSeriesColor--) | رنگ خودکار سری را بر اساس شاخص سری و سبک نمودار برمی‌گرداند. |
| [getShowInnerPoints()](#getShowInnerPoints--) | نقاط داخلی را نشان می‌دهد. |
| [setShowInnerPoints(boolean value)](#setShowInnerPoints-boolean-) | نقاط داخلی را نشان می‌دهد. |
| [getShowOutlierPoints()](#getShowOutlierPoints--) | نقاط پرت را نشان می‌دهد. |
| [setShowOutlierPoints(boolean value)](#setShowOutlierPoints-boolean-) | نقاط پرت را نشان می‌دهد. |
| [getShowMeanMarkers()](#getShowMeanMarkers--) | نشانگرهای میانگین را نشان می‌دهد. |
| [setShowMeanMarkers(boolean value)](#setShowMeanMarkers-boolean-) | نشانگرهای میانگین را نشان می‌دهد. |
| [getShowMeanLine()](#getShowMeanLine--) | خط میانگین را نشان می‌دهد. |
| [setShowMeanLine(boolean value)](#setShowMeanLine-boolean-) | خط میانگین را نشان می‌دهد. |
| [getQuartileMethod()](#getQuartileMethod--) | روش چارک را نشان می‌دهد. |
| [setQuartileMethod(int value)](#setQuartileMethod-int-) | روش چارک را نشان می‌دهد. |
| [getShowConnectorLines()](#getShowConnectorLines--) | خطوط متصل را نشان می‌دهد. |
| [setShowConnectorLines(boolean value)](#setShowConnectorLines-boolean-) | خطوط متصل را نشان می‌دهد. |
| [getParentLabelLayout()](#getParentLabelLayout--) | چیدمان برچسب‌های دسته والد را نشان می‌دهد. |
| [setParentLabelLayout(int value)](#setParentLabelLayout-int-) | چیدمان برچسب‌های دسته والد را نشان می‌دهد. |
| [hasUpDownBars()](#hasUpDownBars--) | تعیین می‌کند که آیا نمودار خط یا سهام دارای میله‌های بالا/پایین است یا خیر. |
| [getGapWidth()](#getGapWidth--) | فاصله بین دسته‌های میله یا ستون را به‌صورت درصدی از عرض میله یا ستون مشخص می‌کند. |
| [getGapDepth()](#getGapDepth--) | فاصله را به‌عنوان درصدی از عرض نشانگر بین سری‌های داده در یک نمودار 3-بعدی برمی‌گرداند یا تنظیم می‌کند. |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | زاویه اولین برش نمودار پای یا دونات را بر حسب درجه (ساعت‌گرد از بالا، از 0 تا 360 درجه) مشخص می‌کند. |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | اندازه سوراخ در نمودار دونات را مشخص می‌کند (می‌تواند بین 10 تا 90 درصد از اندازه ناحیه رسم باشد). |
| [getOverlap()](#getOverlap--) | میزان هم‌پوشانی میله‌ها و ستون‌ها در نمودارهای دو-بعدی را به‌صورت درصد (از -100٪ تا 100٪) مشخص می‌کند. |
| [getSecondPieSize()](#getSecondPieSize--) | اندازه دومین پای یا میله در نمودار پای-در-پای یا میله-در-پای را به‌عنوان درصدی از اندازه اولین پای (می‌تواند بین 5 تا 200 درصد باشد) مشخص می‌کند. |
| [hasSeriesLines()](#hasSeriesLines--) | تعیین می‌کند که آیا خطوط سری برای این سری و سری‌های مرتبط وجود دارد یا خیر. |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | نحوه نمایش مقادیر اندازه حباب‌ها در نمودار حبابی را مشخص می‌کند. |
| [getPieSplitPosition()](#getPieSplitPosition--) | مقداری را که برای تعیین نقاط داده‌ای که در دومین پای یا میله در نمودار پای-در-پای یا میله-در-پای قرار می‌گیرند استفاده می‌شود، مشخص می‌کند. |
| [getPieSplitBy()](#getPieSplitBy--) | نحوه تعیین نقاط داده‌ای که در دومین پای یا میله در نمودار پای-در-پای یا میله-در-پای قرار می‌گیرند را مشخص می‌کند. |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | اطلاعات تقسیم سفارشی برای نمودار پای-در-پای یا میله-در-پای با تقسیم سفارشی. |
| [isColorVaried()](#isColorVaried--) | مشخص می‌کند که هر نشانگر داده در سری رنگ متفاوتی داشته باشد. |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | فاکتور مقیاس برای نمودار حبابی را مشخص می‌کند (می‌تواند بین 0 تا 300 درصد از اندازه پیش‌فرض باشد). |
| [getSlide()](#getSlide--) | اسلاید والد FillFormat را برمی‌گرداند. |
| [getPresentation()](#getPresentation--) | ارائه والد FillFormat را برمی‌گرداند. |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

یک شیء Parent_Immediate را برمی‌گرداند. فقط-خواندنی IDOMObject.

**بازمی‌گرداند:**
com.aspose.slides.IDOMObject

### getChart() {#getChart--}
```
public final IChart getChart()
```

نمودار والد را برمی‌گرداند. فقط-خواندنی [IChart](../../com.aspose.slides/ichart).

**بازمی‌گرداند:**
[IChart](../../com.aspose.slides/ichart)

### getExplosion() {#getExplosion--}
```
public final int getExplosion()
```

فاصله یک برش پیت باز از مرکز نمودار پای چرخان به‌صورت درصدی از قطر پای چرخان بیان می‌شود. قابل‌خواندن/قابل‌نوشتن int.

**بازمی‌گرداند:**
int

### setExplosion(int value) {#setExplosion-int-}
```
public final void setExplosion(int value)
```

فاصله یک برش پیت باز از مرکز نمودار پای چرخان به‌صورت درصدی از قطر پای چرخان بیان می‌شود. قابل‌خواندن/قابل‌نوشتن int.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getSmooth() {#getSmooth--}
```
public final boolean getSmooth()
```

نرمی منحنی را نشان می‌دهد. اگر نرمی منحنی برای نمودار خط یا پراکندگی فعال باشد true برمی‌گرداند. فقط برای نمودارهای خط و پراکندگی متصل به خطوط کاربرد دارد. قابل‌خواندن/قابل‌نوشتن boolean.

**بازمی‌گرداند:**
boolean

### setSmooth(boolean value) {#setSmooth-boolean-}
```
public final void setSmooth(boolean value)
```

نرمی منحنی را نشان می‌دهد. اگر نرمی منحنی برای نمودار خط یا پراکندگی فعال باشد true برمی‌گرداند. فقط برای نمودارهای خط و پراکندگی متصل به خطوط کاربرد دارد. قابل‌خواندن/قابل‌نوشتن boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getName() {#getName--}
```
public final IStringChartValue getName()
```

نام سری را برمی‌گرداند. فقط-خواندنی [IStringChartValue](../../com.aspose.slides/istringchartvalue).

**بازمی‌گرداند:**
[IStringChartValue](../../com.aspose.slides/istringchartvalue)

### getDataPoints() {#getDataPoints--}
```
public final IChartDataPointCollection getDataPoints()
```

مجموعه‌ای از نقاط داده این سری را برمی‌گرداند. فقط-خواندنی [IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection).

**بازمی‌گرداند:**
[IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection)

### getType() {#getType--}
```
public final int getType()
```

یک نوع از این سری را برمی‌گرداند. قابل‌خواندن/قابل‌نوشتن [ChartType](../../com.aspose.slides/charttype).

**بازمی‌گرداند:**
int

### setType(int value) {#setType-int-}
```
public final void setType(int value)
```

یک نوع از این سری را برمی‌گرداند. قابل‌خواندن/قابل‌نوشتن [ChartType](../../com.aspose.slides/charttype).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getPlotOnSecondAxis() {#getPlotOnSecondAxis--}
```
public final boolean getPlotOnSecondAxis()
```

نشان می‌دهد که آیا این سری بر روی محور دوم رسم می‌شود یا خیر. قابل‌خواندن/قابل‌نوشتن boolean.

**بازمی‌گرداند:**
boolean

### setPlotOnSecondAxis(boolean value) {#setPlotOnSecondAxis-boolean-}
```
public final void setPlotOnSecondAxis(boolean value)
```

نشان می‌دهد که آیا این سری بر روی محور دوم رسم می‌شود یا خیر. قابل‌خواندن/قابل‌نوشتن boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getParentSeriesGroup() {#getParentSeriesGroup--}
```
public final IChartSeriesGroup getParentSeriesGroup()
```

ParentSeriesGroup. فقط-خواندنی [IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup).

**بازمی‌گرداند:**
[IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup)

### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

قالب یک سری را برمی‌گرداند. فقط-خواندنی [IFormat](../../com.aspose.slides/iformat).

**بازمی‌گرداند:**
[IFormat](../../com.aspose.slides/iformat)

### getOrder() {#getOrder--}
```
public final int getOrder()
```

ترتیب یک سری را برمی‌گرداند. قابل‌خواندن/قابل‌نوشتن int.

**بازمی‌گرداند:**
int

### setOrder(int value) {#setOrder-int-}
```
public final void setOrder(int value)
```

ترتیب یک سری را برمی‌گرداند. قابل‌خواندن/قابل‌نوشتن int.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getLabels() {#getLabels--}
```
public final IDataLabelCollection getLabels()
```

برچسب‌های یک سری را برمی‌گرداند. فقط-خواندنی [IDataLabelCollection](../../com.aspose.slides/idatalabelcollection).

**بازمی‌گرداند:**
[IDataLabelCollection](../../com.aspose.slides/idatalabelcollection)

### getTrendLines() {#getTrendLines--}
```
public final ITrendlineCollection getTrendLines()
```

مجموعه خطوط روند سری‌ها. فقط-خواندنی [ITrendlineCollection](../../com.aspose.slides/itrendlinecollection).

--------------------

خطوط روند برای سری‌های داده در نمودارهای مساحت دو-بعدی، میله، ستون، خط، سهام، xy (پراکندگی) و حبابی که به-صورت غیر-پشته هستند موجود هستند (خالی نیستند). یک خط روند برای سری‌های داده در هر نوع نموداری که پشته‌دار یا 3-بعدی باشد، موجود نیست. خطوط روند همچنین برای نمودارهای رادار، پای، سطح یا دونات موجود نیستند.

**بازمی‌گرداند:**
[ITrendlineCollection](../../com.aspose.slides/itrendlinecollection)

### getErrorBarsXFormat() {#getErrorBarsXFormat--}
```
public final IErrorBarsFormat getErrorBarsXFormat()
```

نمایانگر ErrorBars از سری با جهت X. فقط-خواندنی [IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat).

--------------------

ErrorBars با جهت X برای سری‌های نوع مساحت، میله، پراکندگی و حباب موجود است. برای هر نوع دیگر (از جمله نمودارهای 3-بعدی) این ویژگی مقدار null برمی‌گرداند. در صورت استفاده از مقادیر سفارشی از مجموعه DataPoints برای تعیین مقدار استفاده کنید (با ویژگی ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues))).

**بازمی‌گرداند:**
[IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)

### getErrorBarsYFormat() {#getErrorBarsYFormat--}
```
public final IErrorBarsFormat getErrorBarsYFormat()
```

نمایانگر ErrorBars از سری با جهت Y. فقط-خواندنی [IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat).

--------------------

ErrorBars با جهت Y برای سری‌های نوع مساحت، میله، خط، پراکندگی و حباب موجود است. برای هر نوع دیگر (از جمله نمودارهای 3-بعدی) این ویژگی مقدار null برمی‌گرداند. در صورت استفاده از مقادیر سفارشی از مجموعه DataPoints برای تعیین مقدار استفاده کنید (با ویژگی ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues))).

**بازمی‌گرداند:**
[IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)

### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public final ILegendEntryProperties getRelatedLegendEntry()
```

نمایانگر ورودی افسانه مرتبط با این سری (فقط-خواندنی) [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**بازمی‌گرداند:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)

### getNumberFormatOfValues() {#getNumberFormatOfValues--}
```
public final String getNumberFormatOfValues()
```

NumberFormatOfValues. قابل‌خواندن/قابل‌نوشتن String.

**بازمی‌گرداند:**
java.lang.String

### setNumberFormatOfValues(String value) {#setNumberFormatOfValues-java.lang.String-}
```
public final void setNumberFormatOfValues(String value)
```

NumberFormatOfValues. قابل‌خواندن/قابل‌نوشتن String.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |

### getNumberFormatOfXValues() {#getNumberFormatOfXValues--}
```
public final String getNumberFormatOfXValues()
```

NumberFormatOfXValues. قابل‌خواندن/قابل‌نوشتن String.

**بازمی‌گرداند:**
java.lang.String

### setNumberFormatOfXValues(String value) {#setNumberFormatOfXValues-java.lang.String-}
```
public final void setNumberFormatOfXValues(String value)
```

NumberFormatOfXValues. قابل‌خواندن/قابل‌نوشتن String.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |

### getNumberFormatOfYValues() {#getNumberFormatOfYValues--}
```
public final String getNumberFormatOfYValues()
```

NumberFormatOfYValues. قابل‌خواندن/قابل‌نوشتن String.

**بازمی‌گرداند:**
java.lang.String

### setNumberFormatOfYValues(String value) {#setNumberFormatOfYValues-java.lang.String-}
```
public final void setNumberFormatOfYValues(String value)
```

NumberFormatOfYValues. قابل‌خواندن/قابل‌نوشتن String.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |

### getNumberFormatOfBubbleSizes() {#getNumberFormatOfBubbleSizes--}
```
public final String getNumberFormatOfBubbleSizes()
```

NumberFormatOfBubbleSizes. قابل‌خواندن/قابل‌نوشتن String.

**بازمی‌گرداند:**
java.lang.String

### setNumberFormatOfBubbleSizes(String value) {#setNumberFormatOfBubbleSizes-java.lang.String-}
```
public final void setNumberFormatOfBubbleSizes(String value)
```

NumberFormatOfBubbleSizes. قابل‌خواندن/قابل‌نوشتن String.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |

### getMarker() {#getMarker--}
```
public final IMarker getMarker()
```

Marker. فقط-خواندنی [IMarker](../../com.aspose.slides/imarker).

**بازمی‌گرداند:**
[IMarker](../../com.aspose.slides/imarker)

### getBar3DShape() {#getBar3DShape--}
```
public final int getBar3DShape()
```

شکل یک سری از نمودار میله‌ ای 3-بعدی را مشخص می‌کند. تغییر این مقدار می‌تواند به‌صورت خودکار نوع سری را تغییر دهد. قابل‌خواندن/قابل‌نوشتن [ChartShapeType](../../com.aspose.slides/chartshapetype).

**بازمی‌گرداند:**
int

### setBar3DShape(int value) {#setBar3DShape-int-}
```
public final void setBar3DShape(int value)
```

شکل یک سری از نمودار میله‌ ای 3-بعدی را مشخص می‌کند. تغییر این مقدار می‌تواند به‌صورت خودکار نوع سری را تغییر دهد. قابل‌خواندن/قابل‌نوشتن [ChartShapeType](../../com.aspose.slides/chartshapetype).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getInvertIfNegative() {#getInvertIfNegative--}
```
public final boolean getInvertIfNegative()
```

مشخص می‌کند که سری میله، ستون یا حباب رنگ‌های خود را در صورت مقدار منفی معکوس کند. قابل‌خواندن/قابل‌نوشتن boolean.

**بازمی‌گرداند:**
boolean

### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public final void setInvertIfNegative(boolean value)
```

مشخص می‌کند که سری میله، ستون یا حباب رنگ‌های خود را در صورت مقدار منفی معکوس کند. قابل‌خواندن/قابل‌نوشتن boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getInvertedSolidFillColor() {#getInvertedSolidFillColor--}
```
public final IColorFormat getInvertedSolidFillColor()
```

رنگ جامد معکوس را برای سری مشخص می‌کند. برای اعمال تنظیم رنگ، نوع پر کردن سری را به FillType.Solid تنظیم کنید. قابل‌خواندن/قابل‌نوشتن [ColorFormat](../../com.aspose.slides/colorformat).

**بازمی‌گرداند:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getAutomaticSeriesColor() {#getAutomaticSeriesColor--}
```
public final Integer getAutomaticSeriesColor()
```

رنگ خودکار سری را بر اساس شاخص سری و سبک نمودار برمی‌گرداند. این رنگ به‌صورت پیش‌فرض وقتی FillType برابر NotDefined باشد استفاده می‌شود.

**بازمی‌گرداند:**
java.lang.Integer - The java.lang.Integer object.

### getShowInnerPoints() {#getShowInnerPoints--}
```
public final boolean getShowInnerPoints()
```

نقاط داخلی را نشان می‌دهد. اگر نقاط داخلی در نمودار BoxAndWhisker نشان داده شوند true برمی‌گرداند. فقط برای نمودارهای BoxAndWhisker کاربرد دارد. قابل‌خواندن/قابل‌نوشتن boolean.

**بازمی‌گرداند:**
boolean

### setShowInnerPoints(boolean value) {#setShowInnerPoints-boolean-}
```
public final void setShowInnerPoints(boolean value)
```

نقاط داخلی را نشان می‌دهد. اگر نقاط داخلی در نمودار BoxAndWhisker نشان داده شوند true برمی‌گرداند. فقط برای نمودارهای BoxAndWhisker کاربرد دارد. قابل‌خواندن/قابل‌نوشتن boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getShowOutlierPoints() {#getShowOutlierPoints--}
```
public final boolean getShowOutlierPoints()
```

نقاط پرت را نشان می‌دهد. اگر نقاط پرت در نمودار BoxAndWhisker نشان داده شوند true برمی‌گرداند. فقط برای نمودارهای BoxAndWhisker کاربرد دارد. قابل‌خواندن/قابل‌نوشتن boolean.

**بازمی‌گرداند:**
boolean

### setShowOutlierPoints(boolean value) {#setShowOutlierPoints-boolean-}
```
public final void setShowOutlierPoints(boolean value)
```

نقاط پرت را نشان می‌دهد. اگر نقاط پرت در نمودار BoxAndWhisker نشان داده شوند true برمی‌گرداند. فقط برای نمودارهای BoxAndWhisker کاربرد دارد. قابل‌خواندن/قابل‌نوشتن boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getShowMeanMarkers() {#getShowMeanMarkers--}
```
public final boolean getShowMeanMarkers()
```

نشانگرهای میانگین را نشان می‌دهد. اگر نشانگرهای میانگین در نمودار BoxAndWhisker نشان داده شوند true برمی‌گرداند. فقط برای نمودارهای BoxAndWhisker کاربرد دارد. قابل‌خواندن/قابل‌نوشتن boolean.

**بازمی‌گرداند:**
boolean

### setShowMeanMarkers(boolean value) {#setShowMeanMarkers-boolean-}
```
public final void setShowMeanMarkers(boolean value)
```

نشانگرهای میانگین را نشان می‌دهد. اگر نشانگرهای میانگین در نمودار BoxAndWhisker نشان داده شوند true برمی‌گرداند. فقط برای نمودارهای BoxAndWhisker کاربرد دارد. قابل‌خواندن/قابل‌نوشتن boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getShowMeanLine() {#getShowMeanLine--}
```
public final boolean getShowMeanLine()
```

خط میانگین را نشان می‌دهد. اگر خط میانگین در نمودار BoxAndWhisker نشان داده شود true برمی‌گرداند. فقط برای نمودارهای BoxAndWhisker کاربرد دارد. قابل‌خواندن/قابل‌نوشتن boolean.

**بازمی‌گرداند:**
boolean

### setShowMeanLine(boolean value) {#setShowMeanLine-boolean-}
```
public final void setShowMeanLine(boolean value)
```

خط میانگین را نشان می‌دهد. اگر خط میانگین در نمودار BoxAndWhisker نشان داده شود true برمی‌گرداند. فقط برای نمودارهای BoxAndWhisker کاربرد دارد. قابل‌خواندن/قابل‌نوشتن boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getQuartileMethod() {#getQuartileMethod--}
```
public final int getQuartileMethod()
```

روش چارک را نشان می‌دهد. فقط برای نمودارهای BoxAndWhisker کاربرد دارد.

**بازمی‌گرداند:**
int

### setQuartileMethod(int value) {#setQuartileMethod-int-}
```
public final void setQuartileMethod(int value)
```

روش چارک را نشان می‌دهد. فقط برای نمودارهای BoxAndWhisker کاربرد دارد.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getShowConnectorLines() {#getShowConnectorLines--}
```
public final boolean getShowConnectorLines()
```

خطوط متصل را نشان می‌دهد. فقط برای نمودارهای Waterfall کاربرد دارد.

**بازمی‌گرداند:**
boolean

### setShowConnectorLines(boolean value) {#setShowConnectorLines-boolean-}
```
public final void setShowConnectorLines(boolean value)
```

خطوط متصل را نشان می‌دهد. فقط برای نمودارهای Waterfall کاربرد دارد.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getParentLabelLayout() {#getParentLabelLayout--}
```
public final int getParentLabelLayout()
```

چیدمان برچسب‌های دسته والد را نشان می‌دهد. فقط برای نمودارهای Treemap کاربرد دارد.

**بازمی‌گرداند:**
int

### setParentLabelLayout(int value) {#setParentLabelLayout-int-}
```
public final void setParentLabelLayout(int value)
```

چیدمان برچسب‌های دسته والد را نشان می‌دهد. فقط برای نمودارهای Treemap کاربرد دارد.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### hasUpDownBars() {#hasUpDownBars--}
```
public final boolean hasUpDownBars()
```

تعیین می‌کند که آیا نمودار خط یا سهام دارای میله‌های بالا/پایین است یا خیر. این ویژگی نه تنها برای این سری بلکه برای تمام سری‌های گروه سری والد نیز اعمال می‌شود؛ بنابراین فقط-خواندنی است. برای تغییر مقدار از ویژگی ParentSeriesGroup.UpDownBars.HasUpDownBars استفاده کنید. برای قالب‌بندی میله‌های بالا/پایین از ویژگی ParentSeriesGroup.UpDownBars استفاده کنید. فقط-خواندنی boolean.

--------------------

این تصویر خصوصیت ParentSeriesGroup.UpDownBars.HasUpDownBars است.

**بازمی‌گرداند:**
boolean

### getGapWidth() {#getGapWidth--}
```
public final int getGapWidth()
```

فاصله بین دسته‌های میله یا ستون را به‌صورت درصدی از عرض میله یا ستون مشخص می‌کند. این ویژگی نه تنها برای این سری بلکه برای تمام سری‌های گروه سری والد نیز اعمال می‌شود؛ بنابراین فقط-خواندنی است. برای تغییر مقدار از ویژگی ParentSeriesGroup.GapWidth استفاده کنید. فقط-خواندنی int.

--------------------

این تصویر خصوصیت ParentSeriesGroup.GapWidth است.

**بازمی‌گرداند:**
int

### getGapDepth() {#getGapDepth--}
```
public final int getGapDepth()
```

فاصله را به‌عنوان درصدی از عرض نشانگر بین سری‌های داده در یک نمودار 3-بعدی برمی‌گرداند یا تنظیم می‌کند. این ویژگی نه تنها برای این سری بلکه برای تمام سری‌های گروه سری والد نیز اعمال می‌شود؛ بنابراین فقط-خواندنی است. برای تغییر مقدار از ویژگی ParentSeriesGroup.GapDepth استفاده کنید. فقط-خواندنی int.

--------------------

این تصویر خصوصیت ParentSeriesGroup.GapDepth است.

**بازمی‌گرداند:**
int

### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public final int getFirstSliceAngle()
```

زاویه اولین برش نمودار پای یا دونات را بر حسب درجه (ساعت‌گرد از بالا، از 0 تا 360 درجه) مشخص می‌کند. این ویژگی نه تنها برای این سری بلکه برای تمام سری‌های گروه سری والد نیز اعمال می‌شود؛ بنابراین فقط-خواندنی است. برای تغییر مقدار از ویژگی ParentSeriesGroup.FirstSliceAngle استفاده کنید. فقط-خواندنی int.

--------------------

این تصویر خصوصیت ParentSeriesGroup.FirstSliceAngle است.

**بازمی‌گرداند:**
int

### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public final byte getDoughnutHoleSize()
```

اندازه سوراخ در نمودار دونات را مشخص می‌کند (می‌تواند بین 10 تا 90 درصد از اندازه ناحیه رسم باشد). این ویژگی نه تنها برای این سری بلکه برای تمام سری‌های گروه سری والد نیز اعمال می‌شود؛ بنابراین فقط-خواندنی است. برای تغییر مقدار از ویژگی ParentSeriesGroup.DoughnutHoleSize استفاده کنید. فقط-خواندنی byte.

--------------------

این تصویر خصوصیت ParentSeriesGroup.DoughnutHoleSize است.

**بازمی‌گرداند:**
byte

### getOverlap() {#getOverlap--}
```
public final byte getOverlap()
```

میزان هم‌پوشانی میله‌ها و ستون‌ها در نمودارهای دو-بعدی را به‌صورت درصد (از -100٪ تا 100٪) مشخص می‌کند. این ویژگی نه تنها برای این سری بلکه برای تمام سری‌های گروه سری والد نیز اعمال می‌شود؛ بنابراین فقط-خواندنی است. برای تغییر مقدار از ویژگی ParentSeriesGroup.Overlap استفاده کنید. فقط- خواندنی byte.

--------------------

Overlap نشان‌دهنده درجه هم‌پوشانی یا فاصله بین میله‌ها و ستون‌ها به‌صورت درصدی از عرض آن‌هاست:
- -100٪: حداکثر فاصله (میله‌ها کاملاً جدا هستند).
- 0٪: میله‌ها بدون هم‌پوشانی یا فاصله کنار هم قرار می‌گیرند.
- 100٪: حداکثر هم‌پوشانی (میله‌ها کاملاً روی هم قرار می‌گیرند).

این تصویر خصوصیت ParentSeriesGroup.Overlap است.

**بازمی‌گرداند:**
byte

### getSecondPieSize() {#getSecondPieSize--}
```
public final int getSecondPieSize()
```

اندازه دومین پای یا میله در نمودار پای-در-پای یا میله-در-پای را به‌عنوان درصدی از اندازه اولین پای (می‌تواند بین 5 تا 200 درصد باشد) مشخص می‌کند. این ویژگی نه تنها برای این سری بلکه برای تمام سری‌های گروه سری والد نیز اعمال می‌شود؛ بنابراین فقط-خواندنی است. برای تغییر مقدار از ویژگی ParentSeriesGroup.SecondPieSize استفاده کنید. فقط-خواندنی int.

--------------------

این تصویر خصوصیت ParentSeriesGroup.SecondPieSize است.

**بازمی‌گرداند:**
int

### hasSeriesLines() {#hasSeriesLines--}
```
public final boolean hasSeriesLines()
```

تعیین می‌کند که آیا خطوط سری برای این سری و سری‌های مرتبط وجود دارد یا خیر. این ویژگی نه تنها برای این سری بلکه برای تمام سری‌های گروه سری والد نیز اعمال می‌شود؛ بنابراین فقط-خواندنی است. برای تغییر مقدار از ویژگی ParentSeriesGroup.HasSeriesLines استفاده کنید. برای قالب‌بندی خطوط سری از ویژگی ParentSeriesGroup.SeriesLinesFormat استفاده کنید. فقط-خواندنی boolean.

--------------------

این تصویر خصوصیت ParentSeriesGroup.HasSeriesLines است.

**بازمی‌گرداند:**
boolean

### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public final int getBubbleSizeRepresentation()
```

نحوه نمایش مقادیر اندازه حباب‌ها در نمودار حبابی را مشخص می‌کند. این ویژگی نه تنها برای این سری بلکه برای تمام سری‌های گروه سری والد نیز اعمال می‌شود؛ بنابراین فقط-خواندنی است. برای تغییر مقدار از ویژگی ParentSeriesGroup.BubbleSizeRepresentation استفاده کنید.

--------------------

این تصویر خصوصیت ParentSeriesGroup.BubbleSizeRepresentation است.

**بازمی‌گرداند:**
int

### getPieSplitPosition() {#getPieSplitPosition--}
```
public final double getPieSplitPosition()
```

مقداری را که برای تعیین نقاط داده‌ای که در دومین پای یا میله در نمودار پای-در-پای یا میله-در-پای قرار می‌گیرند استفاده می‌شود را مشخص می‌کند. این مقدار همراه با ویژگی PieSplitBy استفاده می‌شود. این ویژگی نه تنها برای این سری بلکه برای تمام سری‌های گروه سری والد نیز اعمال می‌شود؛ بنابراین فقط-خواندنی است. برای تغییر مقدار از ویژگی ParentSeriesGroup.PieSplitPosition استفاده کنید. فقط-خواندنی double.

--------------------

این تصویر خصوصیت ParentSeriesGroup.PieSplitPosition است.

**بازمی‌گرداند:**
double

### getPieSplitBy() {#getPieSplitBy--}
```
public final int getPieSplitBy()
```

نحوه تعیین نقاط داده‌ای که در دومین پای یا میله در نمودار پای-در-پای یا میله-در-پای قرار می‌گیرند را مشخص می‌کند. این ویژگی نه تنها برای این سری بلکه برای تمام سری‌های گروه سری والد نیز اعمال می‌شود؛ بنابراین فقط-خواندنی است. برای تغییر مقدار از ویژگی ParentSeriesGroup.PieSplitBy استفاده کنید. فقط-خواندنی [PieSplitType](../../com.aspose.slides/piesplittype).

--------------------

1) این تصویر خصوصیت ParentSeriesGroup.PieSplitBy است. 2) اگر مقدار ویژگی PieSplitType.Custom باشد می‌توانید اطلاعات تقسیم سفارشی را با ویژگی ParentSeriesGroup.PieSplitCustomPoints تعریف کنید.

**بازمی‌گرداند:**
int

### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public final IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

اطلاعات تقسیم سفارشی برای نمودار پای-در-پای یا میله-در-پای با تقسیم سفارشی. شامل نقاط داده‌ای است که باید در دومین پای یا میله رسم شوند. این ویژگی نه تنها برای این سری بلکه برای تمام سری‌های گروه سری والد نیز اعمال می‌شود؛ بنابراین فقط-خواندنی است. [PieSplitCustomPointCollection](../../com.aspose.slides/piesplitcustompointcollection).

--------------------

این تصویر خصوصیت ParentSeriesGroup.PieSplitCustomPoints است.

**بازمی‌گرداند:**
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)

### isColorVaried() {#isColorVaried--}
```
public final boolean isColorVaried()
```

مشخص می‌کند که هر نشانگر داده در سری رنگ متفاوتی داشته باشد. این ویژگی نه تنها برای این سری بلکه برای تمام سری‌های گروه سری والد نیز اعمال می‌شود؛ بنابراین فقط-خواندنی است. برای تغییر مقدار از ویژگی ParentSeriesGroup.IsColorVaried استفاده کنید. فقط-خواندنی boolean.

--------------------

این تصویر خصوصیت ParentSeriesGroup.IsColorVaried است.

**بازمی‌گرداند:**
boolean

### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public final int getBubbleSizeScale()
```

فاکتور مقیاس برای نمودار حبابی را مشخص می‌کند (می‌تواند بین 0 تا 300 درصد از اندازه پیش‌فرض باشد). این ویژگی نه تنها برای این سری بلکه برای تمام سری‌های گروه سری والد نیز اعمال می‌شود؛ بنابراین فقط-خواندنی است. برای تغییر مقدار از ویژگی ParentSeriesGroup.BubbleSizeScale استفاده کنید.

--------------------

این تصویر خصوصیت ParentSeriesGroup.BubbleSizeScale است.

**بازمی‌گرداند:**
int

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

اسلاید والد FillFormat را برمی‌گرداند. فقط-خواندنی [BaseSlide](../../com.aspose.slides/baseslide).

**بازمی‌گرداند:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

ارائه والد FillFormat را برمی‌گرداند. فقط-خواندنی [IPresentation](../../com.aspose.slides/ipresentation).

**بازمی‌گرداند:**
[IPresentation](../../com.aspose.slides/ipresentation)