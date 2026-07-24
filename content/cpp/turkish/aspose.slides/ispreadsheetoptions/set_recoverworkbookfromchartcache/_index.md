---
title: set_RecoverWorkbookFromChartCache()
second_title: Aspose.Slides için C++ API Referansı
description: Grafik için veri kaynağı harici bir çalışma kitabıysa ve mevcut değilse, grafik önbelleğinden geri yüklenir.
type: docs
weight: 40
url: /tr/aspose.slides/ispreadsheetoptions/set_recoverworkbookfromchartcache/
---
## ISpreadsheetOptions::set_RecoverWorkbookFromChartCache(bool) metodu


Grafik için veri kaynağı harici bir çalışma kitabı ise ve mevcut değilse, grafik önbelleğinden geri yüklenir.

```cpp
virtual void Aspose::Slides::ISpreadsheetOptions::set_RecoverWorkbookFromChartCache(bool value)=0
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

## Diğer Bağlantılar

* Sınıf [ISpreadsheetOptions](../)
* Ad alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)