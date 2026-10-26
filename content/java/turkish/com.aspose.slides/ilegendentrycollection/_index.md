---
title: ILegendEntryCollection
second_title: Aspose.Slides için Java API Referansı
description: Efsane girişleri koleksiyonunu temsil eder.
type: docs
url: /tr/com.aspose.slides/ilegendentrycollection/
---```
public interface ILegendEntryCollection
```

Efsane girişleri koleksiyonunu temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Bu listedeki grafik türlerinden birine sahip olduğunda Chart.ChartData.Series[0].DataPoints[index] öğesine karşılık gelen efsane girişinin özelliklerini alır: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie; diğer grafik türleri için Chart.ChartData.Series[index] öğesine karşılık gelir. |
| [getCount()](#getCount--) | Koleksiyonda gerçekte bulunan öğelerin sayısını alır. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ILegendEntryProperties get_Item(int index)
```

Bu listedeki grafik türlerinden birine sahip olduğunda Chart.ChartData.Series[0].DataPoints[index] öğesine karşılık gelen efsane girişinin özelliklerini alır: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie; diğer grafik türleri için Chart.ChartData.Series[index] öğesine karşılık gelir.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int |  |

**Döndürür:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)
### getCount() {#getCount--}
```
public abstract int getCount()
```

Koleksiyonda gerçekte bulunan öğelerin sayısını alır. Salt-okunur int.

**Döndürür:**
int