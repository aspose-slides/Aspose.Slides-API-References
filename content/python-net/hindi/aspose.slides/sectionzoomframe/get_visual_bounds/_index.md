---
title: get_visual_bounds method
second_title: Aspose.Slides for Python via .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/sectionzoomframe/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
रेंडर की गई सामग्री से गणना किए गए शेप के दृश्य सीमाओं को प्राप्त करता है।

### रिटर्न

एक **aspose.slides.RectangleF** जो स्लाइड निर्देशांक में शेप की दृश्य सीमाओं को दर्शाता है



```python
def get_visual_bounds(self):
    ...
```


### टिप्पणी

वापसी आयत उस अक्ष-संरेखित सीमाओं को दर्शाती है जो सभी सामग्री की हैं जो स्लाइड निर्देशांक स्थान में रेंडरिंग के दौरान शेप द्वारा उत्पन्न की गई हैं।
             
ये सीमाएँ शेप के मॉडल सीमाओं से अलग हो सकती हैं ([`Shape.x`](/slides/python-net/hi/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/hi/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/hi/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/hi/aspose.slides/shape/height)) और यदि रेंडर किया गया सामग्री स्लाइड मूल बिंदु से बाहर विस्तारित होती है तो नकारात्मक निर्देशांकों को शामिल कर सकती हैं।
             
दृश्य सीमाएँ रेंडरिंग-संबंधी पहलुओं को ध्यान में रखती हैं जैसे कि रूपांतरण (उदाहरण के लिए, घुमाना), स्ट्रोक चौड़ाई और जोड़, टेक्स्ट लेआउट और ओवरफ़्लो, SmartArt ज्योमेट्री, और अन्य लेआउट प्रभाव जो शेप की अंतिम रेंडर किए गए रूप को प्रभावित करते हैं।
             
वापसी सीमाएँ स्लाइड आयत तक क्लिप नहीं की गई हैं।



### संबंधित देखें
* क्लास [`SectionZoomFrame`](/slides/python-net/hi/aspose.slides/sectionzoomframe)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)