---
title: SlidesAIAgent constructor
second_title: مرجع API Aspose.Slides برای Python از طریق .NET
description: 
type: docs
url: /fa/aspose.slides.ai/slidesaiagent/__init__/
weight: 10
---
## __init__(self) {#}
یک نمونه جدید از [`SlidesAIAgent`](/slides/python-net/fa/aspose.slides.ai/slidesaiagent) را با استفاده از [`AsposeAIWebClient`](/slides/python-net/fa/aspose.slides.ai/asposeaiwebclient) داخلی و با پیکربندی پیش‌فرض آن مقداردهی اولیه می‌کند. مشتری به LLM متعلق به Aspose متصل می‌شود و نیازی به پیکربندی اضافی ندارد. برای استفاده از یک مشتری AI متفاوت، به‌جای آن از overload **Aspose.Slides.AI.SlidesAIAgent.#ctor(Aspose.Slides.A** استفاده کنید.

```python
def __init__(self):
    ...
```

## __init__(self, ai_client) {#iaiwebclient}
یک نمونه جدید از [`SlidesAIAgent`](/slides/python-net/fa/aspose.slides.ai/slidesaiagent) را با یک مشتری AI سفارشی مقداردهی اولیه می‌کند. از این overload برای تعیین ارائه‌دهنده AI، ارائه LLM خود، یا سفارشی‌سازی اتصال (به‌عنوان مثال، با فراهم کردن `HttpClient` خود) استفاده کنید. هر پیاده‌سازی از [`IAIWebClient`](/slides/python-net/fa/aspose.slides.ai/iaiwebclient) می‌تواند استفاده شود، از جمله:

* [`AsposeAIWebClient`](/slides/python-net/fa/aspose.slides.ai/asposeaiwebclient)
* [`OpenAIWebClient`](/slides/python-net/fa/aspose.slides.ai/openaiwebclient)
* [`OpenAICompatibleWebClient`](/slides/python-net/fa/aspose.slides.ai/openaicompatiblewebclient)

برای استفاده از [`AsposeAIWebClient`](/slides/python-net/fa/aspose.slides.ai/asposeaiwebclient) داخلی با پیکربندی پیش‌فرض، به‌جای آن از overload **SlidesAIAgent.#ctor** استفاده کنید.

```python
def __init__(self, ai_client):
    ...
```

| پارامتر | نوع | توضیح |
| :- | :- | :- |
| ai_client | [`IAIWebClient`](/slides/python-net/fa/aspose.slides.ai/iaiwebclient) | نمونهٔ مشتری AI. هر پیاده‌سازی از [`IAIWebClient`](/slides/python-net/fa/aspose.slides.ai/iaiwebclient) می‌تواند استفاده شود. |

### استثناها

| استثنا | توضیح |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | نمونهٔ مشتری AI فراهم نشده است. |

### موارد مرتبط
* کلاس [`AsposeAIWebClient`](/slides/python-net/fa/aspose.slides.ai/asposeaiwebclient)
* کلاس [`IAIWebClient`](/slides/python-net/fa/aspose.slides.ai/iaiwebclient)
* کلاس [`OpenAICompatibleWebClient`](/slides/python-net/fa/aspose.slides.ai/openaicompatiblewebclient)
* کلاس [`OpenAIWebClient`](/slides/python-net/fa/aspose.slides.ai/openaiwebclient)
* کلاس [`SlidesAIAgent`](/slides/python-net/fa/aspose.slides.ai/slidesaiagent)
* ماژول [`aspose.slides.ai`](/slides/python-net/fa/aspose.slides.ai)
* کتابخانه [`Aspose.Slides`](/slides/python-net)