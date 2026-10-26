---
title: OpenAIWebClient constructor
second_title: Aspose.Slides for Python के माध्यम से .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides.ai/openaiwebclient/__init__/
weight: 10
---
## __init__(self, model, api_key, organization_id) {#str-str-str}
OpenAI वेब क्लाइंट का एक उदाहरण बनाता है।

```python
def __init__(self, model, api_key, organization_id):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| model | **str** | OpenAI भाषा मॉडल। संभावित मान:<br/><br/>              - gpt-4o<br/><br/>              - gpt-4o-mini<br/><br/>              - o1<br/><br/>              - o1-mini<br/><br/>              - o3<br/><br/>              - o3-mini |
| api_key | **str** | OpenAI API कुंजी। |
| organization_id | **str** | संगठन आईडी (वैकल्पिक)। |

### अपवाद

| अपवाद | विवरण |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | API कुंजी मान None या खाली नहीं हो सकता। |
| **RuntimeError(Proxy error(ArgumentException))** | टेक्स्ट मॉडल मान None या खाली नहीं हो सकता। |

### देखें
* क्लास [`OpenAIWebClient`](/slides/python-net/hi/aspose.slides.ai/openaiwebclient)
* मॉड्यूल [`aspose.slides.ai`](/slides/python-net/hi/aspose.slides.ai)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)