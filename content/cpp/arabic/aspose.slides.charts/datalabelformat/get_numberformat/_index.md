---
title: get_NumberFormat()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: "يمثل سلسلة التنسيق لكائن DataLabels. اقرأ System::String."
type: docs
weight: 27
url: /ar/aspose.slides.charts/datalabelformat/get_numberformat/
---
## DataLabelFormat::get_NumberFormat() طريقة

يمثل سلسلة التنسيق لكائن DataLabels. اقرأ [System::String](../../../system/string/).

```cpp
System::String Aspose::Slides::Charts::DataLabelFormat::get_NumberFormat() override
```

## ملاحظات



```cpp
auto defaultDataLabelFormat = series->get_Labels()->get_DefaultDataLabelFormat();
defaultDataLabelFormat->set_ShowValue(true);
defaultDataLabelFormat->set_IsNumberFormatLinkedToSource(false);
defaultDataLabelFormat->set_NumberFormat(u"0.0%");
```



إذا كان الأصل لهذا الكائن [DataLabelFormat](../) هو مجموعة [DataLabelCollection](../../datalabelcollection/) من ملصقات البيانات، فإن هذه الخاصية تحصل على القيمة الافتراضية أو تعيينها لخاصية NumberFormat لملصقات البيانات الجديدة في مجموعة [DataLabelCollection](../../datalabelcollection/). عندما يتم تعيين هذه الخاصية بقيمة، تُضبط تلك القيمة أيضًا لخاصية NumberFormat لجميع ملصقات البيانات في مجموعة [DataLabelCollection](../../datalabelcollection/) (على سبيل المثال "DataLabels.DefaultDataLabelFormat.NumberFormat = val;" يجعل جميع DataLabels[i].NumberFormat تساوي val). 


## انظر أيضًا

* الفئة [String](../../../system/string/)
* الفئة [DataLabelFormat](../)
* النطاق [Aspose::Slides::Charts](../../)
* المكتبة [Aspose.Slides](../../../)