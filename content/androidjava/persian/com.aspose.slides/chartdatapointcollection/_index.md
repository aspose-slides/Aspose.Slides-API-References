---
title: ChartDataPointCollection
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: نمایانگر مجموعه‌ای از نقطه دادهٔ یک سری است.
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

نمایانگر مجموعه‌ای از نقطه دادهٔ یک سری است.

## متدها

| متد | توضیح |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | نقطه دادهٔ سری را بر اساس اندیس (شماره سریالی آن در این مجموعه) برمی‌گرداند. |
| [get_Item(IChartDataPoint pt)](#get-Item-com.aspose.slides.IChartDataPoint-) | اندیس (شماره سریالی) نقطه داده را در این مجموعه برمی‌گرداند. |
| [getDataSourceTypeForXValues()](#getDataSourceTypeForXValues--) | مشخص می‌کند که آیا ویژگی AsCell یا AsLiteralString یا AsLiteralDouble در شیء ویژگی XValue نقاط داده واقعی است. |
| [setDataSourceTypeForXValues(int value)](#setDataSourceTypeForXValues-int-) | مشخص می‌کند که آیا ویژگی AsCell یا AsLiteralString یا AsLiteralDouble در شیء ویژگی XValue نقاط داده واقعی است. |
| [getDataSourceTypeForYValues()](#getDataSourceTypeForYValues--) | مشخص می‌کند که آیا ویژگی AsCell یا AsLiteralString یا AsLiteralDouble در شیء ویژگی YValue نقاط داده واقعی است. |
| [setDataSourceTypeForYValues(int value)](#setDataSourceTypeForYValues-int-) | مشخص می‌کند که آیا ویژگی AsCell یا AsLiteralString یا AsLiteralDouble در شیء ویژگی YValue نقاط داده واقعی است. |
| [getDataSourceTypeForBubbleSizes()](#getDataSourceTypeForBubbleSizes--) | مشخص می‌کند که آیا ویژگی AsCell یا AsLiteralString یا AsLiteralDouble در شیء ویژگی BubbleSize نقاط داده واقعی است. |
| [setDataSourceTypeForBubbleSizes(int value)](#setDataSourceTypeForBubbleSizes-int-) | مشخص می‌کند که آیا ویژگی AsCell یا AsLiteralString یا AsLiteralDouble در شیء ویژگی BubbleSize نقاط داده واقعی است. |
| [getDataSourceTypeForValues()](#getDataSourceTypeForValues--) | مشخص می‌کند که آیا ویژگی AsCell یا AsLiteralString یا AsLiteralDouble در شیء ویژگی Value نقاط داده واقعی است. |
| [setDataSourceTypeForValues(int value)](#setDataSourceTypeForValues-int-) | مشخص می‌کند که آیا ویژگی AsCell یا AsLiteralString یا AsLiteralDouble در شیء ویژگی Value نقاط داده واقعی است. |
| [getDataSourceTypeForErrorBarsCustomValues()](#getDataSourceTypeForErrorBarsCustomValues--) | نوع مقادیر را در فهرست ویژگی‌های ChartDataPoint.ErrorBarsCustomValues مشخص می‌کند. |
| [getOrCreateDataPointByIdx(long index)](#getOrCreateDataPointByIdx-long-) | اگر مجموعه قبلاً نقطه داده‌ای با اندیس index داشته باشد، آن نقطه داده را برمی‌گرداند. |
| [size()](#size--) | تعداد عناصری که واقعا در مجموعه وجود دارند را برمی‌دارد. |
| [copyTo(System.Array array, int arrayIndex)](#copyTo-com.aspose.ms.System.Array-int-) | به آرایهٔ مشخص‌شده کپی می‌کند. |
| [isSynchronized()](#isSynchronized--) | مقداری را برمی‌گرداند که نشان می‌دهد دسترسی به مجموعه همگام‌سازی شده (امن برای چندرشته‌ای) است. |
| [getSyncRoot()](#getSyncRoot--) | ریشهٔ همگام‌سازی را برمی‌گرداند. |
| [iterator()](#iterator--) | یک شمارنده را برمی‌گرداند که از طریق مجموعه تکرار می‌کند. |
| [iteratorJava()](#iteratorJava--) | یک iterator جاوا برای کل مجموعه را برمی‌گرداند. |
| [addDataPointForStockSeries(IChartDataCell value)](#addDataPointForStockSeries-com.aspose.slides.IChartDataCell-) | نقطه دادهٔ جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. |
| [addDataPointForStockSeries(double value)](#addDataPointForStockSeries-double-) | نقطه دادهٔ جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. |
| [addDataPointForLineSeries(IChartDataCell value)](#addDataPointForLineSeries-com.aspose.slides.IChartDataCell-) | نقطه دادهٔ جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. |
| [addDataPointForLineSeries(double value)](#addDataPointForLineSeries-double-) | نقطه دادهٔ جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. |
| [addDataPointForScatterSeries(IChartDataCell xValue, IChartDataCell yValue)](#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | نقطه دادهٔ جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. |
| [addDataPointForScatterSeries(double xValue, IChartDataCell yValue)](#addDataPointForScatterSeries-double-com.aspose.slides.IChartDataCell-) | نقطه دادهٔ جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. |
| [addDataPointForScatterSeries(String xValue, IChartDataCell yValue)](#addDataPointForScatterSeries-java.lang.String-com.aspose.slides.IChartDataCell-) | نقطه دادهٔ جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. |
| [addDataPointForScatterSeries(IChartDataCell xValue, double yValue)](#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-double-) | نقطه دادهٔ جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. |
| [addDataPointForScatterSeries(double xValue, double yValue)](#addDataPointForScatterSeries-double-double-) | نقطه دادهٔ جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. |
| [addDataPointForScatterSeries(String xValue, double yValue)](#addDataPointForScatterSeries-java.lang.String-double-) | نقطه دادهٔ جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. |
| [addDataPointForRadarSeries(IChartDataCell value)](#addDataPointForRadarSeries-com.aspose.slides.IChartDataCell-) | نقطه دادهٔ جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. |
| [addDataPointForRadarSeries(double value)](#addDataPointForRadarSeries-double-) | نقطه دادهٔ جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. |
| [addDataPointForBarSeries(IChartDataCell value)](#addDataPointForBarSeries-com.aspose.slides.IChartDataCell-) | نقطه دادهٔ جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. |
| [addDataPointForBarSeries(double value)](#addDataPointForBarSeries-double-) | نقطه دادهٔ جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. |
| [addDataPointForAreaSeries(IChartDataCell value)](#addDataPointForAreaSeries-com.aspose.slides.IChartDataCell-) | نقطه دادهٔ جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. |
| [addDataPointForAreaSeries(double value)](#addDataPointForAreaSeries-double-) | نقطه دادهٔ جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. |
| [addDataPointForPieSeries(IChartDataCell value)](#addDataPointForPieSeries-com.aspose.slides.IChartDataCell-) | نقطه دادهٔ جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. |
| [addDataPointForPieSeries(double value)](#addDataPointForPieSeries-double-) | نقطه دادهٔ جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. |
| [addDataPointForDoughnutSeries(IChartDataCell value)](#addDataPointForDoughnutSeries-com.aspose.slides.IChartDataCell-) | نقطه دادهٔ جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. |
| [addDataPointForDoughnutSeries(double value)](#addDataPointForDoughnutSeries-double-) | نقطه دادهٔ جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. |
| [addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | نقطه دادهٔ جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. |
| [addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | نقطه دادهٔ جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. |
| [addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | نقطه دادهٔ جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. |
| [addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-com.aspose.slides.IChartDataCell-) | نقطه دادهٔ جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. |
| [addDataPointForBubbleSeries(double xValue, double yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-double-double-com.aspose.slides.IChartDataCell-) | نقطه دادهٔ جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. |
| [addDataPointForBubbleSeries(String xValue, double yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-double-com.aspose.slides.IChartDataCell-) | نقطه دادهٔ جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. |
| [addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, double bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-double-) | نقطه دادهٔ جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. |
| [addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, double bubbleSize)](#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-double-) | نقطه دادهٔ جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. |
| [addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, double bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-double-) | نقطه دادهٔ جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. |
| [addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, double bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-double-) | نقطه دادهٔ جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. |
| [addDataPointForBubbleSeries(double xValue, double yValue, double bubbleSize)](#addDataPointForBubbleSeries-double-double-double-) | نقطه دادهٔ جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. |
| [addDataPointForBubbleSeries(String xValue, double yValue, double bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-double-double-) | نقطه دادهٔ جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. |
| [addDataPointForSurfaceSeries(IChartDataCell value)](#addDataPointForSurfaceSeries-com.aspose.slides.IChartDataCell-) | نقطه دادهٔ جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. |
| [addDataPointForSurfaceSeries(double value)](#addDataPointForSurfaceSeries-double-) | نقطه دادهٔ جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. |
| [addDataPointForSunburstSeries(IChartDataCell sizeValue)](#addDataPointForSunburstSeries-com.aspose.slides.IChartDataCell-) | نقطه دادهٔ جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. |
| [addDataPointForTreemapSeries(IChartDataCell sizeValue)](#addDataPointForTreemapSeries-com.aspose.slides.IChartDataCell-) | نقطه دادهٔ جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. |
| [addDataPointForBoxAndWhiskerSeries(IChartDataCell value)](#addDataPointForBoxAndWhiskerSeries-com.aspose.slides.IChartDataCell-) | نقطه دادهٔ جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. |
| [addDataPointForWaterfallSeries(IChartDataCell value)](#addDataPointForWaterfallSeries-com.aspose.slides.IChartDataCell-) | نقطه دادهٔ جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. |
| [addDataPointForHistogramSeries(IChartDataCell value)](#addDataPointForHistogramSeries-com.aspose.slides.IChartDataCell-) | نقطه دادهٔ جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. |
| [addDataPointForFunnelSeries(IChartDataCell value)](#addDataPointForFunnelSeries-com.aspose.slides.IChartDataCell-) | نقطه دادهٔ جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. |
| [addDataPointForMapSeries(IChartDataCell value)](#addDataPointForMapSeries-com.aspose.slides.IChartDataCell-) | نقطه دادهٔ جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. |
| [clear()](#clear--) | همهٔ عناصر را از مجموعه حذف می‌کند. |
| [remove(IChartDataPoint value)](#remove-com.aspose.slides.IChartDataPoint-) | مقدار مشخص‌شده را حذف می‌کند. |
| [removeAt(int index)](#removeAt-int-) | عنصر را در اندیس داده شده حذف می‌کند. |

### get_Item(int index) {#get-Item-int-}
```
public final IChartDataPoint get_Item(int index)
```

نقطه دادهٔ سری را بر اساس اندیس (شماره سریالی آن در این مجموعه) برمی‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int |  |

**بازگشت:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint)

### get_Item(IChartDataPoint pt) {#get-Item-com.aspose.slides.IChartDataPoint-}
```
public final int get_Item(IChartDataPoint pt)
```

اندیس (شماره سریالی) نقطه داده را در این مجموعه برمی‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| pt | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) |  |

**بازگشت:**
int

### getDataSourceTypeForXValues() {#getDataSourceTypeForXValues--}
```
public final int getDataSourceTypeForXValues()
```

مشخص می‌کند که آیا ویژگی AsCell یا AsLiteralString یا AsLiteralDouble در شیء ویژگی XValue نقاط داده واقعی است. به عبارت دیگر نوع مقدار ویژگی ChartDataPoint.XValue.Data را مشخص می‌کند. خواندنی/نوشتنی [DataSourceType](../../com.aspose.slides/datasourcetype).

**بازگشت:**
int

### setDataSourceTypeForXValues(int value) {#setDataSourceTypeForXValues-int-}
```
public final void setDataSourceTypeForXValues(int value)
```

مشخص می‌کند که آیا ویژگی AsCell یا AsLiteralString یا AsLiteralDouble در شیء ویژگی XValue نقاط داده واقعی است. به عبارت دیگر نوع مقدار ویژگی ChartDataPoint.XValue.Data را مشخص می‌کند. خواندنی/نوشتنی [DataSourceType](../../com.aspose.slides/datasourcetype).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForYValues() {#getDataSourceTypeForYValues--}
```
public final int getDataSourceTypeForYValues()
```

مشخص می‌کند که آیا ویژگی AsCell یا AsLiteralString یا AsLiteralDouble در شیء ویژگی YValue نقاط داده واقعی است. به عبارت دیگر نوع مقدار ویژگی ChartDataPoint.YValue.Data را مشخص می‌کند. خواندنی/نوشتنی [DataSourceType](../../com.aspose.slides/datasourcetype).

**بازگشت:**
int

### setDataSourceTypeForYValues(int value) {#setDataSourceTypeForYValues-int-}
```
public final void setDataSourceTypeForYValues(int value)
```

مشخص می‌کند که آیا ویژگی AsCell یا AsLiteralString یا AsLiteralDouble در شیء ویژگی YValue نقاط داده واقعی است. به عبارت دیگر نوع مقدار ویژگی ChartDataPoint.YValue.Data را مشخص می‌کند. خواندنی/نوشتنی [DataSourceType](../../com.aspose.slides/datasourcetype).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForBubbleSizes() {#getDataSourceTypeForBubbleSizes--}
```
public final int getDataSourceTypeForBubbleSizes()
```

مشخص می‌کند که آیا ویژگی AsCell یا AsLiteralString یا AsLiteralDouble در شیء ویژگی BubbleSize نقاط داده واقعی است. به عبارت دیگر نوع مقدار ویژگی ChartDataPoint.BubbleSize.Data را مشخص می‌کند. خواندنی/نوشتنی [DataSourceType](../../com.aspose.slides/datasourcetype).

**بازگشت:**
int

### setDataSourceTypeForBubbleSizes(int value) {#setDataSourceTypeForBubbleSizes-int-}
```
public final void setDataSourceTypeForBubbleSizes(int value)
```

مشخص می‌کند که آیا ویژگی AsCell یا AsLiteralString یا AsLiteralDouble در شیء ویژگی BubbleSize نقاط داده واقعی است. به عبارت دیگر نوع مقدار ویژگی ChartDataPoint.BubbleSize.Data را مشخص می‌کند. خواندنی/نوشتنی [DataSourceType](../../com.aspose.slides/datasourcetype).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForValues() {#getDataSourceTypeForValues--}
```
public final int getDataSourceTypeForValues()
```

مشخص می‌کند که آیا ویژگی AsCell یا AsLiteralString یا AsLiteralDouble در شیء ویژگی Value نقاط داده واقعی است. به عبارت دیگر نوع مقدار ویژگی ChartDataPoint.Value.Data را مشخص می‌کند. خواندنی/نوشتنی [DataSourceType](../../com.aspose.slides/datasourcetype).

**بازگشت:**
int

### setDataSourceTypeForValues(int value) {#setDataSourceTypeForValues-int-}
```
public final void setDataSourceTypeForValues(int value)
```

مشخص می‌کند که آیا ویژگی AsCell یا AsLiteralString یا AsLiteralDouble در شیء ویژگی Value نقاط داده واقعی است. به عبارت دیگر نوع مقدار ویژگی ChartDataPoint.Value.Data را مشخص می‌کند. خواندنی/نوشتنی [DataSourceType](../../com.aspose.slides/datasourcetype).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForErrorBarsCustomValues() {#getDataSourceTypeForErrorBarsCustomValues--}
```
public final IDataSourceTypeForErrorBarsCustomValues getDataSourceTypeForErrorBarsCustomValues()
```

نوع مقادیر را در فهرست ویژگی‌های ChartDataPoint.ErrorBarsCustomValues مشخص می‌کند. فقط خواندنی [IDataSourceTypeForErrorBarsCustomValues](../../com.aspose.slides/idatasourcetypeforerrorbarscustomvalues).

**بازگشت:**
[IDataSourceTypeForErrorBarsCustomValues](../../com.aspose.slides/idatasourcetypeforerrorbarscustomvalues)

### getOrCreateDataPointByIdx(long index) {#getOrCreateDataPointByIdx-long-}
```
public final IChartDataPoint getOrCreateDataPointByIdx(long index)
```

اگر مجموعه قبلاً نقطه داده‌ای با اندیس index داشته باشد، آن نقطه داده را برمی‌گرداند. اگر مجموعه نقطه داده‌ای با اندیس index==N نداشته باشد (زمانی که تعداد نقاط داده در این مجموعه کمتر یا مساوی N است) نقاط داده کمبود اضافه می‌شوند و آخرین نقطه (که اندیس درخواست‌شده را دارد) برگردانده می‌شود. برای مثال، اندیس‌های مجموعه \{0, 1, 2\} هستند و اندیس درخواست‌شده 5 است. سپس متد نقاط کمبود \{0, 1, 2, 3, 4, 5\} را اضافه می‌کند و نقطه دادهٔ با اندیس 5 را برمی‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | long | اندیس. |

**بازگشت:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه دادهٔ با اندیس درخواست‌شده را برمی‌گرداند.

### size() {#size--}
```
public final int size()
```

تعداد عناصری که واقعا در مجموعه وجود دارند را برمی‌دارد. فقط خواندنی int.

**بازگشت:**
int

### copyTo(System.Array array, int arrayIndex) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int arrayIndex)
```

به آرایهٔ مشخص‌شده کپی می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | آرایه‌ای که به آن کپی می‌شود. |
| arrayIndex | int | اندیسی که کپی کردن از آن آغاز می‌شود. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

مقداری را برمی‌گرداند که نشان می‌دهد دسترسی به مجموعه همگام‌سازی شده (امن برای چندرشته‌ای) است. فقط خواندنی boolean.

**بازگشت:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

ریشهٔ همگام‌سازی را برمی‌گرداند. فقط خواندنی Object.

**بازگشت:**
java.lang.Object

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataPoint> iterator()
```

یک شمارندهٔ که از طریق مجموعه تکرار می‌کند را برمی‌گرداند.

**بازگشت:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataPoint> - یک IGenericEnumerator که می‌توان از آن برای تکرار در مجموعه استفاده کرد.

### iteratorJava() {#iteratorJava--}
```
public  \  \  \  \  \  \  \ 
```

یک iterator جاوا برای کل مجموعه را برمی‌گرداند.

**بازگشت:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataPoint> - یک java.util.Iterator برای کل مجموعه.

### addDataPointForStockSeries(IChartDataCell value) {#addDataPointForStockSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForStockSeries(IChartDataCell value)
```

نقطه دادهٔ جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. برای سری‌هایی که chartType یکی از زیرنوع‌های Stock است کاربرد دارد (همچنین به متد [ChartTypeCharacterizer.isChartTypeStock(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeStock-int-) مراجعه کنید).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | مقدار نقطه داده. |

**بازگشت:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه دادهٔ جدید.

### addDataPointForStockSeries(double value) {#addDataPointForStockSeries-double-}
```
public final IChartDataPoint addDataPointForStockSeries(double value)
```

نقطه دادهٔ جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. برای سری‌هایی که chartType یکی از زیرنوع‌های Stock است کاربرد دارد (همچنین به متد [ChartTypeCharacterizer.isChartTypeStock(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeStock-int-) مراجعه کنید).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | double | مقدار نقطه داده. |

**بازگشت:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه دادهٔ جدید.

### addDataPointForLineSeries(IChartDataCell value) {#addDataPointForLineSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForLineSeries(IChartDataCell value)
```

نقطه دادهٔ جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. برای سری‌هایی که chartType یکی از زیرنوع‌های Line است کاربرد دارد (همچنین به متد [ChartTypeCharacterizer.isChartTypeLine(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeLine-int-) مراجعه کنید).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | مقدار نقطه داده. |

**بازگشت:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه دادهٔ جدید.

### addDataPointForLineSeries(double value) {#addDataPointForLineSeries-double-}
```
public final IChartDataPoint addDataPointForLineSeries(double value)
```

نقطه دادهٔ جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. برای سری‌هایی که chartType یکی از زیرنوع‌های Line است کاربرد دارد (همچنین به متد [ChartTypeCharacterizer.isChartTypeLine(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeLine-int-) مراجعه کنید).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | double | مقدار نقطه داده. |

**بازگشت:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه دادهٔ جدید.

### addDataPointForScatterSeries(IChartDataCell xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForScatterSeries(IChartDataCell xValue, IChartDataCell yValue)
```

نقطه دادهٔ جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. برای سری‌هایی که chartType یکی از زیرنوع‌های Scatter است کاربرد دارد (همچنین به متد [ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-) مراجعه کنید).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | XValue نقطه داده |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | YValue نقطه داده |

**بازگشت:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه دادهٔ جدید.

### addDataPointForScatterSeries(double xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-double-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForScatterSeries(double xValue, IChartDataCell yValue)
```

نقطه دادهٔ جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. برای سری‌هایی که chartType یکی از زیرنوع‌های Scatter است کاربرد دارد (همچنین به متد [ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-) مراجعه کنید).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| xValue | double | XValue نقطه داده |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | YValue نقطه داده |

**بازگشت:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه دادهٔ جدید.

### addDataPointForScatterSeries(String xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-java.lang.String-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForScatterSeries(String xValue, IChartDataCell yValue)
```

نقطه دادهٔ جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. برای سری‌هایی که chartType یکی از زیرنوع‌های Scatter است کاربرد دارد (همچنین به متد [ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-) مراجعه کنید).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| xValue | java.lang.String | XValue نقطه داده |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | YValue نقطه داده |

**بازگشت:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه دادهٔ جدید.

### addDataPointForScatterSeries(IChartDataCell xValue, double yValue) {#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-double-}
```
public final IChartDataPoint addDataPointForScatterSeries(IChartDataCell xValue, double yValue)
```

نقطه دادهٔ جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. برای سری‌هایی که chartType یکی از زیرنوع‌های Scatter است کاربرد دارد (همچنین به متد [ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-) مراجعه کنید).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | XValue نقطه داده |
| yValue | double | YValue نقطه داده |

**بازگشت:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه دادهٔ جدید.

### addDataPointForScatterSeries(double xValue, double yValue) {#addDataPointForScatterSeries-double-double-}
```
public final IChartDataPoint addDataPointForScatterSeries(double xValue, double yValue)
```

نقطه دادهٔ جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. برای سری‌هایی که chartType یکی از زیرنوع‌های Scatter است کاربرد دارد (همچنین به متد [ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-) مراجعه کنید).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| xValue | double | XValue نقطه داده |
| yValue | double | YValue نقطه داده |

**بازگشت:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه دادهٔ جدید.

### addDataPointForScatterSeries(String xValue, double yValue) {#addDataPointForScatterSeries-java.lang.String-double-}
```
public final IChartDataPoint addDataPointForScatterSeries(String xValue, double yValue)
```

نقطه دادهٔ جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. برای سری‌هایی که chartType یکی از زیرنوع‌های Scatter است کاربرد دارد (همچنین به متد [ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-) مراجعه کنید).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| xValue | java.lang.String | XValue نقطه داده |
| yValue | double | YValue نقطه داده |

**بازگشت:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه دادهٔ جدید.

### addDataPointForRadarSeries(IChartDataCell value) {#addDataPointForRadarSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForRadarSeries(IChartDataCell value)
```

نقطه دادهٔ جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. برای سری‌هایی که chartType یکی از زیرنوع‌های Radar است کاربرد دارد (همچنین به متد [ChartTypeCharacterizer.isChartTypeRadar(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeRadar-int-) مراجعه کنید).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | مقدار نقطه داده |

**بازگشت:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه دادهٔ جدید.

### addDataPointForRadarSeries(double value) {#addDataPointForRadarSeries-double-}
```
public final IChartDataPoint addDataPointForRadarSeries(double value)
```

نقطه دادهٔ جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. برای سری‌هایی که chartType یکی از زیرنوع‌های Radar است کاربرد دارد (همچنین به متد [ChartTypeCharacterizer.isChartTypeRadar(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeRadar-int-) مراجعه کنید).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | double | مقدار نقطه داده |

**بازگشت:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه دادهٔ جدید.

### addDataPointForBarSeries(IChartDataCell value) {#addDataPointForBarSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBarSeries(IChartDataCell value)
```

نقطه دادهٔ جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. برای سری‌هایی که chartType یکی از زیرنوع‌های Column یا Bar است کاربرد دارد (همچنین به متدهای [ChartTypeCharacterizer.isChartTypeColumn(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeColumn-int-) و [ChartTypeCharacterizer.isChartTypeBar(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBar-int-) مراجعه کنید).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | مقدار نقطه داده |

**بازگشت:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه دادهٔ جدید.

### addDataPointForBarSeries(double value) {#addDataPointForBarSeries-double-}
```
public final IChartDataPoint addDataPointForBarSeries(double value)
```

نقطه دادهٔ جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. برای سری‌هایی که chartType یکی از زیرنوع‌های Column یا Bar است کاربرد دارد (همچنین به متدهای [ChartTypeCharacterizer.isChartTypeColumn(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeColumn-int-) و [ChartTypeCharacterizer.isChartTypeBar(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBar-int-) مراجعه کنید).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | double | مقدار نقطه داده |

**بازگشت:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه دادهٔ جدید.

### addDataPointForAreaSeries(IChartDataCell value) {#addDataPointForAreaSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForAreaSeries(IChartDataCell value)
```

نقطه دادهٔ جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. برای سری‌هایی که chartType یکی از زیرنوع‌های Area است کاربرد دارد (همچنین به متد [ChartTypeCharacterizer.isChartTypeArea(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeArea-int-) مراجعه کنید).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | مقدار نقطه داده |

**بازگشت:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه دادهٔ جدید.

### addDataPointForAreaSeries(double value) {#addDataPointForAreaSeries-double-}
```
public final IChartDataPoint addDataPointForAreaSeries(double value)
```

نقطه دادهٔ جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. برای سری‌هایی که chartType یکی از زیرنوع‌های Area است کاربرد دارد (همچنین به متد [ChartTypeCharacterizer.isChartTypeArea(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeArea-int-) مراجعه کنید).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | double | مقدار نقطه داده |

**بازگشت:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه دادهٔ جدید.

### addDataPointForPieSeries(IChartDataCell value) {#addDataPointForPieSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForPieSeries(IChartDataCell value)
```

نقطه دادهٔ جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. برای سری‌هایی که chartType یکی از زیرنوع‌های Pie است کاربرد دارد (همچنین به متد [ChartTypeCharacterizer.isChartTypePie(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypePie-int-) مراجعه کنید).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | مقدار نقطه داده |

**بازگشت:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه دادهٔ جدید.

### addDataPointForPieSeries(double value) {#addDataPointForPieSeries-double-}
```
public final IChartDataPoint addDataPointForPieSeries(double value)
```

نقطه دادهٔ جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. برای سری‌هایی که chartType یکی از زیرنوع‌های Pie است کاربرد دارد (همچنین به متد [ChartTypeCharacterizer.isChartTypePie(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypePie-int-) مراجعه کنید).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | double | مقدار نقطه داده |

**بازگشت:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه دادهٔ جدید.

### addDataPointForDoughnutSeries(IChartDataCell value) {#addDataPointForDoughnutSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForDoughnutSeries(IChartDataCell value)
```

نقطه دادهٔ جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. برای سری‌هایی که chartType یکی از زیرنوع‌های Doughnut است کاربرد دارد (همچنین به متد [ChartTypeCharacterizer.isChartTypeDoughnut(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeDoughnut-int-) مراجعه کنید).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | مقدار نقطه داده |

**بازگشت:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه دادهٔ جدید.

### addDataPointForDoughnutSeries(double value) {#addDataPointForDoughnutSeries-double-}
```
public final IChartDataPoint addDataPointForDoughnutSeries(double value)
```

نقطه دادهٔ جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. برای سری‌هایی که chartType یکی از زیرنوع‌های Doughnut است کاربرد دارد (همچنین به متد [ChartTypeCharacterizer.isChartTypeDoughnut(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeDoughnut-int-) مراجعه کنید).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | double | مقدار نقطه داده |

**بازگشت:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه دادهٔ جدید.

### addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```

نقطه دادهٔ جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. برای سری‌هایی که chartType یکی از زیرنوع‌های Bubble است کاربرد دارد (همچنین به متد [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) مراجعه کنید).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | XValue نقطه داده |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | YValue نقطه داده |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | BubbleSize نقطه داده |

**بازگشت:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه دادهٔ جدید.

### addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```

نقطه دادهٔ جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. برای سری‌هایی که chartType یکی از زیرنوع‌های Bubble است کاربرد دارد (همچنین به متد [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) مراجعه کنید).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| xValue | double | XValue نقطه داده |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | YValue نقطه داده |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | BubbleSize نقطه داده |

**بازگشت:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه دادهٔ جدید.

### addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```

نقطه دادهٔ جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. برای سری‌هایی که chartType یکی از زیرنوع‌های Bubble است کاربرد دارد (همچنین به متد [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) مراجعه کنید).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| xValue | java.lang.String | XValue نقطه داده |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | YValue نقطه داده |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | BubbleSize نقطه داده |

**بازگشت:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه دادهٔ جدید.

### addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, IChartDataCell bubbleSize)
```

نقطه دادهٔ جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. برای سری‌هایی که chartType یکی از زیرنوع‌های Bubble است کاربرد دارد (همچنین به متد [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) مراجعه کنید).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | XValue نقطه داده |
| yValue | double | YValue نقطه داده |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | BubbleSize نقطه داده |

**بازگشت:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه دادهٔ جدید.

### addDataPointForBubbleSeries(double xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-double-double-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(double xValue, double yValue, IChartDataCell bubbleSize)
```

نقطه دادهٔ جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. برای سری‌هایی که chartType یکی از زیرنوع‌های Bubble است کاربرد دارد (همچنین به متد [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) مراجعه کنید).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| xValue | double | XValue نقطه داده |
| yValue | double | YValue نقطه داده |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | BubbleSize نقطه داده |

**بازگشت:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه دادهٔ جدید.

### addDataPointForBubbleSeries(String xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-double-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(String xValue, double yValue, IChartDataCell bubbleSize)
```

نقطه دادهٔ جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. برای سری‌هایی که chartType یکی از زیرنوع‌های Bubble است کاربرد دارد (همچنین به متد [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) مراجعه کنید).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| xValue | java.lang.String | XValue نقطه داده |
| yValue | double | YValue نقطه داده |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | BubbleSize نقطه داده |

**بازگشت:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه دادهٔ جدید.

### addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, double bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, double bubbleSize)
```

نقطه دادهٔ جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. برای سری‌هایی که chartType یکی از زیرنوع‌های Bubble است کاربرد دارد (همچنین به متد [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) مراجعه کنید).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | XValue نقطه داده |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | YValue نقطه داده |
| bubbleSize | double | BubbleSize نقطه داده |

**بازگشت:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه دادهٔ جدید.

### addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, double bubbleSize) {#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, double bubbleSize)
```

نقطه دادهٔ جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. برای سری‌هایی که chartType یکی از زیرنوع‌های Bubble است کاربرد دارد (همچنین به متد [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) مراجعه کنید).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| xValue | double | XValue نقطه داده |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | YValue نقطه داده |
| bubbleSize | double | BubbleSize نقطه داده |

**بازگشت:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه دادهٔ جدید.

### addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, double bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, double bubbleSize)
```

نقطه دادهٔ جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. برای سری‌هایی که chartType یکی از زیرنوع‌های Bubble است کاربرد دارد (همچنین به متد [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) مراجعه کنید).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| xValue | java.lang.String | XValue نقطه داده |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | YValue نقطه داده |
| bubbleSize | double | BubbleSize نقطه داده |

**بازگشت:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه دادهٔ جدید.

### addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, double bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, double bubbleSize)
```

نقطه دادهٔ جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. برای سری‌هایی که chartType یکی از زیرنوع‌های Bubble است کاربرد دارد (همچنین به متد [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) مراجعه کنید).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | XValue نقطه داده |
| yValue | double | YValue نقطه داده |
| bubbleSize | double | BubbleSize نقطه داده |

**بازگشت:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه دادهٔ جدید.

### addDataPointForBubbleSeries(double xValue, double yValue, double bubbleSize) {#addDataPointForBubbleSeries-double-double-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(double xValue, double yValue, double bubbleSize)
```

نقطه دادهٔ جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. برای سری‌هایی که chartType یکی از زیرنوع‌های Bubble است کاربرد دارد (همچنین به متد [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) مراجعه کنید).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| xValue | double | XValue نقطه داده |
| yValue | double | YValue نقطه داده |
| bubbleSize | double | BubbleSize نقطه داده |

**بازگشت:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه دادهٔ جدید.

### addDataPointForBubbleSeries(String xValue, double yValue, double bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-double-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(String xValue, double yValue, double bubbleSize)
```

نقطه دادهٔ جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. برای سری‌هایی که chartType یکی از زیرنوع‌های Bubble است کاربرد دارد (همچنین به متد [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) مراجعه کنید).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| xValue | java.lang.String | XValue نقطه داده |
| yValue | double | YValue نقطه داده |
| bubbleSize | double | BubbleSize نقطه داده |

**بازگشت:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه دادهٔ جدید.

### addDataPointForSurfaceSeries(IChartDataCell value) {#addDataPointForSurfaceSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForSurfaceSeries(IChartDataCell value)
```

نقطه دادهٔ جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. برای سری‌هایی که chartType یکی از زیرنوع‌های Surface است کاربرد دارد (همچنین به متد [ChartTypeCharacterizer.isChartTypeSurface(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeSurface-int-) مراجعه کنید).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | مقدار نقطه داده |

**بازگشت:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه دادهٔ جدید.

### addDataPointForSurfaceSeries(double value) {#addDataPointForSurfaceSeries-double-}
```
public final IChartDataPoint addDataPointForSurfaceSeries(double value)
```

نقطه دادهٔ جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. برای سری‌هایی که chartType یکی از زیرنوع‌های Surface است کاربرد دارد (همچنین به متد [ChartTypeCharacterizer.isChartTypeSurface(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeSurface-int-) مراجعه کنید).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | double | مقدار نقطه داده |

**بازگشت:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه دادهٔ جدید.

### addDataPointForSunburstSeries(IChartDataCell sizeValue) {#addDataPointForSunburstSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForSunburstSeries(IChartDataCell sizeValue)
```

نقطه دادهٔ جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. برای سری‌هایی که chartType برابر Sunburst است کاربرد دارد.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| sizeValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | SizeValue نقطه داده |

**بازگشت:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه دادهٔ جدید.

### addDataPointForTreemapSeries(IChartDataCell sizeValue) {#addDataPointForTreemapSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForTreemapSeries(IChartDataCell sizeValue)
```

نقطه دادهٔ جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. برای سری‌هایی که chartType برابر Treemap است کاربرد دارد.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| sizeValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | SizeValue نقطه داده |

**بازگشت:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه دادهٔ جدید.

### addDataPointForBoxAndWhiskerSeries(IChartDataCell value) {#addDataPointForBoxAndWhiskerSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBoxAndWhiskerSeries(IChartDataCell value)
```

نقطه دادهٔ جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. برای سری‌هایی که chartType برابر BoxAndWhisker است کاربرد دارد.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | مقدار نقطه داده |

**بازگشت:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه دادهٔ جدید.

### addDataPointForWaterfallSeries(IChartDataCell value) {#addDataPointForWaterfallSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForWaterfallSeries(IChartDataCell value)
```

نقطه دادهٔ جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. برای سری‌هایی که chartType برابر Waterfall است کاربرد دارد.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | مقدار نقطه داده |

**بازگشت:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه دادهٔ جدید.

### addDataPointForHistogramSeries(IChartDataCell value) {#addDataPointForHistogramSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForHistogramSeries(IChartDataCell value)
```

نقطه دادهٔ جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. برای سری‌هایی که chartType برابر Histogram است کاربرد دارد.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | مقدار نقطه داده |

**بازگشت:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه دادهٔ جدید.

### addDataPointForFunnelSeries(IChartDataCell value) {#addDataPointForFunnelSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForFunnelSeries(IChartDataCell value)
```

نقطه دادهٔ جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. برای سری‌هایی که chartType برابر Funnel است کاربرد دارد.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | مقدار نقطه داده |

**بازگشت:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه دادهٔ جدید.

### addDataPointForMapSeries(IChartDataCell value) {#addDataPointForMapSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForMapSeries(IChartDataCell value)
```

نقطه دادهٔ جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. برای سری‌هایی که chartType برابر Map است کاربرد دارد.

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
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | ColorValue نقطه داده |

**بازگشت:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه دادهٔ جدید.

### clear() {#clear--}
```
public final void clear()
```

همهٔ عناصر را از مجموعه حذف می‌کند.

### remove(IChartDataPoint value) {#remove-com.aspose.slides.IChartDataPoint-}
```
public final void remove(IChartDataPoint value)
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

عنصر را در اندیس داده شده حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | اندیس نقطه داده برای حذف. |