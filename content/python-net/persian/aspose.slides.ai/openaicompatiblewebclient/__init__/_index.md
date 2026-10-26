---
title: OpenAICompatibleWebClient constructor
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides.ai/openaicompatiblewebclient/__init__/
weight: 10
---
## __init__(self, model, api_key, base_url) {#str-str-str}
یک نمونه از کلاینت وب سازگار با OpenAI ایجاد می‌کند.

```python
def __init__(self, model, api_key, base_url):
    ...
```

| پارامتر | نوع | توضیح |
| :- | :- | :- |
| model | **str** | نام مدل پشتیبانی‌شده توسط ارائه‌دهنده LLM. |
| api_key | **str** | کلید API (توکن). |
| base_url | **str** | آدرس پایه (Base URL) LLM سازگار با OpenAI. |

### استثناها

| استثنا | توضیح |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | مقدار کلید API نمی‌تواند None یا خالی باشد. |
| **RuntimeError(Proxy error(ArgumentException))** | مقدار مدل متنی نمی‌تواند None یا خالی باشد. |
| **RuntimeError(Proxy error(ArgumentException))** | مقدار Base URL نمی‌تواند None یا خالی باشد. |

### موارد مرتبط
* کلاس [`OpenAICompatibleWebClient`](/slides/python-net/fa/aspose.slides.ai/openaicompatiblewebclient)
* ماژول [`aspose.slides.ai`](/slides/python-net/fa/aspose.slides.ai)
* کتابخانه [`Aspose.Slides`](/slides/python-net)