---
title: ILegendEntryCollection
second_title: Aspose.Slides Android için Java API Referansı
description: Lejant koleksiyonunu temsil eder.
type: docs
url: /tr/com.aspose.slides/ilegendentrycollection/
---```
public interface ILegendEntryCollection
```

Lejant koleksiyonunu temsil eder.
## Yöntemler

| Metot | Açıklama |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Bu listedeki grafik türlerinden biri olduğunda Chart.ChartData.Series[0].DataPoints[index] öğesine karşılık gelen lejant girdisinin özelliklerini alır: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie; diğer grafik türleri için ise Chart.ChartData.Series[index] öğesine karşılık gelir. |
| [getCount()](#getCount--) | Koleksiyon içinde gerçekten bulunan eleman sayısını alır. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ILegendEntryProperties get_Item(int index)
```

Bu listedeki grafik türlerinden biri olduğunda Chart.ChartData.Series[0].DataPoints[index] öğesine karşılık gelen lejant girdisinin özelliklerini alır: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie; diğer grafik türleri için ise Chart.ChartData.Series[index] öğesine karşılık gelir.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**Döndürür:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)
### getCount() {#getCount--}
```
public abstract int getCount()
```

Koleksiyon içinde gerçekten bulunan eleman sayısını alır. Yalnızca okuma int.

**Döndürür:**
int