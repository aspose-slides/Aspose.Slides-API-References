---
title: get_visual_bounds method
second_title: Aspose.Slides के लिए Python द्वारा .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides.smartart/smartartshape/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
आकार की प्रदर्शित सामग्री से गणना किए गए दृश्य सीमाओं को प्राप्त करता है।

### रिटर्न मान

एक **aspose.slides.RectangleF** जो आकार की दृश्य सीमा को दर्शाता है
             स्लाइड निर्देशांक में।

```python
def get_visual_bounds(self):
    ...
```

### टिप्पणियाँ

वापसी किया गया आयताकार आकार रेंडरिंग के दौरान आकार द्वारा उत्पन्न सभी सामग्री की अक्ष-संरेखित सीमाओं को स्लाइड निर्देशांक स्थान में दर्शाता है
             ।

ये सीमाएँ आकार के मॉडल सीमाओं ([`Shape.x`](/slides/python-net/hi/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/hi/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/hi/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/hi/aspose.slides/shape/height)) से भिन्न हो सकती हैं और यदि प्रदर्शित सामग्री स्लाइड मूल बिंदु से आगे बढ़ती है तो इसमें **नकारात्मक निर्देशांक** हो सकते हैं
             ।

दृश्य सीमाएँ परिवर्तन (उदाहरण के लिए, घुमाव), स्ट्रोक चौड़ाई और जोड़, टेक्स्ट लेआउट और ओवरफ़्लो, SmartArt ज्यामिति, और अन्य लेआउट प्रभाव जैसे रेंडरिंग-संबंधी पहलुओं को ध्यान में रखती हैं जो आकार की अंतिम प्रदर्शित उपस्थिति को प्रभावित करते हैं
             ।

वापसी की गई सीमाएँ **स्लाइड आयत में** क्लिप नहीं की गई हैं
             ।

### संबंधित देखें
* क्लास [`SmartArtShape`](/slides/python-net/hi/aspose.slides.smartart/smartartshape)
* मॉड्यूल [`aspose.slides.smartart`](/slides/python-net/hi/aspose.slides.smartart)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)