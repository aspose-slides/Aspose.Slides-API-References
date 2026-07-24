---
title: set_RecoverWorkbookFromChartCache()
second_title: Aspose.Slides für C++ API-Referenz
description: Wenn die Datenquelle für das Diagramm eine externe Arbeitsmappe ist und sie nicht verfügbar ist, wird sie aus dem Diagramm-Cache wiederhergestellt.
type: docs
weight: 40
url: /de/aspose.slides/spreadsheetoptions/set_recoverworkbookfromchartcache/
---
## SpreadsheetOptions::set_RecoverWorkbookFromChartCache(bool) Methode


Wenn die Datenquelle für das Diagramm eine externe Arbeitsmappe ist und sie nicht verfügbar ist, wird sie aus dem Diagramm-Cache wiederhergestellt.

```cpp
void Aspose::Slides::SpreadsheetOptions::set_RecoverWorkbookFromChartCache(bool value) override
```

## Anmerkungen



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

* Klasse [SpreadsheetOptions](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)