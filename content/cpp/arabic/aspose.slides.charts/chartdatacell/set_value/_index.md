---
title: set_Value()
second_title: مرجع API الخاص بـ Aspose.Slides للغة C++
description: "يضبط قيمة الخلية. اكتب System::Object."
type: docs
weight: 40
url: /ar/aspose.slides.charts/chartdatacell/set_value/
---
## ChartDataCell::set_Value(System::SharedPtr\<System::Object\>) طريقة

يضبط قيمة الخلية. اكتب [System::Object](../../../system/object/).

```cpp
void Aspose::Slides::Charts::ChartDataCell::set_Value(System::SharedPtr<System::Object> value) override
```

## ملاحظات



```cpp
workbook->GetCell(0, u"F2")->set_Value(System::ObjectExt::Box<double>(-2.5));
workbook->GetCell(0, u"G3")->set_Value(System::ObjectExt::Box<double>(6.3));
```




## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [Object](../../../system/object/)
* فئة [ChartDataCell](../)
* مساحة الاسم [Aspose::Slides::Charts](../../)
* مكتبة [Aspose.Slides](../../../)