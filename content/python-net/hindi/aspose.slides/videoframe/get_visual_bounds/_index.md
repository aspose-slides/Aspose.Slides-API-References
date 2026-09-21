---
title: get_visual_bounds method
second_title: Aspose.Slides for Python के माध्यम से .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/videoframe/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
रेंडर की गई सामग्री से गणना की गई आकार की दृश्य सीमा को प्राप्त करता है।

### रिटर्न मान

एक **aspose.slides.RectangleF** जो स्लाइड निर्देशांकों में आकार की दृश्य सीमा का प्रतिनिधित्व करता है।



```python
def get_visual_bounds(self):
    ...
```


### टिप्पणी

वापसी किया गया आयताकार सभी सामग्री की अक्ष-संरेखित सीमाओं को दर्शाता है
             जो आकार द्वारा स्लाइड निर्देशांक क्षेत्र में रेंडरिंग के दौरान उत्पन्न की जाती है।

ये सीमाएँ आकार के मॉडल सीमाओं से भिन्न हो सकती हैं
             ([`Shape.x`](/slides/python-net/hi/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/hi/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/hi/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/hi/aspose.slides/shape/height))
             और यदि रेंडर किया गया सामग्री स्लाइड मूल बिंदु से परे विस्तारित हो तो नकारात्मक निर्देशांक हो सकते हैं।

विजुअल सीमाएँ रेंडरिंग-संबंधित पहलुओं जैसे रूपांतरण (उदाहरण के लिए, घूर्णन), स्ट्रोक चौड़ाई और जॉइन,
             पाठ लेआउट और ओवरफ़्लो, SmartArt ज्योमेट्री, और अन्य लेआउट प्रभावों को ध्यान में रखती हैं जो आकार की अंतिम रेंडर की गई उपस्थिति को प्रभावित करते हैं।

वापसी की गई सीमाएँ स्लाइड आयत तक क्लिप नहीं की गई हैं।



### देखें भी
* क्लास [`VideoFrame`](/slides/python-net/hi/aspose.slides/videoframe)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)