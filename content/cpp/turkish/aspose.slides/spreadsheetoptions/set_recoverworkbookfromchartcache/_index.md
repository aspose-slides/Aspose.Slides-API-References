---
title: set_RecoverWorkbookFromChartCache()
second_title: Aspose.Slides for C++ API Referansı
description: Grafik için veri kaynağı harici bir çalışma kitabı ise ve mevcut değilse, grafik önbelleğinden kurtarılacaktır.
type: docs
weight: 40
url: /tr/aspose.slides/spreadsheetoptions/set_recoverworkbookfromchartcache/
---
## SpreadsheetOptions::set_RecoverWorkbookFromChartCache(bool) metot


Grafik için veri kaynağı harici bir çalışma kitabı ise ve mevcut değilse, grafik önbelleğinden kurtarılacaktır.

```cpp
void Aspose::Slides::SpreadsheetOptions::set_RecoverWorkbookFromChartCache(bool value) override
```

## Açıklamalar



Örnek:
```cpp
auto loadOptions = MakeObject<LoadOptions>();
loadOptions->set_SpreadsheetOptions(System::MakeObject<SpreadsheetOptions>());
loadOptions->get_SpreadsheetOptions()->set_RecoverWorkbookFromChartCache(true);

auto pres = MakeObject<Presentation>(u"Presentation.pptx", loadOptions);
auto chart = AsCast<Aspose::Slides::Charts::IChart>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto recoveredWorkbook = chart->get_ChartData()->get_ChartDataWorkbook();
```

## Ayrıca Bakınız

* Sınıf [SpreadsheetOptions](../)
* Ad Alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)