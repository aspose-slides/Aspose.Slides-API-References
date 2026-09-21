---
title: get_visual_bounds method
second_title: Aspose.Slides for Python के लिए .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/autoshape/get_visual_bounds/
weight: 70
---
## get_visual_bounds(self) {#}
शेप के रेंडर किए गए सामग्री से गणना किए गए दृश्य सीमाओं को प्राप्त करता है।

### Returns

A **aspose.slides.RectangleF** जो स्लाइड निर्देशांक में शेप के दृश्य सीमाओं का प्रतिनिधित्व करती है।

```python
def get_visual_bounds(self):
    ...
```

### Remarks

वापसी आयत स्लाइड निर्देशांक स्पेस में रेंडरिंग के दौरान शेप द्वारा उत्पन्न सभी सामग्री की अक्ष-समरेखित सीमाओं का प्रतिनिधित्व करती है।

ये सीमाएँ शेप की मॉडल सीमाओं ([`Shape.x`](/slides/python-net/hi/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/hi/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/hi/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/hi/aspose.slides/shape/height)) से भिन्न हो सकती हैं और यदि रेंडर किया गया कंटेंट स्लाइड मूल बिंदु से बाहर तक फैलता है तो नकारात्मक निर्देशांक भी शामिल हो सकते हैं।

विजुअल बाउंड्स रेंडरिंग-संबंधित पहलुओं जैसे रूपांतरण (उदाहरण के लिए, घूर्णन), स्ट्रोक चौड़ाई और ज्वाइन, टेक्स्ट लेआउट और ओवरफ़्लो, SmartArt ज्योमेट्री, और अन्य लेआउट प्रभावों को ध्यान में रखते हैं जो शेप की अंतिम रेंडर की गई उपस्थिति को प्रभावित करते हैं।

वापसी सीमाएँ स्लाइड आयत तक क्लिप नहीं की गई हैं।

### See Also
* class [`AutoShape`](/slides/python-net/hi/aspose.slides/autoshape)
* module [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)