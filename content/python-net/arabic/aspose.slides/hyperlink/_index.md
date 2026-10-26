---
title: Hyperlink class
second_title: مرجع API لأسبوز سلايدز للبايثون عبر .NET
description: 
type: docs
url: /ar/aspose.slides/hyperlink/
---
## فئة Hyperlink

يمثل Hyperlink.

**الوراثة:**[`Hyperlink`](/slides/python-net/ar/aspose.slides/hyperlink) → [`PVIObject`](/slides/python-net/ar/aspose.slides/pviobject)

نوع Hyperlink يوضح الأعضاء التالية:

## المنشئات

| منشئ | الوصف |
| :- | :- |
| [`__init__(self, url)`](/slides/python-net/ar/aspose.slides/hyperlink/__init__/#str) | ينشئ نسخة من Hyperlink. |
| [`__init__(self, slide)`](/slides/python-net/ar/aspose.slides/hyperlink/__init__/#islide) | ينشئ نسخة من Hyperlink يشير إلى شريحة معينة.<br/>            ملاحظة: يجب تعيين Hyperlink المُنشئ إلى كائن ما من نفس العرض التقديمي، وإلا سيُحفظ الرابط كـ NoAction. |
| [`__init__(self, source, target_frame, tooltip, history, stop_sounds_on_click, highlight_click)`](/slides/python-net/ar/aspose.slides/hyperlink/__init__/#hyperlink-str-str-bool-bool-bool) | ينشئ نسخة من Hyperlink باستخدام Hyperlink آخر كمصدر، متجاوزًا الخصائص الثانوية. |

## الخصائص

| خاصية | الوصف |
| :- | :- |
| [`no_action`](/slides/python-net/ar/aspose.slides/hyperlink/no_action/) | يرجع Hyperlink خاص "لا تفعل شيئًا".<br/>            قراءة فقط [`Hyperlink`](/slides/python-net/ar/aspose.slides/hyperlink). |
| [`media`](/slides/python-net/ar/aspose.slides/hyperlink/media/) | يرجع Hyperlink خاص "تشغيل ملف وسائط". يُستخدم في AudioFrame و VideoFrame.<br/>            قراءة فقط [`Hyperlink`](/slides/python-net/ar/aspose.slides/hyperlink). |
| [`next_slide`](/slides/python-net/ar/aspose.slides/hyperlink/next_slide/) | يرجع Hyperlink إلى الشريحة التالية.<br/>            قراءة فقط [`Hyperlink`](/slides/python-net/ar/aspose.slides/hyperlink). |
| [`previous_slide`](/slides/python-net/ar/aspose.slides/hyperlink/previous_slide/) | يرجع Hyperlink إلى الشريحة السابقة.<br/>            قراءة فقط [`Hyperlink`](/slides/python-net/ar/aspose.slides/hyperlink). |
| [`first_slide`](/slides/python-net/ar/aspose.slides/hyperlink/first_slide/) | يرجع Hyperlink إلى الشريحة الأولى للعرض التقديمي.<br/>            قراءة فقط [`Hyperlink`](/slides/python-net/ar/aspose.slides/hyperlink). |
| [`last_slide`](/slides/python-net/ar/aspose.slides/hyperlink/last_slide/) | يرجع Hyperlink إلى الشريحة الأخيرة للعرض التقديمي.<br/>            قراءة فقط [`Hyperlink`](/slides/python-net/ar/aspose.slides/hyperlink). |
| [`last_vieved_slide`](/slides/python-net/ar/aspose.slides/hyperlink/last_vieved_slide/) | يرجع Hyperlink إلى الشريحة الأخيرة التي تم عرضها.<br/>            قراءة فقط [`Hyperlink`](/slides/python-net/ar/aspose.slides/hyperlink). |
| [`end_show`](/slides/python-net/ar/aspose.slides/hyperlink/end_show/) | يرجع Hyperlink يُنهي العرض.<br/>            قراءة فقط [`Hyperlink`](/slides/python-net/ar/aspose.slides/hyperlink). |
| [`action_type`](/slides/python-net/ar/aspose.slides/hyperlink/action_type/) | يرجع نوع إجراء Hyperlink.<br/>            قراءة فقط [`HyperlinkActionType`](/slides/python-net/ar/aspose.slides/hyperlinkactiontype). |
| [`external_url`](/slides/python-net/ar/aspose.slides/hyperlink/external_url/) | يحدد عنوان URL الخارجي.<br/>            قراءة فقط **str**. |
| [`target_slide`](/slides/python-net/ar/aspose.slides/hyperlink/target_slide/) | إذا كان Hyperlink يستهدف شريحة معينة، يرجع هذه الشريحة.<br/>            قراءة فقط [`ISlide`](/slides/python-net/ar/aspose.slides/islide). |
| [`external_url_original`](/slides/python-net/ar/aspose.slides/hyperlink/external_url_original/) | يمثل Hyperlink يُعيَّن لهذا الجزء دون اعتبار لمحتوى الجزء الفعلي.<br/>            <br/>            يتعامل PowerPoint بطريقة خاصة مع الروابط والنص المقابل لها في الجزء. يسمح بإنشاء نص للـ Hyperlink على<br/>            شكل عنوان URL صالح، يختلف عن العنوان الحقيقي للربط. في هذه الحالة، عند عرض الرابط في نافذة التحرير، سيتغير<br/>            ليطابق نص الجزء. هذه الخاصية تمثل القيمة الأصلية للـ Hyperlink. |
| [`target_frame`](/slides/python-net/ar/aspose.slides/hyperlink/target_frame/) | يرجع الإطار ضمن مجموعة إطارات HTML الأصلية للهدف<br/>            من Hyperlink الأصل عندما يكون موجودًا.<br/>            قراءة/كتابة **str**. |
| [`tooltip`](/slides/python-net/ar/aspose.slides/hyperlink/tooltip/) | يرجع السلسلة التي قد تُظهر في واجهة المستخدم<br/>            كمرتبطة بـ Hyperlink الأصل.<br/>            قراءة/كتابة **str**. |
| [`history`](/slides/python-net/ar/aspose.slides/hyperlink/history/) | يحدد ما إذا كان هدف Hyperlink الأصل سيُضاف<br/>            إلى قائمة الروابط التي عُرضت عند استدعائه.<br/>            قراءة/كتابة **bool**. |
| [`highlight_click`](/slides/python-net/ar/aspose.slides/hyperlink/highlight_click/) | يحدد ما إذا كان يجب تمييز الـ Hyperlink عند النقر.<br/>            قراءة/كتابة **bool**. |
| [`stop_sound_on_click`](/slides/python-net/ar/aspose.slides/hyperlink/stop_sound_on_click/) | يحدد ما إذا كان يجب إيقاف الصوت عند النقر على الـ Hyperlink.<br/>            قراءة/كتابة **bool**. |
| [`sound`](/slides/python-net/ar/aspose.slides/hyperlink/sound/) | يمثل الصوت الجاري تشغيله للـ Hyperlink.<br/>            قراءة/كتابة [`IAudio`](/slides/python-net/ar/aspose.slides/iaudio). |
| [`color_source`](/slides/python-net/ar/aspose.slides/hyperlink/color_source/) | يمثل مصدر لون الـ Hyperlink - إما الأنماط أو تنسيق الجزء.<br/>            قراءة/كتابة [`HyperlinkColorSource`](/slides/python-net/ar/aspose.slides/hyperlinkcolorsource). |
| [`slide`](/slides/python-net/ar/aspose.slides/hyperlink/slide/) |  |
| [`presentation`](/slides/python-net/ar/aspose.slides/hyperlink/presentation/) |  |

## الطرق

| طريقة | الوصف |
| :- | :- |
| [`equals(self, hlink)`](/slides/python-net/ar/aspose.slides/hyperlink/equals/#ihyperlink) | يحدد ما إذا كانت مثلتي Hyperlink متساويتين. |

### انظر أيضًا
* فئة [`Hyperlink`](/slides/python-net/ar/aspose.slides/hyperlink)
* فئة [`PVIObject`](/slides/python-net/ar/aspose.slides/pviobject)
* وحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* مكتبة [`Aspose.Slides`](/slides/python-net)