---
title: IChartSeriesGroupCollection
second_title: Aspose.Slides Java API Referansı
description: Birleştirilebilir serilerin gruplarının koleksiyonunu temsil eder.
type: docs
url: /tr/com.aspose.slides/ichartseriesgroupcollection/
---
**Tüm Uygulanan Arayüzler:**
com.aspose.slides.IGenericCollection
```
public interface IChartSeriesGroupCollection extends IGenericCollection<IChartSeriesGroup>
```

Birleştirilebilir serilerin gruplarının koleksiyonunu temsil eder.

--------------------

1) Her seri grubu, birleştirilebilir türde serileri içerir. Birleştirilebilir seri türlerinin grupları, CombinableSeriesTypesGroup enum’u ile tanımlanır ve açıklanır. Ayrıca her seri grubu, serilerin birincil eksende ya da ikincil eksende (aynı grupta her iki durumda da değil) çizilmesini sağlar. Bu nedenle seri gruplandırma prensibi, yukarıda belirtilen tür gruplarına ve birincil/ikincil çizim tipine göre bir gruplamadır. 2) Seri grubu, grup içindeki her seriye ortak olan bazı seri özelliklerini ("series group properties") içerir. ChartSeriesGroup sınıfındaki "Series group properties" okuma/yazma (read/write) özelliktedir. "Series group properties" öğelerinin her biri, ChartSeries sınıfında yalnızca okunabilen (read-only) bir projeksiyona sahip olabilir.

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [get_Item(IChartSeries ofSeries)](#get-Item-com.aspose.slides.IChartSeries-) | Seriye göre seri grubunu alır. |
| [get_Item(int index)](#get-Item-int-) | İndexe göre seri grubunu alır. |
### get_Item(IChartSeries ofSeries) {#get-Item-com.aspose.slides.IChartSeries-}
```
public abstract IChartSeriesGroup get_Item(IChartSeries ofSeries)
```

Seriye göre seri grubunu alır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ofSeries | [IChartSeries](../../com.aspose.slides/ichartseries) |  |

**Dönüş Değeri:**
[IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup)
### get_Item(int index) {#get-Item-int-}
```
public abstract IChartSeriesGroup get_Item(int index)
```

İndexe göre seri grubunu alır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int |  |

**Dönüş Değeri:**
[IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup)