---
title: set_Value()
second_title: Aspose.Slides के लिए C++ API रेफ़रेंस
description: "किसी सेल का मान सेट करता है। लिखें System::Object."
type: docs
weight: 40
url: /hi/aspose.slides.charts/chartdatacell/set_value/
---
## ChartDataCell::set_Value(System::SharedPtr\<System::Object\>) विधि


किसी सेल का मान सेट करता है। लिखें [System::Object](../../../system/object/).

```cpp
void Aspose::Slides::Charts::ChartDataCell::set_Value(System::SharedPtr<System::Object> value) override
```

## टिप्पणियाँ



```cpp
workbook->GetCell(0, u"F2")->set_Value(System::ObjectExt::Box<double>(-2.5));
workbook->GetCell(0, u"G3")->set_Value(System::ObjectExt::Box<double>(6.3));
```




## देखें भी

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [ChartDataCell](../)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)