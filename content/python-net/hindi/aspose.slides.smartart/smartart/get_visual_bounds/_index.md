---
title: get_visual_bounds method
second_title: Aspose.Slides के लिए Python के माध्यम से .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides.smartart/smartart/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
आकृति के रेंडर्ड कंटेंट से गणना किए गए दृश्य सीमाओं को प्राप्त करता है।

### Returns
एक [`RectangleF`](/slides/python-net/hi/aspose.slides/rectanglef) जो स्लाइड कॉर्डिनेट्स में आकृति की दृश्य सीमाओं का प्रतिनिधित्व करता है।
             
             
```python
def get_visual_bounds(self):
    ...
```
             
             
### Remarks
वापसी किया गया आयताकार वह अक्ष-समतल सीमा दर्शाता है जो आकृति द्वारा रेंडरिंग के दौरान स्लाइड कोऑर्डिनेट स्पेस में उत्पन्न सभी कंटेंट की है।
             
ये सीमाएँ आकृति के मॉडल बाउंड्स ([`Shape.x`](/slides/python-net/hi/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/hi/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/hi/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/hi/aspose.slides/shape/height)) से भिन्न हो सकती हैं और यदि रेंडर्ड कंटेंट स्लाइड मूल से बाहर तक बढ़ जाता है तो नकारात्मक कोऑर्डिनेट्स भी शामिल हो सकते हैं।
             
दृश्य सीमाएँ रेंडरिंग-संबंधी पहलुओं को ध्यान में रखती हैं जैसे ट्रांसफ़ॉर्मेशन (उदाहरण के लिए, रोटेशन), स्ट्रोक चौड़ाई और जॉइन, टेक्स्ट लेआउट और ओवरफ़्लो, SmartArt जियोमेट्री, तथा अन्य लेआउट प्रभाव जो आकृति की अंतिम रेंडर की गई उपस्थिति को प्रभावित करते हैं।
             
वापसी की गई सीमाएँ स्लाइड आयताकार तक क्लिप नहीं की जाती हैं।
             
### See Also
* क्लास [`SmartArt`](/slides/python-net/hi/aspose.slides.smartart/smartart)
* क्लास [`RectangleF`](/slides/python-net/hi/aspose.slides/rectanglef)
* मॉड्यूल [`aspose.slides.smartart`](/slides/python-net/hi/aspose.slides.smartart)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)