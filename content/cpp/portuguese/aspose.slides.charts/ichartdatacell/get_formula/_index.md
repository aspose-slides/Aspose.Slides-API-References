---
title: get_Formula()
second_title: Referência da API Aspose.Slides para C++
description: Obtém a fórmula no estilo A1.
type: docs
weight: 53
url: /pt/aspose.slides.charts/ichartdatacell/get_formula/
---
## IChartDataCell::get_Formula() método


Obtém a fórmula no estilo A1.

```cpp
virtual System::String Aspose::Slides::Charts::IChartDataCell::get_Formula()=0
```

## Observações



```cpp
auto cell = workbook->GetCell(0, u"B2");
cell->set_Formula(u"1 + SUM(F2:H5)");
```

## Veja também

* Classe [String](../../../system/string/)
* Classe [IChartDataCell](../)
* Espaço de nomes [Aspose::Slides::Charts](../../)
* Biblioteca [Aspose.Slides](../../../)