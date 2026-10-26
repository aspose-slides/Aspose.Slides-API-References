---
title: get_RecoverWorkbookFromChartCache()
second_title: Aspose.Slides för C++ API-referens
description: Om datakällan för diagrammet är en extern arbetsbok och den inte är tillgänglig, kommer den att återställas från diagramcachen.
type: docs
weight: 27
url: /sv/aspose.slides/spreadsheetoptions/get_recoverworkbookfromchartcache/
---
## SpreadsheetOptions::get_RecoverWorkbookFromChartCache() metod


Om datakällan för diagrammet är en extern arbetsbok och den inte är tillgänglig, kommer den att återställas från diagramcachen.

```cpp
bool Aspose::Slides::SpreadsheetOptions::get_RecoverWorkbookFromChartCache() override
```

## Anmärkningar



Exempel: 
```cpp
auto loadOptions = MakeObject<LoadOptions>();
loadOptions->set_SpreadsheetOptions(System::MakeObject<SpreadsheetOptions>());
loadOptions->get_SpreadsheetOptions()->set_RecoverWorkbookFromChartCache(true);

auto pres = MakeObject<Presentation>(u"Presentation.pptx", loadOptions);
auto chart = AsCast<Aspose::Slides::Charts::IChart>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto recoveredWorkbook = chart->get_ChartData()->get_ChartDataWorkbook();
```

## Se även

* Klass [SpreadsheetOptions](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)