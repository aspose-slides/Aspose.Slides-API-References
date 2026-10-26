---
title: get_visual_bounds method
second_title: Aspose.Slides for Python के लिए .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/graphicalobject/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
आकृति के रेंडर किए गए कंटेंट से गणना किए गए दृश्य सीमाओं को प्राप्त करता है।

### रिटर्न वैल्यू

एक [`RectangleF`](/slides/python-net/hi/aspose.slides/rectanglef) जो स्लाइड निर्देशांक में आकृति की दृश्य सीमाओं को दर्शाता है।



```python
def get_visual_bounds(self):
    ...
```


### टिप्पणियाँ

वापसी किया गया आयत आकृति द्वारा रेंडरिंग के दौरान स्लाइड निर्देशांक स्थान में उत्पन्न सभी सामग्री की अक्ष-संरेखित सीमाओं को दर्शाता है।

ये सीमाएँ आकृति के मॉडल बाउंड्स ([`Shape.x`](/slides/python-net/hi/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/hi/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/hi/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/hi/aspose.slides/shape/height)) से भिन्न हो सकती हैं और यदि रेंडर की गई सामग्री स्लाइड मूलबिंदु से परे विस्तारित हो तो नकारात्मक निर्देशांक भी शामिल कर सकती हैं।

दृश्य सीमाएँ रेंडरिंग से जुड़े पहलुओं जैसे रूपांतरण (उदाहरण के लिए, घुमाव), स्ट्रोक की चौड़ाई और जोड, पाठ लेआउट और ओवरफ़्लो, SmartArt ज्योमेट्री, और अन्य लेआउट प्रभावों को ध्यान में रखती हैं जो आकृति की अंतिम रेंडर की गई उपस्थिति को प्रभावित करते हैं।

वापसी की गई सीमाएँ स्लाइड आयत में क्लिप नहीं की गई हैं।



### संदर्भ
* क्लास [`GraphicalObject`](/slides/python-net/hi/aspose.slides/graphicalobject)
* क्लास [`RectangleF`](/slides/python-net/hi/aspose.slides/rectanglef)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)