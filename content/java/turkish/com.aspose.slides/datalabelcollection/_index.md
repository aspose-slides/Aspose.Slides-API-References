---
title: DataLabelCollection
second_title: Aspose.Slides için Java API Referansı
description: Seri etiketlerini temsil eder.
type: docs
url: /tr/com.aspose.slides/datalabelcollection/
---
**Kalıtım:**
java.lang.Object, com.aspose.slides.DomObject

**Uygulanan Tüm Arabirimler:**
[com.aspose.slides.IDataLabelCollection](../../com.aspose.slides/idatalabelcollection)
```
public class DataLabelCollection extends DomObject<ChartSeries> implements IDataLabelCollection
```

Seri etiketlerini temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getChart()](#getChart--) | Üst çizelgeyi döndürür. |
| [iterator()](#iterator--) | Koleksiyon içinde yineleme yapan bir enumerator döndürür. |
| [iteratorJava()](#iteratorJava--) | Tüm koleksiyon için bir java iterator döndürür. |
| [isVisible()](#isVisible--) | False, veri etiketinin varsayılan olarak görünür olmadığını gösterir (ve bu nedenle DefaultDataLabelFormat özelliğinin tüm Show*-bayrakları (ShowValue, ...) false olur). |
| [hide()](#hide--) | Veri etiketini varsayılan olarak gizlemek için DefaultDataLabelFormat özelliğinin tüm Show*-bayraklarını (ShowValue, ...) false duruma ayarlayın. |
| [getCountOfVisibleDataLabels()](#getCountOfVisibleDataLabels--) | Koleksiyondaki görünür veri etiketlerinin sayısını alır. |
| [getCount()](#getCount--) | Koleksiyondaki tüm veri etiketlerinin sayısını alır. |
| [getDefaultDataLabelFormat()](#getDefaultDataLabelFormat--) | Varsayılan veri etiketi biçimini alır. |
| [getLeaderLinesFormat()](#getLeaderLinesFormat--) | Veri etiketleri lider çizgi biçimini temsil eder. |
| [getParentSeries()](#getParentSeries--) | Üst seriyi alır. |
| [indexOf(IDataLabel value)](#indexOf-com.aspose.slides.IDataLabel-) | Koleksiyondaki belirtilen DataLabel'ın indeksini döndürür. |
| [get_Item(int index)](#get-Item-int-) | Belirtilen indekse sahip veri noktası için veri etiketini alır. |
| [getDefaultLabelShapeType()](#getDefaultLabelShapeType--) | Veri etiketleri için varsayılan şekil tipini alır veya ayarlar. |
| [setDefaultLabelShapeType(int value)](#setDefaultLabelShapeType-int-) | Veri etiketleri için varsayılan şekil tipini alır veya ayarlar. |
| [getSlide()](#getSlide--) | FillFormat'un üst slaytını döndürür. |
| [getPresentation()](#getPresentation--) | FillFormat'un üst sunumunu döndürür. |
### getChart() {#getChart--}
```
public final IChart getChart()
```

Üst çizelgeyi döndürür. Salt okunur [IChart](../../com.aspose.slides/ichart).

**Döndürür:**
[IChart](../../com.aspose.slides/ichart)
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IDataLabel> iterator()
```

Koleksiyon içinde yineleme yapan bir enumerator döndürür.

**Döndürür:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDataLabel> - Koleksiyon içinde yineleme yapmak için kullanılabilen bir IGenericEnumerator.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IDataLabel> iteratorJava()
```

Tüm koleksiyon için bir java iterator döndürür.

**Döndürür:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDataLabel> - Tüm koleksiyon için bir java.util.Iterator.
### isVisible() {#isVisible--}
```
public final boolean isVisible()
```

False, veri etiketinin varsayılan olarak görünür olmadığını gösterir (ve bu nedenle DefaultDataLabelFormat özelliğinin tüm Show*-bayrakları (ShowValue, ...) false olur). Salt okunur boolean.

--------------------

Veri etiketi varsayılan olarak görünürse, Hide() yöntemiyle varsayılan olarak gizleyebilirsiniz. Ancak veri etiketi varsayılan olarak görünür değilse (IsVisible false ise), DefaultDataLabelFormat özelliğinin Show*-bayraklarını (ShowValue, ...) true duruma ayarlayarak veri etiketini "varsayılan olarak görünür" yapabilirsiniz.

**Döndürür:**
boolean
### hide() {#hide--}
```
public final void hide()
```

Veri etiketini varsayılan olarak gizlemek için DefaultDataLabelFormat özelliğinin tüm Show*-bayraklarını (ShowValue, ...) false durumuna ayarlayın. Bu işlemden sonra IsVisible false olacaktır.

--------------------

Veri etiketi varsayılan olarak görünür değilse (IsVisible false ise), DefaultDataLabelFormat özelliğinin Show*-bayraklarını (ShowValue, ...) true duruma ayarlayarak veri etiketini "varsayılan olarak görünür" yapabilirsiniz.

### getCountOfVisibleDataLabels() {#getCountOfVisibleDataLabels--}
```
public final int getCountOfVisibleDataLabels()
```

Koleksiyondaki görünür veri etiketlerinin sayısını alır. Salt okunur int.

**Döndürür:**
int
### getCount() {#getCount--}
```
public final int getCount()
```

Koleksiyondaki tüm veri etiketlerinin sayısını alır. Salt okunur int.

**Döndürür:**
int
### getDefaultDataLabelFormat() {#getDefaultDataLabelFormat--}
```
public final IDataLabelFormat getDefaultDataLabelFormat()
```

Varsayılan veri etiketi biçimini alır. Salt okunur [IDataLabelFormat](../../com.aspose.slides/idatalabelformat).

**Döndürür:**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
### getLeaderLinesFormat() {#getLeaderLinesFormat--}
```
public final IChartLinesFormat getLeaderLinesFormat()
```

Veri etiketleri lider çizgi biçimini temsil eder. Salt okunur [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IChart chart = (IChart) pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IChartSeriesCollection series = chart.getChartData().getSeries();
>      IDataLabelCollection labels = series.get_Item(0).getLabels();
>      labels.getLeaderLinesFormat().getLine().getFillFormat().setFillType(FillType.Solid);
>      labels.getLeaderLinesFormat().getLine().getFillFormat().getSolidFillColor().setColor(new java.awt.Color(255, 0, 0, 255));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Döndürür:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)
### getParentSeries() {#getParentSeries--}
```
public final IChartSeries getParentSeries()
```

Üst seriyi alır. Salt okunur [IChartSeries](../../com.aspose.slides/ichartseries).

**Döndürür:**
[IChartSeries](../../com.aspose.slides/ichartseries)
### indexOf(IDataLabel value) {#indexOf-com.aspose.slides.IDataLabel-}
```
public final int indexOf(IDataLabel value)
```

Koleksiyondaki belirtilen DataLabel'ın indeksini döndürür.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IDataLabel](../../com.aspose.slides/idatalabel) | Bulunacak DataLabel. |

**Döndürür:**
int - DataLabel'ın indeksi veya DataLabel bu koleksiyona ait değilse -1.
### get_Item(int index) {#get-Item-int-}
```
public final IDataLabel get_Item(int index)
```

Belirtilen indeksli veri noktası için veri etiketini alır.

--------------------

Veri etiketine erişmenin alternatif yolu: - series.getDataPoints().get_Item(i).getLabel() - etiket özelliklerini yönetin.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int |  |

**Döndürür:**
[IDataLabel](../../com.aspose.slides/idatalabel)
### getDefaultLabelShapeType() {#getDefaultLabelShapeType--}
```
public final int getDefaultLabelShapeType()
```

Veri etiketleri için varsayılan şekil tipini alır veya ayarlar. Şekil tanımlı değilse [ShapeType.NotDefined](../../com.aspose.slides/shapetype\#NotDefined) döndürür.

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(1);
>      IChartSeries firstSeries = chart.getChartData().getSeries().get_Item(0);
>      // İlk serideki tüm veri etiketlerinin şekil tipini Ellipse olarak ayarlayın.
>      firstSeries.getLabels().setDefaultLabelShapeType(ShapeType.Ellipse);
>      pres.save("ChartWithEllipseLabels.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

Bu özelliği ayarlamak, koleksiyondaki tüm veri etiketlerinin IDataLabel.LabelShapeType ([IDataLabel.getLabelShapeType](../../com.aspose.slides/idatalabel\#getLabelShapeType)/[IDataLabel.setLabelShapeType(int)](../../com.aspose.slides/idatalabel\#setLabelShapeType-int-)) özelliğini aynı değere de ayarlar.

**Döndürür:**
int
### setDefaultLabelShapeType(int value) {#setDefaultLabelShapeType-int-}
```
public final void setDefaultLabelShapeType(int value)
```

Veri etiketleri için varsayılan şekil tipini alır veya ayarlar. Şekil tanımlı değilse [ShapeType.NotDefined](../../com.aspose.slides/shapetype\#NotDefined) döndürür.

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(1);
>      IChartSeries firstSeries = chart.getChartData().getSeries().get_Item(0);
>      // İlk serideki tüm veri etiketlerinin şekil tipini Ellipse olarak ayarlayın.
>      firstSeries.getLabels().setDefaultLabelShapeType(ShapeType.Ellipse);
>      pres.save("ChartWithEllipseLabels.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

Bu özelliği ayarlamak, koleksiyondaki tüm veri etiketlerinin IDataLabel.LabelShapeType ([IDataLabel.getLabelShapeType](../../com.aspose.slides/idatalabel\#getLabelShapeType)/[IDataLabel.setLabelShapeType(int)](../../com.aspose.slides/idatalabel\#setLabelShapeType-int-)) özelliğini aynı değere de ayarlar.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

FillFormat'un üst slaytını döndürür. Salt okunur [BaseSlide](../../com.aspose.slides/baseslide).

**Döndürür:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

FillFormat'un üst sunumunu döndürür. Salt okunur [IPresentation](../../com.aspose.slides/ipresentation).

**Döndürür:**
[IPresentation](../../com.aspose.slides/ipresentation)