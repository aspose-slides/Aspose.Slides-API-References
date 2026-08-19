---
title: ILegendEntryCollection
second_title: Aspose.Slides for Java API Reference
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
| [get_Item(int index)](#get-Item-int-) | Mendapatkan properti entri legenda yang sesuai dengan Chart.ChartData.Series[0].DataPoints[index] bila tipe diagram termasuk dalam daftar berikut: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie; atau yang sesuai dengan Chart.ChartData.Series[index] untuk tipe diagram lainnya. |
| [getCount()](#getCount--) | Mendapatkan jumlah elemen yang sebenarnya terdapat dalam koleksi. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ILegendEntryProperties get_Item(int index)
```

Mendapatkan properti entri legenda yang sesuai dengan Chart.ChartData.Series[0].DataPoints[index] bila tipe diagram termasuk dalam daftar berikut: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie; atau yang sesuai dengan Chart.ChartData.Series[index] untuk tipe diagram lainnya.

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

Mendapatkan jumlah elemen yang sebenarnya terdapat dalam koleksi. int hanya-baca.

**Mengembalikan:**
int