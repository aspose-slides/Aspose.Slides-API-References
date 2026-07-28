---
title: get_RecoverWorkbookFromChartCache()
second_title: Aspose.Slides dla C++ Referencja API
description: Jeśli źródło danych wykresu jest zewnętrznym skoroszytem i nie jest dostępne, zostanie odzyskane z pamięci podręcznej wykresu.
type: docs
weight: 27
url: /pl/aspose.slides/spreadsheetoptions/get_recoverworkbookfromchartcache/
---
## SpreadsheetOptions::get_RecoverWorkbookFromChartCache() metoda


Jeśli źródło danych wykresu jest zewnętrznym skoroszytem i nie jest dostępne, zostanie odzyskane z pamięci podręcznej wykresu.

```cpp
bool Aspose::Slides::SpreadsheetOptions::get_RecoverWorkbookFromChartCache() override
```

## Uwagi



Przykład: 
```cpp
auto loadOptions = MakeObject<LoadOptions>();
loadOptions->set_SpreadsheetOptions(System::MakeObject<SpreadsheetOptions>());
loadOptions->get_SpreadsheetOptions()->set_RecoverWorkbookFromChartCache(true);

auto pres = MakeObject<Presentation>(u"Presentation.pptx", loadOptions);
auto chart = AsCast<Aspose::Slides::Charts::IChart>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto recoveredWorkbook = chart->get_ChartData()->get_ChartDataWorkbook();
```

## Zobacz także

* Klasa [SpreadsheetOptions](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)