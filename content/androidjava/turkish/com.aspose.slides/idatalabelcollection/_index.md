---
title: IDataLabelCollection
second_title: Java API Referansı aracılığıyla Android için Aspose.Slides
description: Seri etiketlerini temsil eder.
type: docs
url: /tr/com.aspose.slides/idatalabelcollection/
---
**Uygulanan Tüm Arabirimler:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable, [com.aspose.slides.IChartComponent](../../com.aspose.slides/ichartcomponent)
```
public interface IDataLabelCollection extends System.Collections.Generic.IGenericEnumerable<IDataLabel>, IChartComponent
```

Bir seri etiketlerini temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Belirtilen indeksle veri noktasının veri etiketini alır. |
| [getDefaultDataLabelFormat()](#getDefaultDataLabelFormat--) | Koleksiyondaki tüm veri etiketlerinin varsayılan biçimini döndürür. |
| [getLeaderLinesFormat()](#getLeaderLinesFormat--) | Veri etiketleri lider çizgi biçimini temsil eder. |
| [isVisible()](#isVisible--) | False, veri etiketinin varsayılan olarak görünür olmadığını (ve bu yüzden DefaultDataLabelFormat özelliğinin tüm Show*-bayrakları (ShowValue, ...) yanlıştır) ifade eder. |
| [hide()](#hide--) | DefaultDataLabelFormat özelliğinin tüm Show*-bayraklarını (ShowValue, ...) false durumuna ayarlayarak veri etiketini varsayılan olarak gizli yap. |
| [getCountOfVisibleDataLabels()](#getCountOfVisibleDataLabels--) | Koleksiyondaki görünen veri etiketlerinin sayısını alır. |
| [getCount()](#getCount--) | Koleksiyondaki tüm veri etiketlerinin sayısını alır. |
| [getParentSeries()](#getParentSeries--) | Üst grafik serisini döndürür. |
| [indexOf(IDataLabel value)](#indexOf-com.aspose.slides.IDataLabel-) | Koleksiyondaki belirtilen DataLabel'in indeksini döndürür. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IDataLabel get_Item(int index)
```


Belirtilen indeksle veri noktasının veri etiketini alır.

--------------------

Veri etiketine erişmenin alternatif yolu: - getSeries().getDataPoints().get_Item(i).getLabel() - etiket özelliklerini yönetin.

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


Koleksiyondaki tüm veri etiketlerinin varsayılan biçimini döndürür. Yalnızca okuma [IDataLabelFormat](../../com.aspose.slides/idatalabelformat).

**Döndürür:**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
### getLeaderLinesFormat() {#getLeaderLinesFormat--}
```
public abstract IChartLinesFormat getLeaderLinesFormat()
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
### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```


False, veri etiketinin varsayılan olarak görünür olmadığını (ve bu yüzden DefaultDataLabelFormat özelliğinin tüm Show*-bayrakları (ShowValue, ...) false) ifade eder. Yalnızca okuma  boolean .

--------------------

Veri etiketi varsayılan olarak görünür ise, Hide() yöntemiyle varsayılan olarak gizleyebilirsiniz. Ancak veri etiketi varsayılan olarak görünür değilse (IsVisible false), Show*-bayraklarını (ShowValue, ...) DefaultDataLabelFormat özelliğinde true durumuna ayarlayarak veri etiketini "varsayılan olarak görünür" yapabilirsiniz.

**Döndürür:**
boolean
### hide() {#hide--}
```
public abstract void hide()
```


DefaultDataLabelFormat özelliğinin tüm Show*-bayraklarını (ShowValue, ...) false durumuna ayarlayarak veri etiketini varsayılan olarak gizli yapın. Bu işlemden sonra IsVisible false olacaktır.

--------------------

Veri etiketi varsayılan olarak görünür değilse (IsVisible false), Show*-bayraklarını (ShowValue, ...) DefaultDataLabelFormat özelliğinde true durumuna ayarlayarak veri etiketini "varsayılan olarak görünür" yapabilirsiniz.

### getCountOfVisibleDataLabels() {#getCountOfVisibleDataLabels--}
```
public abstract int getCountOfVisibleDataLabels()
```


Koleksiyondaki görünen veri etiketlerinin sayısını alır. Yalnızca okuma  int .

**Döndürür:**
int
### getCount() {#getCount--}
```
public abstract int getCount()
```


Koleksiyondaki tüm veri etiketlerinin sayısını alır. Yalnızca okuma  int .

**Döndürür:**
int
### getParentSeries() {#getParentSeries--}
```
public abstract IChartSeries getParentSeries()
```


Üst grafik serisini döndürür. Yalnızca okuma [IChartSeries](../../com.aspose.slides/ichartseries).

**Döndürür:**
[IChartSeries](../../com.aspose.slides/ichartseries)
### indexOf(IDataLabel value) {#indexOf-com.aspose.slides.IDataLabel-}
```
public abstract int indexOf(IDataLabel value)
```


Koleksiyondaki belirtilen DataLabel'in indeksini döndürür.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IDataLabel](../../com.aspose.slides/idatalabel) | Bulunacak DataLabel. |

**Döndürür:**
int - Bir DataLabel'in indeksi veya DataLabel bu koleksiyona ait değilse -1.