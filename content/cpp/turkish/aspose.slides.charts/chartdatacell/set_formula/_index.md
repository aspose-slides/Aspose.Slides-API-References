---
title: set_Formula()
second_title: Aspose.Slides için C++ API Referansı
description: Formülü A1 biçiminde ayarlar.
type: docs
weight: 66
url: /tr/aspose.slides.charts/chartdatacell/set_formula/
---
## ChartDataCell::set_Formula(System::String) metot

Formülü A1 biçiminde ayarlar.

```cpp
void Aspose::Slides::Charts::ChartDataCell::set_Formula(System::String value) override
```

## Açıklamalar


```cpp
auto cell = workbook->GetCell(0, u"B2");
cell->set_Formula(u"1 + SUM(F2:H5)");
```

## Ayrıca Bakınız

* Sınıf [String](../../../system/string/)
* Sınıf [ChartDataCell](../)
* Ad Alanı [Aspose::Slides::Charts](../../)
* Kütüphane [Aspose.Slides](../../../)