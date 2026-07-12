---
title: LegendEntryCollection
second_title: Aspose.Slides for Android üzerinden Java API Referansı
description: Gösterge öğeleri koleksiyonunu temsil eder.
type: docs
url: /tr/com.aspose.slides/legendentrycollection/
---
**Kalıtım:**
java.lang.Object

**Uygulanan Tüm Arayüzler:**
[com.aspose.slides.ILegendEntryCollection](../../com.aspose.slides/ilegendentrycollection)
```
public class LegendEntryCollection implements ILegendEntryCollection
```

Gösterge öğeleri koleksiyonunu temsil eder.
## Metotlar

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Bu listedeki bir grafik türü durumunda Chart.ChartData.Series[0].DataPoints[index] öğesine karşılık gelen gösterge girdisinin özelliklerini alır: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie; veya diğer grafik türleri için Chart.ChartData.Series[index] öğesine karşılık gelir. |
| [getCount()](#getCount--) | Gösterge girdilerinin sayısını alır. |
### get_Item(int index) {#get-Item-int-}
```
public final ILegendEntryProperties get_Item(int index)
```

Bu listedeki bir grafik türü durumunda Chart.ChartData.Series[0].DataPoints[index] öğesine karşılık gelen gösterge girdisinin özelliklerini alır: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie; veya diğer grafik türleri için Chart.ChartData.Series[index] öğesine karşılık gelir.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int |  |

**Dönüş:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)
### getCount() {#getCount--}
```
public final int getCount()
```

Gösterge girdilerinin sayısını alır. Yalnızca okunur int.

**Dönüş:**
int