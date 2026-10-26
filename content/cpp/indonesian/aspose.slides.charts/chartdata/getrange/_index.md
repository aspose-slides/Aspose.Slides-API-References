---
title: GetRange()
second_title: Referensi API Aspose.Slides untuk C++
description: Mendapatkan rentang data diagram.
type: docs
weight: 157
url: /id/aspose.slides.charts/chartdata/getrange/
---
## ChartData::GetRange() metode

Mendapatkan rentang data diagram.

```cpp
System::String Aspose::Slides::Charts::ChartData::GetRange() override
```

### Nilai Kembali

Formula rentang data sel. Misalnya: "Sheet1!$A$1:$C$4"
## Keterangan

```cpp
auto pres = MakeObject<Presentation>();
auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(Charts::ChartType::PercentsStackedBar, 0.0f, 0.0f, 100.0f, 100.0f);
String result = (AsCast<Charts::ChartData>(chart->get_ChartData()))->GetRange();
```

## Lihat Juga

* Kelas [String](../../../system/string/)
* Kelas [ChartData](../)
* Namespace [Aspose::Slides::Charts](../../)
* Perpustakaan [Aspose.Slides](../../../)