---
title: set_Value()
second_title: Referencia de API de Aspose.Slides para C++
description: "Establece el valor de una celda. Escriba System::Object."
type: docs
weight: 40
url: /es/aspose.slides.charts/ichartdatacell/set_value/
---
## IChartDataCell::set_Value(System::SharedPtr\<System::Object\>) method

Establece el valor de una celda. Escriba [System::Object](../../../system/object/).

```cpp
virtual void Aspose::Slides::Charts::IChartDataCell::set_Value(System::SharedPtr<System::Object> value)=0
```

## Observaciones

```cpp
workbook->GetCell(0, u"F2")->set_Value(System::ObjectExt::Box<double>(-2.5));
workbook->GetCell(0, u"G3")->set_Value(System::ObjectExt::Box<double>(6.3));
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [Object](../../../system/object/)
* Clase [IChartDataCell](../)
* Espacio de nombres [Aspose::Slides::Charts](../../)
* Biblioteca [Aspose.Slides](../../../)