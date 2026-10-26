---
title: ChartDataPointCollection
second_title: Aspose.Slides for Android via Java API Referansı
description: Bir seri veri noktasının koleksiyonunu temsil eder.
type: docs
url: /tr/com.aspose.slides/chartdatapointcollection/
---
**Kalıtım:**  
java.lang.Object, com.aspose.slides.DomObject

**Tüm Gerçekleştirilen Arabirimler:**  
[com.aspose.slides.IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection)  
```
public class ChartDataPointCollection extends DomObject<ChartSeries> implements IChartDataPointCollection
```

Bir seri veri noktasının koleksiyonunu temsil eder.

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Seri veri noktasını indeksine göre döndürür (bu koleksiyondaki sıra numarası). |
| [get_Item(IChartDataPoint pt)](#get-Item-com.aspose.slides.IChartDataPoint-) | Veri noktasının bu koleksiyondaki indeksini (sıra numarasını) döndürür. |
| [getDataSourceTypeForXValues()](#getDataSourceTypeForXValues--) | Veri noktalarının XValue özelliği nesnesinde AsCell veya AsLiteralString veya AsLiteralDouble özelliğinin geçerli olup olmadığını belirtir. |
| [setDataSourceTypeForXValues(int value)](#setDataSourceTypeForXValues-int-) | Veri noktalarının XValue özelliği nesnesinde AsCell veya AsLiteralString veya AsLiteralDouble özelliğinin geçerli olup olmadığını belirtir. |
| [getDataSourceTypeForYValues()](#getDataSourceTypeForYValues--) | Veri noktalarının YValue özelliği nesnesinde AsCell veya AsLiteralString veya AsLiteralDouble özelliğinin geçerli olup olmadığını belirtir. |
| [setDataSourceTypeForYValues(int value)](#setDataSourceTypeForYValues-int-) | Veri noktalarının YValue özelliği nesnesinde AsCell veya AsLiteralString veya AsLiteralDouble özelliğinin geçerli olup olmadığını belirtir. |
| [getDataSourceTypeForBubbleSizes()](#getDataSourceTypeForBubbleSizes--) | Veri noktalarının BubbleSize özelliği nesnesinde AsCell veya AsLiteralString veya AsLiteralDouble özelliğinin geçerli olup olmadığını belirtir. |
| [setDataSourceTypeForBubbleSizes(int value)](#setDataSourceTypeForBubbleSizes-int-) | Veri noktalarının BubbleSize özelliği nesnesinde AsCell veya AsLiteralString veya AsLiteralDouble özelliğinin geçerli olup olmadığını belirtir. |
| [getDataSourceTypeForValues()](#getDataSourceTypeForValues--) | Veri noktalarının Value özelliği nesnesinde AsCell veya AsLiteralString veya AsLiteralDouble özelliğinin geçerli olup olmadığını belirtir. |
| [setDataSourceTypeForValues(int value)](#setDataSourceTypeForValues-int-) | Veri noktalarının Value özelliği nesnesinde AsCell veya AsLiteralString veya AsLiteralDouble özelliğinin geçerli olup olmadığını belirtir. |
| [getDataSourceTypeForErrorBarsCustomValues()](#getDataSourceTypeForErrorBarsCustomValues--) | ChartDataPoint.ErrorBarsCustomValues özellikleri listesinde değer türlerini belirtir. |
| [getOrCreateDataPointByIdx(long index)](#getOrCreateDataPointByIdx-long-) | Koleksiyon zaten index indeksinde bir veri noktasını içeriyorsa bu veri noktasını döndürür. |
| [size()](#size--) | Koleksiyonda gerçekte bulunan eleman sayısını alır. |
| [copyTo(System.Array array, int arrayIndex)](#copyTo-com.aspose.ms.System.Array-int-) | Belirtilen diziye kopyalar. |
| [isSynchronized()](#isSynchronized--) | Koleksiyona erişimin senkronize (iplik-güvenli) olup olmadığını gösteren bir değer döndürür. |
| [getSyncRoot()](#getSyncRoot--) | Bir senkronizasyon kökü döndürür. |
| [iterator()](#iterator--) | Koleksiyon içinde yineleme yapan bir enumerator döndürür. |
| [iteratorJava()](#iteratorJava--) | Tüm koleksiyon için bir java iterator döndürür. |
| [addDataPointForStockSeries(IChartDataCell value)](#addDataPointForStockSeries-com.aspose.slides.IChartDataCell-) | Yeni veri noktasını oluşturur ve koleksiyonun sonuna ekler. |
| [addDataPointForStockSeries(double value)](#addDataPointForStockSeries-double-) | Yeni veri noktasını oluşturur ve koleksiyonun sonuna ekler. |
| [addDataPointForLineSeries(IChartDataCell value)](#addDataPointForLineSeries-com.aspose.slides.IChartDataCell-) | Yeni veri noktasını oluşturur ve koleksiyonun sonuna ekler. |
| [addDataPointForLineSeries(double value)](#addDataPointForLineSeries-double-) | Yeni veri noktasını oluşturur ve koleksiyonun sonuna ekler. |
| [addDataPointForScatterSeries(IChartDataCell xValue, IChartDataCell yValue)](#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | Yeni veri noktasını oluşturur ve koleksiyonun sonuna ekler. |
| [addDataPointForScatterSeries(double xValue, IChartDataCell yValue)](#addDataPointForScatterSeries-double-com.aspose.slides.IChartDataCell-) | Yeni veri noktasını oluşturur ve koleksiyonun sonuna ekler. |
| [addDataPointForScatterSeries(String xValue, IChartDataCell yValue)](#addDataPointForScatterSeries-java.lang.String-com.aspose.slides.IChartDataCell-) | Yeni veri noktasını oluşturur ve koleksiyonun sonuna ekler. |
| [addDataPointForScatterSeries(IChartDataCell xValue, double yValue)](#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-double-) | Yeni veri noktasını oluşturur ve koleksiyonun sonuna ekler. |
| [addDataPointForScatterSeries(double xValue, double yValue)](#addDataPointForScatterSeries-double-double-) | Yeni veri noktasını oluşturur ve koleksiyonun sonuna ekler. |
| [addDataPointForScatterSeries(String xValue, double yValue)](#addDataPointForScatterSeries-java.lang.String-double-) | Yeni veri noktasını oluşturur ve koleksiyonun sonuna ekler. |
| [addDataPointForRadarSeries(IChartDataCell value)](#addDataPointForRadarSeries-com.aspose.slides.IChartDataCell-) | Yeni veri noktasını oluşturur ve koleksiyonun sonuna ekler. |
| [addDataPointForRadarSeries(double value)](#addDataPointForRadarSeries-double-) | Yeni veri noktasını oluşturur ve koleksiyonun sonuna ekler. |
| [addDataPointForBarSeries(IChartDataCell value)](#addDataPointForBarSeries-com.aspose.slides.IChartDataCell-) | Yeni veri noktasını oluşturur ve koleksiyonun sonuna ekler. |
| [addDataPointForBarSeries(double value)](#addDataPointForBarSeries-double-) | Yeni veri noktasını oluşturur ve koleksiyonun sonuna ekler. |
| [addDataPointForAreaSeries(IChartDataCell value)](#addDataPointForAreaSeries-com.aspose.slides.IChartDataCell-) | Yeni veri noktasını oluşturur ve koleksiyonun sonuna ekler. |
| [addDataPointForAreaSeries(double value)](#addDataPointForAreaSeries-double-) | Yeni veri noktasını oluşturur ve koleksiyonun sonuna ekler. |
| [addDataPointForPieSeries(IChartDataCell value)](#addDataPointForPieSeries-com.aspose.slides.IChartDataCell-) | Yeni veri noktasını oluşturur ve koleksiyonun sonuna ekler. |
| [addDataPointForPieSeries(double value)](#addDataPointForPieSeries-double-) | Yeni veri noktasını oluşturur ve koleksiyonun sonuna ekler. |
| [addDataPointForDoughnutSeries(IChartDataCell value)](#addDataPointForDoughnutSeries-com.aspose.slides.IChartDataCell-) | Yeni veri noktasını oluşturur ve koleksiyonun sonuna ekler. |
| [addDataPointForDoughnutSeries(double value)](#addDataPointForDoughnutSeries-double-) | Yeni veri noktasını oluşturur ve koleksiyonun sonuna ekler. |
| [addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | Yeni veri noktasını oluşturur ve koleksiyonun sonuna ekler. |
| [addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | Yeni veri noktasını oluşturur ve koleksiyonun sonuna ekler. |
| [addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | Yeni veri noktasını oluşturur ve koleksiyonun sonuna ekler. |
| [addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-com.aspose.slides.IChartDataCell-) | Yeni veri noktasını oluşturur ve koleksiyonun sonuna ekler. |
| [addDataPointForBubbleSeries(double xValue, double yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-double-double-com.aspose.slides.IChartDataCell-) | Yeni veri noktasını oluşturur ve koleksiyonun sonuna ekler. |
| [addDataPointForBubbleSeries(String xValue, double yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-double-com.aspose.slides.IChartDataCell-) | Yeni veri noktasını oluşturur ve koleksiyonun sonuna ekler. |
| [addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, double bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-double-) | Yeni veri noktasını oluşturur ve koleksiyonun sonuna ekler. |
| [addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, double bubbleSize)](#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-double-) | Yeni veri noktasını oluşturur ve koleksiyonun sonuna ekler. |
| [addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, double bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-double-) | Yeni veri noktasını oluşturur ve koleksiyonun sonuna ekler. |
| [addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, double bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-double-) | Yeni veri noktasını oluşturur ve koleksiyonun sonuna ekler. |
| [addDataPointForBubbleSeries(double xValue, double yValue, double bubbleSize)](#addDataPointForBubbleSeries-double-double-double-) | Yeni veri noktasını oluşturur ve koleksiyonun sonuna ekler. |
| [addDataPointForBubbleSeries(String xValue, double yValue, double bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-double-double-) | Yeni veri noktasını oluşturur ve koleksiyonun sonuna ekler. |
| [addDataPointForSurfaceSeries(IChartDataCell value)](#addDataPointForSurfaceSeries-com.aspose.slides.IChartDataCell-) | Yeni veri noktasını oluşturur ve koleksiyonun sonuna ekler. |
| [addDataPointForSurfaceSeries(double value)](#addDataPointForSurfaceSeries-double-) | Yeni veri noktasını oluşturur ve koleksiyonun sonuna ekler. |
| [addDataPointForSunburstSeries(IChartDataCell sizeValue)](#addDataPointForSunburstSeries-com.aspose.slides.IChartDataCell-) | Yeni veri noktasını oluşturur ve koleksiyonun sonuna ekler. |
| [addDataPointForTreemapSeries(IChartDataCell sizeValue)](#addDataPointForTreemapSeries-com.aspose.slides.IChartDataCell-) | Yeni veri noktasını oluşturur ve koleksiyonun sonuna ekler. |
| [addDataPointForBoxAndWhiskerSeries(IChartDataCell value)](#addDataPointForBoxAndWhiskerSeries-com.aspose.slides.IChartDataCell-) | Yeni veri noktasını oluşturur ve koleksiyonun sonuna ekler. |
| [addDataPointForWaterfallSeries(IChartDataCell value)](#addDataPointForWaterfallSeries-com.aspose.slides.IChartDataCell-) | Yeni veri noktasını oluşturur ve koleksiyonun sonuna ekler. |
| [addDataPointForHistogramSeries(IChartDataCell value)](#addDataPointForHistogramSeries-com.aspose.slides.IChartDataCell-) | Yeni veri noktasını oluşturur ve koleksiyonun sonuna ekler. |
| [addDataPointForFunnelSeries(IChartDataCell value)](#addDataPointForFunnelSeries-com.aspose.slides.IChartDataCell-) | Yeni veri noktasını oluşturur ve koleksiyonun sonuna ekler. |
| [addDataPointForMapSeries(IChartDataCell value)](#addDataPointForMapSeries-com.aspose.slides.IChartDataCell-) | Yeni veri noktasını oluşturur ve koleksiyonun sonuna ekler. |
| [clear()](#clear--) | Koleksiyondaki tüm elemanları kaldırır. |
| [remove(IChartDataPoint value)](#remove-com.aspose.slides.IChartDataPoint-) | Belirtilen değeri kaldırır. |
| [removeAt(int index)](#removeAt-int-) | Belirtilen indeksdeki elemanı kaldırır. |

### get_Item(int index) {#get-Item-int-}
```
public final IChartDataPoint get_Item(int index)
```

Seri veri noktasını indeksine göre döndürür (bu koleksiyondaki sıra numarası).

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| index | int |  |

**Döndürür:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint)

### get_Item(IChartDataPoint pt) {#get-Item-com.aspose.slides.IChartDataPoint-}
```
public final int get_Item(IChartDataPoint pt)
```

Veri noktasının bu koleksiyondaki indeksini (sıra numarasını) döndürür.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| pt | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) |  |

**Döndürür:**  
int

### getDataSourceTypeForXValues() {#getDataSourceTypeForXValues--}
```
public final int getDataSourceTypeForXValues()
```

Veri noktalarının XValue özelliği nesnesinde AsCell veya AsLiteralString veya AsLiteralDouble özelliğinin geçerli olup olmadığını belirtir. Başka bir deyişle ChartDataPoint.XValue.Data özelliğinin değer türünü belirtir. Okunabilir/Yazılabilir [DataSourceType](../../com.aspose.slides/datasourcetype).

**Döndürür:**  
int

### setDataSourceTypeForXValues(int value) {#setDataSourceTypeForXValues-int-}
```
public final void setDataSourceTypeForXValues(int value)
```

Veri noktalarının XValue özelliği nesnesinde AsCell veya AsLiteralString veya AsLiteralDouble özelliğinin geçerli olup olmadığını belirtir. Başka bir deyişle ChartDataPoint.XValue.Data özelliğinin değer türünü belirtir. Okunabilir/Yazılabilir [DataSourceType](../../com.aspose.slides/datasourcetype).

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForYValues() {#getDataSourceTypeForYValues--}
```
public final int getDataSourceTypeForYValues()
```

Veri noktalarının YValue özelliği nesnesinde AsCell veya AsLiteralString veya AsLiteralDouble özelliğinin geçerli olup olmadığını belirtir. Başka bir deyişle ChartDataPoint.YValue.Data özelliğinin değer türünü belirtir. Okunabilir/Yazılabilir [DataSourceType](../../com.aspose.slides/datasourcetype).

**Döndürür:**  
int

### setDataSourceTypeForYValues(int value) {#setDataSourceTypeForYValues-int-}
```
public final void setDataSourceTypeForYValues(int value)
```

Veri noktalarının YValue özelliği nesnesinde AsCell veya AsLiteralString veya AsLiteralDouble özelliğinin geçerli olup olmadığını belirtir. Başka bir deyişle ChartDataPoint.YValue.Data özelliğinin değer türünü belirtir. Okunabilir/Yazılabilir [DataSourceType](../../com.aspose.slides/datasourcetype).

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForBubbleSizes() {#getDataSourceTypeForBubbleSizes--}
```
public final int getDataSourceTypeForBubbleSizes()
```

Veri noktalarının BubbleSize özelliği nesnesinde AsCell veya AsLiteralString veya AsLiteralDouble özelliğinin geçerli olup olmadığını belirtir. Başka bir deyişle ChartDataPoint.BubbleSize.Data özelliğinin değer türünü belirtir. Okunabilir/Yazılabilir [DataSourceType](../../com.aspose.slides/datasourcetype).

**Döndürür:**  
int

### setDataSourceTypeForBubbleSizes(int value) {#setDataSourceTypeForBubbleSizes-int-}
```
public final void setDataSourceTypeForBubbleSizes(int value)
```

Veri noktalarının BubbleSize özelliği nesnesinde AsCell veya AsLiteralString veya AsLiteralDouble özelliğinin geçerli olup olmadığını belirtir. Başka bir deyişle ChartDataPoint.BubbleSize.Data özelliğinin değer türünü belirtir. Okunabilir/Yazılabilir [DataSourceType](../../com.aspose.slides/datasourcetype).

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForValues() {#getDataSourceTypeForValues--}
```
public final int getDataSourceTypeForValues()
```

Veri noktalarının Value özelliği nesnesinde AsCell veya AsLiteralString veya AsLiteralDouble özelliğinin geçerli olup olmadığını belirtir. Başka bir deyişle ChartDataPoint.Value.Data özelliğinin değer türünü belirtir. Okunabilir/Yazılabilir [DataSourceType](../../com.aspose.slides/datasourcetype).

**Döndürür:**  
int

### setDataSourceTypeForValues(int value) {#setDataSourceTypeForValues-int-}
```
public final void setDataSourceTypeForValues(int value)
```

Veri noktalarının Value özelliği nesnesinde AsCell veya AsLiteralString veya AsLiteralDouble özelliğinin geçerli olup olmadığını belirtir. Başka bir deyişle ChartDataPoint.Value.Data özelliğinin değer türünü belirtir. Okunabilir/Yazılabilir [DataSourceType](../../com.aspose.slides/datasourcetype).

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForErrorBarsCustomValues() {#getDataSourceTypeForErrorBarsCustomValues--}
```
public final IDataSourceTypeForErrorBarsCustomValues getDataSourceTypeForErrorBarsCustomValues()
```

ChartDataPoint.ErrorBarsCustomValues özellikleri listesinde değer türlerini belirtir. Yalnızca okuma [IDataSourceTypeForErrorBarsCustomValues](../../com.aspose.slides/idatasourcetypeforerrorbarscustomvalues).

**Döndürür:**  
[IDataSourceTypeForErrorBarsCustomValues](../../com.aspose.slides/idatasourcetypeforerrorbarscustomvalues)

### getOrCreateDataPointByIdx(long index) {#getOrCreateDataPointByIdx-long-}
```
public final IChartDataPoint getOrCreateDataPointByIdx(long index)
```

Koleksiyon zaten index indeksinde bir veri noktasını içeriyorsa bu veri noktasını döndürür. Koleksiyon index==N indeksindeki veri noktasını içermiyorsa (koleksiyondaki veri noktası sayısı N’den küçük veya eşit olduğunda) eksik veri noktalarını ekler ve istenen indekse sahip son veri noktasını döndürür. Örneğin koleksiyon indeksleri {0, 1, 2} iken istenen indeks 5 ise yöntem eksik veri noktalarını ekler: {0, 1, 2, 3, 4, 5} ve indeks 5-teki veri noktasını döndürür.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| index | long | İndeks. |

**Döndürür:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - İstenen indeksli veri noktasını döndürür.

### size() {#size--}
```
public final int size()
```

Koleksiyonda gerçekte bulunan eleman sayısını alır. Yalnızca okuma int.

**Döndürür:**  
int

### copyTo(System.Array array, int arrayIndex) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int arrayIndex)
```

Belirtilen diziye kopyalar.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Kopyalanacak dizi. |
| arrayIndex | int | Kopyalamanın başlayacağı indeks. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Koleksiyona erişimin senkronize (iplik-güvenli) olup olmadığını gösteren bir değer döndürür. Yalnızca okuma boolean.

**Döndürür:**  
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Bir senkronizasyon kökü döndürür. Yalnızca okuma Object.

**Döndürür:**  
java.lang.Object

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataPoint> iterator()
```

Koleksiyon içinde yineleme yapmak için kullanılabilecek bir enumerator döndürür.

**Döndürür:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataPoint> - Koleksiyon içinde yineleme yapmak için kullanılabilecek bir IGenericEnumerator.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataPoint> iteratorJava()
```

Tüm koleksiyon için bir java iterator döndürür.

**Döndürür:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataPoint> - Tüm koleksiyon için bir java.util.Iterator.

### addDataPointForStockSeries(IChartDataCell value) {#addDataPointForStockSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForStockSeries(IChartDataCell value)
```

Yeni veri noktasını oluşturur ve koleksiyonun sonuna ekler. Stock alt türlerinden biri olan chartType’a sahip seriler için uygulanabilir (bkz. [ChartTypeCharacterizer.isChartTypeStock(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeStock-int-) yöntemi).

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Veri noktası Değeri. |

**Döndürür:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Yeni veri noktası.

### addDataPointForStockSeries(double value) {#addDataPointForStockSeries-double-}
```
public final IChartDataPoint addDataPointForStockSeries(double value)
```

Yeni veri noktasını oluşturur ve koleksiyonun sonuna ekler. Stock alt türlerinden biri olan chartType’a sahip seriler için uygulanabilir (bkz. [ChartTypeCharacterizer.isChartTypeStock(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeStock-int-) yöntemi).

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | double | Veri noktası Değeri. |

**Döndürür:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Yeni veri noktası.

### addDataPointForLineSeries(IChartDataCell value) {#addDataPointForLineSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForLineSeries(IChartDataCell value)
```

Yeni veri noktasını oluşturur ve koleksiyonun sonuna ekler. Line alt türlerinden biri olan chartType’a sahip seriler için uygulanabilir (bkz. [ChartTypeCharacterizer.isChartTypeLine(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeLine-int-) yöntemi).

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Veri noktası Değeri. |

**Döndürür:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Yeni veri noktası.

### addDataPointForLineSeries(double value) {#addDataPointForLineSeries-double-}
```
public final IChartDataPoint addDataPointForLineSeries(double value)
```

Yeni veri noktasını oluşturur ve koleksiyonun sonuna ekler. Line alt türlerinden biri olan chartType’a sahip seriler için uygulanabilir (bkz. [ChartTypeCharacterizer.isChartTypeLine(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeLine-int-) yöntemi).

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | double | Veri noktası Değeri. |

**Döndürür:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Yeni veri noktası.

### addDataPointForScatterSeries(IChartDataCell xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForScatterSeries(IChartDataCell xValue, IChartDataCell yValue)
```

Yeni veri noktasını oluşturur ve koleksiyonun sonuna ekler. Scatter alt türlerinden biri olan chartType’a sahip seriler için uygulanabilir (bkz. [ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-) yöntemi).

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Veri noktası XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Veri noktası YValue |

**Döndürür:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Yeni veri noktası.

### addDataPointForScatterSeries(double xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-double-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForScatterSeries(double xValue, IChartDataCell yValue)
```

Yeni veri noktasını oluşturur ve koleksiyonun sonuna ekler. Scatter alt türlerinden biri olan chartType’a sahip seriler için uygulanabilir (bkz. [ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-) yöntemi).

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| xValue | double | Veri noktası XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Veri noktası YValue |

**Döndürür:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Yeni veri noktası.

### addDataPointForScatterSeries(String xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-java.lang.String-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForScatterSeries(String xValue, IChartDataCell yValue)
```

Yeni veri noktasını oluşturur ve koleksiyonun sonuna ekler. Scatter alt türlerinden biri olan chartType’a sahip seriler için uygulanabilir (bkz. [ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-) yöntemi).

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| xValue | java.lang.String | Veri noktası XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Veri noktası YValue |

**Döndürür:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Yeni veri noktası.

### addDataPointForScatterSeries(IChartDataCell xValue, double yValue) {#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-double-}
```
public final IChartDataPoint addDataPointForScatterSeries(IChartDataCell xValue, double yValue)
```

Yeni veri noktasını oluşturur ve koleksiyonun sonuna ekler. Scatter alt türlerinden biri olan chartType’a sahip seriler için uygulanabilir (bkz. [ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-) yöntemi).

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Veri noktası XValue |
| yValue | double | Veri noktası YValue |

**Döndürür:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Yeni veri noktası.

### addDataPointForScatterSeries(double xValue, double yValue) {#addDataPointForScatterSeries-double-double-}
```
public final IChartDataPoint addDataPointForScatterSeries(double xValue, double yValue)
```

Yeni veri noktasını oluşturur ve koleksiyonun sonuna ekler. Scatter alt türlerinden biri olan chartType’a sahip seriler için uygulanabilir (bkz. [ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-) yöntemi).

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| xValue | double | Veri noktası XValue |
| yValue | double | Veri noktası YValue |

**Döndürür:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Yeni veri noktası.

### addDataPointForScatterSeries(String xValue, double yValue) {#addDataPointForScatterSeries-java.lang.String-double-}
```
public final IChartDataPoint addDataPointForScatterSeries(String xValue, double yValue)
```

Yeni veri noktasını oluşturur ve koleksiyonun sonuna ekler. Scatter alt türlerinden biri olan chartType’a sahip seriler için uygulanabilir (bkz. [ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-) yöntemi).

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| xValue | java.lang.String | Veri noktası XValue |
| yValue | double | Veri noktası YValue |

**Döndürür:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Yeni veri noktası.

### addDataPointForRadarSeries(IChartDataCell value) {#addDataPointForRadarSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForRadarSeries(IChartDataCell value)
```

Yeni veri noktasını oluşturur ve koleksiyonun sonuna ekler. Radar alt türlerinden biri olan chartType’a sahip seriler için uygulanabilir (bkz. [ChartTypeCharacterizer.isChartTypeRadar(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeRadar-int-) yöntemi).

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Veri noktası Değeri |

**Döndürür:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Yeni veri noktası.

### addDataPointForRadarSeries(double value) {#addDataPointForRadarSeries-double-}
```
public final IChartDataPoint addDataPointForRadarSeries(double value)
```

Yeni veri noktasını oluşturur ve koleksiyonun sonuna ekler. Radar alt türlerinden biri olan chartType’a sahip seriler için uygulanabilir (bkz. [ChartTypeCharacterizer.isChartTypeRadar(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeRadar-int-) yöntemi).

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | double | Veri noktası Değeri |

**Döndürür:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Yeni veri noktası.

### addDataPointForBarSeries(IChartDataCell value) {#addDataPointForBarSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBarSeries(IChartDataCell value)
```

Yeni veri noktasını oluşturur ve koleksiyonun sonuna ekler. Column veya Bar alt türlerinden biri olan chartType’a sahip seriler için uygulanabilir (bkz. [ChartTypeCharacterizer.isChartTypeColumn(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeColumn-int-) ve [ChartTypeCharacterizer.isChartTypeBar(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBar-int-) yöntemleri).

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Veri noktası Değeri |

**Döndürür:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Yeni veri noktası.

### addDataPointForBarSeries(double value) {#addDataPointForBarSeries-double-}
```
public final IChartDataPoint addDataPointForBarSeries(double value)
```

Yeni veri noktasını oluşturur ve koleksiyonun sonuna ekler. Column veya Bar alt türlerinden biri olan chartType’a sahip seriler için uygulanabilir (bkz. [ChartTypeCharacterizer.isChartTypeColumn(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeColumn-int-) ve [ChartTypeCharacterizer.isChartTypeBar(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBar-int-) yöntemleri).

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | double | Veri noktası Değeri |

**Döndürür:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Yeni veri noktası.

### addDataPointForAreaSeries(IChartDataCell value) {#addDataPointForAreaSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForAreaSeries(IChartDataCell value)
```

Yeni veri noktasını oluşturur ve koleksiyonun sonuna ekler. Area alt türlerinden biri olan chartType’a sahip seriler için uygulanabilir (bkz. [ChartTypeCharacterizer.isChartTypeArea(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeArea-int-) yöntemi).

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Veri noktası Değeri |

**Döndürür:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Yeni veri noktası.

### addDataPointForAreaSeries(double value) {#addDataPointForAreaSeries-double-}
```
public final IChartDataPoint addDataPointForAreaSeries(double value)
```

Yeni veri noktasını oluşturur ve koleksiyonun sonuna ekler. Area alt türlerinden biri olan chartType’a sahip seriler için uygulanabilir (bkz. [ChartTypeCharacterizer.isChartTypeArea(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeArea-int-) yöntemi).

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | double | Veri noktası Değeri |

**Döndürür:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Yeni veri noktası.

### addDataPointForPieSeries(IChartDataCell value) {#addDataPointForPieSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForPieSeries(IChartDataCell value)
```

Yeni veri noktasını oluşturur ve koleksiyonun sonuna ekler. Pie alt türlerinden biri olan chartType’a sahip seriler için uygulanabilir (bkz. [ChartTypeCharacterizer.isChartTypePie(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypePie-int-) yöntemi).

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Veri noktası Değeri |

**Döndürür:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Yeni veri noktası.

### addDataPointForPieSeries(double value) {#addDataPointForPieSeries-double-}
```
public final IChartDataPoint addDataPointForPieSeries(double value)
```

Yeni veri noktasını oluşturur ve koleksiyonun sonuna ekler. Pie alt türlerinden biri olan chartType’a sahip seriler için uygulanabilir (bkz. [ChartTypeCharacterizer.isChartTypePie(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypePie-int-) yöntemi).

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | double | Veri noktası Değeri |

**Döndürür:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Yeni veri noktası.

### addDataPointForDoughnutSeries(IChartDataCell value) {#addDataPointForDoughnutSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForDoughnutSeries(IChartDataCell value)
```

Yeni veri noktasını oluşturur ve koleksiyonun sonuna ekler. Doughnut alt türlerinden biri olan chartType’a sahip seriler için uygulanabilir (bkz. [ChartTypeCharacterizer.isChartTypeDoughnut(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeDoughnut-int-) yöntemi).

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Veri noktası Değeri |

**Döndürür:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Yeni veri noktası.

### addDataPointForDoughnutSeries(double value) {#addDataPointForDoughnutSeries-double-}
```
public final IChartDataPoint addDataPointForDoughnutSeries(double value)
```

Yeni veri noktasını oluşturur ve koleksiyonun sonuna ekler. Doughnut alt türlerinden biri olan chartType’a sahip seriler için uygulanabilir (bkz. [ChartTypeCharacterizer.isChartTypeDoughnut(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeDoughnut-int-) yöntemi).

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | double | Veri noktası Değeri |

**Döndürür:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Yeni veri noktası.

### addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```

Yeni veri noktasını oluşturur ve koleksiyonun sonuna ekler. Bubble alt türlerinden biri olan chartType’a sahip seriler için uygulanabilir (bkz. [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) yöntemi).

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Veri noktası XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Veri noktası YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Veri noktası BubbleSize |

**Döndürür:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Yeni veri noktası.

### addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```

Yeni veri noktasını oluşturur ve koleksiyonun sonuna ekler. Bubble alt türlerinden biri olan chartType’a sahip seriler için uygulanabilir (bkz. [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) yöntemi).

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| xValue | double | Veri noktası XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Veri noktası YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Veri noktası BubbleSize |

**Döndürür:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Yeni veri noktası.

### addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```

Yeni veri noktasını oluşturur ve koleksiyonun sonuna ekler. Bubble alt türlerinden biri olan chartType’a sahip seriler için uygulanabilir (bkz. [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) yöntemi).

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| xValue | java.lang.String | Veri noktası XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Veri noktası YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Veri noktası BubbleSize |

**Döndürür:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Yeni veri noktası.

### addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, IChartDataCell bubbleSize)
```

Yeni veri noktasını oluşturur ve koleksiyonun sonuna ekler. Bubble alt türlerinden biri olan chartType’a sahip seriler için uygulanabilir (bkz. [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) yöntemi).

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Veri noktası XValue |
| yValue | double | Veri noktası YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Veri noktası BubbleSize |

**Döndürür:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Yeni veri noktası.

### addDataPointForBubbleSeries(double xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-double-double-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(double xValue, double yValue, IChartDataCell bubbleSize)
```

Yeni veri noktasını oluşturur ve koleksiyonun sonuna ekler. Bubble alt türlerinden biri olan chartType’a sahip seriler için uygulanabilir (bkz. [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) yöntemi).

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| xValue | double | Veri noktası XValue |
| yValue | double | Veri noktası YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Veri noktası BubbleSize |

**Döndürür:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Yeni veri noktası.

### addDataPointForBubbleSeries(String xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-double-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(String xValue, double yValue, IChartDataCell bubbleSize)
```

Yeni veri noktasını oluşturur ve koleksiyonun sonuna ekler. Bubble alt türlerinden biri olan chartType’a sahip seriler için uygulanabilir (bkz. [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) yöntemi).

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| xValue | java.lang.String | Veri noktası XValue |
| yValue | double | Veri noktası YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Veri noktası BubbleSize |

**Döndürür:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Yeni veri noktası.

### addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, double bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, double bubbleSize)
```

Yeni veri noktasını oluşturur ve koleksiyonun sonuna ekler. Bubble alt türlerinden biri olan chartType’a sahip seriler için uygulanabilir (bkz. [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) yöntemi).

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Veri noktası XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Veri noktası YValue |
| bubbleSize | double | Veri noktası BubbleSize |

**Döndürür:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Yeni veri noktası.

### addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, double bubbleSize) {#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, double bubbleSize)
```

Yeni veri noktasını oluşturur ve koleksiyonun sonuna ekler. Bubble alt türlerinden biri olan chartType’a sahip seriler için uygulanabilir (bkz. [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) yöntemi).

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| xValue | double | Veri noktası XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Veri noktası YValue |
| bubbleSize | double | Veri noktası BubbleSize |

**Döndürür:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Yeni veri noktası.

### addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, double bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, double bubbleSize)
```

Yeni veri noktasını oluşturur ve koleksiyonun sonuna ekler. Bubble alt türlerinden biri olan chartType’a sahip seriler için uygulanabilir (bkz. [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) yöntemi).

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| xValue | java.lang.String | Veri noktası XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Veri noktası YValue |
| bubbleSize | double | Veri noktası BubbleSize |

**Döndürür:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Yeni veri noktası.

### addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, double bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, double bubbleSize)
```

Yeni veri noktasını oluşturur ve koleksiyonun sonuna ekler. Bubble alt türlerinden biri olan chartType’a sahip seriler için uygulanabilir (bkz. [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) yöntemi).

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Veri noktası XValue |
| yValue | double | Veri noktası YValue |
| bubbleSize | double | Veri noktası BubbleSize |

**Döndürür:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Yeni veri noktası.

### addDataPointForBubbleSeries(double xValue, double yValue, double bubbleSize) {#addDataPointForBubbleSeries-double-double-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(double xValue, double yValue, double bubbleSize)
```

Yeni veri noktasını oluşturur ve koleksiyonun sonuna ekler. Bubble alt türlerinden biri olan chartType’a sahip seriler için uygulanabilir (bkz. [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) yöntemi).

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| xValue | double | Veri noktası XValue |
| yValue | double | Veri noktası YValue |
| bubbleSize | double | Veri noktası BubbleSize |

**Döndürür:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Yeni veri noktası.

### addDataPointForBubbleSeries(String xValue, double yValue, double bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-double-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(String xValue, double yValue, double bubbleSize)
```

Yeni veri noktasını oluşturur ve koleksiyonun sonuna ekler. Bubble alt türlerinden biri olan chartType’a sahip seriler için uygulanabilir (bkz. [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) yöntemi).

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| xValue | java.lang.String | Veri noktası XValue |
| yValue | double | Veri noktası YValue |
| bubbleSize | double | Veri noktası BubbleSize |

**Döndürür:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Yeni veri noktası.

### addDataPointForSurfaceSeries(IChartDataCell value) {#addDataPointForSurfaceSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForSurfaceSeries(IChartDataCell value)
```

Yeni veri noktasını oluşturur ve koleksiyonun sonuna ekler. Surface alt türlerinden biri olan chartType’a sahip seriler için uygulanabilir (bkz. [ChartTypeCharacterizer.isChartTypeSurface(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeSurface-int-) yöntemi).

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Veri noktası Değeri |

**Döndürür:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Yeni veri noktası.

### addDataPointForSurfaceSeries(double value) {#addDataPointForSurfaceSeries-double-}
```
public final IChartDataPoint addDataPointForSurfaceSeries(double value)
```

Yeni veri noktasını oluşturur ve koleksiyonun sonuna ekler. Surface alt türlerinden biri olan chartType’a sahip seriler için uygulanabilir (bkz. [ChartTypeCharacterizer.isChartTypeSurface(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeSurface-int-) yöntemi).

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | double | Veri noktası Değeri |

**Döndürür:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Yeni veri noktası.

### addDataPointForSunburstSeries(IChartDataCell sizeValue) {#addDataPointForSunburstSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForSunburstSeries(IChartDataCell sizeValue)
```

Yeni veri noktasını oluşturur ve koleksiyonun sonuna ekler. Sunburst grafik tipine sahip seriler için uygulanabilir.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| sizeValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Veri noktası SizeValue |

**Döndürür:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Yeni veri noktası.

### addDataPointForTreemapSeries(IChartDataCell sizeValue) {#addDataPointForTreemapSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForTreemapSeries(IChartDataCell sizeValue)
```

Yeni veri noktasını oluşturur ve koleksiyonun sonuna ekler. Treemap grafik tipine sahip seriler için uygulanabilir.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| sizeValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Veri noktası SizeValue |

**Döndürür:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Yeni veri noktası.

### addDataPointForBoxAndWhiskerSeries(IChartDataCell value) {#addDataPointForBoxAndWhiskerSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBoxAndWhiskerSeries(IChartDataCell value)
```

Yeni veri noktasını oluşturur ve koleksiyonun sonuna ekler. BoxAndWhisker grafik tipine sahip seriler için uygulanabilir.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Veri noktası Değeri |

**Döndürür:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Yeni veri noktası.

### addDataPointForWaterfallSeries(IChartDataCell value) {#addDataPointForWaterfallSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForWaterfallSeries(IChartDataCell value)
```

Yeni veri noktasını oluşturur ve koleksiyonun sonuna ekler. Waterfall grafik tipine sahip seriler için uygulanabilir.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Veri noktası Değeri |

**Döndürür:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Yeni veri noktası.

### addDataPointForHistogramSeries(IChartDataCell value) {#addDataPointForHistogramSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForHistogramSeries(IChartDataCell value)
```

Yeni veri noktasını oluşturur ve koleksiyonun sonuna ekler. Histogram grafik tipine sahip seriler için uygulanabilir.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Veri noktası Değeri |

**Döndürür:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Yeni veri noktası.

### addDataPointForFunnelSeries(IChartDataCell value) {#addDataPointForFunnelSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForFunnelSeries(IChartDataCell value)
```

Yeni veri noktasını oluşturur ve koleksiyonun sonuna ekler. Funnel grafik tipine sahip seriler için uygulanabilir.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Veri noktası Değeri |

**Döndürür:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Yeni veri noktası.

### addDataPointForMapSeries(IChartDataCell value) {#addDataPointForMapSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForMapSeries(IChartDataCell value)
```

Yeni veri noktasını oluşturur ve koleksiyonun sonuna ekler. Map grafik tipine sahip seriler için uygulanabilir.

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


**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Veri noktası ColorValue |

**Döndürür:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Yeni veri noktası.

### clear() {#clear--}
```
public final void clear()
```

Koleksiyondaki tüm elemanları kaldırır.

### remove(IChartDataPoint value) {#remove-com.aspose.slides.IChartDataPoint-}
```
public final void remove(IChartDataPoint value)
```

Belirtilen değeri kaldırır.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | Değer. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Belirtilen indeksdeki elemanı kaldırır.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| index | int | Kaldırılacak veri noktasının indeksi. |