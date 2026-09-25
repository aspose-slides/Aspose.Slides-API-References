---
title: get_visual_bounds method
second_title: Aspose.Slides for Python via .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/geometryshape/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
आकृति के रेंडर किए गए सामग्री से गणना किए गए दृश्य सीमाएं प्राप्त करता है।

### रिटर्न

एक [`RectangleF`](/slides/python-net/hi/aspose.slides/rectanglef) जो आकार की दृश्य सीमाओं का प्रतिनिधित्व करता है
             स्लाइड निर्देशांक में।  


```python
def get_visual_bounds(self):
    ...
```


### टिप्पणी

वापसी किया गया आयत सभी सामग्री की अक्ष-समरेखित सीमाओं का प्रतिनिधित्व करता है
             जो आकार द्वारा रेंडरिंग के दौरान स्लाइड निर्देशांक स्थान में उत्पन्न होता है।  

ये सीमाएं आकार की मॉडल सीमाओं से भिन्न हो सकती हैं
             ([`Shape.x`](/slides/python-net/hi/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/hi/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/hi/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/hi/aspose.slides/shape/height))
             और नकारात्मक निर्देशांक भी हो सकते हैं यदि रेंडर की गई सामग्री विस्तारित होती है
             स्लाइड मूल बिंदु से परे।  

दृश्य सीमाएं रेंडरिंग-संबंधित पहलुओं को ध्यान में रखती हैं जैसे
             परिवर्तन (उदाहरण के लिए, घूर्णन), स्ट्रोक चौड़ाई और जोड़,
             टेक्स्ट लेआउट और ओवरफ़्लो, SmartArt ज्योमेट्री, और अन्य लेआउट प्रभाव
             जो आकार की अंतिम रेंडर हुई उपस्थिति को प्रभावित करते हैं।  

वापसी की गई सीमाएं स्लाइड आयत तक सीमित नहीं होती हैं।  


### संबंधित देखें
* class [`GeometryShape`](/slides/python-net/hi/aspose.slides/geometryshape)
* class [`RectangleF`](/slides/python-net/hi/aspose.slides/rectanglef)
* module [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)