---
title: IChartSeries
second_title: Aspose.Slides for Android via Java API Referansı
description: Bir grafik serisini temsil eder.
type: docs
url: /tr/com.aspose.slides/ichartseries/
---
**Uygulanan Tüm Arayüzler:**
[com.aspose.slides.IChartComponent](../../com.aspose.slides/ichartcomponent)
```
public interface IChartSeries extends IChartComponent
```

Bir grafik serisini temsil eder.
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [getExplosion()](#getExplosion--) | Açık bir pasta diliminin pasta grafiğinin merkezinden olan mesafesi, pasta çapının yüzdesi olarak ifade edilir. |
| [setExplosion(int value)](#setExplosion-int-) | Açık bir pasta diliminin pasta grafiğinin merkezinden olan mesafesi, pasta çapının yüzdesi olarak ifade edilir. |
| [getSmooth()](#getSmooth--) | Eğri yumuşatmayı temsil eder. |
| [setSmooth(boolean value)](#setSmooth-boolean-) | Eğri yumuşatmayı temsil eder. |
| [getMarker()](#getMarker--) | Seri işaretçisini döndürür. |
| [getBar3DShape()](#getBar3DShape--) | 3-B boyutlu çubuk grafiğinin bir serisinin şeklini belirtir. |
| [setBar3DShape(int value)](#setBar3DShape-int-) | 3-B boyutlu çubuk grafiğinin bir serisinin şeklini belirtir. |
| [getName()](#getName--) | Seri adını döndürür. |
| [getDataPoints()](#getDataPoints--) | Bu serinin veri noktalarının koleksiyonunu döndürür. |
| [getType()](#getType--) | Bu serinin tipini döndürür. |
| [setType(int value)](#setType-int-) | Bu serinin tipini döndürür. |
| [getParentSeriesGroup()](#getParentSeriesGroup--) | Üst seri grubunu döndürür. |
| [getFormat()](#getFormat--) | Bir serinin biçimini döndürür. |
| [getOrder()](#getOrder--) | Bir serinin sırasını döndürür. |
| [setOrder(int value)](#setOrder-int-) | Bir serinin sırasını döndürür. |
| [getLabels()](#getLabels--) | Bir serinin Etiketlerini döndürür. |
| [getTrendLines()](#getTrendLines--) | Seri eğilim hatlarının koleksiyonu (*Yalnızca okunur*) [ITrendlineCollection](../../com.aspose.slides/itrendlinecollection). |
| [getErrorBarsXFormat()](#getErrorBarsXFormat--) | X yönündeki serinin ErrorBars öğesini temsil eder. |
| [getErrorBarsYFormat()](#getErrorBarsYFormat--) | Y yönündeki serinin ErrorBars öğesini temsil eder. |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | Bu serinin ikinci değer ekseninde çizilip çizilmediğini gösterir. |
| [setPlotOnSecondAxis(boolean value)](#setPlotOnSecondAxis-boolean-) | Bu serinin ikinci değer ekseninde çizilip çizilmediğini gösterir. |
| [getNumberFormatOfValues()](#getNumberFormatOfValues--) | Seri değerleri için sayı biçimini alır veya ayarlar. |
| [setNumberFormatOfValues(String value)](#setNumberFormatOfValues-java.lang.String-) | Seri değerleri için sayı biçimini alır veya ayarlar. |
| [getNumberFormatOfXValues()](#getNumberFormatOfXValues--) | Seri x değerleri için sayı biçimini alır veya ayarlar. |
| [setNumberFormatOfXValues(String value)](#setNumberFormatOfXValues-java.lang.String-) | Seri x değerleri için sayı biçimini alır veya ayarlar. |
| [getNumberFormatOfYValues()](#getNumberFormatOfYValues--) | Seri y değerleri için sayı biçimini alır veya ayarlar. |
| [setNumberFormatOfYValues(String value)](#setNumberFormatOfYValues-java.lang.String-) | Seri y değerleri için sayı biçimini alır veya ayarlar. |
| [getNumberFormatOfBubbleSizes()](#getNumberFormatOfBubbleSizes--) | Seri balon boyutları için sayı biçimini alır veya ayarlar. |
| [setNumberFormatOfBubbleSizes(String value)](#setNumberFormatOfBubbleSizes-java.lang.String-) | Seri balon boyutları için sayı biçimini alır veya ayarlar. |
| [getInvertIfNegative()](#getInvertIfNegative--) | Değer negatif olduğunda çubuk, sütun veya balon serisinin renklerinin tersine çevrilmesini belirtir. |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | Değer negatif olduğunda çubuk, sütun veya balon serisinin renklerinin tersine çevrilmesini belirtir. |
| [getInvertedSolidFillColor()](#getInvertedSolidFillColor--) | Seri için ters dolgu katı rengini belirtir. |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | Bu seriye ilişkin lejand girdisini temsil eder (*Yalnızca okunur*) [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties). |
| [getAutomaticSeriesColor()](#getAutomaticSeriesColor--) | Seri indeksine ve grafik stiline göre otomatik bir seri rengi döndürür. |
| [getShowInnerPoints()](#getShowInnerPoints--) | İç noktaları temsil eder. |
| [setShowInnerPoints(boolean value)](#setShowInnerPoints-boolean-) | İç noktaları temsil eder. |
| [getShowOutlierPoints()](#getShowOutlierPoints--) | Aykırı noktalara ait noktaları temsil eder. |
| [setShowOutlierPoints(boolean value)](#setShowOutlierPoints-boolean-) | Aykırı noktalara ait noktaları temsil eder. |
| [getShowMeanMarkers()](#getShowMeanMarkers--) | Ortalama işaretçilerini temsil eder. |
| [setShowMeanMarkers(boolean value)](#setShowMeanMarkers-boolean-) | Ortalama işaretçilerini temsil eder. |
| [getShowMeanLine()](#getShowMeanLine--) | Ortalama işaretçilerini temsil eder. |
| [setShowMeanLine(boolean value)](#setShowMeanLine-boolean-) | Ortalama işaretçilerini temsil eder. |
| [getQuartileMethod()](#getQuartileMethod--) | Çeyrek yöntemini temsil eder. |
| [setQuartileMethod(int value)](#setQuartileMethod-int-) | Çeyrek yöntemini temsil eder. |
| [getShowConnectorLines()](#getShowConnectorLines--) | Bağlayıcı hatları temsil eder. |
| [setShowConnectorLines(boolean value)](#setShowConnectorLines-boolean-) | Bağlayıcı hatları temsil eder. |
| [getParentLabelLayout()](#getParentLabelLayout--) | Üst kategori etiketlerinin düzenini temsil eder. |
| [setParentLabelLayout(int value)](#setParentLabelLayout-int-) | Üst kategori etiketlerinin düzenini temsil eder. |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | Balon grafiği için ölçek faktörünü belirtir (0 ile 300 % arasında olabilir). |
| [hasUpDownBars()](#hasUpDownBars--) | Çizgi-veya hisse senedi grafiğinin yukarı/aşağı çubukları olup olmadığını belirler. |
| [getGapWidth()](#getGapWidth--) | Çubuk veya sütun kümeleri arasındaki boşluğu, çubuk veya sütun genişliğinin yüzde olarak belirtir. |
| [getGapDepth()](#getGapDepth--) | 3D bir grafikte veri serileri arasındaki mesafeyi, işaretçi genişliğinin yüzde olarak alır veya ayarlar. |
| [isColorVaried()](#isColorVaried--) | Serideki her veri işaretçisinin farklı bir renge sahip olduğunu belirtir. |
| [hasSeriesLines()](#hasSeriesLines--) | Bu seri ve ilişkili seriler için seri hatlarının var olup olmadığını belirler. |
| [getOverlap()](#getOverlap--) | 2-D grafiklerde çubuk ve sütunların ne kadar üst üste geleceğini yüzde olarak belirtir (-100 %-100 %). |
| [getSecondPieSize()](#getSecondPieSize--) | Pie-of-pie ya da bar-of-pie grafiğinde ikinci pasta ya da çubuğun boyutunu, ilk pastanın yüzde olarak belirtir (5-200 %). |
| [getPieSplitPosition()](#getPieSplitPosition--) | Pie-of-pie ya da bar-of-pie grafiğinde ikinci pasta ya da çubukta hangi veri noktalarının yer alacağını belirlemek için kullanılacak değeri belirtir. |
| [getPieSplitBy()](#getPieSplitBy--) | Pie-of-pie ya da bar-of-pie grafiğinde ikinci pasta ya da çubukta hangi veri noktalarının yer alacağını nasıl belirleyeceğinizi belirtir. |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | Donut grafiğindeki çukurun boyutunu belirtir (grafik alanının yüzde 10-90 % arası). |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | İlk pasta veya donut diliminin açısını derece cinsinden belirtir (yukarıdan saat yönünde, 0-360). |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | Özelleştirilmiş bölme bilgisi, özelleştirilmiş bölme kullanılan pie-of-pie ya da bar-of-pie grafiği için. |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | Balon grafiğinde balon boyutu değerlerinin nasıl temsil edileceğini belirtir. |
### getExplosion() {#getExplosion--}
```
public abstract int getExplosion()
```

Açık bir pasta diliminin pasta grafiğinin merkezinden olan mesafesi, pasta çapının yüzde olarak ifade edilir. *Okunur/Yazılabilir* int.

**Döndürür:**
int
### setExplosion(int value) {#setExplosion-int-}
```
public abstract void setExplosion(int value)
```

Açık bir pasta diliminin pasta grafiğinin merkezinden olan mesafesi, pasta çapının yüzde olarak ifade edilir. *Okunur/Yazılabilir* int.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |
### getSmooth() {#getSmooth--}
```
public abstract boolean getSmooth()
```

Eğri yumuşatmayı temsil eder. Çizgi grafiği veya dağılım grafiği için eğri yumuşatma açıksa *True*. Yalnızca çizgi ve çizgilerle bağlanan dağılım grafiklerinde uygulanır. *Okunur/Yazılabilir* boolean.

**Döndürür:**
boolean
### setSmooth(boolean value) {#setSmooth-boolean-}
```
public abstract void setSmooth(boolean value)
```

Eğri yumuşatmayı temsil eder. Çizgi grafiği veya dağılım grafiği için eğri yumuşatma açıksa *True*. Yalnızca çizgi ve çizgilerle bağlanan dağılım grafiklerinde uygulanır. *Okunur/Yazılabilir* boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |
### getMarker() {#getMarker--}
```
public abstract IMarker getMarker()
```

Seri işaretçisini döndürür. *Yalnızca okunur* [IMarker](../../com.aspose.slides/imarker).

**Döndürür:**
[IMarker](../../com.aspose.slides/imarker)
### getBar3DShape() {#getBar3DShape--}
```
public abstract int getBar3DShape()
```

3-B boyutlu çubuk grafiğinin bir serisinin şeklini belirtir. Bu özelliğin değeri değiştirildiğinde serinin Tipi otomatik olarak değişebilir. *Okunur/Yazılabilir* [ChartShapeType](../../com.aspose.slides/chartshapetype).

**Döndürür:**
int
### setBar3DShape(int value) {#setBar3DShape-int-}
```
public abstract void setBar3DShape(int value)
```

3-B boyutlu çubuk grafiğinin bir serisinin şeklini belirtir. Bu özelliğin değeri değiştirildiğinde serinin Tipi otomatik olarak değişebilir. *Okunur/Yazılabilir* [ChartShapeType](../../com.aspose.slides/chartshapetype).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |
### getName() {#getName--}
```
public abstract IStringChartValue getName()
```

Seri adını döndürür. *Yalnızca okunur* [IStringChartValue](../../com.aspose.slides/istringchartvalue).

**Döndürür:**
[IStringChartValue](../../com.aspose.slides/istringchartvalue)
### getDataPoints() {#getDataPoints--}
```
public abstract IChartDataPointCollection getDataPoints()
```

Bu serinin veri noktalarının koleksiyonunu döndürür. *Yalnızca okunur* [IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection).

**Döndürür:**
[IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection)
### getType() {#getType--}
```
public abstract int getType()
```

Bu serinin tipini döndürür. *Okunur/Yazılabilir* [ChartType](../../com.aspose.slides/charttype).

**Döndürür:**
int
### setType(int value) {#setType-int-}
```
public abstract void setType(int value)
```

Bu serinin tipini döndürür. *Okunur/Yazılabilir* [ChartType](../../com.aspose.slides/charttype).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |
### getParentSeriesGroup() {#getParentSeriesGroup--}
```
public abstract IChartSeriesGroup getParentSeriesGroup()
```

Üst seri grubunu döndürür. *Yalnızca okunur* [IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup).

**Döndürür:**
[IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup)
### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

Serinin biçimini döndürür. *Yalnızca okunur* [IFormat](../../com.aspose.slides/iformat).

**Döndürür:**
[IFormat](../../com.aspose.slides/iformat)
### getOrder() {#getOrder--}
```
public abstract int getOrder()
```

Serinin sırasını döndürür. *Okunur/Yazılabilir* int.

**Döndürür:**
int
### setOrder(int value) {#setOrder-int-}
```
public abstract void setOrder(int value)
```

Serinin sırasını döndürür. *Okunur/Yazılabilir* int.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |
### getLabels() {#getLabels--}
```
public abstract IDataLabelCollection getLabels()
```

Serinin Etiketlerini döndürür. *Yalnızca okunur* [IDataLabelCollection](../../com.aspose.slides/idatalabelcollection).

**Döndürür:**
[IDataLabelCollection](../../com.aspose.slides/idatalabelcollection)
### getTrendLines() {#getTrendLines--}
```
public abstract ITrendlineCollection getTrendLines()
```

Seri eğilim hatlarının koleksiyonu (*Yalnızca okunur*) [ITrendlineCollection](../../com.aspose.slides/itrendlinecollection).

**Döndürür:**
[ITrendlineCollection](../../com.aspose.slides/itrendlinecollection)
### getErrorBarsXFormat() {#getErrorBarsXFormat--}
```
public abstract IErrorBarsFormat getErrorBarsXFormat()
```

X yönündeki serinin ErrorBars öğesini temsil eder. *Yalnızca okunur* [IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat).

--------------------

X yönündeki ErrorBars, area, bar, scatter ve bubble tipindeki seriler için kullanılabilir. Diğer grafik tipleri için bu özellik **null** döndürür (3D grafikler dahil). Özel değerler için ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues)) özelliğiyle değer belirlemek amacıyla DataPoints koleksiyonu kullanılır.

**Döndürür:**
[IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)
### getErrorBarsYFormat() {#getErrorBarsYFormat--}
```
public abstract IErrorBarsFormat getErrorBarsYFormat()
```

Y yönündeki serinin ErrorBars öğesini temsil eder. *Yalnızca okunur* [IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat).

--------------------

Y yönündeki ErrorBars, area, bar, line, scatter ve bubble tipindeki seriler için kullanılabilir. Diğer grafik tipleri için bu özellik **null** döndürür (3D grafikler dahil). Özel değerler için ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues)) özelliğiyle değer belirlemek amacıyla DataPoints koleksiyonu kullanılır.

**Döndürür:**
[IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)
### getPlotOnSecondAxis() {#getPlotOnSecondAxis--}
```
public abstract boolean getPlotOnSecondAxis()
```

Bu serinin ikinci değer ekseninde çizilip çizilmediğini gösterir. *Okunur/Yazılabilir* boolean.

**Döndürür:**
boolean
### setPlotOnSecondAxis(boolean value) {#setPlotOnSecondAxis-boolean-}
```
public abstract void setPlotOnSecondAxis(boolean value)
```

Bu serinin ikinci değer ekseninde çizilip çizilmediğini gösterir. *Okunur/Yazılabilir* boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |
### getNumberFormatOfValues() {#getNumberFormatOfValues--}
```
public abstract String getNumberFormatOfValues()
```

Seri değerleri için sayı biçimini alır veya ayarlar. *Okunur/Yazılabilir* String.

**Döndürür:**
java.lang.String
### setNumberFormatOfValues(String value) {#setNumberFormatOfValues-java.lang.String-}
```
public abstract void setNumberFormatOfValues(String value)
```

Seri değerleri için sayı biçimini alır veya ayarlar. *Okunur/Yazılabilir* String.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |
### getNumberFormatOfXValues() {#getNumberFormatOfXValues--}
```
public abstract String getNumberFormatOfXValues()
```

Seri x değerleri için sayı biçimini alır veya ayarlar. *Okunur/Yazılabilir* String.

**Döndürür:**
java.lang.String
### setNumberFormatOfXValues(String value) {#setNumberFormatOfXValues-java.lang.String-}
```
public abstract void setNumberFormatOfXValues(String value)
```

Seri x değerleri için sayı biçimini alır veya ayarlar. *Okunur/Yazılabilir* String.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |
### getNumberFormatOfYValues() {#getNumberFormatOfYValues--}
```
public abstract String getNumberFormatOfYValues()
```

Seri y değerleri için sayı biçimini alır veya ayarlar. *Okunur/Yazılabilir* String.

**Döndürür:**
java.lang.String
### setNumberFormatOfYValues(String value) {#setNumberFormatOfYValues-java.lang.String-}
```
public abstract void setNumberFormatOfYValues(String value)
```

Seri y değerleri için sayı biçimini alır veya ayarlar. *Okunur/Yazılabilir* String.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |
### getNumberFormatOfBubbleSizes() {#getNumberFormatOfBubbleSizes--}
```
public abstract String getNumberFormatOfBubbleSizes()
```

Seri balon boyutları için sayı biçimini alır veya ayarlar. *Okunur/Yazılabilir* String.

**Döndürür:**
java.lang.String
### setNumberFormatOfBubbleSizes(String value) {#setNumberFormatOfBubbleSizes-java.lang.String-}
```
public abstract void setNumberFormatOfBubbleSizes(String value)
```

Seri balon boyutları için sayı biçimini alır veya ayarlar. *Okunur/Yazılabilir* String.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |
### getInvertIfNegative() {#getInvertIfNegative--}
```
public abstract boolean getInvertIfNegative()
```

Değer negatif olduğunda çubuk, sütun veya balon serisinin renklerinin tersine çevrilmesini belirtir. *Okunur/Yazılabilir* boolean.

**Döndürür:**
boolean
### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public abstract void setInvertIfNegative(boolean value)
```

Değer negatif olduğunda çubuk, sütun veya balon serisinin renklerinin tersine çevrilmesini belirtir. *Okunur/Yazılabilir* boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |
### getInvertedSolidFillColor() {#getInvertedSolidFillColor--}
```
public abstract IColorFormat getInvertedSolidFillColor()
```

Seri için ters dolgu katı rengini belirtir. Renk ayarını uygulamak için seri biçiminde FillType değerini FillType.Solid olarak ayarlayın. *Okunur/Yazılabilir* [IColorFormat](../../com.aspose.slides/icolorformat).

**Döndürür:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public abstract ILegendEntryProperties getRelatedLegendEntry()
```

Bu seriye ilişkin lejand girdisini temsil eder (*Yalnızca okunur*) [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**Döndürür:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)
### getAutomaticSeriesColor() {#getAutomaticSeriesColor--}
```
public abstract Integer getAutomaticSeriesColor()
```

Seri indeksine ve grafik stiline göre otomatik bir seri rengi döndürür. Bu renk, FillType **NotDefined** olduğunda varsayılan olarak kullanılır.

**Döndürür:**
java.lang.Integer - Otomatik seri rengi java.lang.Integer
### getShowInnerPoints() {#getShowInnerPoints--}
```
public abstract boolean getShowInnerPoints()
```

İç noktaları temsil eder. BoxAndWhisker grafiğinde iç noktalar gösteriliyorsa *True*. Yalnızca BoxAndWhisker grafiklerinde uygulanır. *Okunur/Yazılabilir* boolean.

**Döndürür:**
boolean
### setShowInnerPoints(boolean value) {#setShowInnerPoints-boolean-}
```
public abstract void setShowInnerPoints(boolean value)
```

İç noktaları temsil eder. BoxAndWhisker grafiğinde iç noktalar gösteriliyorsa *True*. Yalnızca BoxAndWhisker grafiklerinde uygulanır. *Okunur/Yazılabilir* boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |
### getShowOutlierPoints() {#getShowOutlierPoints--}
```
public abstract boolean getShowOutlierPoints()
```

Aykırı noktalara ait noktaları temsil eder. BoxAndWhisker grafiğinde aykırı noktalar gösteriliyorsa *True*. Yalnızca BoxAndWhisker grafiklerinde uygulanır. *Okunur/Yazılabilir* boolean.

**Döndürür:**
boolean
### setShowOutlierPoints(boolean value) {#setShowOutlierPoints-boolean-}
```
public abstract void setShowOutlierPoints(boolean value)
```

Aykırı noktalara ait noktaları temsil eder. BoxAndWhisker grafiğinde aykırı noktalar gösteriliyorsa *True*. Yalnızca BoxAndWhisker grafiklerinde uygulanır. *Okunur/Yazılabilir* boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |
### getShowMeanMarkers() {#getShowMeanMarkers--}
```
public abstract boolean getShowMeanMarkers()
```

Ortalama işaretçilerini temsil eder. BoxAndWhisker grafiğinde ortalama işaretçileri gösteriliyorsa *True*. Yalnızca BoxAndWhisker grafiklerinde uygulanır. *Okunur/Yazılabilir* boolean.

**Döndürür:**
boolean
### setShowMeanMarkers(boolean value) {#setShowMeanMarkers-boolean-}
```
public abstract void setShowMeanMarkers(boolean value)
```

Ortalama işaretçilerini temsil eder. BoxAndWhisker grafiğinde ortalama işaretçileri gösteriliyorsa *True*. Yalnızca BoxAndWhisker grafiklerinde uygulanır. *Okunur/Yazılabilir* boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |
### getShowMeanLine() {#getShowMeanLine--}
```
public abstract boolean getShowMeanLine()
```

Ortalama işaretçilerini temsil eder. BoxAndWhisker grafiğinde ortalama çizgi gösteriliyorsa *True*. Yalnızca BoxAndWhisker grafiklerinde uygulanır. *Okunur/Yazılabilir* boolean.

**Döndürür:**
boolean
### setShowMeanLine(boolean value) {#setShowMeanLine-boolean-}
```
public abstract void setShowMeanLine(boolean value)
```

Ortalama işaretçilerini temsil eder. BoxAndWhisker grafinde ortalama çizgi gösteriliyorsa *True*. Yalnızca BoxAndWhisker grafiklerinde uygulanır. *Okunur/Yazılabilir* boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |
### getQuartileMethod() {#getQuartileMethod--}
```
public abstract int getQuartileMethod()
```

Çeyrek yöntemini temsil eder. Yalnızca BoxAndWhisker grafiklerinde uygulanır.

**Döndürür:**
int
### setQuartileMethod(int value) {#setQuartileMethod-int-}
```
public abstract void setQuartileMethod(int value)
```

Çeyrek yöntemini temsil eder. Yalnızca BoxAndWhisker grafiklerinde uygulanır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |
### getShowConnectorLines() {#getShowConnectorLines--}
```
public abstract boolean getShowConnectorLines()
```

Bağlayıcı hatları temsil eder. Yalnızca Waterfall grafiklerinde uygulanır.

**Döndürür:**
boolean
### setShowConnectorLines(boolean value) {#setShowConnectorLines-boolean-}
```
public abstract void setShowConnectorLines(boolean value)
```

Bağlayıcı hatları temsil eder. Yalnızca Waterfall grafiklerinde uygulanır.

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

Balon grafiği için ölçek faktörünü belirtir (0 ile 300 % arasında olabilir). Bu özellik yalnızca bu seri için değil, üst seri grubundaki tüm seriler için geçerlidir – ilgili grup özelliğinin bir yansımasıdır. Bu yüzden *Yalnızca okunur* dur. Üst seri grubuna erişmek için **ParentSeriesGroup** özelliğini kullanın. Değiştirmek için **ParentSeriesGroup.BubbleSizeScale** özelliğini kullanın.

--------------------

Bu, **ParentSeriesGroup.BubbleSizeScale** özelliğinin bir yansısadır.

**Döndürür:**
int
### hasUpDownBars() {#hasUpDownBars--}
```
public abstract boolean hasUpDownBars()
```

Çizgi-veya hisse senedi grafiğinin yukarı/aşağı çubukları olup olmadığını belirler. Bu özellik yalnızca bu seri için değil, üst seri grubundaki tüm seriler için geçerlidir – ilgili grup özelliğinin bir yansısıdır. Bu yüzden *Yalnızca okunur* dur. Üst seri grubuna erişmek için **ParentSeriesGroup** özelliğini, değeri değiştirmek için **ParentSeriesGroup.UpDownBars.HasUpDownBars** özelliğini, çubukları biçimlendirmek için **ParentSeriesGroup.UpDownBars** özelliğini kullanın. *Yalnızca okunur* boolean.

--------------------

Bu, **ParentSeriesGroup.UpDownBars.HasUpDownBars** özelliğinin bir yansısadır.

**Döndürür:**
boolean
### getGapWidth() {#getGapWidth--}
```
public abstract int getGapWidth()
```

Çubuk veya sütun kümeleri arasındaki boşluğu, çubuk veya sütun genişliğinin yüzde olarak belirtir. Bu özellik yalnızca bu seri için değil, üst seri grubundaki tüm seriler için geçerlidir – ilgili grup özelliğinin bir yansısıdır. Bu yüzden *Yalnızca okunur* dur. Değiştirmek için **ParentSeriesGroup.GapWidth** özelliğini kullanın. *Yalnızca okunur* int.

--------------------

Bu, **ParentSeriesGroup.GapWidth** özelliğinin bir yansısadır.

**Döndürür:**
int
### getGapDepth() {#getGapDepth--}
```
public  int  get  GapDepth()
```

3D bir grafikte veri serileri arasındaki mesafeyi, işaretçi genişliğinin yüzde olarak alır veya ayarlar. Bu özellik yalnızca bu seri için değil, üst seri grubundaki tüm seriler için geçerlidir – ilgili grup özelliğinin bir yansısıdır. Bu yüzden *Yalnızca okunur* dur. Değiştirmek için **ParentSeriesGroup.GapDepth** özelliğini kullanın. *Yalnızca okunur* int.

--------------------

Bu, **ParentSeriesGroup.GapDepth** özelliğinin bir yansısadır.

**Döndürür:**
int
### isColorVaried() {#isColorVaried--}
```
public abstract boolean isColorVaried()
```

Serideki her veri işaretçisinin farklı bir renge sahip olduğunu belirtir. Bu özellik yalnızca bu seri için değil, üst seri grubundaki tüm seriler için geçerlidir – ilgili grup özelliğinin bir yansısıdır. Bu yüzden *Yalnızca okunur* dur. Değiştirmek için **ParentSeriesGroup.IsColorVaried** özelliğini kullanın. *Yalnızca okunur* boolean.

--------------------

Bu, **ParentSeriesGroup.IsColorVaried** özelliğinin bir yansısadır.

**Döndürür:**
boolean
### hasSeriesLines() {#hasSeriesLines--}
```
public abstract boolean hasSeriesLines()
```

Bu seri ve ilişkili seriler için seri hatlarının var olup olmadığını belirler. Bu özellik yalnızca bu seri için değil, üst seri grubundaki tüm seriler için geçerlidir – ilgili grup özelliğinin bir yansısıdır. Bu yüzden *Yalnızca okunur* dur. Değiştirmek için **ParentSeriesGroup.HasSeriesLines** özelliğini, biçimlendirme için **ParentSeriesGroup.SeriesLinesFormat** özelliğini kullanın. *Yalnızca okunur* boolean.

--------------------

Bu, **ParentSeriesGroup.HasSeriesLines** özelliğinin bir yansısadır.

**Döndürür:**
boolean
### getOverlap() {#getOverlap--}
```
public abstract byte getOverlap()
```

2-D grafiklerde çubuk ve sütunların ne kadar üst üste geleceğini yüzde olarak belirtir (-100 %-100 %). Bu özellik yalnızca bu seri için değil, üst seri grubundaki tüm seriler için geçerlidir. Değiştirmek için **ParentSeriesGroup.Overlap** özelliğini kullanın. *Yalnızca okunur* byte.

--------------------

Üst Üst Üst Üst Üst Üst: -100 %: maksimum boşluk (çubuklar tamamen ayrılır). 0 %: çubuklar yan yana, üst üste gelmez veya boşluk yok. 100 %: maksimum üst üste gelme (çubuklar tamamen üst üste). Bu, **ParentSeriesGroup.Overlap** özelliğinin bir yansısadır.

**Döndürür:**
byte
### getSecondPieSize() {#getSecondPieSize--}
```
public abstract int getSecondPieSize()
```

Pie-of-pie ya da bar-of-pie grafiğinde ikinci pasta ya da çubuğun boyutunu, ilk pastanın yüzde olarak belirtir (5-200 %). Bu özellik yalnızca bu seri için değil, üst seri grubundaki tüm seriler için geçerlidir. Değiştirmek için **ParentSeriesGroup.SecondPieSize** özelliğini kullanın. *Yalnızca okunur* int.

--------------------

Bu, **ParentSeriesGroup.SecondPieSize** özelliğinin bir yansısadır.

**Döndürür:**
int
### getPieSplitPosition() {#getPieSplitPosition--}
```
public abstract double getPieSplitPosition()
```

Pie-of-pie ya da bar-of-pie grafiğinde ikinci pasta ya da çubuğa hangi veri noktalarının dahil edileceğini belirlemek için kullanılacak değeri belirtir. PieSplitBy özelliğiyle birlikte kullanılır. Bu özellik yalnızca bu seri için değil, üst seri grubundaki tüm seriler için geçerlidir. Değiştirmek için **ParentSeriesGroup.PieSplitPosition** özelliğini kullanın. *Yalnızca okunur* double.

--------------------

Bu, **ParentSeriesGroup.PieSplitPosition** özelliğinin bir yansısadır.

**Döndürür:**
double
### getPieSplitBy() {#getPieSplitBy--}
```
public abstract int getPieSplitBy()
```

Pie-of-pie ya da bar-of-pie grafiğinde ikinci pasta ya da çubuğa hangi veri noktalarının dahil edileceğini nasıl belirleyeceğinizi belirtir. Bu özellik yalnızca bu seri için değil, üst seri grubundaki tüm seriler için geçerlidir. Değiştirmek için **ParentSeriesGroup.PieSplitBy** özelliğini kullanın. *Yalnızca okunur* [PieSplitType](../../com.aspose.slides/piesplittype).

--------------------

1) Bu, **ParentSeriesGroup.PieSplitBy** özelliğinin bir yansısıdır. 2) Özellik değeri **PieSplitType.Custom** ise, **ParentSeriesGroup.PieSplitCustomPoints** özelliğiyle özel bölme bilgisi tanımlanabilir.

**Döndürür:**
int
### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public abstract byte getDoughnutHoleSize()
```

Donut grafiğindeki çukurun boyutunu belirtir (grafik alanının yüzde 10-90 % arası). Bu özellik yalnızca bu seri için değil, üst seri grubundaki tüm seriler için geçerlidir. Değiştirmek için **ParentSeriesGroup.DoughnutHoleSize** özelliğini kullanın. *Yalnızca okunur* byte.

--------------------

Bu, **ParentSeriesGroup.DoughnutHoleSize** özelliğinin bir yansısadır.

**Döndürür:**
byte
### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public abstract int getFirstSliceAngle()
```

İlk pasta ya da donut diliminin açısını derece cinsinden belirtir (yukarıdan saat yönünde, 0-360 derece). Bu özellik yalnızca bu seri için değil, üst seri grubundaki tüm seriler için geçerlidir. Değiştirmek için **ParentSeriesGroup.FirstSliceAngle** özelliğini kullanın. *Yalnızca okunur* int.

--------------------

Bu, **ParentSeriesGroup.FirstSliceAngle** özelliğinin bir yansısadır.

**Döndürür:**
int
### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public abstract IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

Özelleştirilmiş bölme bilgisi, özelleştirilmiş bölme kullanılan pie-of-pie ya da bar-of-pie grafiği için. İkinci pasta ya da çubukta çizilecek veri noktalarını içerir. *Yalnızca okunur* [IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection).

--------------------

Bu, **ParentSeriesGroup.PieSplitCustomPoints** özelliğinin bir yansısadır.

**Döndürür:**
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)
### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public abstract int getBubbleSizeRepresentation()
```

Balon grafiğinde balon boyutu değerlerinin nasıl temsil edileceğini belirtir. Bu özellik yalnızca bu seri için değil, üst seri grubundaki tüm seriler için geçerlidir. Değiştirmek için **ParentSeriesGroup.BubbleSizeRepresentation** özelliğini kullanın.

--------------------

Bu, **ParentSeriesGroup.BubbleSizeRepresentation** özelliğinin bir yansısadır.

**Döndürür:**
int