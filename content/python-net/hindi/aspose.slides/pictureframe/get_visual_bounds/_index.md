---
title: get_visual_bounds method
second_title: Aspose.Slides for Python via .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/pictureframe/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
रेंडर किए गए कंटेंट से गणना की गई आकार की दृश्यमान सीमाओं को प्राप्त करता है।

### वापसी
एक **aspose.slides.RectangleF** जो स्लाइड निर्देशांकों में आकार की दृश्यमान सीमाओं का प्रतिनिधित्व करता है।

```python
def get_visual_bounds(self):
    ...
```

### टिप्पणियाँ
वापसी किया गया आयत आकार द्वारा रेंडरिंग के दौरान स्लाइड निर्देशांक स्थान में उत्पन्न सभी कंटेंट की अक्ष-संरेखित सीमाओं का प्रतिनिधित्व करता है।

ये सीमाएँ आकार के मॉडल बाउंड्स ([`Shape.x`](/slides/python-net/hi/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/hi/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/hi/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/hi/aspose.slides/shape/height)) से अलग हो सकती हैं और यदि रेंडर किया गया कंटेंट स्लाइड मूल बिंदु से आगे विस्तृत हो तो इनमें नकारात्मक निर्देशांक भी हो सकते हैं।

दृश्यमान सीमाएँ रेंडरिंग से संबंधित पहलुओं जैसे परिवर्तन (उदाहरण के लिए, घुमाव), स्ट्रोक चौड़ाई और जॉइन्स, टेक्स्ट लेआउट और ओवरफ़्लो, SmartArt ज्योमेट्री, और अन्य लेआउट प्रभावों को ध्यान में रखती हैं जो आकार की अंतिम रेंडर की गई उपस्थिति को प्रभावित करते हैं।

वापस मिली सीमाएँ स्लाइड आयत तक सीमित नहीं हैं।

### संबंधित देखें
* क्लास [`PictureFrame`](/slides/python-net/hi/aspose.slides/pictureframe)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)