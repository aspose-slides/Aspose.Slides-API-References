---
title: get_Value()
second_title: Referência da API Aspose.Slides para C++
description: "Obtém o valor de uma célula. Leia System::Object."
type: docs
weight: 27
url: /pt/aspose.slides.charts/ichartdatacell/get_value/
---
## IChartDataCell::get_Value() método


Obtém o valor de uma célula. Leia [System::Object](../../../system/object/).

```cpp
virtual System::SharedPtr<System::Object> Aspose::Slides::Charts::IChartDataCell::get_Value()=0
```

## Observações



```cpp
workbook->GetCell(0, u"F2")->set_Value(System::ObjectExt::Box<double>(-2.5));
workbook->GetCell(0, u"G3")->set_Value(System::ObjectExt::Box<double>(6.3));
```




## Ver Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Object](../../../system/object/)
* Classe [IChartDataCell](../)
* Espaço de nomes [Aspose::Slides::Charts](../../)
* Biblioteca [Aspose.Slides](../../../)