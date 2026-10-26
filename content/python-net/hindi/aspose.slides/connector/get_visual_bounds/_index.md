---
title: get_visual_bounds method
second_title: Aspose.Slides के लिए Python via .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/connector/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
आकृति के रेंडर किए गए कंटेंट से गणना किए गए दृश्य सीमाओं को प्राप्त करता है।

### रिटर्न्स
एक [`RectangleF`](/slides/python-net/hi/aspose.slides/rectanglef) जो स्लाइड निर्देशांक में आकार की दृश्य सीमाओं का प्रतिनिधित्व करता है।

```python
def get_visual_bounds(self):
    ...
```

### टिप्पणियाँ
वापसी किया गया आयताकार सभी कंटेंट की अक्ष-समंजित सीमाओं का प्रतिनिधित्व करता है जो रेंडरिंग के दौरान आकृति द्वारा उत्पन्न किया गया है, स्लाइड निर्देशांक स्थान में।

ये सीमाएं आकृति के मॉडल सीमाओं से अलग हो सकती हैं ([`Shape.x`](/slides/python-net/hi/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/hi/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/hi/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/hi/aspose.slides/shape/height)) और यदि रेंडर किया गया कंटेंट स्लाइड मूल बिंदु से आगे बढ़ता है तो नकारात्मक निर्देशांक भी शामिल हो सकते हैं।

दृश्य सीमाएं रेंडरिंग से संबंधित पहलुओं जैसे परिवर्तनों (उदाहरण के लिए, घूर्णन), स्ट्रोक चौड़ाई और जॉइन, टेक्स्ट लेआउट और ओवरफ़्लो, स्मार्टआर्ट ज्योमेट्री, तथा अन्य लेआउट प्रभावों को ध्यान में रखती हैं जो आकृति की अंतिम रेंडर की गई उपस्थिति को प्रभावित करते हैं।

वापसी की गई सीमाएं स्लाइड आयत में क्लिप नहीं की गई हैं।

### संबंधित देखें
* क्लास [`Connector`](/slides/python-net/hi/aspose.slides/connector)
* क्लास [`RectangleF`](/slides/python-net/hi/aspose.slides/rectanglef)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)