---
title: get_visual_bounds method
second_title: Aspose.Slides for Python, .NET API संदर्भ के माध्यम से
description: 
type: docs
url: /hi/aspose.slides/autoshape/get_visual_bounds/
weight: 70
---
## get_visual_bounds(self) {#}
आकार के रेंडर किए गए सामग्री से गणना किए गए दृश्य सीमाओं को प्राप्त करता है।

### Returns
A [`RectangleF`](/slides/python-net/hi/aspose.slides/rectanglef) जो आकार की दृश्य सीमाओं का प्रतिनिधित्व करता है
             स्लाइड निर्देशांकों में.



```python
def get_visual_bounds(self):
    ...
```


### टिप्पणियाँ
लौटा गया आयत सभी सामग्री की अक्ष-संरेखित सीमाओं का प्रतिनिधित्व करता है
             आकार द्वारा स्लाइड निर्देशांक स्थान में रेंडरिंग के दौरान उत्पन्न किया गया।

             ये सीमाएं आकार के मॉडल सीमाओं से अलग हो सकती हैं
             ([`Shape.x`](/slides/python-net/hi/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/hi/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/hi/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/hi/aspose.slides/shape/height))
             और नकारात्मक निर्देशांक रख सकती हैं यदि रेंडर की गई सामग्री विस्तारित होती है
             स्लाइड मूल के परे।

             दृश्य सीमाएं रेंडरिंग-संबंधी पहलुओं को ध्यान में रखती हैं जैसे
             परिवर्तन (उदाहरण के लिए, घुमाव), स्ट्रोक चौड़ाई और जॉइन,
             पाठ लेआउट और ओवरफ़्लो, स्मार्टआर्ट ज्यॉमिक्स, और अन्य लेआउट प्रभाव
             जो आकार की अंतिम रेंडर की गई उपस्थिति को प्रभावित करते हैं।

             लौटा गया सीमाएं स्लाइड आयत में क्लिप नहीं की गई हैं।


### संबंधित देखें
* क्लास [`AutoShape`](/slides/python-net/hi/aspose.slides/autoshape)
* क्लास [`RectangleF`](/slides/python-net/hi/aspose.slides/rectanglef)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* पुस्तकालय [`Aspose.Slides`](/slides/python-net)