---
title: ISlideShowTransition class
second_title: مرجع API Aspose.Slides للبايثون عبر .NET
description: 
type: docs
url: /ar/aspose.slides/islideshowtransition/
---
## ISlideShowTransition فئة

يمثّل انتقال عرض الشرائح.

نوع ISlideShowTransition يعرض الأعضاء التالية:

## الخصائص

| Property | Description |
| :- | :- |
| [`sound`](/slides/python-net/ar/aspose.slides/islideshowtransition/sound/) | يعيد أو يعيّن بيانات الصوت المدمجة.<br/>            قابل للقراءة والكتابة [`IAudio`](/slides/python-net/ar/aspose.slides/iaudio). |
| [`sound_mode`](/slides/python-net/ar/aspose.slides/islideshowtransition/sound_mode/) | يعيّن أو يرجّع وضع الصوت للانتقال بين الشرائح.<br/>            قابل للقراءة والكتابة [`TransitionSoundMode`](/slides/python-net/ar/aspose.slides.slideshow/transitionsoundmode). |
| [`sound_loop`](/slides/python-net/ar/aspose.slides/islideshowtransition/sound_loop/) | هذه الخاصية تحدد ما إذا كان الصوت سيُعيد التشغيل حتى يحدث حدث صوتي التالي في<br/>            عرض الشرائح.<br/>            قابل للقراءة والكتابة **bool**. |
| [`advance_on_click`](/slides/python-net/ar/aspose.slides/islideshowtransition/advance_on_click/) | تحدد ما إذا كانت نقرة الفأرة ستتحرك إلى الشريحة التالية أم لا. إذا لم يتم تحديد هذه الخاصية<br/>            فسيُفترض أن القيمة true.<br/>            قابل للقراءة والكتابة **bool**. |
| [`advance_after`](/slides/python-net/ar/aspose.slides/islideshowtransition/advance_after/) | هذه الخاصية تحدد ما إذا كان عرض الشرائح سيتنقل إلى الشريحة التالية بعد زمن معين.<br/>            قابل للقراءة والكتابة **bool**. |
| [`advance_after_time`](/slides/python-net/ar/aspose.slides/islideshowtransition/advance_after_time/) | تحدد الوقت، بالميليثانية، الذي يبدأ بعده الانتقال. يمكن استخدام هذا الإعداد بالاشتراك مع خاصية advClick. إذا لم يتم تحديد هذه الخاصية<br/>            فسيُفترض عدم حدوث تقدم تلقائي.<br/>            قابل للقراءة والكتابة **int**. |
| [`speed`](/slides/python-net/ar/aspose.slides/islideshowtransition/speed/) | تحدد سرعة الانتقال التي ستُستخدم عند الانتقال من الشريحة الحالية<br/>            إلى التالية.<br/>            قابل للقراءة والكتابة [`TransitionSpeed`](/slides/python-net/ar/aspose.slides.slideshow/transitionspeed). |
| [`value`](/slides/python-net/ar/aspose.slides/islideshowtransition/value/) | قيمة انتقال عرض الشرائح.<br/>            للقراءة فقط [`ITransitionValueBase`](/slides/python-net/ar/aspose.slides.slideshow/itransitionvaluebase). |
| [`type`](/slides/python-net/ar/aspose.slides/islideshowtransition/type/) | نوع الانتقال.<br/>            قابل للقراءة والكتابة [`TransitionType`](/slides/python-net/ar/aspose.slides.slideshow/transitiontype). |
| [`sound_is_built_in`](/slides/python-net/ar/aspose.slides/islideshowtransition/sound_is_built_in/) | تحدد ما إذا كان هذا الصوت مُدمجاً أم لا. إذا تم تعيين هذه الخاصية إلى true فستُعلم التطبيق المولّد للتحقق من خاصية الاسم المحددة لهذا الصوت<br/>            في قائمة الأصوات المدمجة الخاصة به، ويمكنه حينها إظهار اسم مخصص أو واجهة مستخدم حسب الحاجة.<br/>            قابل للقراءة والكتابة **bool**. |
| [`sound_name`](/slides/python-net/ar/aspose.slides/islideshowtransition/sound_name/) | تحدد اسمًا قابلًا للقراءة للإنسان للصوت الخاص بالانتقال. يجب تعيين خاصية [`ISlideShowTransition.sound`](/slides/python-net/ar/aspose.slides/islideshowtransition/sound) للحصول أو تعيين اسم الصوت.<br/>            قابل للقراءة والكتابة **str**. |
| [`duration`](/slides/python-net/ar/aspose.slides/islideshowtransition/duration/) | يحصل أو يعيّن مدة تأثير انتقال الشريحة بالميليثانية.<br/>            قابل للقراءة والكتابة **int**. |

### انظر أيضًا
* وحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* مكتبة [`Aspose.Slides`](/slides/python-net)