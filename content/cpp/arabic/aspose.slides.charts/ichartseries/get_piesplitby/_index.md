---
title: get_PieSplitBy()
second_title: Aspose.Slides للـ C++ مرجع API
description: يحدد كيفية تحديد نقاط البيانات التي تكون في الفتحة الثانية أو العمود في مخطط فطيرة-فطيرة أو شريط-فطيرة. هذه الخاصية ليست فقط لهذه السلسلة بل لجميع سلاسل مجموعة السلسلة الأصلية - هذا إسقاط للخاصية المناسبة للمجموعة. وبالتالي هذه الخاصية للقراءة فقط. استخدم خاصية ParentSeriesGroup للوصول إلى مجموعة السلسلة الأصلية. استخدم get_ParentSeriesGroup()->get(set)_PieSplitBy() خاصية read/write لتغيير القيمة. للقراءة فقط PieSplitType.
type: docs
weight: 729
url: /ar/aspose.slides.charts/ichartseries/get_piesplitby/
---
## IChartSeries::get_PieSplitBy() method

يحدد كيفية تحديد نقاط البيانات التي تكون في الفتحة الثانية أو العمود في مخطط فطيرة-فطيرة أو شريط-فطيرة. هذه الخاصية ليست فقط لهذه السلسلة بل لجميع سلاسل مجموعة السلسلة الأصلية – هي إسقاط لخاصية المجموعة المناسبة. وبالتالي هذه الخاصية للقراءة فقط. استخدم خاصية ParentSeriesGroup للوصول إلى مجموعة السلسلة الأصلية. استخدم [get_ParentSeriesGroup()](../get_parentseriesgroup/)->get(set)_PieSplitBy() خاصية قابلة للقراءة/الكتابة لتغيير القيمة. للقراءة فقط [PieSplitType](../../piesplittype/).

```cpp
virtual PieSplitType Aspose::Slides::Charts::IChartSeries::get_PieSplitBy()=0
```

## ملاحظات

1) هذا هو إسقاط الخاصية [get_ParentSeriesGroup()](../get_parentseriesgroup/)->get(set)_PieSplitBy().
2) إذا كانت قيمة الخاصية هي [PieSplitType::Custom](../../piesplittype/) فيمكنك تعريف معلومات تقسيم مخصصة باستخدام خاصية [get_ParentSeriesGroup()](../get_parentseriesgroup/)->[get_PieSplitCustomPoints()](../get_piesplitcustompoints/).

## انظر أيضًا

* تعداد [PieSplitType](../../piesplittype/)
* فئة [IChartSeries](../)
* نطاق الاسم [Aspose::Slides::Charts](../../)
* مكتبة [Aspose.Slides](../../../)