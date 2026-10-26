---
title: DataLabelCollection
second_title: Aspose.Slides for Android via Java API Referansı
description: Seri etiketlerini temsil eder.
type: docs
url: /tr/com.aspose.slides/datalabelcollection/
---
**Kalıtım:**
java.lang.Object, com.aspose.slides.DomObject

**Uygulanan Tüm Arayüzler:**
[com.aspose.slides.IDataLabelCollection](../../com.aspose.slides/idatalabelcollection)
```
public class DataLabelCollection extends DomObject<ChartSeries> implements IDataLabelCollection
```

Seri etiketlerini temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getChart()](#getChart--) | Üst grafiği döndürür. |
| [iterator()](#iterator--) | Koleksiyonu yineleyen bir enumerator döndürür. |
| [iteratorJava()](#iteratorJava--) | Tüm koleksiyon için bir Java iteratorü döndürür. |
| [isVisible()](#isVisible--) | False, veri etiketinin varsayılan olarak görünmez olduğu anlamına gelir (bu nedenle DefaultDataLabelFormat özelliğinin tüm Show*-bayrakları (ShowValue, ...) false olur). |
| [hide()](#hide--) | DefaultDataLabelFormat özelliğinin tüm Show*-bayraklarını (ShowValue, ...) false duruma ayarlayarak veri etiketini varsayılan olarak gizli yapar. |
| [getCountOfVisibleDataLabels()](#getCountOfVisibleDataLabels--) | Koleksiyondaki görünür veri etiketlerinin sayısını alır. |
| [getCount()](#getCount--) | Koleksiyondaki tüm veri etiketlerinin sayısını alır. |
| [getDefaultDataLabelFormat()](#getDefaultDataLabelFormat--) | Varsayılan veri etiketi biçimini alır. |
| [getLeaderLinesFormat()](#getLeaderLinesFormat--) | Veri etiketleri lider çizgi biçimini temsil eder. |
| [getParentSeries()](#getParentSeries--) | Üst seriyi alır. |
| [indexOf(IDataLabel value)](#indexOf-com.aspose.slides.IDataLabel-) | Belirtilen DataLabel'ın koleksiyondaki indeksini döndürür. |
| [get_Item(int index)](#get-Item-int-) | Belirtilen indekse sahip veri noktasının veri etiketini alır. |
| [getSlide()](#getSlide--) | FillFormat'un üst slaytını döndürür. |
| [getPresentation()](#getPresentation--) | FillFormat'un üst sunumunu döndürür. |
### getChart() {#getChart--}
```
public final IChart getChart()
```


Üst grafiği döndürür. Yalnızca okuma [IChart](../../com.aspose.slides/ichart).

**Döndürür:**
[IChart](../../com.aspose.slides/ichart)
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IDataLabel> iterator()
```


Koleksiyonu yineleyen bir enumerator döndürür.

**Döndürür:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDataLabel> - Koleksiyonu yinelemek için kullanılabilen bir IGenericEnumerator.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IDataLabel> iteratorJava()
```


Tüm koleksiyon için bir Java iteratorü döndürür.

**Döndürür:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDataLabel> - java.util.Iterator for the entire collection.
### isVisible() {#isVisible--}
```
public final boolean isVisible()
```


False, veri etiketinin varsayılan olarak görünmez olduğu anlamına gelir (bu nedenle DefaultDataLabelFormat özelliğinin tüm Show*-bayrakları (ShowValue, ...) false olur). Yalnızca okuma boolean.

--------------------

Eğer veri etiketi varsayılan olarak görünürse, Hide() yöntemiyle varsayılan olarak gizli yapabilirsiniz. Ancak veri etiketi varsayılan olarak görünür değilse (IsVisible false) Show*-bayraklarını (ShowValue, ...) DefaultDataLabelFormat özelliğinde true duruma ayarlayarak veri etiketini “varsayılan olarak görünür” hâle getirebilirsiniz.

**Döndürür:**
boolean
### hide() {#hide--}
```
public final void hide()
```


DefaultDataLabelFormat özelliğinin tüm Show*-bayraklarını (ShowValue, ...) false duruma ayarlayarak veri etiketini varsayılan olarak gizli yapar. Bu işlemden sonra IsVisible false olur.

--------------------

Eğer veri etiketi varsayılan olarak görünmez (IsVisible false) ise Show*-bayraklarını (ShowValue, ...) DefaultDataLabelFormat özelliğinde true duruma ayarlayarak veri etiketini “varsayılan olarak görünür” hâle getirebilirsiniz.

### getCountOfVisibleDataLabels() {#getCountOfVisibleDataLabels--}
```
public final int getCountOfVisibleDataLabels()
```


Koleksiyondaki görünür veri etiketlerinin sayısını alır. Yalnızca okuma int.

**Döndürür:**
int
### getCount() {#getCount--}
```
public final int getCount()
```


Koleksiyondaki tüm veri etiketlerinin sayısını alır. Yalnızca okuma int.

**Döndürür:**
int
### getDefaultDataLabelFormat() {#getDefaultDataLabelFormat--}
```
public final IDataLabelFormat getDefaultDataLabelFormat()
```


Varsayılan veri etiketi biçimini alır. Yalnızca okuma [IDataLabelFormat](../../com.aspose.slides/idatalabelformat).

**Döndürür:**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
### getLeaderLinesFormat() {#getLeaderLinesFormat--}
```
public final IChartLinesFormat getLeaderLinesFormat()
```


Veri etiketleri lider çizgi biçimini temsil eder. Yalnızca okuma [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

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
>      labels.getLeaderLinesFormat().getLine().getFillFormat().getSolidFillColor().setColor(Color.RED);
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


Üst seriyi alır. Yalnızca okuma [IChartSeries](../../com.aspose.slides/ichartseries).

**Döndürür:**
[IChartSeries](../../com.aspose.slides/ichartseries)
### indexOf(IDataLabel value) {#indexOf-com.aspose.slides.IDataLabel-}
```
public final int indexOf(IDataLabel value)
```


Belirtilen DataLabel'ın koleksiyondaki indeksini döndürür.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IDataLabel](../../com.aspose.slides/idatalabel) | Bulunacak DataLabel. |

**Döndürür:**
int - DataLabel'ın indeksi veya DataLabel bu koleksiyondan gelmiyorsa -1.
### get_Item(int index) {#get-Item-int-}
```
public final IDataLabel get_Item(int index)
```


Belirtilen indekse sahip veri noktasının veri etiketini alır.

--------------------

Veri etiketine erişmenin alternatif yolu şudur: - series.getDataPoints().get_Item(i).getLabel() - etiket özelliklerini yönet.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int |  |

**Döndürür:**
[IDataLabel](../../com.aspose.slides/idatalabel)
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```


FillFormat'un üst slaytını döndürür. Yalnızca okuma [BaseSlide](../../com.aspose.slides/baseslide).

**Döndürür:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```


FillFormat'un üst sunumunu döndürür. Yalnızca okuma [IPresentation](../../com.aspose.slides/ipresentation).

**Döndürür:**
[IPresentation](../../com.aspose.slides/ipresentation)