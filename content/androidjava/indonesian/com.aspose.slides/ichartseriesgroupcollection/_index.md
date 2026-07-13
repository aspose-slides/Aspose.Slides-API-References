---
title: IChartSeriesGroupCollection
second_title: Aspose.Slides untuk Android melalui Referensi API Java
description: Mewakili koleksi grup seri yang dapat digabungkan.
type: docs
url: /id/com.aspose.slides/ichartseriesgroupcollection/
---
**Semua Antarmuka yang Diimplementasikan:**
com.aspose.slides.IGenericCollection
```
public interface IChartSeriesGroupCollection extends IGenericCollection<IChartSeriesGroup>
```

Mewakili koleksi grup seri yang dapat digabungkan.

--------------------

1) Setiap grup seri berisi seri dengan tipe yang dapat digabungkan. Grup tipe seri yang dapat digabungkan didefinisikan dan dijelaskan dengan enum CombinableSeriesTypesGroup. Juga setiap grup seri berisi seri yang diplot baik pada sumbu utama atau pada sumbu sekunder (tidak keduanya dalam satu grup). Jadi, prinsip pengelompokan seri adalah pengelompokan berdasarkan grup tipe yang disebutkan di atas dan berdasarkan tipe plot utama/sekunder. 2) Grup seri berisi beberapa properti seri yang umum untuk setiap seri dalam grup ("series group properties"). "Series group properties" dalam kelas ChartSeriesGroup dapat dibaca/tulis. Setiap "series group properties" dapat memiliki proyeksi hanya-baca dalam kelas ChartSeries.

## Metode

| Metode | Deskripsi |
| --- | --- |
| [get_Item(IChartSeries ofSeries)](#get-Item-com.aspose.slides.IChartSeries-) | Mendapatkan grup seri berdasarkan seri. |
| [get_Item(int index)](#get-Item-int-) | Mendapatkan grup seri berdasarkan indeks. |

### get_Item(IChartSeries ofSeries) {#get-Item-com.aspose.slides.IChartSeries-}
```
public abstract IChartSeriesGroup get_Item(IChartSeries ofSeries)
```

Mendapatkan grup seri berdasarkan seri.

Parameter:
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| ofSeries | [IChartSeries](../../com.aspose.slides/ichartseries) |  |

Mengembalikan:
[IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup)

### get_Item(int index) {#get-Item-int-}
```
public abstract IChartSeriesGroup get_Item(int index)
```

Mendapatkan grup seri berdasarkan indeks.

Parameter:
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int |  |

Mengembalikan:
[IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup)