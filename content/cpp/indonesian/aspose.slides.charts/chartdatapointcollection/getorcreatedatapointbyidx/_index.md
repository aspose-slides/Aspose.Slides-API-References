---
title: GetOrCreateDataPointByIdx()
second_title: Referensi API Aspose.Slides untuk C++
description: "Jika koleksi sudah berisi titik data dengan indeks index maka mengembalikan titik data tersebut. Jika koleksi tidak berisi titik data dengan indeks index ==N (ketika jumlah titik data dalam koleksi ini kurang atau sama dengan N) maka menambahkan titik data yang kurang dan mengembalikan yang terakhir (yang memiliki indeks yang diminta). Sebagai contoh, indeks koleksi adalah {0, 1, 2}, dan indeks yang diminta adalah 5. Kemudian metode menambahkan titik data yang kurang: {0, 1, 2, 3, 4, 5}. Dan mengembalikan titik data dengan indeks 5."
type: docs
weight: 170
url: /id/aspose.slides.charts/chartdatapointcollection/getorcreatedatapointbyidx/
---
## ChartDataPointCollection::GetOrCreateDataPointByIdx(uint32_t) metode

Jika koleksi sudah berisi titik data dengan indeks *index* maka mengembalikan titik data tersebut. Jika koleksi tidak berisi titik data dengan indeks *index* ==N (ketika jumlah titik data dalam koleksi ini kurang atau sama dengan N) maka menambahkan titik data yang kurang dan mengembalikan yang terakhir (yang memiliki indeks yang diminta). Misalnya, indeks koleksi adalah {0, 1, 2}, dan indeks yang diminta adalah 5. Maka metode menambahkan titik data yang kurang: {0, 1, 2, 3, 4, 5}. Dan mengembalikan titik data dengan indeks 5.

```cpp
System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::ChartDataPointCollection::GetOrCreateDataPointByIdx(uint32_t index) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | **uint32_t** | Indeks. |

### Nilai Kembali

Mengembalikan titik data dengan indeks yang diminta.

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IChartDataPoint](../../ichartdatapoint/)
* Kelas [ChartDataPointCollection](../)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)