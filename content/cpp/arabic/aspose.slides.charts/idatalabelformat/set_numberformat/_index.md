---
title: set_NumberFormat()
second_title: Aspose.Slides لـ C++ مرجع واجهة برمجة التطبيقات
description: "يمثل سلسلة التنسيق لكائن DataLabels. اكتب System::String."
type: docs
weight: 40
url: /ar/aspose.slides.charts/idatalabelformat/set_numberformat/
---
## IDataLabelFormat::set_NumberFormat(System::String) طريقة

يمثل سلسلة التنسيق لكائن DataLabels. اكتب [System::String](../../../system/string/).

```cpp
virtual void Aspose::Slides::Charts::IDataLabelFormat::set_NumberFormat(System::String value)=0
```

## ملاحظات

```cpp
auto defaultDataLabelFormat = series->get_Labels()->get_DefaultDataLabelFormat();
defaultDataLabelFormat->set_ShowValue(true);
defaultDataLabelFormat->set_IsNumberFormatLinkedToSource(false);
defaultDataLabelFormat->set_NumberFormat(u"0.0%");
```

إذا كان الأصل لهذا الكائن [DataLabelFormat](../../datalabelformat/) هو مجموعة [DataLabelCollection](../../datalabelcollection/) من تسميات البيانات، فإن هذه الخاصية تحصل على أو تعين القيمة الافتراضية لخاصية NumberFormat لتسميات البيانات الجديدة في مجموعة [DataLabelCollection](../../datalabelcollection/). عند تعيين هذه الخاصية بقيمة، يتم أيضًا تعيين تلك القيمة لخاصية NumberFormat لجميع تسميات البيانات في مجموعة [DataLabelCollection](../../datalabelcollection/) (i.e. "DataLabels.DefaultDataLabelFormat.NumberFormat = val;" يجعل جميع DataLabels[i].NumberFormat تساوي val).

## انظر أيضًا

* الفئة [String](../../../system/string/)
* الفئة [IDataLabelFormat](../)
* مساحة الاسم [Aspose::Slides::Charts](../../)
* المكتبة [Aspose.Slides](../../../)