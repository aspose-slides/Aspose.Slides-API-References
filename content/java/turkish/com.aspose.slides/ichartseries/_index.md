---
title: IChartSeries
second_title: Aspose.Slides for Java API Referansı
description: Bir grafik serisini temsil eder.
type: docs
url: /tr/com.aspose.slides/ichartseries/
---
**Tüm Uygulanan Arayüzler:**
[com.aspose.slides.IChartComponent](../../com.aspose.slides/ichartcomponent)
```
public interface IChartSeries extends IChartComponent
```

Bir grafik serisini temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getExplosion()](#getExplosion--) | Açık bir pasta diliminin pasta grafiğinin merkezinden uzaklığı, pasta çapının yüzdesi olarak ifade edilir. |
| [setExplosion(int value)](#setExplosion-int-) | Açık bir pasta diliminin pasta grafiğinin merkezinden uzaklığı, pasta çapının yüzdesi olarak ifade edilir. |
| [getSmooth()](#getSmooth--) | Eğri yumuşatmayı temsil eder. |
| [setSmooth(boolean value)](#setSmooth-boolean-) | Eğri yumuşatmayı temsil eder. |
| [getMarker()](#getMarker--) | Seri işaretçisini döndürür. |
| [getBar3DShape()](#getBar3DShape--) | 3-D çubuk grafiğinin bir serisinin şeklini belirtir. |
| [setBar3DShape(int value)](#setBar3DShape-int-) | 3-D çubuk grafiğinin bir serisinin şeklini belirtir. |
| [getName()](#getName--) | Seri adını döndürür. |
| [getDataPoints()](#getDataPoints--) | Bu serinin veri noktaları koleksiyonunu döndürür. |
| [getType()](#getType--) | Bu serinin tipini döndürür. |
| [setType(int value)](#setType-int-) | Bu serinin tipini döndürür. |
| [getParentSeriesGroup()](#getParentSeriesGroup--) | Üst seri grubunu döndürür. |
| [getFormat()](#getFormat--) | Bir serinin biçimini döndürür. |
| [getOrder()](#getOrder--) | Bir serinin sırasını döndürür. |
| [setOrder(int value)](#setOrder-int-) | Bir serinin sırasını döndürür. |
| [getLabels()](#getLabels--) | Bir serinin Etiketlerini döndürür. |
| [getTrendLines()](#getTrendLines--) | Seri trend hatları koleksiyonu (Yalnızca Okunur) [ITrendlineCollection](../../com.aspose.slides/itrendlinecollection). |
| [getErrorBarsXFormat()](#getErrorBarsXFormat--) | Serinin X yönündeki Hata Çubuklarını temsil eder. |
| [getErrorBarsYFormat()](#getErrorBarsYFormat--) | Serinin Y yönündeki Hata Çubuklarını temsil eder. |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | Bu serinin ikinci değer ekseninde çizilip çizilmediğini gösterir. |
| [setPlotOnSecondAxis(boolean value)](#setPlotOnSecondAxis-boolean-) | Bu serinin ikinci değer ekseninde çizilip çizilmediğini gösterir. |
| [getNumberFormatOfValues()](#getNumberFormatOfValues--) | Seri değerleri için sayı biçimini döndürür veya ayarlar. |
| [setNumberFormatOfValues(String value)](#setNumberFormatOfValues-java.lang.String-) | Seri değerleri için sayı biçimini döndürür veya ayarlar. |
| [getNumberFormatOfXValues()](#getNumberFormatOfXValues--) | Seri x değerleri için sayı biçimini döndürür veya ayarlar. |
| [setNumberFormatOfXValues(String value)](#setNumberFormatOfXValues-java.lang.String-) | Seri x değerleri için sayı biçimini döndürür veya ayarlar. |
| [getNumberFormatOfYValues()](#getNumberFormatOfYValues--) | Seri y değerleri için sayı biçimini döndürür veya ayarlar. |
| [setNumberFormatOfYValues(String value)](#setNumberFormatOfYValues-java.lang.String-) | Seri y değerleri için sayı biçimini döndürür veya ayarlar. |
| [getNumberFormatOfBubbleSizes()](#getNumberFormatOfBubbleSizes--) | Seri balon boyutları için sayı biçimini döndürür veya ayarlar. |
| [setNumberFormatOfBubbleSizes(String value)](#setNumberFormatOfBubbleSizes-java.lang.String-) | Seri balon boyutları için sayı biçimini döndürür veya ayarlar. |
| [getInvertIfNegative()](#getInvertIfNegative--) | Değer negatif olduğunda çubuk, sütun ya da balon serisinin renklerini tersine çevireceğini belirtir. |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | Değer negatif olduğunda çubuk, sütun ya da balon serisinin renklerini tersine çevireceğini belirtir. |
| [getInvertedSolidFillColor()](#getInvertedSolidFillColor--) | Seri için ters katı rengi belirtir. |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | Bu seriye ilişkin gösterge girdisini temsil eder (Yalnızca Okunur) [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties). |
| [getAutomaticSeriesColor()](#getAutomaticSeriesColor--) | Seri indeksine ve grafik stiline dayalı otomatik bir seri rengi döndürür. |
| [getShowInnerPoints()](#getShowInnerPoints--) | İç noktaları temsil eder. |
| [setShowInnerPoints(boolean value)](#setShowInnerPoints-boolean-) | İç noktaları temsil eder. |
| [getShowOutlierPoints()](#getShowOutlierPoints--) | Aykırı noktaları temsil eder. |
| [setShowOutlierPoints(boolean value)](#setShowOutlierPoints-boolean-) | Aykırı noktaları temsil eder. |
| [getShowMeanMarkers()](#getShowMeanMarkers--) | Ortalama işaretçilerini temsil eder. |
| [setShowMeanMarkers(boolean value)](#setShowMeanMarkers-boolean-) | Ortalama işaretçilerini temsil eder. |
| [getShowMeanLine()](#getShowMeanLine--) | Ortalama işaretçilerini temsil eder. |
| [setShowMeanLine(boolean value)](#setShowMeanLine-boolean-) | Ortalama işaretçilerini temsil eder. |
| [getQuartileMethod()](#getQuartileMethod--) | Çeyrek yöntemi temsil eder. |
| [setQuartileMethod(int value)](#setQuartileMethod-int-) | Çeyrek yöntemi temsil eder. |
| [getShowConnectorLines()](#getShowConnectorLines--) | Bağlayıcı hatları temsil eder. |
| [setShowConnectorLines(boolean value)](#setShowConnectorLines-boolean-) | Bağlayıcı hatları temsil eder. |
| [getParentLabelLayout()](#getParentLabelLayout--) | Üst kategori etiketlerinin düzenini temsil eder. |
| [setParentLabelLayout(int value)](#setParentLabelLayout-int-) | Üst kategori etiketlerinin düzenini temsil eder. |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | Balon grafiği için ölçek faktörünü belirtir (varsayılan boyutun %0 ile %300 arasında olabilir). |
| [hasUpDownBars()](#hasUpDownBars--) | Çizgi veya Hisse grafiğinin yükselen/düşen çubukları olup olmadığını belirler. |
| [getGapWidth()](#getGapWidth--) | Çubuk veya sütun kümeleri arasındaki boşluğu, çubuk ya da sütun genişliğinin yüzdesi olarak belirtir. |
| [getGapDepth()](#getGapDepth--) | 3D grafikte veri serileri arasındaki mesafeyi, işaretçi genişliğinin yüzdesi olarak döndürür veya ayarlar. |
| [isColorVaried()](#isColorVaried--) | Serideki her veri işaretçisinin farklı bir renge sahip olduğunu belirtir. |
| [hasSeriesLines()](#hasSeriesLines--) | Bu seri ve ilgili seriler için seri çizgilerinin olup olmadığını belirler. |
| [getOverlap()](#getOverlap--) | 2D grafiklerde çubukların ve sütunların ne kadar üst üste geldiğini yüzde olarak belirtir (-%100'den %100'e). |
| [getSecondPieSize()](#getSecondPieSize--) | Pie-of-pie veya bar-of-pie grafiğinde ikinci pasta ya da çubuğun boyutunu, ilk pastanın boyutunun yüzdesi olarak belirtir (%5 ile %200 arasında olabilir). |
| [getPieSplitPosition()](#getPieSplitPosition--) | Pie-of-pie veya bar-of-pie grafiğinde hangi veri noktalarının ikinci pasta ya da çubukta olduğunu belirlemek için kullanılacak bir değer belirtir. |
| [getPieSplitBy()](#getPieSplitBy--) | Pie-of-pie veya bar-of-pie grafiğinde hangi veri noktalarının ikinci pasta ya da çubukta olduğunu belirleme yöntemini belirtir. |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | Donut grafiğindeki boşluğun boyutunu belirtir (çizim alanının %10 ile %90'ı arasında olabilir). |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | İlk pasta veya donut grafiği diliminin açısını derece cinsinden belirtir (yukarıdan saat yönünde, 0 ile 360 derece arasında). |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | Özel bölünmüş bir pie-of-pie veya bar-of-pie grafiği için özel bölünme bilgisini içerir. |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | Balon grafik üzerindeki balon boyut değerlerinin nasıl temsil edileceğini belirtir. |

### getExplosion() {#getExplosion--}
```
public abstract int getExplosion()
```

Açık bir pasta diliminin pasta grafiğinin merkezinden uzaklığı, pasta çapının yüzdesi olarak ifade edilir. Okuma/Yazma int.

**Döndürür:**
int

### setExplosion(int value) {#setExplosion-int-}
```
public abstract void setExplosion(int value)
```

Açık bir pasta diliminin pasta grafiğinin merkezinden uzaklığı, pasta çapının yüzdesi olarak ifade edilir. Okuma/Yazma int.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getSmooth() {#getSmooth--}
```
public abstract boolean getSmooth()
```

Eğri yumuşatmayı temsil eder. Doğrusal grafik veya dağılım grafiği için eğri yumuşatma açıldıysa true. Yalnızca satır ve çizgilerle bağlanmış dağılım grafiklerine uygulanır. Okuma/Yazma boolean.

**Döndürür:**
boolean

### setSmooth(boolean value) {#setSmooth-boolean-}
```
public abstract void setSmooth(boolean value)
```

Eğri yumuşatmayı temsil eder. Doğrusal grafik veya dağılım grafiği için eğri yumuşatma açıldıysa true. Yalnızca satır ve çizgilerle bağlanmış dağılım grafiklerine uygulanır. Okuma/Yazma boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getMarker() {#getMarker--}
```
public abstract IMarker getMarker()
```

Seri işaretçisini döndürür. Yalnızca Okunur [IMarker](../../com.aspose.slides/imarker).

**Döndürür:**
[IMarker](../../com.aspose.slides/imarker)

### getBar3DShape() {#getBar3DShape--}
```
public abstract int getBar3DShape()
```

3-D çubuk grafiğinin bir serisinin şeklini belirtir. Bu özelliğin değeri değiştirildiğinde seri Tipi otomatik olarak değişebilir. Okuma/Yazma [ChartShapeType](../../com.aspose.slides/chartshapetype).

**Döndürür:**
int

### setBar3DShape(int value) {#setBar3DShape-int-}
```
public abstract void setBar3DShape(int value)
```

3-D çubuk grafiğinin bir serisinin şeklini belirtir. Bu özelliğin değeri değiştirildiğinde seri Tipi otomatik olarak değişebilir. Okuma/Yazma [ChartShapeType](../../com.aspose.slides/chartshapetype).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getName() {#getName--}
```
public abstract IStringChartValue getName()
```

Seri adını döndürür. Yalnızca Okunur [IStringChartValue](../../com.aspose.slides/istringchartvalue).

**Döndürür:**
[IStringChartValue](../../com.aspose.slides/istringchartvalue)

### getDataPoints() {#getDataPoints--}
```
public abstract IChartDataPointCollection getDataPoints()
```

Bu serinin veri noktaları koleksiyonunu döndürür. Yalnızca Okunur [IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection).

**Döndürür:**
[IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection)

### getType() {#getType--}
```
public abstract int getType()
```

Bu serinin tipini döndürür. Okuma/Yazma [ChartType](../../com.aspose.slides/charttype).

**Döndürür:**
int

### setType(int value) {#setType-int-}
```
public abstract void setType(int value)
```

Bu serinin tipini döndürür. Okuma/Yazma [ChartType](../../com.aspose.slides/charttype).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getParentSeriesGroup() {#getParentSeriesGroup--}
```
public abstract IChartSeriesGroup getParentSeriesGroup()
```

Üst seri grubunu döndürür. Yalnızca Okunur [IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup).

**Döndürür:**
[IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup)

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

Bir serinin biçimini döndürür. Yalnızca Okunur [IFormat](../../com.aspose.slides/iformat).

**Döndürür:**
[IFormat](../../com.aspose.slides/iformat)

### getOrder() {#getOrder--}
```
public abstract int getOrder()
```

Bir serinin sırasını döndürür. Okuma/Yazma int.

**Döndürür:**
int

### setOrder(int value) {#setOrder-int-}
```
public abstract void setOrder(int value)
```

Bir serinin sırasını döndürür. Okuma/Yazma int.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getLabels() {#getLabels--}
```
public abstract IDataLabelCollection getLabels()
```

Bir serinin Etiketlerini döndürür. Yalnızca Okunur [IDataLabelCollection](../../com.aspose.slides/idatalabelcollection).

**Döndürür:**
[IDataLabelCollection](../../com.aspose.slides/idatalabelcollection)

### getTrendLines() {#getTrendLines--}
```
public abstract ITrendlineCollection getTrendLines()
```

Seri trend hatları koleksiyonu (Yalnızca Okunur) [ITrendlineCollection](../../com.aspose.slides/itrendlinecollection).

**Döndürür:**
[ITrendlineCollection](../../com.aspose.slides/itrendlinecollection)

### getErrorBarsXFormat() {#getErrorBarsXFormat--}
```
public abstract IErrorBarsFormat getErrorBarsXFormat()
```

Serinin X yönündeki Hata Çubuklarını temsil eder. Yalnızca Okunur [IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat).

--------------------

X yönündeki Hata Çubukları, area, bar, scatter ve bubble tipindeki seriler için mevcuttur. Diğer grafik tipleri için bu özellik null döndürür (3D grafikler dahil). Özel değerler için ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues)) özelliği ile DataPoints koleksiyonunu kullanarak değeri belirtin.

**Döndürür:**
[IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)

### getErrorBarsYFormat() {#getErrorBarsYFormat--}
```
public abstract IErrorBarsFormat getErrorBarsYFormat()
```

Serinin Y yönündeki Hata Çubuklarını temsil eder. Yalnızca Okunur [IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat).

--------------------

Y yönündeki Hata Çubukları, area, bar, line, scatter ve bubble tipindeki seriler için mevcuttur. Diğer grafik tipleri için bu özellik null döndürür (3D grafikler dahil). Özel değerler için ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues)) özelliği ile DataPoints koleksiyonunu kullanarak değeri belirtin.

**Döndürür:**
[IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)

### getPlotOnSecondAxis() {#getPlotOnSecondAxis--}
```
public abstract boolean getPlotOnSecondAxis()
```

Bu serinin ikinci değer ekseninde çizilip çizilmediğini gösterir. Okuma/Yazma boolean.

**Döndürür:**
boolean

### setPlotOnSecondAxis(boolean value) {#setPlotOnSecondAxis-boolean-}
```
public abstract void setPlotOnSecondAxis(boolean value)
```

Bu serinin ikinci değer ekseninde çizilip çizilmediğini gösterir. Okuma/Yazma boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getNumberFormatOfValues() {#getNumberFormatOfValues--}
```
public abstract String getNumberFormatOfValues()
```

Seri değerleri için sayı biçimini döndürür veya ayarlar. Okuma/Yazma String.

**Döndürür:**
java.lang.String

### setNumberFormatOfValues(String value) {#setNumberFormatOfValues-java.lang.String-}
```
public abstract void setNumberFormatOfValues(String value)
```

Seri değerleri için sayı biçimini döndürür veya ayarlar. Okuma/Yazma String.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |

### getNumberFormatOfXValues() {#getNumberFormatOfXValues--}
```
public abstract String getNumberFormatOfXValues()
```

Seri x değerleri için sayı biçimini döndürür veya ayarlar. Okuma/Yazma String.

**Döndürür:**
java.lang.String

### setNumberFormatOfXValues(String value) {#setNumberFormatOfXValues-java.lang.String-}
```
public abstract void setNumberFormatOfXValues(String value)
```

Seri x değerleri için sayı biçimini döndürür veya ayarlar. Okuma/Yazma String.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |

### getNumberFormatOfYValues() {#getNumberFormatOfYValues--}
```
public abstract String getNumberFormatOfYValues()
```

Seri y değerleri için sayı biçimini döndürür veya ayarlar. Okuma/Yazma String.

**Döndürür:**
java.lang.String

### setNumberFormatOfYValues(String value) {#setNumberFormatOfYValues-java.lang.String-}
```
public abstract void setNumberFormatOfYValues(String value)
```

Seri y değerleri için sayı biçimini döndürür veya ayarlar. Okuma/Yazma String.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |

### getNumberFormatOfBubbleSizes() {#getNumberFormatOfBubbleSizes--}
```
public abstract String getNumberFormatOfBubbleSizes()
```

Seri balon boyutları için sayı biçimini döndürür veya ayarlar. Okuma/Yazma String.

**Döndürür:**
java.lang.String

### setNumberFormatOfBubbleSizes(String value) {#setNumberFormatOfBubbleSizes-java.lang.String-}
```
public abstract void setNumberFormatOfBubbleSizes(String value)
```

Seri balon boyutları için sayı biçimini döndürür veya ayarlar. Okuma/Yazma String.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |

### getInvertIfNegative() {#getInvertIfNegative--}
```
public abstract boolean getInvertIfNegative()
```

Değer negatif olduğunda çubuk, sütun ya da balon serisinin renklerini tersine çevireceğini belirtir. Okuma/Yazma boolean.

**Döndürür:**
boolean

### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public abstract void setInvertIfNegative(boolean value)
```

Değer negatif olduğunda çubuk, sütun ya da balon serisinin renklerini tersine çevireceğini belirtir. Okuma/Yazma boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getInvertedSolidFillColor() {#getInvertedSolidFillColor--}
```
public abstract IColorFormat getInvertedSolidFillColor()
```

Seri için ters katı rengi belirtir. Renk ayarını uygulamak için seri formatının FillType özelliğini FillType.Solid olarak ayarlayın. Okuma/Yazma [IColorFormat](../../com.aspose.slides/icolorformat).

**Döndürür:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public abstract ILegendEntryProperties getRelatedLegendEntry()
```

Bu seriye ilişkin gösterge girdisini temsil eder (Yalnızca Okunur) [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**Döndürür:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)

### getAutomaticSeriesColor() {#getAutomaticSeriesColor--}
```
public abstract Color getAutomaticSeriesColor()
```
Seri dizini ve grafik stiline göre serinin otomatik rengini döndürür. Bu renk, FillType NotDefined olduğunda varsayılan olarak kullanılır.

**Döndürür:**  
java.awt.Color - Serinin otomatik rengi java.awt.Color  

### getShowInnerPoints() {#getShowInnerPoints--}
```
public abstract boolean getShowInnerPoints()
```

İç noktaları temsil eder. BoxAndWhisker grafiğinde iç noktalar gösteriliyorsa true. Yalnızca BoxAndWhisker grafiklerinde uygulanır. Okunur/yazılabilir boolean.

**Döndürür:**  
boolean  

### setShowInnerPoints(boolean value) {#setShowInnerPoints-boolean-}
```
public abstract void setShowInnerPoints(boolean value)
```

İç noktaları temsil eder. BoxAndWhisker grafiğinde iç noktalar gösteriliyorsa true. Yalnızca BoxAndWhisker grafiklerinde uygulanır. Okunur/yazılabilir boolean.

**Parametreler:**  
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getShowOutlierPoints() {#getShowOutlierPoints--}
```
public abstract boolean getShowOutlierPoints()
```

Uç değer noktalarını temsil eder. BoxAndWhisker grafiğinde uç değer noktaları gösteriliyorsa true. Yalnızca BoxAndWhisker grafiklerinde uygulanır. Okunur/yazılabilir boolean.

**Döndürür:**  
boolean  

### setShowOutlierPoints(boolean value) {#setShowOutlierPoints-boolean-}
```
public abstract void setShowOutlierPoints(boolean value)
```

Uç değer noktalarını temsil eder. BoxAndWhisker grafiğinde uç değer noktaları gösteriliyorsa true. Yalnızca BoxAndWhisker grafiklerinde uygulanır. Okunur/yazılabilir boolean.

**Parametreler:**  
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getShowMeanMarkers() {#getShowMeanMarkers--}
```
public abstract boolean getShowMeanMarkers()
```

Ortalama işaretçilerini temsil eder. BoxAndWhisker grafiğinde ortalama işaretçileri gösteriliyorsa true. Yalnızca BoxAndWhisker grafiklerinde uygulanır. Okunur/yazılabilir boolean.

**Döndürür:**  
boolean  

### setShowMeanMarkers(boolean value) {#setShowMeanMarkers-boolean-}
```
public abstract void setShowMeanMarkers(boolean value)
```

Ortalama işaretçilerini temsil eder. BoxAndWhisker grafiğinde ortalama işaretçileri gösteriliyorsa true. Yalnızca BoxAndWhisker grafiklerinde uygulanır. Okunur/yazılabilir boolean.

**Parametreler:**  
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getShowMeanLine() {#getShowMeanLine--}
```
public abstract boolean getShowMeanLine()
```

Ortalama işaretçilerini temsil eder. BoxAndWhisker grafiğinde ortalama çizgi gösteriliyorsa true. Yalnızca BoxAndWhisker grafiklerinde uygulanır. Okunur/yazılabilir boolean.

**Döndürür:**  
boolean  

### setShowMeanLine(boolean value) {#setShowMeanLine-boolean-}
```
public abstract void setShowMeanLine(boolean value)
```

Ortalama işaretçilerini temsil eder. BoxAndWhisker grafiğinde ortalama çizgi gösteriliyorsa true. Yalnızca BoxAndWhisker grafiklerinde uygulanır. Okunur/yazılabilir boolean.

**Parametreler:**  
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getQuartileMethod() {#getQuartileMethod--}
```
public abstract int getQuartileMethod()
```

Çeyrek metodunu temsil eder. Yalnızca BoxAndWhisker grafiklerinde uygulanır.

**Döndürür:**  
int  

### setQuartileMethod(int value) {#setQuartileMethod-int-}
```
public abstract void setQuartileMethod(int value)
```

Çeyrek metodunu temsil eder. Yalnızca BoxAndWhisker grafiklerinde uygulanır.

**Parametreler:**  
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getShowConnectorLines() {#getShowConnectorLines--}
```
public abstract boolean getShowConnectorLines()
```

Bağlayıcı çizgilerini temsil eder. Yalnızca Waterfall grafiklerinde uygulanır.

**Döndürür:**  
boolean  

### setShowConnectorLines(boolean value) {#setShowConnectorLines-boolean-}
```
public abstract void setShowConnectorLines(boolean value)
```

Bağlayıcı çizgilerini temsil eder. Yalnızca Waterfall grafiklerinde uygulanır.

**Parametreler:**  
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getParentLabelLayout() {#getParentLabelLayout--}
```
public abstract int getParentLabelLayout()
```

Üst kategori etiketlerinin düzenini temsil eder. Yalnızca Treemap grafiklerinde uygulanır.

**Döndürür:**  
int  

### setParentLabelLayout(int value) {#setParentLabelLayout-int-}
```
public abstract void setParentLabelLayout(int value)
```

Üst kategori etiketlerinin düzenini temsil eder. Yalnızca Treemap grafiklerinde uygulanır.

**Parametreler:**  
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public abstract int getBubbleSizeScale()
```

Balon grafiği için ölçek çarpanını belirtir (varsayılan boyutun %0 ile %300 arasında olabilir). Bu özellik yalnızca bu seriye değil, üst seri grubunun tüm serilerine uygulanır – ilgili grup özelliğinin bir yansımasıdır. Bu yüzden özellik yalnızca okunabilir. Üst seri grubuna erişim için ParentSeriesGroup özelliğini kullanın. Değeri değiştirmek için ParentSeriesGroup.BubbleSizeScale okunur/yazılır özelliğini kullanın.

--------------------

Bu, ParentSeriesGroup.BubbleSizeScale özelliğinin bir yansımasıdır.

**Döndürür:**  
int  

### hasUpDownBars() {#hasUpDownBars--}
```
public abstract boolean hasUpDownBars()
```

Line veya Stock grafiğinin yukarı/aşağı çubukları olup olmadığını belirler. Bu özellik yalnızca bu seriye değil, üst seri grubunun tüm serilerine uygulanır – ilgili grup özelliğinin bir yansımasıdır. Bu yüzden özellik yalnızca okunabilir. Üst seri grubuna erişim için ParentSeriesGroup özelliğini kullanın. Değeri değiştirmek için ParentSeriesGroup.UpDownBars.HasUpDownBars okunur/yazılır özelliğini kullanın. Yukarı/aşağı çubuk formatı için ParentSeriesGroup.UpDownBars özelliğini kullanın. Okunur sadece boolean.

--------------------

Bu, ParentSeriesGroup.UpDownBars.HasUpDownBars özelliğinin bir yansımasıdır.

**Döndürür:**  
boolean  

### getGapWidth() {#getGapWidth--}
```
public abstract int getGapWidth()
```

Sütun veya çubuk kümeleri arasındaki boşluğu, çubuk veya sütun genişliğinin yüzdesi olarak belirtir. Bu özellik yalnızca bu seriye değil, üst seri grubunun tüm serilerine uygulanır – ilgili grup özelliğinin bir yansımasıdır. Bu yüzden özellik yalnızca okunabilir. Üst seri grubuna erişim için ParentSeriesGroup özelliğini kullanın. Değeri değiştirmek için ParentSeriesGroup.GapWidth okunur/yazılır özelliğini kullanın. Okunur sadece int.

--------------------

Bu, ParentSeriesGroup.GapWidth özelliğinin bir yansımasıdır.

**Döndürür:**  
int  

### getGapDepth() {#getGapDepth--}
```
public abstract int getGapDepth()
```

3D grafikte veri serileri arasındaki mesafeyi, işaretçi genişliğinin yüzdesi olarak döndürür veya ayarlar. Bu özellik yalnızca bu seriye değil, üst seri grubunun tüm serilerine uygulanır – ilgili grup özelliğinin bir yansımasıdır. Bu yüzden özellik yalnızca okunabilir. Üst seri grubuna erişim için ParentSeriesGroup özelliğini kullanın. Değeri değiştirmek için ParentSeriesGroup.GapDepth okunur/yazılır özelliğini kullanın. Okunur sadece int.

--------------------

Bu, ParentSeriesGroup.GapDepth özelliğinin bir yansımasıdır.

**Döndürür:**  
int  

### isColorVaried() {#isColorVaried--}
```
public abstract boolean isColorVaried()
```

Serideki her veri işaretçisinin farklı bir renge sahip olduğunu belirtir. Bu özellik yalnızca bu seriye değil, üst seri grubunun tüm serilerine uygulanır – ilgili grup özelliğinin bir yansımasıdır. Bu yüzden özellik yalnızca okunabilir. Üst seri grubuna erişim için ParentSeriesGroup özelliğini kullanın. Değeri değiştirmek için ParentSeriesGroup.IsColorVaried okunur/yazılır özelliğini kullanın. Okunur sadece boolean.

--------------------

Bu, ParentSeriesGroup.IsColorVaried özelliğinin bir yansımasıdır.

**Döndürür:**  
boolean  

### hasSeriesLines() {#hasSeriesLines--}
```
public abstract boolean hasSeriesLines()
```

Bu seri ve ilgili seriler için seri çizgileri olup olmadığını belirler. Bu özellik yalnızca bu seriye değil, üst seri grubunun tüm serilerine uygulanır – ilgili grup özelliğinin bir yansımasıdır. Bu yüzden özellik yalnızca okunabilir. Üst seri grubuna erişim için ParentSeriesGroup özelliğini kullanın. Değeri değiştirmek için ParentSeriesGroup.HasSeriesLines okunur/yazılır özelliğini kullanın. Seri çizgilerini biçimlendirmek için ParentSeriesGroup.SeriesLinesFormat özelliğini kullanın. Okunur sadece boolean.

--------------------

Bu, ParentSeriesGroup.HasSeriesLines özelliğinin bir yansımasıdır.

**Döndürür:**  
boolean  

### getOverlap() {#getOverlap--}
```
public abstract byte getOverlap()
```

2-D grafiklerde çubuk ve sütunların ne kadar çakıştığını yüzde olarak (-100% ile 100% arasında) belirtir. Bu özellik yalnızca bu seriye değil, üst seri grubunun tüm serilerine uygulanır. İlgili grup özelliğinin bir yansımasıdır ve bu yüzden özellik yalnızca okunabilir. Değeri değiştirmek için ParentSeriesGroup.Overlap okunur/yazılır özelliğini kullanın. Okunur sadece byte.

--------------------

Overlap, çubuk ve sütunların genişliklerinin yüzde olarak çakışma veya boşluk derecesini belirtir:  
--100%: En fazla boşluk (çubuklar tamamen ayrılmıştır).  
0%: Çubuklar yan yana, çakışma veya boşluk olmadan yerleştirilir.  
100%: En fazla çakışma (çubuklar tamamen üst üste gelir). Bu, ParentSeriesGroup.Overlap özelliğinin bir yansımasıdır.

**Döndürür:**  
byte  

### getSecondPieSize() {#getSecondPieSize--}
```
public abstract int getSecondPieSize()
```

Pie-of-pie veya bar-of-pie grafiğinde ikinci pie veya barın boyutunu, ilk pie'in boyutunun yüzde olarak belirtir (5 ile 200 arasında olabilir). Bu özellik yalnızca bu seriye değil, üst seri grubunun tüm serilerine uygulanır – ilgili grup özelliğinin bir yansımasıdır. Bu yüzden özellik yalnızca okunabilir. Üst seri grubuna erişim için ParentSeriesGroup özelliğini kullanın. Değeri değiştirmek için ParentSeriesGroup.SecondPieSize okunur/yazılır özelliğini kullanın. Okunur sadece int.

--------------------

Bu, ParentSeriesGroup.SecondPieSize özelliğinin bir yansımasıdır.

**Döndürür:**  
int  

### getPieSplitPosition() {#getPieSplitPosition--}
```
public abstract double getPieSplitPosition()
```

Pie-of-pie veya bar-of-pie grafiğinde hangi veri noktalarının ikinci pie veya bar içinde olacağını belirlemek için kullanılan bir değeri belirtir. PieSplitBy özelliğiyle birlikte kullanılır. Bu özellik yalnızca bu seriye değil, üst seri grubunun tüm serilerine uygulanır – ilgili grup özelliğinin bir yansımasıdır. Bu yüzden özellik yalnızca okunabilir. Üst seri grubuna erişim için ParentSeriesGroup özelliğini kullanın. Değeri değiştirmek için ParentSeriesGroup.PieSplitPosition okunur/yazılır özelliğini kullanın. Okunur sadece double.

--------------------

Bu, ParentSeriesGroup.PieSplitPosition özelliğinin bir yansımasıdır.

**Döndürür:**  
double  

### getPieSplitBy() {#getPieSplitBy--}
```
public abstract int getPieSplitBy()
```

Pie-of-pie veya bar-of-pie grafiğinde hangi veri noktalarının ikinci pie veya bar içinde olacağını belirleme yöntemini belirtir. Bu özellik yalnızca bu seriye değil, üst seri grubunun tüm serilerine uygulanır – ilgili grup özelliğinin bir yansımasıdır. Bu yüzden özellik yalnızca okunabilir. Üst seri grubuna erişim için ParentSeriesGroup özelliğini kullanın. Değeri değiştirmek için ParentSeriesGroup.PieSplitBy okunur/yazılır özelliğini kullanın. Okunur sadece [PieSplitType](../../com.aspose.slides/piesplittype).

--------------------

1) Bu, ParentSeriesGroup.PieSplitBy özelliğinin bir yansımasıdır.  
2) Eğer özellik değeri PieSplitType.Custom ise, ParentSeriesGroup.PieSplitCustomPoints özelliğiyle özel bölme bilgileri tanımlanabilir.

**Döndürür:**  
int  

### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public abstract byte getDoughnutHoleSize()
```

Donut grafiğindeki boşluğun boyutunu belirtir (çizim alanının %10 ila %90 arasında olabilir). Bu özellik yalnızca bu seriye değil, üst seri grubunun tüm serilerine uygulanır – ilgili grup özelliğinin bir yansımasıdır. Bu yüzden özellik yalnızca okunabilir. Üst seri grubuna erişim için ParentSeriesGroup özelliğini kullanın. Değeri değiştirmek için ParentSeriesGroup.DoughnutHoleSize okunur/yazılır özelliğini kullanın. Okunur sadece byte.

--------------------

Bu, ParentSeriesGroup.DoughnutHoleSize özelliğinin bir yansımasıdır.

**Döndürür:**  
byte  

### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public abstract int getFirstSliceAngle()
```

Pie veya donut grafiğinin ilk diliminin açısını derece cinsinden belirtir (yukarıdan saat yönünde, 0-360 derece). Bu özellik yalnızca bu seriye değil, üst seri grubunun tüm serilerine uygulanır – ilgili grup özelliğinin bir yansımasıdır. Bu yüzden özellik yalnızca okunabilir. Üst seri grubuna erişim için ParentSeriesGroup özelliğini kullanın. Değeri değiştirmek için ParentSeriesGroup.FirstSliceAngle okunur/yazılır özelliğini kullanın. Okunur sadece int.

--------------------

Bu, ParentSeriesGroup.FirstSliceAngle özelliğinin bir yansımasıdır.

**Döndürür:**  
int  

### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public abstract IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

Özel bölme bilgilerini içerir; pie-of-pie veya bar-of-pie grafiğinde ikinci pie veya bar içinde çizilecek veri noktalarını tanımlar. Bu özellik yalnızca bu seriye değil, üst seri grubunun tüm serilerine uygulanır – ilgili grup özelliğinin bir yansımasıdır. Okunur sadece [IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection).

--------------------

Bu, ParentSeriesGroup.PieSplitCustomPoints özelliğinin bir yansımasıdır.

**Döndürür:**  
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)

### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public abstract int getBubbleSizeRepresentation()
```
Balon grafiğinde balon boyutu değerlerinin nasıl temsil edildiğini belirtir. Bu, yalnızca bu serinin değil, üst seri grubunun tüm serilerinin özelliğidir – bu, ilgili grup özelliğinin projeksiyonudur. Bu nedenle bu özellik yalnızca okunabilir. Üst seri grubuna erişmek için **ParentSeriesGroup** özelliğini kullanın. Değeri değiştirmek için **ParentSeriesGroup.BubbleSizeRepresentation** okuma/yazma özelliğini kullanın.

--------------------

Bu, **ParentSeriesGroup.BubbleSizeRepresentation** özelliğinin projeksiyonudur.

**Returns:**
int