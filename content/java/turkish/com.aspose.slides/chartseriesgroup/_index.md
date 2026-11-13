---
title: ChartSeriesGroup
second_title: Aspose.Slides for Java API Referansı
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

1) ChartSeriesGroupCollection sınıfı ve CombinableSeriesTypesGroup enum için özet ve notları inceleyin. 2) Seri grubu, grup içindeki her seri için ortak olan bazı seri özelliklerini içerir ("series group properties"). ChartSeriesGroup sınıfındaki "series group properties" okunur/yazılabilir. Her bir "series group properties" ChartSeries sınıfında yalnızca okunabilir bir yansıtma alabilir.

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getType()](#getType--) | Bu seri grubunun tipini döndürür. |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | Bu grubun serilerinin ikincil eksende çizilip çizilmediğini gösterir. |
| [getSeries()](#getSeries--) | Seri koleksiyonunu döndürür. |
| [get_Item(int index)](#get-Item-int-) | Belirtilen indeksteki öğeyi alır. |
| [getUpDownBars()](#getUpDownBars--) | Line veya Stock grafiğinin up/down çubuklarına erişim sağlar. |
| [getGapWidth()](#getGapWidth--) | Çubuk veya sütun kümeleri arasındaki boşluğu, çubuk veya sütun genişliğinin yüzde olarak alır ya da ayarlar. |
| [setGapWidth(int value)](#setGapWidth-int-) | Çubuk veya sütun kümeleri arasındaki boşluğu, çubuk veya sütun genişliğinin yüzde olarak alır ya da ayarlar. |
| [getGapDepth()](#getGapDepth--) | 3D grafikte veri serileri arasındaki mesafeyi, işaretçi genişliğinin yüzde olarak alır ya da ayarlar. |
| [setGapDepth(int value)](#setGapDepth-int-) | 3D grafikte veri serileri arasındaki mesafeyi, işaretçi genişliğinin yüzde olarak alır ya da ayarlar. |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | İlk pasta veya halka grafik diliminin açısını derece cinsinden alır ya da ayarlar (üstten saat yönünde, 0'dan 360 dereceye). |
| [setFirstSliceAngle(int value)](#setFirstSliceAngle-int-) | İlk pasta veya halka grafik diliminin açısını derece cinsinden alır ya da ayarlar (üstten saat yönünde, 0'dan 360 dereceye). |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | Halka grafik içindeki deliğin boyutunu belirtir (grafik alanının boyutunun %0 ile %90 arasında olabilir). |
| [setDoughnutHoleSize(byte value)](#setDoughnutHoleSize-byte-) | Halka grafik içindeki deliğin boyutunu belirtir (grafik alanının boyutunun %0 ile %90 arasında olabilir). |
| [getOverlap()](#getOverlap--) | 2D grafiklerde çubuk ve sütunların ne kadar üst üste geleceğini yüzde olarak belirtir (%-100 ile %100 arasında). |
| [setOverlap(byte value)](#setOverlap-byte-) | 2D grafiklerde çubuk ve sütunların ne kadar üst üste geleceğini yüzde olarak belirtir (%-100 ile %100 arasında). |
| [getSecondPieSize()](#getSecondPieSize--) | Pie-of-pie ya da bar-of-pie grafiğinde ikinci pasta veya çubuğun boyutunu, ilk pastanın boyutuna göre yüzde olarak belirtir (%5 ile %200 arasında olabilir). |
| [setSecondPieSize(int value)](#setSecondPieSize-int-) | Pie-of-pie ya da bar-of-pie grafiğinde ikinci pasta veya çubuğun boyutunu, ilk pastanın boyutuna göre yüzde olarak belirtir (%5 ile %200 arasında olabilir). |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | Balon grafiğinde balon boyutu değerlerinin nasıl temsil edileceğini belirtir. |
| [setBubbleSizeRepresentation(int value)](#setBubbleSizeRepresentation-int-) | Balon grafiğinde balon boyutu değerlerinin nasıl temsil edileceğini belirtir. |
| [getPieSplitPosition()](#getPieSplitPosition--) | Pie-of-pie ya da bar-of-pie grafiğinde hangi veri noktalarının ikinci pasta veya çubukta olacağını belirlemek için kullanılacak bir değeri belirtir. |
| [setPieSplitPosition(double value)](#setPieSplitPosition-double-) | Pie-of-pie ya da bar-of-pie grafiğinde hangi veri noktalarının ikinci pasta veya çubukta olacağını belirlemek için kullanılacak bir değeri belirtir. |
| [getPieSplitBy()](#getPieSplitBy--) | Pie-of-pie ya da bar-of-pie grafiğinde hangi veri noktalarının ikinci pasta veya çubukta olacağını belirleme şeklini belirtir. |
| [setPieSplitBy(int value)](#setPieSplitBy-int-) | Pie-of-pie ya da bar-of-pie grafiğinde hangi veri noktalarının ikinci pasta veya çubukta olacağını belirleme şeklini belirtir. |
| [isColorVaried()](#isColorVaried--) | Serideki her veri işaretçisinin farklı bir renge sahip olacağını belirtir. |
| [setColorVaried(boolean value)](#setColorVaried-boolean-) | Serideki her veri işaretçisinin farklı bir renge sahip olacağını belirtir. |
| [hasSeriesLines()](#hasSeriesLines--) | Grafiğin seri çizgileri varsa true. |
| [setSeriesLines(boolean value)](#setSeriesLines-boolean-) | Grafiğin seri çizgileri varsa true. |
| [getHiLowLinesFormat()](#getHiLowLinesFormat--) | HiLowLines biçimini belirtir. |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | Balon grafiği için ölçek faktörünü belirtir (varsayılan boyutun %0 ile %300 arasında olabilir). |
| [setBubbleSizeScale(int value)](#setBubbleSizeScale-int-) | Balon grafiği için ölçek faktörünü belirtir (varsayılan boyutun %0 ile %300 arasında olabilir). |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | Özel bölünmeye sahip bir pie-of-pie veya bar-of-pie grafiği için özelleştirilmiş bölünme bilgisi. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getChart()](#getChart--) | Üst grafik nesnesini döndürür. |
| [getSlide()](#getSlide--) | FillFormat nesnesinin üst slaytını döndürür. |
| [getPresentation()](#getPresentation--) | FillFormat nesnesinin üst sunumunu döndürür. |

### getType() {#getType--}
```
public final int getType()
```

Bu seri grubunun tipini döndürür. Yalnızca okunabilir [CombinableSeriesTypesGroup](../../com.aspose.slides/combinableseriestypesgroup).

**Döndürür:**
int

### getPlotOnSecondAxis() {#getPlotOnSecondAxis--}
```
public final boolean getPlotOnSecondAxis()
```

Bu grubun serilerinin ikincil eksende çizilip çizilmediğini gösterir. Yalnızca okunabilir boolean.

**Döndürür:**
boolean

### getSeries() {#getSeries--}
```
public final IChartSeriesReadonlyCollection getSeries()
```

Seri koleksiyonunu döndürür. Yalnızca okunabilir [IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection).

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

Line veya Stock grafiğinin up/down çubuklarına erişim sağlar. Yalnızca okunabilir [IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager).

**Döndürür:**
[IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager)

### getGapWidth() {#getGapWidth--}
```
public final int getGapWidth()
```

Çubuk veya sütun kümeleri arasındaki boşluğu, çubuk veya sütun genişliğinin yüzde olarak alır ya da ayarlar. Değer 0 ile 500 arasında olmalıdır. Okunur/yazılabilir int.

--------------------

Bu özellik aşağıdaki türlerdeki serilere uygulanır: Bar alt türleri (ayrıca [ChartTypeCharacterizer.isChartTypeBar(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBar-int-) metoduna bakınız), Column alt türleri (ayrıca [ChartTypeCharacterizer.isChartTypeColumn(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeColumn-int-) metoduna bakınız), [ChartType.BarOfPie](../../com.aspose.slides/charttype\#BarOfPie), [ChartType.PieOfPie](../../com.aspose.slides/charttype\#PieOfPie), [ChartType.BoxAndWhisker](../../com.aspose.slides/charttype\#BoxAndWhisker), [ChartType.Funnel](../../com.aspose.slides/charttype\#Funnel), [ChartType.Histogram](../../com.aspose.slides/charttype\#Histogram), [ChartType.Waterfall](../../com.aspose.slides/charttype\#Waterfall).

**Döndürür:**
int

### setGapWidth(int value) {#setGapWidth-int-}
```
public final void setGapWidth(int value)
```

Çubuk veya sütun kümeleri arasındaki boşluğu, çubuk veya sütun genişliğinin yüzde olarak alır ya da ayarlar. Değer 0 ile 500 arasında olmalıdır. Okunur/yazılabilir int.

--------------------

Bu özellik aşağıdaki türlerdeki serilere uygulanır: Bar alt türleri (ayrıca [ChartTypeCharacterizer.isChartTypeBar(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBar-int-) metoduna bakınız), Column alt türleri (ayrıca [ChartTypeCharacterizer.isChartTypeColumn(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeColumn-int-) metoduna bakınız), [ChartType.BarOfPie](../../com.aspose.slides/charttype\#BarOfPie), [ChartType.PieOfPie](../../com.aspose.slides/charttype\#PieOfPie), [ChartType.BoxAndWhisker](../../com.aspose.slides/charttype\#BoxAndWhisker), [ChartType.Funnel](../../com.aspose.slides/charttype\#Funnel), [ChartType.Histogram](../../com.aspose.slides/charttype\#Histogram), [ChartType.Waterfall](../../com.aspose.slides/charttype\#Waterfall).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getGapDepth() {#getGapDepth--}
```
public final int getGapDepth()
```

3D grafikte veri serileri arasındaki mesafeyi, işaretçi genişliğinin yüzde olarak alır ya da ayarlar. Değer 0 ile 500 arasında olmalıdır. Okunur/yazılabilir int.

--------------------

Bu özellik aşağıdaki türlerdeki serilere uygulanır: 3D bar ve column alt türleri (ayrıca [ChartTypeCharacterizer.isBar3DChart(int)](../../com.aspose.slides/charttypecharacterizer\#isBar3DChart-int-) metoduna bakınız), [ChartType.Line3D](../../com.aspose.slides/charttype\#Line3D), [ChartType.Area3D](../../com.aspose.slides/charttype\#Area3D), [ChartType.StackedArea3D](../../com.aspose.slides/charttype\#StackedArea3D), [ChartType.PercentsStackedArea3D](../../com.aspose.slides/charttype\#PercentsStackedArea3D).

**Döndürür:**
int

### setGapDepth(int value) {#setGapDepth-int-}
```
public final void setGapDepth(int value)
```

3D grafikte veri serileri arasındaki mesafeyi, işaretçi genişliğinin yüzde olarak alır ya da ayarlar. Değer 0 ile 500 arasında olmalıdır. Okunur/yazılabilir int.

--------------------

Bu özellik aşağıdaki türlerdeki serilere uygulanır: 3D bar ve column alt türleri (ayrıca [ChartTypeCharacterizer.isBar3DChart(int)](../../com.aspose.slides/charttypecharacterizer\#isBar3DChart-int-) metoduna bakınız), [ChartType.Line3D](../../com.aspose.slides/charttype\#Line3D), [ChartType.Area3D](../../com.aspose.slides/charttype\#Area3D), [ChartType.StackedArea3D](../../com.aspose.slides/charttype\#StackedArea3D), [ChartType.PercentsStackedArea3D](../../com.aspose.slides/charttype\#PercentsStackedArea3D).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public final int getFirstSliceAngle()
```

İlk pasta veya halka grafik diliminin açısını derece cinsinden alır ya da ayarlar (üstten saat yönünde, 0'dan 360 dereceye). Okunur/yazılabilir int.

**Döndürür:**
int

### setFirstSliceAngle(int value) {#setFirstSliceAngle-int-}
```
public final void setFirstSliceAngle(int value)
```

İlk pasta veya halka grafik diliminin açısını derece cinsinden alır ya da ayarlar (üstten saat yönünde, 0'dan 360 dereceye). Okunur/yazılabilir int.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public final byte getDoughnutHoleSize()
```

Halka grafik içindeki deliğin boyutunu belirtir (grafik alanının %0 ile %90 arasında olabilir). Okunur/yazılabilir byte.

**Döndürür:**
byte

### setDoughnutHoleSize(byte value) {#setDoughnutHoleSize-byte-}
```
public final void setDoughnutHoleSize(byte value)
```

Halka grafik içindeki deliğin boyutunu belirtir (grafik alanının %0 ile %90 arasında olabilir). Okunur/yazılabilir byte.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |

### getOverlap() {#getOverlap--}
```
public final byte getOverlap()
```

2D grafiklerde çubuk ve sütunların ne kadar üst üste geleceğini yüzde olarak belirtir (%-100 ile %100 arasında). - -100%: Maksimum boşluk (çubuklar tamamen ayrılmıştır). - 0%: Çubuklar yan yana, üst üste gelmez veya boşluk yoktur. - 100%: Maksimum üst üste gelme (çubuklar tamamen üst üste). Bu özellik okunur/yazılabilir byte.

--------------------

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


**Döndürür:**
byte

### setOverlap(byte value) {#setOverlap-byte-}
```
public final void setOverlap(byte value)
```

2D grafiklerde çubuk ve sütunların ne kadar üst üste geleceğini yüzde olarak belirtir (%-100 ile %100 arasında). - -100%: Maksimum boşluk (çubuklar tamamen ayrılmıştır). - 0%: Çubuklar yan yana, üst üste gelmez veya boşluk yoktur. - 100%: Maksimum üst üste gelme (çubuklar tamamen üst üste). Bu özellik okunur/yazılabilir byte.

--------------------

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
public final int getSecondPieSize()
```

Pie-of-pie ya da bar-of-pie grafiğinde ikinci pasta veya çubuğun boyutunu, ilk pastanın boyutuna göre yüzde olarak belirtir (%5 ile %200 arasında olabilir). Okunur/yazılabilir int.

**Döndürür:**
int

### setSecondPieSize(int value) {#setSecondPieSize-int-}
```
public final void setSecondPieSize(int value)
```

Pie-of-pie ya da bar-of-pie grafiğinde ikinci pasta veya çubuğun boyutunu, ilk pastanın boyutuna göre yüzde olarak belirtir (%5 ile %200 arasında olabilir). Okunur/yazılabilir int.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public final int getBubbleSizeRepresentation()
```

Balon grafiğinde balon boyutu değerlerinin nasıl temsil edileceğini belirtir. Okunur/yazılabilir [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**Döndürür:**
int

### setBubbleSizeRepresentation(int value) {#setBubbleSizeRepresentation-int-}
```
public final void setBubbleSizeRepresentation(int value)
```

Balon grafiğinde balon boyutu değerlerinin nasıl temsil edileceğini belirtir. Okunur/yazılabilir [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getPieSplitPosition() {#getPieSplitPosition--}
```
public final double getPieSplitPosition()
```

Pie-of-pie ya da bar-of-pie grafiğinde ikinci pasta veya çubukta hangi veri noktalarının olacağını belirlemek için kullanılacak bir değeri belirtir. PieSplitBy özelliğiyle birlikte kullanılır. Okunur/yazılabilir double.

**Döndürür:**
double

### setPieSplitPosition(double value) {#setPieSplitPosition-double-}
```
public final void setPieSplitPosition(double value)
```

Pie-of-pie ya da bar-of-pie grafiğinde ikinci pasta veya çubukta hangi veri noktalarının olacağını belirlemek için kullanılacak bir değeri belirtir. PieSplitBy özelliğiyle birlikte kullanılır. Okunur/yazılabilir double.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | double |  |

### getPieSplitBy() {#getPieSplitBy--}
```
public final int getPieSplitBy()
```

Pie-of-pie ya da bar-of-pie grafiğinde ikinci pasta veya çubukta hangi veri noktalarının olacağını belirleme şeklini belirtir. Okunur/yazılabilir [PieSplitType](../../com.aspose.slides/piesplittype).

**Döndürür:**
int

### setPieSplitBy(int value) {#setPieSplitBy-int-}
```
public final void setPieSplitBy(int value)
```

Pie-of-pie ya da bar-of-pie grafiğinde ikinci pasta veya çubukta hangi veri noktalarının olacağını belirleme şeklini belirtir. Okunur/yazılabilir [PieSplitType](../../com.aspose.slides/piesplittype).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### isColorVaried() {#isColorVaried--}
```
public final boolean isColorVaried()
```

Serideki her veri işaretçisinin farklı bir renge sahip olacağını belirtir. Okunur/yazılabilir boolean.

**Döndürür:**
boolean

### setColorVaried(boolean value) {#setColorVaried-boolean-}
```
public final void setColorVaried(boolean value)
```

Serideki her veri işaretçisinin farklı bir renge sahip olacağını belirtir. Okunur/yazılabilir boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### hasSeriesLines() {#hasSeriesLines--}
```
public final boolean hasSeriesLines()
```

Grafik serileri çizgileri varsa true. Yığılmış bar ve OfPie grafiklerine uygulanır. Okunur/yazılabilir boolean.

**Döndürür:**
boolean

### setSeriesLines(boolean value) {#setSeriesLines-boolean-}
```
public final void setSeriesLines(boolean value)
```

Grafik serileri çizgileri varsa true. Yığılmış bar ve OfPie grafiklerine uygulanır. Okunur/yazılabilir boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getHiLowLinesFormat() {#getHiLowLinesFormat--}
```
public final IChartLinesFormat getHiLowLinesFormat()
```

HiLowLines biçimini belirtir. HiLowLines, HiLowClose, OpenHiLowClose, VolumeHiLowClose ve VolumeOpenHiLowClose grafik tipleriyle birlikte uygulanır.

**Döndürür:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)

### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public final int getBubbleSizeScale()
```

Balon grafiği için ölçek faktörünü belirtir (varsayılan boyutun %0 ile %300 arasında olabilir). Okunur/yazılabilir int.

**Döndürür:**
int

### setBubbleSizeScale(int value) {#setBubbleSizeScale-int-}
```
public final void setBubbleSizeScale(int value)
```

Balon grafiği için ölçek faktörünü belirtir (varsayılan boyutun %0 ile %300 arasında olabilir). Okunur/yazılabilir int.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public final IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

Özel bölünmeye sahip bir pie-of-pie veya bar-of-pie grafiği için özelleştirilmiş bölünme bilgisi. İkinci pasta veya çubukta çizilecek veri noktalarını içerir. Yalnızca okunabilir [PieSplitCustomPointCollection](../../com.aspose.slides/piesplitcustompointcollection).

**Döndürür:**
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate nesnesini döndürür. Yalnızca okunabilir IDOMObject.

**Döndürür:**
com.aspose.slides.IDOMObject

### getChart() {#getChart--}
```
public final IChart getChart()
```

Üst grafik nesnesini döndürür. Yalnızca okunabilir [IChart](../../com.aspose.slides/ichart).

**Döndürür:**
[IChart](../../com.aspose.slides/ichart)

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

FillFormat nesnesinin üst slaytını döndürür. Yalnızca okunabilir [BaseSlide](../../com.aspose.slides/baseslide).

**Döndürür:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

FillFormat nesnesinin üst sunumunu döndürür. Yalnızca okunabilir [IPresentation](../../com.aspose.slides/ipresentation).

**Döndürür:**
[IPresentation](../../com.aspose.slides/ipresentation)