---
title: set_RecoverWorkbookFromChartCache()
second_title: Riferimento API di Aspose.Slides per C++
description: Se la fonte dati per il grafico è una cartella di lavoro esterna e non è disponibile, verrà recuperata dalla cache del grafico.
type: docs
weight: 40
url: /it/aspose.slides/ispreadsheetoptions/set_recoverworkbookfromchartcache/
---
## ISpreadsheetOptions::set_RecoverWorkbookFromChartCache(bool) metodo


Se la fonte dati per il grafico è una cartella di lavoro esterna e non è disponibile, verrà recuperata dalla cache del grafico.

```cpp
virtual void Aspose::Slides::ISpreadsheetOptions::set_RecoverWorkbookFromChartCache(bool value)=0
```

## Osservazioni



Esempio: 
```cpp
auto loadOptions = MakeObject<LoadOptions>();
loadOptions->set_SpreadsheetOptions(System::MakeObject<SpreadsheetOptions>());
loadOptions->get_SpreadsheetOptions()->set_RecoverWorkbookFromChartCache(true);

auto pres = MakeObject<Presentation>(u"Presentation.pptx", loadOptions);
auto chart = AsCast<Aspose::Slides::Charts::IChart>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto recoveredWorkbook = chart->get_ChartData()->get_ChartDataWorkbook();
```

## Vedi anche

* Classe [ISpreadsheetOptions](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)