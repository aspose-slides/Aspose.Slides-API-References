---
title: SlidesAIAgent constructor
second_title: Aspose.Slides لـ Python عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides.ai/slidesaiagent/__init__/
weight: 10
---
## __init__(self) {#}
يقوم بتهيئة نسخة جديدة من [`SlidesAIAgent`](/slides/python-net/ar/aspose.slides.ai/slidesaiagent) باستخدام [`AsposeAIWebClient`](/slides/python-net/ar/aspose.slides.ai/asposeaiwebclient) المدمج بإعداداته الافتراضية. يتصل العميل بـ LLM الخاص بـ Aspose ولا يتطلب أي تكوين إضافي. لاستخدام عميل ذكاء اصطناعي مختلف، استخدم **Aspose.Slides.AI.SlidesAIAgent.#ctor(Aspose.Slides.A** بدلاً من ذلك.

```python
def __init__(self):
    ...
```

## __init__(self, ai_client) {#iaiwebclient}
يقوم بتهيئة نسخة جديدة من [`SlidesAIAgent`](/slides/python-net/ar/aspose.slides.ai/slidesaiagent) باستخدام عميل ذكاء اصطناعي مخصص. استخدم هذا التحميل الزائد لتحديد موفر الذكاء الاصطناعي، أو توفير LLM الخاص بك، أو تخصيص الاتصال (على سبيل المثال، عن طريق توفير `HttpClient` الخاص بك). يمكن استخدام أي تنفيذ لـ [`IAIWebClient`](/slides/python-net/ar/aspose.slides.ai/iaiwebclient)، بما في ذلك:
* [`AsposeAIWebClient`](/slides/python-net/ar/aspose.slides.ai/asposeaiwebclient)
* [`OpenAIWebClient`](/slides/python-net/ar/aspose.slides.ai/openaiwebclient)
* [`OpenAICompatibleWebClient`](/slides/python-net/ar/aspose.slides.ai/openaicompatiblewebclient)

لاستخدام [`AsposeAIWebClient`](/slides/python-net/ar/aspose.slides.ai/asposeaiwebclient) المدمج بإعداداته الافتراضية، استخدم **SlidesAIAgent.#ctor** بدلاً من ذلك.

```python
def __init__(self, ai_client):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| ai_client | [`IAIWebClient`](/slides/python-net/ar/aspose.slides.ai/iaiwebclient) | مثيل عميل الذكاء الاصطناعي. يمكن استخدام أي تنفيذ لـ [`IAIWebClient`](/slides/python-net/ar/aspose.slides.ai/iaiwebclient). |

### الاستثناءات

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | لم يتم توفير مثيل عميل الذكاء الاصطناعي. |

### انظر أيضًا
* فئة [`AsposeAIWebClient`](/slides/python-net/ar/aspose.slides.ai/asposeaiwebclient)
* فئة [`IAIWebClient`](/slides/python-net/ar/aspose.slides.ai/iaiwebclient)
* فئة [`OpenAICompatibleWebClient`](/slides/python-net/ar/aspose.slides.ai/openaicompatiblewebclient)
* فئة [`OpenAIWebClient`](/slides/python-net/ar/aspose.slides.ai/openaiwebclient)
* فئة [`SlidesAIAgent`](/slides/python-net/ar/aspose.slides.ai/slidesaiagent)
* وحدة [`aspose.slides.ai`](/slides/python-net/ar/aspose.slides.ai)
* مكتبة [`Aspose.Slides`](/slides/python-net)