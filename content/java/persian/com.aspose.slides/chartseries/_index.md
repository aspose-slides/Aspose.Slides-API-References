---
title: ChartSeries
second_title: مرجع API Aspose.Slides برای Java
description: نمایانگر یک سری نمودار.
type: docs
url: /fa/com.aspose.slides/chartseries/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IChartSeries](../../com.aspose.slides/ichartseries), com.aspose.slides.IDOMObject
```
public class ChartSeries implements IChartSeries, IDOMObject
```

نمایانگر یک سری نمودار.
## متدها

| متد | توضیح |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getChart()](#getChart--) | نمودار والد را باز می‌گرداند. |
| [getExplosion()](#getExplosion--) | فاصلهٔ یک قطعهٔ کیک باز از مرکز نمودار کیک به‌صورت درصدی از قطر کیک بیان می‌شود. |
| [setExplosion(int value)](#setExplosion-int-) | فاصلهٔ یک قطعهٔ کیک باز از مرکز نمودار کیک به‌صورت درصدی از قطر کیک بیان می‌شود. |
| [getSmooth()](#getSmooth--) | نمایانگر صاف‌سازی منحنی. |
| [setSmooth(boolean value)](#setSmooth-boolean-) | نمایانگر صاف‌سازی منحنی. |
| [getName()](#getName--) | نام سری را باز می‌گرداند. |
| [getDataPoints()](#getDataPoints--) | مجموعه نقاط داده این سری را باز می‌گرداند. |
| [getType()](#getType--) | نوعی از این سری را باز می‌گرداند. |
| [setType(int value)](#setType-int-) | نوعی از این سری را باز می‌گرداند. |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | نشان می‌دهد آیا این سری روی محور ثانویه ترسیم می‌شود. |
| [setPlotOnSecondAxis(boolean value)](#setPlotOnSecondAxis-boolean-) | نشان می‌دهد آیا این سری روی محور ثانویه ترسیم می‌شود. |
| [getParentSeriesGroup()](#getParentSeriesGroup--) | ParentSeriesGroup. |
| [getFormat()](#getFormat--) | قالب یک سری را باز می‌گرداند. |
| [getOrder()](#getOrder--) | ترتیب یک سری را باز می‌گرداند. |
| [setOrder(int value)](#setOrder-int-) | ترتیب یک سری را باز می‌گرداند. |
| [getLabels()](#getLabels--) | برچسب‌های یک سری را باز می‌گرداند. |
| [getTrendLines()](#getTrendLines--) | مجموعه خطوط روند سری. |
| [getErrorBarsXFormat()](#getErrorBarsXFormat--) | نمایانگر ErrorBars سری با جهت X. |
| [getErrorBarsYFormat()](#getErrorBarsYFormat--) | نمایانگر ErrorBars سری با جهت Y. |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | نمایانگر ورودی افسانه مرتبط با این سری فقط-خواندنی [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties). |
| [getNumberFormatOfValues()](#getNumberFormatOfValues--) | NumberFormatOfValues. |
| [setNumberFormatOfValues(String value)](#setNumberFormatOfValues-java.lang.String-) | NumberFormatOfValues. |
| [getNumberFormatOfXValues()](#getNumberFormatOfXValues--) | NumberFormatOfXValues. |
| [setNumberFormatOfXValues(String value)](#setNumberFormatOfXValues-java.lang.String-) | NumberFormatOfXValues. |
| [getNumberFormatOfYValues()](#getNumberFormatOfYValues--) | NumberFormatOfYValues. |
| [setNumberFormatOfYValues(String value)](#setNumberFormatOfYValues-java.lang.String-) | NumberFormatOfYValues. |
| [getNumberFormatOfBubbleSizes()](#getNumberFormatOfBubbleSizes--) | NumberFormatOfBubbleSizes. |
| [setNumberFormatOfBubbleSizes(String value)](#setNumberFormatOfBubbleSizes-java.lang.String-) | NumberFormatOfBubbleSizes. |
| [getMarker()](#getMarker--) | Marker. |
| [getBar3DShape()](#getBar3DShape--) | مشخص می‌کند شکل یک سری از نمودار میله‌ای سه‌بعدی. |
| [setBar3DShape(int value)](#setBar3DShape-int-) | مشخص می‌کند شکل یک سری از نمودار میله‌ای سه‌بعدی. |
| [getInvertIfNegative()](#getInvertIfNegative--) | مشخص می‌کند میله، ستون یا سری حباب در صورت منفی بودن مقدار، رنگ‌های خود را معکوس کند. |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | مشخص می‌کند میله، ستون یا سری حباب در صورت منفی بودن مقدار، رنگ‌های خود را معکوس کند. |
| [getInvertedSolidFillColor()](#getInvertedSolidFillColor--) | مشخص می‌کند معکوس کردن رنگ جامد برای سری. |
| [getAutomaticSeriesColor()](#getAutomaticSeriesColor--) | یک رنگ خودکار برای سری بر اساس اندیس سری و سبک نمودار باز می‌گرداند. |
| [getShowInnerPoints()](#getShowInnerPoints--) | نمایانگر نقاط داخلی. |
| [setShowInnerPoints(boolean value)](#setShowInnerPoints-boolean-) | نمایانگر نقاط داخلی. |
| [getShowOutlierPoints()](#getShowOutlierPoints--) | نمایانگر نقاط دورافتاده. |
| [setShowOutlierPoints(boolean value)](#setShowOutlierPoints-boolean-) | نمایانگر نقاط دورافتاده. |
| [getShowMeanMarkers()](#getShowMeanMarkers--) | نمایانگر نشانگرهای میانگین. |
| [setShowMeanMarkers(boolean value)](#setShowMeanMarkers-boolean-) | نمایانگر نشانگرهای میانگین. |
| [getShowMeanLine()](#getShowMeanLine--) | نمایانگر خط میانگین. |
| [setShowMeanLine(boolean value)](#setShowMeanLine-boolean-) | نمایانگر خط میانگین. |
| [getQuartileMethod()](#getQuartileMethod--) | نمایانگر روش چارک. |
| [setQuartileMethod(int value)](#setQuartileMethod-int-) | نمایانگر روش چارک. |
| [getShowConnectorLines()](#getShowConnectorLines--) | نمایانگر خطوط اتصال. |
| [setShowConnectorLines(boolean value)](#setShowConnectorLines-boolean-) | نمایانگر خطوط اتصال. |
| [getParentLabelLayout()](#getParentLabelLayout--) | نمایانگر چیدمان برچسب‌های دسته‌بندی والد. |
| [setParentLabelLayout(int value)](#setParentLabelLayout-int-) | نمایانگر چیدمان برچسب‌های دسته‌بندی والد. |
| [hasUpDownBars()](#hasUpDownBars--) | تعیین می‌کند آیا نمودار خط یا سهام دارای نوارهای بالا/پایین است. |
| [getGapWidth()](#getGapWidth--) | فضای بین خوشه‌های میله یا ستون را به‌عنوان درصدی از عرض میله یا ستون مشخص می‌کند. |
| [getGapDepth()](#getGapDepth--) | فاصله را به‌عنوان درصدی از عرض نشانگر بین سری‌های داده در یک نمودار سه‌بعدی باز می‌گرداند یا تنظیم می‌کند. |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | زاویه اولین قطعه کیک یا دونات را بر حسب درجه (ساعت‌گرد از بالا، از 0 تا 360 درجه) مشخص می‌کند. |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | اندازهٔ حفره در نمودار دونات را مشخص می‌کند (می‌تواند بین 10 تا 90 درصد از اندازهٔ ناحیهٔ ترسیم باشد). |
| [getOverlap()](#getOverlap--) | مشخص می‌کند چقدر میله‌ها و ستون‌ها در نمودارهای دو‌بعدی همپوشانی دارند، به‌عنوان درصد (از -100% تا 100%). |
| [getSecondPieSize()](#getSecondPieSize--) | اندازهٔ دومین کیک یا میله در نمودار کیک-از-کیک یا میله-از-کیک را به‌عنوان درصدی از اندازهٔ کیک اول مشخص می‌کند (می‌تواند بین 5 تا 200 درصد باشد). |
| [hasSeriesLines()](#hasSeriesLines--) | تعیین می‌کند آیا خطوط سری برای این سری و سری‌های مرتبط وجود دارد. |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | نحوهٔ نمایش مقادیر اندازهٔ حباب در نمودار حباب را مشخص می‌کند. |
| [getPieSplitPosition()](#getPieSplitPosition--) | مقدارهایی را تعیین می‌کند که برای شناسایی نقاط داده در کیک دوم یا میله دوم در نمودار کیک-از-کیک یا میله-از-کیک استفاده می‌شود. |
| [getPieSplitBy()](#getPieSplitBy--) | نحوهٔ تعیین نقاط داده در کیک دوم یا میله دوم در نمودار کیک-از-کیک یا میله-از-کیک را مشخص می‌کند. |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | اطلاعات تقسیم سفارشی برای نمودار کیک-از-کیک یا میله-از-کیک با تقسیم سفارشی. |
| [isColorVaried()](#isColorVaried--) | مشخص می‌کند هر نشانگر داده در سری رنگ متفاوتی داشته باشد. |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | مقیاس ضریب برای نمودار حباب را مشخص می‌کند (می‌تواند بین 0 تا 300 درصد اندازهٔ پیش‌فرض باشد). |
| [getSlide()](#getSlide--) | اسلاید والد یک FillFormat را باز می‌گرداند. |
| [getPresentation()](#getPresentation--) | ارائه‌گر والد یک FillFormat را باز می‌گرداند. |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

نمونهٔ Parent_Immediate را باز می‌گرداند. فقط-خواندنی IDOMObject.

**بازگشت:**
com.aspose.slides.IDOMObject

### getChart() {#getChart--}
```
public final IChart getChart()
```

نمودار والد را باز می‌گرداند. فقط-خواندنی [IChart](../../com.aspose.slides/ichart).

**بازگشت:**
[IChart](../../com.aspose.slides/ichart)

### getExplosion() {#getExplosion--}
```
public final int getExplosion()
```

فاصلهٔ یک قطعهٔ کیک باز از مرکز نمودار کیک به‌صورت درصدی از قطر کیک بیان می‌شود. قابل‌نوشتن int.

**بازگشت:**
int

### setExplosion(int value) {#setExplosion-int-}
```
public final void setExplosion(int value)
```

فاصلهٔ یک قطعهٔ کیک باز از مرکز نمودار کیک به‌صورت درصدی از قطر کیک بیان می‌شود. قابل‌نوشتن int.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getSmooth() {#getSmooth--}
```
public final boolean getSmooth()
```

نمایانگر صاف‌سازی منحنی. اگر صاف‌سازی برای نمودار خط یا پراکندگی فعال باشد، true برگردانده می‌شود. فقط برای نمودارهای خط و پراکندگی متصل به خطوط اعمال می‌شود. قابل‌نوشتن boolean.

**بازگشت:**
boolean

### setSmooth(boolean value) {#setSmooth-boolean-}
```
public final void setSmooth(boolean value)
```

نمایانگر صاف‌سازی منحنی. اگر صاف‌سازی برای نمودار خط یا پراکندگی فعال باشد، true برگردانده می‌شود. فقط برای نمودارهای خط و پراکندگی متصل به خطوط اعمال می‌شود. قابل‌نوشتن boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getName() {#getName--}
```
public final IStringChartValue getName()
```

نام سری را باز می‌گرداند. فقط-خواندنی [IStringChartValue](../../com.aspose.slides/istringchartvalue).

**بازگشت:**
[IStringChartValue](../../com.aspose.slides/istringchartvalue)

### getDataPoints() {#getDataPoints--}
```
public final IChartDataPointCollection getDataPoints()
```

مجموعه نقاط داده این سری را باز می‌گرداند. فقط-خواندنی [IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection).

**بازگشت:**
[IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection)

### getType() {#getType--}
```
public final int getType()
```

نوعی از این سری را باز می‌گرداند. قابل‌نوشتن [ChartType](../../com.aspose.slides/charttype).

**بازگشت:**
int

### setType(int value) {#setType-int-}
```
public final void setType(int value)
```

نوعی از این سری را باز می‌گرداند. قابل‌نوشتن [ChartType](../../com.aspose.slides/charttype).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getPlotOnSecondAxis() {#getPlotOnSecondAxis--}
```
public final boolean getPlotOnSecondAxis()
```

نشان می‌دهد آیا این سری روی محور ثانویه ترسیم می‌شود. قابل‌نوشتن boolean.

**بازگشت:**
boolean

### setPlotOnSecondAxis(boolean value) {#setPlotOnSecondAxis-boolean-}
```
public final void setPlotOnSecondAxis(boolean value)
```

نشان می‌دهد آیا این سری روی محور ثانویه ترسیم می‌شود. قابل‌نوشتن boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getParentSeriesGroup() {#getParentSeriesGroup--}
```
public final IChartSeriesGroup getParentSeriesGroup()
```

ParentSeriesGroup. فقط-خواندنی [IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup).

**بازگشت:**
[IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup)

### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

قالب یک سری را باز می‌گرداند. فقط-خواندنی [IFormat](../../com.aspose.slides/iformat).

**بازگشت:**
[IFormat](../../com.aspose.slides/iformat)

### getOrder() {#getOrder--}
```
public final int getOrder()
```

ترتیب یک سری را باز می‌گرداند. قابل‌نوشتن int.

**بازگشت:**
int

### setOrder(int value) {#setOrder-int-}
```
public final void setOrder(int value)
```

ترتیب یک سری را باز می‌گرداند. قابل‌نوشتن int.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getLabels() {#getLabels--}
```
public final IDataLabelCollection getLabels()
```

برچسب‌های یک سری را باز می‌گرداند. فقط-خواندنی [IDataLabelCollection](../../com.aspose.slides/idatalabelcollection).

**بازگشت:**
[IDataLabelCollection](../../com.aspose.slides/idatalabelcollection)

### getTrendLines() {#getTrendLines--}
```
public final ITrendlineCollection getTrendLines()
```

مجموعه خطوط روند سری. فقط-خواندنی [ITrendlineCollection](../../com.aspose.slides/itrendlinecollection).

--------------------

TrendLines برای سری‌های داده در نمودارهای ناحیه، میله، ستون، خط، سهام، xy (پراکندگی) و حباب دو-بعدی که پشته‌دار نیستند، موجود هستند. برای انواع نمودارهای پشته‌دار یا سه‌بعدی، TrendLines موجود نیست. همچنین برای نمودارهای رادار، کیک، سطح یا دونات نیز موجود نیست.

**بازگشت:**
[ITrendlineCollection](../../com.aspose.slides/itrendlinecollection)

### getErrorBarsXFormat() {#getErrorBarsXFormat--}
```
public final IErrorBarsFormat getErrorBarsXFormat()
```

نمایانگر ErrorBars سری با جهت X. فقط-خواندنی [IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat).

--------------------

ErrorBars با جهت X برای سری‌های نوع ناحیه، میله، پراکندگی و حباب قابل استفاده است. برای سایر انواع نمودار این ویژگی null برمی‌گرداند (از جمله نمودارهای 3D). در صورت استفاده از مقادیر سفارشی، از مجموعه DataPoints برای تعیین مقدار استفاده کنید (با ویژگی ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues))).

**بازگشت:**
[IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)

### getErrorBarsYFormat() {#getErrorBarsYFormat--}
```
public final IErrorBarsFormat getErrorBarsYFormat()
```

نمایانگر ErrorBars سری با جهت Y. فقط-خواندنی [IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat).

--------------------

ErrorBars با جهت Y برای سری‌های نوع ناحیه، میله، خط، پراکندگی و حباب قابل استفاده است. برای سایر انواع نمودار این ویژگی null برمی‌گرداند (از جمله نمودارهای 3D). در صورت استفاده از مقادیر سفارشی، از مجموعه DataPoints برای تعیین مقدار استفاده کنید (با ویژگی ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues))).

**بازگشت:**
[IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)

### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public final ILegendEntryProperties getRelatedLegendEntry()
```

نمایانگر ورودی افسانه مرتبط با این سری فقط-خواندنی [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**بازگشت:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)

### getNumberFormatOfValues() {#getNumberFormatOfValues--}
```
public final String getNumberFormatOfValues()
```

NumberFormatOfValues. قابل‌نوشتن String.

**بازگشت:**
java.lang.String

### setNumberFormatOfValues(String value) {#setNumberFormatOfValues-java.lang.String-}
```
public final void setNumberFormatOfValues(String value)
```

NumberFormatOfValues. قابل‌نوشتن String.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |

### getNumberFormatOfXValues() {#getNumberFormatOfXValues--}
```
public final String getNumberFormatOfXValues()
```

NumberFormatOfXValues. قابل‌نوشتن String.

**بازگشت:**
java.lang.String

### setNumberFormatOfXValues(String value) {#setNumberFormatOfXValues-java.lang.String-}
```
public final void setNumberFormatOfXValues(String value)
```

NumberFormatOfXValues. قابل‌نوشتن String.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |

### getNumberFormatOfYValues() {#getNumberFormatOfYValues--}
```
public final String getNumberFormatOfYValues()
```

NumberFormatOfYValues. قابل‌نوشتن String.

**بازگشت:**
java.lang.String

### setNumberFormatOfYValues(String value) {#setNumberFormatOfYValues-java.lang.String-}
```
public final void setNumberFormatOfYValues(String value)
```

NumberFormatOfYValues. قابل‌نوشتن String.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |

### getNumberFormatOfBubbleSizes() {#getNumberFormatOfBubbleSizes--}
```
public final String getNumberFormatOfBubbleSizes()
```

NumberFormatOfBubbleSizes. قابل‌نوشتن String.

**بازگشت:**
java.lang.String

### setNumberFormatOfBubbleSizes(String value) {#setNumberFormatOfBubbleSizes-java.lang.String-}
```
public final void setNumberFormatOfBubbleSizes(String value)
```

NumberFormatOfBubbleSizes. قابل‌نوشتن String.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |

### getMarker() {#getMarker--}
```
public final IMarker getMarker()
```

Marker. فقط-خواندنی [IMarker](../../com.aspose.slides/imarker).

**بازگشت:**
[IMarker](../../com.aspose.slides/imarker)

### getBar3DShape() {#getBar3DShape--}
```
public final int getBar3DShape()
```

مشخص می‌کند شکل یک سری از نمودار میله‌ای سه‌بعدی. تغییر مقدار این ویژگی می‌تواند باعث تغییر خودکار نوع سری شود. قابل‌نوشتن [ChartShapeType](../../com.aspose.slides/chartshapetype).

**بازگشت:**
int

### setBar3DShape(int value) {#setBar3DShape-int-}
```
public final void setBar3DShape(int value)
```

مشخص می‌کند شکل یک سری از نمودار میله‌ای سه‌بعدی. تغییر مقدار این ویژگی می‌تواند باعث تغییر خودکار نوع سری شود. قابل‌نوشتن [ChartShapeType](../../com.aspose.slides/chartshapetype).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getInvertIfNegative() {#getInvertIfNegative--}
```
public final boolean getInvertIfNegative()
```

مشخص می‌کند میله، ستون یا سری حباب در صورت منفی بودن مقدار، رنگ‌های خود را معکوس کند. قابل‌نوشتن boolean.

**بازگشت:**
boolean

### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public final void setInvertIfNegative(boolean value)
```

مشخص می‌کند میله، ستون یا سری حباب در صورت منفی بودن مقدار، رنگ‌های خود را معکوس کند. قابل‌نوشتن boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getInvertedSolidFillColor() {#getInvertedSolidFillColor--}
```
public final IColorFormat getInvertedSolidFillColor()
```
Specifies invert solid color for series. To apply color setting set series format FillType to FillType.Solid. Read/write [ColorFormat](../../com.aspose.slides/colorformat).

**بازگشت:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getAutomaticSeriesColor() {#getAutomaticSeriesColor--}
```
public final Color getAutomaticSeriesColor()
```


Returns an automatic color of series based on series index and chart style. This color is used by default if FillType equals NotDefined.

**بازگشت:**
java.awt.Color - The java.awt.Color object.
### getShowInnerPoints() {#getShowInnerPoints--}
```
public final boolean getShowInnerPoints()
```


Represents inner points. True if inner points are shown on the BoxAndWhisker chart. Applies only to BoxAndWhisker charts. Read/write boolean.

**بازگشت:**
boolean
### setShowInnerPoints(boolean value) {#setShowInnerPoints-boolean-}
```
public final void setShowInnerPoints(boolean value)
```


Represents inner points. True if inner points are shown on the BoxAndWhisker chart. Applies only to BoxAndWhisker charts. Read/write boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getShowOutlierPoints() {#getShowOutlierPoints--}
```
public final boolean getShowOutlierPoints()
```


Represents outlier points. True if outlier points are shown on the BoxAndWhisker chart. Applies only to BoxAndWhisker charts. Read/write boolean.

**بازگشت:**
boolean
### setShowOutlierPoints(boolean value) {#setShowOutlierPoints-boolean-}
```
public final void setShowOutlierPoints(boolean value)
```


Represents outlier points. True if outlier points are shown on the BoxAndWhisker chart. Applies only to BoxAndWhisker charts. Read/write boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getShowMeanMarkers() {#getShowMeanMarkers--}
```
public final boolean getShowMeanMarkers()
```


Represents mean markers. True if mean markers are shown on the BoxAndWhisker chart. Applies only to BoxAndWhisker charts. Read/write boolean.

**بازگشت:**
boolean
### setShowMeanMarkers(boolean value) {#setShowMeanMarkers-boolean-}
```
public final void setShowMeanMarkers(boolean value)
```


Represents mean markers. True if mean markers are shown on the BoxAndWhisker chart. Applies only to BoxAndWhisker charts. Read/write boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getShowMeanLine() {#getShowMeanLine--}
```
public final boolean getShowMeanLine()
```


Represents mean line. True if mean line are shown on the BoxAndWhisker chart. Applies only to BoxAndWhisker charts. Read/write boolean.

**بازگشت:**
boolean
### setShowMeanLine(boolean value) {#setShowMeanLine-boolean-}
```
public final void setShowMeanLine(boolean value)
```


Represents mean line. True if mean line are shown on the BoxAndWhisker chart. Applies only to BoxAndWhisker charts. Read/write boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getQuartileMethod() {#getQuartileMethod--}
```
public final int getQuartileMethod()
```


Represents quartile method. Applies only to BoxAndWhisker charts.

**بازگشت:**
int
### setQuartileMethod(int value) {#setQuartileMethod-int-}
```
public final void setQuartileMethod(int value)
```


Represents quartile method. Applies only to BoxAndWhisker charts.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getShowConnectorLines() {#getShowConnectorLines--}
```
public final boolean getShowConnectorLines()
```


Represents connector lines. Applies only to Waterfall charts.

**بازگشت:**
boolean
### setShowConnectorLines(boolean value) {#setShowConnectorLines-boolean-}
```
public final void setShowConnectorLines(boolean value)
```


Represents connector lines. Applies only to Waterfall charts.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getParentLabelLayout() {#getParentLabelLayout--}
```
public final int getParentLabelLayout()
```


Represents layout of parent category labels. Applies only to Treemap charts.

**بازگشت:**
int
### setParentLabelLayout(int value) {#setParentLabelLayout-int-}
```
public final void setParentLabelLayout(int value)
```


Represents layout of parent category labels. Applies only to Treemap charts.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### hasUpDownBars() {#hasUpDownBars--}
```
public final boolean hasUpDownBars()
```


Determines whether Line- or Stock-chart has a up/down bars. This is the property not only of this series but of all series of parent series group - this is projection of appropriate group property. And so this property is read-only. Use ParentSeriesGroup property for access to parent series group. Use ParentSeriesGroup.UpDownBars.HasUpDownBars read/write property for change value. Use ParentSeriesGroup.UpDownBars property for format up/down bars. Read-only boolean.

--------------------

This is the projection of the property ParentSeriesGroup.UpDownBars.HasUpDownBars.

**بازگشت:**
boolean
### getGapWidth() {#getGapWidth--}
```
public final int getGapWidth()
```


Specifies the space between bar or column clusters, as a percentage of the bar or column width. This is the property not only of this series but of all series of parent series group - this is projection of appropriate group property. And so this property is read-only. Use ParentSeriesGroup property for access to parent series group. Use ParentSeriesGroup.GapWidth read/write property for change value. Read-only int.

--------------------

This is the projection of the property ParentSeriesGroup.GapWidth.

**بازگشت:**
int
### getGapDepth() {#getGapDepth--}
```
public final int getGapDepth()
```


Returns or sets the distance, as a percentage of the marker width, between the data series in a 3D chart. This is the property not only of this series but of all series of parent series group - this is projection of appropriate group property. And so this property is read-only. Use ParentSeriesGroup property for access to parent series group. Use ParentSeriesGroup.GapDepth read/write property for change value. Read-only int.

--------------------

This is the projection of the property ParentSeriesGroup.GapDepth.

**بازگشت:**
int
### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public final int getFirstSliceAngle()
```


Specifies the angle of the first pie or doughnut chart slice, in degrees (clockwise from up, from 0 to 360 degrees). This is the property not only of this series but of all series of parent series group - this is projection of appropriate group property. And so this property is read-only. Use ParentSeriesGroup property for access to parent series group. Use ParentSeriesGroup.FirstSliceAngle read/write property for change value. Read-only int.

--------------------

This is the projection of the property ParentSeriesGroup.FirstSliceAngle.

**بازگشت:**
int
### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public final byte getDoughnutHoleSize()
```


Specifies the size of the hole in a doughnut chart (can be between 10 and 90 percents of the size of the plot area.). This is the property not only of this series but of all series of parent series group - this is projection of appropriate group property. And so this property is read-only. Use ParentSeriesGroup property for access to parent series group. Use ParentSeriesGroup.DoughnutHoleSize read/write property for change value. Read-only byte.

--------------------

This is the projection of the property ParentSeriesGroup.DoughnutHoleSize.

**بازگشت:**
byte
### getOverlap() {#getOverlap--}
```
public final byte getOverlap()
```


Specifies how much bars and columns overlap on 2-D charts, as a percentage (from -100% to 100%). This is the property not only of this series but of all series of parent series group. It is a projection of the appropriate property in the parent series group, and so this property is read-only. To change the value, use the ParentSeriesGroup.Overlap read/write property. Read-only byte.

--------------------

Overlap specifies the degree of overlap or spacing between bars and columns as a percentage of their width: - -100%: Maximum spacing (bars are completely separated). - 0%: Bars are placed side by side without overlap or spacing. - 100%: Maximum overlap (bars completely overlap each other). This is a projection of the property ParentSeriesGroup.Overlap.

**بازگشت:**
byte
### getSecondPieSize() {#getSecondPieSize--}
```
public final int getSecondPieSize()
```


Specifies the size of the second pie or bar of a pie-of-pie chart or a bar-of-pie chart, as a percentage of the size of the first pie (can be between 5 and 200 percents). This is the property not only of this series but of all series of parent series group - this is projection of appropriate group property. And so this property is read-only. Use ParentSeriesGroup property for access to parent series group. Use ParentSeriesGroup.SecondPieSize read/write property for change value. Read-only int.

--------------------

This is the projection of the property ParentSeriesGroup.SecondPieSize.

**بازگشت:**
int
### hasSeriesLines() {#hasSeriesLines--}
```
public final boolean hasSeriesLines()
```


Determines whether there are series lines for this series and kindred series. This is the property not only of this series but of all series of parent series group - this is projection of appropriate group property. And so this property is read-only. Use ParentSeriesGroup property for access to parent series group. Use ParentSeriesGroup.HasSeriesLines read/write property for change value. Use ParentSeriesGroup.SeriesLinesFormat property for format series lines. Read-only boolean.

--------------------

This is the projection of the property ParentSeriesGroup.HasSeriesLines.

**بازگشت:**
boolean
### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public final int getBubbleSizeRepresentation()
```


Specifies how the bubble size values are represented on the bubble chart. This is the property not only of this series but of all series of parent series group - this is projection of appropriate group property. And so this property is read-only. Use ParentSeriesGroup property for access to parent series group. Use ParentSeriesGroup.BubbleSizeRepresentation read/write property for change value.

--------------------

This is the projection of the property ParentSeriesGroup.BubbleSizeRepresentation.

**بازگشت:**
int
### getPieSplitPosition() {#getPieSplitPosition--}
```
public final double getPieSplitPosition()
```


Specifies a value that shall be used to determine which data points are in the second pie or bar on a pie-of-pie or bar-of-pie chart. Is used together with PieSplitBy property. This is the property not only of this series but of all series of parent series group - this is projection of appropriate group property. And so this property is read-only. Use ParentSeriesGroup property for access to parent series group. Use ParentSeriesGroup.PieSplitPosition read/write property for change value. Read-only double.

--------------------

This is the projection of the property ParentSeriesGroup.PieSplitPosition.

**بازگشت:**
double
### getPieSplitBy() {#getPieSplitBy--}
```
public final int getPieSplitBy()
```


Specifies how to determine which data points are in the second pie or bar on a pie-of-pie or bar-of-pie chart. This is the property not only of this series but of all series of parent series group - this is projection of appropriate group property. And so this property is read-only. Use ParentSeriesGroup property for access to parent series group. Use ParentSeriesGroup.PieSplitBy read/write property for change value. Read-only [PieSplitType](../../com.aspose.slides/piesplittype).

--------------------

1) This is the projection of the property ParentSeriesGroup.PieSplitBy. 2) If property value is PieSplitType.Custom then you can define custom split information with ParentSeriesGroup.PieSplitCustomPoints property.

**بازگشت:**
int
### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public final IPieSplitCustomPointCollection getPieSplitCustomPoints()
```


The custom split information for a pie-of-pie or bar-of-pie chart with a custom split. Contains data points that shall be drawn in the second pie or bar in a pie-of-pie or bar-of-pie chart. This is the property not only of this series but of all series of parent series group - this is projection of appropriate group property Read-only [PieSplitCustomPointCollection](../../com.aspose.slides/piesplitcustompointcollection).

--------------------

This is the projection of the property ParentSeriesGroup.PieSplitCustomPoints.

**بازگشت:**
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)
### isColorVaried() {#isColorVaried--}
```
public final boolean isColorVaried()
```
مشخص می‌کند که هر نشانگر داده در سری رنگ متفاوتی دارد. این ویژگی تنها مربوط به این سری نیست بلکه به تمام سری‌های گروه سری والد نیز اعمال می‌شود - این یک بازتاب از ویژگی مناسب گروه است. بنابراین این ویژگی فقط خواندنی است. از ویژگی ParentSeriesGroup برای دسترسی به گروه سری والد استفاده کنید. برای تغییر مقدار از ویژگی ParentSeriesGroup.IsColorVaried قابل خواندن/نوشتن استفاده کنید. فقط خواندنی boolean.

--------------------

این بازتاب ویژگی ParentSeriesGroup.IsColorVaried است.

**باز می‌گردد:**  
boolean

### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public final int getBubbleSizeScale()
```

مقیاس فاکتور برای نمودار حباب مشخص می‌کند (می‌تواند بین ۰ تا ۳۰۰ درصد اندازه پیش‌فرض باشد). این ویژگی تنها مربوط به این سری نیست بلکه به تمام سری‌های گروه سری والد نیز اعمال می‌شود - این یک بازتاب از ویژگی مناسب گروه است. بنابراین این ویژگی فقط خواندنی است. از ویژگی ParentSeriesGroup برای دسترسی به گروه سری والد استفاده کنید. برای تغییر مقدار از ویژگی ParentSeriesGroup.BubbleSizeScale قابل خواندن/نوشتن استفاده کنید.

--------------------

این بازتاب ویژگی ParentSeriesGroup.BubbleSizeScale است.

**باز می‌گردد:**  
int

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

slide والد یک FillFormat را باز می‌گرداند. فقط خواندنی [BaseSlide](../../com.aspose.slides/baseslide).

**باز می‌گردد:**  
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

presentation والد یک FillFormat را باز می‌گرداند. فقط خواندنی [IPresentation](../../com.aspose.slides/ipresentation).

**باز می‌گردد:**  
[IPresentation](../../com.aspose.slides/ipresentation)