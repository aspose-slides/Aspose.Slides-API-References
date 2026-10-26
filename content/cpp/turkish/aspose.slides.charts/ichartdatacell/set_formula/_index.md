---
title: set_Formula()
second_title: Aspose.Slides for C++ API Referansı
description: A1 stilinde formülü ayarlar.
type: docs
weight: 66
url: /tr/aspose.slides.charts/ichartdatacell/set_formula/
---
## IChartDataCell::set_Formula(System::String) yöntemi

Formülü A1 stilinde ayarlar.

```cpp
virtual void Aspose::Slides::Charts::IChartDataCell::set_Formula(System::String value)=0
```

## Açıklamalar



```cpp
auto cell = workbook->GetCell(0, u"B2");
cell->set_Formula(u"1 + SUM(F2:H5)");
```

## Ayrıca Bakınız

* Sınıf [String](../../../system/string/)
* Sınıf [IChartDataCell](../)
* Ad Alanı [Aspose::Slides::Charts](../../)
* Kütüphane [Aspose.Slides](../../../)