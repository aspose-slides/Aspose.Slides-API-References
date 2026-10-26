---
title: copy_to method
second_title: Aspose.Slides for Python via .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides.animation/behaviorcollection/copy_to/
weight: 40
---
## copy_to(self, array, array_index) {#listibehavior-int}
**System.Collections.Generic.ICollection`1** के तत्वों को **System.Array** में कॉपी करता है, जो एक विशिष्ट **System.Array** सूचकांक से शुरू होता है।

```python
def copy_to(self, array, array_index):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| array | **List[IBehavior]** | वह एक-आयामी **System.Array** जो **System.Collections.Generic.ICollection`1** से कॉपी किए गए तत्वों का गंतव्य है। **System.Array** का शून्य-आधारित अनुक्रमण होना चाहिए। |
| array_index | **int** | यह शून्य-आधारित अनुक्रमण है `array` में जहाँ कॉपी शुरू होती है। |

### अपवाद

| अपवाद | विवरण |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | `array` None है। |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | `array_index` 0 से कम है। |
| **RuntimeError(Proxy error(ArgumentException))** | स्रोत **System.Collections.Generic.ICollection`1** में तत्वों की संख्या `array_index` से गंतव्य `array` के अंत तक उपलब्ध स्थान से अधिक है। |

### संबंधित देखें
* क्लास [`BehaviorCollection`](/slides/python-net/hi/aspose.slides.animation/behaviorcollection)
* मॉड्यूल [`aspose.slides.animation`](/slides/python-net/hi/aspose.slides.animation)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)