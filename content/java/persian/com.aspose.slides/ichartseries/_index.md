---
title: IChartSeries
second_title: مرجع API Aspose.Slides برای Java
description: نمایانگر یک سری نمودار.
type: docs
url: /fa/com.aspose.slides/ichartseries/
---
**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IChartComponent](../../com.aspose.slides/ichartcomponent)
```
public interface IChartSeries extends IChartComponent
```

نمایانگر یک سری نمودار.
## متدها

| Method | Description |
| --- | --- |
| [getExplosion()](#getExplosion--) | فاصله یک برش پیت باز از مرکز نمودار دایره‌ای به‌عنوان درصدی از قطر دایره بیان می‌شود. |
| [setExplosion(int value)](#setExplosion-int-) | فاصله یک برش پیت باز از مرکز نمودار دایره‌ای به‌عنوان درصدی از قطر دایره بیان می‌شود. |
| [getSmooth()](#getSmooth--) | نمایانگر صاف‌سازی منحنی. |
| [setSmooth(boolean value)](#setSmooth-boolean-) | نمایانگر صاف‌سازی منحنی. |
| [getMarker()](#getMarker--) | بازگرداندن نشانگر سری. |
| [getBar3DShape()](#getBar3DShape--) | مشخص می‌کند شکل یک سری از نمودار میله‌ای سه‌بعدی چیست. |
| [setBar3DShape(int value)](#setBar3DShape-int-) | مشخص می‌کند شکل یک سری از نمودار میله‌ای سه‌بعاد چیست. |
| [getName()](#getName--) | بازگرداندن نام سری. |
| [getDataPoints()](#getDataPoints--) | مجموعه‌ای از نقاط داده این سری را برمی‌گرداند. |
| [getType()](#getType--) | نوعی از این سری را برمی‌گرداند. |
| [setType(int value)](#setType-int-) | نوعی از این سری را برمی‌گرداند. |
| [getParentSeriesGroup()](#getParentSeriesGroup--) | گروه پدر سری را برمی‌گرداند. |
| [getFormat()](#getFormat--) | قالب یک سری را برمی‌گرداند. |
| [getOrder()](#getOrder--) | ترتیب یک سری را برمی‌گرداند. |
| [setOrder(int value)](#setOrder-int-) | ترتیب یک سری را برمی‌گرداند. |
| [getLabels()](#getLabels--) | برچسب‌های یک سری را برمی‌گرداند. |
| [getTrendLines()](#getTrendLines--) | مجموعه‌ای از خطوط روند سری. فقط‌خواندنی [ITrendlineCollection](../../com.aspose.slides/itrendlinecollection). |
| [getErrorBarsXFormat()](#getErrorBarsXFormat--) | نمایش نوارهای خطا برای سری با جهت X. |
| [getErrorBarsYFormat()](#getErrorBarsYFormat--) | نمایش نوارهای خطا برای سری با جهت Y. |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | نشان می‌دهد آیا این سری روی محور مقدار دوم ترسیم می‌شود. |
| [setPlotOnSecondAxis(boolean value)](#setPlotOnSecondAxis-boolean-) | نشان می‌دهد آیا این سری روی محور مقدار دوم ترسیم می‌شود. |
| [getNumberFormatOfValues()](#getNumberFormatOfValues--) | قالب عددی مقادیر سری را برمی‌گرداند یا تنظیم می‌کند. |
| [setNumberFormatOfValues(String value)](#setNumberFormatOfValues-java.lang.String-) | قالب عددی مقادیر سری را برمی‌گرداند یا تنظیم می‌کند. |
| [getNumberFormatOfXValues()](#getNumberFormatOfXValues--) | قالب عددی مقادیر x سری را برمی‌گرداند یا تنظیم می‌کند. |
| [setNumberFormatOfXValues(String value)](#setNumberFormatOfXValues-java.lang.String-) | قالب عددی مقادیر x سری را برمی‌گرداند یا تنظیم می‌کند. |
| [getNumberFormatOfYValues()](#getNumberFormatOfYValues--) | قالب عددی مقادیر y سری را برمی‌گرداند یا تنظیم می‌کند. |
| [setNumberFormatOfYValues(String value)](#setNumberFormatOfYValues-java.lang.String-) | قالب عددی مقادیر y سری را برمی‌گرداند یا تنظیم می‌کند. |
| [getNumberFormatOfBubbleSizes()](#getNumberFormatOfBubbleSizes--) | قالب عددی اندازه حباب‌های سری را برمی‌گرداند یا تنظیم می‌کند. |
| [setNumberFormatOfBubbleSizes(String value)](#setNumberFormatOfBubbleSizes-java.lang.String-) | قالب عددی اندازه حباب‌های سری را برمی‌گرداند یا تنظیم می‌کند. |
| [getInvertIfNegative()](#getInvertIfNegative--) | مشخص می‌کند که اگر مقدار منفی باشد، سری میله، ستون یا حباب رنگ‌های خود را معکوس کند. |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | مشخص می‌کند که اگر مقدار منفی باشد، سری میله، ستون یا حباب رنگ‌های خود را معکوس کند. |
| [getInvertedSolidFillColor()](#getInvertedSolidFillColor--) | رنگ جامد معکوس را برای سری مشخص می‌کند. |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | نمایانگر ورودی افقنام مرتبط با این سری. فقط‌خواندنی [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties). |
| [getAutomaticSeriesColor()](#getAutomaticSeriesColor--) | یک رنگ خودکار برای سری بر اساس اندیس سری و سبک نمودار برمی‌گرداند. |
| [getShowInnerPoints()](#getShowInnerPoints--) | نمایانگر نقاط درونی. |
| [setShowInnerPoints(boolean value)](#setShowInnerPoints-boolean-) | نمایانگر نقاط درونی. |
| [getShowOutlierPoints()](#getShowOutlierPoints--) | نمایانگر نقاط دورافتاده. |
| [setShowOutlierPoints(boolean value)](#setShowOutlierPoints-boolean-) | نمایانگر نقاط دورافتاده. |
| [getShowMeanMarkers()](#getShowMeanMarkers--) | نمایانگر نقاط میانگین. |
| [setShowMeanMarkers(boolean value)](#setShowMeanMarkers-boolean-) | نمایانگر نقاط میانگین. |
| [getShowMeanLine()](#getShowMeanLine--) | نمایانگر نقاط میانگین. |
| [setShowMeanLine(boolean value)](#setShowMeanLine-boolean-) | نمایانگر نقاط میانگین. |
| [getQuartileMethod()](#getQuartileMethod--) | نمایانگر روش چهارک. |
| [setQuartileMethod(int value)](#setQuartileMethod-int-) | نمایانگر روش چهارک. |
| [getShowConnectorLines()](#getShowConnectorLines--) | نمایانگر خطوط اتصال. |
| [setShowConnectorLines(boolean value)](#setShowConnectorLines-boolean-) | نمایانگر خطوط اتصال. |
| [getParentLabelLayout()](#getParentLabelLayout--) | نمایانگر چیدمان برچسب‌های دسته‌بندی والد. |
| [setParentLabelLayout(int value)](#setParentLabelLayout-int-) | نمایانگر چیدمان برچسب‌های دسته‌بندی والد. |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | عامل مقیاس برای نمودار حباب را مشخص می‌کند (می‌تواند بین ۰ تا ۳۰۰ درصد اندازه پیش‌فرض باشد). |
| [hasUpDownBars()](#hasUpDownBars--) | مشخص می‌کند آیا نمودار خطی یا سهام دارای میله‌های بالا/پایین است. |
| [getGapWidth()](#getGapWidth--) | فضای بین خوشه‌های میله یا ستون را به‌عنوان درصدی از عرض میله یا ستون مشخص می‌کند. |
| [getGapDepth()](#getGapDepth--) | فاصله بین سری‌های داده در نمودار سه‌بعدی را به‌عنوان درصدی از عرض نشانگر برمی‌گرداند یا تنظیم می‌کند. |
| [isColorVaried()](#isColorVaried--) | مشخص می‌کند که هر نشانگر داده در سری رنگ متفاوتی دارد. |
| [hasSeriesLines()](#hasSeriesLines--) | مشخص می‌کند آیا خطوط سری برای این سری و سری‌های مشابه وجود دارد. |
| [getOverlap()](#getOverlap--) | مشخص می‌کند میزان همپوشانی میله‌ها و ستون‌ها در نمودارهای دو‌بعدی را به‌عنوان درصد (از -۱۰۰٪ تا ۱۰۰٪) تنظیم می‌کند. |
| [getSecondPieSize()](#getSecondPieSize--) | اندازه دومین دایره یا میله در نمودار دایره-در-دایره یا میله-در-دایره را به‌عنوان درصدی از اندازه دایره اول مشخص می‌کند (می‌تواند بین ۵ تا ۲۰۰ درصد باشد). |
| [getPieSplitPosition()](#getPieSplitPosition--) | مقداری را که برای تعیین نقاط داده در دومین دایره یا میله در نمودار دایره-در-دایره یا میله-در-دایره استفاده می‌شود، مشخص می‌کند. |
| [getPieSplitBy()](#getPieSplitBy--) | نحوه تعیین نقاط داده در دومین دایره یا میله در نمودار دایره-در-دایره یا میله-در-دایره را مشخص می‌کند. |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | اندازه حفره در نمودار دونات را مشخص می‌کند (می‌تواند بین ۱۰ تا ۹۰ درصد از اندازه ناحیه‌نقشه باشد). |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | زاویهٔ اولین برش نمودار دایره یا دونات را به‌درجه مشخص می‌کند (ساعت‌گرد از بالا، از ۰ تا ۳۶۰ درجه). |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | اطلاعات تقسیم سفارشی برای نمودار دایره-در-دایره یا میله-در-دایره با تقسیم سفارشی. |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | نحوهٔ نمایش مقادیر اندازه حباب‌ها در نمودار حباب را مشخص می‌کند. |
### getExplosion() {#getExplosion--}
```
public abstract int getExplosion()
```

فاصله یک برش پیت باز از مرکز نمودار دایره‌ای به‌عنوان درصدی از قطر دایره بیان می‌شود. قابل خواندن/نوشتن عدد صحیح.

**Returns:**
int
### setExplosion(int value) {#setExplosion-int-}
```
public abstract void setExplosion(int value)
```

فاصله یک برش پیت باز از مرکز نمودار دایره‌ای به‌عنوان درصدی از قطر دایره بیان می‌شود. قابل خواندن/نوشتن عدد صحیح.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### getSmooth() {#getSmooth--}
```
public abstract boolean getSmooth()
```

نمایانگر صاف‌سازی منحنی. اگر صاف‌سازی برای نمودار خطی یا پراکنش فعال باشد، مقدار true است. فقط برای نمودارهای خطی و پراکنش متصل به خطوط اعمال می‌شود. قابل خواندن/نوشتن بولی.

**Returns:**
boolean
### setSmooth(boolean value) {#setSmooth-boolean-}
```
public abstract void setSmooth(boolean value)
```

نمایانگر صاف‌سازی منحنی. اگر صاف‌سازی برای نمودار خطی یا پراکنش فعال باشد، مقدار true است. فقط برای نمودارهای خطی و پراکنش متصل به خطوط اعمال می‌شود. قابل خواندن/نوشتن بولی.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getMarker() {#getMarker--}
```
public abstract IMarker getMarker()
```

بازگرداندن نشانگر سری. فقط‌خواندنی [IMarker](../../com.aspose.slides/imarker).

**Returns:**
[IMarker](../../com.aspose.slides/imarker)
### getBar3DShape() {#getBar3DShape--}
```
public abstract int getBar3DShape()
```

مشخص می‌کند شکل یک سری از نمودار میله‌ای سه‌بعدی چیست. تغییر مقدار این ویژگی می‌تواند باعث تغییر خودکار نوع سری شود. قابل خواندن/نوشتن [ChartShapeType](../../com.aspose.slides/chartshapetype).

**Returns:**
int
### setBar3DShape(int value) {#setBar3DShape-int-}
```
public abstract void setBar3DShape(int value)
```

مشخص می‌کند شکل یک سری از نمودار میله‌ای سه‌بعدی چیست. تغییر مقدار این ویژگی می‌تواند باعث تغییر خودکار نوع سری شود. قابل خواندن/نوشتن [ChartShapeType](../../com.aspose.slides/chartshapetype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### getName() {#getName--}
```
public abstract IStringChartValue getName()
```

بازگرداندن نام سری. فقط‌خواندنی [IStringChartValue](../../com.aspose.slides/istringchartvalue).

**Returns:**
[IStringChartValue](../../com.aspose.slides/istringchartvalue)
### getDataPoints() {#getDataPoints--}
```
public abstract IChartDataPointCollection getDataPoints()
```

مجموعه‌ای از نقاط داده این سری را برمی‌گرداند. فقط‌خواندنی [IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection).

**Returns:**
[IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection)
### getType() {#getType--}
```
public abstract int getType()
```

نوعی از این سری را برمی‌گرداند. قابل خواندن/نوشتن [ChartType](../../com.aspose.slides/charttype).

**Returns:**
int
### setType(int value) {#setType-int-}
```
public abstract void setType(int value)
```

نوعی از این سری را برمی‌گرداند. قابل خواندن/نوشتن [ChartType](../../com.aspose.slides/charttype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### getParentSeriesGroup() {#getParentSeriesGroup--}
```
public abstract IChartSeriesGroup getParentSeriesGroup()
```

گروه پدر سری را برمی‌گرداند. فقط‌خواندنی [IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup).

**Returns:**
[IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup)
### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

قالب یک سری را برمی‌گرداند. فقط‌خواندنی [IFormat](../../com.aspose.slides/iformat).

**Returns:**
[IFormat](../../com.aspose.slides/iformat)
### getOrder() {#getOrder--}
```
public abstract int getOrder()
```

ترتیب یک سری را برمی‌گرداند. قابل خواندن/نوشتن عدد صحیح.

**Returns:**
int
### setOrder(int value) {#setOrder-int-}
```
public abstract void setOrder(int value)
```

ترتیب یک سری را برمی‌گرداند. قابل خواندن/نوشتن عدد صحیح.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### getLabels() {#getLabels--}
```
public abstract IDataLabelCollection getLabels()
```

برچسب‌های یک سری را برمی‌گرداند. فقط‌خواندنی [IDataLabelCollection](../../com.aspose.slides/idatalabelcollection).

**Returns:**
[IDataLabelCollection](../../com.aspose.slides/idatalabelcollection)
### getTrendLines() {#getTrendLines--}
```
public abstract ITrendlineCollection getTrendLines()
```

مجموعه‌ای از خطوط روند سری. فقط‌خواندنی [ITrendlineCollection](../../com.aspose.slides/itrendlinecollection).

**Returns:**
[ITrendlineCollection](../../com.aspose.slides/itrendlinecollection)
### getErrorBarsXFormat() {#getErrorBarsXFormat--}
```
public abstract IErrorBarsFormat getErrorBarsXFormat()
```

نمایش نوارهای خطا برای سری با جهت X. فقط‌خواندنی [IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat).

--------------------

نوارهای خطا با جهت X برای سری‌های نوع ناحیه، میله، پراکنش و حباب در دسترس هستند. برای سایر انواع نمودار این ویژگی مقدار null برمی‌گرداند (از جمله نمودارهای سه‌بعدی). در صورت استفاده از مقادیر سفارشی، برای تعیین مقدار از مجموعه DataPoints استفاده کنید (با ویژگی ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues))).

**Returns:**
[IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)
### getErrorBarsYFormat() {#getErrorBarsYFormat--}
```
public abstract IErrorBarsFormat getErrorBarsYFormat()
```

نمایش نوارهای خطا برای سری با جهت Y. فقط‌خواندنی [IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat).

--------------------

نوارهای خطا با جهت Y برای سری‌های نوع ناحیه، میله، خط، پراکنش و حباب در دسترس هستند. برای سایر انواع نمودار این ویژگی مقدار null برمی‌گرداند (از جمله نمودارهای سه‌بعدی). در صورت استفاده از مقادیر سفارشی، برای تعیین مقدار از مجموعه DataPoints استفاده کنید (با ویژگی ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues))).

**Returns:**
[IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)
### getPlotOnSecondAxis() {#getPlotOnSecondAxis--}
```
public abstract boolean getPlotOnSecondAxis()
```

نشان می‌دهد آیا این سری روی محور مقدار دوم ترسیم می‌شود. قابل خواندن/نوشتن بولی.

**Returns:**
boolean
### setPlotOnSecondAxis(boolean value) {#setPlotOnSecondAxis-boolean-}
```
public abstract void setPlotOnSecondAxis(boolean value)
```

نشان می‌دهد آیا این سری روی محور مقدار دوم ترسیم می‌شود. قابل خواندن/نوشتن بولی.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getNumberFormatOfValues() {#getNumberFormatOfValues--}
```
public abstract String getNumberFormatOfValues()
```

قالب عددی مقادیر سری را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن String.

**Returns:**
java.lang.String
### setNumberFormatOfValues(String value) {#setNumberFormatOfValues-java.lang.String-}
```
public abstract void setNumberFormatOfValues(String value)
```

قالب عددی مقادیر سری را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |
### getNumberFormatOfXValues() {#getNumberFormatOfXValues--}
```
public abstract String getNumberFormatOfXValues()
```

قالب عددی مقادیر x سری را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن String.

**Returns:**
java.lang.String
### setNumberFormatOfXValues(String value) {#setNumberFormatOfXValues-java.lang.String-}
```
public abstract void setNumberFormatOfXValues(String value)
```

قالب عددی مقادیر x سری را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |
### getNumberFormatOfYValues() {#getNumberFormatOfYValues--}
```
public abstract String getNumberFormatOfYValues()
```

قالب عددی مقادیر y سری را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن String.

**Returns:**
java.lang.String
### setNumberFormatOfYValues(String value) {#setNumberFormatOfYValues-java.lang.String-}
```
public abstract void setNumberFormatOfYValues(String value)
```

قالب عددی مقادیر y سری را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |
### getNumberFormatOfBubbleSizes() {#getNumberFormatOfBubbleSizes--}
```
public abstract String getNumberFormatOfBubbleSizes()
```

قالب عددی اندازه حباب‌های سری را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن String.

**Returns:**
java.lang.String
### setNumberFormatOfBubbleSizes(String value) {#setNumberFormatOfBubbleSizes-java.lang.String-}
```
public abstract void setNumberFormatOfBubbleSizes(String value)
```

قالب عددی اندازه حباب‌های سری را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |
### getInvertIfNegative() {#getInvertIfNegative--}
```
public abstract boolean getInvertIfNegative()
```

مشخص می‌کند که اگر مقدار منفی باشد، سری میله، ستون یا حباب رنگ‌های خود را معکوس کند. قابل خواندن/نوشتن بولی.

**Returns:**
boolean
### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public abstract void setInvertIfNegative(boolean value)
```

مشخص می‌کند که اگر مقدار منفی باشد، سری میله، ستون یا حباب رنگ‌های خود را معکوس کند. قابل خواندن/نوشتن بولی.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getInvertedSolidFillColor() {#getInvertedSolidFillColor--}
```
public abstract IColorFormat getInvertedSolidFillColor()
```

رنگ جامد معکوس را برای سری مشخص می‌کند. برای اعمال تنظیم رنگ، نوع پرکردن سری را به FillType.Solid تنظیم کنید. قابل خواندن/نوشتن [IColorFormat](../../com.aspose.slides/icolorformat).

**Returns:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public abstract ILegendEntryProperties getRelatedLegendEntry()
```

نمایانگر ورودی افقنام مرتبط با این سری. فقط‌خواندنی [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**Returns:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)
### getAutomaticSeriesColor() {#getAutomaticSeriesColor--}
```
public abstract Color getAutomaticSeriesColor()
```
یک رنگ خودکار برای سری بر اساس اندیس سری و سبک نمودار برمی‌گرداند. این رنگ به‌صورت پیش‌فرض استفاده می‌شود اگر FillType برابر NotDefined باشد.

**بازگشت:**  
java.awt.Color - رنگ خودکار سری java.awt.Color

### getShowInnerPoints() {#getShowInnerPoints--}
```
public abstract boolean getShowInnerPoints()
```

نقطه‌های داخلی را نشان می‌دهد. True اگر نقطه‌های داخلی در نمودار BoxAndWhisker نمایش داده شوند. فقط برای نمودارهای BoxAndWhisker اعمال می‌شود. قابل خواندن/نوشتن boolean.

**بازگشت:**  
boolean

### setShowInnerPoints(boolean value) {#setShowInnerPoints-boolean-}
```
public abstract void setShowInnerPoints(boolean value)
```

نقطه‌های داخلی را تنظیم می‌کند. True اگر نقطه‌های داخلی در نمودار BoxAndWhisker نمایش داده شوند. فقط برای نمودارهای BoxAndWhisker اعمال می‌شود. قابل خواندن/نوشتن boolean.

**پارامترها:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowOutlierPoints() {#getShowOutlierPoints--}
```
public abstract boolean getShowOutlierPoints()
```

نقطه‌های بیرونی را نشان می‌دهد. True اگر نقطه‌های بیرونی در نمودار BoxAndWhisker نمایش داده شوند. فقط برای نمودارهای BoxAndWhisker اعمال می‌شود. قابل خواندن/نوشتن boolean.

**بازگشت:**  
boolean

### setShowOutlierPoints(boolean value) {#setShowOutlierPoints-boolean-}
```
public abstract void setShowOutlierPoints(boolean value)
```

نقطه‌های بیرونی را تنظیم می‌کند. True اگر نقطه‌های بیرونی در نمودار BoxAndWhisker نمایش داده شوند. فقط برای نمودارهای BoxAndWhisker اعمال می‌شود. قابل خواندن/نوشتن boolean.

**پارامترها:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowMeanMarkers() {#getShowMeanMarkers--}
```
public abstract boolean getShowMeanMarkers()
```

علامت‌گرهای میانگین را نشان می‌دهد. True اگر علامت‌گرهای میانگین در نمودار BoxAndWhisker نمایش داده شوند. فقط برای نمودارهای BoxAndWhisker اعمال می‌شود. قابل خواندن/نوشتن boolean.

**بازگشت:**  
boolean

### setShowMeanMarkers(boolean value) {#setShowMeanMarkers-boolean-}
```
public abstract void setShowMeanMarkers(boolean value)
```

علامت‌گرهای میانگین را تنظیم می‌کند. True اگر علامت‌گرهای میانگین در نمودار BoxAndWhisker نمایش داده شوند. فقط برای نمودارهای BoxAndWhisker اعمال می‌شود. قابل خواندن/نوشتن boolean.

**پارامترها:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowMeanLine() {#getShowMeanLine--}
```
public abstract boolean getShowMeanLine()
```

خط میانگین را نشان می‌دهد. True اگر خط میانگین در نمودار BoxAndWhisker نمایش داده شود. فقط برای نمودارهای BoxAndWhisker اعمال می‌شود. قابل خواندن/نوشتن boolean.

**بازگشت:**  
boolean

### setShowMeanLine(boolean value) {#setShowMeanLine-boolean-}
```
public abstract void setShowMeanLine(boolean value)
```

خط میانگین را تنظیم می‌کند. True اگر خط میانگین در نمودار BoxAndWhisker نمایش داده شود. فقط برای نمودارهای BoxAndWhisker اعمال می‌شود. قابل خواندن/نوشتن boolean.

**پارامترها:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getQuartileMethod() {#getQuartileMethod--}
```
public abstract int getQuartileMethod()
```

روش چارک را نشان می‌دهد. فقط برای نمودارهای BoxAndWhisker اعمال می‌شود.

**بازگشت:**  
int

### setQuartileMethod(int value) {#setQuartileMethod-int-}
```
public abstract void setQuartileMethod(int value)
```

روش چارک را تنظیم می‌کند. فقط برای نمودارهای BoxAndWhisker اعمال می‌شود.

**پارامترها:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getShowConnectorLines() {#getShowConnectorLines--}
```
public abstract boolean getShowConnectorLines()
```

خط‌های اتصال را نشان می‌دهد. فقط برای نمودارهای Waterfall اعمال می‌شود.

**بازگشت:**  
boolean

### setShowConnectorLines(boolean value) {#setShowConnectorLines-boolean-}
```
public abstract void setShowConnectorLines(boolean value)
```

خط‌های اتصال را تنظیم می‌کند. فقط برای نمودارهای Waterfall اعمال می‌شود.

**پارامترها:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getParentLabelLayout() {#getParentLabelLayout--}
```
public abstract int getParentLabelLayout()
```

چیدمان برچسب‌های دسته والد را نشان می‌دهد. فقط برای نمودارهای Treemap اعمال می‌شود.

**بازگشت:**  
int

### setParentLabelLayout(int value) {#setParentLabelLayout-int-}
```
public abstract void setParentLabelLayout(int value)
```

چیدمان برچسب‌های دسته والد را تنظیم می‌کند. فقط برای نمودارهای Treemap اعمال می‌شود.

**پارامترها:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public abstract int getBubbleSizeScale()
```

مقیاس‌ساز اندازه برای نمودار حبابی را تعیین می‌کند (می‌تواند بین 0 تا 300 درصد اندازه پیش‌فرض باشد). این ویژگی فقط برای این سری نیست بلکه برای تمام سری‌های گروه سری والد است – این یک پروژکشن از ویژگی مربوطه گروه است. بنابراین این ویژگی فقط-خواندنی است. برای دسترسی به گروه سری والد از ویژگی ParentSeriesGroup استفاده کنید. برای تغییر مقدار از ویژگی ParentSeriesGroup.BubbleSizeScale خواندنی/نوشتنی استفاده کنید.

--------------------

این یک پروژکشن از ویژگی ParentSeriesGroup.BubbleSizeScale است.

**بازگشت:**  
int

### hasUpDownBars() {#hasUpDownBars--}
```
public abstract boolean hasUpDownBars()
```

تعیین می‌کند که آیا نمودار Line یا Stock دارای نوارهای بالا/پایین است یا خیر. این ویژگی فقط برای این سری نیست بلکه برای تمام سری‌های گروه سری والد است – این یک پروژکشن از ویژگی مربوطه گروه است. بنابراین این ویژگی فقط-خواندنی است. برای دسترسی به گروه سری والد از ویژگی ParentSeriesGroup استفاده کنید. برای تغییر مقدار از ویژگی ParentSeriesGroup.UpDownBars.HasUpDownBars خواندنی/نوشتنی استفاده کنید. برای قالب‌بندی نوارهای بالا/پایین از ویژگی ParentSeriesGroup.UpDownBars استفاده کنید. فقط-خواندنی boolean.

--------------------

این یک پروژکشن از ویژگی ParentSeriesGroup.UpDownBars.HasUpDownBars است.

**بازگشت:**  
boolean

### getGapWidth() {#getGapWidth--}
```
public abstract int getGapWidth()
```

فاصله بین خوشه‌های میله یا ستون را به‌عنوان درصدی از عرض میله یا ستون تعیین می‌کند. این ویژگی فقط برای این سری نیست بلکه برای تمام سری‌های گروه سری والد است – این یک پروژکشن از ویژگی مربوطه گروه است. بنابراین این ویژگی فقط-خواندنی است. برای دسترسی به گروه سری والد از ویژگی ParentSeriesGroup استفاده کنید. برای تغییر مقدار از ویژگی ParentSeriesGroup.GapWidth خواندنی/نوشتنی استفاده کنید. فقط-خواندنی int.

--------------------

این یک پروژکشن از ویژگی ParentSeriesGroup.GapWidth است.

**بازگشت:**  
int

### getGapDepth() {#getGapDepth--}
```
public abstract int getGapDepth()
```

فاصله را به‌عنوان درصدی از عرض نشانگر بین سری‌های داده در یک نمودار سه‌بعدی برمی‌گرداند یا تنظیم می‌کند. این ویژگی فقط برای این سری نیست بلکه برای تمام سری‌های گروه سری والد است – این یک پروژکشن از ویژگی مربوطه گروه است. بنابراین این ویژگی فقط-خواندنی است. برای دسترسی به گروه سری والد از ویژگی ParentSeriesGroup استفاده کنید. برای تغییر مقدار از ویژگی ParentSeriesGroup.GapDepth خواندنی/نوشتنی استفاده کنید. فقط-خواندنی int.

--------------------

این یک پروژکشن از ویژگی ParentSeriesGroup.GapDepth است.

**بازگشت:**  
int

### isColorVaried() {#isColorVaried--}
```
public abstract boolean isColorVaried()
```

مشخص می‌کند که هر نشانگر داده در سری دارای رنگ متفاوتی باشد. این ویژگی فقط برای این سری نیست بلکه برای تمام سری‌های گروه سری والد است – این یک پروژکشن از ویژگی مربوطه گروه است. بنابراین این ویژگی فقط-خواندنی است. برای دسترسی به گروه سری والد از ویژگی ParentSeriesGroup استفاده کنید. برای تغییر مقدار از ویژگی ParentSeriesGroup.IsColorVaried خواندنی/نوشتنی استفاده کنید. فقط-خواندنی boolean.

--------------------

این یک پروژکشن از ویژگی ParentSeriesGroup.IsColorVaried است.

**بازگشت:**  
boolean

### hasSeriesLines() {#hasSeriesLines--}
```
public abstract boolean hasSeriesLines()
```

تعیین می‌کند که آیا خطوط سری برای این سری و سری‌های مرتبط وجود دارد یا خیر. این ویژگی فقط برای این سری نیست بلکه برای تمام سری‌های گروه سری والد است – این یک پروژکشن از ویژگی مربوطه گروه است. بنابراین این ویژگی فقط-خواندنی است. برای دسترسی به گروه سری والد از ویژگی ParentSeriesGroup استفاده کنید. برای تغییر مقدار از ویژگی ParentSeriesGroup.HasSeriesLines خواندنی/نوشتنی استفاده کنید. برای قالب‌بندی خطوط سری از ویژگی ParentSeriesGroup.SeriesLinesFormat استفاده کنید. فقط-خواندنی boolean.

--------------------

این یک پروژکشن از ویژگی ParentSeriesGroup.HasSeriesLines است.

**بازگشت:**  
boolean

### getOverlap() {#getOverlap--}
```
public abstract byte getOverlap()
```

مشخص می‌کند که میله‌ها و ستون‌ها در نمودارهای دو‌بعدی به چه میزان هم‌پوشانی دارند، به‌عنوان درصد (از -100٪ تا 100٪). این ویژگی فقط برای این سری نیست بلکه برای تمام سری‌های گروه سری والد است. این یک پروژکشن از ویژگی مربوطه در گروه سری والد است و بنابراین این ویژگی فقط-خواندنی است. برای تغییر مقدار از ویژگی ParentSeriesGroup.Overlap خواندنی/نوشتنی استفاده کنید. فقط-خواندنی byte .

--------------------

Overlap میزان هم‌پوشانی یا فاصله بین میله و ستون را به‌عنوان درصدی از عرض آن‌ها مشخص می‌کند: -100٪: حداکثر فاصله (میله‌ها کاملاً جدا هستند). 0٪: میله‌ها بدون هم‌پوشانی یا فاصله کنار هم قرار می‌گیرند. 100٪: حداکثر هم‌پوشانی (میله‌ها کاملاً روی یکدیگر قرار می‌گیرند). این یک پروژکشن از ویژگی ParentSeriesGroup.Overlap است.

**بازگشت:**  
byte

### getSecondPieSize() {#getSecondPieSize--}
```
public abstract int getSecondPieSize()
```

اندازه دایره یا میله دوم در نمودار pie-of-pie یا bar-of-pie را به‌عنوان درصدی از اندازه دایره اول تعیین می‌کند (می‌تواند بین 5 تا 200 درصد باشد). این ویژگی فقط برای این سری نیست بلکه برای تمام سری‌های گروه سری والد است – این یک پروژکشن از ویژگی مربوطه گروه است. بنابراین این ویژگی فقط-خواندنی است. برای دسترسی به گروه سری والد از ویژگی ParentSeriesGroup استفاده کنید. برای تغییر مقدار از ویژگی ParentSeriesGroup.SecondPieSize خواندنی/نوشتنی استفاده کنید. فقط-خواندنی int.

--------------------

این یک پروژکشن از ویژگی ParentSeriesGroup.SecondPieSize است.

**بازگشت:**  
int

### getPieSplitPosition() {#getPieSplitPosition--}
```
public abstract double getPieSplitPosition()
```

مقداری را که برای تعیین اینکه کدام نقاط داده در دایره یا میله دوم در نمودار pie-of-pie یا bar-of-pie قرار گیرند، استفاده می‌کند. همراه با ویژگی PieSplitBy استفاده می‌شود. این ویژگی فقط برای این سری نیست بلکه برای تمام سری‌های گروه سری والد است – این یک پروژکشن از ویژگی مربوطه گروه است. بنابراین این ویژگی فقط-خواندنی است. برای دسترسی به گروه سری والد از ویژگی ParentSeriesGroup استفاده کنید. برای تغییر مقدار از ویژگی ParentSeriesGroup.PieSplitPosition خواندنی/نوشتنی استفاده کنید. فقط-خواندنی double.

--------------------

این یک پروژکشن از ویژگی ParentSeriesGroup.PieSplitPosition است.

**بازگشت:**  
double

### getPieSplitBy() {#getPieSplitBy--}
```
public abstract int getPieSplitBy()
```

نحوه تعیین اینکه کدام نقاط داده در دایره یا میله دوم در نمودار pie-of-pie یا bar-of-pie قرار گیرند را مشخص می‌کند. این ویژگی فقط برای این سری نیست بلکه برای تمام سری‌های گروه سری والد است – این یک پروژکشن از ویژگی مربوطه گروه است. بنابراین این ویژگی فقط-خواندنی است. برای دسترسی به گروه سری والد از ویژگی ParentSeriesGroup استفاده کنید. برای تغییر مقدار از ویژگی ParentSeriesGroup.PieSplitBy خواندنی/نوشتنی استفاده کنید. فقط-خواندنی [PieSplitType](../../com.aspose.slides/piesplittype).

--------------------

1) این یک پروژکشن از ویژگی ParentSeriesGroup.PieSplitBy است. 2) اگر مقدار ویژگی PieSplitType.Custom باشد می‌توانید اطلاعات تقسیم سفارشی را با ویژگی ParentSeriesGroup.PieSplitCustomPoints تعریف کنید.

**بازگشت:**  
int

### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public abstract byte getDoughnutHoleSize()
```

اندازه سوراخ در نمودار doughnut را تعیین می‌کند (می‌تواند بین 10 تا 90 درصد از اندازه ناحیه‌نقشه باشد). این ویژگی فقط برای این سری نیست بلکه برای تمام سری‌های گروه سری والد است – این یک پروژکشن از ویژگی مربوطه گروه است. بنابراین این ویژگی فقط-خواندنی است. برای دسترسی به گروه سری والد از ویژگی ParentSeriesGroup استفاده کنید. برای تغییر مقدار از ویژگی ParentSeriesGroup.DoughnutHoleSize خواندنی/نوشتنی استفاده کنید. فقط-خواندنی byte.

--------------------

این یک پروژکشن از ویژگی ParentSeriesGroup.DoughnutHoleSize است.

**بازگشت:**  
byte

### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public abstract int getFirstSliceAngle()
```

زاویه قطعه اول در نمودار pie یا doughnut را به‌صورت درجه (ساعتگرد از بالا، از 0 تا 360 درجه) تعیین می‌کند. این ویژگی فقط برای این سری نیست بلکه برای تمام سری‌های گروه سری والد است – این یک پروژکشن از ویژگی مربوطه گروه است. بنابراین این ویژگی فقط-خواندنی است. برای دسترسی به گروه سری والد از ویژگی ParentSeriesGroup استفاده کنید. برای تغییر مقدار از ویژگی ParentSeriesGroup.FirstSliceAngle خواندنی/نوشتنی استفاده کنید. فقط-خواندنی int.

--------------------

این یک پروژکشن از ویژگی ParentSeriesGroup.FirstSliceAngle است.

**بازگشت:**  
int

### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public abstract IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

اطلاعات تقسیم سفارشی برای نمودار pie-of-pie یا bar-of-pie با تقسیم سفارشی را ارائه می‌دهد. شامل نقاط داده‌ای است که باید در دایره یا میله دوم در نمودار pie-of-pie یا bar-of-pie رندر شوند. این ویژگی فقط برای این سری نیست بلکه برای تمام سری‌های گروه سری والد است – این یک پروژکشن از ویژگی مربوطه گروه است فقط-خواندنی [IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection).

--------------------

این یک پروژکشن از ویژگی ParentSeriesGroup.PieSplitCustomPoints است.

**بازگشت:**  
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)

### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public abstract int getBubbleSizeRepresentation()
```
نحوه نمایش مقادیر اندازهٔ حباب در نمودار حبابی را مشخص می‌کند. این ویژگی نه تنها برای این سری بلکه برای تمام سری‌های گروه سری والد است - این یک تصویر از ویژگی مناسب گروه است. بنابراین این ویژگی فقط‌خواندنی است. از ویژگی ParentSeriesGroup برای دسترسی به گروه سری والد استفاده کنید. از ویژگی ParentSeriesGroup.BubbleSizeRepresentation که قابل خواندن/نوشتن است برای تغییر مقدار استفاده کنید.

--------------------

این یک تصویر از ویژگی ParentSeriesGroup.BubbleSizeRepresentation است.

**بازگشت:**  
int