---
title: get_visual_bounds method
second_title: Aspose.Slides for Python via .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/graphicalobject/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
आकृति के रेंडर किए गए कंटेंट से गणना किए गए विज़ुअल सीमाएँ प्राप्त करता है।

### वापसी

एक **aspose.slides.RectangleF** जो स्लाइड निर्देशांक में आकृति की विज़ुअल सीमाओं का प्रतिनिधित्व करता है।



```python
def get_visual_bounds(self):
    ...
```


### टिप्पणी

वापसी किया गया आयतांक स्लाइड कॉर्डिनेट स्पेस में रेंडरिंग के दौरान आकृति द्वारा उत्पन्न सभी कंटेंट की अक्ष-संरेखित सीमाओं का प्रतिनिधित्व करता है।

ये सीमाएँ आकृति के मॉडल बाउंड्स ([`Shape.x`](/slides/python-net/hi/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/hi/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/hi/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/hi/aspose.slides/shape/height)) से भिन्न हो सकती हैं और यदि रेंडर किया गया कंटेंट स्लाइड मूल बिंदु से परे जाता है तो इनमें नकारात्मक निर्देशांक हो सकते हैं।

विज़ुअल सीमाएँ रेंडरिंग से संबंधित पहलुओं जैसे रूपांतरण (उदाहरण के लिए, घुमाव), स्ट्रोक चौड़ाई और ज्वाइंट्स, टेक्स्ट लेआउट और ओवरफ़्लो, SmartArt ज्योमेट्री, और अन्य लेआउट प्रभावों को ध्यान में रखती हैं जो आकृति की अंतिम रेंडर की गई उपस्थिति को प्रभावित करते हैं।

वापसी की गई सीमाएँ स्लाइड आयतांक तक क्लिप नहीं की गई हैं।



### संबंधित देखें
* क्लास [`GraphicalObject`](/slides/python-net/hi/aspose.slides/graphicalobject)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)