---
title: ChartDataPointCollection
second_title: مرجع API Aspose.Slides برای جاوا
description: نمایش‌دهنده مجموعه‌ای از نقاط داده یک سری.
type: docs
url: /fa/com.aspose.slides/chartdatapointcollection/
---
**ارث‌بری:**  
java.lang.Object, com.aspose.slides.DomObject

**تمام رابط‌های پیاده‌سازی‌شده:**  
[com.aspose.slides.IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection)  
```
public class ChartDataPointCollection extends DomObject<ChartSeries> implements IChartDataPointCollection
```

نمایش مجموعه‌ای از یک نقطه داده سری.

## متدها

| متد | توضیح |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | نقطه داده سری را بر اساس شاخص (شمارهٔ سریال آن در این مجموعه) برمی‌گرداند. |
| [get_Item(IChartDataPoint pt)](#get-Item-com.aspose.slides.IChartDataPoint-) | شاخص (شمارهٔ سریال) نقطه داده را در این مجموعه برمی‌گرداند. |
| [getDataSourceTypeForXValues()](#getDataSourceTypeForXValues--) | مشخص می‌کند که آیا ویژگی AsCell یا AsLiteralString یا AsLiteralDouble در شیء ویژگی XValue نقاط داده موجود است یا خیر. |
| [setDataSourceTypeForXValues(int value)](#setDataSourceTypeForXValues-int-) | مشخص می‌کند که آیا ویژگی AsCell یا AsLiteralString یا AsLiteralDouble در شیء ویژگی XValue نقاط داده موجود است یا خیر. |
| [getDataSourceTypeForYValues()](#getDataSourceTypeForYValues--) | مشخص می‌کند که آیا ویژگی AsCell یا AsLiteralString یا AsLiteralDouble در شیء ویژگی YValue نقاط داده موجود است یا خیر. |
| [setDataSourceTypeForYValues(int value)](#setDataSourceTypeForYValues-int-) | مشخص می‌کند که آیا ویژگی AsCell یا AsLiteralString یا AsLiteralDouble در شیء ویژگی YValue نقاط داده موجود است یا خیر. |
| [getDataSourceTypeForBubbleSizes()](#getDataSourceTypeForBubbleSizes--) | مشخص می‌کند که آیا ویژگی AsCell یا AsLiteralString یا AsLiteralDouble در شیء ویژگی BubbleSize نقاط داده موجود است یا خیر. |
| [setDataSourceTypeForBubbleSizes(int value)](#setDataSourceTypeForBubbleSizes-int-) | مشخص می‌کند که آیا ویژگی AsCell یا AsLiteralString یا AsLiteralDouble در شیء ویژگی BubbleSize نقاط داده موجود است یا خیر. |
| [getDataSourceTypeForValues()](#getDataSourceTypeForValues--) | مشخص می‌کند که آیا ویژگی AsCell یا AsLiteralString یا AsLiteralDouble در شیء ویژگی Value نقاط داده موجود است یا خیر. |
| [setDataSourceTypeForValues(int value)](#setDataSourceTypeForValues-int-) | مشخص می‌کند که آیا ویژگی AsCell یا AsLiteralString یا AsLiteralDouble در شیء ویژگی Value نقاط داده موجود است یا خیر. |
| [getDataSourceTypeForErrorBarsCustomValues()](#getDataSourceTypeForErrorBarsCustomValues--) | نوع مقادیر در فهرست ویژگی‌های ChartDataPoint.ErrorBarsCustomValues را مشخص می‌کند. |
| [getOrCreateDataPointByIdx(long index)](#getOrCreateDataPointByIdx-long-) | اگر مجموعه از پیش نقطه داده‌ای با شاخص index داشته باشد، آن نقطه داده را برمی‌گرداند. |
| [size()](#size--) | تعداد عناصری که واقعاً در مجموعه موجود است را دریافت می‌کند. |
| [copyTo(System.Array array, int arrayIndex)](#copyTo-com.aspose.ms.System.Array-int-) | به آرایهٔ مشخص شده کپی می‌کند. |
| [isSynchronized()](#isSynchronized--) | مقداری را برمی‌گرداند که نشان می‌دهد دسترسی به مجموعه همگام‌سازی شده (امن برای چند Thread) است یا خیر. |
| [getSyncRoot()](#getSyncRoot--) | ریشهٔ همگام‌سازی را برمی‌گرداند. |
| [iterator()](#iterator--) | یک شمارنده را برمی‌گرداند که از طریق مجموعه تکرار می‌کند. |
| [iteratorJava()](#iteratorJava--) | یک iterator جاوا برای کل مجموعه را برمی‌گرداند. |
| [addDataPointForStockSeries(IChartDataCell value)](#addDataPointForStockSeries-com.aspose.slides.IChartDataCell-) | یک نقطه دادهٔ جدید ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. |
| [addDataPointForStockSeries(double value)](#addDataPointForStockSeries-double-) | یک نقطه دادهٔ جدید ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. |
| [addDataPointForLineSeries(IChartDataCell value)](#addDataPointForLineSeries-com.aspose.slides.IChartDataCell-) | یک نقطه دادهٔ جدید ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. |
| [addDataPointForLineSeries(double value)](#addDataPointForLineSeries-double-) | یک نقطه دادهٔ جدید ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. |
| [addDataPointForScatterSeries(IChartDataCell xValue, IChartDataCell yValue)](#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | یک نقطه دادهٔ جدید ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. |
| [addDataPointForScatterSeries(double xValue, IChartDataCell yValue)](#addDataPointForScatterSeries-double-com.aspose.slides.IChartDataCell-) | یک نقطه دادهٔ جدید ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. |
| [addDataPointForScatterSeries(String xValue, IChartDataCell yValue)](#addDataPointForScatterSeries-java.lang.String-com.aspose.slides.IChartDataCell-) | یک نقطه دادهٔ جدید ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. |
| [addDataPointForScatterSeries(IChartDataCell xValue, double yValue)](#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-double-) | یک نقطه دادهٔ جدید ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. |
| [addDataPointForScatterSeries(double xValue, double yValue)](#addDataPointForScatterSeries-double-double-) | یک نقطه دادهٔ جدید ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. |
| [addDataPointForScatterSeries(String xValue, double yValue)](#addDataPointForScatterSeries-java.lang.String-double-) | یک نقطه دادهٔ جدید ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. |
| [addDataPointForRadarSeries(IChartDataCell value)](#addDataPointForRadarSeries-com.aspose.slides.IChartDataCell-) | یک نقطه دادهٔ جدید ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. |
| [addDataPointForRadarSeries(double value)](#addDataPointForRadarSeries-double-) | یک نقطه دادهٔ جدید ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. |
| [addDataPointForBarSeries(IChartDataCell value)](#addDataPointForBarSeries-com.aspose.slides.IChartDataCell-) | یک نقطه دادهٔ جدید ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. |
| [addDataPointForBarSeries(double value)](#addDataPointForBarSeries-double-) | یک نقطه دادهٔ جدید ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. |
| [addDataPointForAreaSeries(IChartDataCell value)](#addDataPointForAreaSeries-com.aspose.slides.IChartDataCell-) | یک نقطه دادهٔ جدید ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. |
| [addDataPointForAreaSeries(double value)](#addDataPointForAreaSeries-double-) | یک نقطه دادهٔ جدید ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. |
| [addDataPointForPieSeries(IChartDataCell value)](#addDataPointForPieSeries-com.aspose.slides.IChartDataCell-) | یک نقطه دادهٔ جدید ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. |
| [addDataPointForPieSeries(double value)](#addDataPointForPieSeries-double-) | یک نقطه دادهٔ جدید ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. |
| [addDataPointForDoughnutSeries(IChartDataCell value)](#addDataPointForDoughnutSeries-com.aspose.slides.IChartDataCell-) | یک نقطه دادهٔ جدید ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. |
| [addDataPointForDoughnutSeries(double value)](#addDataPointForDoughnutSeries-double-) | یک نقطه دادهٔ جدید ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. |
| [addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | یک نقطه دادهٔ جدید ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. |
| [addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | یک نقطه دادهٔ جدید ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. |
| [addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | یک نقطه دادهٔ جدید ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. |
| [addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-com.aspose.slides.IChartDataCell-) | یک نقطه دادهٔ جدید ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. |
| [addDataPointForBubbleSeries(double xValue, double yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-double-double-com.aspose.slides.IChartDataCell-) | یک نقطه دادهٔ جدید ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. |
| [addDataPointForBubbleSeries(String xValue, double yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-double-com.aspose.slides.IChartDataCell-) | یک نقطه دادهٔ جدید ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. |
| [addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, double bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-double-) | یک نقطه دادهٔ جدید ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. |
| [addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, double bubbleSize)](#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-double-) | یک نقطه دادهٔ جدید ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. |
| [addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, double bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-double-) | یک نقطه دادهٔ جدید ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. |
| [addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, double bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-double-) | یک نقطه دادهٔ جدید ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. |
| [addDataPointForBubbleSeries(double xValue, double yValue, double bubbleSize)](#addDataPointForBubbleSeries-double-double-double-) | یک نقطه دادهٔ جدید ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. |
| [addDataPointForBubbleSeries(String xValue, double yValue, double bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-double-double-) | یک نقطه دادهٔ جدید ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. |
| [addDataPointForSurfaceSeries(IChartDataCell value)](#addDataPointForSurfaceSeries-com.aspose.slides.IChartDataCell-) | یک نقطه دادهٔ جدید ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. |
| [addDataPointForSurfaceSeries(double value)](#addDataPointForSurfaceSeries-double-) | یک نقطه دادهٔ جدید ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. |
| [addDataPointForSunburstSeries(IChartDataCell sizeValue)](#addDataPointForSunburstSeries-com.aspose.slides.IChartDataCell-) | یک نقطه دادهٔ جدید ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. |
| [addDataPointForTreemapSeries(IChartDataCell sizeValue)](#addDataPointForTreemapSeries-com.aspose.slides.IChartDataCell-) | یک نقطه دادهٔ جدید ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. |
| [addDataPointForBoxAndWhiskerSeries(IChartDataCell value)](#addDataPointForBoxAndWhiskerSeries-com.aspose.slides.IChartDataCell-) | یک نقطه دادهٔ جدید ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. |
| [addDataPointForWaterfallSeries(IChartDataCell value)](#addDataPointForWaterfallSeries-com.aspose.slides.IChartDataCell-) | یک نقطه دادهٔ جدید ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. |
| [addDataPointForHistogramSeries(IChartDataCell value)](#addDataPointForHistogramSeries-com.aspose.slides.IChartDataCell-) | یک نقطه دادهٔ جدید ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. |
| [addDataPointForFunnelSeries(IChartDataCell value)](#addDataPointForFunnelSeries-com.aspose.slides.IChartDataCell-) | یک نقطه دادهٔ جدید ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. |
| [addDataPointForMapSeries(IChartDataCell value)](#addDataPointForMapSeries-com.aspose.slides.IChartDataCell-) | یک نقطه دادهٔ جدید ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. |
| [clear()](#clear--) | تمام عناصر را از مجموعه حذف می‌کند. |
| [remove(IChartDataPoint value)](#remove-com.aspose.slides.IChartDataPoint-) | مقدار مشخص‌شده را حذف می‌کند. |
| [removeAt(int index)](#removeAt-int-) | عنصر را در شاخص داده‌شده حذف می‌کند. |

### get_Item(int index) {#get-Item-int-}
```
public final IChartDataPoint get_Item(int index)
```

نقطه داده سری را بر اساس شاخص (شمارهٔ سریال آن در این مجموعه) برمی‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int |  |

**باز می‌گردد:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint)

### get_Item(IChartDataPoint pt) {#get-Item-com.aspose.slides.IChartDataPoint-}
```
public final int get_Item(IChartDataPoint pt)
```

شاخص (شمارهٔ سریال) نقطه داده را در این مجموعه برمی‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| pt | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) |  |

**باز می‌گردد:**
int

### getDataSourceTypeForXValues() {#getDataSourceTypeForXValues--}
```
public final int getDataSourceTypeForXValues()
```

مشخص می‌کند که آیا ویژگی AsCell یا AsLiteralString یا AsLiteralDouble در شیء ویژگی XValue نقاط داده موجود است یا خیر. به عبارت دیگر نوع مقدار ویژگی ChartDataPoint.XValue.Data را مشخص می‌کند. خواندنی/نوشتنی [DataSourceType](../../com.aspose.slides/datasourcetype).

**باز می‌گردد:**
int

### setDataSourceTypeForXValues(int value) {#setDataSourceTypeForXValues-int-}
```
public final void setDataSourceTypeForXValues(int value)
```

مشخص می‌کند که آیا ویژگی AsCell یا AsLiteralString یا AsLiteralDouble در شیء ویژگی XValue نقاط داده موجود است یا خیر. به عبارت دیگر نوع مقدار ویژگی ChartDataPoint.XValue.Data را مشخص می‌کند. خواندنی/نوشتنی [DataSourceType](../../com.aspose.slides/datasourcetype).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForYValues() {#getDataSourceTypeForYValues--}
```
public final int getDataSourceTypeForYValues()
```

مشخص می‌کند که آیا ویژگی AsCell یا AsLiteralString یا AsLiteralDouble در شیء ویژگی YValue نقاط داده موجود است یا خیر. به عبارت دیگر نوع مقدار ویژگی ChartDataPoint.YValue.Data را مشخص می‌کند. خواندنی/نوشتنی [DataSourceType](../../com.aspose.slides/datasourcetype).

**باز می‌گردد:**
int

### setDataSourceTypeForYValues(int value) {#setDataSourceTypeForYValues-int-}
```
public final void setDataSourceTypeForYValues(int value)
```

مشخص می‌کند که آیا ویژگی AsCell یا AsLiteralString یا AsLiteralDouble در شیء ویژگی YValue نقاط داده موجود است یا خیر. به عبارت دیگر نوع مقدار ویژگی ChartDataPoint.YValue.Data را مشخص می‌کند. خواندنی/نوشتنی [DataSourceType](../../com.aspose.slides/datasourcetype).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForBubbleSizes() {#getDataSourceTypeForBubbleSizes--}
```
public final int getDataSourceTypeForBubbleSizes()
```

مشخص می‌کند که آیا ویژگی AsCell یا AsLiteralString یا AsLiteralDouble در شیء ویژگی BubbleSize نقاط داده موجود است یا خیر. به عبارت دیگر نوع مقدار ویژگی ChartDataPoint.BubbleSize.Data را مشخص می‌کند. خواندنی/نوشتنی [DataSourceType](../../com.aspose.slides/datasourcetype).

**باز می‌گردد:**
int

### setDataSourceTypeForBubbleSizes(int value) {#setDataSourceTypeForBubbleSizes-int-}
```
public final void setDataSourceTypeForBubbleSizes(int value)
```

مشخص می‌کند که آیا ویژگی AsCell یا AsLiteralString یا AsLiteralDouble در شیء ویژگی BubbleSize نقاط داده موجود است یا خیر. به عبارت دیگر نوع مقدار ویژگی ChartDataPoint.BubbleSize.Data را مشخص می‌کند. خواندنی/نوشتنی [DataSourceType](../../com.aspose.slides/datasourcetype).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForValues() {#getDataSourceTypeForValues--}
```
public final int getDataSourceTypeForValues()
```

مشخص می‌کند که آیا ویژگی AsCell یا AsLiteralString یا AsLiteralDouble در شیء ویژگی Value نقاط داده موجود است یا خیر. به عبارت دیگر نوع مقدار ویژگی ChartDataPoint.Value.Data را مشخص می‌کند. خواندنی/نوشتنی [DataSourceType](../../com.aspose.slides/datasourcetype).

**باز می‌گردد:**
int

### setDataSourceTypeForValues(int value) {#setDataSourceTypeForValues-int-}
```
public final void setDataSourceTypeForValues(int value)
```

مشخص می‌کند که آیا ویژگی AsCell یا AsLiteralString یا AsLiteralDouble در شیء ویژگی Value نقاط داده موجود است یا خیر. به عبارت دیگر نوع مقدار ویژگی ChartDataPoint.Value.Data را مشخص می‌کند. خواندنی/نوشتنی [DataSourceType](../../com.aspose.slides/datasourcetype).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForErrorBarsCustomValues() {#getDataSourceTypeForErrorBarsCustomValues--}
```
public final IDataSourceTypeForErrorBarsCustomValues getDataSourceTypeForErrorBarsCustomValues()
```

نوع مقادیر در فهرست ویژگی‌های ChartDataPoint.ErrorBarsCustomValues را مشخص می‌کند. فقط-خواندنی [IDataSourceTypeForErrorBarsCustomValues](../../com.aspose.slides/idatasourcetypeforerrorbarscustomvalues).

**باز می‌گردد:**
[IDataSourceTypeForErrorBarsCustomValues](../../com.aspose.slides/idatasourcetypeforerrorbarscustomvalues)

### getOrCreateDataPointByIdx(long index) {#getOrCreateDataPointByIdx-long-}
```
public final IChartDataPoint getOrCreateDataPointByIdx(long index)
```

اگر مجموعه از پیش نقطه داده‌ای با شاخص index داشته باشد، آن نقطه داده را برمی‌گرداند. اگر مجموعه نقطه داده‌ای با شاخص index==N (زمانی که تعداد نقاط داده در این مجموعه کمتر یا مساوی N باشد) نداشته باشد، نقاط دادهٔ ناکافی را اضافه می‌کند و آخرین نقطه (که شاخص درخواست‌شده را دارد) را برمی‌گرداند. به عنوان مثال، شاخص‌های مجموعه \{0, 1, 2\} هستند و شاخص درخواست‌شده 5 است. سپس متد نقاط دادهٔ ناکافی \{0, 1, 2, 3, 4, 5\} را اضافه می‌کند و نقطه دادهٔ با شاخص 5 را برمی‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | long | شاخص. |

**باز می‌گردد:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه دادهٔ با شاخص درخواست‌شده را برمی‌گرداند.

### size() {#size--}
```
public final int size()
```

تعداد عناصری که واقعاً در مجموعه موجود است را دریافت می‌کند. فقط-خواندنی int.

**باز می‌گردد:**
int

### copyTo(System.Array array, int arrayIndex) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int arrayIndex)
```

به آرایهٔ مشخص شده کپی می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | آرایه‌ای که به آن کپی می‌شود. |
| arrayIndex | int | شاخصی که کپی از آن شروع می‌شود. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

مقداری را برمی‌گرداند که نشان می‌دهد دسترسی به مجموعه همگام‌سازی شده (امن برای چند Thread) است یا خیر. فقط-خواندنی boolean.

**باز می‌گردد:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

ریشهٔ همگام‌سازی را برمی‌گرداند. فقط-خواندنی Object.

**باز می‌گردد:**
java.lang.Object

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataPoint> iterator()
```

یک شمارنده را برمی‌گرداند که از طریق مجموعه تکرار می‌کند.

**باز می‌گردد:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataPoint> - یک IGenericEnumerator که می‌توان برای تکرار مجموعه استفاده کرد.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataPoint> iteratorJava()
```

یک iterator جاوا برای کل مجموعه را برمی‌گرداند.

**باز می‌گردد:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataPoint> - یک java.util.Iterator برای کل مجموعه.

### addDataPointForStockSeries(IChartDataCell value) {#addDataPointForStockSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForStockSeries(IChartDataCell value)
```

یک نقطه دادهٔ جدید ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. برای سری‌هایی که chartType آن‌ها یکی از زیرنوع‌های Stock است (به متد [ChartTypeCharacterizer.isChartTypeStock(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeStock-int-) نیز نگاه کنید) قابل استفاده است.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | مقدار نقطه داده. |

**باز می‌گردد:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه دادهٔ جدید.

### addDataPointForStockSeries(double value) {#addDataPointForStockSeries-double-}
```
public final IChartDataPoint addDataPointForStockSeries(double value)
```
یک نقطه داده جدید ایجاد می‌کند و آن را به انتهای مجموعه اضافه می‌کند. برای سری‌هایی که chartType یکی از زیرنوع‌های Stock است قابل استفاده است (همچنین روش [ChartTypeCharacterizer.isChartTypeStock(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeStock-int-) را ببینید).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | double | مقدار Value نقطه داده. |

**بازگشت:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه داده جدید.
### addDataPointForLineSeries(IChartDataCell value) {#addDataPointForLineSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForLineSeries(IChartDataCell value)
```


یک نقطه داده جدید ایجاد می‌کند و آن را به انتهای مجموعه اضافه می‌کند. برای سری‌هایی که chartType یکی از زیرنوع‌های Line است قابل استفاده است (همچنین روش [ChartTypeCharacterizer.isChartTypeLine(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeLine-int-) را ببینید).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | مقدار Value نقطه داده. |

**بازگشت:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه داده جدید.
### addDataPointForLineSeries(double value) {#addDataPointForLineSeries-double-}
```
public final IChartDataPoint addDataPointForLineSeries(double value)
```


یک نقطه داده جدید ایجاد می‌کند و آن را به انتهای مجموعه اضافه می‌کند. برای سری‌هایی که chartType یکی از زیرنوع‌های Line است قابل استفاده است (همچنین روش [ChartTypeCharacterizer.isChartTypeLine(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeLine-int-) را ببینید).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | double | مقدار Value نقطه داده. |

**بازگشت:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه داده جدید.
### addDataPointForScatterSeries(IChartDataCell xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForScatterSeries(IChartDataCell xValue, IChartDataCell yValue)
```


یک نقطه داده جدید ایجاد می‌کند و آن را به انتهای مجموعه اضافه می‌کند. برای سری‌هایی که chartType یکی از زیرنوع‌های Scatter است قابل استفاده است (همچنین روش [ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-) را ببینید).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | مقدار XValue نقطه داده |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | مقدار YValue نقطه داده |

**بازگشت:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه داده جدید.
### addDataPointForScatterSeries(double xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-double-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForScatterSeries(double xValue, IChartDataCell yValue)
```


یک نقطه داده جدید ایجاد می‌کند و آن را به انتهای مجموعه اضافه می‌کند. برای سری‌هایی که chartType یکی از زیرنوع‌های Scatter است قابل استفاده است (همچنین روش [ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-) را ببینید).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| xValue | double | مقدار XValue نقطه داده |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | مقدار YValue نقطه داده |

**بازگشت:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه داده جدید.
### addDataPointForScatterSeries(String xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-java.lang.String-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForScatterSeries(String xValue, IChartDataCell yValue)
```


یک نقطه داده جدید ایجاد می‌کند و آن را به انتهای مجموعه اضافه می‌کند. برای سری‌هایی که chartType یکی از زیرنوع‌های Scatter است قابل استفاده است (همچنین روش [ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-) را ببینید).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| xValue | java.lang.String | مقدار XValue نقطه داده |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | مقدار YValue نقطه داده |

**بازگشت:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه داده جدید.
### addDataPointForScatterSeries(IChartDataCell xValue, double yValue) {#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-double-}
```
public final IChartDataPoint addDataPointForScatterSeries(IChartDataCell xValue, double yValue)
```


یک نقطه داده جدید ایجاد می‌کند و آن را به انتهای مجموعه اضافه می‌کند. برای سری‌هایی که chartType یکی از زیرنوع‌های Scatter است قابل استفاده است (همچنین روش [ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-) را ببینید).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | مقدار XValue نقطه داده |
| yValue | double | مقدار YValue نقطه داده |

**بازگشت:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه داده جدید.
### addDataPointForScatterSeries(double xValue, double yValue) {#addDataPointForScatterSeries-double-double-}
```
public final IChartDataPoint addDataPointForScatterSeries(double xValue, double yValue)
```


یک نقطه داده جدید ایجاد می‌کند و آن را به انتهای مجموعه اضافه می‌کند. برای سری‌هایی که chartType یکی از زیرنوع‌های Scatter است قابل استفاده است (همچنین روش [ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-) را ببینید).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| xValue | double | مقدار XValue نقطه داده |
| yValue | double | مقدار YValue نقطه داده |

**بازگشت:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه داده جدید.
### addDataPointForScatterSeries(String xValue, double yValue) {#addDataPointForScatterSeries-java.lang.String-double-}
```
public final IChartDataPoint addDataPointForScatterSeries(String xValue, double yValue)
```


یک نقطه داده جدید ایجاد می‌کند و آن را به انتهای مجموعه اضافه می‌کند. برای سری‌هایی که chartType یکی از زیرنوع‌های Scatter است قابل استفاده است (همچنین روش [ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-) را ببینید).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| xValue | java.lang.String | مقدار XValue نقطه داده |
| yValue | double | مقدار YValue نقطه داده |

**بازگشت:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه داده جدید.
### addDataPointForRadarSeries(IChartDataCell value) {#addDataPointForRadarSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForRadarSeries(IChartDataCell value)
```


یک نقطه داده جدید ایجاد می‌کند و آن را به انتهای مجموعه اضافه می‌کند. برای سری‌هایی که chartType یکی از زیرنوع‌های Radar است قابل استفاده است (همچنین روش [ChartTypeCharacterizer.isChartTypeRadar(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeRadar-int-) را ببینید).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | مقدار Value نقطه داده |

**بازگشت:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه داده جدید.
### addDataPointForRadarSeries(double value) {#addDataPointForRadarSeries-double-}
```
public final IChartDataPoint addDataPointForRadarSeries(double value)
```


یک نقطه داده جدید ایجاد می‌کند و آن را به انتهای مجموعه اضافه می‌کند. برای سری‌هایی که chartType یکی از زیرنوع‌های Radar است قابل استفاده است (همچنین روش [ChartTypeCharacterizer.isChartTypeRadar(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeRadar-int-) را ببینید).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | double | مقدار Value نقطه داده |

**بازگشت:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه داده جدید.
### addDataPointForBarSeries(IChartDataCell value) {#addDataPointForBarSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBarSeries(IChartDataCell value)
```


یک نقطه داده جدید ایجاد می‌کند و آن را به انتهای مجموعه اضافه می‌کند. برای سری‌هایی که chartType یکی از زیرنوع‌های Column یا Bar است قابل استفاده است (همچنین روش [ChartTypeCharacterizer.isChartTypeColumn(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeColumn-int-) و [ChartTypeCharacterizer.isChartTypeBar(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBar-int-) را ببینید).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | مقدار Value نقطه داده |

**بازگشت:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه داده جدید.
### addDataPointForBarSeries(double value) {#addDataPointForBarSeries-double-}
```
public final IChartDataPoint addDataPointForBarSeries(double value)
```


یک نقطه داده جدید ایجاد می‌کند و آن را به انتهای مجموعه اضافه می‌کند. برای سری‌هایی که chartType یکی از زیرنوع‌های Column یا Bar است قابل استفاده است (همچنین روش [ChartTypeCharacterizer.isChartTypeColumn(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeColumn-int-) و [ChartTypeCharacterizer.isChartTypeBar(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBar-int-) را ببینید).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | double | مقدار Value نقطه داده |

**بازگشت:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه داده جدید.
### addDataPointForAreaSeries(IChartDataCell value) {#addDataPointForAreaSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForAreaSeries(IChartDataCell value)
```


یک نقطه داده جدید ایجاد می‌کند و آن را به انتهای مجموعه اضافه می‌کند. برای سری‌هایی که chartType یکی از زیرنوع‌های Area است قابل استفاده است (همچنین روش [ChartTypeCharacterizer.isChartTypeArea(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeArea-int-) را ببینید).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | مقدار Value نقطه داده |

**بازگشت:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه داده جدید.
### addDataPointForAreaSeries(double value) {#addDataPointForAreaSeries-double-}
```
public final IChartDataPoint addDataPointForAreaSeries(double value)
```


یک نقطه داده جدید ایجاد می‌کند و آن را به انتهای مجموعه اضافه می‌کند. برای سری‌هایی که chartType یکی از زیرنوع‌های Area است قابل استفاده است (همچنین روش [ChartTypeCharacterizer.isChartTypeArea(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeArea-int-) را ببینید).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | double | مقدار Value نقطه داده |

**بازگشت:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه داده جدید.
### addDataPointForPieSeries(IChartDataCell value) {#addDataPointForPieSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForPieSeries(IChartDataCell value)
```


یک نقطه داده جدید ایجاد می‌کند و آن را به انتهای مجموعه اضافه می‌کند. برای سری‌هایی که chartType یکی از زیرنوع‌های Pie است قابل استفاده است (همچنین روش [ChartTypeCharacterizer.isChartTypePie(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypePie-int-) را ببینید).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | مقدار Value نقطه داده |

**بازگشت:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه داده جدید.
### addDataPointForPieSeries(double value) {#addDataPointForPieSeries-double-}
```
public final IChartDataPoint addDataPointForPieSeries(double value)
```


یک نقطه داده جدید ایجاد می‌کند و آن را به انتهای مجموعه اضافه می‌کند. برای سری‌هایی که chartType یکی از زیرنوع‌های Pie است قابل استفاده است (همچنین روش [ChartTypeCharacterizer.isChartTypePie(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypePie-int-) را ببینید).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | double | مقدار Value نقطه داده |

**بازگشت:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه داده جدید.
### addDataPointForDoughnutSeries(IChartDataCell value) {#addDataPointForDoughnutSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForDoughnutSeries(IChartDataCell value)
```


یک نقطه داده جدید ایجاد می‌کند و آن را به انتهای مجموعه اضافه می‌کند. برای سری‌هایی که chartType یکی از زیرنوع‌های Doughnut است قابل استفاده است (همچنین روش [ChartTypeCharacterizer.isChartTypeDoughnut(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeDoughnut-int-) را ببینید).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | مقدار Value نقطه داده |

**بازگشت:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه داده جدید.
### addDataPointForDoughnutSeries(double value) {#addDataPointForDoughnutSeries-double-}
```
public final IChartDataPoint addDataPointForDoughnutSeries(double value)
```


یک نقطه داده جدید ایجاد می‌کند و آن را به انتهای مجموعه اضافه می‌کند. برای سری‌هایی که chartType یکی از زیرنوع‌های Doughnut است قابل استفاده است (همچنین روش [ChartTypeCharacterizer.isChartTypeDoughnut(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeDoughnut-int-) را ببینید).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | double | مقدار Value نقطه داده |

**بازگشت:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه داده جدید.
### addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```


یک نقطه داده جدید ایجاد می‌کند و آن را به انتهای مجموعه اضافه می‌کند. برای سری‌هایی که chartType یکی از زیرنوع‌های Bubble است قابل استفاده است (همچنین روش [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) را ببینید).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | مقدار XValue نقطه داده |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | مقدار YValue نقطه داده |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | مقدار BubbleSize نقطه داده |

**بازگشت:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه داده جدید.
### addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```


یک نقطه داده جدید ایجاد می‌کند و آن را به انتهای مجموعه اضافه می‌کند. برای سری‌هایی که chartType یکی از زیرنوع‌های Bubble است قابل استفاده است (همچنین روش [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) را ببینید).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| xValue | double | مقدار XValue نقطه داده |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | مقدار YValue نقطه داده |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | مقدار BubbleSize نقطه داده |

**بازگشت:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه داده جدید.
### addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```


یک نقطه داده جدید ایجاد می‌کند و آن را به انتهای مجموعه اضافه می‌کند. برای سری‌هایی که chartType یکی از زیرنوع‌های Bubble است قابل استفاده است (همچنین روش [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) را ببینید).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| xValue | java.lang.String | مقدار XValue نقطه داده |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | مقدار YValue نقطه داده |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | مقدار BubbleSize نقطه داده |

**بازگشت:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه داده جدید.
### addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, IChartDataCell bubbleSize)
```


یک نقطه داده جدید ایجاد می‌کند و آن را به انتهای مجموعه اضافه می‌کند. برای سری‌هایی که chartType یکی از زیرنوع‌های Bubble است قابل استفاده است (همچنین روش [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) را ببینید).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | مقدار XValue نقطه داده |
| yValue | double | مقدار YValue نقطه داده |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | مقدار BubbleSize نقطه داده |

**بازگشت:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه داده جدید.
### addDataPointForBubbleSeries(double xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-double-double-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(double xValue, double yValue, IChartDataCell bubbleSize)
```


یک نقطه داده جدید ایجاد می‌کند و آن را به انتهای مجموعه اضافه می‌کند. برای سری‌هایی که chartType یکی از زیرنوع‌های Bubble است قابل استفاده است (همچنین روش [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) را ببینید).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| xValue | double | مقدار XValue نقطه داده |
| yValue | double | مقدار YValue نقطه داده |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | مقدار BubbleSize نقطه داده |

**بازگشت:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه داده جدید.
### addDataPointForBubbleSeries(String xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-double-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(String xValue, double yValue, IChartDataCell bubbleSize)
```


یک نقطه داده جدید ایجاد می‌کند و آن را به انتهای مجموعه اضافه می‌کند. برای سری‌هایی که chartType یکی از زیرنوع‌های Bubble است قابل استفاده است (همچنین روش [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) را ببینید).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| xValue |  ...
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| xValue | java.lang.String | نقطه داده XValue |
| yValue | double | نقطه داده YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | نقطه داده BubbleSize |

**بازگشت:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه داده جدید.

### addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, double bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, double bubbleSize)
```

یک نقطه داده جدید ایجاد می‌کند و آن را به انتهای مجموعه اضافه می‌نماید. برای سلسله‌هایی که chartType یکی از زیرنوع‌های Bubble است کاربرد دارد (همچنین به متد [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) مراجعه کنید).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | نقطه داده XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | نقطه داده YValue |
| bubbleSize | double | نقطه داده BubbleSize |

**بازگشت:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه داده جدید.

### addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, double bubbleSize) {#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, double bubbleSize)
```

یک نقطه داده جدید ایجاد می‌کند و آن را به انتهای مجموعه اضافه می‌نماید. برای سلسله‌هایی که chartType یکی از زیرنوع‌های Bubble است کاربرد دارد (همچنین به متد [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) مراجعه کنید).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| xValue | double | نقطه داده XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | نقطه داده YValue |
| bubbleSize | double | نقطه داده BubbleSize |

**بازگشت:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه داده جدید.

### addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, double bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, double bubbleSize)
```

یک نقطه داده جدید ایجاد می‌کند و آن را به انتهای مجموعه اضافه می‌نماید. برای سلسله‌هایی که chartType یکی از زیرنوع‌های Bubble است کاربرد دارد (همچنین به متد [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) مراجعه کنید).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| xValue | java.lang.String | نقطه داده XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | نقطه داده YValue |
| bubbleSize | double | نقطه داده BubbleSize |

**بازگشت:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه داده جدید.

### addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, double bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, double bubbleSize)
```

یک نقطه داده جدید ایجاد می‌کند و آن را به انتهای مجموعه اضافه می‌نماید. برای سلسله‌هایی که chartType یکی از زیرنوع‌های Bubble است کاربرد دارد (همچنین به متد [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) مراجعه کنید).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | نقطه داده XValue |
| yValue | double | نقطه داده YValue |
| bubbleSize | double | نقطه داده BubbleSize |

**بازگشت:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه داده جدید.

### addDataPointForBubbleSeries(double xValue, double yValue, double bubbleSize) {#addDataPointForBubbleSeries-double-double-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(double xValue, double yValue, double bubbleSize)
```

یک نقطه داده جدید ایجاد می‌کند و آن را به انتهای مجموعه اضافه می‌نماید. برای سلسله‌هایی که chartType یکی از زیرنوع‌های Bubble است کاربرد دارد (همچنین به متد [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) مراجعه کنید).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| xValue | double | نقطه داده XValue |
| yValue | double | نقطه داده YValue |
| bubbleSize | double | نقطه داده BubbleSize |

**بازگشت:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه داده جدید.

### addDataPointForBubbleSeries(String xValue, double yValue, double bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-double-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(String xValue, double yValue, double bubbleSize)
```

یک نقطه داده جدید ایجاد می‌کند و آن را به انتهای مجموعه اضافه می‌نماید. برای سلسله‌هایی که chartType یکی از زیرنوع‌های Bubble است کاربرد دارد (همچنین به متد [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) مراجعه کنید).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| xValue | java.lang.String | نقطه داده XValue |
| yValue | double | نقطه داده YValue |
| bubbleSize | double | نقطه داده BubbleSize |

**بازگشت:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه داده جدید.

### addDataPointForSurfaceSeries(IChartDataCell value) {#addDataPointForSurfaceSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForSurfaceSeries(IChartDataCell value)
```

یک نقطه داده جدید ایجاد می‌کند و آن را به انتهای مجموعه اضافه می‌نماید. برای سلسله‌هایی که chartType یکی از زیرنوع‌های Surface است کاربرد دارد (همچنین به متد [ChartTypeCharacterizer.isChartTypeSurface(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeSurface-int-) مراجعه کنید).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | نقطه داده Value |

**بازگشت:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه داده جدید.

### addDataPointForSurfaceSeries(double value) {#addDataPointForSurfaceSeries-double-}
```
public final IChartDataPoint addDataPointForSurfaceSeries(double value)
```

یک نقطه داده جدید ایجاد می‌کند و آن را به انتهای مجموعه اضافه می‌نماید. برای سلسله‌هایی که chartType یکی از زیرنوع‌های Surface است کاربرد دارد (همچنین به متد [ChartTypeCharacterizer.isChartTypeSurface(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeSurface-int-) مراجعه کنید).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | double | نقطه داده Value |

**بازگشت:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه داده جدید.

### addDataPointForSunburstSeries(IChartDataCell sizeValue) {#addDataPointForSunburstSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForSunburstSeries(IChartDataCell sizeValue)
```

یک نقطه داده جدید ایجاد می‌کند و آن را به انتهای مجموعه اضافه می‌نماید. برای سلسله‌هایی که نوع نمودار Sunburst است کاربرد دارد.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| sizeValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | نقطه داده SizeValue |

**بازگشت:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه داده جدید.

### addDataPointForTreemapSeries(IChartDataCell sizeValue) {#addDataPointForTreemapSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForTreemapSeries(IChartDataCell sizeValue)
```

یک نقطه داده جدید ایجاد می‌کند و آن را به انتهای مجموعه اضافه می‌نماید. برای سلسله‌هایی که نوع نمودار Treemap است کاربرد دارد.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| sizeValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | نقطه داده SizeValue |

**بازگشت:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه داده جدید.

### addDataPointForBoxAndWhiskerSeries(IChartDataCell value) {#addDataPointForBoxAndWhiskerSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBoxAndWhiskerSeries(IChartDataCell value)
```

یک نقطه داده جدید ایجاد می‌کند و آن را به انتهای مجموعه اضافه می‌نماید. برای سلسله‌هایی که نوع نمودار BoxAndWhisker است کاربرد دارد.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | نقطه داده Value |

**بازگشت:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه داده جدید.

### addDataPointForWaterfallSeries(IChartDataCell value) {#addDataPointForWaterfallSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForWaterfallSeries(IChartDataCell value)
```

یک نقطه داده جدید ایجاد می‌کند و آن را به انتهای مجموعه اضافه می‌نماید. برای سلسله‌هایی که نوع نمودار Waterfall است کاربرد دارد.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | نقطه داده Value |

**بازگشت:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه داده جدید.

### addDataPointForHistogramSeries(IChartDataCell value) {#addDataPointForHistogramSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForHistogramSeries(IChartDataCell value)
```

یک نقطه داده جدید ایجاد می‌کند و آن را به انتهای مجموعه اضافه می‌نماید. برای سلسله‌هایی که نوع نمودار Histogram است کاربرد دارد.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | نقطه داده Value |

**بازگشت:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه داده جدید.

### addDataPointForFunnelSeries(IChartDataCell value) {#addDataPointForFunnelSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForFunnelSeries(IChartDataCell value)
```

یک نقطه داده جدید ایجاد می‌کند و آن را به انتهای مجموعه اضافه می‌نماید. برای سلسله‌هایی که نوع نمودار Funnel است کاربرد دارد.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | نقطه داده Value |

**بازگشت:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه داده جدید.

### addDataPointForMapSeries(IChartDataCell value) {#addDataPointForMapSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForMapSeries(IChartDataCell value)
```

یک نقطه داده جدید ایجاد می‌کند و آن را به انتهای مجموعه اضافه می‌نماید. برای سلسله‌هایی که نوع نمودار Map است کاربرد دارد.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.Map, 50, 50, 500, 400, false);
>      IChartDataWorkbook wb = chart.getChartData().getChartDataWorkbook();
>      IChartSeries series = chart.getChartData().getSeries().add(ChartType.Map);
>      series.getDataPoints().addDataPointForMapSeries(wb.getCell(0, "B2", 5));
>      series.getDataPoints().addDataPointForMapSeries(wb.getCell(0, "B3", 1));
>      series.getDataPoints().addDataPointForMapSeries(wb.getCell(0, "B4", 10));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | نقطه داده ColorValue |

**بازگشت:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه داده جدید.

### clear() {#clear--}
```
public final void clear()
```

تمام عناصر را از مجموعه حذف می‌کند.

### remove(IChartDataPoint value) {#remove-com.aspose.slides.IChartDataPoint-}
```
public final void clear()
```

مقدار مشخص‌شده را حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | مقدار. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

عنصر موجود در اندیس داده‌شده را حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | اندیس نقطه داده‌ای که باید حذف شود. |