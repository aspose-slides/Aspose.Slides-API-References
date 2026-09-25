---
title: get_visual_bounds method
second_title: Aspose.Slides Python के लिए .NET API संदर्भ के माध्यम से
description: 
type: docs
url: /hi/aspose.slides/videoframe/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
आकार के दृश्य सीमाओं को इसके रेंडर किए गए कंटेंट से गणना करके प्राप्त करता है।

### वापसी

एक [`RectangleF`](/slides/python-net/hi/aspose.slides/rectanglef) जो स्लाइड समन्वय में आकार की दृश्य सीमाओं को प्रदर्शित करता है।



```python
def get_visual_bounds(self):
    ...
```


### टिप्पणी

वापसी किया गया आयत सभी कंटेंट की अक्ष-समरूप सीमाओं को दर्शाता है
             जो आकार द्वारा रेंडरिंग के दौरान स्लाइड समन्वय स्थान में उत्पन्न किया गया है।

ये सीमाएँ आकार के मॉडल बाउंड्स से अलग हो सकती हैं
             ([`Shape.x`](/slides/python-net/hi/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/hi/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/hi/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/hi/aspose.slides/shape/height))
             और यदि रेंडर किया गया कंटेंट स्लाइड मूल बिंदु से आगे बढ़ता है तो
             नकारात्मक समन्वय शामिल हो सकते हैं।

दृश्य सीमाएँ रेंडरिंग-संबंधी पहलुओं को ध्यान में रखती हैं जैसे
             परिवर्तन (उदाहरण के लिए, घूर्णन), स्ट्रोक चौड़ाई और जोडें,
             टेक्स्ट लेआउट और ओवरफ़्लो, SmartArt ज्यामिति, और अन्य लेआउट प्रभाव
             जो आकार की अंतिम रेंडर की गई उपस्थिति को प्रभावित करते हैं।

वापसी की गई सीमाएँ स्लाइड आयत में क्लिप नहीं की गई हैं।



### और देखें
* क्लास [`VideoFrame`](/slides/python-net/hi/aspose.slides/videoframe)
* क्लास [`RectangleF`](/slides/python-net/hi/aspose.slides/rectanglef)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)