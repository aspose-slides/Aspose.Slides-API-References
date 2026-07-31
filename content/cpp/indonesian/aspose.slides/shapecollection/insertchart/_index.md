---
title: InsertChart()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat bagan baru, menginisialisasinya dengan data seri contoh dan pengaturan, serta menyisipkannya ke dalam koleksi bentuk pada indeks yang ditentukan.
type: docs
weight: 92
url: /id/aspose.slides/shapecollection/insertchart/
---
## ShapeCollection::InsertChart(Charts::ChartType, float, float, float, float, int32_t) method

Membuat bagan baru, menginisialisasinya dengan data seri contoh dan pengaturan, serta menyisipkannya ke dalam koleksi bentuk pada indeks yang ditentukan.

```cpp
System::SharedPtr<Charts::IChart> Aspose::Slides::ShapeCollection::InsertChart(Charts::ChartType type, float x, float y, float width, float height, int32_t index) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | Jenis bagan yang akan dibuat. |
| x | **float** | Koordinat x bagan baru, dalam poin. |
| y | **float** | Koordinat y bagan baru, dalam poin. |
| width | **float** | Lebar bagan baru, dalam poin. |
| height | **float** | Tinggi bagan baru, dalam poin. |
| index | **int32_t** | Indeks berbasis nol tempat menyisipkan bagan baru dalam koleksi bentuk. |

### Nilai Kembalian

[Charts::IChart](../../../aspose.slides.charts/ichart/) yang baru dibuat.

## ShapeCollection::InsertChart(Charts::ChartType, float, float, float, float, int32_t, bool) method

Membuat bagan baru, menginisialisasinya dengan data seri contoh dan pengaturan, serta menyisipkannya ke dalam koleksi bentuk pada indeks yang ditentukan.

```cpp
System::SharedPtr<Charts::IChart> Aspose::Slides::ShapeCollection::InsertChart(Charts::ChartType type, float x, float y, float width, float height, int32_t index, bool initWithSample) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | Jenis bagan yang akan dibuat. |
| x | **float** | Koordinat x bagan baru, dalam poin. |
| y | **float** | Koordinat y bagan baru, dalam poin. |
| width | **float** | Lebar bagan baru, dalam poin. |
| height | **float** | Tinggi bagan baru, dalam poin. |
| index | **int32_t** | Indeks berbasis nol tempat menyisipkan bagan baru dalam koleksi bentuk. |
| initWithSample | **bool** | True untuk menginisialisasi bagan baru dengan data seri contoh dan pengaturan; false untuk membuat bagan tanpa seri dan hanya pengaturan minimal, yang membuat pembuatan lebih cepat. |

### Nilai Kembalian

[Charts::IChart](../../../aspose.slides.charts/ichart/) yang baru dibuat.

## Lihat Juga

* Enum [ChartType](../../../aspose.slides.charts/charttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IChart](../../../aspose.slides.charts/ichart/)
* Kelas [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)