---
title: IChartSeries
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: نمایانگر یک سری نموداری.
type: docs
url: /fa/com.aspose.slides/ichartseries/
---
**همه‌ی واسط‌های پیاده‌سازی شده:**
[com.aspose.slides.IChartComponent](../../com.aspose.slides/ichartcomponent)
```
public interface IChartSeries extends IChartComponent
```

نمایانگر یک سری نموداری است.
## متدها

| متد | توضیح |
| --- | --- |
| [getExplosion()](#getExplosion--) | فاصله یک برش کیک باز از مرکز نمودار کیک به صورت درصدی از قطر کیک بیان می‌شود. |
| [setExplosion(int value)](#setExplosion-int-) | فاصله یک برش کیک باز از مرکز نمودار کیک به صورت درصدی از قطر کیک بیان می‌شود. |
| [getSmooth()](#getSmooth--) | نرم‌سازی منحنی را نشان می‌دهد. |
| [setSmooth(boolean value)](#setSmooth-boolean-) | نرم‌سازی منحنی را نشان می‌دهد. |
| [getMarker()](#getMarker--) | بازگرداندن نشانگر سری. |
| [getBar3DShape()](#getBar3DShape--) | شکل یک سری نمودار میله‌ای 3-بعدی را مشخص می‌کند. |
| [setBar3DShape(int value)](#setBar3DShape-int-) | شکل یک سری نمودار میله‌ای 3-بعدی را مشخص می‌کند. |
| [getName()](#getName--) | بازگرداندن نام سری. |
| [getDataPoints()](#getDataPoints--) | مجموعه‌ای از نقاط داده این سری را برمی‌گرداند. |
| [getType()](#getType--) | یک نوع از این سری را برمی‌گرداند. |
| [setType(int value)](#setType-int-) | یک نوع از این سری را برمی‌گرداند. |
| [getParentSeriesGroup()](#getParentSeriesGroup--) | گروه سری والد را برمی‌گرداند. |
| [getFormat()](#getFormat--) | قالب یک سری را برمی‌گرداند. |
| [getOrder()](#getOrder--) | ترتیب یک سری را برمی‌گرداند. |
| [setOrder(int value)](#setOrder-int-) | ترتیب یک سری را برمی‌گرداند. |
| [getLabels()](#getLabels--) | برچسب‌های یک سری را برمی‌گرداند. |
| [getTrendLines()](#getTrendLines--) | مجموعه خطوط روند سری (فقط‌خواندنی) [ITrendlineCollection](../../com.aspose.slides/itrendlinecollection). |
| [getErrorBarsXFormat()](#getErrorBarsXFormat--) | نوارهای خطای سری با جهت X را نشان می‌دهد. |
| [getErrorBarsYFormat()](#getErrorBarsYFormat--) | نوارهای خطای سری با جهت Y را نشان می‌دهد. |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | مشخص می‌کند آیا این سری بر روی محور دوم مقدار رسم می‌شود. |
| [setPlotOnSecondAxis(boolean value)](#setPlotOnSecondAxis-boolean-) | مشخص می‌کند آیا این سری بر روی محور دوم مقدار رسم می‌شود. |
| [getNumberFormatOfValues()](#getNumberFormatOfValues--) | قالب عددی مقادیر سری را برمی‌گرداند یا تنظیم می‌کند. |
| [setNumberFormatOfValues(String value)](#setNumberFormatOfValues-java.lang.String-) | قالب عددی مقادیر سری را برمی‌گرداند یا تنظیم می‌کند. |
| [getNumberFormatOfXValues()](#getNumberFormatOfXValues--) | قالب عددی مقادیر X سری را برمی‌گرداند یا تنظیم می‌کند. |
| [setNumberFormatOfXValues(String value)](#setNumberFormatOfXValues-java.lang.String-) | قالب عددی مقادیر X سری را برمی‌گرداند یا تنظیم می‌کند. |
| [getNumberFormatOfYValues()](#getNumberFormatOfYValues--) | قالب عددی مقادیر Y سری را برمی‌گرداند یا تنظیم می‌کند. |
| [setNumberFormatOfYValues(String value)](#setNumberFormatOfYValues-java.lang.String-) | قالب عددی مقادیر Y سری را برمی‌گرداند یا تنظیم می‌کند. |
| [getNumberFormatOfBubbleSizes()](#getNumberFormatOfBubbleSizes--) | قالب عددی اندازه حباب‌های سری را برمی‌گرداند یا تنظیم می‌کند. |
| [setNumberFormatOfBubbleSizes(String value)](#setNumberFormatOfBubbleSizes-java.lang.String-) | قالب عددی اندازه حباب‌های سری را برمی‌گرداند یا تنظیم می‌کند. |
| [getInvertIfNegative()](#getInvertIfNegative--) | مشخص می‌کند که سری میله، ستون یا حباب در صورت مقدار منفی رنگ‌هایش را معکوس کند. |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | مشخص می‌کند که سری میله، ستون یا حباب در صورت مقدار منفی رنگ‌هایش را معکوس کند. |
| [getInvertedSolidFillColor()](#getInvertedSolidFillColor--) | رنگ جامد معکوس را برای سری مشخص می‌کند. |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | ورودی راهنمای مرتبط با این سری را نشان می‌دهد (فقط‌خواندنی) [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties). |
| [getAutomaticSeriesColor()](#getAutomaticSeriesColor--) | رنگ خودکاری سری را بر اساس ایندکس سری و سبک نمودار برمی‌گرداند. |
| [getShowInnerPoints()](#getShowInnerPoints--) | نقاط داخلی را نشان می‌دهد. |
| [setShowInnerPoints(boolean value)](#setShowInnerPoints-boolean-) | نقاط داخلی را نشان می‌دهد. |
| [getShowOutlierPoints()](#getShowOutlierPoints--) | نقاط دورافتاده را نشان می‌دهد. |
| [setShowOutlierPoints(boolean value)](#setShowOutlierPoints-boolean-) | نقاط دورافتاده را نشان می‌دهد. |
| [getShowMeanMarkers()](#getShowMeanMarkers--) | نشانگرهای میانگین را نشان می‌دهد. |
| [setShowMeanMarkers(boolean value)](#setShowMeanMarkers-boolean-) | نشانگرهای میانگین را نشان می‌دهد. |
| [getShowMeanLine()](#getShowMeanLine--) | نشانگرهای میانگین را نشان می‌دهد. |
| [setShowMeanLine(boolean value)](#setShowMeanLine-boolean-) | نشانگرهای میانگین را نشان می‌دهد. |
| [getQuartileMethod()](#getQuartileMethod--) | روش چارک را نشان می‌دهد. |
| [setQuartileMethod(int value)](#setQuartileMethod-int-) | روش چارک را نشان می‌دهد. |
| [getShowConnectorLines()](#getShowConnectorLines--) | خطوط اتصال را نشان می‌دهد. |
| [setShowConnectorLines(boolean value)](#setShowConnectorLines-boolean-) | خطوط اتصال را نشان می‌دهد. |
| [getParentLabelLayout()](#getParentLabelLayout--) | چیدمان برچسب‌های دسته والد را نشان می‌دهد. |
| [setParentLabelLayout(int value)](#setParentLabelLayout-int-) | چیدمان برچسب‌های دسته والد را نشان می‌دهد. |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | عامل مقیاس برای نمودار حباب را مشخص می‌کند (می‌تواند بین 0 تا 300 درصد اندازه پیش‌فرض باشد). |
| [hasUpDownBars()](#hasUpDownBars--) | تعیین می‌کند آیا نمودار خطی یا سهام دارای میله‌های بالا/پایین است. |
| [getGapWidth()](#getGapWidth--) | فاصله بین خوشه‌های میله یا ستون را به‌صورت درصدی از عرض میله یا ستون مشخص می‌کند. |
| [getGapDepth()](#getGapDepth--) | فاصله بین سری‌های داده در یک نمودار 3-بعدی را به‌صورت درصدی از عرض نشانگر برمی‌گرداند یا تنظیم می‌کند. |
| [isColorVaried()](#isColorVaried--) | مشخص می‌کند که هر نشانگر داده در سری رنگ متفاوتی داشته باشد. |
| [hasSeriesLines()](#hasSeriesLines--) | تعیین می‌کند آیا خطوط سری برای این سری و سری‌های هم‌نوع وجود دارد یا نه. |
| [getOverlap()](#getOverlap--) | میزان همپوشانی میله‌ها و ستون‌ها در نمودارهای دو-بعدی را به‌صورت درصد (از -100٪ تا 100٪) مشخص می‌کند. |
| [getSecondPieSize()](#getSecondPieSize--) | اندازه دومین کیک یا میله در نمودار کیک-از-کیک یا میله-از-کیک را به‌صورت درصدی از اندازه کیک اول مشخص می‌کند (می‌تواند بین 5 تا 200 درصد باشد). |
| [getPieSplitPosition()](#getPieSplitPosition--) | مقداری را مشخص می‌کند که برای تعیین نقاط داده‌ای که در کیک یا میله دوم در نمودار کیک-از-کیک یا میله-از-کیک قرار می‌گیرند، استفاده می‌شود. |
| [getPieSplitBy()](#getPieSplitBy--) | نحوه تعیین نقاط داده‌ای که در کیک یا میله دوم نمودار کیک-از-کیک یا میله-از-کیک قرار می‌گیرند را مشخص می‌کند. |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | اندازهٔ حفره در نمودار دونات را مشخص می‌کند (می‌تواند بین 10 تا 90 درصد از اندازهٔ ناحیهٔ ترسیم باشد). |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | زاویهٔ اولین برش کیک یا دونات را به‌درجهٔ سنج (ساعتگرد از بالا، از 0 تا 360 درجه) مشخص می‌کند. |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | اطلاعات تقسیم سفارشی برای نمودار کیک-از-کیک یا میله-از-کیک با تقسیم سفارشی. |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | نحوهٔ نمایش مقادیر اندازه حباب در نمودار حباب را مشخص می‌کند. |

### getExplosion() {#getExplosion--}
```
public abstract int getExplosion()
```

فاصله یک برش کیک باز از مرکز نمودار کیک به صورت درصدی از قطر کیک بیان می‌شود. قابل خواندن/نوشتن int.

**بازگشت:**
int

### setExplosion(int value) {#setExplosion-int-}
```
public abstract void setExplosion(int value)
```

فاصله یک برش کیک باز از مرکز نمودار کیک به صورت درصدی از قطر کیک بیان می‌شود. قابل خواندن/نوشتن int.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getSmooth() {#getSmooth--}
```
public abstract boolean getSmooth()
```

نرم‌سازی منحنی را نشان می‌دهد. اگر نرم‌سازی منحنی برای نمودار خطی یا پراکندگی فعال باشد، true برمی‌گردد. فقط برای نمودارهای خطی و پراکندگی متصل به خطوط کاربرد دارد. قابل خواندن/نوشتن boolean.

**بازگشت:**
boolean

### setSmooth(boolean value) {#setSmooth-boolean-}
```
public abstract void setSmooth(boolean value)
```

نرم‌سازی منحنی را نشان می‌دهد. اگر نرم‌سازی منحنی برای نمودار خطی یا پراکندگی فعال باشد، true برمی‌گردد. فقط برای نمودارهای خطی و پراکندگی متصل به خطوط کاربرد دارد. قابل خواندن/نوشتن boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getMarker() {#getMarker--}
```
public abstract IMarker getMarker()
```

بازگرداندن نشانگر سری. فقط‌خواندنی [IMarker](../../com.aspose.slides/imarker).

**بازگشت:**
[IMarker](../../com.aspose.slides/imarker)

### getBar3DShape() {#getBar3DShape--}
```
public abstract int getBar3DShape()
```

شکل یک سری نمودار میله‌ای 3-بعدی را مشخص می‌کند. تغییر مقدار این ویژگی می‌تواند به‌صورت خودکار نوع سری را تغییر دهد. قابل خواندن/نوشتن [ChartShapeType](../../com.aspose.slides/chartshapetype).

**بازگشت:**
int

### setBar3DShape(int value) {#setBar3DShape-int-}
```
public abstract void setBar3DShape(int value)
```

شکل یک سری نمودار میله‌ای 3-بعدی را مشخص می‌کند. تغییر مقدار این ویژگی می‌تواند به‌صورت خودکار نوع سری را تغییر دهد. قابل خواندن/نوشتن [ChartShapeType](../../com.aspose.slides/chartshapetype).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getName() {#getName--}
```
public abstract IStringChartValue getName()
```

بازگرداندن نام سری. فقط‌خواندنی [IStringChartValue](../../com.aspose.slides/istringchartvalue).

**بازگشت:**
[IStringChartValue](../../com.aspose.slides/istringchartvalue)

### getDataPoints() {#getDataPoints--}
```
public abstract IChartDataPointCollection getDataPoints()
```

مجموعه‌ای از نقاط داده این سری را برمی‌گرداند. فقط‌خواندنی [IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection).

**بازگشت:**
[IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection)

### getType() {#getType--}
```
public abstract int getType()
```

یک نوع از این سری را برمی‌گرداند. قابل خواندن/نوشتن [ChartType](../../com.aspose.slides/charttype).

**بازگشت:**
int

### setType(int value) {#setType-int-}
```
public abstract void setType(int value)
```

یک نوع از این سری را برمی‌گرداند. قابل خواندن/نوشتن [ChartType](../../com.aspose.slides/charttype).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getParentSeriesGroup() {#getParentSeriesGroup--}
```
public abstract IChartSeriesGroup getParentSeriesGroup()
```

گروه سری والد را برمی‌گرداند. فقط‌خواندنی [IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup).

**بازگشت:**
[IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup)

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

قالب یک سری را برمی‌گرداند. فقط‌خواندنی [IFormat](../../com.aspose.slides/iformat).

**بازگشت:**
[IFormat](../../com.aspose.slides/iformat)

### getOrder() {#getOrder--}
```
public abstract int getOrder()
```

ترتیب یک سری را برمی‌گرداند. قابل خواندن/نوشتن int.

**بازگشت:**
int

### setOrder(int value) {#setOrder-int-}
```
public abstract void setOrder(int value)
```

ترتیب یک سری را برمی‌گرداند. قابل خواندن/نوشتن int.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getLabels() {#getLabels--}
```
public abstract IDataLabelCollection getLabels()
```

برچسب‌های یک سری را برمی‌گرداند. فقط‌خواندنی [IDataLabelCollection](../../com.aspose.slides/idatalabelcollection).

**بازگشت:**
[IDataLabelCollection](../../com.aspose.slides/idatalabelcollection)

### getTrendLines() {#getTrendLines--}
```
public abstract ITrendlineCollection getTrendLines()
```

مجموعه خطوط روند سری (فقط‌خواندنی) [ITrendlineCollection](../../com.aspose.slides/itrendlinecollection).

**بازگشت:**
[ITrendlineCollection](../../com.aspose.slides/itrendlinecollection)

### getErrorBarsXFormat() {#getErrorBarsXFormat--}
```
public abstract IErrorBarsFormat getErrorBarsXFormat()
```

نوارهای خطای سری با جهت X را نشان می‌دهد. فقط‌خواندنی [IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat).

--------------------

نوارهای خطای جهت X برای سری‌های نوع area، bar، scatter و bubble قابل استفاده هستند. برای سایر انواع نمودار این ویژگی مقدار null برمی‌گرداند (شامل نمودارهای 3D). برای مقادیر سفارشی از مجموعه DataPoints استفاده کنید (با ویژگی ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues))).

**بازگشت:**
[IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)

### getErrorBarsYFormat() {#getErrorBarsYFormat--}
```
public abstract IErrorBarsFormat getErrorBarsYFormat()
```

نوارهای خطای سری با جهت Y را نشان می‌دهد. فقط‌خواندنی [IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat).

--------------------

نوارهای خطای جهت Y برای سری‌های نوع area، bar، line، scatter و bubble قابل استفاده هستند. برای سایر انواع نمودار این ویژگی مقدار null برمی‌گرداند (شامل نمودارهای 3D). برای مقادیر سفارشی از مجموعه DataPoints استفاده کنید (با ویژگی ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues))).

**بازگشت:**
[IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)

### getPlotOnSecondAxis() {#getPlotOnSecondAxis--}
```
public abstract boolean getPlotOnSecondAxis()
```

مشخص می‌کند آیا این سری بر روی محور دوم مقدار رسم می‌شود. قابل خواندن/نوشتن boolean.

**بازگشت:**
boolean

### setPlotOnSecondAxis(boolean value) {#setPlotOnSecondAxis-boolean-}
```
public abstract void setPlotOnSecondAxis(boolean value)
```

مشخص می‌کند آیا این سری بر روی محور دوم مقدار رسم می‌شود. قابل خواندن/نوشتن boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getNumberFormatOfValues() {#getNumberFormatOfValues--}
```
public abstract String getNumberFormatOfValues()
```

قالب عددی مقادیر سری را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن String.

**بازگشت:**
java.lang.String

### setNumberFormatOfValues(String value) {#setNumberFormatOfValues-java.lang.String-}
```
public abstract void setNumberFormatOfValues(String value)
```

قالب عددی مقادیر سری را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن String.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |

### getNumberFormatOfXValues() {#getNumberFormatOfXValues--}
```
public abstract String getNumberFormatOfXValues()
```

قالب عددی مقادیر X سری را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن String.

**بازگشت:**
java.lang.String

### setNumberFormatOfXValues(String value) {#setNumberFormatOfXValues-java.lang.String-}
```
public abstract void setNumberFormatOfXValues(String value)
```

قالب عددی مقادیر X سری را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن String.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |

### getNumberFormatOfYValues() {#getNumberFormatOfYValues--}
```
public abstract String getNumberFormatOfYValues()
```

قالب عددی مقادیر Y سری را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن String.

**بازگشت:**
java.lang.String

### setNumberFormatOfYValues(String value) {#setNumberFormatOfYValues-java.lang.String-}
```
public abstract void setNumberFormatOfYValues(String value)
```

قالب عددی مقادیر Y سری را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن String.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |

### getNumberFormatOfBubbleSizes() {#getNumberFormatOfBubbleSizes--}
```
public abstract String getNumberFormatOfBubbleSizes()
```

قالب عددی اندازه حباب‌های سری را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن String.

**بازگشت:**
java.lang.String

### setNumberFormatOfBubbleSizes(String value) {#setNumberFormatOfBubbleSizes-java.lang.String-}
```
public abstract void setNumberFormatOfBubbleSizes(String value)
```

قالب عددی اندازه حباب‌های سری را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن String.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |

### getInvertIfNegative() {#getInvertIfNegative--}
```
public abstract boolean getInvertIfNegative()
```

مشخص می‌کند که سری میله، ستون یا حباب در صورت مقدار منفی رنگ‌هایش را معکوس کند. قابل خواندن/نوشتن boolean.

**بازگشت:**
boolean

### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public abstract void setInvertIfNegative(boolean value)
```

مشخص می‌کند که سری میله، ستون یا حباب در صورت مقدار منفی رنگ‌هایش را معکوس کند. قابل خواندن/نوشتن boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getInvertedSolidFillColor() {#getInvertedSolidFillColor--}
```
public abstract IColorFormat getInvertedSolidFillColor()
```

رنگ جامد معکوس را برای سری مشخص می‌کند. برای اعمال تنظیم رنگ، نوع پر کردن سری را به FillType.Solid تنظیم کنید. قابل خواندن/نوشتن [IColorFormat](../../com.aspose.slides/icolorformat).

**بازگشت:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public abstract ILegendEntryProperties getRelatedLegendEntry()
```

ورودی راهنمای مرتبط با این سری را نشان می‌دهد (فقط‌خواندنی) [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**بازگشت:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)

### getAutomaticSeriesColor() {#getAutomaticSeriesColor--}
```
public abstract Integer getAutomaticSeriesColor()
```

رنگ خودکاری سری را بر اساس ایندکس سری و سبک نمودار برمی‌گرداند. این رنگ به‌عنوان پیش‌فرض استفاده می‌شود اگر FillType برابر NotDefined باشد.

**بازگشت:**
java.lang.Integer - Automatic color of series java.lang.Integer

### getShowInnerPoints() {#getShowInnerPoints--}
```
public abstract boolean getShowInnerPoints()
```

نقاط داخلی را نشان می‌دهد. اگر نقاط داخلی در نمودار BoxAndWhisker نمایش داده شوند، true برمی‌گردد. فقط برای نمودارهای BoxAndWhisker کاربرد دارد. قابل خواندن/نوشتن boolean.

**بازگشت:**
boolean

### setShowInnerPoints(boolean value) {#setShowInnerPoints-boolean-}
```
public abstract void setShowInnerPoints(boolean value)
```

نقاط داخلی را نشان می‌دهد. اگر نقاط داخلی در نمودار BoxAndWhisker نمایش داده شوند، true برمی‌گردد. فقط برای نمودارهای BoxAndWhisker کاربرد دارد. قابل خواندن/نوشتن boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getShowOutlierPoints() {#getShowOutlierPoints--}
```
public abstract boolean getShowOutlierPoints()
```

نقاط دورافتاده را نشان می‌دهد. اگر نقاط دورافتاده در نمودار BoxAndWhisker نمایش داده شوند، true برمی‌گردد. فقط برای نمودارهای BoxAndWhisker کاربرد دارد. قابل خواندن/نوشتن boolean.

**بازگشت:**
boolean

### setShowOutlierPoints(boolean value) {#setShowOutlierPoints-boolean-}
```
public abstract void setShowOutlierPoints(boolean value)
```

نقاط دورافتاده را نشان می‌دهد. اگر نقاط دورافتاده در نمودار BoxAndWhisker نمایش داده شوند، true برمی‌گردد. فقط برای نمودارهای BoxAndWhisker کاربرد دارد. قابل خواندن/نوشتن boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getShowMeanMarkers() {#getShowMeanMarkers--}
```
public abstract boolean getShowMeanMarkers()
```

نشانگرهای میانگین را نشان می‌دهد. اگر نشانگرهای میانگین در نمودار BoxAndWhisker نمایش داده شوند، true برمی‌گردد. فقط برای نمودارهای BoxAndWhisker کاربرد دارد. قابل خواندن/نوشتن boolean.

**بازگشت:**
boolean

### setShowMeanMarkers(boolean value) {#setShowMeanMarkers-boolean-}
```
public abstract void setShowMeanMarkers(boolean value)
```

نشانگرهای میانگین را نشان می‌دهد. اگر نشانگرهای میانگین در نمودار BoxAndWhisker نمایش داده شوند، true برمی‌گردد. فقط برای نمودارهای BoxAndWhisker کاربرد دارد. قابل خواندن/نوشتن boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getShowMeanLine() {#getShowMeanLine--}
```
public abstract boolean getShowMeanLine()
```

نشانگرهای میانگین را نشان می‌دهد. اگر خط میانگین در نمودار BoxAndWhisker نمایش داده شود، true برمی‌گردد. فقط برای نمودارهای BoxAndWhisker کاربرد دارد. قابل خواندن/نوشتن boolean.

**بازگشت:**
boolean

### setShowMeanLine(boolean value) {#setShowMeanLine-boolean-}
```
public abstract void setShowMeanLine(boolean value)
```

نشانگرهای میانگین را نشان می‌دهد. اگر خط میانگین در نمودار BoxAndWhisker نمایش داده شود، true برمی‌گردد. فقط برای نمودارهای BoxAndWhisker کاربرد دارد. قابل خواندن/نوشتن boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getQuartileMethod() {#getQuartileMethod--}
```
public abstract int getQuartileMethod()
```

روش چارک را نشان می‌دهد. فقط برای نمودارهای BoxAndWhisker کاربرد دارد.

**بازگشت:**
int

### setQuartileMethod(int value) {#setQuartileMethod-int-}
```
public abstract void setQuartileMethod(int value)
```

روش چارک را نشان می‌دهد. فقط برای نمودارهای BoxAndWhisker کاربرد دارد.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getShowConnectorLines() {#getShowConnectorLines--}
```
public abstract boolean getShowConnectorLines()
```

خطوط اتصال را نشان می‌دهد. فقط برای نمودارهای Waterfall کاربرد دارد.

**بازگشت:**
boolean

### setShowConnectorLines(boolean value) {#setShowConnectorLines-boolean-}
```
public abstract void setShowConnectorLines(boolean value)
```

خطوط اتصال را نشان می‌دهد. فقط برای نمودارهای Waterfall کاربرد دارد.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getParentLabelLayout() {#getParentLabelLayout--}
```
public abstract int getParentLabelLayout()
```

چیدمان برچسب‌های دسته والد را نشان می‌دهد. فقط برای نمودارهای Treemap کاربرد دارد.

**بازگشت:**
int

### setParentLabelLayout(int value) {#setParentLabelLayout-int-}
```
public abstract void setParentLabelLayout(int value)
```

چیدمان برچسب‌های دسته والد را نشان می‌دهد. فقط برای نمودارهای Treemap کاربرد دارد.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public abstract int getBubbleSizeScale()
```

عامل مقیاس برای نمودار حباب را مشخص می‌کند (می‌تواند بین 0 تا 300 درصد اندازه پیش‌فرض باشد). این ویژگی نه تنها برای این سری بلکه برای تمام سری‌های گروه سری والد است – این یک انتشار ویژگی مربوط به گروه است. بنابراین این ویژگی فقط‌خواندنی است. برای دسترسی به گروه سری والد از ویژگی ParentSeriesGroup استفاده کنید. برای تغییر مقدار از ویژگی ParentSeriesGroup.BubbleSizeScale قابل خواندن/نوشتن استفاده کنید.

--------------------

این انتشار ویژگی ParentSeriesGroup.BubbleSizeScale است.

**بازگشت:**
int

### hasUpDownBars() {#hasUpDownBars--}
```
public abstract boolean hasUpDownBars()
```

تعیین می‌کند آیا نمودار خطی یا سهام دارای میله‌های بالا/پایین است. این ویژگی نه تنها برای این سری بلکه برای تمام سری‌های گروه سری والد است – این یک انتشار ویژگی مربوط به گروه است. بنابراین این ویژگی فقط‌خواندنی است. برای دسترسی به گروه سری والد از ویژگی ParentSeriesGroup استفاده کنید. برای تغییر مقدار از ویژگی ParentSeriesGroup.UpDownBars.HasUpDownBars قابل خواندن/نوشتن استفاده کنید. برای قالب‌بندی میله‌های بالا/پایین از ویژگی ParentSeriesGroup.UpDownBars استفاده کنید. فقط‌خواندنی boolean.

--------------------

این انتشار ویژگی ParentSeriesGroup.UpDownBars.HasUpDownBars است.

**بازگشت:**
boolean

### getGapWidth() {#getGapWidth--}
```
public  int      // در این خط نظریه فارسی به‌نظر
```

فاصله بین خوشه‌های میله یا ستون را به‌صورت درصدی از عرض میله یا ستون مشخص می‌کند. این ویژگی نه تنها برای این سری بلکه برای تمام سری‌های گروه سری والد است – این یک انتشار ویژگی مربوط به گروه است. بنابراین این ویژگی فقط‌خواندنی است. برای دسترسی به گروه سری والد از ویژگی ParentSeriesGroup استفاده کنید. برای تغییر مقدار از ویژگی ParentSeriesGroup.GapWidth قابل خواندن/نوشتن استفاده کنید. فقط‌خواندنی int.

--------------------

این انتشار ویژگی ParentSeriesGroup.GapWidth است.

**بازگشت:**
int

### getGapDepth() {#getGapDepth--}
```
public abstract int getGapDepth()
```

فاصله بین سری‌های داده در یک نمودار 3-بعدی را به‌صورت درصدی از عرض نشانگر برمی‌گرداند یا تنظیم می‌کند. این ویژگی نه تنها برای این سری بلکه برای تمام سری‌های گروه سری والد است – این یک انتشار ویژگی مربوط به گروه است. بنابراین این ویژگی فقط‌خواندنی است. برای دسترسی به گروه سری والد از ویژگی ParentSeriesGroup استفاده کنید. برای تغییر مقدار از ویژگی ParentSeriesGroup.GapDepth قابل خواندن/نوشتن استفاده کنید. فقط‌خواندنی int.

--------------------

این انتشار ویژگی ParentSeriesGroup.GapDepth است.

**بازگشت:**
int

### isColorVaried() {#isColorVaried--}
```
public abstract boolean isColorVaried()
```

مشخص می‌کند که هر نشانگر داده در سری رنگ متفاوتی داشته باشد. این ویژگی نه تنها برای این سری بلکه برای تمام سری‌های گروه سری والد است – این یک انتشار ویژگی مربوط به گروه است. بنابراین این ویژگی فقط‌خواندنی است. برای دسترسی به گروه سری والد از ویژگی ParentSeriesGroup استفاده کنید. برای تغییر مقدار از ویژگی ParentSeriesGroup.IsColorVaried قابل خواندن/نوشتن استفاده کنید. فقط‌خواندنی boolean.

--------------------

این انتشار ویژگی ParentSeriesGroup.IsColorVaried است.

**بازگشت:**
boolean

### hasSeriesLines() {#hasSeriesLines--}
```
public abstract boolean hasSeriesLines()
```

تعیین می‌کند آیا خطوط سری برای این سری و سری‌های هم‌نوع وجود دارد یا نه. این ویژگی نه تنها برای این سری بلکه برای تمام سری‌های گروه سری والد است – این یک انتشار ویژگی مربوط به گروه است. بنابراین این ویژگی فقط‌خواندنی است. برای دسترسی به گروه سری والد از ویژگی ParentSeriesGroup استفاده کنید. برای تغییر مقدار از ویژگی ParentSeriesGroup.HasSeriesLines قابل خواندن/نوشتن استفاده کنید. برای قالب‌بندی خطوط سری از ویژگی ParentSeriesGroup.SeriesLinesFormat استفاده کنید. فقط‌خواندنی boolean.

--------------------

این انتشار ویژگی ParentSeriesGroup.HasSeriesLines است.

**بازگشت:**
boolean

### getOverlap() {#getOverlap--}
```
public abstract byte getOverlap()
```

میزان همپوشانی میله‌ها و ستون‌ها در نمودارهای دو-بعدی را به‌صورت درصد (از -100٪ تا 100٪) مشخص می‌کند. این ویژگی نه تنها برای این سری بلکه برای تمام سری‌های گروه سری والد است. این یک انتشار ویژگی مربوط به گروه است و بنابراین فقط‌خواندنی است. برای تغییر مقدار از ویژگی ParentSeriesGroup.Overlap قابل خواندن/نوشتن استفاده کنید. فقط‌خواندنی byte.

--------------------

Overlap میزان همپوشانی یا فاصله بین میله‌ها و ستون‌ها را به‌صورت درصد بیان می‌کند: -100٪ حداکثر فاصله (میله‌ها کاملاً جدا هستند). 0٪ میله‌ها بدون همپوشانی یا فاصله کنار هم قرار می‌گیرند. 100٪ حداکثر همپوشانی (میله‌ها کاملاً روی یکدیگر می‌نشینند). این یک انتشار ویژگی ParentSeriesGroup.Overlap است.

**بازگشت:**
byte

### getSecondPieSize() {#getSecondPieSize--}
```
public abstract int getSecondPieSize()
```

اندازه دومین کیک یا میله در نمودار کیک-از-کیک یا میله-از-کیک را به‌صورت درصدی از اندازه کیک اول مشخص می‌کند (می‌تواند بین 5 تا 200 درصد باشد). این ویژگی نه تنها برای این سری بلکه برای تمام سری‌های گروه سری والد است – این یک انتشار ویژگی مربوط به گروه است. بنابراین این ویژگی فقط‌خواندنی است. برای دسترسی به گروه سری والد از ویژگی ParentSeriesGroup استفاده کنید. برای تغییر مقدار از ویژگی ParentSeriesGroup.SecondPieSize قابل خواندن/نوشتن استفاده کنید. فقط‌خواندنی int.

--------------------

این انتشار ویژگی ParentSeriesGroup.SecondPieSize است.

**بازگشت:**
int

### getPieSplitPosition() {#getPieSplitPosition--}
```
public abstract double getPieSplitPosition()
```

مقداری را مشخص می‌کند که برای تعیین نقاط داده‌ای که در کیک یا میله دوم در نمودار کیک-از-کیک یا میله-از-کیک قرار می‌گیرند، استفاده می‌شود. همراه با ویژگی PieSplitBy استفاده می‌شود. این ویژگی نه تنها برای این سری بلکه برای تمام سری‌های گروه سری والد است – این یک انتشار ویژگی مربوط به گروه است. بنابراین این ویژگی فقط‌خواندنی است. برای دسترسی به گروه سری والد از ویژگی ParentSeriesGroup استفاده کنید. برای تغییر مقدار از ویژگی ParentSeriesGroup.PieSplitPosition قابل خواندن/نوشتن استفاده کنید. فقط‌خواندنی double.

--------------------

این انتشار ویژگی ParentSeriesGroup.PieSplitPosition است.

**بازگشت:**
double

### getPieSplitBy() {#getPieSplitBy--}
```
public abstract int getPieSplitBy()
```

نحوه تعیین نقاط داده‌ای که در کیک یا میله دوم در نمودار کیک-از-کیک یا میله-از-کیک قرار می‌گیرند را مشخص می‌کند. این ویژگی نه تنها برای این سری بلکه برای تمام سری‌های گروه سری والد است – این یک انتشار ویژگی مربوط به گروه است. بنابراین این ویژگی فقط‌خواندنی است. برای دسترسی به گروه سری والد از ویژگی ParentSeriesGroup استفاده کنید. برای تغییر مقدار از ویژگی ParentSeriesGroup.PieSplitBy قابل خواندن/نوشتن استفاده کنید. فقط‌خواندنی [PieSplitType](../../com.aspose.slides/piesplittype).

--------------------

1) این انتشار ویژگی ParentSeriesGroup.PieSplitBy است. 2) اگر مقدار ویژگی PieSplitType.Custom باشد می‌توانید اطلاعات تقسیم سفارشی را با ویژگی ParentSeriesGroup.PieSplitCustomPoints تعریف کنید.

**بازگشت:**
int

### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public abstract byte getDoughnutHoleSize()
```

اندازهٔ حفره در نمودار دونات را مشخص می‌کند (می‌تواند بین 10 تا 90 درصد از اندازهٔ ناحیهٔ ترسیم باشد). این ویژگی نه تنها برای این سری بلکه برای تمام سری‌های گروه سری والد است – این یک انتشار ویژگی مربوط به گروه است. بنابراین این ویژگی فقط‌خواندنی است. برای دسترسی به گروه سری والد از ویژگی ParentSeriesGroup استفاده کنید. برای تغییر مقدار از ویژگی ParentSeriesGroup.DoughnutHoleSize قابل خواندن/نوشتن استفاده کنید. فقط‌خواندنی byte.

--------------------

این انتشار ویژگی ParentSeriesGroup.DoughnutHoleSize است.

**بازگشت:**
byte

### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public abstract int getFirstSliceAngle()
```

زاویهٔ اولین برش کیک یا دونات را به‌درجهٔ سنج (ساعتگرد از بالا، از 0 تا 360 درجه) مشخص می‌کند. این ویژگی نه تنها برای این سری بلکه برای تمام سری‌های گروه سری والد است – این یک انتشار ویژگی مربوط به گروه است. بنابراین این ویژگی فقط‌خواندنی است. برای دسترسی به گروه سری والد از ویژگی ParentSeriesGroup استفاده کنید. برای تغییر مقدار از ویژگی ParentSeriesGroup.FirstSliceAngle قابل خواندن/نوشتن استفاده کنید. فقط‌خواندنی int.

--------------------

این انتشار ویژگی ParentSeriesGroup.FirstSliceAngle است.

**بازگشت:**
int

### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public abstract IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

اطلاعات تقسیم سفارشی برای نمودار کیک-از-کیک یا میله-از-کیک با تقسیم سفارشی. شامل نقاط داده‌ای است که باید در کیک یا میله دوم کشیده شوند. این ویژگی نه تنها برای این سری بلکه برای تمام سری‌های گروه سری والد است – این یک انتشار ویژگی مربوط به گروه است. فقط‌خواندنی [IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection).

--------------------

این انتشار ویژگی ParentSeriesGroup.PieSplitCustomPoints است.

**بازگشت:**
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)

### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public abstract int getBubbleSizeRepresentation()
```

نحوهٔ نمایش مقادیر اندازه حباب در نمودار حباب را مشخص می‌کند. این ویژگی نه تنها برای این سری بلکه برای تمام سری‌های گروه سری والد است – این یک انتشار ویژگی مربوط به گروه است. بنابراین این ویژگی فقط‌خواندنی است. برای دسترسی به گروه سری والد از ویژگی ParentSeriesGroup استفاده کنید. برای تغییر مقدار از ویژگی ParentSeriesGroup.BubbleSizeRepresentation قابل خواندن/نوشتن استفاده کنید.

--------------------

این انتشار ویژگی ParentSeriesGroup.BubbleSizeRepresentation است.

**بازگشت:**
int