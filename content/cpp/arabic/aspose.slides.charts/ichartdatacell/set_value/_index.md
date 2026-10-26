---
title: set_Value()
second_title: Aspose.Slides لمرجع API للغة C++
description: "يضبط قيمة الخلية. اكتب System::Object."
type: docs
weight: 40
url: /ar/aspose.slides.charts/ichartdatacell/set_value/
---
## IChartDataCell::set_Value(System::SharedPtr\<System::Object\>) طريقة

يقوم بتعيين قيمة الخلية. اكتب [System::Object](../../../system/object/).

```cpp
virtual void Aspose::Slides::Charts::IChartDataCell::set_Value(System::SharedPtr<System::Object> value)=0
```

## ملاحظات



```cpp
workbook->GetCell(0, u"F2")->set_Value(System::ObjectExt::Box<double>(-2.5));
workbook->GetCell(0, u"G3")->set_Value(System::ObjectExt::Box<double>(6.3));
```




## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [Object](../../../system/object/)
* فئة [IChartDataCell](../)
* مساحة الاسم [Aspose::Slides::Charts](../../)
* مكتبة [Aspose.Slides](../../../)