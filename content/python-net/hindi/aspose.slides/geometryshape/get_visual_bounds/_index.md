---
title: get_visual_bounds method
second_title: Aspose.Slides for Python के लिए .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/geometryshape/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
रेंडर किए गए सामग्री से गणना किए गए आकार की दृश्य सीमाओं को प्राप्त करता है।

### रिटर्न

A **aspose.slides.RectangleF** जो आकार की दृश्य सीमाओं को दर्शाता है
             स्लाइड निर्देशांक में।

```python
def get_visual_bounds(self):
    ...
```

### टिप्पणियाँ

वापसी किया गया आयताकार सभी सामग्री की अक्ष-समतल सीमाओं को दर्शाता है
             आकार द्वारा रेंडरिंग के दौरान स्लाइड निर्देशांक स्थान में उत्पन्न।

इन सीमाओं में आकार के मॉडल सीमाओं से अंतर हो सकता है
             ([`Shape.x`](/slides/python-net/hi/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/hi/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/hi/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/hi/aspose.slides/shape/height))
             और यदि रेंडर की गई सामग्री स्लाइड के मूल बिंदु से आगे बढ़ती है तो नकारात्मक निर्देशांक भी हो सकते हैं।

दृश्य सीमाएँ रेंडरिंग से संबंधित पहलुओं को ध्यान में रखती हैं जैसे
             परिवर्तन (उदाहरण के लिए, घुमाव), स्ट्रोक की चौड़ाई और जोड़,
             टेक्स्ट लेआउट और ओवरफ़्लो, SmartArt ज्योमेट्री, और अन्य लेआउट प्रभाव
             जो आकार की अंतिम रेंडर की गई उपस्थिति को प्रभावित करते हैं।

वापसी की गई सीमाएँ स्लाइड आयत में क्लिप नहीं की गई हैं।

### और देखें
* क्लास [`GeometryShape`](/slides/python-net/hi/aspose.slides/geometryshape)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)