---
title: set_Overlap()
second_title: Referensi API Aspose.Slides untuk C++
description: Menentukan seberapa banyak batang dan kolom harus tumpang tindih pada diagram 2-D, sebagai persentase (dari -100% hingga 100%).
type: docs
weight: 196
url: /id/aspose.slides.charts/ichartseriesgroup/set_overlap/
---
## IChartSeriesGroup::set_Overlap(int8_t) metode


Menentukan seberapa banyak batang dan kolom harus saling tumpang tindih pada diagram 2D, sebagai persentase (dari -100% hingga 100%).

```cpp
virtual void Aspose::Slides::Charts::IChartSeriesGroup::set_Overlap(int8_t value)=0
```

## Catatan


* -100%: Jarak maksimum (batang sepenuhnya terpisah).
* 0%: Batang ditempatkan berdampingan tanpa tumpang tindih atau jarak.
* 100%: Tumpang tindih maksimum (batang sepenuhnya tumpang tindih satu sama lain). Properti ini adalah baca/tulis **int8_t**.



Contoh berikut menunjukkan cara mengatur tumpang tindih untuk grup seri diagram dan merender diagram yang dihasilkan pada sebuah form: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::SharedPtr<ISlide> slide = pres->get_Slide(0);

System::SharedPtr<IChart> chart = slide->get_Shapes()->AddChart(ChartType::ClusteredColumn, 10.0f, 10.0f, 600.0f, 300.0f);
System::SharedPtr<IChartSeriesCollection> series = chart->get_ChartData()->get_Series();
series->idx_get(0)->get_ParentSeriesGroup()->set_Overlap(55); // Set tumpang tindih ke 55%

auto image = slide->GetImage(1.0f, 1.0f);
image->Save(u"image.png", ImageFormat::Png);
```


## Lihat Juga

* Kelas [IChartSeriesGroup](../)
* Ruang Nama [Aspose::Slides::Charts](../../)
* Pustaka [Aspose.Slides](../../../)