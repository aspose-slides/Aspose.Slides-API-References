---
title: get_visual_bounds method
second_title: Aspose.Slides for Python द्वारा .NET API रेफ़रेंस
description: 
type: docs
url: /hi/aspose.slides/oleobjectframe/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
आकार की रेंडर की गई सामग्री से गणना किए गए दृश्य सीमाएँ प्राप्त करता है।

### Returns

एक [`RectangleF`](/slides/python-net/hi/aspose.slides/rectanglef) जो स्लाइड निर्देशांक में आकार की दृश्य सीमाओं का प्रतिनिधित्व करता है।



```python
def get_visual_bounds(self):
    ...
```


### Remarks

वापसी में प्राप्त आयत स्लाइड निर्देशांक स्थान में रेंडरिंग के दौरान आकार द्वारा उत्पन्न सभी सामग्री की अक्ष-संरेखित सीमाओं का प्रतिनिधित्व करती है।

ये सीमाएँ आकार के मॉडल सीमाओं ([`Shape.x`](/slides/python-net/hi/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/hi/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/hi/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/hi/aspose.slides/shape/height)) से भिन्न हो सकती हैं और यदि रेंडर की गई सामग्री स्लाइड की मूल बिंदु के बाहर विस्तारित होती है तो नकारात्मक निर्देशांक भी शामिल कर सकती हैं।

दृश्य सीमाएँ रेंडरिंग से संबंधित पहलुओं जैसे कि रूपांतरण (उदाहरण के लिए, घूर्णन), स्ट्रोक चौड़ाई और जोड़, टेक्स्ट लेआउट और ओवरफ़्लो, SmartArt ज्यामिति, और अन्य लेआउट प्रभावों को ध्यान में रखती हैं जो आकार की अंतिम रेंडर की गई उपस्थिति को प्रभावित करते हैं।

वापसी में प्राप्त सीमाएँ स्लाइड आयत तक सीमित नहीं की जाती हैं।



### See Also
* क्लास [`OleObjectFrame`](/slides/python-net/hi/aspose.slides/oleobjectframe)
* क्लास [`RectangleF`](/slides/python-net/hi/aspose.slides/rectanglef)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)