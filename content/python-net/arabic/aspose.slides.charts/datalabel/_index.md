---
title: DataLabel class
second_title: Aspose.Slides لـ Python عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides.charts/datalabel/
---
## DataLabel فئة

يمثل تسميات السلسلة.

نوع DataLabel يعرض الأعضاء التالية:

## المنشئات

| المنشئ | الوصف |
| :- | :- |
| [`__init__(self, parent_immediate)`](/slides/python-net/ar/aspose.slides.charts/datalabel/__init__/#ichartdatapoint) | ينشئ مثالا جديدًا من فئة DataLabel. |

## الخصائص

| الخاصية | الوصف |
| :- | :- |
| [`chart`](/slides/python-net/ar/aspose.slides.charts/datalabel/chart/) | يعيد المخطط الأصلي.<br/>            قراءة فقط [`IChart`](/slides/python-net/ar/aspose.slides.charts/ichart). |
| [`is_visible`](/slides/python-net/ar/aspose.slides.charts/datalabel/is_visible/) | False يعني أن تسمية البيانات غير مرئية (وبالتالي جميع أعلام Show*-flags (ShowValue, ...) تكون false).<br/>            قراءة فقط **bool**. |
| [`text_frame_for_overriding`](/slides/python-net/ar/aspose.slides.charts/datalabel/text_frame_for_overriding/) | يمكن أن يحتوي على نص منسق غني. إذا لم تكن هذه الخاصية None فإن قيمة النص المنسق <br/>            تتجاوز النص المولد تلقائيًا لتسمية البيانات.<br/>            يعني النص المولد تلقائيًا لتسمية البيانات النص الذي تديره خصائص ShowSeriesName، <br/>            ShowValue، ... ويتم تنسيقه باستخدام خاصية TextFormatManager.TextFormat.<br/>            قراءة فقط [`ITextFrame`](/slides/python-net/ar/aspose.slides/itextframe). |
| [`text_format`](/slides/python-net/ar/aspose.slides.charts/datalabel/text_format/) | يعيد تنسيق النص.<br/>            قراءة فقط [`IChartTextFormat`](/slides/python-net/ar/aspose.slides.charts/icharttextformat). |
| [`x`](/slides/python-net/ar/aspose.slides.charts/datalabel/x/) | يعيد أو يحدد إحداثي x لعنوان كنسبة من عرض المخطط.<br/>            قراءة/كتابة **float**. |
| [`y`](/slides/python-net/ar/aspose.slides.charts/datalabel/y/) | يعيد أو يحدد إحداثي y لعنوان كنسبة من ارتفاع المخطط.<br/>            قراءة/كتابة **float**. |
| [`width`](/slides/python-net/ar/aspose.slides.charts/datalabel/width/) | يعيد أو يحدد عرض العنوان كنسبة من عرض المخطط.<br/>            قراءة/كتابة **float**. |
| [`height`](/slides/python-net/ar/aspose.slides.charts/datalabel/height/) | يعيد أو يحدد ارتفاع العنوان كنسبة من ارتفاع المخطط.<br/>            قراءة/كتابة **float**. |
| [`right`](/slides/python-net/ar/aspose.slides.charts/datalabel/right/) | يمين.<br/>            قراءة فقط **float**. |
| [`bottom`](/slides/python-net/ar/aspose.slides.charts/datalabel/bottom/) | أسفل.<br/>            قراءة فقط **float**. |
| [`data_label_format`](/slides/python-net/ar/aspose.slides.charts/datalabel/data_label_format/) | يعيد تنسيق تسمية البيانات.<br/>            قراءة فقط [`IDataLabelFormat`](/slides/python-net/ar/aspose.slides.charts/idatalabelformat). |
| [`value_from_cell`](/slides/python-net/ar/aspose.slides.charts/datalabel/value_from_cell/) | يحصل أو يحدد خلية بيانات دفتر العمل. يُطبق إذا كانت خاصية IDataLabelFormat.ShowLabelValueFromCell تساوي true. |
| [`label_shape_type`](/slides/python-net/ar/aspose.slides.charts/datalabel/label_shape_type/) | يحصل أو يحدد نوع الشكل لتسمية البيانات.<br/>             يعيد [`ShapeType.NOT_DEFINED`](/slides/python-net/ar/aspose.slides/shapetype/NOT_DEFINED) إذا لم يتم تعريف أي شكل. |
| [`actual_x`](/slides/python-net/ar/aspose.slides.charts/datalabel/actual_x/) | يحدد الموقع الفعلي x (اليسار) لعنصر المخطط بالنسبة إلى الزاوية اليسرى العليا للمخطط.<br/>            استدعي الطريقة IChart.ValidateChartLayout() أولاً للحصول على القيم الفعلية. <br/>            قراءة **float**. |
| [`actual_y`](/slides/python-net/ar/aspose.slides.charts/datalabel/actual_y/) | يحدد أعلى العنصر في المخطط نسبة إلى الزاوية اليسرى العليا للمخطط.<br/>            استدعي الطريقة IChart.ValidateChartLayout() أولاً للحصول على القيم الفعلية. <br/>            قراءة **float**. |
| [`actual_width`](/slides/python-net/ar/aspose.slides.charts/datalabel/actual_width/) | يحدد العرض الفعلي لعنصر المخطط. استدعي الطريقة IChart.ValidateChartLayout() أولاً للحصول على القيم الفعلية. <br/>            قراءة **float**. |
| [`actual_height`](/slides/python-net/ar/aspose.slides.charts/datalabel/actual_height/) | يحدد الارتفاع الفعلي لعنصر المخطط. استدعي الطريقة IChart.ValidateChartLayout() أولاً للحصول على القيم الفعلية. <br/>            قراءة **float**. |
| [`slide`](/slides/python-net/ar/aspose.slides.charts/datalabel/slide/) |  |
| [`presentation`](/slides/python-net/ar/aspose.slides.charts/datalabel/presentation/) |  |

## الطرق

| الطريقة | الوصف |
| :- | :- |
| [`hide(self)`](/slides/python-net/ar/aspose.slides.charts/datalabel/hide/#) | اجعل تسمية البيانات مخفية عن طريق ضبط جميع أعلام Show*-flags (ShowValue, ...) إلى الحالة false.<br/>            ستكون IsVisible false بعد ذلك. |
| [`get_actual_label_text(self)`](/slides/python-net/ar/aspose.slides.charts/datalabel/get_actual_label_text/#) | يعيد النص الفعلي للتسمية بناءً على إعدادات DataLabelFormat أو قيمة TextFrameForOverriding.Text. |
| [`add_text_frame_for_overriding(self, text)`](/slides/python-net/ar/aspose.slides.charts/datalabel/add_text_frame_for_overriding/#str) | أبدأ TextFrameForOverriding بالنص الموجود في المعامل "text".<br/>            إذا كان TextFrameForOverriding مبدئًا بالفعل فسيُغير نصه فقط. |

### انظر أيضًا
* الوحدة [`aspose.slides.charts`](/slides/python-net/ar/aspose.slides.charts)
* المكتبة [`Aspose.Slides`](/slides/python-net)