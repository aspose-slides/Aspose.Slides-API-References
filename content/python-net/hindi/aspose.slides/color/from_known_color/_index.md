---
title: from_known_color method
second_title: Aspose.Slides के लिए Python द्वारा .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/color/from_known_color/
weight: 30
---
## from_known_color(known_color) {#knowncolor}
निर्दिष्ट पूर्वनिर्धारित रंग से एक रंग बनाता है।<br/>यह सिस्टम रंग (जैसे `KnownColor.CONTROL`) प्राप्त करने का एकमात्र तरीका है: सिस्टम रंगों को `Color` गुणों के रूप में उजागर नहीं किया जाता क्योंकि उनके मान डेस्कटॉप थीम पर निर्भर करते हैं, इसलिए उन्हें लाइब्रेरी रनटाइम से पढ़ा जाता है।

### वापसी मान

यह विधि द्वारा निर्मित रंग।

```python
@staticmethod
def from_known_color(known_color):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| known_color | **KnownColor** | एक `KnownColor` एनीमरेशन का तत्व (`IntEnum` जो .NET `System.Drawing.KnownColor` को प्रतिबिंबित करता है) या उसका पूर्णांक मान। |

### अपवाद

| अपवाद | विवरण |
| :- | :- |
| **ValueError** | मान मान्य `KnownColor` सदस्य नहीं है। |

### संबंधित
* वर्ग [`Color`](/slides/python-net/hi/aspose.slides/color)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)