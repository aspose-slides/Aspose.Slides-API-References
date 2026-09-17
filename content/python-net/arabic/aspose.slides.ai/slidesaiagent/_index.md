---
title: SlidesAIAgent class
second_title: Aspose.Slides للغة Python عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides.ai/slidesaiagent/
---
## فئة SlidesAIAgent

يوفر ميزات مدعومة بالذكاء الاصطناعي لمعالجة العروض التقديمية.

يكشف نوع SlidesAIAgent عن الأعضاء التالية:

## المنشئات

| المنشئ | الوصف |
| :- | :- |
| [`__init__(self, ai_client)`](/slides/python-net/ar/aspose.slides.ai/slidesaiagent/__init__/#iaiwebclient) | يُنشئ مثيلاً جديدًا من [`SlidesAIAgent`](/slides/python-net/ar/aspose.slides.ai/slidesaiagent) باستخدام عميل ذكاء اصطناعي مخصص.<br/>            استخدم هذا التحميل الزائد لتحديد موفر الذكاء الاصطناعي، أو تزويدك بـ LLM الخاص بك، أو تخصيص الاتصال (على سبيل المثال، عن طريق توفير `HttpClient` الخاص بك).<br/>            يمكن استخدام أي تنفيذ لـ [`IAIWebClient`](/slides/python-net/ar/aspose.slides.ai/iaiwebclient)، بما في ذلك:<br/>            <br/>* [`AsposeAIWebClient`](/slides/python-net/ar/aspose.slides.ai/asposeaiwebclient)<br/>* [`OpenAIWebClient`](/slides/python-net/ar/aspose.slides.ai/openaiwebclient)<br/>* [`OpenAICompatibleWebClient`](/slides/python-net/ar/aspose.slides.ai/openaicompatiblewebclient)<br/><br/><br/>            لاستخدام [`AsposeAIWebClient`](/slides/python-net/ar/aspose.slides.ai/asposeaiwebclient) المدمج مع تكوينه الافتراضي،<br/>            استخدم التحميل الزائد **SlidesAIAgent.#ctor** بدلاً من ذلك. |
| [`__init__(self)`](/slides/python-net/ar/aspose.slides.ai/slidesaiagent/__init__/#) | يُنشئ مثيلاً جديدًا من [`SlidesAIAgent`](/slides/python-net/ar/aspose.slides.ai/slidesaiagent) باستخدام المدمج<br/>            [`AsposeAIWebClient`](/slides/python-net/ar/aspose.slides.ai/asposeaiwebclient) مع تكوينه الافتراضي. يتصل العميل بـ LLM الخاص بـ Aspose ولا يتطلب أي تكوين إضافي.<br/>            لاستخدام عميل ذكاء اصطناعي مختلف، استخدم التحميل الزائد **Aspose.Slides.AI.SlidesAIAgent.#ctor(Aspose.Slides.A** بدلاً من ذلك. |

## الطرق

| الطريقة | الوصف |
| :- | :- |
| [`generate_presentation(self, description, presentation_content_amount)`](/slides/python-net/ar/aspose.slides.ai/slidesaiagent/generate_presentation/#str-presentationcontentamounttype) | يُنشئ مثيلاً لعرض تقديمي من وصف نصي. قدم موضوعًا أو أفكارًا أو اقتباسات أو مقاطع نصية باللغة المطلوبة. |
| [`generate_presentation(self, description, presentation_content_amount, presentation_template)`](/slides/python-net/ar/aspose.slides.ai/slidesaiagent/generate_presentation/#str-presentationcontentamounttype-ipresentation) | يُنشئ مثيلاً لعرض تقديمي من وصف نصي. قدم موضوعًا أو أفكارًا أو اقتباسات أو مقاطع نصية باللغة المطلوبة. |
| [`translate(self, presentation, language)`](/slides/python-net/ar/aspose.slides.ai/slidesaiagent/translate/#ipresentation-str) | يترجم عرضًا تقديميًا إلى اللغة المحددة باستخدام الذكاء الاصطناعي (الإصدار المتزامن). |

### انظر أيضًا
* الفئة [`AsposeAIWebClient`](/slides/python-net/ar/aspose.slides.ai/asposeaiwebclient)
* الفئة [`IAIWebClient`](/slides/python-net/ar/aspose.slides.ai/iaiwebclient)
* الفئة [`OpenAICompatibleWebClient`](/slides/python-net/ar/aspose.slides.ai/openaicompatiblewebclient)
* الفئة [`OpenAIWebClient`](/slides/python-net/ar/aspose.slides.ai/openaiwebclient)
* الفئة [`SlidesAIAgent`](/slides/python-net/ar/aspose.slides.ai/slidesaiagent)
* الوحدة [`aspose.slides.ai`](/slides/python-net/ar/aspose.slides.ai)
* المكتبة [`Aspose.Slides`](/slides/python-net)