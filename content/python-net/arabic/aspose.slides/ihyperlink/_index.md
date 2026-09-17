---
title: IHyperlink class
second_title: Aspose.Slides لبايثون عبر .NET مرجع واجهة برمجة التطبيقات
description: 
type: docs
url: /ar/aspose.slides/ihyperlink/
---
## IHyperlink فئة

يمثل ارتباطًا تشعبيًا.

يُظهر نوع IHyperlink الأعضاء التالية:

## الخصائص

| خاصية | الوصف |
| :- | :- |
| [`action_type`](/slides/python-net/ar/aspose.slides/ihyperlink/action_type/) | يرجع نوع إجراء HyperLinkEx.<br/>            للقراءة فقط [`HyperlinkActionType`](/slides/python-net/ar/aspose.slides/hyperlinkactiontype). |
| [`external_url`](/slides/python-net/ar/aspose.slides/ihyperlink/external_url/) | يحدد عنوان URL الخارجي<br/>            إذا أصبحت هذه الخاصية غير None فإن خاصية TargetSlide تصبح None.<br/>            للقراءة فقط **str**. |
| [`external_url_original`](/slides/python-net/ar/aspose.slides/ihyperlink/external_url_original/) | يمثل ارتباطًا تشعبيًا يتم تعيينه لهذا الجزء دون اعتبار لمحتوى الجزء الفعلي.<br/>            <br/>            يتعامل PowerPoint بطريقة خاصة مع الروابط والنص المقابل لها في الجزء. يسمح بإنشاء نص للارتباط التشعبي على شكل عنوان URL صالح، مختلف عن العنوان الحقيقي للرابط. في هذه الحالة، عند عرض الرابط في نافذة التحرير، سيتم تغييره ليتطابق مع الجزء النصي. تمثل هذه الخاصية القيمة الأصلية للارتباط التشعبي. |
| [`target_slide`](/slides/python-net/ar/aspose.slides/ihyperlink/target_slide/) | إذا كان HyperlinkEx يستهدف شريحة محددة فسيعيد هذه الشريحة.<br/>            إذا أصبحت الخاصية غير None فإن خاصية ExternalUrl تصبح None.<br/>            للقراءة فقط [`ISlide`](/slides/python-net/ar/aspose.slides/islide). |
| [`target_frame`](/slides/python-net/ar/aspose.slides/ihyperlink/target_frame/) | يرجع الإطار داخل مجموعة إطارات HTML الأب للهدف<br/>            للارتباط التشعبي الأب عندما يكون موجودًا.<br/>            قراءة/كتابة **str**. |
| [`tooltip`](/slides/python-net/ar/aspose.slides/ihyperlink/tooltip/) | يرجع السلسلة التي قد تُعرض في واجهة المستخدم<br/>            كمرتبطة بالارتباط التشعبي الأب.<br/>            قراءة/كتابة **str**. |
| [`history`](/slides/python-net/ar/aspose.slides/ihyperlink/history/) | يحدد ما إذا كان هدف الارتباط التشعبي الأب سيُضاف<br/>            إلى قائمة الروابط التي تم عرضها عند استدعائه.<br/>            قراءة/كتابة **bool**. |
| [`highlight_click`](/slides/python-net/ar/aspose.slides/ihyperlink/highlight_click/) | يحدد ما إذا كان يجب تمييز الارتباط التشعبي عند النقر.<br/>            قراءة/كتابة **bool**. |
| [`stop_sound_on_click`](/slides/python-net/ar/aspose.slides/ihyperlink/stop_sound_on_click/) | يحدد ما إذا كان يجب إيقاف الصوت عند النقر على الارتباط التشعبي.<br/>            قراءة/كتابة **bool**. |
| [`sound`](/slides/python-net/ar/aspose.slides/ihyperlink/sound/) | يمثل الصوت الجاري للارتباط التشعبي.<br/>            قراءة/كتابة [`IAudio`](/slides/python-net/ar/aspose.slides/iaudio). |
| [`color_source`](/slides/python-net/ar/aspose.slides/ihyperlink/color_source/) | يمثل مصدر لون الارتباط التشعبي - إما الأنماط أو تنسيق الجزء.<br/>            قراءة/كتابة [`HyperlinkColorSource`](/slides/python-net/ar/aspose.slides/hyperlinkcolorsource). |

## الطرق

| طريقة | الوصف |
| :- | :- |
| [`equals(self, hlink)`](/slides/python-net/ar/aspose.slides/ihyperlink/equals/#ihyperlink) | يحدد ما إذا كان مثلي Hyperlink متساويين. |

### انظر أيضًا
* الوحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* المكتبة [`Aspose.Slides`](/slides/python-net)