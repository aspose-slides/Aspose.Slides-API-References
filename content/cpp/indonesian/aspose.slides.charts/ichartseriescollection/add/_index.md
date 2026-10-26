---
title: Add()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat seri diagram baru dan menambahkannya ke koleksi.
type: docs
weight: 14
url: /id/aspose.slides.charts/ichartseriescollection/add/
---
## IChartSeriesCollection::Add(ChartType) metode


Membuat seri diagram baru dan menambahkannya ke koleksi.

```cpp
virtual System::SharedPtr<IChartSeries> Aspose::Slides::Charts::IChartSeriesCollection::Add(ChartType type)=0
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| type | [ChartType](../../charttype/) | Tipe seri |

### Nilai Kembalian

Seri diagram baru.

## IChartSeriesCollection::Add(System::SharedPtr\<IChartDataCell\>, ChartType) metode


Membuat seri diagram baru dari [IChartDataCell](../../ichartdatacell/) dan menambahkannya ke koleksi.

```cpp
virtual System::SharedPtr<IChartSeries> Aspose::Slides::Charts::IChartSeriesCollection::Add(System::SharedPtr<IChartDataCell> cellWithSeriesName, ChartType type)=0
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| cellWithSeriesName | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | [Cell](../../../aspose.slides/cell/) yang berisi nama seri. |
| type | [ChartType](../../charttype/) | Tipe set tipe seri |

### Nilai Kembalian

Seri diagram yang ditambahkan atau seri yang sudah ada di koleksi.

## Catatan


Jika seri diagram dibuat dari sel yang sama yang sudah ada di koleksi, maka metode tidak menambahkan apa pun dan mengembalikan indeksnya.



## IChartSeriesCollection::Add(System::SharedPtr\<IChartCellCollection\>, ChartType) metode


Membuat seri diagram baru dari [IChartCellCollection](../../ichartcellcollection/) dan menambahkannya ke koleksi.

```cpp
virtual System::SharedPtr<IChartSeries> Aspose::Slides::Charts::IChartSeriesCollection::Add(System::SharedPtr<IChartCellCollection> cellsWithSeriesName, ChartType type)=0
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| cellsWithSeriesName | [System::SharedPtr](../../../system/sharedptr/)\<[IChartCellCollection](../../ichartcellcollection/)\> | Sel yang berisi nama seri. |
| type | [ChartType](../../charttype/) | Tipe set tipe seri |

### Nilai Kembalian

Seri diagram yang ditambahkan atau seri yang sudah ada di koleksi.

## Catatan


Jika seri diagram dibuat dari sel yang sama yang sudah ada di koleksi, maka metode tidak menambahkan apa pun dan mengembalikan indeksnya.



## IChartSeriesCollection::Add(System::String, ChartType) metode


Membuat seri diagram baru dari nilai dan menambahkannya ke koleksi.

```cpp
virtual System::SharedPtr<IChartSeries> Aspose::Slides::Charts::IChartSeriesCollection::Add(System::String name, ChartType type)=0
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| name | [System::String](../../../system/string/) | Nama seri. |
| type | [ChartType](../../charttype/) | Tipe set tipe seri |

### Nilai Kembalian

Seri diagram yang ditambahkan.



## Lihat Juga

* Enum [ChartType](../../charttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IChartSeries](../../ichartseries/)
* Kelas [IChartSeriesCollection](../)
* Kelas [IChartDataCell](../../ichartdatacell/)
* Kelas [IChartCellCollection](../../ichartcellcollection/)
* Kelas [String](../../../system/string/)
* Ruang Nama [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)