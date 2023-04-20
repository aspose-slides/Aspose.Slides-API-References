---
title: set_Value()
second_title: Aspose.Slides for C++ API Reference
description: "Sets the value of a cell. Write System::Object."
type: docs
weight: 40
url: /cpp/aspose.slides.charts/chartdatacell/set_value/
---
## ChartDataCell::set_Value(System::SharedPtr\<System::Object\>) method


Sets the value of a cell. Write [System::Object](../../../system/object/).

```cpp
void Aspose::Slides::Charts::ChartDataCell::set_Value(System::SharedPtr<System::Object> value) override
```

## Remarks



```cpp
workbook->GetCell(0, u"F2")->set_Value(System::ObjectExt::Box<double>(-2.5));
workbook->GetCell(0, u"G3")->set_Value(System::ObjectExt::Box<double>(6.3));
```




## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [ChartDataCell](../)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)