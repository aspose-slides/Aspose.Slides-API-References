---
title: get_RecoverWorkbookFromChartCache()
second_title: Aspose.Slides C++ API referencia
description: Ha a diagram adatforrása egy külső munkafüzet, és az nem érhető el, akkor a diagram gyorsítótárából kerül helyreállításra.
type: docs
weight: 27
url: /hu/aspose.slides/spreadsheetoptions/get_recoverworkbookfromchartcache/
---
## SpreadsheetOptions::get_RecoverWorkbookFromChartCache() metódus


Ha a diagram adatforrása egy külső munkafüzet, és az nem érhető el, akkor a diagram gyorsítótárából kerül helyreállításra.

```cpp
bool Aspose::Slides::SpreadsheetOptions::get_RecoverWorkbookFromChartCache() override
```

## Megjegyzések



Példa: 
```cpp
auto loadOptions = MakeObject<LoadOptions>();
loadOptions->set_SpreadsheetOptions(System::MakeObject<SpreadsheetOptions>());
loadOptions->get_SpreadsheetOptions()->set_RecoverWorkbookFromChartCache(true);

auto pres = MakeObject<Presentation>(u"Presentation.pptx", loadOptions);
auto chart = AsCast<Aspose::Slides::Charts::IChart>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto recoveredWorkbook = chart->get_ChartData()->get_ChartDataWorkbook();
```

## Lásd még

* Class [SpreadsheetOptions](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)