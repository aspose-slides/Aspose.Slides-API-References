---
title: get_visual_bounds method
second_title: Aspose.Slides Python के लिए .NET API रेफ़रेंसेज
description: 
type: docs
url: /hi/aspose.slides/connector/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
शेप के रेंडर किए गए कंटेंट से गणना किए गए दृश्य सीमा को प्राप्त करता है।

### रिटर्न मान

A **aspose.slides.RectangleF** जो शेप की दृश्य सीमा को स्लाइड निर्देशांक में दर्शाता है।

```python
def get_visual_bounds(self):
    ...
```

### टिप्पणियाँ

वापस किया गया आयताकार सभी कंटेंट की धुरी-समान सीमाओं को दर्शाता है जो शेप द्वारा रेंडरिंग के दौरान स्लाइड निर्देशांक स्थान में उत्पन्न किया गया है।

इन सीमाओं में शेप के मॉडल सीमाएँ ([`Shape.x`](/slides/python-net/hi/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/hi/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/hi/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/hi/aspose.slides/shape/height)) शामिल नहीं हो सकती हैं और यदि रेंडर किया गया कंटेंट स्लाइड मूल बिंदु से परे विस्तारित हो तो नकारात्मक निर्देशांक भी हो सकते हैं।

विज़ुअल बाउंड्स रेंडरिंग-संबंधी पहलुओं जैसे ट्रांसफ़ॉर्मेशन (उदाहरण के लिए, रोटेशन), स्ट्रोक चौड़ाई और जॉइन, टेक्स्ट लेआउट और ओवरफ़्लो, स्मार्टआर्ट ज्योमेट्री, तथा अन्य लेआउट प्रभावों को ध्यान में रखते हैं जो शेप की अंतिम रेंडर की गई उपस्थिति को प्रभावित करते हैं।

वापस की गई सीमाएँ स्लाइड आयताकार तक सीमित नहीं की गई हैं।

### संबंधित देखें
* क्लास [`Connector`](/slides/python-net/hi/aspose.slides/connector)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)