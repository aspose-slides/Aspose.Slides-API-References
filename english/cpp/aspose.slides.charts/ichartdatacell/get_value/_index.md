---
title: get_Value()
second_title: Aspose.Slides for C++ API Reference
description: "Gets the value of a cell. Read System::Object."
type: docs
weight: 27
url: /cpp/aspose.slides.charts/ichartdatacell/get_value/
---
## IChartDataCell::get_Value() method


Gets the value of a cell. Read [System::Object](../../../system/object/).

```cpp
virtual System::SharedPtr<System::Object> Aspose::Slides::Charts::IChartDataCell::get_Value()=0
```

## Remarks



```cpp
workbook->GetCell(0, u"F2")->set_Value(System::ObjectExt::Box<double>(-2.5));
workbook->GetCell(0, u"G3")->set_Value(System::ObjectExt::Box<double>(6.3));
```




## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [IChartDataCell](../)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)
