---
title: get_visual_bounds method
second_title: Aspose.Slides for Python via .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides.ink/ink/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
शेप के रेंडर किए गए कंटेंट से गणना किए गए दृश्य सीमाओं को प्राप्त करता है।

### वापसी मान

एक [`RectangleF`](/slides/python-net/hi/aspose.slides/rectanglef) जो स्लाइड निर्देशांक में शेप की दृश्य सीमाओं का प्रतिनिधित्व करता है।



```python
def get_visual_bounds(self):
    ...
```


### टिप्पणियाँ

वापसी किया गया आयत स्लाइड निर्देशांक स्थान में रेंडरिंग के दौरान शेप द्वारा उत्पन्न सभी सामग्री की अक्ष-समरेखित सीमाओं का प्रतिनिधित्व करता है।

ये सीमाएँ शेप के मॉडल सीमाओं ([`Shape.x`](/slides/python-net/hi/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/hi/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/hi/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/hi/aspose.slides/shape/height)) से भिन्न हो सकती हैं और यदि रेंडर किया गया कंटेंट स्लाइड मूल बिंदु से बाहर विस्तारित हो तो नकारात्मक निर्देशांक भी शामिल हो सकते हैं।

विज़ुअल बॉउंड्स रेंडरिंग से संबंधित पहलुओं जैसे ट्रांसफ़ॉर्मेशन (उदाहरण के लिए, रोटेशन), स्ट्रोक चौड़ाई और जोइन्स, टेक्स्ट लेआउट और ओवरफ़्लो, स्मार्टआर्ट ज्योमेट्री, और अन्य लेआउट प्रभावों को ध्यान में रखते हैं जो शेप के अंतिम रेंडर किए गए रूप को प्रभावित करते हैं।

वापसी किए गए सीमाएँ स्लाइड आयत में क्लिप नहीं की गई हैं।

### संबंधित देखें
* क्लास [`Ink`](/slides/python-net/hi/aspose.slides.ink/ink)
* क्लास [`RectangleF`](/slides/python-net/hi/aspose.slides/rectanglef)
* मॉड्यूल [`aspose.slides.ink`](/slides/python-net/hi/aspose.slides.ink)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)