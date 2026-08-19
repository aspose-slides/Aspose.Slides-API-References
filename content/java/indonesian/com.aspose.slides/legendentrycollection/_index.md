---
title: LegendEntryCollection
second_title: Referensi API Aspose.Slides untuk Java
description: Mewakili koleksi legenda.
type: docs
url: /id/com.aspose.slides/legendentrycollection/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.ILegendEntryCollection](../../com.aspose.slides/ilegendentrycollection)
```
public class LegendEntryCollection implements ILegendEntryCollection
```

Mewakili koleksi legenda.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Mendapatkan properti entri legenda yang sesuai dengan Chart.ChartData.Series[0].DataPoints[index] dalam kasus tipe bagan dari daftar ini: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie; atau yang sesuai dengan Chart.ChartData.Series[index] untuk tipe bagan lainnya. |
| [getCount()](#getCount--) | Mendapatkan jumlah entri legenda. |
### get_Item(int index) {#get-Item-int-}
```
public final ILegendEntryProperties get_Item(int index)
```


Mendapatkan properti entri legenda yang sesuai dengan Chart.ChartData.Series[0].DataPoints[index] dalam kasus tipe bagan dari daftar ini: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie; atau yang sesuai dengan Chart.ChartData.Series[index] untuk tipe bagan lainnya.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int |  |

**Mengembalikan:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)
### getCount() {#getCount--}
```
public final int getCount()
```


Mendapatkan jumlah entri legenda. Hanya-baca int.

**Mengembalikan:**
int