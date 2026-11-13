---
title: IChartSeriesGroup
second_title: Aspose.Slides for Java API Referansı
description: Seri grubunu temsil eder.
type: docs
url: /tr/com.aspose.slides/ichartseriesgroup/
---
**Tüm Uygulanan Arayüzler:**
[com.aspose.slides.IChartComponent](../../com.aspose.slides/ichartcomponent)
```
public interface IChartSeriesGroup extends IChartComponent
```

Seri grubunu temsil eder.

--------------------

1) ChartSeriesGroupCollection sınıfı ve CombinableSeriesTypesGroup enum'ı için özet ve açıklamalara bakın. 2) Seri grubu, grup içindeki her seri için ortak olan bazı seri özelliklerini ("seri grup özellikleri") içerir. ChartSeriesGroup sınıfındaki "seri grup özellikleri" okunabilir/yazılabilir. "Seri grup özellikleri"nin her biri ChartSeries sınıfında yalnızca okuma amaçlı bir projeksiyona sahip olabilir.

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getType()](#getType--) | Bu seri grubunun türünü döndürür. |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | Bu grubun serilerinin ikincil eksende çizilip çizilmediğini gösterir. |
| [getSeries()](#getSeries--) | Yalnızca okunabilir bir grafik serileri koleksiyonunu döndürür. |
| [get_Item(int index)](#get-Item-int-) | Belirtilen dizindeki öğeyi alır. |
| [getUpDownBars()](#getUpDownBars--) | Çizgi veya Hisse grafiğinin yukarı/aşağı çubuklarına erişim sağlar. |
| [getGapWidth()](#getGapWidth--) | Çubuk veya sütun kümeleri arasındaki boşluğu, çubuk veya sütun genişliğinin yüzde olarak ayarlar veya alır. |
| [setGapWidth(int value)](#setGapWidth-int-) | Çubuk veya sütun kümeleri arasındaki boşluğu, çubuk veya sütun genişliğinin yüzde olarak ayarlar veya alır. |
| [getGapDepth()](#getGapDepth--) | 3B grafikte veri serileri arasındaki mesafeyi, işaretçi genişliğinin yüzde olarak ayarlar veya alır. |
| [setGapDepth(int value)](#setGapDepth-int-) | 3B grafikte veri serileri arasındaki mesafeyi, işaretçi genişliğinin yüzde olarak ayarlar veya alır. |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | İlk pasta veya halka grafik diliminin açısını derece cinsinden ayarlar veya alır (yukarıdan saat yönünde, 0'dan 360 dereceye). |
| [setFirstSliceAngle(int value)](#setFirstSliceAngle-int-) | İlk pasta veya halka grafik diliminin açısını derece cinsinden ayarlar veya alır (yukarıdan saat yönünde, 0'dan 360 dereceye). |
| [isColorVaried()](#isColorVaried--) | Serideki her veri işaretçisinin farklı bir renge sahip olmasını belirtir. |
| [setColorVaried(boolean value)](#setColorVaried-boolean-) | Serideki her veri işaretçisinin farklı bir renge sahip olmasını belirtir. |
| [hasSeriesLines()](#hasSeriesLines--) | Grafik serileri çizgilerine sahipse doğru değer döner. |
| [setSeriesLines(boolean value)](#setSeriesLines-boolean-) | Grafik serileri çizgilerine sahipse doğru değer döner. |
| [getOverlap()](#getOverlap--) | 2D grafiklerde çubuk ve sütunların ne kadar üst üste geleceğini yüzde olarak ayarlar veya alır (-100% ile 100% arası). |
| [setOverlap(byte value)](#setOverlap-byte-) | 2D grafiklerde çubuk ve sütunların ne kadar üst üste geleceğini yüzde olarak ayarlar veya alır (-100% ile 100% arası). |
| [getSecondPieSize()](#getSecondPieSize--) | Pie-of-pie veya bar-of-pie grafiklerinde ikinci pasta veya çubuğun boyutunu, ilk pastanın boyutunun yüzde olarak ayarlar veya alır (5 ile 200 yüzde arasında olabilir). |
| [setSecondPieSize(int value)](#setSecondPieSize-int-) | Pie-of-pie veya bar-of-pie grafiklerinde ikinci pasta veya çubuğun boyutunu, ilk pastanın boyutunun yüzde olarak ayarlar veya alır (5 ile 200 yüzde arasında olabilir). |
| [getPieSplitPosition()](#getPieSplitPosition--) | Pie-of-pie veya bar-of-pie grafiklerinde ikinci pasta veya çubuğa hangi veri noktalarının düşeceğini belirlemek için kullanılacak değeri ayarlar veya alır. |
| [setPieSplitPosition(double value)](#setPieSplitPosition-double-) | Pie-of-pie veya bar-of-pie grafiklerinde ikinci pasta veya çubuğa hangi veri noktalarının düşeceğini belirlemek için kullanılacak değeri ayarlar veya alır. |
| [getPieSplitBy()](#getPieSplitBy--) | Pie-of-pie veya bar-of-pie grafiklerinde ikinci pasta veya çubuğa hangi veri noktalarının düşeceğini belirleme şeklinin ayarlanmasını sağlar. |
| [setPieSplitBy(int value)](#setPieSplitBy-int-) | Pie-of-pie veya bar-of-pie grafiklerinde ikinci pasta veya çubuğa hangi veri noktalarının düşeceğini belirleme şeklinin ayarlanmasını sağlar. |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | Özel bölme bilgisi, özel bölmesi olan pie-of-pie veya bar-of-pie grafikleri için. |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | Donut grafikteki deliğin boyutunu ayarlar (grafik alanının boyutunun %10 ile %90 arasında olabilir). |
| [setDoughnutHoleSize(byte value)](#setDoughnutHoleSize-byte-) | Donut grafikteki deliğin boyutunu ayarlar (grafik alanının boyutunun %10 ile %90 arasında olabilir). |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | Baloncuk grafik için ölçek faktörünü ayarlar (varsayılan boyutun %0 ile %300 arasında olabilir). |
| [setBubbleSizeScale(int value)](#setBubbleSizeScale-int-) | Baloncuk grafik için ölçek faktörünü ayarlar (varsayılan boyutun %0 ile %300 arasında olabilir). |
| [getHiLowLinesFormat()](#getHiLowLinesFormat--) | HiLowLines biçimini ayarlar. |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | Baloncuk grafik üzerindeki baloncuk boyutu değerlerinin nasıl temsil edildiğini ayarlar. |
| [setBubbleSizeRepresentation(int value)](#setBubbleSizeRepresentation-int-) | Baloncuk grafik üzerindeki baloncuk boyutu değerlerinin nasıl temsil edildiğini ayarlar. |

### getType() {#getType--}
```
public abstract int getType()
```

Bu seri grubunun türünü döndürür. Yalnızca okuma [CombinableSeriesTypesGroup](../../com.aspose.slides/combinableseriestypesgroup).

**Döndürür:**
int

### getPlotOnSecondAxis() {#getPlotOnSecondAxis--}
```
public abstract boolean getPlotOnSecondAxis()
```

Bu grubun serilerinin ikincil eksende çizilip çizilmediğini gösterir. Yalnızca okuma boolean.

**Döndürür:**
boolean

### getSeries() {#getSeries--}
```
public abstract IChartSeriesReadonlyCollection getSeries()
```

Yalnızca okunabilir bir grafik serileri koleksiyonunu döndürür. Yalnızca okuma [IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection).

**Döndürür:**
[IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection)

### get_Item(int index) {#get-Item-int-}
```
public abstract IChartSeries get_Item(int index)
```

Belirtilen dizindeki öğeyi alır.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| index | int |  |

**Döndürür:**
[IChartSeries](../../com.aspose.slides/ichartseries)

### getUpDownBars() {#getUpDownBars--}
```
public abstract IUpDownBarsManager getUpDownBars()
```

Çizgi veya Hisse grafiğinin yukarı/aşağı çubuklarına erişim sağlar. Yalnızca okuma [IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager).

**Döndürür:**
[IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager)

### getGapWidth() {#getGapWidth--}
```
public abstract int getGapWidth()
```

Çubuk veya sütun kümeleri arasındaki boşluğu, çubuk veya sütun genişliğinin yüzde olarak ayarlar veya alır. Değer 0 ile 500 arasında olmalıdır. Okunur/yazılır int.

--------------------

Bu özellik aşağıdaki tiplerin serilerine uygulanır: Tüm çubuk ve sütun alt tipleri, [ChartType.BarOfPie](../../com.aspose.slides/charttype\#BarOfPie), [ChartType.PieOfPie](../../com.aspose.slides/charttype\#PieOfPie), [ChartType.BoxAndWhisker](../../com.aspose.slides/charttype\#BoxAndWhisker), [ChartType.Funnel](../../com.aspose.slides/charttype\#Funnel), [ChartType.Histogram](../../com.aspose.slides/charttype\#Histogram), [ChartType.Waterfall](../../com.aspose.slides/charttype\#Waterfall).

**Döndürür:**
int

### setGapWidth(int value) {#setGapWidth-int-}
```
public abstract void setGapWidth(int value)
```

Çubuk veya sütun kümeleri arasındaki boşluğu, çubuk veya sütun genişliğinin yüzde olarak ayarlar veya alır. Değer 0 ile 500 arasında olmalıdır. Okunur/yazılır int.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | int |  |

--------------------

Bu özellik aşağıdaki tiplerin serilerine uygulanır: Tüm çubuk ve sütun alt tipleri, [ChartType.BarOfPie](../../com.aspose.slides/charttype\#BarOfPie), [ChartType.PieOfPie](../../com.aspose.slides/charttype\#PieOfPie), [ChartType.BoxAndWhisker](../../com.aspose.slides/charttype\#BoxAndWhisker), [ChartType.Funnel](../../com.aspose.slides/charttype\#Funnel), [ChartType.Histogram](../../com.aspose.slides/charttype\#Histogram), [ChartType.Waterfall](../../com.aspose.slides/charttype\#Waterfall).

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | int |  |

### getGapDepth() {#getGapDepth--}
```
public abstract int getGapDepth()
```

3B grafikte veri serileri arasındaki mesafeyi, işaretçi genişliğinin yüzde olarak ayarlar veya alır. Değer 0 ile 500 arasında olmalıdır. Okunur/yazılır int.

--------------------

Bu özellik aşağıdaki tiplerin serilerine uygulanır: 3B çubuk ve sütun alt tipleri, [ChartType.Line3D](../../com.aspose.slides/charttype\#Line3D), [ChartType.Area3D](../../com.aspose.slides/charttype\#Area3D), [ChartType.StackedArea3D](../../com.aspose.slides/charttype\#StackedArea3D), [ChartType.PercentsStackedArea3D](../../com.aspose.slides/charttype\#PercentsStackedArea3D).

**Döndürür:**
int

### setGapDepth(int value) {#setGapDepth-int-}
```
public abstract void setGapDepth(int value)
```

3B grafikte veri serileri arasındaki mesafeyi, işaretçi genişliğinin yüzde olarak ayarlar veya alır. Değer 0 ile 500 arasında olmalıdır. Okunur/yazılır int.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | int |  |

--------------------

Bu özellik aşağıdaki tiplerin serilerine uygulanır: 3B çubuk ve sütun alt tipleri, [ChartType.Line3D](../../com.aspose.slides/charttype\#Line3D), [ChartType.Area3D](../../com.aspose.slides/charttype\#Area3D), [ChartType.StackedArea3D](../../com.aspose.slides/charttype\#StackedArea3D), [ChartType.PercentsStackedArea3D](../../com.aspose.slides/charttype\#PercentsStackedArea3D).

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | int |  |

### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public abstract int getFirstSliceAngle()
```

İlk pasta veya halka grafik diliminin açısını derece cinsinden ayarlar veya alır (yukarıdan saat yönünde, 0'dan 360 dereceye). Okunur/yazılır int.

**Döndürür:**
int

### setFirstSliceAngle(int value) {#setFirstSliceAngle-int-}
```
public abstract void setFirstSliceAngle(int value)
```

İlk pasta veya halka grafik diliminin açısını derece cinsinden ayarlar veya alır (yukarıdan saat yönünde, 0'dan 360 dereceye). Okunur/yazılır int.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | int |  |

### isColorVaried() {#isColorVaried--}
```
public abstract boolean isColorVaried()
```

Serideki her veri işaretçisinin farklı bir renge sahip olmasını belirtir. Okunur/yazılır boolean.

**Döndürür:**
boolean

### setColorVaried(boolean value) {#setColorVaried-boolean-}
```
public abstract void setColorVaried(boolean value)
```

Serideki her veri işaretçisinin farklı bir renge sahip olmasını belirtir. Okunur/yazılır boolean.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### hasSeriesLines() {#hasSeriesLines--}
```
public abstract boolean hasSeriesLines()
```

Grafikte seri çizgileri varsa doğru döner. Yığılmış çubuk ve OfPie grafiklerine uygulanır. Okunur/yazılır boolean.

**Döndürür:**
boolean

### setSeriesLines(boolean value) {#setSeriesLines-boolean-}
```
public abstract void setSeriesLines(boolean value)
```

Grafikte seri çizgileri varsa doğru döner. Yığılmış çubuk ve OfPie grafiklerine uygulanır. Okunur/yazılır boolean.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getOverlap() {#getOverlap--}
```
public abstract byte getOverlap()
```

2D grafiklerde çubuk ve sütunların ne kadar üst üste geleceğini yüzde olarak ayarlar veya alır (-100% ile 100% arasında). --100%: En fazla boşluk (çubuklar tamamen ayrılmıştır). -0%: Çubuklar yan yana, üst üste gelmeden ya da boşluk olmadan yerleştirilir. -100%: En fazla üst üste gelme (çubuklar tamamen üst üste gelir). Bu özellik okunur/yazılır byte.

--------------------

> ```
> The following example demonstrates how to set the overlap for a chart series group 
>   and render the resulting chart on a form:
>   
>  Presentation pres = new Presentation();
>  try {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.ClusteredColumn, 10, 10, 600, 300);
>      IChartSeriesCollection series = chart.getChartData().getSeries();
>      series.get_Item(0).getParentSeriesGroup().setOverlap((byte)55); // Üst üste bindirmeyi %55 olarak ayarla
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

2D grafiklerde çubuk ve sütunların ne kadar üst üste geleceğini yüzde olarak ayarlar veya alır (-100% ile 100% arasında). --100%: En fazla boşluk (çubuklar tamamen ayrılmıştır). -0%: Çubuklar yan yana, üst üste gelmeden ya da boşluk olmadan yerleştirilir. -100%: En fazla üst üste gelme (çubuklar tamamen üst üste gelir). Bu özellik okunur/yazılır byte.

--------------------

> ```
> The following example demonstrates how to set the overlap for a chart series group 
>   and render the resulting chart on a form:
>   
>  Presentation pres = new Presentation();
>  try {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.ClusteredColumn, 10, 10, 600, 300);
>      IChartSeriesCollection series = chart.getChartData().getSeries();
>      series.get_Item(0).getParentSeriesGroup().setOverlap((byte)55); // Üst üste bindirmeyi %55 olarak ayarla
>      pres.getSlides().get_Item(0).getImage(1, 1).save("chart.png", ImageFormat.Png);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | byte |  |

### getSecondPieSize() {#getSecondPieSize--}
```
public abstract int getSecondPieSize()
```

Pie-of-pie veya bar-of-pie grafiklerinde ikinci pasta veya çubuğun boyutunu, ilk pastanın boyutunun yüzde olarak ayarlar veya alır (5 ile 200 yüzde arasında). Okunur/yazılır int.

**Döndürür:**
int

### setSecondPieSize(int value) {#setSecondPieSize-int-}
```
public abstract void setSecondPieSize(int value)
```

Pie-of-pie veya bar-of-pie grafiklerinde ikinci pasta veya çubuğun boyutunu, ilk pastanın boyutunun yüzde olarak ayarlar veya alır (5 ile 200 yüzde arasında). Okunur/yazılır int.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | int |  |

### getPieSplitPosition() {#getPieSplitPosition--}
```
public abstract double getPieSplitPosition()
```

Pie-of-pie veya bar-of-pie grafiklerinde ikinci pasta veya çubuğa hangi veri noktalarının düşeceğini belirlemek için kullanılacak değeri ayarlar veya alır. PieSplitBy özelliğiyle birlikte kullanılır. Okunur/yazılır double.

**Döndürür:**
double

### setPieSplitPosition(double value) {#setPieSplitPosition-double-}
```
public abstract void setPieSplitPosition(double value)
```

Pie-of-pie veya bar-of-pie grafiklerinde ikinci pasta veya çubuğa hangi veri noktalarının düşeceğini belirlemek için kullanılacak değeri ayarlar veya alır. PieSplitBy özelliğiyle birlikte kullanılır. Okunur/yazılır double.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | double |  |

### getPieSplitBy() {#getPieSplitBy--}
```
public abstract int getPieSplitBy()
```

Pie-of-pie veya bar-of-pie grafiklerinde ikinci pasta veya çubuğa hangi veri noktalarının düşeceğini belirleme şeklinin ayarlanmasını sağlar. Okunur/yazılır [PieSplitType](../../com.aspose.slides/piesplittype).

**Döndürür:**
int

### setPieSplitBy(int value) {#setPieSplitBy-int-}
```
public abstract void setPieSplitBy(int value)
```

Pie-of-pie veya bar-of-pie grafiklerinde ikinci pasta veya çubuğa hangi veri noktalarının düşeceğini belirleme şeklinin ayarlanmasını sağlar. Okunur/yazılır [PieSplitType](../../com.aspose.slides/piesplittype).

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | int |  |

### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public abstract IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

Özel bölme bilgisi, özel bölmesi olan pie-of-pie veya bar-of-pie grafikleri için. İkinci pasta veya çubukta çizilecek veri noktalarını içerir. Yalnızca okuma [IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection).

**Döndürür:**
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)

### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public abstract byte getDoughnutHoleSize()
```

Donut grafikteki deliğin boyutunu ayarlar (grafik alanının %10 ile %90 arasında olabilir). Okunur/yazılır byte.

**Döndürür:**
byte

### setDoughnutHoleSize(byte value) {#setDoughnutHoleSize-byte-}
```
public abstract void setDoughnutHoleSize(byte value)
```

Donut grafikteki deliğin boyutunu ayarlar (grafik alanının %10 ile %90 arasında olabilir). Okunur/yazılır byte.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | byte |  |

### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public abstract int getBubbleSizeScale()
```

Baloncuk grafik için ölçek faktörünü ayarlar (varsayılan boyutun %0 ile %300 arasında olabilir). Okunur/yazılır int.

**Döndürür:**
int

### setBubbleSizeScale(int value) {#setBubbleSizeScale-int-}
```
public abstract void setBubbleSizeScale(int value)
```

Baloncuk grafik için ölçek faktörünü ayarlar (varsayılan boyutun %0 ile %300 arasında olabilir). Okunur/yazılır int.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | int |  |

### getHiLowLinesFormat() {#getHiLowLinesFormat--}
```
public abstract IChartLinesFormat getHiLowLinesFormat()
```

HiLowLines biçimini ayarlar. HiLowLines, HiLowClose, OpenHiLowClose, VolumeHiLowClose ve VolumeOpenHiLowClose grafik tipleriyle uygulanır.

**Döndürür:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)

### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public abstract int getBubbleSizeRepresentation()
```

Baloncuk grafik üzerindeki baloncuk boyutu değerlerinin nasıl temsil edildiğini ayarlar. Okunur/yazılır [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**Döndürür:**
int

### setBubbleSizeRepresentation(int value) {#setBubbleSizeRepresentation-int-}
```
public abstract void setBubbleSizeRepresentation(int value)
```

Baloncuk grafik üzerindeki baloncuk boyutu değerlerinin nasıl temsil edildiğini ayarlar. Okunur/yazılır [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | int |  |