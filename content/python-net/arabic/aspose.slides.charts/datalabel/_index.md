---
title: DataLabel class
second_title: Aspose.Slides لبايثون عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides.charts/datalabel/
---
## DataLabel فئة

يمثل تسميات السلسلة.

نوع DataLabel يعرض الأعضاء التالية:

## المنشئات

| منشئ | الوصف |
| :- | :- |
| [`__init__(self, parent_immediate)`](/slides/python-net/ar/aspose.slides.charts/datalabel/__init__/#ichartdatapoint) | ينشئ نسخة جديدة من فئة DataLabel. |

## الخصائص

| خاصية | الوصف |
| :- | :- |
| [`chart`](/slides/python-net/ar/aspose.slides.charts/datalabel/chart/) | يعيد الرسم البياني الأب.<br/>            للقراءة فقط [`IChart`](/slides/python-net/ar/aspose.slides.charts/ichart). |
| [`is_visible`](/slides/python-net/ar/aspose.slides.charts/datalabel/is_visible/) | False يعني أن تسمية البيانات غير مرئية (وبالتالي جميع أعلام Show* (ShowValue, ...) تكون false).<br/>            للقراءة فقط **bool**. |
| [`text_frame_for_overriding`](/slides/python-net/ar/aspose.slides.charts/datalabel/text_frame_for_overriding/) | يمكن أن يحتوي على نص منسق غني. إذا لم تكن هذه الخاصية None فإن قيمة النص المنسق هذه <br/>            تتجاوز النص الذي يتم إنشاؤه تلقائيًا لتسمية البيانات.<br/>            النص الذي يتم إنشاؤه تلقائيًا لتسمية البيانات يعني النص الذي تديره خصائص ShowSeriesName، <br/>            ShowValue، ... ويتم تنسيقه باستخدام خاصية TextFormatManager.TextFormat.<br/>            للقراءة فقط [`ITextFrame`](/slides/python-net/ar/aspose.slides/itextframe). |
| [`text_format`](/slides/python-net/ar/aspose.slides.charts/datalabel/text_format/) | يعيد تنسيق النص.<br/>            للقراءة فقط [`IChartTextFormat`](/slides/python-net/ar/aspose.slides.charts/icharttextformat). |
| [`x`](/slides/python-net/ar/aspose.slides.charts/datalabel/x/) | يعيد أو يحدد إحداثي x للعنوان كنسبة من عرض الرسم البياني.<br/>            قابل للقراءة والكتابة **float**. |
| [`y`](/slides/python-net/ar/aspose.slides.charts/datalabel/y/) | يعيد أو يحدد إحداثي y للعنوان كنسبة من ارتفاع الرسم البياني.<br/>            قابل للقراءة والكتابة **float**. |
| [`width`](/slides/python-net/ar/aspose.slides.charts/datalabel/width/) | يعيد أو يحدد عرض العنوان كنسبة من عرض الرسم البياني.<br/>            قابل للقراءة والكتابة **float**. |
| [`height`](/slides/python-net/ar/aspose.slides.charts/datalabel/height/) | يعيد أو يحدد ارتفاع العنوان كنسبة من ارتفاع الرسم البياني.<br/>            قابل للقراءة والكتابة **float**. |
| [`right`](/slides/python-net/ar/aspose.slides.charts/datalabel/right/) | يمين.<br/>            للقراءة فقط **float**. |
| [`bottom`](/slides/python-net/ar/aspose.slides.charts/datalabel/bottom/) | أسفل.<br/>            للقراءة فقط **float**. |
| [`data_label_format`](/slides/python-net/ar/aspose.slides.charts/datalabel/data_label_format/) | يعيد تنسيق تسمية البيانات.<br/>            للقراءة فقط [`IDataLabelFormat`](/slides/python-net/ar/aspose.slides.charts/idatalabelformat). |
| [`value_from_cell`](/slides/python-net/ar/aspose.slides.charts/datalabel/value_from_cell/) | يحصل أو يحدد خلية بيانات المصنف. يطبق إذا كانت خاصية IDataLabelFormat.ShowLabelValueFromCell تساوي true. |
| [`actual_x`](/slides/python-net/ar/aspose.slides.charts/datalabel/actual_x/) | يحدد الموقع الفعلي x (اليسار) لعنصر الرسم البياني بالنسبة للزاوية اليسرى العلوية للرسم البياني.<br/>            استدعِ الطريقة IChart.ValidateChartLayout() مسبقًا للحصول على القيم الفعلية. <br/>            قراءة **float**. |
| [`actual_y`](/slides/python-net/ar/aspose.slides.charts/datalabel/actual_y/) | يحدد أعلى عنصر الرسم البياني الفعلي بالنسبة للزاوية اليسرى العلوية للرسم البياني.<br/>            استدعِ الطريقة IChart.ValidateChartLayout() مسبقًا للحصول على القيم الفعلية. <br/>            قراءة **float**. |
| [`actual_width`](/slides/python-net/ar/aspose.slides.charts/datalabel/actual_width/) | يحدد العرض الفعلي لعنصر الرسم البياني. استدعِ الطريقة IChart.ValidateChartLayout() مسبقًا للحصول على القيم الفعلية. <br/>            قراءة **float**. |
| [`actual_height`](/slides/python-net/ar/aspose.slides.charts/datalabel/actual_height/) | يحدد الارتفاع الفعلي لعنصر الرسم البياني. استدعِ الطريقة IChart.ValidateChartLayout() مسبقًا للحصول على القيم الفعلية. <br/>            قراءة **float**. |
| [`slide`](/slides/python-net/ar/aspose.slides.charts/datalabel/slide/) |  |
| [`presentation`](/slides/python-net/ar/aspose.slides.charts/datalabel/presentation/) |  |

## الطرق

| طريقة | الوصف |
| :- | :- |
| [`hide(self)`](/slides/python-net/ar/aspose.slides.charts/datalabel/hide/#) | اجعل تسمية البيانات مخفية عن طريق ضبط جميع أعلام Show* (ShowValue, ...) إلى الحالة false.<br/>            سيكون IsVisible false بعد ذلك. |
| [`get_actual_label_text(self)`](/slides/python-net/ar/aspose.slides.charts/datalabel/get_actual_label_text/#) | يعيد النص الفعلي للتسمية بناءً على إعدادات DataLabelFormat أو قيمة TextFrameForOverriding.Text. |
| [`add_text_frame_for_overriding(self, text)`](/slides/python-net/ar/aspose.slides.charts/datalabel/add_text_frame_for_overriding/#str) | تهيئة TextFrameForOverriding بالنص الموجود في المعامل "text".<br/>            إذا كان TextFrameForOverriding مُهيأً بالفعل فسيتم تغيير نصه ببساطة. |

### انظر أيضًا
* وحدة [`aspose.slides.charts`](/slides/python-net/ar/aspose.slides.charts)
* مكتبة [`Aspose.Slides`](/slides/python-net)