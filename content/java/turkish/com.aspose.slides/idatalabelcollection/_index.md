---
title: IDataLabelCollection
second_title: Aspose.Slides for Java API Referansı
description: Bir seri etiketini temsil eder.
type: docs
url: /tr/com.aspose.slides/idatalabelcollection/
---
**Tüm Uygulanan Arayüzler:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable, [com.aspose.slides.IChartComponent](../../com.aspose.slides/ichartcomponent)
```
public interface IDataLabelCollection extends System.Collections.Generic.IGenericEnumerable<IDataLabel>, IChartComponent
```

Bir seri etiketini temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Belirtilen dizine sahip veri noktasının veri etiketini alır. |
| [getDefaultDataLabelFormat()](#getDefaultDataLabelFormat--) | Koleksiyondaki tüm veri etiketlerinin varsayılan biçimini döndürür. |
| [getLeaderLinesFormat()](#getLeaderLinesFormat--) | Veri etiketleri lider çizgi biçimini temsil eder. |
| [isVisible()](#isVisible--) | False, veri etiketinin varsayılan olarak görünür olmadığını (ve bu nedenle DefaultDataLabelFormat özelliğinin tüm Show*-bayraklarının (ShowValue, ...) false olduğunu) ifade eder. |
| [hide()](#hide--) | Veri etiketi varsayılan olarak gizlemek için DefaultDataLabelFormat özelliğinin tüm Show*-bayraklarını (ShowValue, ...) false duruma ayarlayın. |
| [getCountOfVisibleDataLabels()](#getCountOfVisibleDataLabels--) | Koleksiyondaki görünen veri etiketlerinin sayısını alır. |
| [getCount()](#getCount--) | Koleksiyondaki tüm veri etiketlerinin sayısını alır. |
| [getParentSeries()](#getParentSeries--) | Üst grafik serisini döndürür. |
| [indexOf(IDataLabel value)](#indexOf-com.aspose.slides.IDataLabel-) | Koleksiyondaki belirtilen DataLabel'ın indeksini döndürür. |
| [getDefaultLabelShapeType()](#getDefaultLabelShapeType--) | Veri etiketleri için varsayılan şekil türünü alır veya ayarlar. |
| [setDefaultLabelShapeType(int value)](#setDefaultLabelShapeType-int-) | Veri etiketleri için varsayılan şekil türünü alır veya ayarlar. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IDataLabel get_Item(int index)
```


Belirtilen dizine sahip veri noktasının veri etiketini alır.

--------------------

Veri etiketine erişmenin alternatif yolu şudur:
- getSeries().getDataPoints().get_Item(i).getLabel()
- etiket özelliklerini yönet.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int |  |

**Döndürür:**
[IDataLabel](../../com.aspose.slides/idatalabel)
### getDefaultDataLabelFormat() {#getDefaultDataLabelFormat--}
```
public abstract IDataLabelFormat getDefaultDataLabelFormat()
```


Koleksiyondaki tüm veri etiketlerinin varsayılan biçimini döndürür. Yalnızca okunabilir [IDataLabelFormat](../../com.aspose.slides/idatalabelformat).

**Döndürür:**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
### getLeaderLinesFormat() {#getLeaderLinesFormat--}
```
public abstract IChartLinesFormat getLeaderLinesFormat()
```


Veri etiketleri lider çizgi biçimini temsil eder. Yalnızca okunabilir [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

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
### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```


False, veri etiketinin varsayılan olarak görünür olmadığını (ve bu nedenle DefaultDataLabelFormat özelliğinin tüm Show*-bayraklarının (ShowValue, ...) false olduğunu) ifade eder. Yalnızca okunabilir boolean .

Veri etiketi varsayılan olarak görünürse, Hide() metodu ile varsayılan olarak gizleyebilirsiniz. Ancak veri etiketi varsayılan olarak görünür değilse (IsVisible false) Show*-bayraklarını (ShowValue, ...) DefaultDataLabelFormat özelliğinde true duruma ayarlayarak veri etiketini "varsayılan olarak görünür" yapabilirsiniz.

**Döndürür:**
boolean
### hide() {#hide--}
```
public abstract void hide()
```


DefaultDataLabelFormat özelliğinin tüm Show*-bayraklarını (ShowValue, ...) false duruma ayarlayarak veri etiketini varsayılan olarak gizleyin. Bu işlemden sonra IsVisible false olur.

Veri etiketi varsayılan olarak görünür değilse (IsVisible false) Show*-bayraklarını (ShowValue, ...) DefaultDataLabelFormat özelliğinde true duruma ayarlayarak veri etiketini "varsayılan olarak görünür" yapabilirsiniz.

### getCountOfVisibleDataLabels() {#getCountOfVisibleDataLabels--}
```
public abstract int getCountOfVisibleDataLabels()
```


Koleksiyondaki görünen veri etiketlerinin sayısını alır. Yalnızca okunabilir int .

**Döndürür:**
int
### getCount() {#getCount--}
```
public abstract int getCount()
```


Koleksiyondaki tüm veri etiketlerinin sayısını alır. Yalnızca okunabilir int .

**Döndürür:**
int
### getParentSeries() {#getParentSeries--}
```
public abstract IChartSeries getParentSeries()
```


Üst grafik serisini döndürür. Yalnızca okunabilir [IChartSeries](../../com.aspose.slides/ichartseries).

**Döndürür:**
[IChartSeries](../../com.aspose.slides/ichartseries)
### indexOf(IDataLabel value) {#indexOf-com.aspose.slides.IDataLabel-}
```
public abstract int indexOf(IDataLabel value)
```


Koleksiyondaki belirtilen DataLabel'ın indeksini döndürür.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IDataLabel](../../com.aspose.slides/idatalabel) | Bulunacak DataLabel. |

**Döndürür:**
int - Bir DataLabel'ın indeksi veya DataLabel bu koleksiyondan değilse -1.
### getDefaultLabelShapeType() {#getDefaultLabelShapeType--}
```
public abstract int getDefaultLabelShapeType()
```


Veri etiketleri için varsayılan şekil türünü alır veya ayarlar. Şekil tanımlı değilse [ShapeType.NotDefined](../../com.aspose.slides/shapetype\#NotDefined) döndürür.

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(1);
>      IChartSeries firstSeries = chart.getChartData().getSeries().get_Item(0);
>      // İlk serideki tüm veri etiketlerinin şekil tipini Elips olarak ayarla.
>      firstSeries.getLabels().setDefaultLabelShapeType(ShapeType.Ellipse);
>      pres.save("ChartWithEllipseLabels.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

Bu özelliği ayarlamak, koleksiyondaki tüm veri etiketlerinin IDataLabel.LabelShapeType ([IDataLabel.getLabelShapeType](../../com.aspose.slides/idatalabel\#getLabelShapeType)/[IDataLabel.setLabelShapeType(int)](../../com.aspose.slides/idatalabel\#setLabelShapeType-int-)) özelliğini aynı değere ayarlar.

**Döndürür:**
int
### setDefaultLabelShapeType(int value) {#setDefaultLabelShapeType-int-}
```
public abstract void setDefaultLabelShapeType(int value)
```


Veri etiketleri için varsayılan şekil türünü alır veya ayarlar. Şekil tanımlı değilse [ShapeType.NotDefined](../../com.aspose.slides/shapetype\#NotDefined) döndürür.

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(1);
>      IChartSeries firstSeries = chart.getChartData().getSeries().get_Item(0);
>      // İlk serideki tüm veri etiketlerinin şekil tipini Elips olarak ayarla.
>      firstSeries.getLabels().setDefaultLabelShapeType(ShapeType.Ellipse);
>      pres.save("ChartWithEllipseLabels.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

Bu özelliği ayarlamak, koleksiyondaki tüm veri etiketlerinin IDataLabel.LabelShapeType ([IDataLabel.getLabelShapeType](../../com.aspose.slides/idatalabel\#getLabelShapeType)/[IDataLabel.setLabelShapeType(int)](../../com.aspose.slides/idatalabel\#setLabelShapeType-int-)) özelliğini aynı değere ayarlar.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |