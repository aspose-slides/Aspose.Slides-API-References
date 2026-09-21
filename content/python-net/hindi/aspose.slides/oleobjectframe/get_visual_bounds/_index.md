---
title: get_visual_bounds method
second_title: Aspose.Slides for Python via .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/oleobjectframe/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
शेप की रेंडर की गई सामग्री से गणना किए गए दृश्य सीमाओं को प्राप्त करता है।

### Returns

एक **aspose.slides.RectangleF** जो स्लाइड कॉर्डिनेट्स में शेप की दृश्य सीमाओं को दर्शाता है।



```python
def get_visual_bounds(self):
    ...
```


### Remarks

वापसी किया गया आयताकार स्लाइड कॉर्डिनेट स्पेस में रेंडरिंग के दौरान शेप द्वारा उत्पन्न सभी सामग्री की अक्ष-अलाइन सीमाओं को दर्शाता है।

ये सीमाएँ शेप के मॉडल बाउंड्स ([`Shape.x`](/slides/python-net/hi/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/hi/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/hi/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/hi/aspose.slides/shape/height)) से अलग हो सकती हैं और यदि रेंडर की गई सामग्री स्लाइड मूल बिंदु से परे जाती है तो इनमें नकारात्मक कोऑर्डिनेट्स भी हो सकते हैं।

विज़ुअल बाउंड्स रेंडरिंग-संबंधी पहलुओं जैसे परिवर्तन (उदाहरण के लिए, रोटेशन), स्ट्रोक चौड़ाई और जॉइन्स, टेक्स्ट लेआउट और ओवरफ़्लो, SmartArt ज्योमेट्री, और अन्य लेआउट प्रभावों को ध्यान में रखते हैं जो शेप की अंतिम रेंडर की गई उपस्थिति को प्रभावित करते हैं।

वापसी की गई सीमाएँ स्लाइड आयत तक क्लिप नहीं की गई हैं।



### See Also
* क्लास [`OleObjectFrame`](/slides/python-net/hi/aspose.slides/oleobjectframe)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)