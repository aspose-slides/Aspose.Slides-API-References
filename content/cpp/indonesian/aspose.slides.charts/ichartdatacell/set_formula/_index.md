---
title: set_Formula()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengatur formula dengan gaya A1.
type: docs
weight: 66
url: /id/aspose.slides.charts/ichartdatacell/set_formula/
---
## IChartDataCell::set_Formula(System::String) metode


Mengatur formula dengan gaya A1.

```cpp
virtual void Aspose::Slides::Charts::IChartDataCell::set_Formula(System::String value)=0
```

## Catatan



```cpp
auto cell = workbook->GetCell(0, u"B2");
cell->set_Formula(u"1 + SUM(F2:H5)");
```

## Lihat Juga

* Kelas [String](../../../system/string/)
* Kelas [IChartDataCell](../)
* Ruang Nama [Aspose::Slides::Charts](../../)
* Perpustakaan [Aspose.Slides](../../../)