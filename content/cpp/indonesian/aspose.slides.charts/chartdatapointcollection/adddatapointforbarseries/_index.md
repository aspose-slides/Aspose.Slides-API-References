---
title: AddDataPointForBarSeries()
second_title: Referensi API Aspose.Slides untuk C++
description: "Membuat titik data baru dan menambahkannya ke akhir koleksi. Berlaku untuk seri yang chartType adalah salah satu subtipe Column atau Bar (lihat juga ChartTypeCharacterizer::IsChartTypeColumn(ChartType) dan ChartTypeCharacterizer::IsChartTypeBar(ChartType) metode)."
type: docs
weight: 261
url: /id/aspose.slides.charts/chartdatapointcollection/adddatapointforbarseries/
---
## ChartDataPointCollection::AddDataPointForBarSeries(System::SharedPtr\<IChartDataCell\>) metode

Membuat titik data baru dan menambahkannya ke akhir koleksi. Berlaku untuk seri yang chartType merupakan salah satu [Column](../../../aspose.slides/column/) atau subtipe Bar (lihat juga [ChartTypeCharacterizer::IsChartTypeColumn(ChartType)](../../charttypecharacterizer/ischarttypecolumn/) dan [ChartTypeCharacterizer::IsChartTypeBar(ChartType)](../../charttypecharacterizer/ischarttypebar/) metode).

```cpp
System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::ChartDataPointCollection::AddDataPointForBarSeries(System::SharedPtr<IChartDataCell> value) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | Nilai titik data |

### Nilai Kembali

Titik data baru.

## ChartDataPointCollection::AddDataPointForBarSeries(double) metode

Membuat titik data baru dan menambahkannya ke akhir koleksi. Berlaku untuk seri yang chartType merupakan salah satu [Column](../../../aspose.slides/column/) atau subtipe Bar (lihat juga [ChartTypeCharacterizer::IsChartTypeColumn(ChartType)](../../charttypecharacterizer/ischarttypecolumn/) dan [ChartTypeCharacterizer::IsChartTypeBar(ChartType)](../../charttypecharacterizer/ischarttypebar/) metode).

```cpp
System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::ChartDataPointCollection::AddDataPointForBarSeries(double value) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | **double** | Nilai titik data |

### Nilai Kembali

Titik data baru.

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IChartDataPoint](../../ichartdatapoint/)
* Kelas [IChartDataCell](../../ichartdatacell/)
* Kelas [ChartDataPointCollection](../)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)