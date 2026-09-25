---
title: get_visual_bounds method
second_title: Aspose.Slides for Python via .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/sectionzoomframe/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
शेप के रेंडर किए गए सामग्री से गणना किए गए दृश्य सीमाओं को प्राप्त करता है।

### रिटर्न्स
एक [`RectangleF`](/slides/python-net/hi/aspose.slides/rectanglef) जो स्लाइड निर्देशांक में शेप की दृश्य सीमाओं को दर्शाता है।

```python
def get_visual_bounds(self):
    ...
```

### टिप्पणी
वापस किया गया आयत आकार रेंडरिंग के दौरान शेप द्वारा उत्पन्न सभी सामग्री की अक्ष-अवलंबीय सीमाओं को स्लाइड निर्देशांक स्थान में दर्शाता है।  
ये सीमाएँ शेप के मॉडल बाउंड्स ([`Shape.x`](/slides/python-net/hi/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/hi/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/hi/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/hi/aspose.slides/shape/height)) से भिन्न हो सकती हैं और यदि रेंडर की गई सामग्री स्लाइड मूल बिंदु से परे विस्तारित होती है तो नकारात्मक निर्देशांक भी रख सकती हैं।  
दृश्य सीमाएँ रेंडरिंग से संबंधित पहलुओं जैसे परिवर्तन (उदाहरण के लिए, घूर्णन), स्ट्रोक चौड़ाई और जोड़, टेक्स्ट लेआउट और ओवरफ़्लो, SmartArt ज्यामिति, तथा अन्य लेआउट प्रभावों को ध्यान में रखती हैं जो शेप के अंतिम रेंडर किए गए रूप को प्रभावित करते हैं।  
वापस किए गए सीमाएँ स्लाइड आयत तक सीमित नहीं की गई हैं।

### संबंधित देखें
* क्लास [`SectionZoomFrame`](/slides/python-net/hi/aspose.slides/sectionzoomframe)
* क्लास [`RectangleF`](/slides/python-net/hi/aspose.slides/rectanglef)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)