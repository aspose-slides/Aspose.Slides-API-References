---
title: set_Value()
second_title: Aspose.Slides for C++ API संदर्भ
description: "सेल का मान सेट करता है। लिखें System::Object."
type: docs
weight: 40
url: /hi/aspose.slides.charts/ichartdatacell/set_value/
---
## IChartDataCell::set_Value(System::SharedPtr\<System::Object\>) विधि

सेल का मान सेट करता है। लिखें [System::Object](../../../system/object/).

```cpp
virtual void Aspose::Slides::Charts::IChartDataCell::set_Value(System::SharedPtr<System::Object> value)=0
```

## टिप्पणियाँ



```cpp
workbook->GetCell(0, u"F2")->set_Value(System::ObjectExt::Box<double>(-2.5));
workbook->GetCell(0, u"G3")->set_Value(System::ObjectExt::Box<double>(6.3));
```




## संबंधित देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [IChartDataCell](../)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)