---
title: get_visual_bounds method
second_title: Aspose.Slides Python के लिए .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/table/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
शेप के रेंडर किए गए सामग्री से गणना किए गए दृश्य सीमाओं को प्राप्त करता है।

### रिटर्न
एक [`RectangleF`](/slides/python-net/hi/aspose.slides/rectanglef) जो स्लाइड निर्देशांक में आकार की दृश्य सीमाओं को दर्शाता है।

```python
def get_visual_bounds(self):
    ...
```

### टिप्पणी
वापसी किया गया आयताकार आकार रेंडरिंग के दौरान आकार द्वारा उत्पन्न सभी सामग्री की अक्ष-समरेखित सीमाओं को स्लाइड निर्देशांक स्थान में दर्शाता है।

ये सीमाएँ आकार के मॉडल सीमाओं ([`Shape.x`](/slides/python-net/hi/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/hi/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/hi/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/hi/aspose.slides/shape/height)) से भिन्न हो सकती हैं और यदि रेंडर की गई सामग्री स्लाइड मूल बिंदु से परे विस्तारित होती है तो नकारात्मक निर्देशांक भी शामिल कर सकती हैं।

दृश्य सीमाएँ रेंडरिंग-संबंधित पहलुओं जैसे रूपांतरण (उदाहरण के लिए, घुमाव), स्ट्रोक चौड़ाई और जोड़ों, टेक्स्ट लेआउट और ओवरफ़्लो, SmartArt ज्यामिति, और अन्य लेआउट प्रभावों को ध्यान में रखती हैं जो आकार की अंतिम रेंडर किए गए रूप को प्रभावित करते हैं।

वापसी की गई सीमाएँ स्लाइड आयत में क्लिप नहीं की जाती हैं।

### देखें
* क्लास [`Table`](/slides/python-net/hi/aspose.slides/table)
* क्लास [`RectangleF`](/slides/python-net/hi/aspose.slides/rectanglef)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)