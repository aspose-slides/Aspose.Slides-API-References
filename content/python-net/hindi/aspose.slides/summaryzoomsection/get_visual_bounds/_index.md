---
title: get_visual_bounds method
second_title: Aspose.Slides for Python द्वारा .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/summaryzoomsection/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
आकार की रेंडर की गई सामग्री से गणना किए गए दृश्य सीमाओं को प्राप्त करता है।

### रिटर्न

एक **aspose.slides.RectangleF** जो आकार की दृश्य सीमाओं का प्रतिनिधित्व करता है
             स्लाइड निर्देशांक में।



```python
def get_visual_bounds(self):
    ...
```


### टिप्पणियाँ

वापसी किया गया आयत आकार स्लाइड निर्देशांक स्थान में रेंडरिंग के दौरान आकार द्वारा उत्पन्न सभी सामग्री की अक्ष-संकुचित सीमाओं को दर्शाता है।

ये सीमाएँ आकार के मॉडल सीमाओं ([`Shape.x`](/slides/python-net/hi/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/hi/aspose.slides/shape/y),
[`Shape.width`](/slides/python-net/hi/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/hi/aspose.slides/shape/height))
से भिन्न हो सकती हैं और यदि रेंडर की गई सामग्री स्लाइड मूल बिंदु से बाहर विस्तारित होती है तो इनमें नकारात्मक निर्देशांक हो सकते हैं।

दृश्यमान सीमाएँ रेंडरिंग से संबंधित पहलुओं जैसे कि रूपांतरण (उदाहरण के लिए, घूर्णन), स्ट्रोक की चौड़ाई और जोड़, टेक्स्ट लेआउट और ओवरफ़्लो, SmartArt ज्यामिति, तथा अन्य लेआउट प्रभावों को ध्यान में रखती हैं, जो आकार की अंतिम रेंडर की गई उपस्थिति को प्रभावित करते हैं।

वापसी की गई सीमाएँ स्लाइड आयत में क्लिप नहीं की गईँ हैं।



### संबंधित देखें
* क्लास [`SummaryZoomSection`](/slides/python-net/hi/aspose.slides/summaryzoomsection)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)