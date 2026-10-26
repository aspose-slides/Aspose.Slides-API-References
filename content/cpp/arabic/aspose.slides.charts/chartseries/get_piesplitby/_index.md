---
title: get_PieSplitBy()
second_title: مرجع API Aspose.Slides للغة C++
description: يحدد كيفية تحديد أي نقاط البيانات توجد في الفطيرة أو الشريط الثاني في مخطط فطيرة-فطيرة أو شريط-فطيرة. هذه الخاصية ليست فقط لهذه السلسلة بل لجميع السلاسل في مجموعة السلاسل الأصلية – هذا إسقاط للخاصية المناسبة للمجموعة. وبالتالي هذه الخاصية للقراءة فقط. استخدم خاصية ParentSeriesGroup للوصول إلى مجموعة السلاسل الأصلية. استخدم get_ParentSeriesGroup()->get(set)_PieSplitBy() خاصية قراءة/كتابة لتغيير القيمة. للقراءة فقط PieSplitType.
type: docs
weight: 755
url: /ar/aspose.slides.charts/chartseries/get_piesplitby/
---
## ChartSeries::get_PieSplitBy() طريقة

يحدد كيفية تحديد أي نقاط البيانات تكون في الفطيرة أو الشريط الثاني في مخطط فطيرة-فطيرة أو شريط-فطيرة. هذه الخاصية ليست فقط لهذه السلسلة بل لجميع السلاسل في مجموعة السلاسل الأصلية – هذا إسقاط للخاصية المناسبة للمجموعة. وبالتالي هذه الخاصية للقراءة فقط. استخدم خاصية ParentSeriesGroup للوصول إلى مجموعة السلاسل الأصلية. استخدم [get_ParentSeriesGroup()](../get_parentseriesgroup/)->get(set)_PieSplitBy() خاصية قراءة/كتابة لتغيير القيمة. للقراءة فقط [PieSplitType](../../piesplittype/).

```cpp
PieSplitType Aspose::Slides::Charts::ChartSeries::get_PieSplitBy() override
```

## ملاحظات

1) هذا هو إسقاط الخاصية [get_ParentSeriesGroup()](../get_parentseriesgroup/)->get(set)_PieSplitBy(). 2) إذا كانت قيمة الخاصية [PieSplitType::Custom](../../piesplittype/) يمكنك تعريف معلومات تقسيم مخصصة باستخدام خاصية [get_ParentSeriesGroup()](../get_parentseriesgroup/)->[get_PieSplitCustomPoints()](../get_piesplitcustompoints/).

## انظر أيضًا

* Enum [PieSplitType](../../piesplittype/)
* فئة [ChartSeries](../)
* نطاق [Aspose::Slides::Charts](../../)
* مكتبة [Aspose.Slides](../../../)