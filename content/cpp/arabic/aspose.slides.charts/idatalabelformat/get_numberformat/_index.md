---
title: get_NumberFormat()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: "يمثل سلسلة التنسيق لكائن DataLabels. اقرأ System::String."
type: docs
weight: 27
url: /ar/aspose.slides.charts/idatalabelformat/get_numberformat/
---
## IDataLabelFormat::get_NumberFormat() طريقة

يمثل سلسلة التنسيق لكائن DataLabels. اقرأ [System::String](../../../system/string/).

```cpp
virtual System::String Aspose::Slides::Charts::IDataLabelFormat::get_NumberFormat()=0
```

## ملاحظات

```cpp
auto defaultDataLabelFormat = series->get_Labels()->get_DefaultDataLabelFormat();
defaultDataLabelFormat->set_ShowValue(true);
defaultDataLabelFormat->set_IsNumberFormatLinkedToSource(false);
defaultDataLabelFormat->set_NumberFormat(u"0.0%");
```

إذا كان الأصل لهذا الكائن [DataLabelFormat](../../datalabelformat/) هو مجموعة [DataLabelCollection](../../datalabelcollection/) من تسميات البيانات، فإن هذه الخاصية تحصل على أو تعيين القيمة الافتراضية لخاصية NumberFormat لتسميات البيانات الجديدة في مجموعة [DataLabelCollection](../../datalabelcollection/). عندما يتم تعيين هذه الخاصية بقيمة، تُعطى نفس القيمة لخاصية NumberFormat لجميع تسميات البيانات في مجموعة [DataLabelCollection](../../datalabelcollection/) (أي "DataLabels.DefaultDataLabelFormat.NumberFormat = val;" يتسبب في أن يكون جميع DataLabels[i].NumberFormat مساويًا للـ val).

## انظر أيضًا

* الفئة [String](../../../system/string/)
* الفئة [IDataLabelFormat](../)
* مساحة الاسم [Aspose::Slides::Charts](../../)
* المكتبة [Aspose.Slides](../../../)