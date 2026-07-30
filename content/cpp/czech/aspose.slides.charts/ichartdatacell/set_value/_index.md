---
title: set_Value()
second_title: Aspose.Slides pro C++ referenci API
description: "Nastaví hodnotu buňky. Zapište System::Object."
type: docs
weight: 40
url: /cs/aspose.slides.charts/ichartdatacell/set_value/
---
## IChartDataCell::set_Value(System::SharedPtr\<System::Object\>) metoda

Nastaví hodnotu buňky. Zapište [System::Object](../../../system/object/).

```cpp
virtual void Aspose::Slides::Charts::IChartDataCell::set_Value(System::SharedPtr<System::Object> value)=0
```

## Poznámky



```cpp
workbook->GetCell(0, u"F2")->set_Value(System::ObjectExt::Box<double>(-2.5));
workbook->GetCell(0, u"G3")->set_Value(System::ObjectExt::Box<double>(6.3));
```




## Viz také

* Definice typu [SharedPtr](../../../system/sharedptr/)
* Třída [Object](../../../system/object/)
* Třída [IChartDataCell](../)
* Jmenný prostor [Aspose::Slides::Charts](../../)
* Knihovna [Aspose.Slides](../../../)