---
title: get_visual_bounds method
second_title: Aspose.Slides के लिए Python via .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/zoomobject/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
आकार के रेंडर किए गए कंटेंट से गणना किए गए दृश्य सीमाओं को प्राप्त करता है।

### रिटर्न

एक **aspose.slides.RectangleF** जो स्लाइड निर्देशांक में आकार की दृश्य सीमाओं का प्रतिनिधित्व करता है।
            

```python
def get_visual_bounds(self):
    ...
```


### टिप्पणी

वापसी किया गया आयताकार स्लाइड निर्देशांक स्थान में रेंडरिंग के दौरान आकार द्वारा उत्पन्न सभी सामग्री की एक्सिस-संकुलित सीमाओं का प्रतिनिधित्व करता है।

ये सीमाएँ आकार के मॉडल सीमाओं ([`Shape.x`](/slides/python-net/hi/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/hi/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/hi/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/hi/aspose.slides/shape/height)) से भिन्न हो सकती हैं और यदि रेंडर किया गया कंटेंट स्लाइड मूल बिंदु से परे विस्तार करता है तो नकारात्मक निर्देशांक भी शामिल कर सकती हैं।

दृश्य सीमाएँ ट्रांसफ़ॉर्मेशन (जैसे, घूर्णन), स्ट्रोक चौड़ाई और जोड़, टेक्स्ट लेआउट और ओवरफ़्लो, SmartArt ज्योमेट्री, तथा अन्य लेआउट प्रभाव जैसे रेंडरिंग-संबंधी पहलुओं को ध्यान में रखती हैं जो आकार की अंतिम रेंडर की गई उपस्थिति को प्रभावित करते हैं।

वापसी की गई सीमाएँ स्लाइड आयत में क्लिप नहीं की गई हैं।



### संबंधित देखें
* क्लास [`ZoomObject`](/slides/python-net/hi/aspose.slides/zoomobject)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)