---
title: get_visual_bounds method
second_title: Aspose.Slides Python के लिए .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/summaryzoomsection/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
शेप के रेंडर किए गए कंटेंट से गणना किए गए विज़ुअल बाउंड्स प्राप्त करता है।

### रिटर्न
एक [`RectangleF`](/slides/python-net/hi/aspose.slides/rectanglef) जो शैप के विज़ुअल बाउंड्स को स्लाइड कोऑर्डिनेट्स में दर्शाता है।

```python
def get_visual_bounds(self):
    ...
```

### टिप्पणी
वापसी में प्राप्त आयत शैप द्वारा रेंडरिंग के दौरान स्लाइड कोऑर्डिनेट स्पेस में उत्पन्न सभी कंटेंट की अक्ष-संरेखित बाउंड्स को दर्शाती है।

इन बाउंड्स में शैप की मॉडल बाउंड्स ([`Shape.x`](/slides/python-net/hi/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/hi/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/hi/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/hi/aspose.slides/shape/height)) से अंतर हो सकता है और यदि रेंडर किया गया कंटेंट स्लाइड मूल बिंदु से आगे बढ़ता है तो इनमें नकारात्मक कोऑर्डिनेट्स हो सकते हैं।

विज़ुअल बाउंड्स रेंडरिंग-संबंधी पहलुओं जैसे ट्रांसफॉर्मेशन (उदाहरण के लिए, रोटेशन), स्ट्रोक चौड़ाई और जॉइन, टेक्स्ट लेआउट और ओवरफ़्लो, SmartArt ज्यामिति, और अन्य लेआउट प्रभावों को ध्यान में रखती हैं जो शैप की अंतिम रेंडर की गई उपस्थिति को प्रभावित करते हैं।

वापसी में प्राप्त बाउंड्स को स्लाइड आयत तक सीमित नहीं किया जाता।

### देखें
* क्लास [`SummaryZoomSection`](/slides/python-net/hi/aspose.slides/summaryzoomsection)
* क्लास [`RectangleF`](/slides/python-net/hi/aspose.slides/rectanglef)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)