---
title: set_Value()
second_title: Aspose.Slides för C++ API-referens
description: "Ställer in värdet på en cell. Skriv System::Object."
type: docs
weight: 40
url: /sv/aspose.slides.charts/chartdatacell/set_value/
---
## ChartDataCell::set_Value(System::SharedPtr\<System::Object\>) metod


Ställer in värdet på en cell. Skriv [System::Object](../../../system/object/).

```cpp
void Aspose::Slides::Charts::ChartDataCell::set_Value(System::SharedPtr<System::Object> value) override
```

## Anmärkningar



```cpp
workbook->GetCell(0, u"F2")->set_Value(System::ObjectExt::Box<double>(-2.5));
workbook->GetCell(0, u"G3")->set_Value(System::ObjectExt::Box<double>(6.3));
```




## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [Object](../../../system/object/)
* Klass [ChartDataCell](../)
* Namnrymd [Aspose::Slides::Charts](../../)
* Bibliotek [Aspose.Slides](../../../)