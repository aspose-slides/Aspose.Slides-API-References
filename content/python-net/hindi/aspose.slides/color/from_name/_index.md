---
title: from_name method
second_title: Aspose.Slides Python के लिए .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/color/from_name/
weight: 40
---
## from_name(name) {#str}
निर्दिष्ट पूर्वपरिभाषित रंग के नाम से एक रंग बनाता है।<br/>लुकअप केस-इंसेंसिटिव है और अंडरस्कोर व स्पेस को अनदेखा करता है: `"LightBlue"`, `"lightblue"` और `"light_blue"` सभी `Color.light_blue` में परिवर्तित होते हैं। देखें [`Color`](/slides/python-net/hi/aspose.slides/color) क्लास पेज पर पूर्वपरिभाषित रंगों की सूची।

### रिटर्न

नामित रंग।

```python
@staticmethod
def from_name(name):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| name | **str** | एक स्ट्रिंग जो पूर्वपरिभाषित रंग का नाम है। |

### अपवाद

| अपवाद | विवरण |
| :- | :- |
| **ValueError** | नाम पूर्वपरिभाषित रंग के नाम में से नहीं है। |
| **TypeError** | नाम स्ट्रिंग नहीं है। |

### देखें
* क्लास [`Color`](/slides/python-net/hi/aspose.slides/color)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)