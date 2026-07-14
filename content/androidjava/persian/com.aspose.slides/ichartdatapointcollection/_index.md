---
title: IChartDataPointCollection
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: نمایانگر مجموعه‌ای از یک نقطه داده سری.
type: docs
url: /fa/com.aspose.slides/ichartdatapointcollection/
---
**تمام رابط‌های پیاده‌سازی شده:**
com.aspose.slides.IGenericCollection
```
public interface IChartDataPointCollection extends IGenericCollection<IChartDataPoint>
```

نمایانگر مجموعه‌ای از یک نقطه داده سری است.
## متدها

| متد | توضیح |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | نقطه داده سری را بر اساس اندیس (شماره ترتیبی آن در این مجموعه) باز می‌گرداند. |
| [get_Item(IChartDataPoint pt)](#get-Item-com.aspose.slides.IChartDataPoint-) | شماره اندیس (شماره ترتیبی در این مجموعه) نقطه داده در این مجموعه را باز می‌گرداند. |
| [getDataSourceTypeForXValues()](#getDataSourceTypeForXValues--) | مشخص می‌کند که آیا ویژگی AsCell یا AsLiteralString یا AsLiteralDouble در شیء ویژگی XValue نقاط داده واقعی است. |
| [setDataSourceTypeForXValues(int value)](#setDataSourceTypeForXValues-int-) | مشخص می‌کند که آیا ویژگی AsCell یا AsLiteralString یا AsLiteralDouble در شیء ویژگی XValue نقاط داده واقعی است. |
| [getDataSourceTypeForYValues()](#getDataSourceTypeForYValues--) | مشخص می‌کند که آیا ویژگی AsCell یا AsLiteralString یا AsLiteralDouble در شیء ویژگی YValue نقاط داده واقعی است. |
| [setDataSourceTypeForYValues(int value)](#setDataSourceTypeForYValues-int-) | مشخص می‌کند که آیا ویژگی AsCell یا AsLiteralString یا AsLiteralDouble در شیء ویژگی YValue نقاط داده واقعی است. |
| [getDataSourceTypeForBubbleSizes()](#getDataSourceTypeForBubbleSizes--) | مشخص می‌کند که آیا ویژگی AsCell یا AsLiteralString یا AsLiteralDouble در شیء ویژگی BubbleSize نقاط داده واقعی است. |
| [setDataSourceTypeForBubbleSizes(int value)](#setDataSourceTypeForBubbleSizes-int-) | مشخص می‌کند که آیا ویژگی AsCell یا AsLiteralString یا AsLiteralDouble در شیء ویژگی BubbleSize نقاط داده واقعی است. |
| [getDataSourceTypeForValues()](#getDataSourceTypeForValues--) | مشخص می‌کند که آیا ویژگی AsCell یا AsLiteralString یا AsLiteralDouble در شیء ویژگی Value نقاط داده واقعی است. |
| [setDataSourceTypeForValues(int value)](#setDataSourceTypeForValues-int-) | مشخص می‌کند که آیا ویژگی AsCell یا AsLiteralString یا AsLiteralDouble در شیء ویژگی Value نقاط داده واقعی است. |
| [getDataSourceTypeForErrorBarsCustomValues()](#getDataSourceTypeForErrorBarsCustomValues--) | نوع مقادیر در فهرست ویژگی‌های ChartDataPoint.ErrorBarsCustomValues را مشخص می‌کند. |
| [getOrCreateDataPointByIdx(long index)](#getOrCreateDataPointByIdx-long-) | اگر مجموعه قبلاً نقطه داده‌ای با اندیس index داشته باشد، این نقطه داده را باز می‌گرداند. |
| [addDataPointForStockSeries(IChartDataCell value)](#addDataPointForStockSeries-com.aspose.slides.IChartDataCell-) | نقطه داده جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. |
| [addDataPointForStockSeries(double value)](#addDataPointForStockSeries-double-) | نقطه داده جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. |
| [addDataPointForLineSeries(IChartDataCell value)](#addDataPointForLineSeries-com.aspose.slides.IChartDataCell-) | نقطه داده جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. |
| [addDataPointForLineSeries(double value)](#addDataPointForLineSeries-double-) | نقطه داده جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. |
| [addDataPointForScatterSeries(IChartDataCell xValue, IChartDataCell yValue)](#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | نقطه داده جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. |
| [addDataPointForScatterSeries(double xValue, IChartDataCell yValue)](#addDataPointForScatterSeries-double-com.aspose.slides.IChartDataCell-) | نقطه داده جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. |
| [addDataPointForScatterSeries(String xValue, IChartDataCell yValue)](#addDataPointForScatterSeries-java.lang.String-com.aspose.slides.IChartDataCell-) | نقطه داده جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. |
| [addDataPointForScatterSeries(IChartDataCell xValue, double yValue)](#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-double-) | نقطه داده جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. |
| [addDataPointForScatterSeries(double xValue, double yValue)](#addDataPointForScatterSeries-double-double-) | نقطه داده جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. |
| [addDataPointForScatterSeries(String xValue, double yValue)](#addDataPointForScatterSeries-java.lang.String-double-) | نقطه داده جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. |
| [addDataPointForRadarSeries(IChartDataCell value)](#addDataPointForRadarSeries-com.aspose.slides.IChartDataCell-) | نقطه داده جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. |
| [addDataPointForRadarSeries(double value)](#addDataPointForRadarSeries-double-) | نقطه داده جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. |
| [addDataPointForBarSeries(IChartDataCell value)](#addDataPointForBarSeries-com.aspose.slides.IChartDataCell-) | نقطه داده جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. |
| [addDataPointForBarSeries(double value)](#addDataPointForBarSeries-double-) | نقطه داده جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. |
| [addDataPointForAreaSeries(IChartDataCell value)](#addDataPointForAreaSeries-com.aspose.slides.IChartDataCell-) | نقطه داده جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. |
| [addDataPointForAreaSeries(double value)](#addDataPointForAreaSeries-double-) | نقطه داده جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. |
| [addDataPointForPieSeries(IChartDataCell value)](#addDataPointForPieSeries-com.aspose.slides.IChartDataCell-) | نقطه داده جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. |
| [addDataPointForPieSeries(double value)](#addDataPointForPieSeries-double-) | نقطه داده جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. |
| [addDataPointForDoughnutSeries(IChartDataCell value)](#addDataPointForDoughnutSeries-com.aspose.slides.IChartDataCell-) | نقطه داده جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. |
| [addDataPointForDoughnutSeries(double value)](#addDataPointForDoughnutSeries-double-) | نقطه داده جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. |
| [addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | نقطه داده جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. |
| [addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | نقطه داده جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. |
| [addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | نقطه داده جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. |
| [addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-com.aspose.slides.IChartDataCell-) | نقطه داده جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. |
| [addDataPointForBubbleSeries(double xValue, double yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-double-double-com.aspose.slides.IChartDataCell-) | نقطه داده جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. |
| [addDataPointForBubbleSeries(String xValue, double yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-double-com.aspose.slides.IChartDataCell-) | نقطه داده جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. |
| [addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, double bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-double-) | نقطه داده جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. |
| [addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, double bubbleSize)](#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-double-) | نقطه داده جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. |
| [addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, double bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-double-) | نقطه داده جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. |
| [addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, double bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-double-) | نقطه داده جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. |
| [addDataPointForBubbleSeries(double xValue, double yValue, double bubbleSize)](#addDataPointForBubbleSeries-double-double-double-) | نقطه داده جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. |
| [addDataPointForBubbleSeries(String xValue, double yValue, double bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-double-double-) | نقطه داده جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. |
| [addDataPointForSurfaceSeries(IChartDataCell value)](#addDataPointForSurfaceSeries-com.aspose.slides.IChartDataCell-) | نقطه داده جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. |
| [addDataPointForSurfaceSeries(double value)](#addDataPointForSurfaceSeries-double-) | نقطه داده جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. |
| [addDataPointForSunburstSeries(IChartDataCell sizeValue)](#addDataPointForSunburstSeries-com.aspose.slides.IChartDataCell-) | نقطه داده جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. |
| [addDataPointForWaterfallSeries(IChartDataCell value)](#addDataPointForWaterfallSeries-com.aspose.slides.IChartDataCell-) | نقطه داده جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. |
| [addDataPointForBoxAndWhiskerSeries(IChartDataCell value)](#addDataPointForBoxAndWhiskerSeries-com.aspose.slides.IChartDataCell-) | نقطه داده جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. |
| [addDataPointForTreemapSeries(IChartDataCell sizeValue)](#addDataPointForTreemapSeries-com.aspose.slides.IChartDataCell-) | نقطه داده جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. |
| [addDataPointForHistogramSeries(IChartDataCell value)](#addDataPointForHistogramSeries-com.aspose.slides.IChartDataCell-) | نقطه داده جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. |
| [addDataPointForFunnelSeries(IChartDataCell value)](#addDataPointForFunnelSeries-com.aspose.slides.IChartDataCell-) | نقطه داده جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. |
| [addDataPointForMapSeries(IChartDataCell value)](#addDataPointForMapSeries-com.aspose.slides.IChartDataCell-) | نقطه داده جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. |
| [clear()](#clear--) | تمام عناصر را از مجموعه حذف می‌کند. |
| [remove(IChartDataPoint value)](#remove-com.aspose.slides.IChartDataPoint-) | مقدار مشخص‌شده را حذف می‌کند. |
| [removeAt(int index)](#removeAt-int-) | عنصر را در اندیس داده‌شده حذف می‌کند. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IChartDataPoint get_Item(int index)
```

نقطه داده سری را بر اساس اندیس (شماره ترتیبی آن در این مجموعه) باز می‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int |  |

**باز می‌گردد:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint)
### get_Item(IChartDataPoint pt) {#get-Item-com.aspose.slides.IChartDataPoint-}
```
public abstract int get_Item(IChartDataPoint pt)
```

شماره اندیس (شماره ترتیبی در این مجموعه) نقطه داده در این مجموعه را باز می‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| pt | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) |  |

**باز می‌گردد:**
int
### getDataSourceTypeForXValues() {#getDataSourceTypeForXValues--}
```
public abstract int getDataSourceTypeForXValues()
```

مشخص می‌کند که آیا ویژگی AsCell یا AsLiteralString یا AsLiteralDouble در شیء ویژگی XValue نقاط داده واقعی است. به عبارت دیگر نوع مقدار ویژگی ChartDataPointEx.XValue.Data را مشخص می‌کند. قابل نوشتن [DataSourceType](../../com.aspose.slides/datasourcetype).

**باز می‌گردد:**
int
### setDataSourceTypeForXValues(int value) {#setDataSourceTypeForXValues-int-}
```
public abstract void setDataSourceTypeForXValues(int value)
```

مشخص می‌کند که آیا ویژگی AsCell یا AsLiteralString یا AsLiteralDouble در شیء ویژگی XValue نقاط داده واقعی است. به عبارت دیگر نوع مقدار ویژگی ChartDataPointEx.XValue.Data را مشخص می‌کند. قابل نوشتن [DataSourceType](../../com.aspose.slides/datasourcetype).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForYValues() {#getDataSourceTypeForYValues--}
```
public abstract int getDataSourceTypeForYValues()
```

مشخص می‌کند که آیا ویژگی AsCell یا AsLiteralString یا AsLiteralDouble در شیء ویژگی YValue نقاط داده واقعی است. به عبارت دیگر نوع مقدار ویژگی ChartDataPointEx.YValue.Data را مشخص می‌کند. قابل نوشتن [DataSourceType](../../com.aspose.slides/datasourcetype).

**باز می‌گردد:**
int
### setDataSourceTypeForYValues(int value) {#setDataSourceTypeForYValues-int-}
```
public abstract void setDataSourceTypeForYValues(int value)
```

مشخص می‌کند که آیا ویژگی AsCell یا AsLiteralString یا AsLiteralDouble در شیء ویژگی YValue نقاط داده واقعی است. به عبارت دیگر نوع مقدار ویژگی ChartDataPointEx.YValue.Data را مشخص می‌کند. قابل نوشتن [DataSourceType](../../com.aspose.slides/datasourcetype).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForBubbleSizes() {#getDataSourceTypeForBubbleSizes--}
```
public abstract int getDataSourceTypeForBubbleSizes()
```

مشخص می‌کند که آیا ویژگی AsCell یا AsLiteralString یا AsLiteralDouble در شیء ویژگی BubbleSize نقاط داده واقعی است. به عبارت دیگر نوع مقدار ویژگی ChartDataPointEx.BubbleSize.Data را مشخص می‌کند. قابل نوشتن [DataSourceType](../../com.aspose.slides/datasourcetype).

**باز می‌گردد:**
int
### setDataSourceTypeForBubbleSizes(int value) {#setDataSourceTypeForBubbleSizes-int-}
```
public abstract void setDataSourceTypeForBubbleSizes(int value)
```

مشخص می‌کند که آیا ویژگی AsCell یا AsLiteralString یا AsLiteralDouble در شیء ویژگی BubbleSize نقاط داده واقعی است. به عبارت دیگر نوع مقدار ویژگی ChartDataPointEx.BubbleSize.Data را مشخص می‌کند. قابل نوشتن [DataSourceType](../../com.aspose.slides/datasourcetype).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForValues() {#getDataSourceTypeForValues--}
```
public abstract int getDataSourceTypeForValues()
```

مشخص می‌کند که آیا ویژگی AsCell یا AsLiteralString یا AsLiteralDouble در شیء ویژگی Value نقاط داده واقعی است. به عبارت دیگر نوع مقدار ویژگی ChartDataPoint.Value.Data را مشخص می‌کند. قابل نوشتن [DataSourceType](../../com.aspose.slides/datasourcetype).

**باز می‌گردد:**
int
### setDataSourceTypeForValues(int value) {#setDataSourceTypeForValues-int-}
```
public abstract void setDataSourceTypeForValues(int value)
```

مشخص می‌کند که آیا ویژگی AsCell یا AsLiteralString یا AsLiteralDouble در شیء ویژگی Value نقاط داده واقعی است. به عبارت دیگر نوع مقدار ویژگی ChartDataPoint.Value.Data را مشخص می‌کند. قابل نوشتن [DataSourceType](../../com.aspose.slides/datasourcetype).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForErrorBarsCustomValues() {#getDataSourceTypeForErrorBarsCustomValues--}
```
public abstract IDataSourceTypeForErrorBarsCustomValues getDataSourceTypeForErrorBarsCustomValues()
```

نوع مقادیر در فهرست ویژگی‌های ChartDataPoint.ErrorBarsCustomValues را مشخص می‌کند. فقط‌خواندنی [IDataSourceTypeForErrorBarsCustomValues](../../com.aspose.slides/idatasourcetypeforerrorbarscustomvalues).

**باز می‌گردد:**
[IDataSourceTypeForErrorBarsCustomValues](../../com.aspose.slides/idatasourcetypeforerrorbarscustomvalues)
### getOrCreateDataPointByIdx(long index) {#getOrCreateDataPointByIdx-long-}
```
public abstract IChartDataPoint getOrCreateDataPointByIdx(long index)
```

اگر مجموعه قبلاً نقطه داده‌ای با اندیس index داشته باشد، این نقطه داده را باز می‌گرداند. اگر مجموعه نقطه داده‌ای با اندیس index==N نداشته باشد (زمانی که عدد نقاط داده در این مجموعه کمتر یا مساوی N باشد) نقطه داده‌های کمبود را اضافه می‌کند و آخرین نقطه داده (که اندیس درخواست-شده را دارد) را باز می‌گرداند. برای مثال، اندیس‌های مجموعه {0, 1, 2} هستند و اندیس درخواست‌شده 5 است. سپس متد نقاط کمبود را اضافه می‌کند: {0, 1, 2, 3, 4, 5}. و نقطه داده با اندیس 5 را باز می‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | long | اندیس. |

**باز می‌گردد:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه داده با اندیس درخواست‌شده را باز می‌گرداند.
### addDataPointForStockSeries(IChartDataCell value) {#addDataPointForStockSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForStockSeries(IChartDataCell value)
```

نقطه داده جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. برای سری‌هایی که chartType یکی از زیرنوع‌های Stock است (همچنین به متد ChartTypeCharacterizer.IsChartTypeStock(ChartType) مراجعه کنید).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | مقدار Value نقطه داده. |

**باز می‌گردد:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه داده جدید.
### addDataPointForStockSeries(double value) {#addDataPointForStockSeries-double-}
```
public abstract IChartDataPoint addDataPointForStockSeries(double value)
```

نقطه داده جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. برای سری‌هایی که chartType یکی از زیرنوع‌های Stock است (همچنین به متد ChartTypeCharacterizer.IsChartTypeStock(ChartType) مراجعه کنید).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | double | مقدار Value نقطه داده. |

**باز می‌گردد:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه داده جدید.
### addDataPointForLineSeries(IChartDataCell value) {#addDataPointForLineSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForLineSeries(IChartDataCell value)
```

نقطه داده جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. برای سری‌هایی که chartType یکی از زیرنوع‌های Line است (همچنین به متد ChartTypeCharacterizer.IsChartTypeLine(ChartType) مراجعه کنید).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | مقدار Value نقطه داده. |

**باز می‌گردد:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه داده جدید.
### addDataPointForLineSeries(double value) {#addDataPointForLineSeries-double-}
```
public abstract IChartDataPoint addDataPointForLineSeries(double value)
```

نقطه داده جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. برای سری‌هایی که chartType یکی از زیرنوع‌های Line است (همچنین به متد ChartTypeCharacterizer.IsChartTypeLine(ChartType) مراجعه کنید).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | double | مقدار Value نقطه داده. |

**باز می‌گردد:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه داده جدید.
### addDataPointForScatterSeries(IChartDataCell xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForScatterSeries(IChartDataCell xValue, IChartDataCell yValue)
```

نقطه داده جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. برای سری‌هایی که chartType یکی از زیرنوع‌های Scatter است (همچنین به متد ChartTypeCharacterizer.IsChartTypeScatter(ChartType) مراجعه کنید).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | XValue نقطه داده |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | YValue نقطه داده |

**باز می‌گردد:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه داده جدید.
### addDataPointForScatterSeries(double xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-double-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForScatterSeries(double xValue, IChartDataCell yValue)
```

نقطه داده جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. برای سری‌هایی که chartType یکی از زیرنوع‌های Scatter است (همچنین به متد ChartTypeCharacterizer.IsChartTypeScatter(ChartType) مراجعه کنید).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| xValue | double | XValue نقطه داده |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | YValue نقطه داده |

**باز می‌گردد:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه داده جدید.
### addDataPointForScatterSeries(String xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-java.lang.String-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForScatterSeries(String xValue, IChartDataCell yValue)
```

نقطه داده جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. برای سری‌هایی که chartType یکی از زیرنوع‌های Scatter است (همچنین به متد ChartTypeCharacterizer.IsChartTypeScatter(ChartType) مراجعه کنید).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| xValue | java.lang.String | XValue نقطه داده |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | YValue نقطه داده |

**باز می‌گردد:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه داده جدید.
### addDataPointForScatterSeries(IChartDataCell xValue, double yValue) {#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-double-}
```
public abstract IChartDataPoint addDataPointForScatterSeries(IChartDataCell xValue, double yValue)
```

نقطه داده جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. برای سری‌هایی که chartType یکی از زیرنوع‌های Scatter است (همچنین به متد ChartTypeCharacterizer.IsChartTypeScatter(ChartType) مراجعه کنید).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | XValue نقطه داده |
| yValue | double | YValue نقطه داده |

**باز می‌گردد:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه داده جدید.
### addDataPointForScatterSeries(double xValue, double yValue) {#addDataPointForScatterSeries-double-double-}
```
public abstract IChartDataPoint addDataPointForScatterSeries(double xValue, double yValue)
```

نقطه داده جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. برای سری‌هایی که chartType یکی از زیرنوع‌های Scatter است (همچنین به متد ChartTypeCharacterizer.IsChartTypeScatter(ChartType) مراجعه کنید).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| xValue | double | XValue نقطه داده |
| yValue | double | YValue نقطه داده |

**باز می‌گردد:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه داده جدید.
### addDataPointForScatterSeries(String xValue, double yValue) {#addDataPointForScatterSeries-java.lang.String-double-}
```
public abstract IChartDataPoint addDataPointForScatterSeries(String xValue, double yValue)
```

نقطه داده جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. برای سری‌هایی که chartType یکی از زیرنوع‌های Scatter است (همچنین به متد ChartTypeCharacterizer.IsChartTypeScatter(ChartType) مراجعه کنید).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| xValue | java.lang.String | XValue نقطه داده |
| yValue | double | YValue نقطه داده |

**باز می‌گردد:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه داده جدید.
### addDataPointForRadarSeries(IChartDataCell value) {#addDataPointForRadarSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForRadarSeries(IChartDataCell value)
```

نقطه داده جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. برای سری‌هایی که chartType یکی از زیرنوع‌های Radar است (همچنین به متد ChartTypeCharacterizer.IsChartTypeRadar(ChartType) مراجعه کنید).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | مقدار Value نقطه داده |

**باز می‌گردد:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه داده جدید.
### addDataPointForRadarSeries(double value) {#addDataPointForRadarSeries-double-}
```
public abstract IChartDataPoint addDataPointForRadarSeries(double value)
```

نقطه داده جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. برای سری‌هایی که chartType یکی از زیرنوع‌های Radar است (همچنین به متد ChartTypeCharacterizer.IsChartTypeRadar(ChartType) مراجعه کنید).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | double | مقدار Value نقطه داده |

**باز می‌گردد:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه داده جدید.
### addDataPointForBarSeries(IChartDataCell value) {#addDataPointForBarSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBarSeries(IChartDataCell value)
```

نقطه داده جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. برای سری‌هایی که chartType یکی از زیرنوع‌های Column یا Bar است (همچنین به متدهای ChartTypeCharacterizer.IsChartTypeColumn(ChartType) و ChartTypeCharacterizer.IsChartTypeBar(ChartType) مراجعه کنید).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | مقدار Value نقطه داده |

**باز می‌گردد:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه داده جدید.
### addDataPointForBarSeries(double value) {#addDataPointForBarSeries-double-}
```
public abstract IChartDataPoint addDataPointForBarSeries(double value)
```

نقطه داده جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. برای سری‌هایی که chartType یکی از زیرنوع‌های Column یا Bar است (همچنین به متدهای ChartTypeCharacterizer.IsChartTypeColumn(ChartType) و ChartTypeCharacterizer.IsChartTypeBar(ChartType) مراجعه کنید).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | double | مقدار Value نقطه داده |

**باز می‌گردد:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه داده جدید.
### addDataPointForAreaSeries(IChartDataCell value) {#addDataPointForAreaSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForAreaSeries(IChartDataCell value)
```

نقطه داده جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. برای سری‌هایی که chartType یکی از زیرنوع‌های Area است (همچنین به متد ChartTypeCharacterizer.IsChartTypeArea(ChartType) مراجعه کنید).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | مقدار Value نقطه داده |

**باز می‌گردد:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه داده جدید.
### addDataPointForAreaSeries(double value) {#addDataPointForAreaSeries-double-}
```
public abstract IChartDataPoint addDataPointForAreaSeries(double value)
```

نقطه داده جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. برای سری‌هایی که chartType یکی از زیرنوع‌های Area است (همچنین به متد ChartTypeCharacterizer.IsChartTypeArea(ChartType) مراجعه کنید).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | double | مقدار Value نقطه داده |

**باز می‌گردد:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه داده جدید.
### addDataPointForPieSeries(IChartDataCell value) {#addDataPointForPieSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForPieSeries(IChartDataCell value)
```

نقطه داده جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. برای سری‌هایی که chartType یکی از زیرنوع‌های Pie است (همچنین به متد ChartTypeCharacterizer.IsChartTypePie(ChartType) مراجعه کنید).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | مقدار Value نقطه داده |

**باز می‌گردد:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه داده جدید.
### addDataPointForPieSeries(double value) {#addDataPointForPieSeries-double-}
```
public abstract IChartDataPoint addDataPointForPieSeries(double value)
```

نقطه داده جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. برای سری‌هایی که chartType یکی از زیرنوع‌های Pie است (همچنین به متد ChartTypeCharacterizer.IsChartTypePie(ChartType) مراجعه کنید).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | double | مقدار Value نقطه داده |

**باز می‌گردد:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه داده جدید.
### addDataPointForDoughnutSeries(IChartDataCell value) {#addDataPointForDoughnutSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForDoughnutSeries(IChartDataCell value)
```

نقطه داده جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. برای سری‌هایی که chartType یکی از زیرنوع‌های Doughnut است (همچنین به متد ChartTypeCharacterizer.IsChartTypeDoughnut(ChartType) مراجعه کنید).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | مقدار Value نقطه داده |

**باز می‌گردد:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه داده جدید.
### addDataPointForDoughnutSeries(double value) {#addDataPointForDoughnutSeries-double-}
```
public abstract IChartDataPoint addDataPointForDoughnutSeries(double value)
```

نقطه داده جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. برای سری‌هایی که chartType یکی از زیرنوع‌های Doughnut است (همچنین به متد ChartTypeCharacterizer.IsChartTypeDoughnut(ChartType) مراجعه کنید).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | double | مقدار Value نقطه داده |

**باز می‌گردد:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه داده جدید.
### addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```

نقطه داده جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. برای سری‌هایی که chartType یکی از زیرنوع‌های Bubble است (همچنین به متد ChartTypeCharacterizer.IsChartTypeBubble(ChartType) مراجعه کنید).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | XValue نقطه داده |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | YValue نقطه داده |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | BubbleSize نقطه داده |

**باز می‌گردد:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه داده جدید.
### addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```

نقطه داده جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. برای سری‌هایی که chartType یکی از زیرنوع‌های Bubble است (همچنین به متد ChartTypeCharacterizer.IsChartTypeBubble(ChartType) مراجعه کنید).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| xValue | double | XValue نقطه داده |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | YValue نقطه داده |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | BubbleSize نقطه داده |

**باز می‌گردد:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه داده جدید.
### addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```

نقطه داده جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. برای سری‌هایی که chartType یکی از زیرنوع‌های Bubble است (همچنین به متد ChartTypeCharacterizer.IsChartTypeBubble(ChartType) مراجعه کنید).

**پارامترها::
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| xValue | java.lang.String | XValue نقطه داده |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | YValue نقطه داده |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | BubbleSize نقطه داده |

**باز می‌گردد:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه داده جدید.
### addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, IChartDataCell bubbleSize)
```

نقطه داده جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. برای سری‌هایی که chartType یکی از زیرنوع‌های Bubble است (همچنین به متد ChartTypeCharacterizer.IsChartTypeBubble(ChartType) مراجعه کنید).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | XValue نقطه داده |
| yValue | double | YValue نقطه داده |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | BubbleSize نقطه داده |

**باز می‌گردد:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه داده جدید.
### addDataPointForBubbleSeries(double xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-double-double-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(double xValue, double yValue, IChartDataCell bubbleSize)
```

نقطه داده جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. برای سری‌هایی که chartType یکی از زیرنوع‌های Bubble است (همچنین به متد ChartTypeCharacterizer.IsChartTypeBubble(ChartType) مراجعه کنید).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| xValue | double | XValue نقطه داده |
| yValue | double | YValue نقطه داده |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | BubbleSize نقطه داده |

**باز می‌گردد:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه داده جدید.
### addDataPointForBubbleSeries(String xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-double-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(String xValue, double yValue, IChartDataCell bubbleSize)
```

نقطه داده جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. برای سری‌هایی که chartType یکی از زیرنوع‌های Bubble است (همچنین به متد ChartTypeCharacterizer.IsChartTypeBubble(ChartType) مراجعه کنید).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| xValue | java.lang.String | XValue نقطه داده |
| yValue | double | YValue نقطه داده |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | BubbleSize نقطه داده |

**باز می‌گردد:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه داده جدید.
### addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, double bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-double-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, double bubbleSize)
```

نقطه داده جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. برای سری‌هایی که chartType یکی از زیرنوع‌های Bubble است (همچنین به متد ChartTypeCharacterizer.IsChartTypeBubble(ChartType) مراجعه کنید).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | XValue نقطه داده |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | YValue نقطه داده |
| bubbleSize | double | BubbleSize نقطه داده |

**باز می‌گردد:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه داده جدید.
### addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, double bubbleSize) {#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-double-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, double bubbleSize)
```

نقطه داده جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. برای سری‌هایی که chartType یکی از زیرنوع‌های Bubble است (همچنین به متد ChartTypeCharacterizer.IsChartTypeBubble(ChartType) مراجعه کنید).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| xValue | double | XValue نقطه داده |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | YValue نقطه داده |
| bubbleSize | double | BubbleSize نقطه داده |

**باز می‌گردد:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه داده جدید.
### addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, double bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-double-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, double bubbleSize)
```

نقطه داده جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. برای سری‌هایی که chartType یکی از زیرنوع‌های Bubble است (همچنین به متد ChartTypeCharacterizer.IsChartTypeBubble(ChartType) مراجعه کنید).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| xValue | java.lang.String | XValue نقطه داده |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | YValue نقطه داده |
| bubbleSize | double | BubbleSize نقطه داده |

**باز می‌گردد:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه داده جدید.
### addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, double bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-double-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, double bubbleSize)
```

نقطه داده جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. برای سری‌هایی که chartType یکی از زیرنوع‌های Bubble است (همچنین به متد ChartTypeCharacterizer.IsChartTypeBubble(ChartType) مراجعه کنید).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | XValue نقطه داده |
| yValue | double | YValue نقطه داده |
| bubbleSize | double | BubbleSize نقطه داده |

**باز می‌گردد:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه داده جدید.
### addDataPointForBubbleSeries(double xValue, double yValue, double bubbleSize) {#addDataPointForBubbleSeries-double-double-double-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(double xValue, double yValue, double bubbleSize)
```

نقطه داده جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. برای سری‌هایی که chartType یکی از زیرنوع‌های Bubble است (همچنین به متد ChartTypeCharacterizer.IsChartTypeBubble(ChartType) مراجعه کنید).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| xValue | double | XValue نقطه داده |
| yValue | double | YValue نقطه داده |
| bubbleSize | double | BubbleSize نقطه داده |

**باز می‌گردد:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه داده جدید.
### addDataPointForBubbleSeries(String xValue, double yValue, double bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-double-double-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(String xValue, double yValue, double bubbleSize)
```

نقطه داده جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. برای سری‌هایی که chartType یکی از زیرنوع‌های Bubble است (همچنین به متد ChartTypeCharacterizer.IsChartTypeBubble(ChartType) مراجعه کنید).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| xValue | java.lang.String | XValue نقطه داده |
| yValue | double | YValue نقطه داده |
| bubbleSize | double | BubbleSize نقطه داده |

**باز می‌گردد:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه داده جدید.
### addDataPointForSurfaceSeries(IChartDataCell value) {#addDataPointForSurfaceSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForSurfaceSeries(IChartDataCell value)
```

نقطه داده جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. برای سری‌هایی که chartType یکی از زیرنوع‌های Surface است (همچنین به متد ChartTypeCharacterizer.IsChartTypeSurface(ChartType) مراجعه کنید).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | مقدار Value نقطه داده |

**باز می‌گردد:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه داده جدید.
### addDataPointForSurfaceSeries(double value) {#addDataPointForSurfaceSeries-double-}
```
public abstract IChartDataPoint addDataPointForSurfaceSeries(double value)
```

نقطه داده جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. برای سری‌هایی که chartType یکی از زیرنوع‌های Surface است (همچنین به متد ChartTypeCharacterizer.IsChartTypeSurface(ChartType) مراجعه کنید).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | double | مقدار Value نقطه داده |

**باز می‌گردد:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه داده جدید.
### addDataPointForSunburstSeries(IChartDataCell sizeValue) {#addDataPointForSunburstSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForSunburstSeries(IChartDataCell sizeValue)
```

نقطه داده جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. برای سری‌هایی که chartType برابر Sunburst است.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| sizeValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | SizeValue نقطه داده |

**باز می‌گردد:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه داده جدید.
### addDataPointForWaterfallSeries(IChartDataCell value) {#addDataPointForWaterfallSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForWaterfallSeries(IChartDataCell value)
```

نقطه داده جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. برای سری‌هایی که chartType برابر Waterfall است.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | مقدار value نقطه داده |

**باز می‌گردد:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه داده جدید.
### addDataPointForBoxAndWhiskerSeries(IChartDataCell value) {#addDataPointForBoxAndWhiskerSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBoxAndWhiskerSeries(IChartDataCell value)
```

نقطه داده جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. برای سری‌هایی که chartType برابر BoxAndWhisker است.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | مقدار Value نقطه داده |

**باز می‌گردد:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه داده جدید.
### addDataPointForTreemapSeries(IChartDataCell sizeValue) {#addDataPointForTreemapSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForTreemapSeries(IChartDataCell sizeValue)
```

نقطه داده جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. برای سری‌هایی که chartType برابر Treemap است.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| sizeValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | SizeValue نقطه داده |

**باز می‌گردد:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه داده جدید.
### addDataPointForHistogramSeries(IChartDataCell value) {#addDataPointForHistogramSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForHistogramSeries(IChartDataCell value)
```

نقطه داده جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. برای سری‌هایی که chartType برابر Histogram است.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | مقدار value نقطه داده |

**باز می‌گردد:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه داده جدید.
### addDataPointForFunnelSeries(IChartDataCell value) {#addDataPointForFunnelSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForFunnelSeries(IChartDataCell value)
```

نقطه داده جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. برای سری‌هایی که chartType برابر Funnel است.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | مقدار value نقطه داده |

**باز می‌گردد:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه داده جدید.
### addDataPointForMapSeries(IChartDataCell value) {#addDataPointForMapSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForMapSeries(IChartDataCell value)
```

نقطه داده جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. برای سری‌هایی که chartType برابر Map است.

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

**باز می‌گردد:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه داده جدید.
### clear() {#clear--}
```
public abstract void clear()
```

تمام عناصر را از مجموعه حذف می‌کند.
### remove(IChartDataPoint value) {#remove-com.aspose.slides.IChartDataPoint-}
```
public abstract void remove(IChartDataPoint value)
```

مقدار مشخص‌شده را حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | مقدار. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

عنصر را در اندیس داده‌شده حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | اندیس نقطه داده برای حذف. |