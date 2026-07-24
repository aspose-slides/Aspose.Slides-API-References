---
title: get_RecoverWorkbookFromChartCache()
second_title: Aspose.Slides için C++ API Referansı
description: Grafik için veri kaynağı harici bir çalışma kitabı ise ve mevcut değilse, grafik önbelleğinden kurtarılacaktır.
type: docs
weight: 27
url: /tr/aspose.slides/spreadsheetoptions/get_recoverworkbookfromchartcache/
---
## SpreadsheetOptions::get_RecoverWorkbookFromChartCache() yöntemi


If data source for the chart is an external workbook and it's not available, it will be recovered from the chart cache.

```cpp
bool Aspose::Slides::SpreadsheetOptions::get_RecoverWorkbookFromChartCache() override
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

## İlgili

* Sınıf [SpreadsheetOptions](../)
* Ad alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)