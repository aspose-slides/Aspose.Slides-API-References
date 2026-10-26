---
title: set_RecoverWorkbookFromChartCache()
second_title: Referencia de API de Aspose.Slides para C++
description: Si la fuente de datos para el gráfico es un libro de trabajo externo y no está disponible, se recuperará del caché del gráfico.
type: docs
weight: 40
url: /es/aspose.slides/spreadsheetoptions/set_recoverworkbookfromchartcache/
---
## SpreadsheetOptions::set_RecoverWorkbookFromChartCache(bool) método

Si la fuente de datos para el gráfico es un libro de trabajo externo y no está disponible, se recuperará del caché del gráfico.

```cpp
void Aspose::Slides::SpreadsheetOptions::set_RecoverWorkbookFromChartCache(bool value) override
```

## Observaciones

Ejemplo: 
```cpp
auto loadOptions = MakeObject<LoadOptions>();
loadOptions->set_SpreadsheetOptions(System::MakeObject<SpreadsheetOptions>());
loadOptions->get_SpreadsheetOptions()->set_RecoverWorkbookFromChartCache(true);

auto pres = MakeObject<Presentation>(u"Presentation.pptx", loadOptions);
auto chart = AsCast<Aspose::Slides::Charts::IChart>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto recoveredWorkbook = chart->get_ChartData()->get_ChartDataWorkbook();
```

## Ver también

* Clase [SpreadsheetOptions](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)