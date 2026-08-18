---
title: IDataLabelCollection
second_title: Aspose.Slides için Java API Referansı
description: Bir serinin etiketlerini temsil eder.
type: docs
url: /tr/com.aspose.slides/idatalabelcollection/
---
**Tüm Uygulanan Arabirimler:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable, [com.aspose.slides.IChartComponent](../../com.aspose.slides/ichartcomponent)
```
public interface IDataLabelCollection extends System.Collections.Generic.IGenericEnumerable<IDataLabel>, IChartComponent
```

Bir seri etiketlerini temsil eder.
## Yöntemler

| Metot | Açıklama |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Belirtilen indeksli veri noktası için veri etiketini alır. |
| [getDefaultDataLabelFormat()](#getDefaultDataLabelFormat--) | Koleksiyondaki tüm veri etiketlerinin varsayılan biçimini döndürür. |
| [getLeaderLinesFormat()](#getLeaderLinesFormat--) | Veri etiketlerinin lider çizgi biçimini temsil eder. |
| [isVisible()](#isVisible--) | False, veri etiketinin varsayılan olarak görünür olmadığını (ve bu nedenle DefaultDataLabelFormat özelliğinin tüm Show*-bayraklarının (ShowValue, ...) false olduğunu) ifade eder. |
| [hide()](#hide--) | DefaultDataLabelFormat özelliğinin tüm Show*-bayraklarını (ShowValue, ...) false durumuna ayarlayarak veri etiketini varsayılan olarak gizli yapar. |
| [getCountOfVisibleDataLabels()](#getCountOfVisibleDataLabels--) | Koleksiyondaki görünen veri etiketlerinin sayısını alır. |
| [getCount()](#getCount--) | Koleksiyondaki tüm veri etiketlerinin sayısını alır. |
| [getParentSeries()](#getParentSeries--) | Üst (ana) grafik serisini döndürür. |
| [indexOf(IDataLabel value)](#indexOf-com.aspose.slides.IDataLabel-) | Koleksiyondaki belirtilen DataLabel'ın indeksini döndürür. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IDataLabel get_Item(int index)
```

Veri noktası için belirtilen indeks ile veri etiketini alır.

--------------------

Veri etiketine erişmenin alternatif yolu şudur: - getSeries().getDataPoints().get_Item(i).getLabel() - etiket özelliklerini yönet.

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

Koleksiyondaki tüm veri etiketlerinin varsayılan biçimini döndürür. Salt okunur [IDataLabelFormat](../../com.aspose.slides/idatalabelformat).

**Döndürür:**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
### getLeaderLinesFormat() {#getLeaderLinesFormat--}
```
public abstract IChartLinesFormat getLeaderLinesFormat()
```

Veri etiketlerinin lider çizgi biçimini temsil eder. Salt okunur [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

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

False, veri etiketinin varsayılan olarak görünür olmadığını (ve bu yüzden DefaultDataLabelFormat özelliğinin tüm Show*-bayraklarının (ShowValue, ...) false olduğunu) ifade eder. Salt okunur  boolean .

--------------------

Veri etiketi varsayılan olarak görünür ise Hide() yöntemiyle varsayılan olarak gizleyebilirsiniz. Ancak veri etiketi varsayılan olarak görünür değilse (IsVisible false ise) Show*-bayraklarını (ShowValue, ...) DefaultDataLabelFormat özelliğinde true durumuna ayarlayarak veri etiketini "varsayılan olarak görünür" yapabilirsiniz.

**Döndürür:**
boolean
### hide() {#hide--}
```
public abstract void hide()
```

DefaultDataLabelFormat özelliğinin tüm Show*-bayraklarını (ShowValue, ...) false durumuna ayarlayarak veri etiketini varsayılan olarak gizli yapar. Bu işlemden sonra IsVisible false olacaktır.

--------------------

Veri etiketi varsayılan olarak görünür değilse (IsVisible false ise) Show*-bayraklarını (ShowValue, ...) DefaultDataLabelFormat özelliğinde true durumuna ayarlayarak veri etiketini "varsayılan olarak görünür" yapabilirsiniz.

### getCountOfVisibleDataLabels() {#getCountOfVisibleDataLabels--}
```
public abstract int getCountOfVisibleDataLabels()
```

Koleksiyondaki görünen veri etiketlerinin sayısını alır. Salt okunur  int .

**Döndürür:**
int
### getCount() {#getCount--}
```
public abstract int getCount()
```

Koleksiyondaki tüm veri etiketlerinin sayısını alır. Salt okunur  int .

**Döndürür:**
int
### getParentSeries() {#getParentSeries--}
```
public abstract IChartSeries getParentSeries()
```

Üst (ana) grafik serisini döndürür. Salt okunur [IChartSeries](../../com.aspose.slides/ichartseries).

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