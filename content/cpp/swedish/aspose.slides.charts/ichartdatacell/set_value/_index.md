---
title: set_Value()
second_title: Aspose.Slides för C++ API-referens
description: "Sätter värdet på en cell. Skriv System::Object."
type: docs
weight: 40
url: /sv/aspose.slides.charts/ichartdatacell/set_value/
---
## IChartDataCell::set_Value(System::SharedPtr\<System::Object\>) metod


Sätter värdet på en cell. Skriv [System::Object](../../../system/object/).

```cpp
virtual void Aspose::Slides::Charts::IChartDataCell::set_Value(System::SharedPtr<System::Object> value)=0
```

## Anmärkningar


```cpp
workbook->GetCell(0, u"F2")->set_Value(System::ObjectExt::Box<double>(-2.5));
workbook->GetCell(0, u"G3")->set_Value(System::ObjectExt::Box<double>(6.3));
```




## Se även

* Typdefinition [SharedPtr](../../../system/sharedptr/)
* Klass [Object](../../../system/object/)
* Klass [IChartDataCell](../)
* Namnrymd [Aspose::Slides::Charts](../../)
* Bibliotek [Aspose.Slides](../../../)