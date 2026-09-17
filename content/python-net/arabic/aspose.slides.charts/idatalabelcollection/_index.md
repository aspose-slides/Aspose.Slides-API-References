---
title: IDataLabelCollection class
second_title: مرجع API لـ Aspose.Slides للبايثون عبر .NET
description: 
type: docs
url: /ar/aspose.slides.charts/idatalabelcollection/
---
## IDataLabelCollection class

يمثل تسميات سلسلة.

نوع IDataLabelCollection يكشف عن الأعضاء التالية:

## Properties

| الخاصية | الوصف |
| :- | :- |
| [`default_data_label_format`](/slides/python-net/ar/aspose.slides.charts/idatalabelcollection/default_data_label_format/) | إرجاع التنسيق الافتراضي لجميع تسميات البيانات في المجموعة.<br/>            قراءة فقط [`IDataLabelFormat`](/slides/python-net/ar/aspose.slides.charts/idatalabelformat). |
| [`leader_lines_format`](/slides/python-net/ar/aspose.slides.charts/idatalabelcollection/leader_lines_format/) | يمثل تنسيق خطوط القادة لتسميات البيانات.<br/>             قراءة فقط [`IChartLinesFormat`](/slides/python-net/ar/aspose.slides.charts/ichartlinesformat). |
| [`is_visible`](/slides/python-net/ar/aspose.slides.charts/idatalabelcollection/is_visible/) | False تعني أن تسمية البيانات غير مرئية افتراضيًا (وبالتالي جميع <br/>            أعلام Show* (ShowValue, ...) الخاصة بخصيصة DefaultDataLabelFormat هي false).<br/>            قراءة فقط **bool**. |
| [`count_of_visible_data_labels`](/slides/python-net/ar/aspose.slides.charts/idatalabelcollection/count_of_visible_data_labels/) | يجلب عدد تسميات البيانات المرئية في المجموعة.<br/>            قراءة فقط **int**. |
| [`count`](/slides/python-net/ar/aspose.slides.charts/idatalabelcollection/count/) | يجلب عدد جميع تسميات البيانات في المجموعة.<br/>            قراءة فقط **int**. |
| [`parent_series`](/slides/python-net/ar/aspose.slides.charts/idatalabelcollection/parent_series/) | إرجاع سلسلة الرسم البياني الأصلية.<br/>            قراءة فقط [`IChartSeries`](/slides/python-net/ar/aspose.slides.charts/ichartseries). |
| [`chart`](/slides/python-net/ar/aspose.slides.charts/idatalabelcollection/chart/) |  |
| [`slide`](/slides/python-net/ar/aspose.slides.charts/idatalabelcollection/slide/) |  |
| [`presentation`](/slides/python-net/ar/aspose.slides.charts/idatalabelcollection/presentation/) |  |

يجلب تسمية البيانات للنقطة ذات الفهرس المحدد.

## Indexer

| الاسم | الوصف |
| :- | :- |
| [`[index]`](/slides/python-net/ar/aspose.slides.charts/idatalabelcollection/__getitem__/) |  |

## Methods

| الطريقة | الوصف |
| :- | :- |
| [`hide(self)`](/slides/python-net/ar/aspose.slides.charts/idatalabelcollection/hide/#) | اجعل تسمية البيانات مخفية افتراضيًا عن طريق تعيين جميع أعلام Show* (ShowValue, ...) الخاصة بخصيصة DefaultDataLabelFormat إلى الحالة false.<br/>            ستصبح IsVisible false بعد ذلك. |
| [`index_of(self, value)`](/slides/python-net/ar/aspose.slides.charts/idatalabelcollection/index_of/#idatalabel) | إرجاع فهرس تسمية البيانات المحددة في المجموعة. |


### See Also
* module [`aspose.slides.charts`](/slides/python-net/ar/aspose.slides.charts)
* library [`Aspose.Slides`](/slides/python-net)