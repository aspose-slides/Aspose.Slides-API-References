---
title: get_RecoverWorkbookFromChartCache()
second_title: Referência da API Aspose.Slides para C++
description: Se a fonte de dados para o gráfico for uma pasta de trabalho externa e não estiver disponível, ela será recuperada do cache do gráfico.
type: docs
weight: 27
url: /pt/aspose.slides/ispreadsheetoptions/get_recoverworkbookfromchartcache/
---
## ISpreadsheetOptions::get_RecoverWorkbookFromChartCache() método


Se a fonte de dados para o gráfico for uma pasta de trabalho externa e não estiver disponível, ela será recuperada do cache do gráfico.

```cpp
virtual bool Aspose::Slides::ISpreadsheetOptions::get_RecoverWorkbookFromChartCache()=0
```

## Observações



Exemplo: 
```cpp
auto loadOptions = MakeObject<LoadOptions>();
loadOptions->set_SpreadsheetOptions(System::MakeObject<SpreadsheetOptions>());
loadOptions->get_SpreadsheetOptions()->set_RecoverWorkbookFromChartCache(true);

auto pres = MakeObject<Presentation>(u"Presentation.pptx", loadOptions);
auto chart = AsCast<Aspose::Slides::Charts::IChart>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto recoveredWorkbook = chart->get_ChartData()->get_ChartDataWorkbook();
```

## Veja também

* Classe [ISpreadsheetOptions](../)
* Namespace [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)