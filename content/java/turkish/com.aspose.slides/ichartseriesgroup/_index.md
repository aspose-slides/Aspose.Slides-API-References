---
title: IChartSeriesGroup
second_title: Aspose.Slides için Java API Referansı
description: Seri grubunu temsil eder.
type: docs
url: /tr/com.aspose.slides/ichartseriesgroup/
---
**Tüm Uygulanmış Arayüzler:**
[com.aspose.slides.IChartComponent](../../com.aspose.slides/ichartcomponent)
```
public interface IChartSeriesGroup extends IChartComponent
```

Seri grubunu temsil eder.

--------------------

1) ChartSeriesGroupCollection sınıfı ve CombinableSeriesTypesGroup enum için özet ve açıklamalara bakın. 2) Seri grubu, gruptaki her seri için ortak olan bazı seri özellikleri içerir ("seri grup özellikleri"). ChartSeriesGroup sınıfındaki "seri grup özellikleri" okunur/yazılırdır. Her "seri grup özelliği" ChartSeries sınıfında salt okunur bir projeksiyona sahip olabilir.

## Metotlar

| Metot | Açıklama |
| --- | --- |
| [getType()](#getType--) | Bu seri grubunun bir tipini döndürür. |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | Bu grubun serilerinin ikincil eksende çizilip çizilmediğini gösterir. |
| [getSeries()](#getSeries--) | Grafik serilerinin salt okunur bir koleksiyonunu döndürür. |
| [get_Item(int index)](#get-Item-int-) | Belirtilen indeksteki öğeyi alır. |
| [getUpDownBars()](#getUpDownBars--) | Line veya Stock grafiğinin yukarı/aşağı çubuklarına erişim sağlar. |
| [getGapWidth()](#getGapWidth--) | Çubuk veya sütun kümeleri arasındaki boşluğu, çubuk veya sütun genişliğinin yüzde olarak belirtir. |
| [setGapWidth(int value)](#setGapWidth-int-) | Çubuk veya sütun kümeleri arasındaki boşluğu, çubuk veya sütun genişliğinin yüzde olarak belirtir. |
| [getGapDepth()](#getGapDepth--) | 3D grafikte veri serileri arasındaki mesafeyi, gösterge genişliğinin yüzde olarak döndürür veya ayarlar. |
| [setGapDepth(int value)](#setGapDepth-int-) | 3D grafikte veri serileri arasındaki mesafeyi, gösterge genişliğinin yüzde olarak döndürür veya ayarlar. |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | İlk pasta veya halka grafiği diliminin açısını dereceler cinsinden alır veya ayarlar (yukarıdan saat yönünde, 0’dan 360 dereceye). |
| [setFirstSliceAngle(int value)](#setFirstSliceAngle-int-) | İlk pasta veya halka grafiği diliminin açısını dereceler cinsinden alır veya ayarlar (yukarıdan saat yönünde, 0’dan 360 dereceye). |
| [isColorVaried()](#isColorVaried--) | Serideki her veri işaretçisinin farklı bir renge sahip olacağını belirtir. |
| [setColorVaried(boolean value)](#setColorVaried-boolean-) | Serideki her veri işaretçisinin farklı bir renge sahip olacağını belirtir. |
| [hasSeriesLines()](#hasSeriesLines--) | Grafik serileri çizgileri varsa doğru. |
| [setSeriesLines(boolean value)](#setSeriesLines-boolean-) | Grafik serileri çizgileri varsa doğru. |
| [getOverlap()](#getOverlap--) | 2D grafiklerde çubuk ve sütunların ne kadar üst üste geleceğini yüzde olarak belirtir (-100% ile 100% arasında). |
| [setOverlap(byte value)](#setOverlap-byte-) | 2D grafiklerde çubuk ve sütunların ne kadar üst üste geleceğini yüzde olarak belirtir (-100% ile 100% arasında). |
| [getSecondPieSize()](#getSecondPieSize--) | İlk pastanın boyutunun yüzde olarak ikinci pasta veya çubuk boyutunu belirtir (5 ile 200 yüzde arasında olabilir). |
| [setSecondPieSize(int value)](#setSecondPieSize-int-) | İlk pastanın boyutunun yüzde olarak ikinci pasta veya çubuk boyutunu belirtir (5 ile 200 yüzde arasında olabilir). |
| [getPieSplitPosition()](#getPieSplitPosition--) | Pie-of-pie veya bar-of-pie grafiğinde hangi veri noktalarının ikinci pasta veya çubukta olacağını belirlemek için kullanılacak bir değeri belirtir. |
| [setPieSplitPosition(double value)](#setPieSplitPosition-double-) | Pie-of-pie veya bar-of-pie grafiğinde hangi veri noktalarının ikinci pasta veya çubukta olacağını belirlemek için kullanılacak bir değeri belirtir. |
| [getPieSplitBy()](#getPieSplitBy--) | Pie-of-pie veya bar-of-pie grafiğinde hangi veri noktalarının ikinci pasta veya çubukta olacağını belirleme şeklini tanımlar. |
| [setPieSplitBy(int value)](#setPieSplitBy-int-) | Pie-of-pie veya bar-of-pie grafiğinde hangi veri noktalarının ikinci pasta veya çubukta olacağını belirleme şeklini tanımlar. |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | Özel bölünmeye sahip bir pie-of-pie veya bar-of-pie grafiği için özelleştirilmiş bölünme bilgisini içerir. |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | Halka grafiğindeki deliğin boyutunu belirtir (çizim alanının boyutunun %10 ile %90 arasında). |
| [setDoughnutHoleSize(byte value)](#setDoughnutHoleSize-byte-) | Halka grafiğindeki deliğin boyutunu belirtir (çizim alanının boyutunun %10 ile %90 arasında). |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | Balon grafiği için ölçek faktörünü belirtir (varsayılan boyutun %0 ile %300 arasında). |
| [setBubbleSizeScale(int value)](#setBubbleSizeScale-int-) | Balon grafiği için ölçek faktörünü belirtir (varsayılan boyutun %0 ile %300 arasında). |
| [getHiLowLinesFormat()](#getHiLowLinesFormat--) | HiLowLines biçimini belirtir. |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | Balon grafiğinde balon boyutu değerlerinin nasıl temsil edildiğini belirtir. |
| [setBubbleSizeRepresentation(int value)](#setBubbleSizeRepresentation-int-) | Balon grafiğinde balon boyutu değerlerinin nasıl temsil edildiğini belirtir. |

### getType() {#getType--}
```
public abstract int getType()
```

Bu seri grubunun bir tipini döndürür. Salt okunur [CombinableSeriesTypesGroup](../../com.aspose.slides/combinableseriestypesgroup).

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

Grafik serilerinin salt okunur bir koleksiyonunu döndürür. Salt okunur [IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection).

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

Line veya Stock grafiğinin yukarı/aşağı çubuklarına erişim sağlar. Salt okunur [IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager).

**Döndürür:**
[IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager)

### getGapWidth() {#getGapWidth--}
```
public abstract int getGapWidth()
```

Çubuk veya sütun kümeleri arasındaki boşluğu, çubuk veya sütun genişliğinin yüzde olarak belirtir. Okunur/yazılır int.

**Döndürür:**
int

### setGapWidth(int value) {#setGapWidth-int-}
```
public abstract void setGapWidth(int value)
```

Çubuk veya sütun kümeleri arasındaki boşluğu, çubuk veya sütun genişliğinin yüzde olarak belirtir. Okunur/yazılır int.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getGapDepth() {#getGapDepth--}
```
public abstract int getGapDepth()
```

3D grafikte veri serileri arasındaki mesafeyi, gösterge genişliğinin yüzde olarak döndürür veya ayarlar. Okunur/yazılır int.

**Döndürür:**
int

### setGapDepth(int value) {#setGapDepth-int-}
```
public abstract void setGapDepth(int value)
```

3D grafikte veri serileri arasındaki mesafeyi, gösterge genişliğinin yüzde olarak döndürür veya ayarlar. Okunur/yazılır int.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public abstract int getFirstSliceAngle()
```

İlk pasta veya halka grafiği diliminin açısını dereceler cinsinden alır veya ayarlar (yukarıdan saat yönünde, 0’dan 360 dereceye). Okunur/yazılır int.

**Döndürür:**
int

### setFirstSliceAngle(int value) {#setFirstSliceAngle-int-}
```
public abstract void setFirstSliceAngle(int value)
```

İlk pasta veya halka grafiği diliminin açısını dereceler cinsinden alır veya ayarlar (yukarıdan saat yönünde, 0’dan 360 dereceye). Okunur/yazılır int.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### isColorVaried() {#isColorVaried--}
```
public abstract boolean isColorVaried()
```

Serideki her veri işaretçisinin farklı bir renge sahip olacağını belirtir. Okunur/yazılır boolean.

**Döndürür:**
boolean

### setColorVaried(boolean value) {#setColorVaried-boolean-}
```
public abstract void setColorVaried(boolean value)
```

Serideki her veri işaretçisinin farklı bir renge sahip olacağını belirtir. Okunur/yazılır boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### hasSeriesLines() {#hasSeriesLines--}
```
public abstract boolean hasSeriesLines()
```

Grafikte seri çizgileri varsa doğru. Yığılmış çubuk ve OfPie grafiklerine uygulanır. Okunur/yazılır boolean.

**Döndürür:**
boolean

### setSeriesLines(boolean value) {#setSeriesLines-boolean-}
```
public abstract void setSeriesLines(boolean value)
```

Grafikte seri çizgileri varsa doğru. Yığılmış çubuk ve OfPie grafiklerine uygulanır. Okunur/yazılır boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getOverlap() {#getOverlap--}
```
public abstract byte getOverlap()
```

2D grafiklerde çubuk ve sütunların ne kadar üst üste geleceğini yüzde olarak belirtir (-100% ile 100% arasında). - -100%: Azami boşluk (çubuklar tamamen ayrılmış). - 0%: Çubuklar yan yana, üst üste gelmeden veya boşluk olmadan yer alır. - 100%: Azami üst üste binme (çubuklar tamamen birbiri üzerine gelir). Bu özellik okunur/yazılır byte.

> ```
> The following example demonstrates how to set the overlap for a chart series group 
>   and render the resulting chart on a form:
>   
>  Presentation pres = new Presentation();
>  try {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.ClusteredColumn, 10, 10, 600, 300);
>      IChartSeriesCollection series = chart.getChartData().getSeries();
>      series.get_Item(0).getParentSeriesGroup().setOverlap((byte)55); // Üst üste binmeyi %55 olarak ayarla
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

2D grafiklerde çubuk ve sütunların ne kadar üst üste geleceğini yüzde olarak belirtir (-100% ile 100% arasında). - -100%: Azami boşluk (çubuklar tamamen ayrılmış). - 0%: Çubuklar yan yana, üst üste gelmeden veya boşluk olmadan yer alır. - 100%: Azami üst üste binme (çubuklar tamamen birbiri üzerine gelir). Bu özellik okunur/yazılır byte.

> ```
> The following example demonstrates how to set the overlap for a chart series group 
>   and render the resulting chart on a form:
>   
>  Presentation pres = new Presentation();
>  try {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.ClusteredColumn, 10, 10, 600, 300);
>      IChartSeriesCollection series = chart.getChartData().getSeries();
>      series.get_Item(0).getParentSeriesGroup().setOverlap((byte)55); // Üst üste binmeyi %55 olarak ayarla
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

İlk pastanın boyutunun yüzde olarak ikinci pasta veya çubuğun boyutunu belirtir (5 ile 200 yüzde arasında olabilir). Okunur/yazılır int.

**Döndürür:**
int

### setSecondPieSize(int value) {#setSecondPieSize-int-}
```
public abstract void setSecondPieSize(int value)
```

İlk pastanın boyutunun yüzde olarak ikinci pasta veya çubuğun boyutunu belirtir (5 ile 200 yüzde arasında olabilir). Okunur/yazılır int.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getPieSplitPosition() {#getPieSplitPosition--}
```
public abstract double getPieSplitPosition()
```

Pie-of-pie veya bar-of-pie grafiğinde hangi veri noktalarının ikinci pasta veya çubukta olacağını belirlemek için kullanılacak bir değeri belirtir. PieSplitBy özelliği ile birlikte kullanılır. Okunur/yazılır double.

**Döndürür:**
double

### setPieSplitPosition(double value) {#setPieSplitPosition-double-}
```
public abstract void setPieSplitPosition(double value)
```

Pie-of-pie veya bar-of-pie grafiğinde hangi veri noktalarının ikinci pasta veya çubukta olacağını belirlemek için kullanılacak bir değeri belirtir. PieSplitBy özelliği ile birlikte kullanılır. Okunur/yazılır double.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | double |  |

### getPieSplitBy() {#getPieSplitBy--}
```
public abstract int getPieSplitBy()
```

Pie-of-pie veya bar-of-pie grafiğinde hangi veri noktalarının ikinci pasta veya çubukta olacağını belirleme şeklini belirtir. Okunur/yazılır [PieSplitType](../../com.aspose.slides/piesplittype).

**Döndürür:**
int

### setPieSplitBy(int value) {#setPieSplitBy-int-}
```
public abstract void setPieSplitBy(int value)
```

Pie-of-pie veya bar-of-pie grafiğinde hangi veri noktalarının ikinci pasta veya çubukta olacağını belirleme şeklini belirtir. Okunur/yazılır [PieSplitType](../../com.aspose.slides/piesplittype).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public abstract IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

Özel bölünmeye sahip bir pie-of-pie veya bar-of-pie grafiği için özelleştirilmiş bölünme bilgisini içerir. Pie-of-pie veya bar-of-pie grafiğinde ikinci pasta veya çubukta çizilecek veri noktalarını içerir. Salt okunur [IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection).

**Döndürür:**
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)

### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public abstract byte getDoughnutHoleSize()
```

Doughnut grafiğindeki deliğin boyutunu belirtir (çizim alanının boyutunun %10 ile %90 arasında olabilir). Okunur/yazılır byte.

**Döndürür:**
byte

### setDoughnutHoleSize(byte value) {#setDoughnutHoleSize-byte-}
```
public abstract void setDoughnutHoleSize(byte value)
```

Doughnut grafiğindeki deliğin boyutunu belirtir (çizim alanının boyutunun %10 ile %90 arasında olabilir). Okunur/yazılır byte.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |

### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public abstract int getBubbleSizeScale()
```

Balon grafiği için ölçek faktörünü belirtir (varsayılan boyutun %0 ile %300 arasında). Okunur/yazılır int.

**Döndürür:**
int

### setBubbleSizeScale(int value) {#setBubbleSizeScale-int-}
```
public abstract void setBubbleSizeScale(int value)
```

Balon grafiği için ölçek faktörünü belirtir (varsayılan boyutun %0 ile %300 arasında). Okunur/yazılır int.

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

Balon grafiğinde balon boyutu değerlerinin nasıl temsil edildiğini belirtir. Okunur/yazılır [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**Döndürür:**
int

### setBubbleSizeRepresentation(int value) {#setBubbleSizeRepresentation-int-}
```
public abstract void setBubbleSizeRepresentation(int value)
```

Balon grafiğinde balon boyutu değerlerinin nasıl temsil edildiğini belirtir. Okunur/yazılır [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |