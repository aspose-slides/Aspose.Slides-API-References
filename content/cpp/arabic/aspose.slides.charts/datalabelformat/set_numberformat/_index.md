---
title: set_NumberFormat()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: "يمثل سلسلة التنسيق لكائن DataLabels. اكتب System::String."
type: docs
weight: 40
url: /ar/aspose.slides.charts/datalabelformat/set_numberformat/
---
## DataLabelFormat::set_NumberFormat(System::String) طريقة

تمثل سلسلة التنسيق لكائن DataLabels. اكتب [System::String](../../../system/string/).

```cpp
void Aspose::Slides::Charts::DataLabelFormat::set_NumberFormat(System::String value) override
```

## ملاحظات

```cpp
auto defaultDataLabelFormat = series->get_Labels()->get_DefaultDataLabelFormat();
defaultDataLabelFormat->set_ShowValue(true);
defaultDataLabelFormat->set_IsNumberFormatLinkedToSource(false);
defaultDataLabelFormat->set_NumberFormat(u"0.0%");
```

إذا كان الأصل لهذا الكائن [DataLabelFormat](../) هو مجموعة [DataLabelCollection](../../datalabelcollection/) من تسميات البيانات، فإن هذه الخاصية تحصل أو تعيين القيمة الافتراضية للخاصية NumberFormat لتسميات البيانات الجديدة في مجموعة [DataLabelCollection](../../datalabelcollection/). عند تعيين هذه الخاصية بقيمة، يتم تعيين تلك القيمة أيضًا للخاصية NumberFormat لجميع تسميات البيانات في مجموعة [DataLabelCollection](../../datalabelcollection/) (أي "DataLabels.DefaultDataLabelFormat.NumberFormat = val;" يجعل جميع DataLabels[i].NumberFormat يساوي القيمة).

## انظر أيضًا

* فئة [String](../../../system/string/)
* فئة [DataLabelFormat](../)
* نطاق [Aspose::Slides::Charts](../../)
* مكتبة [Aspose.Slides](../../../)