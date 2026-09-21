---
title: get_visual_bounds method
second_title: Aspose.Slides for Python via .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/summaryzoomframe/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
आकार के रेंडर किए गए सामग्री से गणना किए गए दृश्य सीमाएँ प्राप्त करता है।

### रिटर्न

A **aspose.slides.RectangleF** that represents the visual bounds of the shape
             in slide coordinates.



```python
def get_visual_bounds(self):
    ...
```


### टिप्पणी

वापसी किया गया आयताकार आकार स्लाइड निर्देशांक स्थान में रेंडरिंग के दौरान आकार द्वारा उत्पन्न सभी सामग्री की अक्ष-संरेखित सीमाओं को दर्शाता है।
            
             ये सीमाएँ आकार के मॉडल सीमाओं ([`Shape.x`](/slides/python-net/hi/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/hi/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/hi/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/hi/aspose.slides/shape/height))
             से भिन्न हो सकती हैं और यदि रेंडर किया गया कंटेंट स्लाइड मूल बिंदु से परे विस्तारित हो तो इसमें नकारात्मक निर्देशांक भी हो सकते हैं।
            
             दृश्य सीमाएँ ट्रांसफ़ॉर्मेशन (उदाहरण के लिए, रोटेशन), स्ट्रोक चौड़ाई और जोड़, टेक्स्ट लेआउट और ओवरफ़्लो, SmartArt ज्यामिति, और अन्य लेआउट प्रभावों जैसे रेंडरिंग-संबंधी पहलुओं को ध्यान में रखती हैं, जो आकार की अंतिम रेंडर किए गए स्वरूप को प्रभावित करते हैं।
            
             वापसी की गई सीमाएँ स्लाइड आयत के भीतर क्लिप नहीं की गई हैं।



### संबंधित देखें
* क्लास [`SummaryZoomFrame`](/slides/python-net/hi/aspose.slides/summaryzoomframe)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)