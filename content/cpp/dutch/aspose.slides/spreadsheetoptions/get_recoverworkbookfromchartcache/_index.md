---
title: get_RecoverWorkbookFromChartCache()
second_title: Aspose.Slides voor C++ API-referentie
description: Als de gegevensbron voor de grafiek een extern werkblad is en deze niet beschikbaar is, wordt deze hersteld vanuit de grafiekcache.
type: docs
weight: 27
url: /nl/aspose.slides/spreadsheetoptions/get_recoverworkbookfromchartcache/
---
## SpreadsheetOptions::get_RecoverWorkbookFromChartCache() methode


Als de gegevensbron voor de grafiek een extern werkblad is en deze niet beschikbaar is, wordt deze hersteld vanuit de grafiekcache.

```cpp
bool Aspose::Slides::SpreadsheetOptions::get_RecoverWorkbookFromChartCache() override
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
* Bibliotheek [Aspose.Slides](../../../)