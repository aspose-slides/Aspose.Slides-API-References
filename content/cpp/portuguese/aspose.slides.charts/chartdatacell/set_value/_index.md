---
title: set_Value()
second_title: Aspose.Slides para C++ Referência da API
description: "Define o valor de uma célula. Escreva System::Object."
type: docs
weight: 40
url: /pt/aspose.slides.charts/chartdatacell/set_value/
---
## ChartDataCell::set_Value(System::SharedPtr\<System::Object\>) método


Define o valor de uma célula. Escreva [System::Object](../../../system/object/).

```cpp
void Aspose::Slides::Charts::ChartDataCell::set_Value(System::SharedPtr<System::Object> value) override
```

## Observações



```cpp
workbook->GetCell(0, u"F2")->set_Value(System::ObjectExt::Box<double>(-2.5));
workbook->GetCell(0, u"G3")->set_Value(System::ObjectExt::Box<double>(6.3));
```




## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Object](../../../system/object/)
* Classe [ChartDataCell](../)
* Espaço de nomes [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)