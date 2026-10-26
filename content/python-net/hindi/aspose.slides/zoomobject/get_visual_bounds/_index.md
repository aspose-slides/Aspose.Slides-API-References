---
title: get_visual_bounds method
second_title: Aspose.Slides के लिए Python के माध्यम से .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/zoomobject/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
शेप के रेंडर किए गए कंटेंट से गणना किए गए विज़ुअल बाउंड्स प्राप्त करता है।

### वापसी मान

[`RectangleF`](/slides/python-net/hi/aspose.slides/rectanglef) जो स्लाइड निर्देशांक में शैप के विज़ुअल बाउंड्स को दर्शाता है।



```python
def get_visual_bounds(self):
    ...
```


### टिप्पणी

वापस किया गया आयत स्लाइड निर्देशांक स्पेस में रेंडरिंग के दौरान शैप द्वारा उत्पन्न सभी कंटेंट की अक्ष-आधारित बाउंड्स को दर्शाता है।

ये बाउंड्स शैप के मॉडल बाउंड्स ([`Shape.x`](/slides/python-net/hi/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/hi/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/hi/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/hi/aspose.slides/shape/height)) से अलग हो सकते हैं और यदि रेंडर किया गया कंटेंट स्लाइड मूल बिंदु से आगे बढ़ता है तो नकारात्मक निर्देशांक भी शामिल हो सकते हैं।

विज़ुअल बाउंड्स रेंडरिंग से संबंधित पहलुओं जैसे ट्रांसफ़ॉर्मेशन (उदाहरण के लिए, रोटेशन), स्ट्रोक की चौड़ाई और जॉइन, टेक्स्ट लेआउट और ओवरफ़्लो, स्मार्टआर्ट ज्योमेट्री, और अन्य लेआउट प्रभावों को ध्यान में रखते हैं जो शैप की अंतिम रेंडर की गई उपस्थिति को प्रभावित करते हैं।

वापस किए गए बाउंड्स स्लाइड आयत तक सीमित नहीं होते।



### संबंधित देखें
* क्लास [`ZoomObject`](/slides/python-net/hi/aspose.slides/zoomobject)
* क्लास [`RectangleF`](/slides/python-net/hi/aspose.slides/rectanglef)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)