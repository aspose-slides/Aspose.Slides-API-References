---
title: set_RecoverWorkbookFromChartCache()
second_title: Aspose.Slides a C++ API referenciája
description: Ha a diagram adatforrása egy külső munkafüzet, és az nem érhető el, akkor a diagram gyorsítótárából kerül helyreállításra.
type: docs
weight: 40
url: /hu/aspose.slides/ispreadsheetoptions/set_recoverworkbookfromchartcache/
---
## ISpreadsheetOptions::set_RecoverWorkbookFromChartCache(bool) metódus


Ha a diagram adatforrása egy külső munkafüzet, és az nem érhető el, akkor a diagram gyorsítótárából kerül helyreállításra.

```cpp
virtual void Aspose::Slides::ISpreadsheetOptions::set_RecoverWorkbookFromChartCache(bool value)=0
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

* Osztály [ISpreadsheetOptions](../)
* Névterület [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)