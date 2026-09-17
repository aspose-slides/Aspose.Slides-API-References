---
title: ITextFrameFormat class
second_title: مرجع API لـ Aspose.Slides للبايثون عبر .NET
description: 
type: docs
url: /ar/aspose.slides/itextframeformat/
---
## ITextFrameFormat فئة

تحتوي على خصائص تنسيق TextFrame.

يعرض نوع ITextFrameFormat الأعضاء التالية:

## الخصائص

| الخاصية | الوصف |
| :- | :- |
| [`text_style`](/slides/python-net/ar/aspose.slides/itextframeformat/text_style/) | يعيد نمط النص.<br/>            للقراءة فقط [`ITextStyle`](/slides/python-net/ar/aspose.slides/itextstyle). |
| [`margin_left`](/slides/python-net/ar/aspose.slides/itextframeformat/margin_left/) | يعيد أو يعيّن الهامش الأيسر (نقاط) في TextFrame.<br/>            قراءة/كتابة **float**. |
| [`margin_right`](/slides/python-net/ar/aspose.slides/itextframeformat/margin_right/) | يعيد أو يعيّن الهامش الأيمن (نقاط) في TextFrame.<br/>            قراءة/كتابة **float**. |
| [`margin_top`](/slides/python-net/ar/aspose.slides/itextframeformat/margin_top/) | يعيد أو يعيّن الهامش العلوي (نقاط) في TextFrame.<br/>            قراءة/كتابة **float**. |
| [`margin_bottom`](/slides/python-net/ar/aspose.slides/itextframeformat/margin_bottom/) | يعيد أو يعيّن الهامش السفلي (نقاط) في TextFrame.<br/>            قراءة/كتابة **float**. |
| [`wrap_text`](/slides/python-net/ar/aspose.slides/itextframeformat/wrap_text/) | **True** إذا كان النص ملتفًا عند حدود TextFrame.<br/>            قراءة/كتابة [`NullableBool`](/slides/python-net/ar/aspose.slides/nullablebool). |
| [`anchoring_type`](/slides/python-net/ar/aspose.slides/itextframeformat/anchoring_type/) | يعيد أو يعيّن النص العمودي المرجعي في TextFrame.<br/>            قراءة/كتابة [`TextAnchorType`](/slides/python-net/ar/aspose.slides/textanchortype). |
| [`center_text`](/slides/python-net/ar/aspose.slides/itextframeformat/center_text/) | إذا كان NullableBool.True فإن النص يجب أن يكون متمركزًا أفقيًا داخل الصندوق.<br/>            قراءة/كتابة [`NullableBool`](/slides/python-net/ar/aspose.slides/nullablebool). |
| [`text_vertical_type`](/slides/python-net/ar/aspose.slides/itextframeformat/text_vertical_type/) | يحدد اتجاه النص.<br/>            القيمة الناتجة من دوران النص البصري المستخرجة من هذه الخاصية والزاوية المخصصة<br/>            في الخاصية RotationAngle.<br/>            قراءة/كتابة [`TextVerticalType`](/slides/python-net/ar/aspose.slides/textverticaltype). |
| [`autofit_type`](/slides/python-net/ar/aspose.slides/itextframeformat/autofit_type/) | يعيد أو يعيّن وضع الضبط التلقائي للنص.<br/>            قراءة/كتابة [`TextAutofitType`](/slides/python-net/ar/aspose.slides/textautofittype). |
| [`column_count`](/slides/python-net/ar/aspose.slides/itextframeformat/column_count/) | يعيد أو يعيّن عدد الأعمدة في منطقة النص.<br/>            يجب أن تكون هذه القيمة عددًا موجبًا. وإلا سيتم ضبط القيمة إلى صفر. <br/>            القيمة 0 تعني قيمة غير محددة.<br/>            قراءة/كتابة **int**. |
| [`column_spacing`](/slides/python-net/ar/aspose.slides/itextframeformat/column_spacing/) | يعيد أو يعيّن المسافة بين أعمدة النص في منطقة النص (بالنقاط). يجب أن يُطبق هذا فقط <br/>            عندما يكون هناك أكثر من عمود واحد.<br/>            يجب أن تكون هذه القيمة عددًا موجبًا. وإلا سيتم ضبط القيمة إلى صفر. <br/>            قراءة/كتابة **float**. |
| [`three_d_format`](/slides/python-net/ar/aspose.slides/itextframeformat/three_d_format/) | يعيد كائن ThreeDFormat الذي يمثل خصائص التأثير ثلاثي الأبعاد للنص.<br/>            للقراءة فقط [`IThreeDFormat`](/slides/python-net/ar/aspose.slides/ithreedformat). |
| [`keep_text_flat`](/slides/python-net/ar/aspose.slides/itextframeformat/keep_text_flat/) | يعيد أو يعيّن إبقاء النص خارج مشهد ثلاثي الأبعاد تمامًا.<br/>            قراءة/كتابة **bool**. |
| [`rotation_angle`](/slides/python-net/ar/aspose.slides/itextframeformat/rotation_angle/) | يحدد الدوران المخصص الذي يُطبق على النص داخل المربع المحدد. إذا لم يُحدد، يُستخدم دوران الشكل المرافق.<br/>            إذا تم تحديده، يتم تطبيقه بشكل مستقل عن الشكل.<br/>            أي أن الشكل يمكن أن يكون له دوران يضاف إلى أن للنص نفسه دوران يُطبق عليه.<br/>            القيمة الناتجة من دوران النص البصري المستخرجة من هذه الخاصية والنوع العمودي المُعرّف مسبقًا في الخاصية TextVerticalType.<br/>            قراءة/كتابة **float**. |
| [`transform`](/slides/python-net/ar/aspose.slides/itextframeformat/transform/) | يعيد أو يعيّن شكل لف النص.<br/>            قراءة/كتابة [`TextShapeType`](/slides/python-net/ar/aspose.slides/textshapetype). |

## الطرق

| الطريقة | الوصف |
| :- | :- |
| [`get_effective(self)`](/slides/python-net/ar/aspose.slides/itextframeformat/get_effective/#) | يعيد بيانات تنسيق إطار النص الفعّالة مع تطبيق الوراثة. |

### انظر أيضًا
* الوحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* المكتبة [`Aspose.Slides`](/slides/python-net)