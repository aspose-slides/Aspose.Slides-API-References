---
title: get_visual_bounds method
second_title: Aspose.Slides Python के लिये .NET API रेफ़रेंस के माध्यम से
description: 
type: docs
url: /hi/aspose.slides.smartart/smartartshape/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
शेप के रेंडर किए गए कंटेंट से गणना की गई दृश्य सीमाएँ प्राप्त करता है।

### Returns

एक [`RectangleF`](/slides/python-net/hi/aspose.slides/rectanglef) जो स्लाइड निर्देशांकों में शेप की दृश्य सीमाओं का प्रतिनिधित्व करता है।



```python
def get_visual_bounds(self):
    ...
```


### Remarks

वापसी आयत सभी कंटेंट की अक्ष-संरेखित सीमाओं का प्रतिनिधित्व करती है,
             जो स्लाइड निर्देशांक स्थान में रेंडरिंग के दौरान शेप द्वारा उत्पन्न किया जाता है।

             ये सीमाएँ शेप के मॉडल बाउंड्स ([`Shape.x`](/slides/python-net/hi/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/hi/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/hi/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/hi/aspose.slides/shape/height))
             से भिन्न हो सकती हैं और यदि रेंडर किया गया कंटेंट स्लाइड मूल बिंदु से आगे बढ़ता है तो नकारात्मक निर्देशांक भी हो सकते हैं।

             विज़ुअल बाउंड्स रेंडरिंग से संबंधित पहलुओं जैसे परिवर्तन (उदाहरण के लिए, घुमाव), स्ट्रोक की चौड़ाई और जॉइन,
             टेक्स्ट लेआउट और ओवरफ़्लो, SmartArt ज्योमेट्री, और अन्य लेआउट प्रभावों को ध्यान में रखते हैं जो शेप की अंतिम रेंडर की गई उपस्थिति को प्रभावित करते हैं।

             वापसी सीमाएँ स्लाइड आयत तक क्लिप नहीं की गई हैं।



### और देखें
* क्लास [`SmartArtShape`](/slides/python-net/hi/aspose.slides.smartart/smartartshape)
* क्लास [`RectangleF`](/slides/python-net/hi/aspose.slides/rectanglef)
* मॉड्यूल [`aspose.slides.smartart`](/slides/python-net/hi/aspose.slides.smartart)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)