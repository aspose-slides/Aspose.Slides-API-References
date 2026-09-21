---
title: get_visual_bounds method
second_title: Aspose.Slides Python के लिए .NET API संदर्भ के माध्यम से
description: 
type: docs
url: /hi/aspose.slides/groupshape/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
रेंडर की गई सामग्री से गणना किए गए shape की दृश्य सीमाओं को प्राप्त करता है।

### रिटर्न
एक **aspose.slides.RectangleF** जो slide निर्देशांक में shape की दृश्य सीमाओं का प्रतिनिधित्व करता है।

```python
def get_visual_bounds(self):
    ...
```

### टिप्पणी
वापस किया गया आयत (rectangle) slide निर्देशांक स्थान में रेंडरिंग के दौरान shape द्वारा उत्पन्न सभी सामग्री की एक्सिस-एलाइन सीमाओं का प्रतिनिधित्व करता है।

ये सीमाएँ shape के मॉडल बाउंड्स ([`Shape.x`](/slides/python-net/hi/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/hi/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/hi/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/hi/aspose.slides/shape/height)) से अलग हो सकती हैं और यदि रेंडर की गई सामग्री slide मूल बिंदु से परे विस्तारित हो तो नकारात्मक निर्देशांक भी हो सकते हैं।

दृश्य सीमाएँ रेंडरिंग से संबंधित पहलुओं जैसे ट्रांसफ़ॉर्मेशन (उदाहरण के लिए, रोटेशन), स्ट्रोक चौड़ाई और जॉइन्स, टेक्स्ट लेआउट और ओवरफ़्लो, SmartArt ज्योमेट्री, तथा अन्य लेआउट प्रभावों को ध्यान में रखती हैं, जो shape की अंतिम रेंडर की गई दिखावट को प्रभावित करते हैं।

वापस की गई सीमाएँ slide आयत में क्लिप नहीं की गई हैं।

### देखें
* क्लास [`GroupShape`](/slides/python-net/hi/aspose.slides/groupshape)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)