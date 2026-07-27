---
title: set_RecoverWorkbookFromChartCache()
second_title: Referência da API Aspose.Slides para C++
description: Se a fonte de dados do gráfico for uma pasta de trabalho externa e ela não estiver disponível, será recuperada a partir do cache do gráfico.
type: docs
weight: 40
url: /pt/aspose.slides/spreadsheetoptions/set_recoverworkbookfromchartcache/
---
## SpreadsheetOptions::set_RecoverWorkbookFromChartCache(bool) método


Se a fonte de dados do gráfico for uma pasta de trabalho externa e ela não estiver disponível, será recuperada a partir do cache do gráfico.

```cpp
void Aspose::Slides::SpreadsheetOptions::set_RecoverWorkbookFromChartCache(bool value) override
```

## Observações



Example: 
```cpp
auto loadOptions = MakeObject<LoadOptions>();
loadOptions->set_SpreadsheetOptions(System::MakeObject<SpreadsheetOptions>());
loadOptions->get_SpreadsheetOptions()->set_RecoverWorkbookFromChartCache(true);

auto pres = MakeObject<Presentation>(u"Presentation.pptx", loadOptions);
auto chart = AsCast<Aspose::Slides::Charts::IChart>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto recoveredWorkbook = chart->get_ChartData()->get_ChartDataWorkbook();
```

## Ver Também

* Classe [SpreadsheetOptions](../)
* Espaço de nomes [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)