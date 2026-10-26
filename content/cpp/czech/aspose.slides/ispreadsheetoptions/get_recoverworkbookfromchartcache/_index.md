---
title: get_RecoverWorkbookFromChartCache()
second_title: Aspose.Slides pro referenční příručku API C++
description: Pokud je zdroj dat pro graf externí sešit a není dostupný, bude obnoven z mezipaměti grafu.
type: docs
weight: 27
url: /cs/aspose.slides/ispreadsheetoptions/get_recoverworkbookfromchartcache/
---
## ISpreadsheetOptions::get_RecoverWorkbookFromChartCache() metoda

Pokud je zdroj dat pro graf externí sešit a není dostupný, bude obnoven z mezipaměti grafu.

```cpp
virtual bool Aspose::Slides::ISpreadsheetOptions::get_RecoverWorkbookFromChartCache()=0
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

* Třída [ISpreadsheetOptions](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)