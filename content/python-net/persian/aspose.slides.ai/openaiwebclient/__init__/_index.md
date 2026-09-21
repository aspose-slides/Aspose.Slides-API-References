---
title: OpenAIWebClient constructor
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides.ai/openaiwebclient/__init__/
weight: 10
---
## __init__(self, model, api_key, organization_id) {#str-str-str}
یک نمونه از کلاینت وب OpenAI ایجاد می‌کند.

```python
def __init__(self, model, api_key, organization_id):
    ...
```

| پارامتر | نوع | توضیح |
| :- | :- | :- |
| model | **str** | OpenAI language model. Possible values:<br/><br/>              - gpt-4o<br/><br/>              - gpt-4o-mini<br/><br/>              - o1<br/><br/>              - o1-mini<br/><br/>              - o3<br/><br/>              - o3-mini |
| api_key | **str** | OpenAI API key. |
| organization_id | **str** | Organization ID (optional). |

### استثناها

| استثنا | توضیح |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | مقدار کلید API نمی‌تواند None یا خالی باشد. |
| **RuntimeError(Proxy error(ArgumentException))** | مقدار مدل متن نمی‌تواند None یا خالی باشد. |

### موارد مرتبط
* کلاس [`OpenAIWebClient`](/slides/python-net/fa/aspose.slides.ai/openaiwebclient)
* ماژول [`aspose.slides.ai`](/slides/python-net/fa/aspose.slides.ai)
* کتابخانه [`Aspose.Slides`](/slides/python-net)