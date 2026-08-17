---
title: ChartSeriesGroup
second_title: Aspose.Slides for Java API Referansı
description: Serilerin bir grubunu temsil eder.
type: docs
url: /tr/com.aspose.slides/chartseriesgroup/
---
**Kalıtım:**
java.lang.Object

**Tüm Uygulanan Arabirimler:**
[com.aspose.slides.IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup), com.aspose.slides.IDOMObject
```
public class ChartSeriesGroup implements IChartSeriesGroup, IDOMObject
```

Seri grubunu temsil eder.

--------------------

1) ChartSeriesGroupCollection sınıfı ve CombinableSeriesTypesGroup enum'ı için özeti ve açıklamaları inceleyin. 2) Seri grubu, gruptaki her seri için ortak olan bazı seri özelliklerini içerir ("series group properties"). ChartSeriesGroup sınıfındaki "Series group properties" okuma/yazma özelliktedir. "Series group properties" öğelerinin her biri, ChartSeries sınıfında yalnızca okuma projeksiyonuna sahip olabilir.
## Metotlar

| Metod | Açıklama |
| --- | --- |
| [getType()](#getType--) | Bu seri grubunun tipini döndürür. |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | Bu grubun serilerinin ikincil eksende çizilip çizilmediğini gösterir. |
| [getSeries()](#getSeries--) | Seri koleksiyonunu döndürür. |
| [get_Item(int index)](#get-Item-int-) | Belirtilen indeksteki öğeyi alır. |
| [getUpDownBars()](#getUpDownBars--) | Line ya da Stock grafiğinin yükseliş/düşüş çubuklarına erişim sağlar. |
| [getGapWidth()](#getGapWidth--) | Çubuk veya sütun kümeleri arasındaki boşluğu, çubuk veya sütun genişliğinin yüzdesi olarak belirtir. |
| [setGapWidth(int value)](#setGapWidth-int-) | Çubuk veya sütun kümeleri arasındaki boşluğu, çubuk veya sütun genişliğinin yüzdesi olarak belirtir. |
| [getGapDepth()](#getGapDepth--) | 3D grafikte veri serileri arasındaki mesafeyi, işaretçi genişliğinin yüzdesi olarak döndürür veya ayarlar. |
| [setGapDepth(int value)](#setGapDepth-int-) | 3D grafikte veri serileri arasındaki mesafeyi, işaretçi genişliğinin yüzdesi olarak döndürür veya ayarlar. |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | İlk pasta veya halka grafiği diliminin açısını derece cinsinden alır veya ayarlar (yukarıdan saat yönünde, 0'dan 360 dereceye). |
| [setFirstSliceAngle(int value)](#setFirstSliceAngle-int-) | İlk pasta veya halka grafiği diliminin açısını derece cinsinden alır veya ayarlar (yukarıdan saat yönünde, 0'dan 360 dereceye). |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | Halka grafiğindeki deliğin boyutunu belirtir (çizim alanının boyutunun %0 ile %90 arasında olabilir). |
| [setDoughnutHoleSize(byte value)](#setDoughnutHoleSize-byte-) | Halka grafiğindeki deliğin boyutunu belirtir (çizim alanının boyutunun %0 ile %90 arasında olabilir). |
| [getOverlap()](#getOverlap--) | 2D grafiklerde çubuk ve sütunların ne kadar üst üste geleceğini yüzde olarak belirler (%-100 ile %100 arasında). |
| [setOverlap(byte value)](#setOverlap-byte-) | 2D grafiklerde çubuk ve sütunların ne kadar üst üste geleceğini yüzde olarak belirler (%-100 ile %100 arasında). |
| [getSecondPieSize()](#getSecondPieSize--) | Pie-of-pie veya bar-of-pie grafiğinde ikinci pasta ya da çubuğun boyutunu, ilk pastanın boyutunun yüzdesi olarak belirtir (%5 ile %200 arasında olabilir). |
| [setSecondPieSize(int value)](#setSecondPieSize-int-) | Pie-of-pie veya bar-of-pie grafiğinde ikinci pasta ya da çubuğun boyutunu, ilk pastanın boyutunun yüzdesi olarak belirtir (%5 ile %200 arasında olabilir). |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | Baloncuk grafikindeki baloncuk boyutu değerlerinin nasıl temsil edileceğini belirtir. |
| [setBubbleSizeRepresentation(int value)](#setBubbleSizeRepresentation-int-) | Baloncuk grafikindeki baloncuk boyutu değerlerinin nasıl temsil edileceğini belirtir. |
| [getPieSplitPosition()](#getPieSplitPosition--) | Pie-of-pie veya bar-of-pie grafiğinde ikinci pasta ya da çubuğa hangi veri noktalarının dahil edileceğini belirlemek için kullanılacak bir değeri belirtir. |
| [setPieSplitPosition(double value)](#setPieSplitPosition-double-) | Pie-of-pie veya bar-of-pie grafiğinde ikinci pasta ya da çubuğa hangi veri noktalarının dahil edileceğini belirlemek için kullanılacak bir değeri belirtir. |
| [getPieSplitBy()](#getPieSplitBy--) | Pie-of-pie ya da bar-of-pie grafiğinde ikinci pasta ya da çubuğa hangi veri noktalarının dahil edileceğini belirleme yöntemini belirtir. |
| [setPieSplitBy(int value)](#setPieSplitBy-int-) | Pie-of-pie ya da bar-of-pie grafiğinde ikinci pasta ya da çubuğa hangi veri noktalarının dahil edileceğini belirleme yöntemini belirtir. |
| [isColorVaried()](#isColorVaried--) | Serideki her veri işaretçisinin farklı bir renge sahip olduğunu belirtir. |
| [setColorVaried(boolean value)](#setColorVaried-boolean-) | Serideki her veri işaretçisinin farklı bir renge sahip olduğunu belirtir. |
| [hasSeriesLines()](#hasSeriesLines--) | Grafiğin seri çizgileri varsa true döner. |
| [setSeriesLines(boolean value)](#setSeriesLines-boolean-) | Grafiğin seri çizgileri varsa true döner. |
| [getHiLowLinesFormat()](#getHiLowLinesFormat--) | HiLowLines biçimini belirtir. |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | Baloncuk grafiği için ölçek çarpanını belirtir (varsayılan boyutun %0 ile %300 arasında olabilir). |
| [setBubbleSizeScale(int value)](#setBubbleSizeScale-int-) | Baloncuk grafiği için ölçek çarpanını belirtir (varsayılan boyutun %0 ile %300 arasında olabilir). |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | Özel bölünmeye sahip bir pie-of-pie veya bar-of-pie grafiği için özel bölünme bilgisini içerir. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getChart()](#getChart--) | Üst grafiği döndürür. |
| [getSlide()](#getSlide--) | FillFormat nesnesinin üst slaytını döndürür. |
| [getPresentation()](#getPresentation--) | FillFormat nesnesinin üst sunumunu döndürür. |

### getType() {#getType--}
```
public final int getType()
```

Döndürür:  
int  
Bu seri grubunun tipini döndürür. Yalnızca okuma [CombinableSeriesTypesGroup](../../com.aspose.slides/combinableseriestypesgroup).

### getPlotOnSecondAxis() {#getPlotOnSecondAxis--}
```
public final boolean getPlotOnSecondAxis()
```

Döndürür:  
boolean  
Bu grubun serilerinin ikincil eksende çizilip çizilmediğini gösterir. Yalnızca okuma boolean.

### getSeries() {#getSeries--}
```
public final IChartSeriesReadonlyCollection getSeries()
```

Döndürür:  
[IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection)  
Seri koleksiyonunu döndürür. Yalnızca okuma [IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection).

### get_Item(int index) {#get-Item-int-}
```
public final IChartSeries get_Item(int index)
```

Döndürür:  
[IChartSeries](../../com.aspose.slides/ichartseries)  
Belirtilen indeksteki öğeyi alır.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

### getUpDownBars() {#getUpDownBars--}
```
public final IUpDownBarsManager getUpDownBars()
```

Döndürür:  
[IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager)  
Line ya da Stock grafiğinin yükseliş/düşüş çubuklarına erişim sağlar. Yalnızca okuma [IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager).

### getGapWidth() {#getGapWidth--}
```
public final int getGapWidth()
```

Döndürür:  
int  
Çubuk veya sütun kümeleri arasındaki boşluğu, çubuk veya sütun genişliğinin yüzdesi olarak belirtir. Okuma/yazma int.

### setGapWidth(int value) {#setGapWidth-int-}
```
public final void setGapWidth(int value)
```

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

Çubuk veya sütun kümeleri arasındaki boşluğu, çubuk veya sütun genişliğinin yüzdesi olarak belirtir. Okuma/yazma int.

### getGapDepth() {#getGapDepth--}
```
public final int getGapDepth()
```

Döndürür:  
int  
3D grafikte veri serileri arasındaki mesafeyi, işaretçi genişliğinin yüzdesi olarak döndürür veya ayarlar. Okuma/yazma int.

### setGapDepth(int value) {#setGapDepth-int-}
```
public final void setGapDepth(int value)
```

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

3D grafikte veri serileri arasındaki mesafeyi, işaretçi genişliğinin yüzdesi olarak döndürür veya ayarlar. Okuma/yazma int.

### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public final int getFirstSliceAngle()
```

Döndürür:  
int  
İlk pasta veya halka grafiği diliminin açısını derece cinsinden alır veya ayarlar (yukarıdan saat yönünde, 0'dan 360 dereceye). Okuma/yazma int.

### setFirstSliceAngle(int value) {#setFirstSliceAngle-int-}
```
public final void setFirstSliceAngle(int value)
```

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

İlk pasta veya halka grafiği diliminin açısını derece cinsinden alır veya ayarlar (yukarıdan saat yönünde, 0'dan 360 dereceye). Okuma/yazma int.

### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public final byte getDoughnutHoleSize()
```

Döndürür:  
byte  
Halka grafiğindeki deliğin boyutunu belirtir (çizim alanının boyutunun %0 ile %90 arasında olabilir). Okuma/yazma byte.

### setDoughnutHoleSize(byte value) {#setDoughnutHoleSize-byte-}
```
public final void setDoughnutHoleSize(byte value)
```

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

Halka grafiğindeki deliğin boyutunu belirtir (çizim alanının boyutunun %0 ile %90 arasında olabilir). Okuma/yazma byte.

### getOverlap() {#getOverlap--}
```
public final byte getOverlap()
```

Döndürür:  
byte  
2D grafiklerde çubuk ve sütunların ne kadar üst üste geleceğini yüzde olarak belirler (%-100 ile %100 arasında). - -100%: Azami boşluk (çubuklar tamamen ayrılmış). - 0%: Çubuklar yan yana, üst üste gelme ya da boşluk olmadan yerleştirilir. - 100%: Azami üst üste gelme (çubuklar tamamen birbirinin üzerine gelir). Bu özellik Okuma/yazma byte.

> ```
> The following example demonstrates how to set the overlap for a chart series group 
>   and render the resulting chart on a form:
>   
>  Presentation pres = new Presentation();
>  try {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.ClusteredColumn, 10, 10, 600, 300);
>      IChartSeriesCollection series = chart.getChartData().getSeries();
>      series.get_Item(0).getParentSeriesGroup().setOverlap((byte)55); // Örtüşmeyi %55 olarak ayarla
>      pres.getSlides().get_Item(0).getImage(1, 1).save("chart.png", ImageFormat.Png);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
```

Döndürür:  
byte  

### setOverlap(byte value) {#setOverlap-byte-}
```
public final void setOverlap(byte value)
```

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

2D grafiklerde çubuk ve sütunların ne kadar üst üste geleceğini yüzde olarak belirler (%-100 ile %100 arasında). - -100%: Azami boşluk (çubuklar tamamen ayrılmış). - 0%: Çubuklar yan yana, üst üste gelme ya da boşluk olmadan yerleştirilir. - 100%: Azami üst üste gelme (çubuklar tamamen birbirinin üzerine gelir). Bu özellik Okuma/yazma byte.

> ```
> The following example demonstrates how to set the overlap for a chart series group 
>   and render the resulting chart on a form:
>   
>  Presentation pres = new Presentation();
>  try {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.ClusteredColumn, 10, 10, 600, 300);
>      IChartSeriesCollection series = chart.getChartData().getSeries();
>      series.get_Item(0).getParentSeriesGroup().setOverlap((byte)55); // Örtüşmeyi %55 olarak ayarla
>      pres.getSlides().get_Item(0).getImage(1, 1).save("chart.png", ImageFormat.Png);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getSecondPieSize() {#getSecondPieSize--}
```
public final int getSecondPieSize()
```

Döndürür:  
int  
İkinci pasta ya da barın boyutunu, ilk pastanın boyutunun yüzdesi olarak belirtir (%5 ile %200 arasında olabilir). Okuma/yazma int.

### setSecondPieSize(int value) {#setSecondPieSize-int-}
```
public final void setSecondPieSize(int value)
```

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

İkinci pasta ya da barın boyutunu, ilk pastanın boyutunun yüzdesi olarak belirtir (%5 ile %200 arasında olabilir). Okuma/yazma int.

### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public final int getBubbleSizeRepresentation()
```

Döndürür:  
int  
Baloncuk grafikindeki baloncuk boyutu değerlerinin nasıl temsil edileceğini belirtir. Okuma/yazma [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

### setBubbleSizeRepresentation(int value) {#setBubbleSizeRepresentation-int-}
```
public final void setBubbleSizeRepresentation(int value)
```

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

Baloncuk grafikindeki baloncuk boyutu değerlerinin nasıl temsil edileceğini belirtir. Okuma/yazma [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

### getPieSplitPosition() {#getPieSplitPosition--}
```
public final double getPieSplitPosition()
```

Döndürür:  
double  
Pie-of-pie veya bar-of-pie grafiğinde ikinci pasta ya da çubuğa hangi veri noktalarının dahil edileceğini belirlemek için kullanılacak bir değeri belirtir. PieSplitBy özelliğiyle birlikte kullanılır. Okuma/yazma double.

### setPieSplitPosition(double value) {#setPieSplitPosition-double-}
```
public final void setPieSplitPosition(double value)
```

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

Pie-of-pie veya bar-of-pie grafiğinde ikinci pasta ya da çubuğa hangi veri noktalarının dahil edileceğini belirlemek için kullanılacak bir değeri belirtir. PieSplitBy özelliğiyle birlikte kullanılır. Okuma/yazma double.

### getPieSplitBy() {#getPieSplitBy--}
```
public final int getPieSplitBy()
```

Döndürür:  
int  
Pie-of-pie ya da bar-of-pie grafiğinde ikinci pasta ya da çubuğa hangi veri noktalarının dahil edileceğini belirleme yöntemini belirtir. Okuma/yazma [PieSplitType](../../com.aspose.slides/piesplittype).

### setPieSplitBy(int value) {#setPieSplitBy-int-}
```
public final void setPieSplitBy(int value)
```

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

Pie-of-pie ya da bar-of-pie grafiğinde ikinci pasta ya da çubuğa hangi veri noktalarının dahil edileceğini belirleme yöntemini belirtir. Okuma/yazma [PieSplitType](../../com.aspose.slides/piesplittype).

### isColorVaried() {#isColorVaried--}
```
public final boolean isColorVaried()
```

Döndürür:  
boolean  
Serideki her veri işaretçisinin farklı bir renge sahip olduğunu belirtir. Okuma/yazma boolean.

### setColorVaried(boolean value) {#setColorVaried-boolean-}
```
public final void setColorVaried(boolean value)
```

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

Serideki her veri işaretçisinin farklı bir renge sahip olduğunu belirtir. Okuma/yazma boolean.

### hasSeriesLines() {#hasSeriesLines--}
```
public final boolean hasSeriesLines()
```

Döndürür:  
boolean  
Grafiğin seri çizgileri varsa true döner. Yığılmış çubuk ve OfPie grafiklerinde uygulanır. Okuma/yazma boolean.

### setSeriesLines(boolean value) {#setSeriesLines-boolean-}
```
public final void setSeriesLines(boolean value)
```

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

Grafiğin seri çizgileri varsa true döner. Yığılmış çubuk ve OfPie grafiklerinde uygulanır. Okuma/yazma boolean.

### getHiLowLinesFormat() {#getHiLowLinesFormat--}
```
public final IChartLinesFormat getHiLowLinesFormat()
```

Döndürür:  
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)  
HiLowLines biçimini belirtir. HiLowLines, HiLowClose, OpenHiLowClose, VolumeHiLowClose ve VolumeOpenHiLowClose grafik tipleriyle kullanılır.

### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public final int getBubbleSizeScale()
```

Döndürür:  
int  
Baloncuk grafiği için ölçek çarpanını belirtir (varsayılan boyutun %0 ile %300 arasında olabilir). Okuma/yazma int.

### setBubbleSizeScale(int value) {#setBubbleSizeScale-int-}
```
public final void setBubbleSizeScale(int value)
```

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

Baloncuk grafiği için ölçek çarpanını belirtir (varsayılan boyutun %0 ile %300 arasında olabilir). Okuma/yazma int.

### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public final IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

Döndürür:  
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)  
Özel bölünmeye sahip bir pie-of-pie veya bar-of-pie grafiği için özel bölünme bilgisini içerir. Pie-of-pie veya bar-of-pie grafiğinde ikinci pasta ya da çubukta çizilecek veri noktalarını içerir. Yalnızca okuma [PieSplitCustomPointCollection](../../com.aspose.slides/piesplitcustompointcollection).

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Döndürür:  
com.aspose.slides.IDOMObject  
Parent_Immediate nesnesini döndürür. Yalnızca okuma IDOMObject.

### getChart() {#getChart--}
```
public final IChart getChart()
```

Döndürür:  
[IChart](../../com.aspose.slides/ichart)  
Üst grafiği döndürür. Yalnızca okuma [IChart](../../com.aspose.slides/ichart).

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Döndürür:  
[IBaseSlide](../../com.aspose.slides/ibaseslide)  
FillFormat nesnesinin üst slaytını döndürür. Yalnızca okuma [BaseSlide](../../com.aspose.slides/baseslide).

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Döndürür:  
[IPresentation](../../com.aspose.slides/ipresentation)  
FillFormat nesnesinin üst sunumunu döndürür. Yalnızca okuma [IPresentation](../../com.aspose.slides/ipresentation).