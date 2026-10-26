---
title: get_RecoverWorkbookFromChartCache()
second_title: Aspose.Slides voor C++ API-referentie
description: Als de gegevensbron voor de chart een extern workbook is en deze niet beschikbaar is, wordt deze hersteld vanuit de chart cache.
type: docs
weight: 27
url: /nl/aspose.slides/ispreadsheetoptions/get_recoverworkbookfromchartcache/
---
## ISpreadsheetOptions::get_RecoverWorkbookFromChartCache() methode


Als de gegevensbron voor de chart een externe workbook is en deze niet beschikbaar is, wordt deze hersteld vanuit de chart cache.

```cpp
virtual bool Aspose::Slides::ISpreadsheetOptions::get_RecoverWorkbookFromChartCache()=0
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

* Klasse [ISpreadsheetOptions](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)