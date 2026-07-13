---
title: ILegendEntryCollection
second_title: Aspose.Slides for Android via Java API Reference
description: Represents legends collection.
type: docs
url: /id/com.aspose.slides/ilegendentrycollection/
---```
public interface ILegendEntryCollection
```

Mewakili koleksi legenda.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Mendapatkan properti dari entri legenda yang sesuai dengan Chart.ChartData.Series[0].DataPoints[index] bila tipe diagram dari daftar berikut: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie; atau yang sesuai dengan Chart.ChartData.Series[index] untuk tipe diagram lainnya. |
| [getCount()](#getCount--) | Mendapatkan jumlah elemen yang sebenarnya terkandung dalam koleksi. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ILegendEntryProperties get_Item(int index)
```


Mendapatkan properti dari entri legenda yang sesuai dengan Chart.ChartData.Series[0].DataPoints[index] bila tipe diagram dari daftar berikut: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie; atau yang sesuai dengan Chart.ChartData.Series[index] untuk tipe diagram lainnya.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int |  |

**Mengembalikan:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)
### getCount() {#getCount--}
```
public abstract int getCount()
```


Mendapatkan jumlah elemen yang sebenarnya terkandung dalam koleksi. int hanya-baca.

**Mengembalikan:**
int