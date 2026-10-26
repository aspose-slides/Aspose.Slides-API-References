---
title: set_RecoverWorkbookFromChartCache()
second_title: Aspose.Slides för C++ API-referens
description: Om datakällan för diagrammet är en extern arbetsbok och den inte är tillgänglig, kommer den att återställas från diagramcachen.
type: docs
weight: 40
url: /sv/aspose.slides/ispreadsheetoptions/set_recoverworkbookfromchartcache/
---
## ISpreadsheetOptions::set_RecoverWorkbookFromChartCache(bool) metod


Om datakälla för diagrammet är en extern arbetsbok och den inte är tillgänglig, kommer den att återställas från diagramcachen.

```cpp
virtual void Aspose::Slides::ISpreadsheetOptions::set_RecoverWorkbookFromChartCache(bool value)=0
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

* Klass [ISpreadsheetOptions](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)