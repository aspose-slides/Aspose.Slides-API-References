---
title: ChartSeries
second_title: Aspose.Slides for Android için Java API Referansı
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
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getChart()](#getChart--) | Üst grafiği döndürür. |
| [getExplosion()](#getExplosion--) | Açık bir pasta diliminin pasta grafiğinin merkezinden uzaklığı, pasta çapının yüzde olarak ifadesi olarak belirtilir. |
| [setExplosion(int value)](#setExplosion-int-) | Açık bir pasta diliminin pasta grafiğinin merkezinden uzaklığı, pasta çapının yüzde olarak ifadesi olarak belirtilir. |
| [getSmooth()](#getSmooth--) | Eğri yumuşatmayı temsil eder. |
| [setSmooth(boolean value)](#setSmooth-boolean-) | Eğri yumuşatmayı temsil eder. |
| [getName()](#getName--) | Seri adını döndürür. |
| [getDataPoints()](#getDataPoints--) | Bu serinin veri noktaları koleksiyonunu döndürür. |
| [getType()](#getType--) | Bu serinin bir tipini döndürür. |
| [setType(int value)](#setType-int-) | Bu serinin bir tipini döndürür. |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | Serinin ikincil eksende çizilip çizilmediğini gösterir. |
| [setPlotOnSecondAxis(boolean value)](#setPlotOnSecondAxis-boolean-) | Serinin ikincil eksende çizilip çizilmediğini gösterir. |
| [getParentSeriesGroup()](#getParentSeriesGroup--) | ParentSeriesGroup. |
| [getFormat()](#getFormat--) | Bir serinin formatını döndürür. |
| [getOrder()](#getOrder--) | Bir serinin sırasını döndürür. |
| [setOrder(int value)](#setOrder-int-) | Bir serinin sırasını döndürür. |
| [getLabels()](#getLabels--) | Bir serinin Etiketlerini döndürür. |
| [getTrendLines()](#getTrendLines--) | Seri eğilim çizgileri koleksiyonu. |
| [getErrorBarsXFormat()](#getErrorBarsXFormat--) | X yönündeki serinin ErrorBars'ını temsil eder. |
| [getErrorBarsYFormat()](#getErrorBarsYFormat--) | Y yönündeki serinin ErrorBars'ını temsil eder. |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | Bu seriyle ilgili lejand girdisini temsil eder Yalnızca-okunur [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties). |
| [getNumberFormatOfValues()](#getNumberFormatOfValues--) | NumberFormatOfValues. |
| [setNumberFormatOfValues(String value)](#setNumberFormatOfValues-java.lang.String-) | NumberFormatOfValues. |
| [getNumberFormatOfXValues()](#getNumberFormatOfXValues--) | NumberFormatOfXValues. |
| [setNumberFormatOfXValues(String value)](#setNumberFormatOfXValues-java.lang.String-) | NumberFormatOfXValues. |
| [getNumberFormatOfYValues()](#getNumberFormatOfYValues--) | NumberFormatOfYValues. |
| [setNumberFormatOfYValues(String value)](#setNumberFormatOfYValues-java.lang.String-) | NumberFormatOfYValues. |
| [getNumberFormatOfBubbleSizes()](#getNumberFormatOfBubbleSizes--) | NumberFormatOfBubbleSizes. |
| [setNumberFormatOfBubbleSizes(String value)](#setNumberFormatOfBubbleSizes-java.lang.String-) | NumberFormatOfBubbleSizes. |
| [getMarker()](#getMarker--) | İşaretleyici. |
| [getBar3DShape()](#getBar3DShape--) | 3-D çubuk grafiğinin bir serisinin şeklini belirtir. |
| [setBar3DShape(int value)](#setBar3DShape-int-) | 3-D çubuk grafiğinin bir serisinin şeklini belirtir. |
| [getInvertIfNegative()](#getInvertIfNegative--) | Değer negatif ise çubuk, sütun veya balon serisinin renklerini tersine çevireceğini belirtir. |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | Değer negatif ise çubuk, sütun veya balon serisinin renklerini tersine çevireceğini belirtir. |
| [getInvertedSolidFillColor()](#getInvertedSolidFillColor--) | Seri için ters katı rengi belirtir. |
| [getAutomaticSeriesColor()](#getAutomaticSeriesColor--) | Seri indeksine ve grafik stiline göre otomatik bir renk döndürür. |
| [getShowInnerPoints()](#getShowInnerPoints--) | İç noktaları temsil eder. |
| [setShowInnerPoints(boolean value)](#setShowInnerPoints-boolean-) | İç noktaları temsil eder. |
| [getShowOutlierPoints()](#getShowOutlierPoints--) | Aykırı noktaları temsil eder. |
| [setShowOutlierPoints(boolean value)](#setShowOutlierPoints-boolean-) | Aykırı noktaları temsil eder. |
| [getShowMeanMarkers()](#getShowMeanMarkers--) | Ortalama işaretleyicileri temsil eder. |
| [setShowMeanMarkers(boolean value)](#setShowMeanMarkers-boolean-) | Ortalama işaretleyicileri temsil eder. |
| [getShowMeanLine()](#getShowMeanLine--) | Ortalama çizgiyi temsil eder. |
| [setShowMeanLine(boolean value)](#setShowMeanLine-boolean-) | Ortalama çizgiyi temsil eder. |
| [getQuartileMethod()](#getQuartileMethod--) | Çeyrek yöntemini temsil eder. |
| [setQuartileMethod(int value)](#setQuartileMethod-int-) | Çeyrek yöntemini temsil eder. |
| [getShowConnectorLines()](#getShowConnectorLines--) | Bağlayıcı çizgileri temsil eder. |
| [setShowConnectorLines(boolean value)](#setShowConnectorLines-boolean-) | Bağlayıcı çizgileri temsil eder. |
| [getParentLabelLayout()](#getParentLabelLayout--) | Üst kategori etiketlerinin düzenini temsil eder. |
| [setParentLabelLayout(int value)](#setParentLabelLayout-int-) | Üst kategori etiketlerinin düzenini temsil eder. |
| [hasUpDownBars()](#hasUpDownBars--) | Çizgi veya Hisse grafiğinin yükseliş/aşağı düşüş çubuklarına sahip olup olmadığını belirler. |
| [getGapWidth()](#getGapWidth--) | Çubuk veya sütun kümeleri arasındaki boşluğu, çubuk veya sütun genişliğinin yüzde olarak belirtir. |
| [getGapDepth()](#getGapDepth--) | 3D grafikte veri serileri arasındaki mesafeyi, işaretleyici genişliğinin yüzde olarak döndürür veya ayarlar. |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | İlk pasta veya halka diliminin açısını derece olarak belirtir (yukarıdan saat yönünde, 0'dan 360 dereceye). |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | Halkanın içindeki deliğin boyutunu belirtir (çizim alanının %10 ile %90 arasında olabilir). |
| [getOverlap()](#getOverlap--) | 2D grafikleri üzerindeki çubuk ve sütunların ne kadar üst üste geleceğini yüzde olarak belirtir (-100% ile %100 arasında). |
| [getSecondPieSize()](#getSecondPieSize--) | Pie-of-pie veya bar-of-pie grafiğinin ikinci pasta ya da çubuğunun boyutunu, ilk pastanın boyutunun yüzde olarak belirtir ( %5 ile %200 arasında). |
| [hasSeriesLines()](#hasSeriesLines--) | Bu seri ve yakın seriler için seri çizgileri olup olmadığını belirler. |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | Balon grafiğinde balon boyutu değerlerinin nasıl temsil edildiğini belirtir. |
| [getPieSplitPosition()](#getPieSplitPosition--) | Pie-of-pie veya bar-of-pie grafiğinde ikinci pasta veya çubukta hangi veri noktalarının bulunacağını belirlemek için kullanılacak değeri belirtir. |
| [getPieSplitBy()](#getPieSplitBy--) | Pie-of-pie veya bar-of-pie grafiğinde ikinci pasta veya çubukta hangi veri noktalarının bulunacağını belirleme yöntemini belirtir. |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | Özel bölme bilgisi, özel bölme ile bir pie-of-pie veya bar-of-pie grafiği için. |
| [isColorVaried()](#isColorVaried--) | Serideki her veri işaretleyicisinin farklı renge sahip olduğunu belirtir. |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | Balon grafiği için ölçek faktörünü belirtir (varsayılan boyutun %0 ile %300 arasında). |
| [getSlide()](#getSlide--) | FillFormat'un üst slaytını döndürür. |
| [getPresentation()](#getPresentation--) | FillFormat'un üst sunumunu döndürür. |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate nesnesini döndürür. Yalnızca-okunur IDOMObject.

**Döndürür:**
com.aspose.slides.IDOMObject
### getChart() {#getChart--}
```
public final IChart getChart()
```

Üst grafiği döndürür. Yalnızca-okunur [IChart](../../com.aspose.slides/ichart).

**Döndürür:**
[IChart](../../com.aspose.slides/ichart)
### getExplosion() {#getExplosion--}
```
public final int getExplosion()
```

Açık bir pasta diliminin pasta grafiğinin merkezinden uzaklığı, pasta çapının yüzde olarak ifade edilir. Okunur/yazılır int.

**Döndürür:**
int
### setExplosion(int value) {#setExplosion-int-}
```
public final void setExplosion(int value)
```

Açık bir pasta diliminin pasta grafiğinin merkezinden uzaklığı, pasta çapının yüzde olarak ifade edilir. Okunur/yazılır int.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |
### getSmooth() {#getSmooth--}
```
public final boolean getSmooth()
```

Eğri yumuşatmayı temsil eder. Çizgi grafiği veya dağılım grafiği için eğri yumuşatma açıksa doğru. Sadece çizgi ve çizgiyle bağlanan dağılım grafiklerine uygulanır. Okunur/yazılır boolean.

**Döndürür:**
boolean
### setSmooth(boolean value) {#setSmooth-boolean-}
```
public final void setSmooth(boolean value)
```

Eğri yumuşatmayı temsil eder. Çizgi grafiği veya dağılım grafiği için eğri yumuşatma açıksa doğru. Sadece çizgi ve çizgiyle bağlanan dağılım grafiklerine uygulanır. Okunur/yazılır boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |
### getName() {#getName--}
```
public final IStringChartValue getName()
```

Seri adını döndürür. Yalnızca-okunur [IStringChartValue](../../com.aspose.slides/istringchartvalue).

**Döndürür:**
[IStringChartValue](../../com.aspose.slides/istringchartvalue)
### getDataPoints() {#getDataPoints--}
```
public final IChartDataPointCollection getDataPoints()
```

Bu serinin veri noktaları koleksiyonunu döndürür. Yalnızca-okunur [IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection).

**Döndürür:**
[IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection)
### getType() {#getType--}
```
public final int getType()
```

Bu serinin bir tipini döndürür. Okunur/yazılır [ChartType](../../com.aspose.slides/charttype).

**Döndürür:**
int
### setType(int value) {#setType-int-}
```
public final void setType(int value)
```

Bu serinin bir tipini döndürür. Okunur/yazılır [ChartType](../../com.aspose.slides/charttype).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |
### getPlotOnSecondAxis() {#getPlotOnSecondAxis--}
```
public final boolean getPlotOnSecondAxis()
```

Serinin ikincil eksende çizilip çizilmediğini gösterir. Okunur/yazılır boolean.

**Döndürür:**
boolean
### setPlotOnSecondAxis(boolean value) {#setPlotOnSecondAxis-boolean-}
```
public final void setPlotOnSecondAxis(boolean value)
```

Serinin ikincil eksende çizilip çizilmediğini gösterir. Okunur/yazılır boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |
### getParentSeriesGroup() {#getParentSeriesGroup--}
```
public final IChartSeriesGroup getParentSeriesGroup()
```

ParentSeriesGroup. Yalnızca-okunur [IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup).

**Döndürür:**
[IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup)
### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

Bir serinin formatını döndürür. Yalnızca-okunur [IFormat](../../com.aspose.slides/iformat).

**Döndürür:**
[IFormat](../../com.aspose.slides/iformat)
### getOrder() {#getOrder--}
```
public final int getOrder()
```

Bir serinin sırasını döndürür. Okunur/yazılır int.

**Döndürür:**
int
### setOrder(int value) {#setOrder-int-}
```
public final void setOrder(int value)
```

Bir serinin sırasını döndürür. Okunur/yazılır int.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |
### getLabels() {#getLabels--}
```
public final IDataLabelCollection getLabels()
```

Bir serinin Etiketlerini döndürür. Yalnızca-okunur [IDataLabelCollection](../../com.aspose.slides/idatalabelcollection).

**Döndürür:**
[IDataLabelCollection](../../com.aspose.slides/idatalabelcollection)
### getTrendLines() {#getTrendLines--}
```
public final ITrendlineCollection getTrendLines()
```

Seri eğilim çizgileri koleksiyonu. Yalnızca-okunur [ITrendlineCollection](../../com.aspose.slides/itrendlinecollection).

TrendLines, yığılmamış 2D alan, çubuk, sütun, çizgi, hisse, xy (dağılım) ve balon grafiklerindeki veri serileri için (null olmayan) mevcuttur. Yığılmış veya 3D olan herhangi bir grafik tipindeki veri serileri için bir trend çizgisi mevcut değildir. TrendLines ayrıca radar, pasta, yüzey veya halka grafiklerde de mevcut değildir.

**Döndürür:**
[ITrendlineCollection](../../com.aspose.slides/itrendlinecollection)
### getErrorBarsXFormat() {#getErrorBarsXFormat--}
```
public final IErrorBarsFormat getErrorBarsXFormat()
```

X yönündeki serinin ErrorBars'ını temsil eder. Yalnızca-okunur [IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat).

ErrorBars with X direction are avalible for series of type area, bar, scatter and bubble. For any other types of chart this property returns null (including 3D charts). In case of custom values use DataPoints collection to specify value (with ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues)) property).

**Döndürür:**
[IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)
### getErrorBarsYFormat() {#getErrorBarsYFormat--}
```
public final IErrorBarsFormat getErrorBarsYFormat()
```

Y yönündeki serinin ErrorBars'ını temsil eder. Yalnızca-okunur [IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat).

ErrorBars with Y direction are avalible for series of type area, bar, line, scatter and bubble. For any other types of chart this property returns null (including 3D charts). In case of custom values use DataPoints collection to specify value (with ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues)) property).

**Döndürür:**
[IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)
### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public final ILegendEntryProperties getRelatedLegendEntry()
```

Bu seriyle ilgili lejand girdisini temsil eder Yalnızca-okunur [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**Döndürür:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)
### getNumberFormatOfValues() {#getNumberFormatOfValues--}
```
public final String getNumberFormatOfValues()
```

NumberFormatOfValues. Okunur/yazılır String.

**Döndürür:**
java.lang.String
### setNumberFormatOfValues(String value) {#setNumberFormatOfValues-java.lang.String-}
```
public final void setNumberFormatOfValues(String value)
```

NumberFormatOfValues. Okunur/yazılır String.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |
### getNumberFormatOfXValues() {#getNumberFormatOfXValues--}
```
public final String getNumberFormatOfXValues()
```

NumberFormatOfXValues. Okunur/yazılır String.

**Döndürür:**
java.lang.String
### setNumberFormatOfXValues(String value) {#setNumberFormatOfXValues-java.lang.String-}
```
public final void setNumberFormatOfXValues(String value)
```

NumberFormatOfXValues. Okunur/yazılır String.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |
### getNumberFormatOfYValues() {#getNumberFormatOfYValues--}
```
public final String getNumberFormatOfYValues()
```

NumberFormatOfYValues. Okunur/yazılır String.

**Döndürür:**
java.lang.String
### setNumberFormatOfYValues(String value) {#setNumberFormatOfYValues-java.lang.String-}
```
public final void setNumberFormatOfYValues(String value)
```

NumberFormatOfYValues. Okunur/yazılır String.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |
### getNumberFormatOfBubbleSizes() {#getNumberFormatOfBubbleSizes--}
```
public final String getNumberFormatOfBubbleSizes()
```

NumberFormatOfBubbleSizes. Okunur/yazılır String.

**Döndürür:**
java.lang.String
### setNumberFormatOfBubbleSizes(String value) {#setNumberFormatOfBubbleSizes-java.lang.String-}
```
public final void setNumberFormatOfBubbleSizes(String value)
```

NumberFormatOfBubbleSizes. Okunur/yazılır String.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |
### getMarker() {#getMarker--}
```
public final IMarker getMarker()
```

Marker. Yalnızca-okunur [IMarker](../../com.aspose.slides/imarker).

**Döndürür:**
[IMarker](../../com.aspose.slides/imarker)
### getBar3DShape() {#getBar3DShape--}
```
public final int getBar3DShape()
```

3-D çubuk grafiğinin bir serisinin şeklini belirtir. Bu özelliğin değerinin değiştirilmesi, serinin Tipini otomatik olarak değiştirebilir. Okunur/yazılır [ChartShapeType](../../com.aspose.slides/chartshapetype).

**Döndürür:**
int
### setBar3DShape(int value) {#setBar3DShape-int-}
```
public final void setBar3DShape(int value)
```

3-D çubuk grafiğinin bir serisinin şeklini belirtir. Bu özelliğin değerinin değiştirilmesi, serinin Tipini otomatik olarak değiştirebilir. Okunur/yazılır [ChartShapeType](../../com.aspose.slides/chartshapetype).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |
### getInvertIfNegative() {#getInvertIfNegative--}
```
public final boolean getInvertIfNegative()
```

Değer negatif ise çubuk, sütun veya balon serisinin renklerini tersine çevireceğini belirtir. Okunur/yazılır boolean.

**Döndürür:**
boolean
### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public final void setInvertIfNegative(boolean value)
```

Değer negatif ise çubuk, sütun veya balon serisinin renklerini tersine çevireceğini belirtir. Okunur/yazılır boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |
### getInvertedSolidFillColor() {#getInvertedSolidFillColor--}
```
public final IColorFormat getInvertedSolidFillColor()
```

Seri için ters katı rengi belirtir. Renk ayarını uygulamak için seri formatının FillType özelliğini FillType.Solid olarak ayarlayın. Okunur/yazılır [ColorFormat](../../com.aspose.slides/colorformat).

**Döndürür:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getAutomaticSeriesColor() {#getAutomaticSeriesColor--}
```
public final Integer getAutomaticSeriesColor()
```

Seri indeksine ve grafik stiline göre otomatik bir renk döndürür. Bu renk, FillType NotDefined olduğunda varsayılan olarak kullanılır.

**Döndürür:**
java.lang.Integer - The java.lang.Integer object.
### getShowInnerPoints() {#getShowInnerPoints--}
```
public final boolean getShowInnerPoints()
```

İç noktaları temsil eder. BoxAndWhisker grafiğinde iç noktalar gösteriliyorsa doğru. Sadece BoxAndWhisker grafiklerinde uygulanır. Okunur/yazılır boolean.

**Döndürür:**
boolean
### setShowInnerPoints(boolean value) {#setShowInnerPoints-boolean-}
```
public final void setShowInnerPoints(boolean value)
```

İç noktaları temsil eder. BoxAndWhisker grafiğinde iç noktalar gösteriliyorsa doğru. Sadece BoxAndWhisker grafiklerinde uygulanır. Okunur/yazılır boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |
### getShowOutlierPoints() {#getShowOutlierPoints--}
```
public final boolean getShowOutlierPoints()
```

Aykırı noktaları temsil eder. BoxAndWhisker grafiğinde aykırı noktalar gösteriliyorsa doğru. Sadece BoxAndWhisker grafiklerinde uygulanır. Okunur/yazılır boolean.

**Döndürür:**
boolean
### setShowOutlierPoints(boolean value) {#setShowOutlierPoints-boolean-}
```
public final void setShowOutlierPoints(boolean value)
```

Aykırı noktaları temsil eder. BoxAndWhisker grafiğinde aykırı noktalar gösteriliyorsa doğru. Sadece BoxAndWhisker grafiklerinde uygulanır. Okunur/yazılır boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |
### getShowMeanMarkers() {#getShowMeanMarkers--}
```
public final boolean getShowMeanMarkers()
```

Ortalama işaretleyicileri temsil eder. BoxAndWhisker grafiğinde ortalama işaretleyiciler gösteriliyorsa doğru. Sadece BoxAndWhisker grafiklerinde uygulanır. Okunur/yazılır boolean.

**Döndürür:**
boolean
### setShowMeanMarkers(boolean value) {#setShowMeanMarkers-boolean-}
```
public final void setShowMeanMarkers(boolean value)
```

Ortalama işaretleyicileri temsil eder. BoxAndWhisker grafiğinde ortalama işaretleyiciler gösteriliyorsa doğru. Sadece BoxAndWhisker grafiklerinde uygulanır. Okunur/yazılır boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |
### getShowMeanLine() {#getShowMeanLine--}
```
public final boolean getShowMeanLine()
```

Ortalama çizgiyi temsil eder. BoxAndWhisker grafiğinde ortalama çizgi gösteriliyorsa doğru. Sadece BoxAndWhisker grafiklerinde uygulanır. Okunur/yazılır boolean.

**Döndürür:**
boolean
### setShowMeanLine(boolean value) {#setShowMeanLine-boolean-}
```
public final void setShowMeanLine(boolean value)
```

Ortalama çizgiyi temsil eder. BoxAndWhisker grafiğinde ortalama çizgi gösteriliyorsa doğru. Sadece BoxAndWhisker grafiklerinde uygulanır. Okunur/yazılır boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |
### getQuartileMethod() {#getQuartileMethod--}
```
public final int getQuartileMethod()
```

Çeyrek yöntemini temsil eder. Sadece BoxAndWhisker grafiklerinde uygulanır.

**Döndürür:**
int
### setQuartileMethod(int value) {#setQuartileMethod-int-}
```
public final void setQuartileMethod(int value)
```

Çeyrek yöntemini temsil eder. Sadece BoxAndWhisker grafiklerinde uygulanır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |
### getShowConnectorLines() {#getShowConnectorLines--}
```
public final boolean getShowConnectorLines()
```

Bağlayıcı çizgileri temsil eder. Sadece Waterfall grafiklerinde uygulanır.

**Döndürür:**
boolean
### setShowConnectorLines(boolean value) {#setShowConnectorLines-boolean-}
```
public final void setShowConnectorLines(boolean value)
```

Bağlayıcı çizgileri temsil eder. Sadece Waterfall grafiklerinde uygulanır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |
### getParentLabelLayout() {#getParentLabelLayout--}
```
... 
```

Üst kategori etiketlerinin düzenini temsil eder. Sadece Treemap grafiklerinde uygulanır.

**Döndürür:**
int
### setParentLabelLayout(int value) {#setParentLabelLayout-int-}
```
public final void setParentLabelLayout(int value)
```

Üst kategori etiketlerinin düzenini temsil eder. Sadece Treemap grafiklerinde uygulanır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |
### hasUpDownBars() {#hasUpDownBars--}
```
public final boolean hasUpDownBars()
```

Çizgi veya Hisse grafiğinin yükseliş/aşağı düşüş çubuklarına sahip olup olmadığını belirler. Bu özellik yalnızca bu seri için değil, üst seri grubundaki tüm seriler için geçerlidir – ilgili grup özelliğinin bir yansımasıdır. Bu nedenle özellik yalnızca-okunur olur. Üst seri grubuna erişmek için ParentSeriesGroup özelliğini kullanın. Değeri değiştirmek için ParentSeriesGroup.UpDownBars.HasUpDownBars okunur/yazılır özelliğini kullanın. Up/Down çubuklarını biçimlendirmek için ParentSeriesGroup.UpDownBars özelliğini kullanın. Yalnızca-okunur boolean.

Bu, ParentSeriesGroup.UpDownBars.HasUpDownBars özelliğinin bir yansımasıdır.

**Döndürür:**
boolean
### getGapWidth() {#getGapWidth--}
```
public final int getGapWidth()
```

Çubuk veya sütun kümeleri arasındaki boşluğu, çubuk veya sütun genişliğinin yüzde olarak belirtir. Bu özellik yalnızca bu seri için değil, üst seri grubundaki tüm seriler için geçerlidir – ilgili grup özelliğinin bir yansımasıdır. Bu nedenle özellik yalnızca-okunur olur. Üst seri grubuna erişmek için ParentSeriesGroup özelliğini kullanın. Değeri değiştirmek için ParentSeriesGroup.GapWidth okunur/yazılır özelliğini kullanın. Yalnızca-okunur int.

Bu, ParentSeriesGroup.GapWidth özelliğinin bir yansımasıdır.

**Döndürür:**
int
### getGapDepth() {#getGapDepth--}
```
public final int getGapDepth()
```

3D grafikte veri serileri arasındaki mesafeyi, işaretleyici genişliğinin yüzde olarak döndürür veya ayarlar. Bu özellik yalnızca bu seri için değil, üst seri grubundaki tüm seriler için geçerlidir – ilgili grup özelliğinin bir yansımasıdır. Bu nedenle özellik yalnızca-okunur olur. Üst seri grubuna erişmek için ParentSeriesGroup özelliğini kullanın. Değeri değiştirmek için ParentSeriesGroup.GapDepth okunur/yazılır özelliğini kullanın. Yalnızca-okunur int.

Bu, ParentSeriesGroup.GapDepth özelliğinin bir yansımasıdır.

**Döndürür:**
int
### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public final int getFirstSliceAngle()
```

İlk pasta veya halka diliminin açısını derece olarak belirtir (yukarıdan saat yönünde, 0'dan 360 dereceye). Bu özellik yalnızca bu seri için değil, üst seri grubundaki tüm seriler için geçerlidir – ilgili grup özelliğinin bir yansımasıdır. Bu nedenle özellik yalnızca-okunur olur. Üst seri grubuna erişmek için ParentSeriesGroup özelliğini kullanın. Değeri değiştirmek için ParentSeriesGroup.FirstSliceAngle okunur/yazılır özelliğini kullanın. Yalnızca-okunur int.

Bu, ParentSeriesGroup.FirstSliceAngle özelliğinin bir yansımasıdır.

**Döndürür:**
int
### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public final byte getDoughnutHoleSize()
```

Halka grafiğindeki deliğin boyutunu belirtir (çizim alanının %10 ile %90 arasında olabilir). Bu özellik yalnızca bu seri için değil, üst seri grubundaki tüm seriler için geçerlidir – ilgili grup özelliğinin bir yansımasıdır. Bu nedenle özellik yalnızca-okunur olur. Üst seri grubuna erişmek için ParentSeriesGroup özelliğini kullanın. Değeri değiştirmek için ParentSeriesGroup.DoughnutHoleSize okunur/yazılır özelliğini kullanın. Yalnızca-okunur byte.

Bu, ParentSeriesGroup.DoughnutHoleSize özelliğinin bir yansımasıdır.

**Döndürür:**
byte
### getOverlap() {#getOverlap--}
```
public final byte getOverlap()
```

2D grafikleri üzerindeki çubuk ve sütunların ne kadar üst üste geleceğini yüzde olarak belirtir (-100% ile %100 arasında). Bu özellik yalnızca bu seri için değil, üst seri grubundaki tüm seriler için geçerlidir. İlgili grup özelliğinin bir yansımasıdır ve bu nedenle özellik yalnızca-okunur olur. Değeri değiştirmek için ParentSeriesGroup.Overlap okunur/yazılır özelliğini kullanın. Yalnızca-okunur byte.

Overlap, çubuk ve sütunların genişliklerinin yüzde olarak ne kadar üst üste geleceğini belirtir: -100%: En fazla boşluk (çubuklar tamamen ayrılmış). 0%: Çubuklar yan yana, üst üste gelmez veya boşluk yok. 100%: En fazla üst üste gelme (çubuklar tamamen üst üste). Bu, ParentSeriesGroup.Overlap özelliğinin bir yansımasıdır.

**Döndürür:**
byte
### getSecondPieSize() {#getSecondPieSize--}
```
public final int getSecondPieSize()
```

Pie-of-pie veya bar-of-pie grafiğinin ikinci pasta ya da çubuğunun boyutunu, ilk pastanın boyutunun yüzde olarak belirtir ( %5 ile %200 arasında). Bu özellik yalnızca bu seri için değil, üst seri grubundaki tüm seriler için geçerlidir – ilgili grup özelliğinin bir yansımasıdır. Bu nedenle özellik yalnızca-okunur olur. Üst seri grubuna erişmek için ParentSeriesGroup özelliğini kullanın. Değeri değiştirmek için ParentSeriesGroup.SecondPieSize okunur/yazılır özelliğini kullanın. Yalnızca-okunur int.

Bu, ParentSeriesGroup.SecondPieSize özelliğinin bir yansımasıdır.

**Döndürür:**
int
### hasSeriesLines() {#hasSeriesLines--}
```
public final boolean hasSeriesLines()
```

Bu seri ve yakın seriler için seri çizgileri olup olmadığını belirler. Bu özellik yalnızca bu seri için değil, üst seri grubundaki tüm seriler için geçerlidir – ilgili grup özelliğinin bir yansımasıdır. Bu nedenle özellik yalnızca-okunur olur. Üst seri grubuna erişmek için ParentSeriesGroup özelliğini kullanın. Değeri değiştirmek için ParentSeriesGroup.HasSeriesLines okunur/yazılır özelliğini kullanın. Seri çizgilerini biçimlendirmek için ParentSeriesGroup.SeriesLinesFormat özelliğini kullanın. Yalnızca-okunur boolean.

Bu, ParentSeriesGroup.HasSeriesLines özelliğinin bir yansımasıdır.

**Döndürür:**
boolean
### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public final int getBubbleSizeRepresentation()
```

Balon grafiğinde balon boyutu değerlerinin nasıl temsil edildiğini belirtir. Bu özellik yalnızca bu seri için değil, üst seri grubundaki tüm seriler için geçerlidir – ilgili grup özelliğinin bir yansımasıdır. Bu nedenle özellik yalnızca-okunur olur. Üst seri grubuna erişmek için ParentSeriesGroup özelliğini kullanın. Değeri değiştirmek için ParentSeriesGroup.BubbleSizeRepresentation okunur/yazılır özelliğini kullanın.

Bu, ParentSeriesGroup.BubbleSizeRepresentation özelliğinin bir yansımasıdır.

**Döndürür:**
int
### getPieSplitPosition() {#getPieSplitPosition--}
```
public final double getPieSplitPosition()
```

Pie-of-pie veya bar-of-pie grafiğinde ikinci pasta veya çubukta hangi veri noktalarının bulunacağını belirlemek için kullanılacak bir değer belirtir. PieSplitBy özelliğiyle birlikte kullanılır. Bu özellik yalnızca bu seri için değil, üst seri grubundaki tüm seriler için geçerlidir – ilgili grup özelliğinin bir yansımasıdır. Bu nedenle özellik yalnızca-okunur olur. Üst seri grubuna erişmek için ParentSeriesGroup özelliğini kullanın. Değeri değiştirmek için ParentSeriesGroup.PieSplitPosition okunur/yazılır özelliğini kullanın. Yalnızca-okunur double.

Bu, ParentSeriesGroup.PieSplitPosition özelliğinin bir yansımasıdır.

**Döndürür:**
double
### getPieSplitBy() {#getPieSplitBy--}
```
public final int getPieSplitBy()
```

Pie-of-pie veya bar-of-pie grafiğinde ikinci pasta veya çubukta hangi veri noktalarının bulunacağını belirleme yöntemini belirtir. Bu özellik yalnızca bu seri için değil, üst seri grubundaki tüm seriler için geçerlidir – ilgili grup özelliğinin bir yansımasıdır. Bu nedenle özellik yalnızca-okunur olur. Üst seri grubuna erişmek için ParentSeriesGroup özelliğini kullanın. Değeri değiştirmek için ParentSeriesGroup.PieSplitBy okunur/yazılır özelliğini kullanın. Yalnızca-okunur [PieSplitType](../../com.aspose.slides/piesplittype).

1) Bu, ParentSeriesGroup.PieSplitBy özelliğinin bir yansımasıdır. 2) Özellik değeri PieSplitType.Custom ise ParentSeriesGroup.PieSplitCustomPoints özelliğiyle özel bölme bilgisi tanımlanabilir.

**Döndürür:**
int
### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public final IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

Özel bölme bilgisi, özel bölme ile bir pie-of-pie veya bar-of-pie grafiği için. İkinci pasta veya çubukta çizilecek veri noktalarını içerir. Bu özellik yalnızca bu seri için değil, üst seri grubundaki tüm seriler için geçerlidir – ilgili grup özelliğinin bir yansımasıdır. Yalnızca-okunur [PieSplitCustomPointCollection](../../com.aspose.slides/piesplitcustompointcollection).

Bu, ParentSeriesGroup.PieSplitCustomPoints özelliğinin bir yansımasıdır.

**Döndürür:**
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)
### isColorVaried() {#isColorVaried--}
```
public final boolean isColorVaried()
```

Serideki her veri işaretleyicisinin farklı renge sahip olduğunu belirtir. Bu özellik yalnızca bu seri için değil, üst seri grubundaki tüm seriler için geçerlidir – ilgili grup özelliğinin bir yansımasıdır. Bu nedenle özellik yalnızca-okunur olur. Üst seri grubuna erişmek için ParentSeriesGroup özelliğini kullanın. Değeri değiştirmek için ParentSeriesGroup.IsColorVaried okunur/yazılır özelliğini kullanın. Yalnızca-okunur boolean.

Bu, ParentSeriesGroup.IsColorVaried özelliğinin bir yansımasıdır.

**Döndürür:**
boolean
### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public final int getBubbleSizeScale()
```

Balon grafiği için ölçek faktörünü belirtir (varsayılan boyutun %0 ile %300 arasında). Bu özellik yalnızca bu seri için değil, üst seri grubundaki tüm seriler için geçerlidir – ilgili grup özelliğinin bir yansımasıdır. Bu nedenle özellik yalnızca-okunur olur. Üst seri grubuna erişmek için ParentSeriesGroup özelliğini kullanın. Değeri değiştirmek için ParentSeriesGroup.BubbleSizeScale okunur/yazılır özelliğini kullanın.

Bu, ParentSeriesGroup.BubbleSizeScale özelliğinin bir yansımasıdır.

**Döndürür:**
int
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

FillFormat'un üst slaytını döndürür. Yalnızca-okunur [BaseSlide](../../com.aspose.slides/baseslide).

**Döndürür:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

FillFormat'un üst sunumunu döndürür. Yalnızca-okunur [IPresentation](../../com.aspose.slides/ipresentation).

**Döndürür:**
[IPresentation](../../com.aspose.slides/ipresentation)