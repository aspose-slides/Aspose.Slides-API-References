---
title: MathDelimiter constructor
second_title: Aspose.Slides Python के लिए .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides.mathtext/mathdelimiter/__init__/
weight: 10
---
## __init__(self, element) {#imathelement}
निर्दिष्ट element के साथ MathDelimiter को एकल आधार तर्क के रूप में प्रारंभ करता है


```python
def __init__(self, element):
    ...
```


| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| element | [`IMathElement`](/slides/python-net/hi/aspose.slides.mathtext/imathelement) | वह आधार element जिससे delimiter लागू होता है। None हो सकता है। |

### अपवाद

| अपवाद | विवरण |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | जब `element` अन्य elements का container होता है, जैसे MathBlock, तब थ्रो करता है। इस मामले में, आपको IEnumerable तर्क के साथ एक अलग constructor को कॉल करना चाहिए। |



### देखें
* क्लास [`IMathElement`](/slides/python-net/hi/aspose.slides.mathtext/imathelement)
* क्लास [`MathDelimiter`](/slides/python-net/hi/aspose.slides.mathtext/mathdelimiter)
* मॉड्यूल [`aspose.slides.mathtext`](/slides/python-net/hi/aspose.slides.mathtext)
* library [`Aspose.Slides`](/slides/python-net)