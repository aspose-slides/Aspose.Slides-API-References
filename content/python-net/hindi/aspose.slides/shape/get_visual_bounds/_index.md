---
title: get_visual_bounds method
second_title: Aspose.Slides for Python via .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/shape/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
रेंडर किए गए कंटेंट से गणना करके आकार की दृश्य सीमाओं को प्राप्त करता है।

### रिटर्न

[`RectangleF`](/slides/python-net/hi/aspose.slides/rectanglef) वह वस्तु है जो आकार की दृश्य सीमाओं को
             स्लाइड निर्देशांकों में दर्शाती है।



```python
def get_visual_bounds(self):
    ...
```


### टिप्पणी

वापस किया गया आयताकार आकार स्लाइड निर्देशांक स्थान में रेंडरिंग के दौरान आकार द्वारा उत्पन्न सभी सामग्री की अक्ष-संरेखित सीमाओं को दर्शाता है।
            
            ये सीमाएँ आकार के मॉडल सीमाओं ([`Shape.x`](/slides/python-net/hi/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/hi/aspose.slides/shape/y),
            [`Shape.width`](/slides/python-net/hi/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/hi/aspose.slides/shape/height)) से भिन्न हो सकती हैं और यदि रेंडर किया गया कंटेंट स्लाइड मूल बिंदु से परे विस्तारित हो तो नकारात्मक निर्देशांक शामिल हो सकते हैं।
            
            दृश्य सीमाएँ रेंडरिंग-संबंधी पहलुओं जैसे कि परिवर्तन (उदाहरण के लिए, घुमाव), स्ट्रोक की चौड़ाई और जॉइन्स, पाठ लेआउट और ओवरफ़्लो, SmartArt ज्यामिति, और अन्य लेआउट प्रभावों को ध्यान में रखती हैं जो आकार की अंतिम रेंडरिंग दिखावट को प्रभावित करते हैं।
            
            वापस की गई सीमाएँ स्लाइड आयत में क्लिप नहीं की गई हैं।



### देखें
* क्लास [`Shape`](/slides/python-net/hi/aspose.slides/shape)
* क्लास [`RectangleF`](/slides/python-net/hi/aspose.slides/rectanglef)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)