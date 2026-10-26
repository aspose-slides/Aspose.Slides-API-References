---
title: get_RecoverWorkbookFromChartCache()
second_title: Referência da API Aspose.Slides para C++
description: Se a fonte de dados para o gráfico for uma pasta de trabalho externa e não estiver disponível, ela será recuperada do cache do gráfico.
type: docs
weight: 27
url: /pt/aspose.slides/spreadsheetoptions/get_recoverworkbookfromchartcache/
---
## SpreadsheetOptions::get_RecoverWorkbookFromChartCache() método


Se a fonte de dados para o gráfico for uma pasta de trabalho externa e não estiver disponível, ela será recuperada do cache do gráfico.

```cpp
bool Aspose::Slides::SpreadsheetOptions::get_RecoverWorkbookFromChartCache() override
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

* Classe [SpreadsheetOptions](../)
* Espaço de nomes [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)