---
title: get_visual_bounds method
second_title: Aspose.Slides Python के लिए .NET API संदर्भ के माध्यम से
description: 
type: docs
url: /hi/aspose.slides/audioframe/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
रेंडर किए गए कंटेंट से गणना की गई आकार की दृश्य सीमाओं को प्राप्त करता है।

### वापसी

एक **aspose.slides.RectangleF** जो स्लाइड निर्देशांक में आकार की दृश्य सीमाओं का प्रतिनिधित्व करता है।



```python
def get_visual_bounds(self):
    ...
```


### टिप्पणी

वापस किया गया आयताकार स्लाइड निर्देशांक स्थान में रेंडरिंग के दौरान आकार द्वारा उत्पन्न सभी कंटेंट की अक्ष-समांतर सीमाओं को दर्शाता है।

ये सीमाएँ आकार के मॉडल बाउंड्स ([`Shape.x`](/slides/python-net/hi/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/hi/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/hi/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/hi/aspose.slides/shape/height)) से भिन्न हो सकती हैं और यदि रेंडर किया गया कंटेंट स्लाइड मूल बिंदु से परे विस्तारित हो तो इनमें नकारात्मक निर्देशांक हो सकते हैं।

दृश्य सीमाएँ रेंडरिंग से संबंधित पहलुओं जैसे रूपांतरण (उदाहरण के लिए, घुर्णन), स्ट्रोक चौड़ाई और जॉइन, पाठ लेआउट और ओवरफ़्लो, SmartArt ज्यामिति, और आकार की अंतिम रेंडर की गई उपस्थिति को प्रभावित करने वाले अन्य लेआउट प्रभावों को ध्यान में रखती हैं।

वापस की गई सीमाएँ स्लाइड आयताकार में क्लिप नहीं की गई हैं।



### देखें
* क्लास [`AudioFrame`](/slides/python-net/hi/aspose.slides/audioframe)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)