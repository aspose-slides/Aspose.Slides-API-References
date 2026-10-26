---
title: get_RecoverWorkbookFromChartCache()
second_title: Aspose.Slides for C++ – dokumentacja API
description: Jeśli źródło danych wykresu jest zewnętrznym skoroszytem i nie jest dostępne, zostanie ono odzyskane z pamięci podręcznej wykresu.
type: docs
weight: 27
url: /pl/aspose.slides/ispreadsheetoptions/get_recoverworkbookfromchartcache/
---
## ISpreadsheetOptions::get_RecoverWorkbookFromChartCache() metoda


Jeśli źródło danych dla wykresu jest zewnętrznym skoroszytem i nie jest dostępne, zostanie ono odzyskane z pamięci podręcznej wykresu.

```cpp
virtual bool Aspose::Slides::ISpreadsheetOptions::get_RecoverWorkbookFromChartCache()=0
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

* Klasa [ISpreadsheetOptions](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)