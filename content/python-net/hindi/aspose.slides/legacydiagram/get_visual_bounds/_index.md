---
title: get_visual_bounds method
second_title: Aspose.Slides के लिए Python via .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/legacydiagram/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
शेप के विज़ुअल बाउंड्स को उसके रेंडर किए गए कंटेंट से गणना करके प्राप्त करता है।

### Returns
एक **aspose.slides.RectangleF** जो स्लाइड कॉर्डिनेट्स में शेप के विज़ुअल बाउंड्स को दर्शाता है।

```python
def get_visual_bounds(self):
    ...
```

### Remarks
वापसी किया गया आयताकार सभी कंटेंट के अक्ष-समरेखित बाउंड्स को दर्शाता है जो रेंडरिंग के दौरान स्लाइड कॉर्डिनेट स्पेस में शेप द्वारा उत्पन्न किया जाता है।

इन बाउंड्स में शेप के मॉडल बाउंड्स ([`Shape.x`](/slides/python-net/hi/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/hi/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/hi/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/hi/aspose.slides/shape/height)) से अंतर हो सकता है और यदि रेंडर किया गया कंटेंट स्लाइड मूल बिंदु से बाहर जाता है तो इनमें नकारात्मक कॉर्डिनेट्स भी हो सकते हैं।

विज़ुअल बाउंड्स रेंडरिंग-संबंधित पहलुओं जैसे ट्रांसफ़ॉर्मेशन (उदाहरण के लिए, घुमाव), स्ट्रोक चौड़ाई और जोड़, टेक्स्ट लेआउट और ओवरफ़्लो, SmartArt ज्योमेट्री, और अन्य लेआउट प्रभावों को ध्यान में रखते हैं जो शेप की अंतिम रेंडर की गई उपस्थिति को प्रभावित करते हैं।

वापसी किए गए बाउंड्स स्लाइड आयत में क्लिप नहीं किए गए हैं।

### See Also
* वर्ग [`LegacyDiagram`](/slides/python-net/hi/aspose.slides/legacydiagram)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)