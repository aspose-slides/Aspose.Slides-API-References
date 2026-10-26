---
title: IChartDataPointCollection
second_title: Aspose.Slides for Java API Referansı
description: Bir serinin veri noktasının koleksiyonunu temsil eder.
type: docs
url: /tr/com.aspose.slides/ichartdatapointcollection/
---
**Tüm Uygulanan Arabirimler:**
com.aspose.slides.IGenericCollection
```
public interface IChartDataPointCollection extends IGenericCollection<IChartDataPoint>
```

Seri veri noktasının koleksiyonunu temsil eder.
## Yöntemler

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Seri veri noktasını indeksine göre döndürür (bu koleksiyondaki sıralama numarası). |
| [get_Item(IChartDataPoint pt)](#get-Item-com.aspose.slides.IChartDataPoint-) | Bu koleksiyondaki veri noktasının indeksini (sıralama numarasını) döndürür. |
| [getDataSourceTypeForXValues()](#getDataSourceTypeForXValues--) | Veri noktalarının XValue özelliği nesnesinde AsCell, AsLiteralString veya AsLiteralDouble özelliğinin gerçek olup olmadığını belirtir. |
| [setDataSourceTypeForXValues(int value)](#setDataSourceTypeForXValues-int-) | Veri noktalarının XValue özelliği nesnesinde AsCell, AsLiteralString veya AsLiteralDouble özelliğinin gerçek olup olmadığını belirtir. |
| [getDataSourceTypeForYValues()](#getDataSourceTypeForYValues--) | Veri noktalarının YValue özelliği nesnesinde AsCell, AsLiteralString veya AsLiteralDouble özelliğinin gerçek olup olmadığını belirtir. |
| [setDataSourceTypeForYValues(int value)](#setDataSourceTypeForYValues-int-) | Veri noktalarının YValue özelliği nesnesinde AsCell, AsLiteralString veya AsLiteralDouble özelliğinin gerçek olup olmadığını belirtir. |
| [getDataSourceTypeForBubbleSizes()](#getDataSourceTypeForBubbleSizes--) | Veri noktalarının BubbleSize özelliği nesnesinde AsCell, AsLiteralString veya AsLiteralDouble özelliğinin gerçek olup olmadığını belirtir. |
| [setDataSourceTypeForBubbleSizes(int value)](#setDataSourceTypeForBubbleSizes-int-) | Veri noktalarının BubbleSize özelliği nesnesinde AsCell, AsLiteralString veya AsLiteralDouble özelliğinin gerçek olup olmadığını belirtir. |
| [getDataSourceTypeForValues()](#getDataSourceTypeForValues--) | Veri noktalarının Value özelliği nesnesinde AsCell, AsLiteralString veya AsLiteralDouble özelliğinin gerçek olup olmadığını belirtir. |
| [setDataSourceTypeForValues(int value)](#setDataSourceTypeForValues-int-) | Veri noktalarının Value özelliği nesnesinde AsCell, AsLiteralString veya AsLiteralDouble özelliğinin gerçek olup olmadığını belirtir. |
| [getDataSourceTypeForErrorBarsCustomValues()](#getDataSourceTypeForErrorBarsCustomValues--) | ChartDataPoint.ErrorBarsCustomValues özellik listesinde değerlerin tipini belirtir. |
| [getOrCreateDataPointByIdx(long index)](#getOrCreateDataPointByIdx-long-) | Koleksiyon zaten belirtilen indeksde bir veri noktası içeriyorsa bu veri noktasını döndürür. |
| [addDataPointForStockSeries(IChartDataCell value)](#addDataPointForStockSeries-com.aspose.slides.IChartDataCell-) | Yeni bir veri noktası oluşturur ve koleksiyonun sonuna ekler. |
| [addDataPointForStockSeries(double value)](#addDataPointForStockSeries-double-) | Yeni bir veri noktası oluşturur ve koleksiyonun sonuna ekler. |
| [addDataPointForLineSeries(IChartDataCell value)](#addDataPointForLineSeries-com.aspose.slides.IChartDataCell-) | Yeni bir veri noktası oluşturur ve koleksiyonun sonuna ekler. |
| [addDataPointForLineSeries(double value)](#addDataPointForLineSeries-double-) | Yeni bir veri noktası oluşturur ve koleksiyonun sonuna ekler. |
| [addDataPointForScatterSeries(IChartDataCell xValue, IChartDataCell yValue)](#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | Yeni bir veri noktası oluşturur ve koleksiyonun sonuna ekler. |
| [addDataPointForScatterSeries(double xValue, IChartDataCell yValue)](#addDataPointForScatterSeries-double-com.aspose.slides.IChartDataCell-) | Yeni bir veri noktası oluşturur ve koleksiyonun sonuna ekler. |
| [addDataPointForScatterSeries(String xValue, IChartDataCell yValue)](#addDataPointForScatterSeries-java.lang.String-com.aspose.slides.IChartDataCell-) | Yeni bir veri noktası oluşturur ve koleksiyonun sonuna ekler. |
| [addDataPointForScatterSeries(IChartDataCell xValue, double yValue)](#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-double-) | Yeni bir veri noktası oluşturur ve koleksiyonun sonuna ekler. |
| [addDataPointForScatterSeries(double xValue, double yValue)](#addDataPointForScatterSeries-double-double-) | Yeni bir veri noktası oluşturur ve koleksiyonun sonuna ekler. |
| [addDataPointForScatterSeries(String xValue, double yValue)](#addDataPointForScatterSeries-java.lang.String-double-) | Yeni bir veri noktası oluşturur ve koleksiyonun sonuna ekler. |
| [addDataPointForRadarSeries(IChartDataCell value)](#addDataPointForRadarSeries-com.aspose.slides.IChartDataCell-) | Yeni bir veri noktası oluşturur ve koleksiyonun sonuna ekler. |
| [addDataPointForRadarSeries(double value)](#addDataPointForRadarSeries-double-) | Yeni bir veri noktası oluşturur ve koleksiyonun sonuna ekler. |
| [addDataPointForBarSeries(IChartDataCell value)](#addDataPointForBarSeries-com.aspose.slides.IChartDataCell-) | Yeni bir veri noktası oluşturur ve koleksiyonun sonuna ekler. |
| [addDataPointForBarSeries(double value)](#addDataPointForBarSeries-double-) | Yeni bir veri noktası oluşturur ve koleksiyonun sonuna ekler. |
| [addDataPointForAreaSeries(IChartDataCell value)](#addDataPointForAreaSeries-com.aspose.slides.IChartDataCell-) | Yeni bir veri noktası oluşturur ve koleksiyonun sonuna ekler. |
| [addDataPointForAreaSeries(double value)](#addDataPointForAreaSeries-double-) | Yeni bir veri noktası oluşturur ve koleksiyonun sonuna ekler. |
| [addDataPointForPieSeries(IChartDataCell value)](#addDataPointForPieSeries-com.aspose.slides.IChartDataCell-) | Yeni bir veri noktası oluşturur ve koleksiyonun sonuna ekler. |
| [addDataPointForPieSeries(double value)](#addDataPointForPieSeries-double-) | Yeni bir veri noktası oluşturur ve koleksiyonun sonuna ekler. |
| [addDataPointForDoughnutSeries(IChartDataCell value)](#addDataPointForDoughnutSeries-com.aspose.slides.IChartDataCell-) | Yeni bir veri noktası oluşturur ve koleksiyonun sonuna ekler. |
| [addDataPointForDoughnutSeries(double value)](#addDataPointForDoughnutSeries-double-) | Yeni bir veri noktası oluşturur ve koleksiyonun sonuna ekler. |
| [addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | Yeni bir veri noktası oluşturur ve koleksiyonun sonuna ekler. |
| [addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | Yeni bir veri noktası oluşturur ve koleksiyonun sonuna ekler. |
| [addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | Yeni bir veri noktası oluşturur ve koleksiyonun sonuna ekler. |
| [addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-com.aspose.slides.IChartDataCell-) | Yeni bir veri noktası oluşturur ve koleksiyonun sonuna ekler. |
| [addDataPointForBubbleSeries(double xValue, double yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-double-double-com.aspose.slides.IChartDataCell-) | Yeni bir veri noktası oluşturur ve koleksiyonun sonuna ekler. |
| [addDataPointForBubbleSeries(String xValue, double yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-double-com.aspose.slides.IChartDataCell-) | Yeni bir veri noktası oluşturur ve koleksiyonun sonuna ekler. |
| [addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, double bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-double-) | Yeni bir veri noktası oluşturur ve koleksiyonun sonuna ekler. |
| [addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, double bubbleSize)](#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-double-) | Yeni bir veri noktası oluşturur ve koleksiyonun sonuna ekler. |
| [addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, double bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-double-) | Yeni bir veri noktası oluşturur ve koleksiyonun sonuna ekler. |
| [addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, double bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-double-) | Yeni bir veri noktası oluşturur ve koleksiyonun sonuna ekler. |
| [addDataPointForBubbleSeries(double xValue, double yValue, double bubbleSize)](#addDataPointForBubbleSeries-double-double-double-) | Yeni bir veri noktası oluşturur ve koleksiyonun sonuna ekler. |
| [addDataPointForBubbleSeries(String xValue, double yValue, double bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-double-double-) | Yeni bir veri noktası oluşturur ve koleksiyonun sonuna ekler. |
| [addDataPointForSurfaceSeries(IChartDataCell value)](#addDataPointForSurfaceSeries-com.aspose.slides.IChartDataCell-) | Yeni bir veri noktası oluşturur ve koleksiyonun sonuna ekler. |
| [addDataPointForSurfaceSeries(double value)](#addDataPointForSurfaceSeries-double-) | Yeni bir veri noktası oluşturur ve koleksiyonun sonuna ekler. |
| [addDataPointForSunburstSeries(IChartDataCell sizeValue)](#addDataPointForSunburstSeries-com.aspose.slides.IChartDataCell-) | Yeni bir veri noktası oluşturur ve koleksiyonun sonuna ekler. |
| [addDataPointForWaterfallSeries(IChartDataCell value)](#addDataPointForWaterfallSeries-com.aspose.slides.IChartDataCell-) | Yeni bir veri noktası oluşturur ve koleksiyonun sonuna ekler. |
| [addDataPointForBoxAndWhiskerSeries(IChartDataCell value)](#addDataPointForBoxAndWhiskerSeries-com.aspose.slides.IChartDataCell-) | Yeni bir veri noktası oluşturur ve koleksiyonun sonuna ekler. |
| [addDataPointForTreemapSeries(IChartDataCell sizeValue)](#addDataPointForTreemapSeries-com.aspose.slides.IChartDataCell-) | Yeni bir veri noktasını oluşturur ve koleksiyonun sonuna ekler. |
| [addDataPointForHistogramSeries(IChartDataCell value)](#addDataPointForHistogramSeries-com.aspose.slides.IChartDataCell-) | Yeni bir veri noktası oluşturur ve koleksiyonun sonuna ekler. |
| [addDataPointForFunnelSeries(IChartDataCell value)](#addDataPointForFunnelSeries-com.aspose.slides.IChartDataCell-) | Yeni bir veri noktası oluşturur ve koleksiyonun sonuna ekler. |
| [addDataPointForMapSeries(IChartDataCell value)](#addDataPointForMapSeries-com.aspose.slides.IChartDataCell-) | Yeni bir veri noktası oluşturur ve koleksiyonun sonuna ekler. |
| [clear()](#clear--) | Koleksiyondaki tüm öğeleri kaldırır. |
| [remove(IChartDataPoint value)](#remove-com.aspose.slides.IChartDataPoint-) | Belirtilen değeri kaldırır. |
| [removeAt(int index)](#removeAt-int-) | Verilen indeksteki öğeyi kaldırır. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IChartDataPoint get_Item(int index)
```

Seri veri noktasını indeksine göre döndürür (bu koleksiyondaki sıralama numarası).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int |  |

**Döndürür:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint)
### get_Item(IChartDataPoint pt) {#get-Item-com.aspose.slides.IChartDataPoint-}
```
public abstract int get_Item(IChartDataPoint pt)
```

Bu koleksiyondaki veri noktasının indeksini (sıralama numarasını) döndürür.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pt | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) |  |

**Döndürür:**
int
### getDataSourceTypeForXValues() {#getDataSourceTypeForXValues--}
```
public abstract int getDataSourceTypeForXValues()
```

Veri noktalarının XValue özelliği nesnesinde AsCell, AsLiteralString veya AsLiteralDouble özelliğinin gerçek olup olmadığını belirtir. Başka bir deyişle ChartDataPointEx.XValue.Data özelliğinin değer tipini belirtir. Okunabilir/Yazılabilir [DataSourceType](../../com.aspose.slides/datasourcetype).

**Döndürür:**
int
### setDataSourceTypeForXValues(int value) {#setDataSourceTypeForXValues-int-}
```
public abstract void setDataSourceTypeForXValues(int value)
```

Veri noktalarının XValue özelliği nesnesinde AsCell, AsLiteralString veya AsLiteralDouble özelliğinin gerçek olup olmadığını belirtir. Başka bir deyişle ChartDataPointEx.XValue.Data özelliğinin değer tipini belirtir. Okunabilir/Yazılabilir [DataSourceType](../../com.aspose.slides/datasourcetype).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |
### getDataSourceTypeForYValues() {#getDataSourceTypeForYValues--}
```
public abstract int getDataSourceTypeForYValues()
```

Veri noktalarının YValue özelliği nesnesinde AsCell, AsLiteralString veya AsLiteralDouble özelliğinin gerçek olup olmadığını belirtir. Başka bir deyişle ChartDataPointEx.YValue.Data özelliğinin değer tipini belirtir. Okunabilir/Yazılabilir [DataSourceType](../../com.aspose.slides/datasourcetype).

**Döndürür:**
int
### setDataSourceTypeForYValues(int value) {#setDataSourceTypeForYValues-int-}
```
public abstract void setDataSourceTypeForYValues(int value)
```

Veri noktalarının YValue özelliği nesnesinde AsCell, AsLiteralString veya AsLiteralDouble özelliğinin gerçek olup olmadığını belirtir. Başka bir deyişle ChartDataPointEx.YValue.Data özelliğinin değer tipini belirtir. Okunabilir/Yazılabilir [DataSourceType](../../com.aspose.slides/datasourcetype).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |
### getDataSourceTypeForBubbleSizes() {#getDataSourceTypeForBubbleSizes--}
```
public abstract int getDataSourceTypeForBubbleSizes()
```

Veri noktalarının BubbleSize özelliği nesnesinde AsCell, AsLiteralString veya AsLiteralDouble özelliğinin gerçek olup olmadığını belirtir. Başka bir deyişle ChartDataPointEx.BubbleSize.Data özelliğinin değer tipini belirtir. Okunabilir/Yazılabilir [DataSourceType](../../com.aspose.slides/datasourcetype).

**Döndürür:**
int
### setDataSourceTypeForBubbleSizes(int value) {#setDataSourceTypeForBubbleSizes-int-}
```
public abstract void setDataSourceTypeForBubbleSizes(int value)
```

Veri noktalarının BubbleSize özelliği nesnesinde AsCell, AsLiteralString veya AsLiteralDouble özelliğinin gerçek olup olmadığını belirtir. Başka bir deyişle ChartDataPointEx.BubbleSize.Data özelliğinin değer tipini belirtir. Okunabilir/Yazılabilir [DataSourceType](../../com.aspose.slides/datasourcetype).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |
### getDataSourceTypeForValues() {#getDataSourceTypeForValues--}
```
public abstract int getDataSourceTypeForValues()
```

Veri noktalarının Value özelliği nesnesinde AsCell, AsLiteralString veya AsLiteralDouble özelliğinin gerçek olup olmadığını belirtir. Başka bir deyişle ChartDataPoint.Value.Data özelliğinin değer tipini belirtir. Okunabilir/Yazılabilir [DataSourceType](../../com.aspose.slides/datasourcetype).

**Döndürür:**
int
### setDataSourceTypeForValues(int value) {#setDataSourceTypeForValues-int-}
```
public abstract void setDataSourceTypeForValues(int value)
```

Veri noktalarının Value özelliği nesnesinde AsCell, AsLiteralString veya AsLiteralDouble özelliğinin gerçek olup olmadığını belirtir. Başka bir deyişle ChartDataPoint.Value.Data özelliğinin değer tipini belirtir. Okunabilir/Yazılabilir [DataSourceType](../../com.aspose.slides/datasourcetype).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |
### getDataSourceTypeForErrorBarsCustomValues() {#getDataSourceTypeForErrorBarsCustomValues--}
```
public abstract IDataSourceTypeForErrorBarsCustomValues getDataSourceTypeForErrorBarsCustomValues()
```

ChartDataPoint.ErrorBarsCustomValues özellik listesinde değerlerin tipini belirtir. Salt okunur [IDataSourceTypeForErrorBarsCustomValues](../../com.aspose.slides/idatasourcetypeforerrorbarscustomvalues).

**Döndürür:**
[IDataSourceTypeForErrorBarsCustomValues](../../com.aspose.slides/idatasourcetypeforerrorbarscustomvalues)
### getOrCreateDataPointByIdx(long index) {#getOrCreateDataPointByIdx-long-}
```
public abstract IChartDataPoint getOrCreateDataPointByIdx(long index)
```

Koleksiyon zaten belirtilen indekste bir veri noktası içeriyorsa bu veri noktasını döndürür. Koleksiyon, indeks==N (bu koleksiyondaki veri noktası sayısı N’den az ya da eşitse) olan bir veri noktasını içermiyorsa eksik veri noktalarını ekler ve sonuncusunu (istek yapılan indeksi taşıyanı) döndürür. Örneğin koleksiyon indeksleri {0, 1, 2} ve istenen indeks 5 ise metod eksik veri noktalarını ekler: {0, 1, 2, 3, 4, 5}. Ve indeks 5 olan veri noktasını döndürür.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | long | Indeks. |

**Döndürür:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - İstenen indeksli veri noktasını döndürür.
### addDataPointForStockSeries(IChartDataCell value) {#addDataPointForStockSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForStockSeries(IChartDataCell value)
```

Yeni bir veri noktası oluşturur ve koleksiyonun sonuna ekler. Seri tipinin chartType özelliği Stock alt tiplerinden biri olduğunda uygulanabilir (ayrıca ChartTypeCharacterizer.IsChartTypeStock(ChartType) metoduna bakınız).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Veri noktası Değeri. |

**Döndürür:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Yeni veri noktası.
### addDataPointForStockSeries(double value) {#addDataPointForStockSeries-double-}
```
public abstract IChartDataPoint addDataPointForStockSeries(double value)
```

Yeni bir veri noktası oluşturur ve koleksiyonun sonuna ekler. Seri tipinin chartType özelliği Stock alt tiplerinden biri olduğunda uygulanabilir (ayrıca ChartTypeCharacterizer.IsChartTypeStock(ChartType) metoduna bakınız).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | double | Veri noktası Değeri. |

**Döndürür:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Yeni veri noktası.
### addDataPointForLineSeries(IChartDataCell value) {#addDataPointForLineSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForLineSeries(IChartDataCell value)
```

Yeni bir veri noktası oluşturur ve koleksiyonun sonuna ekler. Seri tipinin chartType özelliği Line alt tiplerinden biri olduğunda uygulanabilir (ayrıca ChartTypeCharacterizer.IsChartTypeLine(ChartType) metoduna bakınız).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Veri noktası Değeri. |

**Döndürür:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Yeni veri noktası.
### addDataPointForLineSeries(double value) {#addDataPointForLineSeries-double-}
```
public abstract IChartDataPoint addDataPointForLineSeries(double value)
```

Yeni bir veri noktası oluşturur ve koleksiyonun sonuna ekler. Seri tipinin chartType özelliği Line alt tiplerinden biri olduğunda uygulanabilir (ayrıca ChartTypeCharacterizer.IsChartTypeLine(ChartType) metoduna bakınız).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | double | Veri noktası Değeri. |

**Döndürür:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Yeni veri noktası.
### addDataPointForScatterSeries(IChartDataCell xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForScatterSeries(IChartDataCell xValue, IChartDataCell yValue)
```

Yeni bir veri noktası oluşturur ve koleksiyonun sonuna ekler. Seri tipinin chartType özelliği Scatter alt tiplerinden biri olduğunda uygulanabilir (ayrıca ChartTypeCharacterizer.IsChartTypeScatter(ChartType) metoduna bakınız).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |

| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Veri noktası XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Veri noktası YValue |

**Döndürür:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Yeni veri noktası.

### addDataPointForScatterSeries(double xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-double-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForScatterSeries(double xValue, IChartDataCell yValue)
```

Yeni veri noktasını oluşturur ve koleksiyonun sonuna ekler. Grafik türü Scatter alt tiplerinden biri olan seriler için geçerlidir (ayrıca ChartTypeCharacterizer.IsChartTypeScatter(ChartType) yöntemi).

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| xValue | double | Veri noktası XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Veri noktası YValue |

**Döndürür:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Yeni veri noktası.

### addDataPointForScatterSeries(String xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-java.lang.String-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForScatterSeries(String xValue, IChartDataCell yValue)
```

Yeni veri noktasını oluşturur ve koleksiyonun sonuna ekler. Grafik türü Scatter alt tiplerinden biri olan seriler için geçerlidir (ayrıca ChartTypeCharacterizer.IsChartTypeScatter(ChartType) yöntemi).

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| xValue | java.lang.String | Veri noktası XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Veri noktası YValue |

**Döndürür:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Yeni veri noktası.

### addDataPointForScatterSeries(IChartDataCell xValue, double yValue) {#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-double-}
```
public abstract IChartDataPoint addDataPointForScatterSeries(IChartDataCell xValue, double yValue)
```

Yeni veri noktasını oluşturur ve koleksiyonun sonuna ekler. Grafik türü Scatter alt tiplerinden biri olan seriler için geçerlidir (ayrıca ChartTypeCharacterizer.IsChartTypeScatter(ChartType) yöntemi).

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Veri noktası XValue |
| yValue | double | Veri noktası YValue |

**Döndürür:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Yeni veri noktası.

### addDataPointForScatterSeries(double xValue, double yValue) {#addDataPointForScatterSeries-double-double-}
```
public abstract IChartDataPoint addDataPointForScatterSeries(double xValue, double yValue)
```

Yeni veri noktasını oluşturur ve koleksiyonun sonuna ekler. Grafik türü Scatter alt tiplerinden biri olan seriler için geçerlidir (ayrıca ChartTypeCharacterizer.IsChartTypeScatter(ChartType) yöntemi).

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| xValue | double | Veri noktası XValue |
| yValue | double | Veri noktası YValue |

**Döndürür:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Yeni veri noktası.

### addDataPointForScatterSeries(String xValue, double yValue) {#addDataPointForScatterSeries-java.lang.String-double-}
```
public abstract IChartDataPoint addDataPointForScatterSeries(String xValue, double yValue)
```

Yeni veri noktasını oluşturur ve koleksiyonun sonuna ekler. Grafik türü Scatter alt tiplerinden biri olan seriler için geçerlidir (ayrıca ChartTypeCharacterizer.IsChartTypeScatter(ChartType) yöntemi).

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| xValue | java.lang.String | Veri noktası XValue |
| yValue | double | Veri noktası YValue |

**Döndürür:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Yeni veri noktası.

### addDataPointForRadarSeries(IChartDataCell value) {#addDataPointForRadarSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForRadarSeries(IChartDataCell value)
```

Yeni veri noktasını oluşturur ve koleksiyonun sonuna ekler. Grafik türü Radar alt tiplerinden biri olan seriler için geçerlidir (ayrıca ChartTypeCharacterizer.IsChartTypeRadar(ChartType) yöntemi).

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Veri noktası Value |

**Döndürür:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Yeni veri noktası.

### addDataPointForRadarSeries(double value) {#addDataPointForRadarSeries-double-}
```
public abstract IChartDataPoint addDataPointForRadarSeries(double value)
```

Yeni veri noktasını oluşturur ve koleksiyonun sonuna ekler. Grafik türü Radar alt tiplerinden biri olan seriler için geçerlidir (ayrıca ChartTypeCharacterizer.IsChartTypeRadar(ChartType) yöntemi).

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | Veri noktası Value |

**Döndürür:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Yeni veri noktası.

### addDataPointForBarSeries(IChartDataCell value) {#addDataPointForBarSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBarSeries(IChartDataCell value)
```

Yeni veri noktasını oluşturur ve koleksiyonun sonuna ekler. Grafik türü Column veya Bar alt tiplerinden biri olan seriler için geçerlidir (ayrıca ChartTypeCharacterizer.IsChartTypeColumn(ChartType) ve ChartTypeCharacterizer.IsChartTypeBar(ChartType) yöntemleri).

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Veri noktası Value |

**Döndürür:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Yeni veri noktası.

### addDataPointForBarSeries(double value) {#addDataPointForBarSeries-double-}
```
public abstract IChartDataPoint addDataPointForBarSeries(double value)
```

Yeni veri noktasını oluşturur ve koleksiyonun sonuna ekler. Grafik türü Column veya Bar alt tiplerinden biri olan seriler için geçerlidir (ayrıca ChartTypeCharacterizer.IsChartTypeColumn(ChartType) ve ChartTypeCharacterizer.IsChartTypeBar(ChartType) yöntemleri).

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | Veri noktası Value |

**Döndürür:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Yeni veri noktası.

### addDataPointForAreaSeries(IChartDataCell value) {#addDataPointForAreaSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForAreaSeries(IChartDataCell value)
```

Yeni veri noktasını oluşturur ve koleksiyonun sonuna ekler. Grafik türü Area alt tiplerinden biri olan seriler için geçerlidir (ayrıca ChartTypeCharacterizer.IsChartTypeArea(ChartType) yöntemi).

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Veri noktası Value |

**Döndürür:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Yeni veri noktası.

### addDataPointForAreaSeries(double value) {#addDataPointForAreaSeries-double-}
```
public abstract IChartDataPoint addDataPointForAreaSeries(double value)
```

Yeni veri noktasını oluşturur ve koleksiyonun sonuna ekler. Grafik türü Area alt tiplerinden biri olan seriler için geçerlidir (ayrıca ChartTypeCharacterizer.IsChartTypeArea(ChartType) yöntemi).

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | Veri noktası Value |

**Döndürür:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Yeni veri noktası.

### addDataPointForPieSeries(IChartDataCell value) {#addDataPointForPieSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForPieSeries(IChartDataCell value)
```

Yeni veri noktasını oluşturur ve koleksiyonun sonuna ekler. Grafik türü Pie alt tiplerinden biri olan seriler için geçerlidir (ayrıca ChartTypeCharacterizer.IsChartTypePie(ChartType) yöntemi).

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Veri noktası Value |

**Döndürür:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Yeni veri noktası.

### addDataPointForPieSeries(double value) {#addDataPointForPieSeries-double-}
```
public abstract IChartDataPoint addDataPointForPieSeries(double value)
```

Yeni veri noktasını oluşturur ve koleksiyonun sonuna ekler. Grafik türü Pie alt tiplerinden biri olan seriler için geçerlidir (ayrıca ChartTypeCharacterizer.IsChartTypePie(ChartType) yöntemi).

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | Veri noktası Value |

**Döndürür:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Yeni veri noktası.

### addDataPointForDoughnutSeries(IChartDataCell value) {#addDataPointForDoughnutSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForDoughnutSeries(IChartDataCell value)
```

Yeni veri noktasını oluşturur ve koleksiyonun sonuna ekler. Grafik türü Doughnut alt tiplerinden biri olan seriler için geçerlidir (ayrıca ChartTypeCharacterizer.IsChartTypeDoughnut(ChartType) yöntemi).

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Veri noktası Value |

**Döndürür:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Yeni veri noktası.

### addDataPointForDoughnutSeries(double value) {#addDataPointForDoughnutSeries-double-}
```
public abstract IChartDataPoint addDataPointForDoughnutSeries(double value)
```

Yeni veri noktasını oluşturur ve koleksiyonun sonuna ekler. Grafik türü Doughnut alt tiplerinden biri olan seriler için geçerlidir (ayrıca ChartTypeCharacterizer.IsChartTypeDoughnut(ChartType) yöntemi).

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | Veri noktası Value |

**Döndürür:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Yeni veri noktası.

### addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```

Yeni veri noktasını oluşturur ve koleksiyonun sonuna ekler. Grafik türü Bubble alt tiplerinden biri olan seriler için geçerlidir (ayrıca ChartTypeCharacterizer.IsChartTypeBubble(ChartType) yöntemi).

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Veri noktası XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Veri noktası YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Veri noktası BubbleSize |

**Döndürür:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Yeni veri noktası.

### addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```

Yeni veri noktasını oluşturur ve koleksiyonun sonuna ekler. Grafik türü Bubble alt tiplerinden biri olan seriler için geçerlidir (ayrıca ChartTypeCharacterizer.IsChartTypeBubble(ChartType) yöntemi).

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| xValue | double | Veri noktası XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Veri noktası YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Veri noktası BubbleSize |

**Döndürür:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Yeni veri noktası.

### addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```

Yeni veri noktasını oluşturur ve koleksiyonun sonuna ekler. Grafik türü Bubble alt tiplerinden biri olan seriler için geçerlidir (ayrıca ChartTypeCharacterizer.IsChartTypeBubble(ChartType) yöntemi).

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| xValue | java.lang.String | Veri noktası XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Veri noktası YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Veri noktası BubbleSize |

**Döndürür:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Yeni veri noktası.

### addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, IChartDataCell bubbleSize)
```

Yeni veri noktasını oluşturur ve koleksiyonun sonuna ekler. Grafik türü Bubble alt tiplerinden biri olan seriler için geçerlidir (ayrıca ChartTypeCharacterizer.IsChartTypeBubble(ChartType) yöntemi).

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Veri noktası XValue |
| yValue | double | Veri noktası YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Veri noktası BubbleSize |

**Döndürür:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Yeni veri noktası.

### addDataPointForBubbleSeries(double xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-double-double-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(double xValue, double yValue, IChartDataCell bubbleSize)
```

Yeni veri noktasını oluşturur ve koleksiyonun sonuna ekler. Grafik türü Bubble alt tiplerinden biri olan seriler için geçerlidir (ayrıca ChartTypeCharacterizer.IsChartTypeBubble(ChartType) yöntemi).

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| xValue | double | Veri noktası XValue |
| yValue | double | Veri noktası YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Veri noktası BubbleSize |

**Döndürür:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Yeni veri noktası.

### addDataPointForBubbleSeries(String xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-double-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(String xValue, double yValue, IChartDataCell bubbleSize)
```

Yeni veri noktasını oluşturur ve koleksiyonun sonuna ekler. Grafik türü Bubble alt tiplerinden biri olan seriler için geçerlidir (ayrıca ChartTypeCharacterizer.IsChartTypeBubble(ChartType) yöntemi).

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| xValue | java.lang.String | Veri noktası XValue |
| yValue | double | Veri noktası YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Veri noktası BubbleSize |

**Döndürür:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Yeni veri noktası.

### addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, double bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-double-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, double bubbleSize)
```
Yeni veri noktasını oluşturur ve koleksiyonun sonuna ekler. Bu, chartType özelliği Bubble alt tiplerinden biri olan seriler için geçerlidir (bkz. ChartTypeCharacterizer.IsChartTypeBubble(ChartType) metodu).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Veri noktasının XValue değeri |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Veri noktasının YValue değeri |
| bubbleSize | double | Veri noktasının BubbleSize değeri |

**Döndürür:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Yeni veri noktası.
### addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, double bubbleSize) {#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-double-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, double bubbleSize)
```


Yeni veri noktasını oluşturur ve koleksiyonun sonuna ekler. Bu, chartType özelliği Bubble alt tiplerinden biri olan seriler için geçerlidir (bkz. ChartTypeCharacterizer.IsChartTypeBubble(ChartType) metodu).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| xValue | double | Veri noktasının XValue değeri |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Veri noktasının YValue değeri |
| bubbleSize | double | Veri noktasının BubbleSize değeri |

**Döndürür:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Yeni veri noktası.
### addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, double bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-double-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, double bubbleSize)
```


Yeni veri noktasını oluşturur ve koleksiyonun sonuna ekler. Bu, chartType özelliği Bubble alt tiplerinden biri olan seriler için geçerlidir (bkz. ChartTypeCharacterizer.IsChartTypeBubble(ChartType) metodu).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| xValue | java.lang.String | Veri noktasının XValue değeri |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Veri noktasının YValue değeri |
| bubbleSize | double | Veri noktasının BubbleSize değeri |

**Döndürür:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Yeni veri noktası.
### addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, double bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-double-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, double bubbleSize)
```


Yeni veri noktasını oluşturur ve koleksiyonun sonuna ekler. Bu, chartType özelliği Bubble alt tiplerinden biri olan seriler için geçerlidir (bkz. ChartTypeCharacterizer.IsChartTypeBubble(ChartType) metodu).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Veri noktasının XValue değeri |
| yValue | double | Veri noktasının YValue değeri |
| bubbleSize | double | Veri noktasının BubbleSize değeri |

**Döndürür:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Yeni veri noktası.
### addDataPointForBubbleSeries(double xValue, double yValue, double bubbleSize) {#addDataPointForBubbleSeries-double-double-double-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(double xValue, double yValue, double bubbleSize)
```


Yeni veri noktasını oluşturur ve koleksiyonun sonuna ekler. Bu, chartType özelliği Bubble alt tiplerinden biri olan seriler için geçerlidir (bkz. ChartTypeCharacterizer.IsChartTypeBubble(ChartType) metodu).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| xValue | double | Veri noktasının XValue değeri |
| yValue | double | Veri noktasının YValue değeri |
| bubbleSize | double | Veri noktasının BubbleSize değeri |

**Döndürür:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Yeni veri noktası.
### addDataPointForBubbleSeries(String xValue, double yValue, double bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-double-double-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(String xValue, double yValue, double bubbleSize)
```


Yeni veri noktasını oluşturur ve koleksiyonun sonuna ekler. Bu, chartType özelliği Bubble alt tiplerinden biri olan seriler için geçerlidir (bkz. ChartTypeCharacterizer.IsChartTypeBubble(ChartType) metodu).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| xValue | java.lang.String | Veri noktasının XValue değeri |
| yValue | double | Veri noktasının YValue değeri |
| bubbleSize | double | Veri noktasının BubbleSize değeri |

**Döndürür:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Yeni veri noktası.
### addDataPointForSurfaceSeries(IChartDataCell value) {#addDataPointForSurfaceSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForSurfaceSeries(IChartDataCell value)
```


Yeni veri noktasını oluşturur ve koleksiyonun sonuna ekler. Bu, chartType özelliği Surface alt tiplerinden biri olan seriler için geçerlidir (bkz. ChartTypeCharacterizer.IsChartTypeSurface(ChartType) metodu).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Veri noktasının Value değeri |

**Döndürür:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Yeni veri noktası.
### addDataPointForSurfaceSeries(double value) {#addDataPointForSurfaceSeries-double-}
```
public abstract IChartDataPoint addDataPointForSurfaceSeries(double value)
```


Yeni veri noktasını oluşturur ve koleksiyonun sonuna ekler. Bu, chartType özelliği Surface alt tiplerinden biri olan seriler için geçerlidir (bkz. ChartTypeCharacterizer.IsChartTypeSurface(ChartType) metodu).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | double | Veri noktasının Value değeri |

**Döndürür:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Yeni veri noktası.
### addDataPointForSunburstSeries(IChartDataCell sizeValue) {#addDataPointForSunburstSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForSunburstSeries(IChartDataCell sizeValue)
```


Yeni veri noktasını oluşturur ve koleksiyonun sonuna ekler. Bu, chart type özelliği Sunburst için geçerlidir.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sizeValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Veri noktasının SizeValue değeri |

**Döndürür:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Yeni veri noktası.
### addDataPointForWaterfallSeries(IChartDataCell value) {#addDataPointForWaterfallSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForWaterfallSeries(IChartDataCell value)
```


Yeni veri noktasını oluşturur ve koleksiyonun sonuna ekler. Bu, chart type özelliği Waterfall için geçerlidir.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Veri noktasının value değeri |

**Döndürür:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Yeni veri noktası.
### addDataPointForBoxAndWhiskerSeries(IChartDataCell value) {#addDataPointForBoxAndWhiskerSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBoxAndWhiskerSeries(IChartDataCell value)
```


Yeni veri noktasını oluşturur ve koleksiyonun sonuna ekler. Bu, chart type özelliği BoxAndWhisker için geçerlidir.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Veri noktasının Value değeri |

**Döndürür:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Yeni veri noktası.
### addDataPointForTreemapSeries(IChartDataCell sizeValue) {#addDataPointForTreemapSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForTreemapSeries(IChartDataCell sizeValue)
```


Yeni veri noktasını oluşturur ve koleksiyonun sonuna ekler. Bu, chart type özelliği Treemap için geçerlidir.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sizeValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Veri noktasının SizeValue değeri |

**Döndürür:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Yeni veri noktası.
### addDataPointForHistogramSeries(IChartDataCell value) {#addDataPointForHistogramSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForHistogramSeries(IChartDataCell value)
```


Yeni veri noktasını oluşturur ve koleksiyonun sonuna ekler. Bu, chart type özelliği Histogram için geçerlidir.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Veri noktasının value değeri |

**Döndürür:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Yeni veri noktası.
### addDataPointForFunnelSeries(IChartDataCell value) {#addDataPointForFunnelSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForFunnelSeries(IChartDataCell value)
```


Yeni veri noktasını oluşturur ve koleksiyonun sonuna ekler. Bu, chart type özelliği Funnel için geçerlidir.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Veri noktasının value değeri |

**Döndürür:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Yeni veri noktası.
### addDataPointForMapSeries(IChartDataCell value) {#addDataPointForMapSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForMapSeries(IChartDataCell value)
```


Yeni veri noktasını oluşturur ve koleksiyonun sonuna ekler. Bu, chart type özelliği Map için geçerlidir.

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


**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Veri noktasının ColorValue değeri |

**Döndürür:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Yeni veri noktası.
### clear() {#clear--}
```
public abstract void clear()
```


Koleksiyondaki tüm öğeleri kaldırır.

### remove(IChartDataPoint value) {#remove-com.aspose.slides.IChartDataPoint-}
```
public abstract void remove(IChartDataPoint value)
```


Belirtilen değeri kaldırır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | Değer. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Belirtilen indisteki öğeyi kaldırır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Kaldırılacak veri noktasının indeksi. |