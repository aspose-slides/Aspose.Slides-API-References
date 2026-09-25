---
title: get_visual_bounds method
second_title: Aspose.Slides for Python via .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/summaryzoomframe/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
आकृति की दृश्य सीमा को प्राप्त करता है जो उसकी रेंडर की गई सामग्री से गणना की गई है।

### Returns

[`RectangleF`](/slides/python-net/hi/aspose.slides/rectanglef) वह वस्तु है जो स्लाइड निर्देशांकों में आकृति की दृश्य सीमा का प्रतिनिधित्व करती है।



```python
def get_visual_bounds(self):
    ...
```


### Remarks

वापसी किया गया आयताकार आकार स्लाइड निर्देशांक स्थान में रेंडरिंग के दौरान आकृति द्वारा उत्पन्न सभी सामग्री की अक्ष-समरेखित सीमाओं का प्रतिनिधित्व करता है।

ये सीमाएँ आकृति के मॉडल सीमाओं ([`Shape.x`](/slides/python-net/hi/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/hi/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/hi/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/hi/aspose.slides/shape/height)) से अलग हो सकती हैं और यदि रेंडर की गई सामग्री स्लाइड मूल बिंदु से परे विस्तारित होती है तो नकारात्मक निर्देशांक भी शामिल कर सकती हैं।

दृश्य सीमाएँ रेंडरिंग-संबंधी पहलुओं जैसे परिवर्तन (उदाहरण के लिए, घूर्णन), स्ट्रोक की चौड़ाई और जोड़, पाठ लेआउट और अतिप्रवाह, SmartArt ज्यामिति, और अन्य लेआउट प्रभावों को ध्यान में रखती हैं जो आकृति की अंतिम रेंडर की गई उपस्थिति को प्रभावित करते हैं।

वापसी की गई सीमाएँ स्लाइड आयत में क्लिप नहीं की गई हैं।


### See Also
* क्लास [`SummaryZoomFrame`](/slides/python-net/hi/aspose.slides/summaryzoomframe)
* क्लास [`RectangleF`](/slides/python-net/hi/aspose.slides/rectanglef)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)