---
title: get_visual_bounds method
second_title: Aspose.Slides for Python द्वारा .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/pictureframe/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
आकार की दृश्य सीमाओं को उसके रेंडर किए गए सामग्री से गणना करके प्राप्त करता है।

### रिटर्न मान

एक [`RectangleF`](/slides/python-net/hi/aspose.slides/rectanglef) जो स्लाइड निर्देशांक में आकार की दृश्य सीमाओं का प्रतिनिधित्व करता है
             in slide coordinates.



```python
def get_visual_bounds(self):
    ...
```


### टिप्पणी
वापसी आयत सभी सामग्री की अक्ष-संरेखित सीमाओं का प्रतिनिधित्व करता है
             produced by the shape during rendering in slide coordinate space.
            
             ये सीमाएँ आकार के मॉडल सीमाओं से भिन्न हो सकती हैं
             ([`Shape.x`](/slides/python-net/hi/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/hi/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/hi/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/hi/aspose.slides/shape/height))
             और यदि रेंडर की गई सामग्री विस्तारित हो तो नकारात्मक निर्देशांक शामिल हो सकते हैं
             स्लाइड मूल बिंदु से परे.
            
             दृश्य सीमाएँ रेंडरिंग-संबंधित पहलुओं को ध्यान में रखती हैं जैसे
             रूपांतरण (उदाहरण के लिए, घूर्णन), स्ट्रोक की चौड़ाई और जॉइन,
             टेक्स्ट लेआउट और ओवरफ़्लो, SmartArt ज्यामिति, और अन्य लेआउट प्रभाव
             जो आकार की अंतिम रेंडर की गई उपस्थिति को प्रभावित करते हैं.
            
             वापसी सीमाओं को स्लाइड आयत तक सीमित नहीं किया गया है.



### देखें
* क्लास [`PictureFrame`](/slides/python-net/hi/aspose.slides/pictureframe)
* क्लास [`RectangleF`](/slides/python-net/hi/aspose.slides/rectanglef)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)