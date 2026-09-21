---
title: get_visual_bounds method
second_title: Aspose.Slides के लिए Python .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/shape/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
शेपट के रेंडर की गई सामग्री से गणना किए गए आकार की दृश्य सीमाएँ प्राप्त करता है।

### रिटर्न
एक **aspose.slides.RectangleF** जो स्लाइड निर्देशांक में आकार की दृश्य सीमाओं को दर्शाता है।  

```python
def get_visual_bounds(self):
    ...
```

### टिप्पणी
वापसी किया गया आयत सभी सामग्री की अक्ष-समांतर सीमाओं का प्रतिनिधित्व करता है, जो आकार द्वारा स्लाइड निर्देशांक स्थान में रेंडरिंग के दौरान उत्पन्न की गई है।

ये सीमाएँ आकार के मॉडल सीमाओं ([`Shape.x`](/slides/python-net/hi/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/hi/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/hi/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/hi/aspose.slides/shape/height)) से भिन्न हो सकती हैं और यदि रेंडर की गई सामग्री स्लाइड मूल बिंदु से बाहर विस्तृत हो तो **नकारात्मक** निर्देशांक भी शामिल कर सकती हैं।

दृश्य सीमाएँ रेंडरिंग-संबंधित पहलुओं को ध्यान में रखती हैं जैसे कि रूपांतरण (उदाहरण के लिए, घुमाव), स्ट्रोक चौड़ाई और जॉइन्स, टेक्स्ट लेआउट और ओवरफ़्लो, SmartArt ज्यामिति, **और अन्य** लेआउट प्रभाव जो आकार की अंतिम रेंडर की गई उपस्थिति को प्रभावित करते हैं।

वापसी की गई सीमाओं को **स्लाइड आयत तक** नहीं काटा गया है।

### देखें
* क्लास [`Shape`](/slides/python-net/hi/aspose.slides/shape)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)