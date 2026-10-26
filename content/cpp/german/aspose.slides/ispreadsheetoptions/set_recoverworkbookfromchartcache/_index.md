---
title: set_RecoverWorkbookFromChartCache()
second_title: Aspose.Slides für C++ API-Referenz
description: Wenn die Datenquelle für das Diagramm eine externe Arbeitsmappe ist und diese nicht verfügbar ist, wird sie aus dem Diagramm-Cache wiederhergestellt.
type: docs
weight: 40
url: /de/aspose.slides/ispreadsheetoptions/set_recoverworkbookfromchartcache/
---
## ISpreadsheetOptions::set_RecoverWorkbookFromChartCache(bool) Methode


Wenn die Datenquelle für das Diagramm eine externe Arbeitsmappe ist und diese nicht verfügbar ist, wird sie aus dem Diagramm-Cache wiederhergestellt.

```cpp
virtual void Aspose::Slides::ISpreadsheetOptions::set_RecoverWorkbookFromChartCache(bool value)=0
```

## Hinweise



Beispiel: 
```cpp
auto loadOptions = MakeObject<LoadOptions>();
loadOptions->set_SpreadsheetOptions(System::MakeObject<SpreadsheetOptions>());
loadOptions->get_SpreadsheetOptions()->set_RecoverWorkbookFromChartCache(true);

auto pres = MakeObject<Presentation>(u"Presentation.pptx", loadOptions);
auto chart = AsCast<Aspose::Slides::Charts::IChart>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto recoveredWorkbook = chart->get_ChartData()->get_ChartDataWorkbook();
```

## Siehe auch

* Klasse [ISpreadsheetOptions](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)