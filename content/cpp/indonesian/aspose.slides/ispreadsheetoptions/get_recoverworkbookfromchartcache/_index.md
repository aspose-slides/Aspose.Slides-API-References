---
title: get_RecoverWorkbookFromChartCache()
second_title: Aspose.Slides untuk C++ Referensi API
description: Jika sumber data untuk diagram adalah buku kerja eksternal dan tidak tersedia, maka akan dipulihkan dari cache diagram.
type: docs
weight: 27
url: /id/aspose.slides/ispreadsheetoptions/get_recoverworkbookfromchartcache/
---
## ISpreadsheetOptions::get_RecoverWorkbookFromChartCache() metode


Jika sumber data untuk diagram adalah buku kerja eksternal dan tidak tersedia, maka akan dipulihkan dari cache diagram.

```cpp
virtual bool Aspose::Slides::ISpreadsheetOptions::get_RecoverWorkbookFromChartCache()=0
```
## Catatan



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

* Kelas [ISpreadsheetOptions](../)
* Ruang Nama [Aspose::Slides](../../)
* Perpustakaan [Aspose.Slides](../../../)