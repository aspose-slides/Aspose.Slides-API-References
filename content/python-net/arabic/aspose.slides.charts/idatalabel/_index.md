---
title: IDataLabel class
second_title: Aspose.Slides للبايثون عبر .NET دليل API
description: 
type: docs
url: /ar/aspose.slides.charts/idatalabel/
---
## فئة IDataLabel

يمثل تسميات السلسلة.

يعرض نوع IDataLabel الأعضاء التالية:

## الخصائص

| خاصية | الوصف |
| :- | :- |
| [`is_visible`](/slides/python-net/ar/aspose.slides.charts/idatalabel/is_visible/) | False يعني أن تسمية البيانات غير مرئية (وبالتالي جميع أعلام Show* (ShowValue, ...) تكون false).<br/>            قراءة فقط **bool**. |
| [`data_label_format`](/slides/python-net/ar/aspose.slides.charts/idatalabel/data_label_format/) | يعيد تنسيق تسمية البيانات.<br/>            قراءة فقط [`IDataLabelFormat`](/slides/python-net/ar/aspose.slides.charts/idatalabelformat). |
| [`value_from_cell`](/slides/python-net/ar/aspose.slides.charts/idatalabel/value_from_cell/) | يحصل أو يعيّن خلية بيانات المصنف. يُطبق إذا كان خاصية IDataLabelFormat.ShowLabelValueFromCell تساوي true. |
| [`label_shape_type`](/slides/python-net/ar/aspose.slides.charts/idatalabel/label_shape_type/) | يحصل أو يعيّن نوع الشكل لتسمية البيانات.<br/>             يعيد [`ShapeType.NOT_DEFINED`](/slides/python-net/ar/aspose.slides/shapetype/NOT_DEFINED) إذا لم يتم تعريف شكل. |
| [`x`](/slides/python-net/ar/aspose.slides.charts/idatalabel/x/) |  |
| [`y`](/slides/python-net/ar/aspose.slides.charts/idatalabel/y/) |  |
| [`width`](/slides/python-net/ar/aspose.slides.charts/idatalabel/width/) |  |
| [`height`](/slides/python-net/ar/aspose.slides.charts/idatalabel/height/) |  |
| [`right`](/slides/python-net/ar/aspose.slides.charts/idatalabel/right/) |  |
| [`bottom`](/slides/python-net/ar/aspose.slides.charts/idatalabel/bottom/) |  |
| [`chart`](/slides/python-net/ar/aspose.slides.charts/idatalabel/chart/) |  |
| [`slide`](/slides/python-net/ar/aspose.slides.charts/idatalabel/slide/) |  |
| [`presentation`](/slides/python-net/ar/aspose.slides.charts/idatalabel/presentation/) |  |
| [`text_frame_for_overriding`](/slides/python-net/ar/aspose.slides.charts/idatalabel/text_frame_for_overriding/) |  |
| [`text_format`](/slides/python-net/ar/aspose.slides.charts/idatalabel/text_format/) |  |
| [`actual_x`](/slides/python-net/ar/aspose.slides.charts/idatalabel/actual_x/) |  |
| [`actual_y`](/slides/python-net/ar/aspose.slides.charts/idatalabel/actual_y/) |  |
| [`actual_width`](/slides/python-net/ar/aspose.slides.charts/idatalabel/actual_width/) |  |
| [`actual_height`](/slides/python-net/ar/aspose.slides.charts/idatalabel/actual_height/) |  |

## الطرق

| طريقة | الوصف |
| :- | :- |
| [`hide(self)`](/slides/python-net/ar/aspose.slides.charts/idatalabel/hide/#) | اجعل تسمية البيانات مخفية عن طريق ضبط جميع أعلام Show* (ShowValue, ...) إلى الحالة false.<br/>            ستكون IsVisible false بعد ذلك. |
| [`get_actual_label_text(self)`](/slides/python-net/ar/aspose.slides.charts/idatalabel/get_actual_label_text/#) | يعيد نص التسمية الفعلي بناءً على إعدادات DataLabelFormat أو قيمة TextFrameForOverriding.Text. |
| [`add_text_frame_for_overriding(self, text)`](/slides/python-net/ar/aspose.slides.charts/idatalabel/add_text_frame_for_overriding/#str) |  |

### أنظر أيضًا
* وحدة [`aspose.slides.charts`](/slides/python-net/ar/aspose.slides.charts)
* مكتبة [`Aspose.Slides`](/slides/python-net)