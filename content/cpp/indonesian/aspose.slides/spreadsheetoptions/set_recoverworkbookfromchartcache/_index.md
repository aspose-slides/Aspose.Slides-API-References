---
title: set_RecoverWorkbookFromChartCache()
second_title: Referensi API Aspose.Slides untuk C++
description: Jika sumber data untuk bagan adalah buku kerja eksternal dan tidak tersedia, maka akan dipulihkan dari cache bagan.
type: docs
weight: 40
url: /id/aspose.slides/spreadsheetoptions/set_recoverworkbookfromchartcache/
---
## SpreadsheetOptions::set_RecoverWorkbookFromChartCache(bool) metode


Jika sumber data untuk bagan adalah buku kerja eksternal dan tidak tersedia, maka akan dipulihkan dari cache bagan.

```cpp
void Aspose::Slides::SpreadsheetOptions::set_RecoverWorkbookFromChartCache(bool value) override
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
* Perpustakaan [Aspose.Slides](../../../)