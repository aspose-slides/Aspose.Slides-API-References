---
title: get_visual_bounds method
second_title: Aspose.Slides for Python के लिए .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/zoomframe/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
रेंडर किए गए कंटेंट से गणना किए गए आकार की दृश्य सीमाओं को प्राप्त करता है।

### वापसी

एक **aspose.slides.RectangleF** जो आकार की दृश्य सीमाओं का प्रतिनिधित्व करता है
             स्लाइड निर्देशांक में।



```python
def get_visual_bounds(self):
    ...
```


### टिप्पणी

वापसी किया गया आयताकार स्लाइड निर्देशांक स्थान में रेंडरिंग के दौरान आकार द्वारा उत्पन्न सभी कंटेंट की अक्ष-समरेखित सीमाओं को दर्शाता है.

ये सीमाएं आकार की मॉडल सीमाओं से भिन्न हो सकती हैं
             ([`Shape.x`](/slides/python-net/hi/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/hi/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/hi/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/hi/aspose.slides/shape/height))
             और यदि रेंडर किया गया कंटेंट स्लाइड मूल बिंदु से आगे बढ़ता है तो नकारात्मक निर्देशांक हो सकते हैं
             स्लाइड मूल बिंदु से परे।

विजुअल बॉउंड्स रेंडरिंग से संबंधित पहलुओं को ध्यान में रखते हैं जैसे
 transformations (उदाहरण के लिए, rotation), stroke width and joins,
 text layout and overflow, SmartArt geometry, and other layout effects
 that influence the final rendered appearance of the shape.

            वापसी की गई सीमाएं स्लाइड आयत तक सीमित नहीं होती हैं.



### देखें
* क्लास [`ZoomFrame`](/slides/python-net/hi/aspose.slides/zoomframe)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)