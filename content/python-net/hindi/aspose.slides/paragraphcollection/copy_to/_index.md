---
title: copy_to method
second_title: Aspose.Slides Python के लिए .NET API संदर्भ के माध्यम से
description: 
type: docs
url: /hi/aspose.slides/paragraphcollection/copy_to/
weight: 50
---
## copy_to(self, array, array_index) {#listiparagraph-int}
**System.Collections.Generic.ICollection`1** के तत्वों को एक **System.Array** में कॉपी करता है, जो एक विशिष्ट **System.Array** अनुक्रमणिका से शुरू होता है।


```python
def copy_to(self, array, array_index):
    ...
```


| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| array | **List[IParagraph]** | एक-आयामी **System.Array** जो **System.Collections.Generic.ICollection`1** से कॉपी किए गए तत्वों का गंतव्य है। **System.Array** में शून्य-आधारित अनुक्रमणिका होनी चाहिए। |
| array_index | **int** | `array` में शून्य-आधारित अनुक्रमणिका जहाँ से कॉपी शुरू होती है। |

### अपवाद

| अपवाद | विवरण |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | `array` None है। |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | `array_index` 0 से कम है। |
| **RuntimeError(Proxy error(ArgumentException))** | स्रोत **System.Collections.Generic.ICollection`1** में तत्वों की संख्या `array_index` से लेकर गंतव्य `array` के अंत तक उपलब्ध स्थान से अधिक है। |



### संबंधित देखें
* क्लास [`ParagraphCollection`](/slides/python-net/hi/aspose.slides/paragraphcollection)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)