---
title: get_RecoverWorkbookFromChartCache()
second_title: Referensi API Aspose.Slides untuk C++
description: Jika sumber data untuk diagram adalah buku kerja eksternal dan tidak tersedia, maka akan dipulihkan dari cache diagram.
type: docs
weight: 27
url: /id/aspose.slides/spreadsheetoptions/get_recoverworkbookfromchartcache/
---
## SpreadsheetOptions::get_RecoverWorkbookFromChartCache() metode


Jika sumber data untuk diagram adalah buku kerja eksternal dan tidak tersedia, data akan dipulihkan dari cache diagram.

```cpp
bool Aspose::Slides::SpreadsheetOptions::get_RecoverWorkbookFromChartCache() override
```

## Keterangan



Contoh: 
```cpp
auto loadOptions = MakeObject<LoadOptions>();
loadOptions->set_SpreadsheetOptions(System::MakeObject<SpreadsheetOptions>());
loadOptions->get_SpreadsheetOptions()->set_RecoverWorkbookFromChartCache(true);

auto pres = MakeObject<Presentation>(u"Presentation.pptx", loadOptions);
auto chart = AsCast<Aspose::Slides::Charts::IChart>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto recoveredWorkbook = chart->get_ChartData()->get_ChartDataWorkbook();
```

## Lihat Juga

* Kelas [SpreadsheetOptions](../)
* Ruang Nama [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)