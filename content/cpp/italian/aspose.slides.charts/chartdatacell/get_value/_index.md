---
title: get_Value()
second_title: Riferimento API di Aspose.Slides per C++
description: "Ottiene il valore di una cella. Leggi System::Object."
type: docs
weight: 27
url: /it/aspose.slides.charts/chartdatacell/get_value/
---
## ChartDataCell::get_Value() metodo

Ottiene il valore di una cella. Leggi [System::Object](../../../system/object/).

```cpp
System::SharedPtr<System::Object> Aspose::Slides::Charts::ChartDataCell::get_Value() override
```

## Osservazioni



```cpp
workbook->GetCell(0, u"F2")->set_Value(System::ObjectExt::Box<double>(-2.5));
workbook->GetCell(0, u"G3")->set_Value(System::ObjectExt::Box<double>(6.3));
```




## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Object](../../../system/object/)
* Classe [ChartDataCell](../)
* Spazio dei nomi [Aspose::Slides::Charts](../../)
* Libreria [Aspose.Slides](../../../)