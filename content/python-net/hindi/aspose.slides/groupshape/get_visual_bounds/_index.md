---
title: get_visual_bounds method
second_title: Aspose.Slides for Python via .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/groupshape/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
शेप के रेंडर किए गए कंटेंट से गणना किए गए विज़ुअल बाउंड्स प्राप्त करता है।

### वापसी

एक [`RectangleF`](/slides/python-net/hi/aspose.slides/rectanglef) जो स्लाइड निर्देशांक में शेप के विज़ुअल बाउंड्स को दर्शाता है।

```python
def get_visual_bounds(self):
    ...
```

### टिप्पणी

वापसी किया गया आयताकार सभी कंटेंट के अक्ष-अलाइन बाउंड्स को दर्शाता है जो रेंडरिंग के दौरान शेप द्वारा स्लाइड निर्देशांक में उत्पन्न किया गया।

ये बाउंड्स शेप के मॉडल बाउंड्स ([`Shape.x`](/slides/python-net/hi/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/hi/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/hi/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/hi/aspose.slides/shape/height)) से भिन्न हो सकते हैं और यदि रेंडर किया गया कंटेंट स्लाइड मूल बिंदु से आगे बढ़ता है तो नकारात्मक निर्देशांक भी शामिल हो सकते हैं।

विज़ुअल बाउंड्स रेंडरिंग से संबंधित पहलुओं जैसे रूपांतरण (उदाहरण के लिए, घुमाव), स्ट्रोक चौड़ाई और जोड़ों, टेक्स्ट लेआउट और ओवरफ़्लो, SmartArt ज्योमेट्री, और अन्य लेआउट प्रभावों को ध्यान में रखते हैं जो शेप की अंतिम रेंडर हुई उपस्थिति को प्रभावित करते हैं।

वापसी किए गए बाउंड्स को स्लाइड आयताकार में क्लिप नहीं किया जाता है।

### देखें
* वर्ग [`GroupShape`](/slides/python-net/hi/aspose.slides/groupshape)
* वर्ग [`RectangleF`](/slides/python-net/hi/aspose.slides/rectanglef)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)