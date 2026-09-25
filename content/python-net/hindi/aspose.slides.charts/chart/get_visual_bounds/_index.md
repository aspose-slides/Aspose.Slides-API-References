---
title: get_visual_bounds method
second_title: Aspose.Slides for Python via .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides.charts/chart/get_visual_bounds/
weight: 50
---
## get_visual_bounds(self) {#}
रेंडर किए गए कंटेंट से गणना किए गए आकार की दृश्य सीमाओं को प्राप्त करता है।

### रिटर्न
एक [`RectangleF`](/slides/python-net/hi/aspose.slides/rectanglef) जो स्लाइड निर्देशांक में आकार की दृश्य सीमाओं का प्रतिनिधित्व करता है।

```python
def get_visual_bounds(self):
    ...
```

### टिप्पणी
वापसी किया गया आयताकार आकार द्वारा रेंडरिंग के दौरान स्लाइड निर्देशांक स्थान में उत्पन्न सभी सामग्री की अक्ष-समरूप सीमाओं को दर्शाता है।

ये सीमाएँ आकार के मॉडल सीमाओं ([`Shape.x`](/slides/python-net/hi/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/hi/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/hi/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/hi/aspose.slides/shape/height)) से भिन्न हो सकती हैं और यदि रेंडर किया गया कंटेंट स्लाइड मूल बिंदु से आगे विस्तारित हो तो उनमें नकारात्मक निर्देशांक हो सकते हैं।

दृश्य सीमाएँ रेंडरिंग से संबंधित पहलुओं जैसे परिवर्तन (उदाहरण के लिए, घुमाव), स्ट्रोक चौड़ाई और जॉइन, टेक्स्ट लेआउट और ओवरफ़्लो, SmartArt ज्योमेट्री, और अन्य लेआउट प्रभावों को ध्यान में रखती हैं जो आकार की अंतिम रेंडर की गई उपस्थिति को प्रभावित करते हैं।

वापसी की गई सीमाएँ स्लाइड आयत में क्लिप नहीं की गई हैं।

### देखें
* क्लास [`Chart`](/slides/python-net/hi/aspose.slides.charts/chart)
* क्लास [`RectangleF`](/slides/python-net/hi/aspose.slides/rectanglef)
* मॉड्यूल [`aspose.slides.charts`](/slides/python-net/hi/aspose.slides.charts)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)