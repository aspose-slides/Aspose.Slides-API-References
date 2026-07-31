---
title: AddDataPointForBarSeries()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat titik data baru dan menambahkannya ke akhir koleksi. Berlaku untuk seri yang chartType-nya merupakan salah satu Column atau Bar subtipe (lihat juga ChartTypeCharacterizer.IsChartTypeColumn(ChartType) dan ChartTypeCharacterizer.IsChartTypeBar(ChartType) metode).
type: docs
weight: 196
url: /id/aspose.slides.charts/ichartdatapointcollection/adddatapointforbarseries/
---
## IChartDataPointCollection::AddDataPointForBarSeries(System::SharedPtr\<IChartDataCell\>) metode


Membuat titik data baru dan menambahkannya ke akhir koleksi. Berlaku untuk seri yang chartType-nya merupakan salah satu [Column](../../../aspose.slides/column/) atau subtipe Bar (lihat juga [ChartTypeCharacterizer.IsChartTypeColumn(ChartType)](../../charttypecharacterizer/ischarttypecolumn/) dan [ChartTypeCharacterizer.IsChartTypeBar(ChartType)](../../charttypecharacterizer/ischarttypebar/) metode).

```cpp
virtual System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::IChartDataPointCollection::AddDataPointForBarSeries(System::SharedPtr<IChartDataCell> value)=0
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | Nilai titik data |

### Nilai Kembalian

Titik data baru.

## IChartDataPointCollection::AddDataPointForBarSeries(double) metode


Membuat titik data baru dan menambahkannya ke akhir koleksi. Berlaku untuk seri yang chartType-nya merupakan salah satu [Column](../../../aspose.slides/column/) atau subtipe Bar (lihat juga [ChartTypeCharacterizer.IsChartTypeColumn(ChartType)](../../charttypecharacterizer/ischarttypecolumn/) dan [ChartTypeCharacterizer.IsChartTypeBar(ChartType)](../../charttypecharacterizer/ischarttypebar/) metode).

```cpp
virtual System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::IChartDataPointCollection::AddDataPointForBarSeries(double value)=0
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | **double** | Nilai titik data |

### Nilai Kembalian

Titik data baru.

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IChartDataPoint](../../ichartdatapoint/)
* Kelas [IChartDataCell](../../ichartdatacell/)
* Kelas [IChartDataPointCollection](../)
* Ruang Nama [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)