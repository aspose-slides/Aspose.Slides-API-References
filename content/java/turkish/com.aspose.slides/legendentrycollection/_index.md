---
title: LegendEntryCollection
second_title: Aspose.Slides için Java API Referansı
description: Lejant koleksiyonunu temsil eder.
type: docs
url: /tr/com.aspose.slides/legendentrycollection/
---
**Kalıtım:**
java.lang.Object

**Tüm Uygulanan Arayüzler:**
[com.aspose.slides.ILegendEntryCollection](../../com.aspose.slides/ilegendentrycollection)
```
public class LegendEntryCollection implements ILegendEntryCollection
```

Lejant koleksiyonunu temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Lejant girişine karşılık gelen ve bu listeden bir grafik türü olması durumunda Chart.ChartData.Series[0].DataPoints[index] öğesinin özelliklerini alır: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie; veya diğer grafik türleri için Chart.ChartData.Series[index] öğesine karşılık gelir. |
| [getCount()](#getCount--) | Lejant girişlerinin sayısını alır. |
### get_Item(int index) {#get-Item-int-}
```
public final ILegendEntryProperties get_Item(int index)
```


Lejant girişine karşılık gelen ve bu listeden bir grafik türü olması durumunda Chart.ChartData.Series[0].DataPoints[index] öğesinin özelliklerini alır: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie; veya diğer grafik türleri için Chart.ChartData.Series[index] öğesine karşılık gelir.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int |  |

**Döndürür:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)
### getCount() {#getCount--}
```
public final int getCount()
```


Lejant girişlerinin sayısını alır. Sadece okuma int.

**Döndürür:**
int