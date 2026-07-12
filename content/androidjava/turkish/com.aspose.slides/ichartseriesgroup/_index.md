---
title: IChartSeriesGroup
second_title: Aspose.Slides for Android Java API Referansı
description: Seri grubunu temsil eder.
type: docs
url: /tr/com.aspose.slides/ichartseriesgroup/
---
**Uygulanan Tüm Arabirimler:**
[com.aspose.slides.IChartComponent](../../com.aspose.slides/ichartcomponent)
```
public interface IChartSeriesGroup extends IChartComponent
```

Seri grubunu temsil eder.

--------------------

1) ChartSeriesGroupCollection sınıfı ve CombinableSeriesTypesGroup enum'ı için özet ve açıklamaları inceleyin. 2) Seri grubu, grup içindeki her seri için ortak olan bazı seri özelliklerini ("seri grup özellikleri") içerir. "Series group properties" in ChartSeriesGroup class is read/write. Each of "series group properties" can have a read-only projection in ChartSeries class.

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getType()](#getType--) | Bu seri grubunun tipini döndürür. |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | Bu grubun serilerinin ikincil eksende çizilip çizilmediğini gösterir. |
| [getSeries()](#getSeries--) | Okunabilir bir grafik serileri koleksiyonunu döndürür. |
| [get_Item(int index)](#get-Item-int-) | Belirtilen indeksteki öğeyi alır. |
| [getUpDownBars()](#getUpDownBars--) | Çizgi veya Stok grafiğinin yukarı/aşağı çubuklarına erişim sağlar. |
| [getGapWidth()](#getGapWidth--) | Çubuk veya sütun küme arası boşluğu, çubuk veya sütun genişliğinin yüzde olarak belirler. |
| [setGapWidth(int value)](#setGapWidth-int-) | Çubuk veya sütun küme arası boşluğu, çubuk veya sütun genişliğinin yüzde olarak belirler. |
| [getGapDepth()](#getGapDepth--) | 3D grafikte veri serileri arasındaki mesafeyi, işaretçi genişliğinin yüzde olarak döndürür veya ayarlar. |
| [setGapDepth(int value)](#setGapDepth-int-) | 3D grafikte veri serileri arasındaki mesafeyi, işaretçi genişliğinin yüzde olarak döndürür veya ayarlar. |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | İlk pasta veya halka grafiği diliminin açısını derece cinsinden alır veya ayarlar (yukarıdan saat yönünde, 0'dan 360 dereceye). |
| [setFirstSliceAngle(int value)](#setFirstSliceAngle-int-) | İlk pasta veya halka grafiği diliminin açısını derece cinsinden alır veya ayarlar (yukarıdan saat yönünde, 0'dan 360 dereceye). |
| [isColorVaried()](#isColorVaried--) | Serideki her veri işaretçisinin farklı bir renge sahip olmasını belirtir. |
| [setColorVaried(boolean value)](#setColorVaried-boolean-) | Serideki her veri işaretçisinin farklı bir renge sahip olmasını belirtir. |
| [hasSeriesLines()](#hasSeriesLines--) | Grafik seri çizgilerine sahipse doğru. |
| [setSeriesLines(boolean value)](#setSeriesLines-boolean-) | Grafik seri çizgilerine sahipse doğru. |
| [getOverlap()](#getOverlap--) | 2D grafiklerde çubuk ve sütunların ne kadar üst üste geleceğini yüzde olarak belirler (-%100'ten %100'e). |
| [setOverlap(byte value)](#setOverlap-byte-) | 2D grafiklerde çubuk ve sütunların ne kadar üst üste geleceğini yüzde olarak belirler (-%100'ten %100'e). |
| [getSecondPieSize()](#getSecondPieSize--) | Pasta-üzerine-pasta veya çubuk-üzerine-pasta grafiğinde ikinci pasta veya çubuğun boyutunu, ilk pastanın boyutunun yüzde olarak belirler (5 ile 200 arasında olabilir). |
| [setSecondPieSize(int value)](#setSecondPieSize-int-) | Pasta-üzerine-pasta veya çubuk-üzerine-pasta grafiğinde ikinci pasta veya çubuğun boyutunu, ilk pastanın boyutunun yüzde olarak belirler (5 ile 200 arasında olabilir). |
| [getPieSplitPosition()](#getPieSplitPosition--) | Pasta-üzerine-pasta veya çubuk-üzerine-pasta grafiğinde ikinci pasta veya çubuğa hangi veri noktalarının gireceğini belirlemek için kullanılacak bir değeri belirtir. |
| [setPieSplitPosition(double value)](#setPieSplitPosition-double-) | Pasta-üzerine-pasta veya çubuk-üzerine-pasta grafiğinde ikinci pasta veya çubuğa hangi veri noktalarının gireceğini belirlemek için kullanılacak bir değeri belirtir. |
| [getPieSplitBy()](#getPieSplitBy--) | Pasta-üzerine-pasta veya çubuk-üzerine-pasta grafiğinde ikinci pasta veya çubuğa hangi veri noktalarının gireceğini belirleme yöntemini belirtir. |
| [setPieSplitBy(int value)](#setPieSplitBy-int-) | Pasta-üzerine-pasta veya çubuk-üzerine-pasta grafiğinde ikinci pasta veya çubuğa hangi veri noktalarının gireceğini belirleme yöntemini belirtir. |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | Özel bölme ile bir pasta-üzerine-pasta veya çubuk-üzerine-pasta grafiği için özelleştirilmiş bölme bilgisi. |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | Halka grafiğindeki deliğin boyutunu belirtir (çizim alanının boyutunun %10 ile %90 arasında olabilir). |
| [setDoughnutHoleSize(byte value)](#setDoughnutHoleSize-byte-) | Halka grafiğindeki deliğin boyutunu belirtir (çizim alanının boyutunun %10 ile %90 arasında olabilir). |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | Balon grafiği için ölçek faktörünü belirtir (varsayılan boyutun %0 ile %300 arasında). |
| [setBubbleSizeScale(int value)](#setBubbleSizeScale-int-) | Balon grafiği için ölçek faktörünü belirtir (varsayılan boyutun %0 ile %300 arasında). |
| [getHiLowLinesFormat()](#getHiLowLinesFormat--) | HiLowLines biçimini belirtir. |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | Balon grafiğinde balon boyutu değerlerinin nasıl temsil edildiğini belirtir. |
| [setBubbleSizeRepresentation(int value)](#setBubbleSizeRepresentation-int-) | Balon grafiğinde balon boyutu değerlerinin nasıl temsil edildiğini belirtir. |

### getType() {#getType--}
```
public abstract int getType()
```

Bu seri grubunun tipini döndürür. Salt okunur [CombinableSeriesTypesGroup](../../com.aspose.slides/combinableseriestypesgroup).

**Döndürür:**
int

### getPlotOnSecondAxis() {#getPlotOnSecondAxis--}
```
public abstract boolean getPlotOnSecondAxis()
```

Bu grubun serilerinin ikincil eksende çizilip çizilmediğini gösterir. Salt okunur boolean.

**Döndürür:**
boolean

### getSeries() {#getSeries--}
```
public abstract IChartSeriesReadonlyCollection getSeries()
```

Okunabilir bir grafik serileri koleksiyonunu döndürür. Salt okunur [IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection).

**Döndürür:**
[IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection)

### get_Item(int index) {#get-Item-int-}
```
public abstract IChartSeries get_Item(int index)
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
public abstract IUpDownBarsManager getUpDownBars()
```

Çizgi veya Stok grafiğinin yukarı/aşağı çubuklarına erişim sağlar. Salt okunur [IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager).

**Döndürür:**
[IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager)

### getGapWidth() {#getGapWidth--}
```
public abstract int getGapWidth()
```

Çubuk veya sütun küme arası boşluğu, çubuk veya sütun genişliğinin yüzde olarak belirler. Okunabilir/Yazılabilir int.

**Döndürür:**
int

### setGapWidth(int value) {#setGapWidth-int-}
```
public abstract void setGapWidth(int value)
```

Çubuk veya sütun küme arası boşluğu, çubuk veya sütun genişliğinin yüzde olarak belirler. Okunabilir/Yazılabilir int.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getGapDepth() {#getGapDepth--}
```
public abstract int getGapDepth()
```

3D grafikte veri serileri arasındaki mesafeyi, işaretçi genişliğinin yüzde olarak döndürür veya ayarlar. Okunabilir/Yazılabilir int.

**Döndürür:**
int

### setGapDepth(int value) {#setGapDepth-int-}
```
public abstract void setGapDepth(int value)
```

3D grafikte veri serileri arasındaki mesafeyi, işaretçi genişliğinin yüzde olarak döndürür veya ayarlar. Okunabilir/Yazılabilir int.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public abstract int getFirstSliceAngle()
```

İlk pasta veya halka grafiği diliminin açısını derece cinsinden alır veya ayarlar (yukarıdan saat yönünde, 0'dan 360 dereceye). Okunabilir/Yazılabilir int.

**Döndürür:**
int

### setFirstSliceAngle(int value) {#setFirstSliceAngle-int-}
```
public abstract void setFirstSliceAngle(int value)
```

İlk pasta veya halka grafiği diliminin açısını derece cinsinden alır veya ayarlar (yukarıdan saat yönünde, 0'dan 360 dereceye). Okunabilir/Yazılabilir int.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### isColorVaried() {#isColorVaried--}
```
public abstract boolean isColorVaried()
```

Serideki her veri işaretçisinin farklı bir renge sahip olmasını belirtir. Okunabilir/Yazılabilir boolean.

**Döndürür:**
boolean

### setColorVaried(boolean value) {#setColorVaried-boolean-}
```
public abstract void setColorVaried(boolean value)
```

Serideki her veri işaretçisinin farklı bir renge sahip olmasını belirtir. Okunabilir/Yazılabilir boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### hasSeriesLines() {#hasSeriesLines--}
```
public abstract boolean hasSeriesLines()
```

Grafik seri çizgilerine sahipse doğru. Yığılmış çubuk ve OfPie grafiklerine uygulanır. Okunabilir/Yazılabilir boolean.

**Döndürür:**
boolean

### setSeriesLines(boolean value) {#setSeriesLines-boolean-}
```
public abstract void setSeriesLines(boolean value)
```

Grafik seri çizgilerine sahipse doğru. Yığılmış çubuk ve OfPie grafiklerine uygulanır. Okunabilir/Yazılabilir boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getOverlap() {#getOverlap--}
```
public abstract byte getOverlap()
```

2D grafiklerde çubuk ve sütunların ne kadar üst üste geleceğini yüzde olarak belirtir (-%100'ten %100'e). - -%100: Azami boşluk (çubuklar tamamen ayrık). - 0%: Çubuklar yan yana, üst üste gelmeden veya boşluk olmadan yerleştirilir. - %100: Azami üst üste binme (çubuklar tamamen birbirinin üstünde). Bu özellik okunabilir/yazılabilir byte.

**Döndürür:**
byte

> ```
> The following example demonstrates how to set the overlap for a chart series group 
>   and render the resulting chart on a form:
>   
>  Presentation pres = new Presentation();
>  try {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.ClusteredColumn, 10, 10, 600, 300);
>      IChartSeriesCollection series = chart.getChartData().getSeries();
>      series.get_Item(0).getParentSeriesGroup().setOverlap((byte)55); // Çakışmayı %55 olarak ayarla
>      pres.getSlides().get_Item(0).getImage(1, 1).save("chart.png");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Döndürür:**
byte

### setOverlap(byte value) {#setOverlap-byte-}
```
public abstract void setOverlap(byte value)
```

2D grafiklerde çubuk ve sütunların ne kadar üst üste geleceğini yüzde olarak belirtir (-%100'ten %100'e). - -%100: Azami boşluk (çubuklar tamamen ayrık). - 0%: Çubuklar yan yana, üst üste gelmeden veya boşluk olmadan yerleştirilir. - %100: Azami üst üste binme (çubuklar tamamen birbirinin üstünde). Bu özellik okunabilir/yazılabilir byte.

> ```
> The following example demonstrates how to set the overlap for a chart series group 
>   and render the resulting chart on a form:
>   
>  Presentation pres = new Presentation();
>  try {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.ClusteredColumn, 10, 10, 600, 300);
>      IChartSeriesCollection series = chart.getChartData().getSeries();
>      series.get_Item(0).getParentSeriesGroup().setOverlap((byte)55); // Çakışmayı %55 olarak ayarla
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
public abstract int getSecondPieSize()
```

İkinci pasta veya çubuğun boyutunu, ilk pastanın boyutunun yüzde olarak belirtir (5 ile 200 arasında olabilir). Okunabilir/Yazılabilir int.

**Döndürür:**
int

### setSecondPieSize(int value) {#setSecondPieSize-int-}
```
public abstract void setSecondPieSize(int value)
```

İkinci pasta veya çubuğun boyutunu, ilk pastanın boyutunun yüzde olarak belirtir (5 ile 200 arasında olabilir). Okunabilir/Yazılabilir int.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getPieSplitPosition() {#getPieSplitPosition--}
```
public abstract double getPieSplitPosition()
```

Pasta-üzerine-pasta veya çubuk-üzerine-pasta grafiğinde ikinci pasta veya çubuğa hangi veri noktalarının gireceğini belirlemek için kullanılacak bir değeri belirtir. PieSplitBy özelliği ile birlikte kullanılır. Okunabilir/Yazılabilir double.

**Döndürür:**
double

### setPieSplitPosition(double value) {#setPieSplitPosition-double-}
```
public abstract void setPieSplitPosition(double value)
```

Pasta-üzerine-pasta veya çubuk-üzerine-pasta grafiğinde ikinci pasta veya çubuğa hangi veri noktalarının gireceğini belirlemek için kullanılacak bir değeri belirtir. PieSplitBy özelliği ile birlikte kullanılır. Okunabilir/Yazılabilir double.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | double |  |

### getPieSplitBy() {#getPieSplitBy--}
```
public abstract int getPieSplitBy()
```

Pasta-üzerine-pasta veya çubuk-üzerine-pasta grafiğinde ikinci pasta veya çubuğa hangi veri noktalarının gireceğini belirleme yöntemini belirtir. Okunabilir/Yazılabilir [PieSplitType](../../com.aspose.slides/piesplittype).

**Döndürür:**
int

### setPieSplitBy(int value) {#setPieSplitBy-int-}
```
public abstract void setPieSplitBy(int value)
```

Pasta-üzerine-pasta veya çubuk-üzerine-pasta grafiğinde ikinci pasta veya çubuğa hangi veri noktalarının gireceğini belirleme yöntemini belirtir. Okunabilir/Yazılabilir [PieSplitType](../../com.aspose.slides/piesplittype).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public abstract IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

Özel bölme ile bir pasta-üzerine-pasta veya çubuk-üzerine-pasta grafiği için özelleştirilmiş bölme bilgisi. İkinci pasta veya çubukta çizilecek veri noktalarını içerir. Salt okunur [IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection).

**Döndürür:**
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)

### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public abstract byte getDoughnutHoleSize()
```

Halka grafiğindeki deliğin boyutunu belirtir (çizim alanının boyutunun %10 ile %90 arasında olabilir). Okunabilir/Yazılabilir byte.

**Döndürür:**
byte

### setDoughnutHoleSize(byte value) {#setDoughnutHoleSize-byte-}
```
public abstract void setDoughnutHoleSize(byte value)
```

Halka grafiğindeki deliğin boyutunu belirtir (çizim alanının boyutunun %10 ile %90 arasında olabilir). Okunabilir/Yazılabilir byte.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |

### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public abstract int getBubbleSizeScale()
```

Balon grafiği için ölçek faktörünü belirtir (varsayılan boyutun %0 ile %300 arasında). Okunabilir/Yazılabilir int.

**Döndürür:**
int

### setBubbleSizeScale(int value) {#setBubbleSizeScale-int-}
```
public abstract void setBubbleSizeScale(int value)
```

Balon grafiği için ölçek faktörünü belirtir (varsayılan boyutun %0 ile %300 arasında). Okunabilir/Yazılabilir int.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getHiLowLinesFormat() {#getHiLowLinesFormat--}
```
public abstract IChartLinesFormat getHiLowLinesFormat()
```

HiLowLines biçimini belirtir. HiLowLines, HiLowClose, OpenHiLowClose, VolumeHiLowClose ve VolumeOpenHiLowClose grafik tipleriyle uygulanır.

**Döndürür:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)

### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public abstract int getBubbleSizeRepresentation()
```

Balon grafiğinde balon boyutu değerlerinin nasıl temsil edildiğini belirtir. Okunabilir/Yazılabilir [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**Döndürür:**
int

### setBubbleSizeRepresentation(int value) {#setBubbleSizeRepresentation-int-}
```
public abstract void setBubbleSizeRepresentation(int value)
```

Balon grafiğinde balon boyutu değerlerinin nasıl temsil edildiğini belirtir. Okunabilir/Yazılabilir [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |