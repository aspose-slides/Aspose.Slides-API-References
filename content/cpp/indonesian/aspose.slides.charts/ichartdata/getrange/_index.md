---
title: GetRange()
second_title: Referensi API Aspose.Slides untuk C++
description: Mendapatkan rentang data diagram.
type: docs
weight: 170
url: /id/aspose.slides.charts/ichartdata/getrange/
---
## IChartData::GetRange() metode


Mendapatkan rentang data diagram.

```cpp
virtual System::String Aspose::Slides::Charts::IChartData::GetRange()=0
```


### Nilai Kembali

Formula rentang data sel. Contoh: "Sheet1!$A$1:$C$4"
## Keterangan


```cpp
auto pres = MakeObject<Presentation>();
auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(Charts::ChartType::PercentsStackedBar, 100.0f, 100.0f, 500.0f, 400.0f);
String result = (AsCast<Charts::ChartData>(chart->get_ChartData()))->GetRange();
```

## Lihat Juga

* Kelas [String](../../../system/string/)
* Kelas [IChartData](../)
* Ruang Nama [Aspose::Slides::Charts](../../)
* Perpustakaan [Aspose.Slides](../../../)