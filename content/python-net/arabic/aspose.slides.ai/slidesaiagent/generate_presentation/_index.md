---
title: generate_presentation method
second_title: Aspose.Slides لـ Python عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides.ai/slidesaiagent/generate_presentation/
weight: 20
---
## generate_presentation(self, description, presentation_content_amount) {#str-presentationcontentamounttype}
يقوم بإنشاء نسخة من العرض التقديمي من وصف نصي. قدِّم موضوعًا أو أفكارًا أو اقتباسات أو مقتطفات نصية باللغة المطلوبة.

```python
def generate_presentation(self, description, presentation_content_amount):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| description | **str** | الموضوع أو الأفكار أو الاقتباسات أو مقتطفات النص. |
| presentation_content_amount | [`PresentationContentAmountType`](/slides/python-net/ar/aspose.slides.ai/presentationcontentamounttype) | كمية المحتوى في العرض التقديمي الناتج. |

### ملاحظات
المثال أدناه يستخدم الإعداد الافتراضي [`AsposeAIWebClient`](/slides/python-net/ar/aspose.slides.ai/asposeaiwebclient)، الذي يتم إنشاؤه عن طريق مُنشئ **SlidesAIAgent.#ctor** بدون معلمات ويتصل بـ LLM الخاص بـ Aspose.
             لاستخدام مزود AI مختلف، زوِّد LLM الخاص بك، أو خصِّص الاتصال
             (على سبيل المثال، عن طريق توفير `HttpClient` الخاص بك)، مرِّر تنفيذًا من نوع [`IAIWebClient`](/slides/python-net/ar/aspose.slides.ai/iaiwebclient)
             إلى مُنشئ **Aspose.Slides.AI.SlidesAIAgent.#ctor(Aspose.Slides.A**. تشمل التنفيذات المتاحة:
             
* [`AsposeAIWebClient`](/slides/python-net/ar/aspose.slides.ai/asposeaiwebclient)
* [`OpenAIWebClient`](/slides/python-net/ar/aspose.slides.ai/openaiwebclient)
* [`OpenAICompatibleWebClient`](/slides/python-net/ar/aspose.slides.ai/openaicompatiblewebclient)

### استثناءات

| استثناء | الوصف |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | تعليمات محادثة AI لا يمكن أن تكون None أو فارغة. |

## generate_presentation(self, description, presentation_content_amount, presentation_template) {#str-presentationcontentamounttype-ipresentation}
يقوم بإنشاء نسخة من العرض التقديمي من وصف نصي. قدِّم موضوعًا أو أفكارًا أو اقتباسات أو مقتطفات نصية باللغة المطلوبة.

```python
def generate_presentation(self, description, presentation_content_amount, presentation_template):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| description | **str** | الموضوع أو الأفكار أو الاقتباسات أو مقتطفات النص. |
| presentation_content_amount | [`PresentationContentAmountType`](/slides/python-net/ar/aspose.slides.ai/presentationcontentamounttype) | كمية المحتوى في العرض التقديمي الناتج. |
| presentation_template | [`IPresentation`](/slides/python-net/ar/aspose.slides/ipresentation) | عرض تقديمي يُستخدم كقالب لتخطيط وتصميم الشرائح، بدلاً من القالب الافتراضي. |

### ملاحظات
المثال أدناه يستخدم الإعداد الافتراضي [`AsposeAIWebClient`](/slides/python-net/ar/aspose.slides.ai/asposeaiwebclient)، الذي يتم إنشاؤه عن طريق مُنشئ **SlidesAIAgent.#ctor** بدون معلمات ويتصل بـ LLM الخاص بـ Aspose.
            لاستخدام مزود AI مختلف، زوِّد LLM الخاص بك، أو خصِّص الاتصال
            (على سبيل المثال، عن طريق توفير `HttpClient` الخاص بك)، مرِّر تنفيذًا من نوع [`IAIWebClient`](/slides/python-net/ar/aspose.slides.ai/iaiwebclient)
            إلى مُنشئ **Aspose.Slides.AI.SlidesAIAgent.#ctor(Aspose.Slides.A**. تشمل التنفيذات المتاحة:
            
* [`AsposeAIWebClient`](/slides/python-net/ar/aspose.slides.ai/asposeaiwebclient)
* [`OpenAIWebClient`](/slides/python-net/ar/aspose.slides.ai/openaiwebclient)
* [`OpenAICompatibleWebClient`](/slides/python-net/ar/aspose.slides.ai/openaicompatiblewebclient)

### استثناءات

| استثناء | الوصف |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | لم يتم توفير قالب العرض التقديمي. |
| **RuntimeError(Proxy error(ArgumentException))** | تعليمات محادثة AI لا يمكن أن تكون None أو فارغة. |

### انظر أيضًا
* فئة [`AsposeAIWebClient`](/slides/python-net/ar/aspose.slides.ai/asposeaiwebclient)
* فئة [`IAIWebClient`](/slides/python-net/ar/aspose.slides.ai/iaiwebclient)
* فئة [`IPresentation`](/slides/python-net/ar/aspose.slides/ipresentation)
* فئة [`OpenAICompatibleWebClient`](/slides/python-net/ar/aspose.slides.ai/openaicompatiblewebclient)
* فئة [`OpenAIWebClient`](/slides/python-net/ar/aspose.slides.ai/openaiwebclient)
* تعداد [`PresentationContentAmountType`](/slides/python-net/ar/aspose.slides.ai/presentationcontentamounttype)
* فئة [`SlidesAIAgent`](/slides/python-net/ar/aspose.slides.ai/slidesaiagent)
* وحدة [`aspose.slides.ai`](/slides/python-net/ar/aspose.slides.ai)
* مكتبة [`Aspose.Slides`](/slides/python-net)