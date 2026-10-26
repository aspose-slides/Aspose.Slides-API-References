---
title: get_font_embedding_level method
second_title: Aspose.Slides for Python via .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/fontsmanager/get_font_embedding_level/
weight: 40
---
## get_font_embedding_level(self, font_bytes, font_name) {#bytes-str}
दिए गए बाइट एरे और फ़ॉन्ट नाम से फ़ॉन्ट के एम्बेडिंग स्तर का निर्धारण करता है।

### रिटर्न

निर्दिष्ट फ़ॉन्ट का एम्बेडिंग स्तर।

```python
def get_font_embedding_level(self, font_bytes, font_name):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| font_bytes | **bytes** | फ़ॉन्ट डेटा युक्त बाइट एरे। |
| font_name | **str** | फ़ॉन्ट का नाम। |

### अपवाद

| अपवाद | विवरण |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | जब `font_bytes` None हो तो फेंका जाता है। |

### देखें
* एन्यूमरेशन [`EmbeddingLevel`](/slides/python-net/hi/aspose.slides/embeddinglevel)
* क्लास [`FontsManager`](/slides/python-net/hi/aspose.slides/fontsmanager)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)