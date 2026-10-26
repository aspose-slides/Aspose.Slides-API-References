---
title: IChartSeriesGroupCollection
second_title: Aspose.Slides Android için Java API Referansı
description: Birleştirilebilir serilerin gruplarının koleksiyonunu temsil eder.
type: docs
url: /tr/com.aspose.slides/ichartseriesgroupcollection/
---
**Uygulanan Tüm Arabirimler:**
com.aspose.slides.IGenericCollection
```
public interface IChartSeriesGroupCollection extends IGenericCollection<IChartSeriesGroup>
```

Birleştirilebilir serilerin gruplarının koleksiyonunu temsil eder.

--------------------

1) Her seri grubu, birleştirilebilir türlere sahip serileri içerir. Birleştirilebilir seri türleri grupları, CombinableSeriesTypesGroup enum ile tanımlanır ve açıklanır. Ayrıca her seri grubu, birincil eksenlerde ya da ikincil eksenlerde (her iki durumda bir grup içinde değil) çizilen serileri içerir. Bu nedenle, seri gruplandırma prensibi, yukarıda bahsedilen tür gruplarına ve birincil/ikincil çizim tipine göre gruplamadır. 2) Seri grubu, gruptaki her seri için ortak olan bazı seri özelliklerine sahiptir ("seri grup özellikleri"). ChartSeriesGroup sınıfındaki "seri grup özellikleri" okuma/yazma özelliktedir. "Seri grup özellikleri"nin her biri, ChartSeries sınıfında yalnızca okuma için bir projeksiyona sahip olabilir.
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

**Döndürür:**
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

**Döndürür:**
[IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup)