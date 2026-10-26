---
title: OpenAIWebClient constructor
second_title: مرجع API لـ Aspose.Slides للبايثون عبر .NET
description: 
type: docs
url: /ar/aspose.slides.ai/openaiwebclient/__init__/
weight: 10
---
## __init__(self, model, api_key, organization_id) {#str-str-str}
ينشئ مثيلًا لعميل الويب الخاص بـ OpenAI.

```python
def __init__(self, model, api_key, organization_id):
    ...
```

| المعامل | النوع | الوصف |
| :- | :- | :- |
| model | **str** | نموذج لغة OpenAI. القيم المحتملة:<br/><br/>              - gpt-4o<br/><br/>              - gpt-4o-mini<br/><br/>              - o1<br/><br/>              - o1-mini<br/><br/>              - o3<br/><br/>              - o3-mini |
| api_key | **str** | مفتاح API الخاص بـ OpenAI. |
| organization_id | **str** | معرف المؤسسة (اختياري). |

### استثناءات

| الاستثناء | الوصف |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | قيمة مفتاح API لا يمكن أن تكون None أو فارغة. |
| **RuntimeError(Proxy error(ArgumentException))** | قيمة نموذج النص لا يمكن أن تكون None أو فارغة. |

### انظر أيضاً
* فئة [`OpenAIWebClient`](/slides/python-net/ar/aspose.slides.ai/openaiwebclient)
* وحدة [`aspose.slides.ai`](/slides/python-net/ar/aspose.slides.ai)
* مكتبة [`Aspose.Slides`](/slides/python-net)