---
title: GetCell()
second_title: Referensi API Aspose.Slides untuk C++
description: Mendapatkan sel yang dapat digunakan untuk seri atau kategori diagram
type: docs
weight: 27
url: /id/aspose.slides.charts/chartdataworkbook/getcell/
---
## ChartDataWorkbook::GetCell(System::String, int32_t, int32_t) metode

Mendapatkan sel yang dapat digunakan untuk seri atau kategori diagram

```cpp
System::SharedPtr<IChartDataCell> Aspose::Slides::Charts::ChartDataWorkbook::GetCell(System::String worksheetName, int32_t row, int32_t column) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| worksheetName | [System::String](../../../system/string/) | Nama lembar kerja. |
| row | **int32_t** | Baris. |
| column | **int32_t** | Kolom. |

### Nilai Kembalian

[Cell](../../../aspose.slides/cell/) objek

## ChartDataWorkbook::GetCell(int32_t, int32_t, int32_t) metode

Mendapatkan sel yang dapat digunakan untuk seri atau kategori diagram

```cpp
System::SharedPtr<IChartDataCell> Aspose::Slides::Charts::ChartDataWorkbook::GetCell(int32_t worksheetIndex, int32_t row, int32_t column) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| worksheetIndex | **int32_t** | Indeks lembar kerja. |
| row | **int32_t** | Baris. |
| column | **int32_t** | Kolom. |

### Nilai Kembalian

[Cell](../../../aspose.slides/cell/) objek

## ChartDataWorkbook::GetCell(int32_t, System::String) metode

Mendapatkan sel yang dapat digunakan untuk seri atau kategori diagram

```cpp
System::SharedPtr<IChartDataCell> Aspose::Slides::Charts::ChartDataWorkbook::GetCell(int32_t worksheetIndex, System::String cellName) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| worksheetIndex | **int32_t** | Indeks lembar kerja. |
| cellName | [System::String](../../../system/string/) | Nama sel. |

### Nilai Kembalian

[Cell](../../../aspose.slides/cell/) objek

## ChartDataWorkbook::GetCell(int32_t, System::String, System::SharedPtr\<System::Object\>) metode

Mendapatkan sel yang dapat digunakan untuk seri atau kategori diagram

```cpp
System::SharedPtr<IChartDataCell> Aspose::Slides::Charts::ChartDataWorkbook::GetCell(int32_t worksheetIndex, System::String cellName, System::SharedPtr<System::Object> value) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| worksheetIndex | **int32_t** | Indeks lembar kerja. |
| cellName | [System::String](../../../system/string/) | Nama sel. |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | Nilai. |

### Nilai Kembalian

[Cell](../../../aspose.slides/cell/) objek

## ChartDataWorkbook::GetCell(int32_t, int32_t, int32_t, System::SharedPtr\<System::Object\>) metode

Mendapatkan sel yang dapat digunakan untuk seri atau kategori diagram

```cpp
System::SharedPtr<IChartDataCell> Aspose::Slides::Charts::ChartDataWorkbook::GetCell(int32_t worksheetIndex, int32_t row, int32_t column, System::SharedPtr<System::Object> value) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| worksheetIndex | **int32_t** | Indeks lembar kerja. |
| row | **int32_t** | Baris. |
| column | **int32_t** | Kolom. |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | Nilai. |

### Nilai Kembalian

[Cell](../../../aspose.slides/cell/) objek

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IChartDataCell](../../ichartdatacell/)
* Kelas [String](../../../system/string/)
* Kelas [ChartDataWorkbook](../)
* Kelas [Object](../../../system/object/)
* Namespace [Aspose::Slides::Charts](../../)
* Pustaka [Aspose.Slides](../../../)