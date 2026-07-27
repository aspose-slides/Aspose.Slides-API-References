---
title: set_Formula()
second_title: Referência da API Aspose.Slides para C++
description: Define a fórmula no estilo A1.
type: docs
weight: 66
url: /pt/aspose.slides.charts/ichartdatacell/set_formula/
---
## IChartDataCell::set_Formula(System::String) método

Define a fórmula no estilo A1.

```cpp
virtual void Aspose::Slides::Charts::IChartDataCell::set_Formula(System::String value)=0
```

## Observações



```cpp
auto cell = workbook->GetCell(0, u"B2");
cell->set_Formula(u"1 + SUM(F2:H5)");
```

## Veja Também

* Classe [String](../../../system/string/)
* Classe [IChartDataCell](../)
* Namespace [Aspose::Slides::Charts](../../)
* Biblioteca [Aspose.Slides](../../../)