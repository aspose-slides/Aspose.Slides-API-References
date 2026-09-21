---
title: get_visual_bounds method
second_title: Aspose.Slides for Python via .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/table/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
रेंडर की गई सामग्री से गणना किए गए आकार की दृश्य सीमाओं को प्राप्त करता है।

### रिटर्न्स

एक **aspose.slides.RectangleF** जो स्लाइड निर्देशांक में आकार की दृश्य सीमाओं का प्रतिनिधित्व करता है।



```python
def get_visual_bounds(self):
    ...
```


### टिप्पणियाँ

वापसी किया गया आयत आकार द्वारा रेंडरिंग के दौरान उत्पन्न सभी सामग्री की अक्ष-सरल सीमाओं को स्लाइड निर्देशांक स्पेस में दर्शाता है।

ये सीमाएं आकार के मॉडल सीमाओं ([`Shape.x`](/slides/python-net/hi/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/hi/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/hi/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/hi/aspose.slides/shape/height)) से भिन्न हो सकती हैं और यदि रेंडर की गई सामग्री स्लाइड मूल बिंदु से बाहर विस्तारित होती है तो नकारात्मक निर्देशांक शामिल कर सकती हैं।

दृश्य सीमाएं ट्रांसफॉर्मेशन (उदाहरण के लिए, घूर्णन), स्ट्रोक चौड़ाई और जोड़, टेक्स्ट लेआउट और ओवरफ्लो, SmartArt ज्यामिति, और अन्य लेआउट प्रभावों जैसे रेंडरिंग-संबंधी पहलुओं को ध्यान में रखती हैं जो आकार की अंतिम रेंडर की गई उपस्थिति को प्रभावित करते हैं।

वापसी किए गए सीमाओं को स्लाइड आयत तक काटा नहीं जाता है।

### देखें
* वर्ग [`Table`](/slides/python-net/hi/aspose.slides/table)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)