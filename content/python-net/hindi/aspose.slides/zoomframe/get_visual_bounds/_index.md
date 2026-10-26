---
title: get_visual_bounds method
second_title: Aspose.Slides Python के लिए .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/zoomframe/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
शेप के रेंडर किए गए कंटेंट से गणना किए गए दृश्य सीमाओं को प्राप्त करता है।

### रिटर्न

एक [`RectangleF`](/slides/python-net/hi/aspose.slides/rectanglef) जो स्लाइड निर्देशांकों में शेप की दृश्य सीमाओं को दर्शाता है।



```python
def get_visual_bounds(self):
    ...
```


### टिप्पणियाँ

वापसी किया गया आयताक्षर स्लाइड निर्देशांक स्थान में रेंडरिंग के दौरान शेप द्वारा उत्पन्न सभी कंटेंट की एक्सिस-अलाइन सीमाओं को दर्शाता है।

ये सीमाएँ शेप के मॉडल सीमाओं ([`Shape.x`](/slides/python-net/hi/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/hi/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/hi/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/hi/aspose.slides/shape/height)) से भिन्न हो सकती हैं और यदि रेंडर किया गया कंटेंट स्लाइड मूल बिंदु से आगे बढ़ता है तो नकारात्मक निर्देशांक भी शामिल हो सकते हैं।

दृश्य सीमाएँ ट्रांसफॉर्मेशन (उदाहरण के लिए, रोटेशन), स्ट्रोक चौड़ाई और जॉइन्स, टेक्स्ट लेआउट और ओवरफ़्लो, SmartArt ज्योमेट्री, तथा अन्य लेआउट प्रभावों जैसे रेंडरिंग-संबंधी पहलुओं को ध्यान में रखती हैं जो शेप की अंतिम रेंडर की गई उपस्थिति को प्रभावित करते हैं।

वापसी किए गए सीमाओं को स्लाइड आयताक्षर तक सीमित नहीं किया गया है।



### देखें
* क्लास [`ZoomFrame`](/slides/python-net/hi/aspose.slides/zoomframe)
* क्लास [`RectangleF`](/slides/python-net/hi/aspose.slides/rectanglef)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)