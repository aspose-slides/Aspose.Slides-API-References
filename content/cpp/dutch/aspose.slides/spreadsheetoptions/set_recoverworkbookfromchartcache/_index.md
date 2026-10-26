---
title: set_RecoverWorkbookFromChartCache()
second_title: Aspose.Slides voor C++ API-referentie
description: Als de gegevensbron voor de grafiek een extern werkboek is en deze niet beschikbaar is, wordt deze hersteld uit de grafiekcache.
type: docs
weight: 40
url: /nl/aspose.slides/spreadsheetoptions/set_recoverworkbookfromchartcache/
---
## SpreadsheetOptions::set_RecoverWorkbookFromChartCache(bool) methode


Als de gegevensbron voor de grafiek een extern werkboek is en deze niet beschikbaar is, wordt deze hersteld uit de grafiekcache.

```cpp
void Aspose::Slides::SpreadsheetOptions::set_RecoverWorkbookFromChartCache(bool value) override
```

## Opmerkingen



Voorbeeld: 
```cpp
auto loadOptions = MakeObject<LoadOptions>();
loadOptions->set_SpreadsheetOptions(System::MakeObject<SpreadsheetOptions>());
loadOptions->get_SpreadsheetOptions()->set_RecoverWorkbookFromChartCache(true);

auto pres = MakeObject<Presentation>(u"Presentation.pptx", loadOptions);
auto chart = AsCast<Aspose::Slides::Charts::IChart>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto recoveredWorkbook = chart->get_ChartData()->get_ChartDataWorkbook();
```

## Zie ook

* Klasse [SpreadsheetOptions](../)
* Naamruimte [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)