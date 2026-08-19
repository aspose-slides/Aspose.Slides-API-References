---
title: IChartDataPointCollection
second_title: مرجع API Aspose.Slides برای جاوا
description: نمایانگر مجموعه‌ای از نقاط داده یک سری.
type: docs
url: /fa/com.aspose.slides/ichartdatapointcollection/
---
**همهٔ رابط‌های پیاده‌سازی‌شده:**
com.aspose.slides.IGenericCollection
```
public interface IChartDataPointCollection extends IGenericCollection<IChartDataPoint>
```

نمایش مجموعه‌ای از نقطه دادهٔ سری.

## متدها

| متد | توضیح |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | نقطه دادهٔ سری را براساس شاخص (شمارهٔ سریال آن در این مجموعه) برمی‌گرداند. |
| [get_Item(IChartDataPoint pt)](#get-Item-com.aspose.slides.IChartDataPoint-) | شاخص (شمارهٔ سریال در این مجموعه) نقطه داده در این مجموعه را برمی‌گرداند. |
| [getDataSourceTypeForXValues()](#getDataSourceTypeForXValues--) | مشخص می‌کند که آیا ویژگی AsCell یا AsLiteralString یا AsLiteralDouble در شیء ویژگی XValue نقاط داده واقعی است. |
| [setDataSourceTypeForXValues(int value)](#setDataSourceTypeForXValues-int-) | مشخص می‌کند که آیا ویژگی AsCell یا AsLiteralString یا AsLiteralDouble در شیء ویژگی XValue نقاط داده واقعی است. |
| [getDataSourceTypeForYValues()](#getDataSourceTypeForYValues--) | مشخص می‌کند که آیا ویژگی AsCell یا AsLiteralString یا AsLiteralDouble در شیء ویژگی YValue نقاط داده واقعی است. |
| [setDataSourceTypeForYValues(int value)](#setDataSourceTypeForYValues-int-) | مشخص می‌کند که آیا ویژگی AsCell یا AsLiteralString یا AsLiteralDouble در شیء ویژگی YValue نقاط داده واقعی است. |
| [getDataSourceTypeForBubbleSizes()](#getDataSourceTypeForBubbleSizes--) | مشخص می‌کند که آیا ویژگی AsCell یا AsLiteralString یا AsLiteralDouble در شیء ویژگی BubbleSize نقاط داده واقعی است. |
| [setDataSourceTypeForBubbleSizes(int value)](#setDataSourceTypeForBubbleSizes-int-) | مشخص می‌کند که آیا ویژگی AsCell یا AsLiteralString یا AsLiteralDouble در شیء ویژگی BubbleSize نقاط داده واقعی است. |
| [getDataSourceTypeForValues()](#getDataSourceTypeForValues--) | مشخص می‌کند که آیا ویژگی AsCell یا AsLiteralString یا AsLiteralDouble در شیء ویژگی Value نقاط داده واقعی است. |
| [setDataSourceTypeForValues(int value)](#setDataSourceTypeForValues-int-) | مشخص می‌کند که آیا ویژگی AsCell یا AsLiteralString یا AsLiteralDouble در شیء ویژگی Value نقاط داده واقعی است. |
| [getDataSourceTypeForErrorBarsCustomValues()](#getDataSourceTypeForErrorBarsCustomValues--) | نوع مقادیر در فهرست ویژگی‌های ChartDataPoint.ErrorBarsCustomValues را مشخص می‌کند. |
| [getOrCreateDataPointByIdx(long index)](#getOrCreateDataPointByIdx-long-) | اگر مجموعه قبلاً نقطه داده‌ای با شاخص index داشته باشد، این نقطه داده را برمی‌گرداند. |
| [addDataPointForStockSeries(IChartDataCell value)](#addDataPointForStockSeries-com.aspose.slides.IChartDataCell-) | یک نقطه داده جدید می‌سازد و آن را به انتهای مجموعه اضافه می‌کند. |
| [addDataPointForStockSeries(double value)](#addDataPointForStockSeries-double-) | یک نقطه داده جدید می‌سازد و آن را به انتهای مجموعه اضافه می‌کند. |
| [addDataPointForLineSeries(IChartDataCell value)](#addDataPointForLineSeries-com.aspose.slides.IChartDataCell-) | یک نقطه داده جدید می‌سازد و آن را به انتهای مجموعه اضافه می‌کند. |
| [addDataPointForLineSeries(double value)](#addDataPointForLineSeries-double-) | یک نقطه داده جدید می‌سازد و آن را به انتهای مجموعه اضافه می‌کند. |
| [addDataPointForScatterSeries(IChartDataCell xValue, IChartDataCell yValue)](#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | یک نقطه داده جدید می‌سازد و آن را به انتهای مجموعه اضافه می‌کند. |
| [addDataPointForScatterSeries(double xValue, IChartDataCell yValue)](#addDataPointForScatterSeries-double-com.aspose.slides.IChartDataCell-) | یک نقطه داده جدید می‌سازد و آن را به انتهای مجموعه اضافه می‌کند. |
| [addDataPointForScatterSeries(String xValue, IChartDataCell yValue)](#addDataPointForScatterSeries-java.lang.String-com.aspose.slides.IChartDataCell-) | یک نقطه داده جدید می‌سازد و آن را به انتهای مجموعه اضافه می‌کند. |
| [addDataPointForScatterSeries(IChartDataCell xValue, double yValue)](#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-double-) | یک نقطه داده جدید می‌سازد و آن را به انتهای مجموعه اضافه می‌کند. |
| [addDataPointForScatterSeries(double xValue, double yValue)](#addDataPointForScatterSeries-double-double-) | یک نقطه داده جدید می‌سازد و آن را به انتهای مجموعه اضافه می‌کند. |
| [addDataPointForScatterSeries(String xValue, double yValue)](#addDataPointForScatterSeries-java.lang.String-double-) | یک نقطه داده جدید می‌سازد و آن را به انتهای مجموعه اضافه می‌کند. |
| [addDataPointForRadarSeries(IChartDataCell value)](#addDataPointForRadarSeries-com.aspose.slides.IChartDataCell-) | یک نقطه داده جدید می‌سازد و آن را به انتهای مجموعه اضافه می‌کند. |
| [addDataPointForRadarSeries(double value)](#addDataPointForRadarSeries-double-) | یک نقطه داده جدید می‌سازد و آن را به انتهای مجموعه اضافه می‌کند. |
| [addDataPointForBarSeries(IChartDataCell value)](#addDataPointForBarSeries-com.aspose.slides.IChartDataCell-) | یک نقطه داده جدید می‌سازد و آن را به انتهای مجموعه اضافه می‌کند. |
| [addDataPointForBarSeries(double value)](#addDataPointForBarSeries-double-) | یک نقطه داده جدید می‌سازد و آن را به انتهای مجموعه اضافه می‌کند. |
| [addDataPointForAreaSeries(IChartDataCell value)](#addDataPointForAreaSeries-com.aspose.slides.IChartDataCell-) | یک نقطه داده جدید می‌سازد و آن را به انتهای مجموعه اضافه می‌کند. |
| [addDataPointForAreaSeries(double value)](#addDataPointForAreaSeries-double-) | یک نقطه داده جدید می‌سازد و آن را به انتهای مجموعه اضافه می‌کند. |
| [addDataPointForPieSeries(IChartDataCell value)](#addDataPointForPieSeries-com.aspose.slides.IChartDataCell-) | یک نقطه داده جدید می‌سازد و آن را به انتهای مجموعه اضافه می‌کند. |
| [addDataPointForPieSeries(double value)](#addDataPointForPieSeries-double-) | یک نقطه داده جدید می‌سازد و آن را به انتهای مجموعه اضافه می‌کند. |
| [addDataPointForDoughnutSeries(IChartDataCell value)](#addDataPointForDoughnutSeries-com.aspose.slides.IChartDataCell-) | یک نقطه داده جدید می‌سازد و آن را به انتهای مجموعه اضافه می‌کند. |
| [addDataPointForDoughnutSeries(double value)](#addDataPointForDoughnutSeries-double-) | یک نقطه داده جدید می‌سازد و آن را به انتهای مجموعه اضافه می‌کند. |
| [addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | یک نقطه داده جدید می‌سازد و آن را به انتهای مجموعه اضافه می‌کند. |
| [addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | یک نقطه داده جدید می‌سازد و آن را به انتهای مجموعه اضافه می‌کند. |
| [addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | یک نقطه داده جدید می‌سازد و آن را به انتهای مجموعه اضافه می‌کند. |
| [addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-com.aspose.slides.IChartDataCell-) | یک نقطه داده جدید می‌سازد و آن را به انتهای مجموعه اضافه می‌کند. |
| [addDataPointForBubbleSeries(double xValue, double yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-double-double-com.aspose.slides.IChartDataCell-) | یک نقطه داده جدید می‌سازد و آن را به انتهای مجموعه اضافه می‌کند. |
| [addDataPointForBubbleSeries(String xValue, double yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-double-com.aspose.slides.IChartDataCell-) | یک نقطه داده جدید می‌سازد و آن را به انتهای مجموعه اضافه می‌کند. |
| [addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, double bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-double-) | یک نقطه داده جدید می‌سازد و آن را به انتهای مجموعه اضافه می‌کند. |
| [addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, double bubbleSize)](#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-double-) | یک نقطه داده جدید می‌سازد و آن را به انتهای مجموعه اضافه می‌کند. |
| [addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, double bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-double-) | یک نقطه داده جدید می‌سازد و آن را به انتهای مجموعه اضافه می‌کند. |
| [addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, double bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-double-) | یک نقطه داده جدید می‌سازد و آن را به انتهای مجموعه اضافه می‌کند. |
| [addDataPointForBubbleSeries(double xValue, double yValue, double bubbleSize)](#addDataPointForBubbleSeries-double-double-double-) | یک نقطه داده جدید می‌سازد و آن را به انتهای مجموعه اضافه می‌کند. |
| [addDataPointForBubbleSeries(String xValue, double yValue, double bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-double-double-) | یک نقطه داده جدید می‌سازد و آن را به انتهای مجموعه اضافه می‌کند. |
| [addDataPointForSurfaceSeries(IChartDataCell value)](#addDataPointForSurfaceSeries-com.aspose.slides.IChartDataCell-) | یک نقطه داده جدید می‌سازد و آن را به انتهای مجموعه اضافه می‌کند. |
| [addDataPointForSurfaceSeries(double value)](#addDataPointForSurfaceSeries-double-) | یک نقطه داده جدید می‌سازد و آن را به انتهای مجموعه اضافه می‌کند. |
| [addDataPointForSunburstSeries(IChartDataCell sizeValue)](#addDataPointForSunburstSeries-com.aspose.slides.IChartDataCell-) | یک نقطه داده جدید می‌سازد و آن را به انتهای مجموعه اضافه می‌کند. |
| [addDataPointForWaterfallSeries(IChartDataCell value)](#addDataPointForWaterfallSeries-com.aspose.slides.IChartDataCell-) | یک نقطه داده جدید می‌سازد و آن را به انتهای مجموعه اضافه می‌کند. |
| [addDataPointForBoxAndWhiskerSeries(IChartDataCell value)](#addDataPointForBoxAndWhiskerSeries-com.aspose.slides.IChartDataCell-) | یک نقطه داده جدید می‌سازد و آن را به انتهای مجموعه اضافه می‌کند. |
| [addDataPointForTreemapSeries(IChartDataCell sizeValue)](#addDataPointForTreemapSeries-com.aspose.slides.IChartDataCell-) | یک نقطه داده جدید می‌سازد و آن را به انتهای مجموعه اضافه می‌کند. |
| [addDataPointForHistogramSeries(IChartDataCell value)](#addDataPointForHistogramSeries-com.aspose.slides.IChartDataCell-) | یک نقطه داده جدید می‌سازد و آن را به انتهای مجموعه اضافه می‌کند. |
| [addDataPointForFunnelSeries(IChartDataCell value)](#addDataPointForFunnelSeries-com.aspose.slides.IChartDataCell-) | یک نقطه داده جدید می‌سازد و آن را به انتهای مجموعه اضافه می‌کند. |
| [addDataPointForMapSeries(IChartDataCell value)](#addDataPointForMapSeries-com.aspose.slides.IChartDataCell-) | یک نقطه داده جدید می‌سازد و آن را به انتهای مجموعه اضافه می‌کند. |
| [clear()](#clear--) | تمام عناصر را از مجموعه حذف می‌کند. |
| [remove(IChartDataPoint value)](#remove-com.aspose.slides.IChartDataPoint-) | مقدار مشخص‌شده را حذف می‌کند. |
| [removeAt(int index)](#removeAt-int-) | عنصر در شاخص داده‌شده را حذف می‌کند. |

### get_Item(int index) {#get-Item-int-}
```
public abstract IChartDataPoint get_Item(int index)
```

نقطه دادهٔ سری را براساس شاخص (شمارهٔ سریال آن در این مجموعه) برمی‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int |  |

**بازگشت:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint)

### get_Item(IChartDataPoint pt) {#get-Item-com.aspose.slides.IChartDataPoint-}
```
public abstract int get_Item(IChartDataPoint pt)
```

شاخص (شمارهٔ سریال در این مجموعه) نقطه داده در این مجموعه را برمی‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| pt | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) |  |

**بازگشت:**
int

### getDataSourceTypeForXValues() {#getDataSourceTypeForXValues--}
```
public abstract int getDataSourceTypeForXValues()
```

مشخص می‌کند که آیا ویژگی AsCell یا AsLiteralString یا AsLiteralDouble در شیء ویژگی XValue نقاط داده واقعی است. به عبارتی نوع مقدار ویژگی ChartDataPointEx.XValue.Data را مشخص می‌کند. خواندنی/نوشتنی [DataSourceType](../../com.aspose.slides/datasourcetype).

**بازگشت:**
int

### setDataSourceTypeForXValues(int value) {#setDataSourceTypeForXValues-int-}
```
public abstract void setDataSourceTypeForXValues(int value)
```

مشخص می‌کند که آیا ویژگی AsCell یا AsLiteralString یا AsLiteralDouble در شیء ویژگی XValue نقاط داده واقعی است. به عبارتی نوع مقدار ویژگی ChartDataPointEx.XValue.Data را مشخص می‌کند. خواندنی/نوشتنی [DataSourceType](../../com.aspose.slides/datasourcetype).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForYValues() {#getDataSourceTypeForYValues--}
```
public abstract int getDataSourceTypeForYValues()
```

مشخص می‌کند که آیا ویژگی AsCell یا AsLiteralString یا AsLiteralDouble در شیء ویژگی YValue نقاط داده واقعی است. به عبارتی نوع مقدار ویژگی ChartDataPointEx.YValue.Data را مشخص می‌کند. خواندنی/نوشتنی [DataSourceType](../../com.aspose.slides/datasourcetype).

**بازگشت:**
int

### setDataSourceTypeForYValues(int value) {#setDataSourceTypeForYValues-int-}
```
public abstract void setDataSourceTypeForYValues(int value)
```

مشخص می‌کند که آیا ویژگی AsCell یا AsLiteralString یا AsLiteralDouble در شیء ویژگی YValue نقاط داده واقعی است. به عبارتی نوع مقدار ویژگی ChartDataPointEx.YValue.Data را مشخص می‌کند. خواندنی/نوشتنی [DataSourceType](../../com.aspose.slides/datasourcetype).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForBubbleSizes() {#getDataSourceTypeForBubbleSizes--}
```
public abstract int getDataSourceTypeForBubbleSizes()
```

مشخص می‌کند که آیا ویژگی AsCell یا AsLiteralString یا AsLiteralDouble در شیء ویژگی BubbleSize نقاط داده واقعی است. به عبارتی نوع مقدار ویژگی ChartDataPointEx.BubbleSize.Data را مشخص می‌کند. خواندنی/نوشتنی [DataSourceType](../../com.aspose.slides/datasourcetype).

**بازگشت:**
int

### setDataSourceTypeForBubbleSizes(int value) {#setDataSourceTypeForBubbleSizes-int-}
```
public abstract void setDataSourceTypeForBubbleSizes(int value)
```

مشخص می‌کند که آیا ویژگی AsCell یا AsLiteralString یا AsLiteralDouble در شیء ویژگی BubbleSize نقاط داده واقعی است. به عبارتی نوع مقدار ویژگی ChartDataPointEx.BubbleSize.Data را مشخص می‌کند. خواندنی/نوشتنی [DataSourceType](../../com.aspose.slides/datasourcetype).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForValues() {#getDataSourceTypeForValues--}
```
public abstract int getDataSourceTypeForValues()
```

مشخص می‌کند که آیا ویژگی AsCell یا AsLiteralString یا AsLiteralDouble در شیء ویژگی Value نقاط داده واقعی است. به عبارتی نوع مقدار ویژگی ChartDataPoint.Value.Data را مشخص می‌کند. خواندنی/نوشتنی [DataSourceType](../../com.aspose.slides/datasourcetype).

**بازگشت:**
int

### setDataSourceTypeForValues(int value) {#setDataSourceTypeForValues-int-}
```
public abstract void setDataSourceTypeForValues(int value)
```

مشخص می‌کند که آیا ویژگی AsCell یا AsLiteralString یا AsLiteralDouble در شیء ویژگی Value نقاط داده واقعی است. به عبارتی نوع مقدار ویژگی ChartDataPoint.Value.Data را مشخص می‌کند. خواندنی/نوشتنی [DataSourceType](../../com.aspose.slides/datasourcetype).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForErrorBarsCustomValues() {#getDataSourceTypeForErrorBarsCustomValues--}
```
public abstract IDataSourceTypeForErrorBarsCustomValues getDataSourceTypeForErrorBarsCustomValues()
```

نوع مقادیر در فهرست ویژگی‌های ChartDataPoint.ErrorBarsCustomValues را مشخص می‌کند. فقط‌خواندنی [IDataSourceTypeForErrorBarsCustomValues](../../com.aspose.slides/idatasourcetypeforerrorbarscustomvalues).

**بازگشت:**
[IDataSourceTypeForErrorBarsCustomValues](../../com.aspose.slides/idatasourcetypeforerrorbarscustomvalues)

### getOrCreateDataPointByIdx(long index) {#getOrCreateDataPointByIdx-long-}
```
public abstract IChartDataPoint getOrCreateDataPointByIdx(long index)
```

اگر مجموعه قبلاً نقطه داده‌ای با شاخص index داشته باشد، این نقطه داده را برمی‌گرداند. اگر مجموعه نقطه داده‌ای با شاخص index==N (زمانی که تعداد نقاط داده در این مجموعه کمتر یا مساوی N باشد) نداشته باشد، نقاط دادهٔ کم‌بود را اضافه کرده و آخرین نقطه (که شاخص درخواستی را دارد) را برمی‌گرداند. به عنوان مثال، شاخص‌های مجموعه \{0, 1, 2\} هستند و شاخص درخواستی 5 است. سپس متد نقاط کمبود \{0, 1, 2, 3, 4, 5\} را اضافه می‌کند و نقطه دادهٔ شاخص 5 را برمی‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | long | شاخص. |

**بازگشت:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه دادهٔ با شاخص درخواستی را برمی‌گرداند.

### addDataPointForStockSeries(IChartDataCell value) {#addDataPointForStockSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForStockSeries(IChartDataCell value)
```

یک نقطه داده جدید می‌سازد و آن را به انتهای مجموعه اضافه می‌کند. کاربردی برای سری‌هایی که chartType آنها یکی از زیرنوع‌های Stock است (همچنین به متد ChartTypeCharacterizer.IsChartTypeStock(ChartType) مراجعه کنید).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | مقدار Value نقطه داده. |

**بازگشت:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه دادهٔ جدید.

### addDataPointForStockSeries(double value) {#addDataPointForStockSeries-double-}
```
public abstract IChartDataPoint addDataPointForStockSeries(double value)
```

یک نقطه داده جدید می‌سازد و آن را به انتهای مجموعه اضافه می‌کند. کاربردی برای سری‌هایی که chartType آنها یکی از زیرنوع‌های Stock است (همچنین به متد ChartTypeCharacterizer.IsChartTypeStock(ChartType) مراجعه کنید).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | double | مقدار Value نقطه داده. |

**بازگشت:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه دادهٔ جدید.

### addDataPointForLineSeries(IChartDataCell value) {#addDataPointForLineSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForLineSeries(IChartDataCell value)
```

یک نقطه داده جدید می‌سازد و آن را به انتهای مجموعه اضافه می‌کند. کاربردی برای سری‌هایی که chartType آنها یکی از زیرنوع‌های Line است (همچنین به متد ChartTypeCharacterizer.IsChartTypeLine(ChartType) مراجعه کنید).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | مقدار Value نقطه داده. |

**بازگشت:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه دادهٔ جدید.

### addDataPointForLineSeries(double value) {#addDataPointForLineSeries-double-}
```
public abstract IChartDataPoint addDataPointForLineSeries(double value)
```

یک نقطه داده جدید می‌سازد و آن را به انتهای مجموعه اضافه می‌کند. کاربردی برای سری‌هایی که chartType آنها یکی از زیرنوع‌های Line است (همچنین به متد ChartTypeCharacterizer.IsChartTypeLine(ChartType) مراجعه کنید).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | double | مقدار Value نقطه داده. |

**بازگشت:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه دادهٔ جدید.

### addDataPointForScatterSeries(IChartDataCell xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForScatterSeries(IChartDataCell xValue, IChartDataCell yValue)
```

یک نقطه داده جدید می‌سازد و آن را به انتهای مجموعه اضافه می‌کند. کاربردی برای سری‌هایی که chartType آنها یکی از زیرنوع‌های Scatter است (همچنین به متد ChartTypeCharacterizer.IsChartTypeScatter(ChartType) مراجعه کنید).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| xValue | {{...}} | مقدار X. |
| yValue | {{...}} | مقدار Y. |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | نقطه داده XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | نقطه داده YValue |

**بازگشت:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه داده جدید.

### addDataPointForScatterSeries(double xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-double-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForScatterSeries(double xValue, IChartDataCell yValue)
```

یک نقطه داده جدید ایجاد می‌کند و آن را به انتهای مجموعه اضافه می‌نماید. برای سری‌هایی که chartType آن‌ها یکی از زیرنوع‌های Scatter است کاربرد دارد (همچنین به متد ChartTypeCharacterizer.IsChartTypeScatter(ChartType) مراجعه کنید).

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| xValue | double | نقطه داده XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | نقطه داده YValue |

**بازگشت:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه داده جدید.

### addDataPointForScatterSeries(String xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-java.lang.String-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForScatterSeries(String xValue, IChartDataCell yValue)
```

یک نقطه داده جدید ایجاد می‌کند و آن را به انتهای مجموعه اضافه می‌نماید. برای سری‌هایی که chartType آن‌ها یکی از زیرنوع‌های Scatter است کاربرد دارد (همچنین به متد ChartTypeCharacterizer.IsChartTypeScatter(ChartType) مراجعه کنید).

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| xValue | java.lang.String | نقطه داده XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | نقطه داده YValue |

**بازگشت:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه داده جدید.

### addDataPointForScatterSeries(IChartDataCell xValue, double yValue) {#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-double-}
```
public abstract IChartDataPoint addDataPointForScatterSeries(IChartDataCell xValue, double yValue)
```

یک نقطه داده جدید ایجاد می‌کند و آن را به انتهای مجموعه اضافه می‌نماید. برای سری‌هایی که chartType آن‌ها یکی از زیرنوع‌های Scatter است کاربرد دارد (همچنین به متد ChartTypeCharacterizer.IsChartTypeScatter(ChartType) مراجعه کنید).

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | نقطه داده XValue |
| yValue | double | نقطه داده YValue |

**بازگشت:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه داده جدید.

### addDataPointForScatterSeries(double xValue, double yValue) {#addDataPointForScatterSeries-double-double-}
```
public abstract IChartDataPoint addDataPointForScatterSeries(double xValue, double yValue)
```

یک نقطه داده جدید ایجاد می‌کند و آن را به انتهای مجموعه اضافه می‌نماید. برای سری‌هایی که chartType آن‌ها یکی از زیرنوع‌های Scatter است کاربرد دارد (همچنین به متد ChartTypeCharacterizer.IsChartTypeScatter(ChartType) مراجعه کنید).

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| xValue | double | نقطه داده XValue |
| yValue | double | نقطه داده YValue |

**بازگشت:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه داده جدید.

### addDataPointForScatterSeries(String xValue, double yValue) {#addDataPointForScatterSeries-java.lang.String-double-}
```
public abstract IChartDataPoint addDataPointForScatterSeries(String xValue, double yValue)
```

یک نقطه داده جدید ایجاد می‌کند و آن را به انتهای مجموعه اضافه می‌نماید. برای سری‌هایی که chartType آن‌ها یکی از زیرنوع‌های Scatter است کاربرد دارد (همچنین به متد ChartTypeCharacterizer.IsChartTypeScatter(ChartType) مراجعه کنید).

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| xValue | java.lang.String | نقطه داده XValue |
| yValue | double | نقطه داده YValue |

**بازگشت:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه داده جدید.

### addDataPointForRadarSeries(IChartDataCell value) {#addDataPointForRadarSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForRadarSeries(IChartDataCell value)
```

یک نقطه داده جدید ایجاد می‌کند و آن را به انتهای مجموعه اضافه می‌نماید. برای سری‌هایی که chartType آن‌ها یکی از زیرنوع‌های Radar است کاربرد دارد (همچنین به متد ChartTypeCharacterizer.IsChartTypeRadar(ChartType) مراجعه کنید).

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | مقدار نقطه داده |

**بازگشت:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه داده جدید.

### addDataPointForRadarSeries(double value) {#addDataPointForRadarSeries-double-}
```
public abstract IChartDataPoint addDataPointForRadarSeries(double value)
```

یک نقطه داده جدید ایجاد می‌کند و آن را به انتهای مجموعه اضافه می‌نماید. برای سری‌هایی که chartType آن‌ها یکی از زیرنوع‌های Radar است کاربرد دارد (همچنین به متد ChartTypeCharacterizer.IsChartTypeRadar(ChartType) مراجعه کنید).

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | double | مقدار نقطه داده |

**بازگشت:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه داده جدید.

### addDataPointForBarSeries(IChartDataCell value) {#addDataPointForBarSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBarSeries(IChartDataCell value)
```

یک نقطه داده جدید ایجاد می‌کند و آن را به انتهای مجموعه اضافه می‌نماید. برای سری‌هایی که chartType آن‌ها یکی از زیرنوع‌های Column یا Bar است کاربرد دارد (همچنین به متدهای ChartTypeCharacterizer.IsChartTypeColumn(ChartType) و ChartTypeCharacterizer.IsChartTypeBar(ChartType) مراجعه کنید).

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | مقدار نقطه داده |

**بازگشت:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه داده جدید.

### addDataPointForBarSeries(double value) {#addDataPointForBarSeries-double-}
```
public abstract IChartDataPoint addDataPointForBarSeries(double value)
```

یک نقطه داده جدید ایجاد می‌کند و آن را به انتهای مجموعه اضافه می‌نماید. برای سری‌هایی که chartType آن‌ها یکی از زیرنوع‌های Column یا Bar است کاربرد دارد (همچنین به متدهای ChartTypeCharacterizer.IsChartTypeColumn(ChartType) و ChartTypeCharacterizer.IsChartTypeBar(ChartType) مراجعه کنید).

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | double | مقدار نقطه داده |

**بازگشت:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه داده جدید.

### addDataPointForAreaSeries(IChartDataCell value) {#addDataPointForAreaSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForAreaSeries(IChartDataCell value)
```

یک نقطه داده جدید ایجاد می‌کند و آن را به انتهای مجموعه اضافه می‌نماید. برای سری‌هایی که chartType آن‌ها یکی از زیرنوع‌های Area است کاربرد دارد (همچنین به متد ChartTypeCharacterizer.IsChartTypeArea(ChartType) مراجعه کنید).

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | مقدار نقطه داده |

**بازگشت:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه داده جدید.

### addDataPointForAreaSeries(double value) {#addDataPointForAreaSeries-double-}
```
public abstract IChartDataPoint addDataPointForAreaSeries(double value)
```

یک نقطه داده جدید ایجاد می‌کند و آن را به انتهای مجموعه اضافه می‌نماید. برای سری‌هایی که chartType آن‌ها یکی از زیرنوع‌های Area است کاربرد دارد (همچنین به متد ChartTypeCharacterizer.IsChartTypeArea(ChartType) مراجعه کنید).

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | double | مقدار نقطه داده |

**بازگشت:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه داده جدید.

### addDataPointForPieSeries(IChartDataCell value) {#addDataPointForPieSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForPieSeries(IChartDataCell value)
```

یک نقطه داده جدید ایجاد می‌کند و آن را به انتهای مجموعه اضافه می‌نماید. برای سری‌هایی که chartType آن‌ها یکی از زیرنوع‌های Pie است کاربرد دارد (همچنین به متد ChartTypeCharacterizer.IsChartTypePie(ChartType) مراجعه کنید).

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | مقدار نقطه داده |

**بازگشت:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه داده جدید.

### addDataPointForPieSeries(double value) {#addDataPointForPieSeries-double-}
```
public abstract IChartDataPoint addDataPointForPieSeries(double value)
```

یک نقطه داده جدید ایجاد می‌کند و آن را به انتهای مجموعه اضافه می‌نماید. برای سری‌هایی که chartType آن‌ها یکی از زیرنوع‌های Pie است کاربرد دارد (همچنین به متد ChartTypeCharacterizer.IsChartTypePie(ChartType) مراجعه کنید).

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | double | مقدار نقطه داده |

**بازگشت:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه داده جدید.

### addDataPointForDoughnutSeries(IChartDataCell value) {#addDataPointForDoughnutSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForDoughnutSeries(IChartDataCell value)
```

یک نقطه داده جدید ایجاد می‌کند و آن را به انتهای مجموعه اضافه می‌نماید. برای سری‌هایی که chartType آن‌ها یکی از زیرنوع‌های Doughnut است کاربرد دارد (همچنین به متد ChartTypeCharacterizer.IsChartTypeDoughnut(ChartType) مراجعه کنید).

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | مقدار نقطه داده |

**بازگشت:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه داده جدید.

### addDataPointForDoughnutSeries(double value) {#addDataPointForDoughnutSeries-double-}
```
public abstract IChartDataPoint addDataPointForDoughnutSeries(double value)
```

یک نقطه داده جدید ایجاد می‌کند و آن را به انتهای مجموعه اضافه می‌نماید. برای سری‌هایی که chartType آن‌ها یکی از زیرنوع‌های Doughnut است کاربرد دارد (همچنین به متد ChartTypeCharacterizer.IsChartTypeDoughnut(ChartType) مراجعه کنید).

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | double | مقدار نقطه داده |

**بازگشت:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه داده جدید.

### addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```

یک نقطه داده جدید ایجاد می‌کند و آن را به انتهای مجموعه اضافه می‌نماید. برای سری‌هایی که chartType آن‌ها یکی از زیرنوع‌های Bubble است کاربرد دارد (همچنین به متد ChartTypeCharacterizer.IsChartTypeBubble(ChartType) مراجعه کنید).

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | نقطه داده XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | نقطه داده YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | اندازه BubbleSize |

**بازگشت:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه داده جدید.

### addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```

یک نقطه داده جدید ایجاد می‌کند و آن را به انتهای مجموعه اضافه می‌نماید. برای سری‌هایی که chartType آن‌ها یکی از زیرنوع‌های Bubble است کاربرد دارد (همچنین به متد ChartTypeCharacterizer.IsChartTypeBubble(ChartType) مراجعه کنید).

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| xValue | double | نقطه داده XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | نقطه داده YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | اندازه BubbleSize |

**بازگشت:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه داده جدید.

### addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```

یک نقطه داده جدید ایجاد می‌کند و آن را به انتهای مجموعه اضافه می‌نماید. برای سری‌هایی که chartType آن‌ها یکی از زیرنوع‌های Bubble است کاربرد دارد (همچنین به متد ChartTypeCharacterizer.IsChartTypeBubble(ChartType) مراجعه کنید).

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| xValue | java.lang.String | نقطه داده XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | نقطه داده YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | اندازه BubbleSize |

**بازگشت:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه داده جدید.

### addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, IChartDataCell bubbleSize)
```

یک نقطه داده جدید ایجاد می‌کند و آن را به انتهای مجموعه اضافه می‌نماید. برای سری‌هایی که chartType آن‌ها یکی از زیرنوع‌های Bubble است کاربرد دارد (همچنین به متد ChartTypeCharacterizer.IsChartTypeBubble(ChartType) مراجعه کنید).

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | نقطه داده XValue |
| yValue | double | نقطه داده YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | اندازه BubbleSize |

**بازگشت:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه داده جدید.

### addDataPointForBubbleSeries(double xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-double-double-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(double xValue, double yValue, IChartDataCell bubbleSize)
```

یک نقطه داده جدید ایجاد می‌کند و آن را به انتهای مجموعه اضافه می‌نماید. برای سری‌هایی که chartType آن‌ها یکی از زیرنوع‌های Bubble است کاربرد دارد (همچنین به متد ChartTypeCharacterizer.IsChartTypeBubble(ChartType) مراجعه کنید).

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| xValue | double | نقطه داده XValue |
| yValue | double | نقطه داده YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | اندازه BubbleSize |

**بازگشت:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه داده جدید.

### addDataPointForBubbleSeries(String xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-double-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(String xValue, double yValue, IChartDataCell bubbleSize)
```

یک نقطه داده جدید ایجاد می‌کند و آن را به انتهای مجموعه اضافه می‌نماید. برای سری‌هایی که chartType آن‌ها یکی از زیرنوع‌های Bubble است کاربرد دارد (همچنین به متد ChartTypeCharacterizer.IsChartTypeBubble(ChartType) مراجعه کنید).

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| xValue | java.lang.String | نقطه داده XValue |
| yValue | double | نقطه داده YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | اندازه BubbleSize |

**بازگشت:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه داده جدید.

### addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, double bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-double-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, double bubbleSize)
```
یک نقطه داده جدید ایجاد می‌کند و آن را به انتهای مجموعه اضافه می‌نماید. قابل استفاده برای سری‌هایی که chartType آن‌ها یکی از زیرنوع‌های Bubble است (همچنین به متد ChartTypeCharacterizer.IsChartTypeBubble(ChartType) مراجعه کنید).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | XValue نقطه داده |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | YValue نقطه داده |
| bubbleSize | double | BubbleSize نقطه داده |

**بازگشت:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه داده جدید.
### addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, double bubbleSize) {#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-double-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, double bubbleSize)
```

یک نقطه داده جدید ایجاد می‌کند و آن را به انتهای مجموعه اضافه می‌نماید. قابل استفاده برای سری‌هایی که chartType آن‌ها یکی از زیرنوع‌های Bubble است (همچنین به متد ChartTypeCharacterizer.IsChartTypeBubble(ChartType) مراجعه کنید).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| xValue | double | XValue نقطه داده |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | YValue نقطه داده |
| bubbleSize | double | BubbleSize نقطه داده |

**بازگشت:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه داده جدید.
### addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, double bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-double-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, double bubbleSize)
```

یک نقطه داده جدید ایجاد می‌کند و آن را به انتهای مجموعه اضافه می‌نماید. قابل استفاده برای سری‌هایی که chartType آن‌ها یکی از زیرنوع‌های Bubble است (همچنین به متد ChartTypeCharacterizer.IsChartTypeBubble(ChartType) مراجعه کنید).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| xValue | java.lang.String | XValue نقطه داده |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | YValue نقطه داده |
| bubbleSize | double | BubbleSize نقطه داده |

**بازگشت:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه داده جدید.
### addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, double bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-double-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, double bubbleSize)
```

یک نقطه داده جدید ایجاد می‌کند و آن را به انتهای مجموعه اضافه می‌نماید. قابل استفاده برای سری‌هایی که chartType آن‌ها یکی از زیرنوع‌های Bubble است (همچنین به متد ChartTypeCharacterizer.IsChartTypeBubble(ChartType) مراجعه کنید).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | XValue نقطه داده |
| yValue | double | YValue نقطه داده |
| bubbleSize | double | BubbleSize نقطه داده |

**بازگشت:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه داده جدید.
### addDataPointForBubbleSeries(double xValue, double yValue, double bubbleSize) {#addDataPointForBubbleSeries-double-double-double-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(double xValue, double yValue, double bubbleSize)
```

یک نقطه داده جدید ایجاد می‌کند و آن را به انتهای مجموعه اضافه می‌نماید. قابل استفاده برای سری‌هایی که chartType آن‌ها یکی از زیرنوع‌های Bubble است (همچنین به متد ChartTypeCharacterizer.IsChartTypeBubble(ChartType) مراجعه کنید).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| xValue | double | XValue نقطه داده |
| yValue | double | YValue نقطه داده |
| bubbleSize | double | BubbleSize نقطه داده |

**بازگشت:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه داده جدید.
### addDataPointForBubbleSeries(String xValue, double yValue, double bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-double-double-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(String xValue, double yValue, double bubbleSize)
```

یک نقطه داده جدید ایجاد می‌کند و آن را به انتهای مجموعه اضافه می‌نماید. قابل استفاده برای سری‌هایی که chartType آن‌ها یکی از زیرنوع‌های Bubble است (همچنین به متد ChartTypeCharacterizer.IsChartTypeBubble(ChartType) مراجعه کنید).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| xValue | java.lang.String | XValue نقطه داده |
| yValue | double | YValue نقطه داده |
| bubbleSize | double | BubbleSize نقطه داده |

**بازگشت:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه داده جدید.
### addDataPointForSurfaceSeries(IChartDataCell value) {#addDataPointForSurfaceSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForSurfaceSeries(IChartDataCell value)
```

یک نقطه داده جدید ایجاد می‌کند و آن را به انتهای مجموعه اضافه می‌نماید. قابل استفاده برای سری‌هایی که chartType آن‌ها یکی از زیرنوع‌های Surface است (همچنین به متد ChartTypeCharacterizer.IsChartTypeSurface(ChartType) مراجعه کنید).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Value نقطه داده |

**بازگشت:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه داده جدید.
### addDataPointForSurfaceSeries(double value) {#addDataPointForSurfaceSeries-double-}
```
public abstract IChartDataPoint addDataPointForSurfaceSeries(double value)
```

یک نقطه داده جدید ایجاد می‌کند و آن را به انتهای مجموعه اضافه می‌نماید. قابل استفاده برای سری‌هایی که chartType آن‌ها یکی از زیرنوع‌های Surface است (همچنین به متد ChartTypeCharacterizer.IsChartTypeSurface(ChartType) مراجعه کنید).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | double | Value نقطه داده |

**بازگشت:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه داده جدید.
### addDataPointForSunburstSeries(IChartDataCell sizeValue) {#addDataPointForSunburstSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForSunburstSeries(IChartDataCell sizeValue)
```

یک نقطه داده جدید ایجاد می‌کند و آن را به انتهای مجموعه اضافه می‌نماید. قابل استفاده برای سری‌هایی که chart type آن‌ها Sunburst است.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| sizeValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | SizeValue نقطه داده |

**بازگشت:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه داده جدید.
### addDataPointForWaterfallSeries(IChartDataCell value) {#addDataPointForWaterfallSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForWaterfallSeries(IChartDataCell value)
```

یک نقطه داده جدید ایجاد می‌کند و آن را به انتهای مجموعه اضافه می‌نماید. قابل استفاده برای سری‌هایی که chart type آن‌ها Waterfall است.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | value نقطه داده |

**بازگشت:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه داده جدید.
### addDataPointForBoxAndWhiskerSeries(IChartDataCell value) {#addDataPointForBoxAndWhiskerSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBoxAndWhiskerSeries(IChartDataCell value)
```

یک نقطه داده جدید ایجاد می‌کند و آن را به انتهای مجموعه اضافه می‌نماید. قابل استفاده برای سری‌هایی که chart type آن‌ها BoxAndWhisker است.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Value نقطه داده |

**بازگشت:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه داده جدید.
### addDataPointForTreemapSeries(IChartDataCell sizeValue) {#addDataPointForTreemapSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForTreemapSeries(IChartDataCell sizeValue)
```

یک نقطه داده جدید ایجاد می‌کند و آن را به انتهای مجموعه اضافه می‌نماید. قابل استفاده برای سری‌هایی که chart type آن‌ها Treemap است.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| sizeValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | SizeValue نقطه داده |

**بازگشت:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه داده جدید.
### addDataPointForHistogramSeries(IChartDataCell value) {#addDataPointForHistogramSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForHistogramSeries(IChartDataCell value)
```

یک نقطه داده جدید ایجاد می‌کند و آن را به انتهای مجموعه اضافه می‌نماید. قابل استفاده برای سری‌هایی که chart type آن‌ها Histogram است.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | value نقطه داده |

**بازگشت:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه داده جدید.
### addDataPointForFunnelSeries(IChartDataCell value) {#addDataPointForFunnelSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForFunnelSeries(IChartDataCell value)
```

یک نقطه داده جدید ایجاد می‌کند و آن را به انتهای مجموعه اضافه می‌نماید. قابل استفاده برای سری‌هایی که chart type آن‌ها Funnel است.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | value نقطه داده |

**بازگشت:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه داده جدید.
### addDataPointForMapSeries(IChartDataCell value) {#addDataPointForMapSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForMapSeries(IChartDataCell value)
```

یک نقطه داده جدید ایجاد می‌کند و آن را به انتهای مجموعه اضافه می‌نماید. قابل استفاده برای سری‌هایی که chart type آن‌ها Map است.

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

مقدار مشخص شده را حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | مقدار. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

عنصر را در ایندکس مشخص حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | ایندکس نقطه داده برای حذف. |