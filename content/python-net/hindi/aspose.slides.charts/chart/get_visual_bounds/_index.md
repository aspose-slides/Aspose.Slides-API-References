---
title: get_visual_bounds method
second_title: Aspose.Slides Python के लिए .NET API संदर्भ के माध्यम से
description: 
type: docs
url: /hi/aspose.slides.charts/chart/get_visual_bounds/
weight: 50
---
## get_visual_bounds(self) {#}
शेप के रेंडर किए गए कंटेंट से गणना की गई दृश्य सीमा प्राप्त करता है।

### Returns
एक **aspose.slides.RectangleF** जो स्लाइड निर्देशांक में शैप की दृश्य सीमा को दर्शाता है
             in slide coordinates.



```python
def get_visual_bounds(self):
    ...
```


### Remarks
वापसी किया गया आयत शैप द्वारा रेंडरिंग के दौरान स्लाइड निर्देशांक स्थान में उत्पन्न सभी सामग्री की एक्सिस-लाइनड सीमाओं को दर्शाता है।

इन सीमाओं में शैप के मॉडल बाउंड्स ([`Shape.x`](/slides/python-net/hi/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/hi/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/hi/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/hi/aspose.slides/shape/height))
से अंतर हो सकता है और यदि रेंडर किया गया कंटेंट स्लाइड मूल बिंदु से परे विस्तारित होता है तो इनमें नकारात्मक निर्देशांक हो सकते हैं।

विज़ुअल बॉन्ड्स रेंडरिंग से संबंधित पहलुओं जैसे कि ट्रांसफ़ॉर्मेशन (उदाहरण के लिए, rotation), स्ट्रोक चौड़ाई और जॉइन, टेक्स्ट लेआउट और ओवरफ़्लो, SmartArt ज्योमेट्री, और अन्य लेआउट प्रभावों को ध्यान में रखते हैं जो शैप की अंतिम रेंडर की गई उपस्थिति को प्रभावित करते हैं।

वापसी की गई सीमाएँ स्लाइड आयत में क्लिप नहीं की गई हैं।



### See Also
* क्लास [`Chart`](/slides/python-net/hi/aspose.slides.charts/chart)
* मॉड्यूल [`aspose.slides.charts`](/slides/python-net/hi/aspose.slides.charts)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)