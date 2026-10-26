---
title: CalculateFormulas()
second_title: Referensi API Aspose.Slides untuk C++
description: Menghitung semua rumus dalam workbook dan memperbarui nilai sel yang sesuai.
type: docs
weight: 53
url: /id/aspose.slides.charts/chartdataworkbook/calculateformulas/
---
## ChartDataWorkbook::CalculateFormulas() metode


Menghitung semua rumus dalam workbook dan memperbarui nilai sel yang sesuai.

```cpp
void Aspose::Slides::Charts::ChartDataWorkbook::CalculateFormulas() override
```

## Catatan



Contoh menunjukkan cara menetapkan rumus ke sel dan menghitung nilai. Nilai sel \"B4\" diatur menjadi 5. 
```cpp
auto pres = System::MakeObject<Presentation>();

auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(ChartType::Pie, 100.0f, 100.0f, 300.0f, 400.0f);
auto wb = chart->get_ChartData()->get_ChartDataWorkbook();
wb->GetCell(0, u"B2", ObjectExt::Box<int32_t>(2));
wb->GetCell(0, u"B3", ObjectExt::Box<int32_t>(3));
wb->GetCell(0, u"B4")->set_Formula(u"B2+B3");
wb->CalculateFormulas();
//...
```

## Lihat Juga

* Kelas [ChartDataWorkbook](../)
* Ruang Nama [Aspose::Slides::Charts](../../)
* Perpustakaan [Aspose.Slides](../../../)