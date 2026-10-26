---
title: set_RecoverWorkbookFromChartCache()
second_title: Aspose.Slides C++ API referencia
description: Ha a diagram adatforrása egy külső munkafüzet, és az nem elérhető, akkor a diagram gyorsítótárából lesz helyreállítva.
type: docs
weight: 40
url: /hu/aspose.slides/spreadsheetoptions/set_recoverworkbookfromchartcache/
---
## SpreadsheetOptions::set_RecoverWorkbookFromChartCache(bool) metódus

Ha a diagram adatforrása egy külső munkafüzet, és az nem elérhető, akkor a diagram gyorsítótárából lesz helyreállítva.

```cpp
void Aspose::Slides::SpreadsheetOptions::set_RecoverWorkbookFromChartCache(bool value) override
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

* Osztály [SpreadsheetOptions](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)