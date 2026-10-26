---
title: get_visual_bounds method
second_title: Aspose.Slides Python के लिए .NET API संदर्भ के माध्यम से
description: 
type: docs
url: /hi/aspose.slides/legacydiagram/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
आकृति की दृश्यमान सीमाएँ प्राप्त करता है जो उसकी रेंडर्ड सामग्री से गणना की गई हैं।

### रिटर्न्स

एक [`RectangleF`](/slides/python-net/hi/aspose.slides/rectanglef) जो स्लाइड निर्देशांक में आकृति की दृश्यमान सीमाओं का प्रतिनिधित्व करता है



```python
def get_visual_bounds(self):
    ...
```


### टिप्पणियाँ

वापसी में प्राप्त आयताकार सभी सामग्री की अक्ष-समरेखित सीमाएँ दर्शाता है
जो स्लाइड निर्देशांक स्थान में रेंडरिंग के दौरान आकृति द्वारा उत्पन्न की गई हैं।

ये सीमाएँ आकृति के मॉडल सीमा से अलग हो सकती हैं
([`Shape.x`](/slides/python-net/hi/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/hi/aspose.slides/shape/y),
[`Shape.width`](/slides/python-net/hi/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/hi/aspose.slides/shape/height))
और यदि रेंडर्ड सामग्री स्लाइड मूल बिंदु से आगे निकलती है तो नकारात्मक निर्देशांक भी शामिल हो सकते हैं।

दृश्यमान सीमाएँ रेंडरिंग-संबंधित पहलुओं जैसे
रूपांतरण (उदाहरण के लिए, घुमाव), स्ट्रोक चौड़ाई और जोड़,
पाठ लेआउट और ओवरफ़्लो, SmartArt ज्यामिति, और अन्य लेआउट इफ़ेक्ट्स
को ध्यान में रखती हैं जो आकृति के अंतिम रेंडर्ड रूप को प्रभावित करते हैं।

वापसी की गई सीमाएँ स्लाइड आयताकार तक सीमित नहीं हैं।



### संबंधित देखें
* क्लास [`LegacyDiagram`](/slides/python-net/hi/aspose.slides/legacydiagram)
* क्लास [`RectangleF`](/slides/python-net/hi/aspose.slides/rectanglef)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)