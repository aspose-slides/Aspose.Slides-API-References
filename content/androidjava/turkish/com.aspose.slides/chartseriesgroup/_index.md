---
title: ChartSeriesGroup
second_title: Android için Aspose.Slides, Java API Referansı
description: Seri grubunu temsil eder.
type: docs
url: /tr/com.aspose.slides/chartseriesgroup/
---
**Kalıtım:**
java.lang.Object

**Uygulanan Tüm Arayüzler:**
[com.aspose.slides.IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup), com.aspose.slides.IDOMObject
```
public class ChartSeriesGroup implements IChartSeriesGroup, IDOMObject
```

Seri grubunu temsil eder.

--------------------

1) ChartSeriesGroupCollection sınıfı ve CombinableSeriesTypesGroup enum'ı için özet ve açıklamaları görün. 2) Seri grubu, grup içindeki her seri için ortak olan bazı seri özellikleri içerir ("seri grup özellikleri"). ChartSeriesGroup sınıfındaki "seri grup özellikleri" okunabilir/yazılabilir. Her bir "seri grup özellikleri", ChartSeries sınıfında yalnızca okuma projeksiyonuna sahip olabilir.

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getType()](#getType--) | Bu seri grubunun tipini döndürür. |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | Bu grubun serilerinin ikincil eksende çizilip çizilmediğini gösterir. |
| [getSeries()](#getSeries--) | Serilerin bir koleksiyonunu döndürür. |
| [get_Item(int index)](#get-Item-int-) | Belirtilen indeksteki öğeyi alır. |
| [getUpDownBars()](#getUpDownBars--) | Çizgi veya Hisse grafiğinin yukarı/aşağı çubuklarına erişim sağlar. |
| [getGapWidth()](#getGapWidth--) | Çubuk veya sütun kümeleri arasındaki boşluğu, çubuk veya sütun genişliğinin yüzdesi olarak belirtir. |
| [setGapWidth(int value)](#setGapWidth-int-) | Çubuk veya sütun kümeleri arasındaki boşluğu, çubuk veya sütun genişliğinin yüzdesi olarak belirtir. |
| [getGapDepth()](#getGapDepth--) | 3D grafikte veri serileri arasındaki mesafeyi, işaretçi genişliğinin yüzdesi olarak alır veya ayarlar. |
| [setGapDepth(int value)](#setGapDepth-int-) | 3D grafikte veri serileri arasındaki mesafeyi, işaretçi genişliğinin yüzdesi olarak alır veya ayarlar. |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | İlk pasta veya halka grafiği diliminin açısını derece cinsinden alır veya ayarlar (yukarıdan saat yönünde, 0 ile 360 derece arasında). |
| [setFirstSliceAngle(int value)](#setFirstSliceAngle-int-) | İlk pasta veya halka grafiği diliminin açısını derece cinsinden alır veya ayarlar (yukarıdan saat yönünde, 0 ile 360 derece arasında). |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | Halka grafiğindeki boşluğun boyutunu belirtir (çizim alanının %0 ile %90 arasında olabilir). |
| [setDoughnutHoleSize(byte value)](#setDoughnutHoleSize-byte-) | Halka grafiğindeki boşluğun boyutunu belirtir (çizim alanının %0 ile %90 arasında olabilir). |
| [getOverlap()](#getOverlap--) | 2D grafiklerde çubuk ve sütunların ne kadar üst üste geleceğini yüzde olarak belirtir (-%100 ile %100 arasında). |
| [setOverlap(byte value)](#setOverlap-byte-) | 2D grafiklerde çubuk ve sütunların ne kadar üst üste geleceğini yüzde olarak belirtir (-%100 ile %100 arasında). |
| [getSecondPieSize()](#getSecondPieSize--) | Pie-of-pie grafiği veya bar-of-pie grafiğinde ikinci pasta veya barın boyutunu, ilk pastanın boyutunun yüzde olarak belirtir (%5 ile %200 arasında). |
| [setSecondPieSize(int value)](#setSecondPieSize-int-) | Pie-of-pie grafiği veya bar-of-pie grafiğinde ikinci pasta veya barın boyutunu, ilk pastanın boyutunun yüzde olarak belirtir (%5 ile %200 arasında). |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | Baloncuk grafiğinde baloncuk boyutu değerlerinin nasıl temsil edildiğini belirtir. |
| [setBubbleSizeRepresentation(int value)](#setBubbleSizeRepresentation-int-) | Baloncuk grafiğinde baloncuk boyutu değerlerinin nasıl temsil edildiğini belirtir. |
| [getPieSplitPosition()](#getPieSplitPosition--) | Pie-of-pie veya bar-of-pie grafiğinde hangi veri noktalarının ikinci pasta veya bar içinde olacağını belirlemek için kullanılacak bir değeri belirtir. |
| [setPieSplitPosition(double value)](#setPieSplitPosition-double-) | Pie-of-pie veya bar-of-pie grafiğinde hangi veri noktalarının ikinci pasta veya bar içinde olacağını belirlemek için kullanılacak bir değeri belirtir. |
| [getPieSplitBy()](#getPieSplitBy--) | Pie-of-pie veya bar-of-pie grafiğinde hangi veri noktalarının ikinci pasta veya bar içinde olacağını belirleme yöntemini belirtir. |
| [setPieSplitBy(int value)](#setPieSplitBy-int-) | Pie-of-pie veya bar-of-pie grafiğinde hangi veri noktalarının ikinci pasta veya bar içinde olacağını belirleme yöntemini belirtir. |
| [isColorVaried()](#isColorVaried--) | Serideki her veri işaretçisinin farklı bir renge sahip olduğunu belirtir. |
| [setColorVaried(boolean value)](#setColorVaried-boolean-) | Serideki her veri işaretçisinin farklı bir renge sahip olduğunu belirtir. |
| [hasSeriesLines()](#hasSeriesLines--) | Grafikte seri çizgileri varsa doğru. |
| [setSeriesLines(boolean value)](#setSeriesLines-boolean-) | Grafikte seri çizgileri varsa doğru. |
| [getHiLowLinesFormat()](#getHiLowLinesFormat--) | HiLowLines biçimini belirtir. |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | Baloncuk grafiğinin ölçek faktörünü belirtir (varsayılan boyutun %0 ile %300 arasında olabilir). |
| [setBubbleSizeScale(int value)](#setBubbleSizeScale-int-) | Baloncuk grafiğinin ölçek faktörünü belirtir (varsayılan boyutun %0 ile %300 arasında olabilir). |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | Özel bölünmeye sahip bir pie-of-pie veya bar-of-pie grafiği için özel bölünme bilgisi. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getChart()](#getChart--) | Üst grafiği döndürür. |
| [getSlide()](#getSlide--) | Bir FillFormat'ın üst slaytını döndürür. |
| [getPresentation()](#getPresentation--) | Bir FillFormat'ın üst sunumunu döndürür. |

### getType() {#getType--}
```
public final int getType()
```

Bu seri grubunun tipini döndürür. Yalnızca okuma [CombinableSeriesTypesGroup](../../com.aspose.slides/combinableseriestypesgroup).

**Döndürür:**
int

### getPlotOnSecondAxis() {#getPlotOnSecondAxis--}
```
public final boolean getPlotOnSecondAxis()
```

Bu grubun serilerinin ikincil eksende çizilip çizilmediğini gösterir. Yalnızca okuma boolean.

**Döndürür:**
boolean

### getSeries() {#getSeries--}
```
public final IChartSeriesReadonlyCollection getSeries()
```

Serilerin bir koleksiyonunu döndürür. Yalnızca okuma [IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection).

**Döndürür:**
[IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection)

### get_Item(int index) {#get-Item-int-}
```
public final IChartSeries get_Item(int index)
```

Belirtilen indeksteki öğeyi alır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int |  |

**Döndürür:**
[IChartSeries](../../com.aspose.slides/ichartseries)

### getUpDownBars() {#getUpDownBars--}
```
public final IUpDownBarsManager getUpDownBars()
```

Çizgi veya Hisse grafiğinin yukarı/aşağı çubuklarına erişim sağlar. Yalnızca okuma [IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager).

**Döndürür:**
[IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager)

### getGapWidth() {#getGapWidth--}
```
public final int getGapWidth()
```

Çubuk veya sütun kümeleri arasındaki boşluğu, çubuk veya sütun genişliğinin yüzdesi olarak belirtir. Okunabilir/yazılabilir int.

**Döndürür:**
int

### setGapWidth(int value) {#setGapWidth-int-}
```
public final void setGapWidth(int value)
```

Çubuk veya sütun kümeleri arasındaki boşluğu, çubuk veya sütun genişliğinin yüzdesi olarak belirtir. Okunabilir/yazılabilir int.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getGapDepth() {#getGapDepth--}
```
public final int getGapDepth()
```

3D grafikte veri serileri arasındaki mesafeyi, işaretçi genişliğinin yüzdesi olarak alır veya ayarlar. Okunabilir/yazılabilir int.

**Döndürür:**
int

### setGapDepth(int value) {#setGapDepth-int-}
```
public final void setGapDepth(int value)
```

3D grafikte veri serileri arasındaki mesafeyi, işaretçi genişliğinin yüzdesi olarak alır veya ayarlar. Okunabilir/yazılabilir int.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public final int getFirstSliceAngle()
```

İlk pasta veya halka grafiği diliminin açısını derece cinsinden alır veya ayarlar (yukarıdan saat yönünde, 0 ile 360 derece arasında). Okunabilir/yazılabilir int.

**Döndürür:**
int

### setFirstSliceAngle(int value) {#setFirstSliceAngle-int-}
```
public final void setFirstSliceAngle(int value)
```

İlk pasta veya halka grafiği diliminin açısını derece cinsinden alır veya ayarlar (yukarıdan saat yönünde, 0 ile 360 derece arasında). Okunabilir/yazılabilir int.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public final byte getDoughnutHoleSize()
```

Halka grafiğindeki boşluğun boyutunu belirtir (çizim alanının %0 ile %90 arasında olabilir). Okunabilir/yazılabilir byte.

**Döndürür:**
byte

### setDoughnutHoleSize(byte value) {#setDoughnutHoleSize-byte-}
```
public final void setDoughnutHoleSize(byte value)
```

Halka grafiğindeki boşluğun boyutunu belirtir (çizim alanının %0 ile %90 arasında olabilir). Okunabilir/yazılabilir byte.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |

### getOverlap() {#getOverlap--}
```
public final byte getOverlap()
```

2D grafiklerde çubuk ve sütunların ne kadar üst üste geleceğini yüzde olarak belirtir (-%100 ile %100 arasında). -%100: En fazla boşluk (çubuklar tamamen ayrılır). -0%: Çubuklar üst üste gelmeden yan yana yer alır. -%100: En fazla üst üste binme (çubuklar tamamen üst üste biner). Bu özellik okunabilir/yazılabilir byte.

--------------------

> ```
> The following example demonstrates how to set the overlap for a chart series group 
>   and render the resulting chart on a form:
>   
>  Presentation pres = new Presentation();
>  try {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.ClusteredColumn, 10, 10, 600, 300);
>      IChartSeriesCollection series = chart.getChartData().getSeries();
>      series.get_Item(0).getParentSeriesGroup().setOverlap((byte)55); // Üst üste binme oranını %55 olarak ayarla
>      pres.getSlides().get_Item(0).getImage(1, 1).save("chart.png", ImageFormat.Png);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Döndürür:**
byte

### setOverlap(byte value) {#setOverlap-byte-}
```
public final void setOverlap(byte value)
```

2D grafiklerde çubuk ve sütunların ne kadar üst üste geleceğini yüzde olarak belirtir (-%100 ile %100 arasında). -%100: En fazla boşluk (çubuklar tamamen ayrılır). -0%: Çubuklar üst üste gelmeden yan yana yer alır. -%100: En fazla üst üste binme (çubuklar tamamen üst üste biner). Bu özellik okunabilir/yazılabilir byte.

--------------------

> ```
> The following example demonstrates how to set the overlap for a chart series group 
>   and render the resulting chart on a form:
>   
>  Presentation pres = new Presentation();
>  try {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.ClusteredColumn, 10, 10, 600, 300);
>      IChartSeriesCollection series = chart.getChartData().getSeries();
>      series.get_Item(0).getParentSeriesGroup().setOverlap((byte)55); // Üst üste binme oranını %55 olarak ayarla
>      pres.getSlides().get_Item(0).getImage(1, 1).save("chart.png", ImageFormat.Png);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |

### getSecondPieSize() {#getSecondPieSize--}
```
public final int getSecondPieSize()
```

Pie-of-pie grafiği veya bar-of-pie grafiğinde ikinci pasta veya barın boyutunu, ilk pastanın boyutunun yüzde olarak belirtir (%5 ile %200 arasında). Okunabilir/yazılabilir int.

**Döndürür:**
int

### setSecondPieSize(int value) {#setSecondPieSize-int-}
```
public final void setSecondPieSize(int value)
```

Pie-of-pie grafiği veya bar-of-pie grafiğinde ikinci pasta veya barın boyutunu, ilk pastanın boyutunun yüzde olarak belirtir (%5 ile %200 arasında). Okunabilir/yazılabilir int.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public final int getBubbleSizeRepresentation()
```

Baloncuk grafiğinde baloncuk boyutu değerlerinin nasıl temsil edildiğini belirtir. Okunabilir/yazılabilir [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**Döndürür:**
int

### setBubbleSizeRepresentation(int value) {#setBubbleSizeRepresentation-int-}
```
public final void setBubbleSizeRepresentation(int value)
```

Baloncuk grafiğinde baloncuk boyutu değerlerinin nasıl temsil edildiğini belirtir. Okunabilir/yazılabilir [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getPieSplitPosition() {#getPieSplitPosition--}
```
public final double getPieSplitPosition()
```

Pie-of-pie veya bar-of-pie grafiğinde ikinci pasta veya bar içinde hangi veri noktalarının yer alacağını belirlemek için kullanılacak bir değeri belirtir. PieSplitBy özelliğiyle birlikte kullanılır. Okunabilir/yazılabilir double.

**Döndürür:**
double

### setPieSplitPosition(double value) {#setPieSplitPosition-double-}
```
public final void setPieSplitPosition(double value)
```

Pie-of-pie veya bar-of-pie grafiğinde ikinci pasta veya bar içinde hangi veri noktalarının yer alacağını belirlemek için kullanılacak bir değeri belirtir. PieSplitBy özelliğiyle birlikte kullanılır. Okunabilir/yazılabilir double.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | double |  |

### getPieSplitBy() {#getPieSplitBy--}
```
public final int getPieSplitBy()
```

Pie-of-pie veya bar-of-pie grafiğinde ikinci pasta veya bar içinde hangi veri noktalarının yer alacağını belirleme yöntemini belirtir. Okunabilir/yazılabilir [PieSplitType](../../com.aspose.slides/piesplittype).

**Döndürür:**
int

### setPieSplitBy(int value) {#setPieSplitBy-int-}
```
public final void setPieSplitBy(int value)
```

Pie-of-pie veya bar-of-pie grafiğinde ikinci pasta veya bar içinde hangi veri noktalarının yer alacağını belirleme yöntemini belirtir. Okunabilir/yazılabilir [PieSplitType](../../com.aspose.slides/piesplittype).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### isColorVaried() {#isColorVaried--}
```
public final boolean isColorVaried()
```

Serideki her veri işaretçisinin farklı bir renge sahip olduğunu belirtir. Okunabilir/yazılabilir boolean.

**Döndürür:**
boolean

### setColorVaried(boolean value) {#setColorVaried-boolean-}
```
public final void setColorVaried(boolean value)
```

Serideki her veri işaretçisinin farklı bir renge sahip olduğunu belirtir. Okunabilir/yazılabilir boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### hasSeriesLines() {#hasSeriesLines--}
```
public final boolean hasSeriesLines()
```

Grafikte seri çizgileri varsa doğru. Yığılmış çubuk ve OfPie grafiklerine uygulanır. Okunabilir/yazılabilir boolean.

**Döndürür:**
boolean

### setSeriesLines(boolean value) {#setSeriesLines-boolean-}
```
public final void setSeriesLines(boolean value)
```

Grafikte seri çizgileri varsa doğru. Yığılmış çubuk ve OfPie grafiklerine uygulanır. Okunabilir/yazılabilir boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getHiLowLinesFormat() {#getHiLowLinesFormat--}
```
public final IChartLinesFormat getHiLowLinesFormat()
```

HiLowLines biçimini belirtir. HiLowLines, HiLowClose, OpenHiLowClose, VolumeHiLowClose ve VolumeOpenHiLowClose grafik tipleriyle uygulanır.

**Döndürür:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)

### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public final int getBubbleSizeScale()
```

Baloncuk grafiğinin ölçek faktörünü belirtir (varsayılan boyutun %0 ile %300 arasında olabilir). Okunabilir/yazılabilir int.

**Döndürür:**
int

### setBubbleSizeScale(int value) {#setBubbleSizeScale-int-}
```
public final void setBubbleSizeScale(int value)
```

Baloncuk grafiğinin ölçek faktörünü belirtir (varsayılan boyutun %0 ile %300 arasında olabilir). Okunabilir/yazılabilir int.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public final IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

Özel bölünmeye sahip bir pie-of-pie veya bar-of-pie grafiği için özel bölünme bilgisi. İkinci pasta veya bar içinde çizilecek veri noktalarını içerir. Yalnızca okuma [PieSplitCustomPointCollection](../../com.aspose.slides/piesplitcustompointcollection).

**Döndürür:**
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate nesnesini döndürür. Yalnızca okuma IDOMObject.

**Döndürür:**
com.aspose.slides.IDOMObject

### getChart() {#getChart--}
```
public final IChart getChart()
```

Üst grafiği döndürür. Yalnızca okuma [IChart](../../com.aspose.slides/ichart).

**Döndürür:**
[IChart](../../com.aspose.slides/ichart)

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Bir FillFormat'ın üst slaytını döndürür. Yalnızca okuma [BaseSlide](../../com.aspose.slides/baseslide).

**Döndürür:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Bir FillFormat'ın üst sunumunu döndürür. Yalnızca okuma [IPresentation](../../com.aspose.slides/ipresentation).

**Döndürür:**
[IPresentation](../../com.aspose.slides/ipresentation)