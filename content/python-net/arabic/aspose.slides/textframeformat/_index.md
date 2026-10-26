---
title: TextFrameFormat class
second_title: Aspose.Slides لـ Python عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides/textframeformat/
---
## TextFrameFormat class

يتضمن خصائص formatTextFrameFormatting الخاصة بـ TextFrame.

**Inheritance:**[`TextFrameFormat`](/slides/python-net/ar/aspose.slides/textframeformat) → [`PVIObject`](/slides/python-net/ar/aspose.slides/pviobject)

يعرض نوع TextFrameFormat الأعضاء التالية:

## Constructors

| Constructor | Description |
| :- | :- |
| [`__init__(self)`](/slides/python-net/ar/aspose.slides/textframeformat/__init__/#) | Initializes a new instance of [`TextFrameFormat`](/slides/python-net/ar/aspose.slides/textframeformat) class. |

## Properties

| Property | Description |
| :- | :- |
| [`three_d_format`](/slides/python-net/ar/aspose.slides/textframeformat/three_d_format/) | يرجع كائن ThreeDFormat الذي يمثل خصائص تأثير 3D للنص.<br/>            للقراءة فقط [`IThreeDFormat`](/slides/python-net/ar/aspose.slides/ithreedformat). |
| [`margin_left`](/slides/python-net/ar/aspose.slides/textframeformat/margin_left/) | يرجع أو يضبط الهامش الأيسر (نقطة) في TextFrame.<br/>            قراءة/كتابة **float**. |
| [`margin_right`](/slides/python-net/ar/aspose.slides/textframeformat/margin_right/) | يرجع أو يضبط الهامش الأيمن (نقطة) في TextFrame.<br/>            قراءة/كتابة **float**. |
| [`margin_top`](/slides/python-net/ar/aspose.slides/textframeformat/margin_top/) | يرجع أو يضبط الهامش العلوي (نقطة) في TextFrame.<br/>            قراءة/كتابة **float**. |
| [`margin_bottom`](/slides/python-net/ar/aspose.slides/textframeformat/margin_bottom/) | يرجع أو يضبط الهامش السفلي (نقطة) في TextFrame.<br/>            قراءة/كتابة **float**. |
| [`wrap_text`](/slides/python-net/ar/aspose.slides/textframeformat/wrap_text/) | **True** إذا تم التفاف النص عند هوامش TextFrame.<br/>            قراءة/كتابة [`NullableBool`](/slides/python-net/ar/aspose.slides/nullablebool). |
| [`anchoring_type`](/slides/python-net/ar/aspose.slides/textframeformat/anchoring_type/) | يرجع أو يضبط النص عموديًا في TextFrame.<br/>            قراءة/كتابة [`TextAnchorType`](/slides/python-net/ar/aspose.slides/textanchortype). |
| [`center_text`](/slides/python-net/ar/aspose.slides/textframeformat/center_text/) | إذا كان NullableBool.True فإن النص يجب أن يكون مركّزًا أفقيًا داخل الصندوق.<br/>            قراءة/كتابة [`NullableBool`](/slides/python-net/ar/aspose.slides/nullablebool). |
| [`text_vertical_type`](/slides/python-net/ar/aspose.slides/textframeformat/text_vertical_type/) | يحدد اتجاه النص.<br/>            القيمة الناتجة من تدوير النص البصري المستخلصة من هذه الخاصية والزواية المخصصة في خاصية RotationAngle.<br/>            قراءة/كتابة [`TextVerticalType`](/slides/python-net/ar/aspose.slides/textverticaltype). |
| [`autofit_type`](/slides/python-net/ar/aspose.slides/textframeformat/autofit_type/) | يرجع أو يضبط وضع الملاءمة التلقائية للنص.<br/>            قراءة/كتابة [`TextAutofitType`](/slides/python-net/ar/aspose.slides/textautofittype). |
| [`column_count`](/slides/python-net/ar/aspose.slides/textframeformat/column_count/) | يرجع أو يضبط عدد الأعمدة في مساحة النص.<br/>            يجب أن تكون هذه القيمة عددًا موجبًا. وإلا، سيتم تعيين القيمة إلى صفر.<br/>            القيمة 0 تعني قيمة غير محددة.<br/>            قراءة/كتابة **int**. |
| [`column_spacing`](/slides/python-net/ar/aspose.slides/textframeformat/column_spacing/) | يرجع أو يضبط المسافة بين أعمدة النص في مساحة النص (بالنقطة). يجب أن تطبق فقط عندما يكون هناك أكثر من عمود واحد.<br/>            يجب أن تكون هذه القيمة عددًا موجبًا. وإلا، سيتم تعيين القيمة إلى صفر.<br/>            قراءة/كتابة **float**. |
| [`rotation_angle`](/slides/python-net/ar/aspose.slides/textframeformat/rotation_angle/) |حدد التدوير المخصص الذي يُطبق على النص داخل الصندوق المحدد. إذا لم يُحدد، يُستخدم تدوير الشكل المرافق. إذا تم تحديده، يُطبق بشكل مستقل عن الشكل. أي أن الشكل يمكن أن يكون له تدوير بالإضافة إلى أن النص نفسه لديه تدوير خاص به.<br/>            القيمة الناتجة من تدوير النص البصري المستخلصة من هذه الخاصية والنوع الرأسي المحدد مسبقًا في خاصية TextVerticalType.<br/>            قراءة/كتابة **float**. |
| [`transform`](/slides/python-net/ar/aspose.slides/textframeformat/transform/) | يرجع أو يضبط شكل التفاف النص.<br/>            قراءة/كتابة [`TextShapeType`](/slides/python-net/ar/aspose.slides/textshapetype). |
| [`keep_text_flat`](/slides/python-net/ar/aspose.slides/textframeformat/keep_text_flat/) | يرجع أو يضبط إبقاء النص مسطحًا حتى إذا تم تطبيق تأثير تدوير ثلاثي الأبعاد.<br/>            قراءة/كتابة **bool**. |
| [`slide`](/slides/python-net/ar/aspose.slides/textframeformat/slide/) |  |
| [`presentation`](/slides/python-net/ar/aspose.slides/textframeformat/presentation/) |  |
| [`text_style`](/slides/python-net/ar/aspose.slides/textframeformat/text_style/) |  |

## Methods

| Method | Description |
| :- | :- |
| [`get_effective(self)`](/slides/python-net/ar/aspose.slides/textframeformat/get_effective/#) | يرجع بيانات تنسيق إطار النص الفعّالة مع تطبيق الوراثة. |


### See Also
* الفئة [`PVIObject`](/slides/python-net/ar/aspose.slides/pviobject)
* الفئة [`TextFrameFormat`](/slides/python-net/ar/aspose.slides/textframeformat)
* الوحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* المكتبة [`Aspose.Slides`](/slides/python-net)