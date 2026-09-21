---
title: translate method
second_title: مرجع API Aspose.Slides برای پایتون از طریق .NET
description: 
type: docs
url: /fa/aspose.slides.ai/slidesaiagent/translate/
weight: 30
---
## translate(self, presentation, language) {#ipresentation-str}
یک ارائه را به زبان مشخص شده با استفاده از هوش مصنوعی (نسخه همزمان) ترجمه می‌کند.


```python
def translate(self, presentation, language):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| presentation | [`IPresentation`](/slides/python-net/fa/aspose.slides/ipresentation) | ارائه هدف |
| language | **str** | زبان هدف |

### توضیحات

مثال زیر از [`AsposeAIWebClient`](/slides/python-net/fa/aspose.slides.ai/asposeaiwebclient) پیش‌فرض استفاده می‌کند که توسط سازنده بدون پارامتر **SlidesAIAgent.#ctor** ایجاد می‌شود و به LLM داخلی Aspose متصل می‌شود. برای استفاده از ارائه‌دهنده هوش مصنوعی متفاوت، LLM خود را فراهم کنید یا اتصال را سفارشی کنید (به عنوان مثال، با ارائه `HttpClient` خود)، یک پیاده‌سازی [`IAIWebClient`](/slides/python-net/fa/aspose.slides.ai/iaiwebclient) را به سازنده **Aspose.Slides.AI.SlidesAIAgent.#ctor(Aspose.Slides.A** پاس دهید. پیاده‌سازی‌های موجود عبارتند از:
             
* [`AsposeAIWebClient`](/slides/python-net/fa/aspose.slides.ai/asposeaiwebclient)
* [`OpenAIWebClient`](/slides/python-net/fa/aspose.slides.ai/openaiwebclient)
* [`OpenAICompatibleWebClient`](/slides/python-net/fa/aspose.slides.ai/openaicompatiblewebclient)

### استثناها

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | نمونه ارائه ارائه نشده است |
| **RuntimeError(Proxy error(ArgumentException))** | مقدار زبان نمی‌تواند None یا خالی باشد |



### همچنین ببینید
* کلاس [`AsposeAIWebClient`](/slides/python-net/fa/aspose.slides.ai/asposeaiwebclient)
* کلاس [`IAIWebClient`](/slides/python-net/fa/aspose.slides.ai/iaiwebclient)
* کلاس [`IPresentation`](/slides/python-net/fa/aspose.slides/ipresentation)
* کلاس [`OpenAICompatibleWebClient`](/slides/python-net/fa/aspose.slides.ai/openaicompatiblewebclient)
* کلاس [`OpenAIWebClient`](/slides/python-net/fa/aspose.slides.ai/openaiwebclient)
* کلاس [`SlidesAIAgent`](/slides/python-net/fa/aspose.slides.ai/slidesaiagent)
* ماژول [`aspose.slides.ai`](/slides/python-net/fa/aspose.slides.ai)
* کتابخانه [`Aspose.Slides`](/slides/python-net)