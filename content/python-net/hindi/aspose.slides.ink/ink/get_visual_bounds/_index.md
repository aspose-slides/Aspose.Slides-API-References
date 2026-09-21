---
title: get_visual_bounds method
second_title: Aspose.Slides पायथन के लिए .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides.ink/ink/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
आकृति की दृश्य सीमाओं को उसके रेंडर किए गए कंटेंट से गणना करके प्राप्त करता है।

### Returns
एक **aspose.slides.RectangleF** जो स्लाइड निर्देशांक में आकृति की दृश्य सीमाओं को दर्शाता है
             ।

```python
def get_visual_bounds(self):
    ...
```

### Remarks
वापस किया गया आयताकार सभी सामग्री की अक्ष-समरेखित सीमाओं को दर्शाता है
             जो रेंडरिंग के दौरान स्लाइड निर्देशांक स्थान में आकृति द्वारा उत्पन्न होती हैं।
            
             ये सीमाएँ आकृति के मॉडल सीमाओं से भिन्न हो सकती हैं
             ([`Shape.x`](/slides/python-net/hi/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/hi/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/hi/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/hi/aspose.slides/shape/height))
             और यदि रेंडर किया गया कंटेंट स्लाइड मूल बिंदु से बाहर विस्तारित होता है तो नकारात्मक निर्देशांक शामिल हो सकते हैं।
            
             दृश्य सीमाएँ रेंडरिंग-सम्बन्धी पहलुओं जैसे
             रूपांतरण (उदा., घूर्णन), स्ट्रोक चौड़ाई और जोड़,
             टेक्स्ट लेआउट और ओवरफ़्लो, SmartArt ज्योमेट्री, तथा अन्य लेआउट प्रभावों को ध्यान में रखती हैं
             जो आकृति की अंतिम रेंडर की गई उपस्थिति को प्रभावित करते हैं।
            
             वापस की गई सीमाएँ स्लाइड आयत में क्लिप नहीं की गई हैं।

### संबंधित देखें
* class [`Ink`](/slides/python-net/hi/aspose.slides.ink/ink)
* module [`aspose.slides.ink`](/slides/python-net/hi/aspose.slides.ink)
* library [`Aspose.Slides`](/slides/python-net)