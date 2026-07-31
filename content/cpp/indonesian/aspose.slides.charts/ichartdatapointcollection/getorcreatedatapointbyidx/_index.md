---
title: GetOrCreateDataPointByIdx()
second_title: Referensi API Aspose.Slides untuk C++
description: "Jika koleksi sudah berisi data point dengan indeks index maka mengembalikan data point tersebut. Jika koleksi tidak berisi data point dengan indeks index ==N (ketika jumlah data point dalam koleksi ini kurang atau sama dengan N) maka menambahkan data point yang kurang dan mengembalikan yang terakhir (yang memiliki indeks yang diminta). Sebagai contoh, indeks koleksi adalah {0, 1, 2}, dan indeks yang diminta adalah 5. Maka metode menambahkan data point yang kurang: {0, 1, 2, 3, 4, 5}. Dan mengembalikan data point dengan indeks 5."
type: docs
weight: 131
url: /id/aspose.slides.charts/ichartdatapointcollection/getorcreatedatapointbyidx/
---
## IChartDataPointCollection::GetOrCreateDataPointByIdx(uint32_t) metode


Jika koleksi sudah berisi data point dengan indeks *index* maka mengembalikan data point tersebut. Jika koleksi tidak berisi data point dengan indeks *index* ==N (ketika jumlah data point dalam koleksi ini kurang atau sama dengan N) maka menambahkan data point yang kurang dan mengembalikan yang terakhir (yang memiliki indeks yang diminta). Misalnya, indeks koleksi adalah {0, 1, 2}, dan indeks yang diminta adalah 5. Maka metode menambahkan data point yang kurang: {0, 1, 2, 3, 4, 5}. Dan mengembalikan data point dengan indeks 5.

```cpp
virtual System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::IChartDataPointCollection::GetOrCreateDataPointByIdx(uint32_t index)=0
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | **uint32_t** | Indeks. |

### Nilai Kembalian

Mengembalikan data point dengan indeks yang diminta.

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IChartDataPoint](../../ichartdatapoint/)
* Kelas [IChartDataPointCollection](../)
* Ruang Nama [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)