---
title: Remove()
second_title: Referensi API Aspose.Slides untuk C++
description: Menghapus item dari koleksi.
type: docs
weight: 79
url: /id/aspose.slides.charts/piesplitcustompointcollection/remove/
---
## PieSplitCustomPointCollection::Remove(const System::SharedPtr\<IChartDataPoint\>\&) metode


Menghapus item dari koleksi.

```cpp
bool Aspose::Slides::Charts::PieSplitCustomPointCollection::Remove(const System::SharedPtr<IChartDataPoint> &dataPoint) override
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| dataPoint | const [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataPoint](../../ichartdatapoint/)\>\& | Data point remove to. |

### Nilai Pengembalian

true jika item berhasil dihapus; sebaliknya, false. Metode ini juga mengembalikan false jika item tidak ditemukan dalam [System::Collections::Generic::List](../../../system.collections.generic/list/){T}.

## PieSplitCustomPointCollection::Remove(int32_t) metode


Menghapus item dari koleksi berdasarkan indeksnya dalam koleksi titik seri induk.

```cpp
void Aspose::Slides::Charts::PieSplitCustomPointCollection::Remove(int32_t dataPointIndex) override
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| dataPointIndex | **int32_t** | Indeks titik data dalam koleksi titik seri induk. |

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IChartDataPoint](../../ichartdatapoint/)
* Kelas [PieSplitCustomPointCollection](../)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)