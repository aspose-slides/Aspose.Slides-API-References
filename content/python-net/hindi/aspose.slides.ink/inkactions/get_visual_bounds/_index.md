---
title: get_visual_bounds method
second_title: Aspose.Slides के लिए Python via .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides.ink/inkactions/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
शेप की रेंडर की गई सामग्री से गणना की गई दृश्य सीमा प्राप्त करता है।

### Returns
A [`RectangleF`](/slides/python-net/hi/aspose.slides/rectanglef) जो शेप की दृश्य सीमा को
             स्लाइड निर्देशांक में दर्शाता है।



```python
def get_visual_bounds(self):
    ...
```


### Remarks
वापसी आयत सभी कंटेंट की धुरी-संरेखित सीमाओं को दर्शाती है
             शेप द्वारा रेंडरिंग के दौरान स्लाइड निर्देशांक स्थान में उत्पन्न।

ये सीमाएँ शेप के मॉडल बाउंड्स से भिन्न हो सकती हैं
             ([`Shape.x`](/slides/python-net/hi/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/hi/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/hi/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/hi/aspose.slides/shape/height))
             और रेंडर किया गया कंटेंट स्लाइड मूल से बाहर तक विस्तार करता है तो नकारात्मक निर्देशांक हो सकते हैं
             स्लाइड मूल से परे।

विज़ुअल बाउंड्स रेंडरिंग-संबंधित पहलुओं को ध्यान में रखते हैं जैसे ट्रांसफ़ॉर्मेशन (उदाहरण के लिए, घुमाव), स्ट्रोक चौड़ाई और जॉइन्स, टेक्स्ट लेआउट और ओवरफ़्लो, SmartArt जियोमेट्री, और अन्य लेआउट प्रभाव जो शेप के अंतिम रेंडर किए गए रूप को प्रभावित करते हैं।

वापसी सीमाएँ स्लाइड आयत में क्लिप नहीं की गई हैं।



### संबंधित देखें
* क्लास [`InkActions`](/slides/python-net/hi/aspose.slides.ink/inkactions)
* क्लास [`RectangleF`](/slides/python-net/hi/aspose.slides/rectanglef)
* मॉड्यूल [`aspose.slides.ink`](/slides/python-net/hi/aspose.slides.ink)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)