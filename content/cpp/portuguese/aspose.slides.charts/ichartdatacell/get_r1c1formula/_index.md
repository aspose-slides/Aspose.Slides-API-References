---
title: get_R1C1Formula()
second_title: Referência da API Aspose.Slides para C++
description: Obtém a fórmula no estilo R1C1.
type: docs
weight: 79
url: /pt/aspose.slides.charts/ichartdatacell/get_r1c1formula/
---
## IChartDataCell::get_R1C1Formula() método


Obtém a fórmula no estilo R1C1.

```cpp
virtual System::String Aspose::Slides::Charts::IChartDataCell::get_R1C1Formula()=0
```

## Observações



```cpp
auto cell = workbook->GetCell(0, u"C2");
cell->set_R1C1Formula(u"MAX(R2C6:R5C8) / 3");
```

## Ver também

* Classe [String](../../../system/string/)
* Classe [IChartDataCell](../)
* Espaço de nomes [Aspose::Slides::Charts](../../)
* Biblioteca [Aspose.Slides](../../../)