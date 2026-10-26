---
title: AddChart()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat chart baru, menginisialisasinya dengan data seri contoh dan pengaturan, serta menambahkannya ke akhir koleksi shape.
type: docs
weight: 27
url: /id/aspose.slides/ishapecollection/addchart/
---
## IShapeCollection::AddChart(Charts::ChartType, float, float, float, float) metode

Membuat chart baru, menginisialisasinya dengan data seri contoh dan pengaturan, serta menambahkannya ke akhir koleksi shape.

```cpp
virtual System::SharedPtr<Charts::IChart> Aspose::Slides::IShapeCollection::AddChart(Charts::ChartType type, float x, float y, float width, float height)=0
```

### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | Jenis chart yang akan ditambahkan. |
| x | **float** | Koordinat x chart baru, dalam poin. |
| y | **float** | Koordinat y chart baru, dalam poin. |
| width | **float** | Lebar chart, dalam poin. |
| height | **float** | Tinggi chart, dalam poin. |

### Nilai Kembali

[Charts::IChart](../../../aspose.slides.charts/ichart/) yang baru dibuat.

## IShapeCollection::AddChart(Charts::ChartType, float, float, float, float, bool) metode

Membuat chart baru, menginisialisasinya dengan data seri contoh dan pengaturan, serta menambahkannya ke akhir koleksi shape.

```cpp
virtual System::SharedPtr<Charts::IChart> Aspose::Slides::IShapeCollection::AddChart(Charts::ChartType type, float x, float y, float width, float height, bool initWithSample)=0
```

### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | Jenis chart yang akan ditambahkan. |
| x | **float** | Koordinat x chart baru, dalam poin. |
| y | **float** | Koordinat y chart baru, dalam poin. |
| width | **float** | Lebar chart, dalam poin. |
| height | **float** | Tinggi chart, dalam poin. |
| initWithSample | **bool** | Benar untuk menginisialisasi chart baru dengan data seri contoh dan pengaturan; false untuk membuat chart tanpa seri dan hanya dengan pengaturan minimal, yang membuat pembuatan lebih cepat. |

### Nilai Kembali

[Charts::IChart](../../../aspose.slides.charts/ichart/) yang baru dibuat.

## Lihat Juga

* Enum [ChartType](../../../aspose.slides.charts/charttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IChart](../../../aspose.slides.charts/ichart/)
* Class [IShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)