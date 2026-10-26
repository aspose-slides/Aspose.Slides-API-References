---
title: set_RecoverWorkbookFromChartCache()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Pokud je zdroj dat pro graf externí sešit a není k dispozici, bude obnoven z mezipaměti grafu.
type: docs
weight: 40
url: /cs/aspose.slides/spreadsheetoptions/set_recoverworkbookfromchartcache/
---
## SpreadsheetOptions::set_RecoverWorkbookFromChartCache(bool) metoda


Pokud je zdroj dat pro graf externí sešit a není k dispozici, bude obnoven z mezipaměti grafu.

```cpp
void Aspose::Slides::SpreadsheetOptions::set_RecoverWorkbookFromChartCache(bool value) override
```

## Poznámky



Příklad: 
```cpp
auto loadOptions = MakeObject<LoadOptions>();
loadOptions->set_SpreadsheetOptions(System::MakeObject<SpreadsheetOptions>());
loadOptions->get_SpreadsheetOptions()->set_RecoverWorkbookFromChartCache(true);

auto pres = MakeObject<Presentation>(u"Presentation.pptx", loadOptions);
auto chart = AsCast<Aspose::Slides::Charts::IChart>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto recoveredWorkbook = chart->get_ChartData()->get_ChartDataWorkbook();
```

## Viz také

* Třída [SpreadsheetOptions](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)