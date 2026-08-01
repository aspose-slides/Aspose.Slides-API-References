---
title: set_RecoverWorkbookFromChartCache()
second_title: Aspose.Slides voor C++ API-referentie
description: Als de gegevensbron voor de grafiek een extern werkboek is en deze niet beschikbaar is, wordt deze hersteld vanuit de grafiekcache.
type: docs
weight: 40
url: /nl/aspose.slides/ispreadsheetoptions/set_recoverworkbookfromchartcache/
---
## ISpreadsheetOptions::set_RecoverWorkbookFromChartCache(bool) methode


Als de gegevensbron voor de grafiek een extern werkboek is en deze niet beschikbaar is, wordt deze hersteld vanuit de grafiekcache.

```cpp
virtual void Aspose::Slides::ISpreadsheetOptions::set_RecoverWorkbookFromChartCache(bool value)=0
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