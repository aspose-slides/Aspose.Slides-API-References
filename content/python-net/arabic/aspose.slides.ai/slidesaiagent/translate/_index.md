---
title: translate method
second_title: Aspose.Slides لـ Python عبر مرجع API .NET
description: 
type: docs
url: /ar/aspose.slides.ai/slidesaiagent/translate/
weight: 30
---
## translate(self, presentation, language) {#ipresentation-str}
يترجم عرض تقديمي إلى اللغة المحددة باستخدام الذكاء الاصطناعي (الإصدار المتزامن).


```python
def translate(self, presentation, language):
    ...
```


| المعامل | النوع | الوصف |
| :- | :- | :- |
| presentation | [`IPresentation`](/slides/python-net/ar/aspose.slides/ipresentation) | Target presentation |
| language | **str** | Target language |

### ملاحظات

المثال أدناه يستخدم الافتراضي [`AsposeAIWebClient`](/slides/python-net/ar/aspose.slides.ai/asposeaiwebclient)، والذي يتم إنشاؤه بواسطة
المُنشئ **SlidesAIAgent.#ctor** بدون معلمات ويتصل بواجهة اللغة الكبيرة الخاصة بـ Aspose.
لاستخدام مزود ذكاء اصطناعي مختلف، زوّد LLM الخاص بك، أو خصّص الاتصال
(على سبيل المثال، عن طريق توفير `HttpClient` الخاص بك)، مرّر تطبيق [`IAIWebClient`](/slides/python-net/ar/aspose.slides.ai/iaiwebclient)
إلى مُنشئ **Aspose.Slides.AI.SlidesAIAgent.#ctor(Aspose.Slides.A**. التطبيقات المتاحة
تشمل التطبيقات:
             
* [`AsposeAIWebClient`](/slides/python-net/ar/aspose.slides.ai/asposeaiwebclient)
* [`OpenAIWebClient`](/slides/python-net/ar/aspose.slides.ai/openaiwebclient)
* [`OpenAICompatibleWebClient`](/slides/python-net/ar/aspose.slides.ai/openaicompatiblewebclient)

### استثناءات

| الاستثناء | الوصف |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Presentation instance is not provided |
| **RuntimeError(Proxy error(ArgumentException))** | Language value can't be None or empty |



### انظر أيضًا
* فئة [`AsposeAIWebClient`](/slides/python-net/ar/aspose.slides.ai/asposeaiwebclient)
* فئة [`IAIWebClient`](/slides/python-net/ar/aspose.slides.ai/iaiwebclient)
* فئة [`IPresentation`](/slides/python-net/ar/aspose.slides/ipresentation)
* فئة [`OpenAICompatibleWebClient`](/slides/python-net/ar/aspose.slides.ai/openaicompatiblewebclient)
* فئة [`OpenAIWebClient`](/slides/python-net/ar/aspose.slides.ai/openaiwebclient)
* فئة [`SlidesAIAgent`](/slides/python-net/ar/aspose.slides.ai/slidesaiagent)
* الوحدة [`aspose.slides.ai`](/slides/python-net/ar/aspose.slides.ai)
* المكتبة [`Aspose.Slides`](/slides/python-net)