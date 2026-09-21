---
title: copy_to method
second_title: Aspose.Slides के लिए Python के माध्यम से .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/portioncollection/copy_to/
weight: 40
---
## copy_to(self, array, array_index) {#listiportion-int}
**System.Collections.Generic.ICollection`1** के तत्वों को एक **System.Array** में कॉपी करता है, जो एक विशेष **System.Array** अनुक्रमणिका से शुरू होता है।

```python
def copy_to(self, array, array_index):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| array | **List[IPortion]** | एक-आयामी **System.Array** जो **System.Collections.Generic.ICollection`1** से कॉपी किए गए तत्वों का गन्तव्य है। **System.Array** में शून्य-आधारित अनुक्रमणिका होना आवश्यक है। |
| array_index | **int** | `array` में शून्य-आधारित वह अनुक्रमणिका जहाँ से कॉपी शुरू होती है। |

### अपवाद

| अपवाद | विवरण |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | `array` None है। |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | `array_index` 0 से कम है। |
| **RuntimeError(Proxy error(ArgumentException))** | स्रोत **System.Collections.Generic.ICollection`1** में तत्वों की संख्या `array_index` से लेकर गन्तव्य `array` के अंत तक उपलब्ध जगह से अधिक है। |

### संबंधित देखें
* क्लास [`PortionCollection`](/slides/python-net/hi/aspose.slides/portioncollection)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)