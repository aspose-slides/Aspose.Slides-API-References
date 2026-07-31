---
title: Add()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat seri diagram baru dan menambahkannya ke koleksi.
type: docs
weight: 53
url: /id/aspose.slides.charts/chartseriescollection/add/
---
## ChartSeriesCollection::Add(ChartType) metode


Membuat seri diagram baru dan menambahkannya ke koleksi.

```cpp
System::SharedPtr<IChartSeries> Aspose::Slides::Charts::ChartSeriesCollection::Add(ChartType type) override
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| type | [ChartType](../../charttype/) | Tipe seri |

### Nilai Kembalian

Seri diagram baru.

## ChartSeriesCollection::Add(System::SharedPtr\<IChartDataCell\>, ChartType) metode


Membuat seri diagram baru dari [ChartDataCell](../../chartdatacell/) dan menambahkannya ke koleksi.

```cpp
System::SharedPtr<IChartSeries> Aspose::Slides::Charts::ChartSeriesCollection::Add(System::SharedPtr<IChartDataCell> cellWithSeriesName, ChartType type) override
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| cellWithSeriesName | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | [Cell](../../../aspose.slides/cell/) yang berisi nama seri. |
| type | [ChartType](../../charttype/) | Tipe yang mengatur tipe seri |

### Nilai Kembalian

Seri diagram yang ditambahkan atau seri yang sudah ada di koleksi.

## Catatan


Jika seri diagram dibuat dari sel yang sama yang sudah ada di koleksi, maka metode tidak menambahkan apa-apa dan mengembalikan indeksnya.



## ChartSeriesCollection::Add(System::SharedPtr\<IChartCellCollection\>, ChartType) metode


Membuat seri diagram baru dari [ChartCellCollection](../../chartcellcollection/) dan menambahkannya ke koleksi.

```cpp
System::SharedPtr<IChartSeries> Aspose::Slides::Charts::ChartSeriesCollection::Add(System::SharedPtr<IChartCellCollection> cellsWithSeriesName, ChartType type) override
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| cellsWithSeriesName | [System::SharedPtr](../../../system/sharedptr/)\<[IChartCellCollection](../../ichartcellcollection/)\> | Sel yang berisi nama seri. |
| type | [ChartType](../../charttype/) | Tipe yang mengatur tipe seri |

### Nilai Kembalian

Seri diagram yang ditambahkan atau seri yang sudah ada di koleksi.

## Catatan


Jika seri diagram dibuat dari sel yang sama yang sudah ada di koleksi, maka metode tidak menambahkan apa-apa dan mengembalikan indeksnya.



## ChartSeriesCollection::Add(System::String, ChartType) metode


Membuat seri diagram baru dari nilai dan menambahkannya ke koleksi.

```cpp
System::SharedPtr<IChartSeries> Aspose::Slides::Charts::ChartSeriesCollection::Add(System::String name, ChartType type) override
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| name | [System::String](../../../system/string/) | Nama seri. |
| type | [ChartType](../../charttype/) | Tipe yang mengatur tipe seri |

### Nilai Kembalian

Seri diagram yang ditambahkan.



## Lihat Juga

* Enum [ChartType](../../charttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IChartSeries](../../ichartseries/)
* Class [ChartSeriesCollection](../)
* Class [IChartDataCell](../../ichartdatacell/)
* Class [IChartCellCollection](../../ichartcellcollection/)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)