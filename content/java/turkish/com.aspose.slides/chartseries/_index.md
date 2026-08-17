---
title: ChartSeries
second_title: Aspose.Slides Java API Referansı
description: Bir grafik serisini temsil eder.
type: docs
url: /tr/com.aspose.slides/chartseries/
---
**Kalıtım:**
java.lang.Object

**Uygulanan Tüm Arayüzler:**
[com.aspose.slides.IChartSeries](../../com.aspose.slides/ichartseries), com.aspose.slides.IDOMObject
```
public class ChartSeries implements IChartSeries, IDOMObject
```

Bir grafik serisini temsil eder.
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getChart()](#getChart--) | Üst grafiği döndürür. |
| [getExplosion()](#getExplosion--) | Açık bir pasta diliminin, pasta grafiğinin merkezinden olan mesafesi, pasta çapının yüzde olarak ifade edilir. |
| [setExplosion(int value)](#setExplosion-int-) | Açık bir pasta diliminin, pasta grafiğinin merkezinden olan mesafesi, pasta çapının yüzde olarak ifade edilir. |
| [getSmooth()](#getSmooth--) | Eğri yumuşatmayı temsil eder. |
| [setSmooth(boolean value)](#setSmooth-boolean-) | Eğri yumuşatmayı temsil eder. |
| [getName()](#getName--) | Seri adını döndürür. |
| [getDataPoints()](#getDataPoints--) | Bu serinin veri noktalarının koleksiyonunu döndürür. |
| [getType()](#getType--) | Bu serinin bir tipini döndürür. |
| [setType(int value)](#setType-int-) | Bu serinin bir tipini döndürür. |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | Bu serinin ikincil eksende çizilip çizilmediğini gösterir. |
| [setPlotOnSecondAxis(boolean value)](#setPlotOnSecondAxis-boolean-) | Bu serinin ikincil eksende çizilip çizilmediğini gösterir. |
| [getParentSeriesGroup()](#getParentSeriesGroup--) | ParentSeriesGroup. |
| [getFormat()](#getFormat--) | Bir serinin formatını döndürür. |
| [getOrder()](#getOrder--) | Bir serinin sırasını döndürür. |
| [setOrder(int value)](#setOrder-int-) | Bir serinin sırasını döndürür. |
| [getLabels()](#getLabels--) | Bir serinin Etiketlerini döndürür. |
| [getTrendLines()](#getTrendLines--) | Seri eğilim çizgilerinin koleksiyonu. |
| [getErrorBarsXFormat()](#getErrorBarsXFormat--) | X yönündeki serinin ErrorBars'ını temsil eder. |
| [getErrorBarsYFormat()](#getErrorBarsYFormat--) | Y yönündeki serinin ErrorBars'ını temsil eder. |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | Bu seriye ilgili lejand girişini temsil eder. Salt okunur [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties). |
| [getNumberFormatOfValues()](#getNumberFormatOfValues--) | NumberFormatOfValues. |
| [setNumberFormatOfValues(String value)](#setNumberFormatOfValues-java.lang.String-) | NumberFormatOfValues. |
| [getNumberFormatOfXValues()](#getNumberFormatOfXValues--) | NumberFormatOfXValues. |
| [setNumberFormatOfXValues(String value)](#setNumberFormatOfXValues-java.lang.String-) | NumberFormatOfXValues. |
| [getNumberFormatOfYValues()](#getNumberFormatOfYValues--) | NumberFormatOfYValues. |
| [setNumberFormatOfYValues(String value)](#setNumberFormatOfYValues-java.lang.String-) | NumberFormatOfYValues. |
| [getNumberFormatOfBubbleSizes()](#getNumberFormatOfBubbleSizes--) | NumberFormatOfBubbleSizes. |
| [setNumberFormatOfBubbleSizes(String value)](#setNumberFormatOfBubbleSizes-java.lang.String-) | NumberFormatOfBubbleSizes. |
| [getMarker()](#getMarker--) | Marker. |
| [getBar3DShape()](#getBar3DShape--) | 3D çubuk grafiğinin bir serisinin şeklini belirler. |
| [setBar3DShape(int value)](#setBar3DShape-int-) | 3D çubuk grafiğinin bir serisinin şeklini belirler. |
| [getInvertIfNegative()](#getInvertIfNegative--) | Değer negatif olduğunda çubuk, sütun veya balon serisinin renklerinin ters çevrilmesini belirler. |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | Değer negatif olduğunda çubuk, sütun veya balon serisinin renklerinin ters çevrilmesini belirler. |
| [getInvertedSolidFillColor()](#getInvertedSolidFillColor--) | Seri için ters katı rengi belirler. |
| [getAutomaticSeriesColor()](#getAutomaticSeriesColor--) | Seri dizini ve grafik stiline göre otomatik bir renk döndürür. |
| [getShowInnerPoints()](#getShowInnerPoints--) | İç noktaları temsil eder. |
| [setShowInnerPoints(boolean value)](#setShowInnerPoints-boolean-) | İç noktaları temsil eder. |
| [getShowOutlierPoints()](#getShowOutlierPoints--) | Uç değer noktalarını temsil eder. |
| [setShowOutlierPoints(boolean value)](#setShowOutlierPoints-boolean-) | Uç değer noktalarını temsil eder. |
| [getShowMeanMarkers()](#getShowMeanMarkers--) | Ortalama işaretçilerini temsil eder. |
| [setShowMeanMarkers(boolean value)](#setShowMeanMarkers-boolean-) | Ortalama işaretçilerini temsil eder. |
| [getShowMeanLine()](#getShowMeanLine--) | Ortalama çizgiyi temsil eder. |
| [setShowMeanLine(boolean value)](#setShowMeanLine-boolean-) | Ortalama çizgiyi temsil eder. |
| [getQuartileMethod()](#getQuartileMethod--) | Çeyrek yöntemini temsil eder. |
| [setQuartileMethod(int value)](#setQuartileMethod-int-) | Çeyrek yöntemini temsil eder. |
| [getShowConnectorLines()](#getShowConnectorLines--) | Bağlayıcı çizgileri temsil eder. |
| [setShowConnectorLines(boolean value)](#setShowConnectorLines-boolean-) | Bağlayıcı çizgileri temsil eder. |
| [getParentLabelLayout()](#getParentLabelLayout--) | Üst kategori etiketlerinin düzenini temsil eder. |
| [setParentLabelLayout(int value)](#setParentLabelLayout-int-) | Üst kategori etiketlerinin düzenini temsil eder. |
| [hasUpDownBars()](#hasUpDownBars--) | Çizgi veya Stok grafiğinin yükseliş/düşüş çubukları olup olmadığını belirler. |
| [getGapWidth()](#getGapWidth--) | Çubuk veya sütun kümeleri arasındaki boşluğu, çubuk veya sütun genişliğinin yüzde olarak belirler. |
| [getGapDepth()](#getGapDepth--) | 3D grafikte veri serileri arasındaki mesafeyi, işaretçi genişliğinin yüzde olarak döndürür veya ayarlar. |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | İlk pasta veya halka grafik diliminin açısını derece cinsinden (yukarıdan saat yönünde, 0'dan 360 dereceye) belirler. |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | Halka grafiğindeki deliğin boyutunu belirler (grafik alanının %10 ile %90 arasında olabilir). |
| [getOverlap()](#getOverlap--) | 2D grafiklerde çubukların ve sütunların ne kadar çakıştığını yüzde olarak belirler (-%100 ile %100 arasında). |
| [getSecondPieSize()](#getSecondPieSize--) | Pasta-üzerine-pasta veya çubuk-üzerine-pasta grafiğinde ikinci pasta veya çubuğun boyutunu, ilk pastanın boyutunun yüzde olarak (%5 ile %200 arasında) belirler. |
| [hasSeriesLines()](#hasSeriesLines--) | Bu seri ve benzer seriler için seri çizgileri olup olmadığını belirler. |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | Balon grafiğinde balon boyutu değerlerinin nasıl gösterileceğini belirler. |
| [getPieSplitPosition()](#getPieSplitPosition--) | Pasta-üzerine-pasta veya çubuk-üzerine-pasta grafiğinde ikinci pasta veya çubukta hangi veri noktalarının olacağını belirlemek için kullanılacak bir değeri belirtir. |
| [getPieSplitBy()](#getPieSplitBy--) | Pasta-üzerine-pasta veya çubuk-üzerine-pasta grafiğinde ikinci pasta veya çubukta hangi veri noktalarının bulunacağını belirleme şeklini belirtir. |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | Özel bölme bilgisi, özel bölmeli pasta-üzerine-pasta veya çubuk-üzerine-pasta grafiği için. |
| [isColorVaried()](#isColorVaried--) | Serideki her veri işaretçisinin farklı bir renge sahip olmasını belirler. |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | Balon grafiği için ölçek faktörünü (varsayılan boyutun %0 ile %300 arasında) belirler. |
| [getSlide()](#getSlide--) | FillFormat'un üst slaytını döndürür. |
| [getPresentation()](#getPresentation--) | FillFormat'un üst sunumunu döndürür. |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate nesnesini döndürür. Salt okunur IDOMObject.

**Döndürür:**
com.aspose.slides.IDOMObject

### getChart() {#getChart--}
```
public final IChart getChart()
```

Üst grafiği döndürür. Salt okunur [IChart](../../com.aspose.slides/ichart).

**Döndürür:**
[IChart](../../com.aspose.slides/ichart)

### getExplosion() {#getExplosion--}
```
public final int getExplosion()
```

Açık bir pasta diliminin, pasta grafiğinin merkezinden olan mesafesi, pasta çapının yüzde olarak ifade edilir. Okuma/Yazma int.

**Döndürür:**
int

### setExplosion(int value) {#setExplosion-int-}
```
public final void setExplosion(int value)
```

Açık bir pasta diliminin, pasta grafiğinin merkezinden olan mesafesi, pasta çapının yüzde olarak ifade edilir. Okuma/Yazma int.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getSmooth() {#getSmooth--}
```
public final boolean getSmooth()
```

Eğri yumuşatmayı temsil eder. Çizgi grafiği veya dağılım grafiği için eğri yumuşatma etkinse true döner. Yalnızca çizgi ve çizgiyle bağlanan dağılım grafiklerine uygulanır. Okuma/Yazma boolean.

**Döndürür:**
boolean

### setSmooth(boolean value) {#setSmooth-boolean-}
```
public final void setSmooth(boolean value)
```

Eğri yumuşatmayı temsil eder. Çizgi grafiği veya dağılım grafiği için eğri yumuşatma etkinse true döner. Yalnızca çizgi ve çizgiyle bağlanan dağılım grafiklerine uygulanır. Okuma/Yazma boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getName() {#getName--}
```
public final IStringChartValue getName()
```

Seri adını döndürür. Salt okunur [IStringChartValue](../../com.aspose.slides/istringchartvalue).

**Döndürür:**
[IStringChartValue](../../com.aspose.slides/istringchartvalue)

### getDataPoints() {#getDataPoints--}
```
public final IChartDataPointCollection getDataPoints()
```

Bu serinin veri noktalarının koleksiyonunu döndürür. Salt okunur [IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection).

**Döndürür:**
[IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection)

### getType() {#getType--}
```
public final int getType()
```

Bu serinin bir tipini döndürür. Okuma/Yazma [ChartType](../../com.aspose.slides/charttype).

**Döndürür:**
int

### setType(int value) {#setType-int-}
```
public final void setType(int value)
```

Bu serinin bir tipini döndürür. Okuma/Yazma [ChartType](../../com.aspose.slides/charttype).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getPlotOnSecondAxis() {#getPlotOnSecondAxis--}
```
public final boolean getPlotOnSecondAxis()
```

Bu serinin ikincil eksende çizilip çizilmediğini gösterir. Okuma/Yazma boolean.

**Döndürür:**
boolean

### setPlotOnSecondAxis(boolean value) {#setPlotOnSecondAxis-boolean-}
```
public final void setPlotOnSecondAxis(boolean value)
```

Bu serinin ikincil eksende çizilip çizilmediğini gösterir. Okuma/Yazma boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getParentSeriesGroup() {#getParentSeriesGroup--}
```
public final IChartSeriesGroup getParentSeriesGroup()
```

ParentSeriesGroup. Salt okunur [IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup).

**Döndürür:**
[IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup)

### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

Bir serinin formatını döndürür. Salt okunur [IFormat](../../com.aspose.slides/iformat).

**Döndürür:**
[IFormat](../../com.aspose.slides/iformat)

### getOrder() {#getOrder--}
```
public final int getOrder()
```

Bir serinin sırasını döndürür. Okuma/Yazma int.

**Döndürür:**
int

### setOrder(int value) {#setOrder-int-}
```
public final void setOrder(int value)
```

Bir serinin sırasını döndürür. Okuma/Yazma int.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getLabels() {#getLabels--}
```
public final IDataLabelCollection getLabels()
```

Bir serinin Etiketlerini döndürür. Salt okunur [IDataLabelCollection](../../com.aspose.slides/idatalabelcollection).

**Döndürür:**
[IDataLabelCollection](../../com.aspose.slides/idatalabelcollection)

### getTrendLines() {#getTrendLines--}
```
public final ITrendlineCollection getTrendLines()
```

Seri eğilim çizgilerinin koleksiyonu. Salt okunur [ITrendlineCollection](../../com.aspose.slides/itrendlinecollection).

--------------------

Eğim Çizgileri, yığılmamış 2D alan, çubuk, sütun, çizgi, stok, xy (dağılım) ve balon grafiklerindeki veri serileri için mevcuttur (null değildir). Yığılmış veya 3D olan herhangi bir grafik tipindeki veri serileri için eğim çizgisi mevcut değildir. Eğim çizgileri ayrıca radar, pasta, yüzey veya halka grafikler için mevcut değildir.

**Döndürür:**
[ITrendlineCollection](../../com.aspose.slides/itrendlinecollection)

### getErrorBarsXFormat() {#getErrorBarsXFormat--}
```
public final IErrorBarsFormat getErrorBarsXFormat()
```

X yönündeki serinin ErrorBars'ını temsil eder. Salt okunur [IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat).

--------------------

X yönündeki ErrorBars, alan, çubuk, dağılım ve balon tipindeki seriler için kullanılabilir. Diğer grafik tipleri için bu özellik null döndürür (3D grafikler dahil). Özel değerlerde değeri belirtmek için DataPoints koleksiyonunu ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues) özelliği ile) kullanın.

**Döndürür:**
[IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)

### getErrorBarsYFormat() {#getErrorBarsYFormat--}
```
public final IErrorBarsFormat getErrorBarsYFormat()
```

Y yönündeki serinin ErrorBars'ını temsil eder. Salt okunur [IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat).

--------------------

Y yönündeki ErrorBars, alan, çubuk, çizgi, dağılım ve balon tipindeki seriler için kullanılabilir. Diğer grafik tipleri için bu özellik null döndürür (3D grafikler dahil). Özel değerlerde değeri belirtmek için DataPoints koleksiyonunu ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues) özelliği ile) kullanın.

**Döndürür:**
[IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)

### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public final ILegendEntryProperties getRelatedLegendEntry()
```

Bu seriye ilgili lejand girişini temsil eder. Salt okunur [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**Döndürür:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)

### getNumberFormatOfValues() {#getNumberFormatOfValues--}
```
public final String getNumberFormatOfValues()
```

NumberFormatOfValues. Okuma/Yazma String.

**Döndürür:**
java.lang.String

### setNumberFormatOfValues(String value) {#setNumberFormatOfValues-java.lang.String-}
```
public final void setNumberFormatOfValues(String value)
```

NumberFormatOfValues. Okuma/Yazma String.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |

### getNumberFormatOfXValues() {#getNumberFormatOfXValues--}
```
public final String getNumberFormatOfXValues()
```

NumberFormatOfXValues. Okuma/Yazma String.

**Döndürür:**
java.lang.String

### setNumberFormatOfXValues(String value) {#setNumberFormatOfXValues-java.lang.String-}
```
public final void setNumberFormatOfXValues(String value)
```

NumberFormatOfXValues. Okuma/Yazma String.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |

### getNumberFormatOfYValues() {#getNumberFormatOfYValues--}
```
public final String getNumberFormatOfYValues()
```

NumberFormatOfYValues. Okuma/Yazma String.

**Döndürür:**
java.lang.String

### setNumberFormatOfYValues(String value) {#setNumberFormatOfYValues-java.lang.String-}
```
public final void setNumberFormatOfYValues(String value)
```

NumberFormatOfYValues. Okuma/Yazma String.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |

### getNumberFormatOfBubbleSizes() {#getNumberFormatOfBubbleSizes--}
```
public final String getNumberFormatOfBubbleSizes()
```

NumberFormatOfBubbleSizes. Okuma/Yazma String.

**Döndürür:**
java.lang.String

### setNumberFormatOfBubbleSizes(String value) {#setNumberFormatOfBubbleSizes-java.lang.String-}
```
public final void setNumberFormatOfBubbleSizes(String value)
```

NumberFormatOfBubbleSizes. Okuma/Yazma String.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |

### getMarker() {#getMarker--}
```
public final IMarker getMarker()
```

Marker. Salt okunur [IMarker](../../com.aspose.slides/imarker).

**Döndürür:**
[IMarker](../../com.aspose.slides/imarker)

### getBar3DShape() {#getBar3DShape--}
```
public final int getBar3DShape()
```

3D çubuk grafiğinin bir serisinin şeklini belirler. Bu özelliğin değerinin değiştirilmesi, serinin Tipinin otomatik olarak değişmesine neden olabilir. Okuma/Yazma [ChartShapeType](../../com.aspose.slides/chartshapetype).

**Döndürür:**
int

### setBar3DShape(int value) {#setBar3DShape-int-}
```
public final void setBar3DShape(int value)
```

3D çubuk grafiğinin bir serisinin şeklini belirler. Bu özelliğin değerinin değiştirilmesi, serinin Tipinin otomatik olarak değişmesine neden olabilir. Okuma/Yazma [ChartShapeType](../../com.aspose.slides/chartshapetype).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getInvertIfNegative() {#getInvertIfNegative--}
```
public final boolean getInvertIfNegative()
```

Değer negatif olduğunda çubuk, sütun veya balon serisinin renklerini ters çevirmesini belirler. Okuma/Yazma boolean.

**Döndürür:**
boolean

### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public final void setInvertIfNegative(boolean value)
```

Değer negatif olduğunda çubuk, sütun veya balon serisinin renklerini ters çevirmesini belirler. Okuma/Yazma boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getInvertedSolidFillColor() {#getInvertedSolidFillColor--}
```
public final IColorFormat getInvertedSolidFillColor()
```
Seri için ters katı rengi belirler. Renk ayarını uygulamak için seri formatının FillType özelliğini FillType.Solid olarak ayarlayın. Okuma/yazma [ColorFormat](../../com.aspose.slides/colorformat).

**Döndürür:**  
[IColorFormat](../../com.aspose.slides/icolorformat)

### getAutomaticSeriesColor() {#getAutomaticSeriesColor--}
```
public final Color getAutomaticSeriesColor()
```

Seri indeksine ve grafik stiline göre serinin otomatik rengini döndürür. Bu renk, FillType NotDefined ise varsayılan olarak kullanılır.

**Döndürür:**  
java.awt.Color - java.awt.Color nesnesi.

### getShowInnerPoints() {#getShowInnerPoints--}
```
public final boolean getShowInnerPoints()
```

İç noktaları temsil eder. BoxAndWhisker grafiğinde iç noktalar gösteriliyorsa True. Yalnızca BoxAndWhisker grafiklerinde uygulanır. Okuma/yazma boolean.

**Döndürür:**  
boolean

### setShowInnerPoints(boolean value) {#setShowInnerPoints-boolean-}
```
public final void setShowInnerPoints(boolean value)
```

İç noktaları temsil eder. BoxAndWhisker grafiğinde iç noktalar gösteriliyorsa True. Yalnızca BoxAndWhisker grafiklerinde uygulanır. Okuma/yazma boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getShowOutlierPoints() {#getShowOutlierPoints--}
```
public final boolean getShowOutlierPoints()
```

Uç nokta noktalarını temsil eder. BoxAndWhisker grafiğinde uç noktalar gösteriliyorsa True. Yalnızca BoxAndWhisker grafiklerinde uygulanır. Okuma/yazma boolean.

**Döndürür:**  
boolean

### setShowOutlierPoints(boolean value) {#setShowOutlierPoints-boolean-}
```
public final void setShowOutlierPoints(boolean value)
```

Uç nokta noktalarını temsil eder. BoxAndWhisker grafiğinde uç noktalar gösteriliyorsa True. Yalnızca BoxAndWhisker grafiklerinde uygulanır. Okuma/yazma boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getShowMeanMarkers() {#getShowMeanMarkers--}
```
public final boolean getShowMeanMarkers()
```

Ortalama işaretçilerini temsil eder. BoxAndWhisker grafiğinde ortalama işaretçileri gösteriliyorsa True. Yalnızca BoxAndWhisker grafiklerinde uygulanır. Okuma/yazma boolean.

**Döndürür:**  
boolean

### setShowMeanMarkers(boolean value) {#setShowMeanMarkers-boolean-}
```
public final void setShowMeanMarkers(boolean value)
```

Ortalama işaretçilerini temsil eder. BoxAndWhisker grafiğinde ortalama işaretçileri gösteriliyorsa True. Yalnızca BoxAndWhisker grafiklerinde uygulanır. Okuma/yazma boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getShowMeanLine() {#getShowMeanLine--}
```
public final boolean getShowMeanLine()
```

Ortalama çizgisini temsil eder. BoxAndWhisker grafiğinde ortalama çizgi gösteriliyorsa True. Yalnızca BoxAndWhisker grafiklerinde uygulanır. Okuma/yazma boolean.

**Döndürür:**  
boolean

### setShowMeanLine(boolean value) {#setShowMeanLine-boolean-}
```
public final void setShowMeanLine(boolean value)
```

Ortalama çizgisini temsil eder. BoxAndWhisker grafiğinde ortalama çizgi gösteriliyorsa True. Yalnızca BoxAndWhisker grafiklerinde uygulanır. Okuma/yazma boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getQuartileMethod() {#getQuartileMethod--}
```
public final int getQuartileMethod()
```

Çeyrek değer yöntemini temsil eder. Yalnızca BoxAndWhisker grafiklerinde uygulanır.

**Döndürür:**  
int

### setQuartileMethod(int value) {#setQuartileMethod-int-}
```
public final void setQuartileMethod(int value)
```

Çeyrek değer yöntemini temsil eder. Yalnızca BoxAndWhisker grafiklerinde uygulanır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getShowConnectorLines() {#getShowConnectorLines--}
```
public final boolean getShowConnectorLines()
```

Bağlayıcı hatları temsil eder. Yalnızca Waterfall grafiklerinde uygulanır.

**Döndürür:**  
boolean

### setShowConnectorLines(boolean value) {#setShowConnectorLines-boolean-}
```
public final void setShowConnectorLines(boolean value)
```

Bağlayıcı hatları temsil eder. Yalnızca Waterfall grafiklerinde uygulanır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getParentLabelLayout() {#getParentLabelLayout--}
```
public final int getParentLabelLayout()
```

Üst kategori etiketlerinin düzenini temsil eder. Yalnızca Treemap grafiklerinde uygulanır.

**Döndürür:**  
int

### setParentLabelLayout(int value) {#setParentLabelLayout-int-}
```
public final void setParentLabelLayout(int value)
```

Üst kategori etiketlerinin düzenini temsil eder. Yalnızca Treemap grafiklerinde uygulanır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### hasUpDownBars() {#hasUpDownBars--}
```
public final boolean hasUpDownBars()
```

Line- veya Stock-grafiğinde yukarı/aşağı çubuklarının olup olmadığını belirler. Bu, yalnızca bu serinin değil, üst seriler grubunun tüm serilerinin bir yansımasıdır – ilgili grup özelliğinin bir projeksiyonudur. Bu nedenle özellik sadece okuma-yazma değildir. Üst seriler grubuna erişmek için ParentSeriesGroup özelliğini kullanın. Değeri değiştirmek için ParentSeriesGroup.UpDownBars.HasUpDownBars okuma/yazma özelliğini kullanın. Üst seriler grubunun UpDownBars özelliğini kullanarak çubukları biçimlendirin. Okuma-yazma boolean.

--------------------

Bu, ParentSeriesGroup.UpDownBars.HasUpDownBars özelliğinin bir projeksiyonudur.

**Döndürür:**  
boolean

### getGapWidth() {#getGapWidth--}
```
public final int getGapWidth()
```

Sütun veya çubuk kümeleri arasındaki boşluğu, çubuk veya sütun genişliğinin yüzdesi olarak belirtir. Bu, yalnızca bu serinin değil, üst seriler grubunun tüm serilerinin bir yansımasıdır – ilgili grup özelliğinin bir projeksiyonudur. Bu nedenle özellik sadece okuma-yazmadır. Üst seriler grubuna erişmek için ParentSeriesGroup özelliğini kullanın. Değeri değiştirmek için ParentSeriesGroup.GapWidth okuma/yazma özelliğini kullanın. Okuma-yazma int.

--------------------

Bu, ParentSeriesGroup.GapWidth özelliğinin bir projeksiyonudur.

**Döndürür:**  
int

### getGapDepth() {#getGapDepth--}
```
public final int getGapDepth()
```

3D grafikte veri serileri arasındaki mesafeyi, işaretleyici genişliğinin yüzdesi olarak döndürür veya ayarlar. Bu, yalnızca bu serinin değil, üst seriler grubunun tüm serilerinin bir yansımasıdır – ilgili grup özelliğinin bir projeksiyonudur. Bu nedenle özellik sadece okuma-yazmadır. Üst seriler grubuna erişmek için ParentSeriesGroup özelliğini kullanın. Değeri değiştirmek için ParentSeriesGroup.GapDepth okuma/yazma özelliğini kullanın. Okuma-yazma int.

--------------------

Bu, ParentSeriesGroup.GapDepth özelliğinin bir projeksiyonudur.

**Döndürür:**  
int

### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public final int getFirstSliceAngle()
```

İlk pasta veya halka diliminin açısını derece cinsinden belirtir (yukarıdan saat yönünde, 0-360 derece). Bu, yalnızca bu serinin değil, üst seriler grubunun tüm serilerinin bir yansımasıdır – ilgili grup özelliğinin bir projeksiyonudur. Bu nedenle özellik sadece okuma-yazmadır. Üst seriler grubuna erişmek için ParentSeriesGroup özelliğini kullanın. Değeri değiştirmek için ParentSeriesGroup.FirstSliceAngle okuma/yazma özelliğini kullanın. Okuma-yazma int.

--------------------

Bu, ParentSeriesGroup.FirstSliceAngle özelliğinin bir projeksiyonudur.

**Döndürür:**  
int

### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public final byte getDoughnutHoleSize()
```

Halka grafiğindeki deliğin boyutunu belirtir (grafik alanının boyutunun %10-%90 arasında). Bu, yalnızca bu serinin değil, üst seriler grubunun tüm serilerinin bir yansımasıdır – ilgili grup özelliğinin bir projeksiyonudur. Bu nedenle özellik sadece okuma-yazmadır. Üst seriler grubuna erişmek için ParentSeriesGroup özelliğini kullanın. Değeri değiştirmek için ParentSeriesGroup.DoughnutHoleSize okuma/yazma özelliğini kullanın. Okuma-yazma byte.

--------------------

Bu, ParentSeriesGroup.DoughnutHoleSize özelliğinin bir projeksiyonudur.

**Döndürür:**  
byte

### getOverlap() {#getOverlap--}
```
public final byte getOverlap()
```

2-D grafiklerde çubuk ve sütunların ne kadar üst üste geleceğini yüzde olarak belirtir (-100%-100% arası). Bu, yalnızca bu serinin değil, üst seriler grubunun tüm serilerinin bir yansımasıdır. İlgili grup özelliğinin bir projeksiyonudur ve bu nedenle özellik sadece okuma-yazmadır. Değeri değiştirmek için ParentSeriesGroup.Overlap okuma/yazma özelliğini kullanın. Okuma-yazma byte.

--------------------

Overlap, çubuk ve sütunların genişliğinin yüzde olarak üst üste gelme veya aralık derecesini belirtir: -100%: En fazla boşluk (çubuklar tamamen ayrılmıştır). 0%: Çubuklar yan yana, üst üste gelmeden veya boşluk olmadan yerleştirilir. 100%: En fazla üst üste binme (çubuklar tamamen üst üste gelir). Bu, ParentSeriesGroup.Overlap özelliğinin bir projeksiyonudur.

**Döndürür:**  
byte

### getSecondPieSize() {#getSecondPieSize--}
```
public final int getSecondPieSize()
```

İkinci pasta veya pasta-iç-pasta grafiğinde ikinci pasta veya çubuğun boyutunu, ilk pastanın boyutunun yüzdesi olarak belirtir (5-200% arası). Bu, yalnızca bu serinin değil, üst seriler grubunun tüm serilerinin bir yansımasıdır – ilgili grup özelliğinin bir projeksiyonudur. Bu nedenle özellik sadece okuma-yazmadır. Üst seriler grubuna erişmek için ParentSeriesGroup özelliğini kullanın. Değeri değiştirmek için ParentSeriesGroup.SecondPieSize okuma/yazma özelliğini kullanın. Okuma-yazma int.

--------------------

Bu, ParentSeriesGroup.SecondPieSize özelliğinin bir projeksiyonudur.

**Döndürür:**  
int

### hasSeriesLines() {#hasSeriesLines--}
```
public final boolean hasSeriesLines()
```

Bu serinin ve ilişkili serilerin seriler çizgilerine sahip olup olmadığını belirler. Bu, yalnızca bu serinin değil, üst seriler grubunun tüm serilerinin bir yansımasıdır – ilgili grup özelliğinin bir projeksiyonudur. Bu nedenle özellik sadece okuma-yazmadır. Üst seriler grubuna erişmek için ParentSeriesGroup özelliğini kullanın. Değeri değiştirmek için ParentSeriesGroup.HasSeriesLines okuma/yazma özelliğini kullanın. Seriler çizgilerini biçimlendirmek için ParentSeriesGroup.SeriesLinesFormat özelliğini kullanın. Okuma-yazma boolean.

--------------------

Bu, ParentSeriesGroup.HasSeriesLines özelliğinin bir projeksiyonudur.

**Döndürür:**  
boolean

### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public final int getBubbleSizeRepresentation()
```

Baloncuk grafiğinde baloncuk boyutu değerlerinin nasıl temsil edildiğini belirtir. Bu, yalnızca bu serinin değil, üst seriler grubunun tüm serilerinin bir yansımasıdır – ilgili grup özelliğinin bir projeksiyonudur. Bu nedenle özellik sadece okuma-yazmadır. Üst seriler grubuna erişmek için ParentSeriesGroup özelliğini kullanın. Değeri değiştirmek için ParentSeriesGroup.BubbleSizeRepresentation okuma/yazma özelliğini kullanın.

--------------------

Bu, ParentSeriesGroup.BubbleSizeRepresentation özelliğinin bir projeksiyonudur.

**Döndürür:**  
int

### getPieSplitPosition() {#getPieSplitPosition--}
```
public final double getPieSplitPosition()
```

Pasta-iç-pasta veya çubuk-iç-pasta grafiğinde hangi veri noktalarının ikinci pasta veya çubukta bulunacağını belirlemek için kullanılacak değeri belirtir. PieSplitBy özelliğiyle birlikte kullanılır. Bu, yalnızca bu serinin değil, üst seriler grubunun tüm serilerinin bir yansımasıdır – ilgili grup özelliğinin bir projeksiyonudur. Bu nedenle özellik sadece okuma-yazmadır. Üst seriler grubuna erişmek için ParentSeriesGroup özelliğini kullanın. Değeri değiştirmek için ParentSeriesGroup.PieSplitPosition okuma/yazma özelliğini kullanın. Okuma-yazma double.

--------------------

Bu, ParentSeriesGroup.PieSplitPosition özelliğinin bir projeksiyonudur.

**Döndürür:**  
double

### getPieSplitBy() {#getPieSplitBy--}
```
public final int getPieSplitBy()
```

Pasta-iç-pasta veya çubuk-iç-pasta grafiğinde hangi veri noktalarının ikinci pasta veya çubukta bulunacağını belirleme yöntemini belirtir. Bu, yalnızca bu serinin değil, üst seriler grubunun tüm serilerinin bir yansımasıdır – ilgili grup özelliğinin bir projeksiyonudur. Bu nedenle özellik sadece okuma-yazmadır. Üst seriler grubuna erişmek için ParentSeriesGroup özelliğini kullanın. Değeri değiştirmek için ParentSeriesGroup.PieSplitBy okuma/yazma özelliğini kullanın. Okuma-yazma [PieSplitType](../../com.aspose.slides/piesplittype).

--------------------

1) Bu, ParentSeriesGroup.PieSplitBy özelliğinin bir projeksiyonudur. 2) Eğer özellik değeri PieSplitType.Custom ise ParentSeriesGroup.PieSplitCustomPoints özelliğiyle özel bölme bilgileri tanımlanabilir.

**Döndürür:**  
int

### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public final IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

Özel bölme bilgileri, özel bölme ile bir pasta-iç-pasta veya çubuk-iç-pasta grafiğinde ikinci pasta veya çubukta çizilecek veri noktalarını içerir. Bu, yalnızca bu serinin değil, üst seriler grubunun tüm serilerinin bir yansımasıdır – ilgili grup özelliğinin bir projeksiyonudur. Okuma-yazma [PieSplitCustomPointCollection](../../com.aspose.slides/piesplitcustompointcollection).

--------------------

Bu, ParentSeriesGroup.PieSplitCustomPoints özelliğinin bir projeksiyonudur.

**Döndürür:**  
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)

### isColorVaried() {#isColorVaried--}
```
public final boolean isColorVaried()
```
Specifies that each data marker in the series has a different color. This is the property not only of this series but of all series of parent series group - this is projection of appropriate group property. And so this property is read-only. Use ParentSeriesGroup property for access to parent series group. Use ParentSeriesGroup.IsColorVaried read/write property for change value. Read-only boolean.

--------------------

This is the projection of the property ParentSeriesGroup.IsColorVaried.

**Returns:**
boolean
### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public final int getBubbleSizeScale()
```


Specifies the scale factor for the bubble chart (can be between 0 and 300 percents of the default size). This is the property not only of this series but of all series of parent series group - this is projection of appropriate group property. And so this property is read-only. Use ParentSeriesGroup property for access to parent series group. Use ParentSeriesGroup.BubbleSizeScale read/write property for change value.

--------------------

This is the projection of the property ParentSeriesGroup.BubbleSizeScale.

**Returns:**
int
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```


Returns the parent slide of a FillFormat. Read-only [BaseSlide](../../com.aspose.slides/baseslide).

**Returns:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```


Returns the parent presentation of a FillFormat. Read-only [IPresentation](../../com.aspose.slides/ipresentation).

**Returns:**
[IPresentation](../../com.aspose.slides/ipresentation)