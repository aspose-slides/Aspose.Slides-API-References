---
title: remove method
second_title: Aspose.Slides Python के लिए via .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/layoutslide/remove/
weight: 60
---
## remove(self) {#}
प्रस्तुति से लेआउट को हटाता है।


```python
def remove(self):
    ...
```


### टिप्पणी

PptxEditException को फेंके जाने से बचने के लिए, लेआउट की HasDependingSlides प्रॉपर्टी को पहले जांचें।

### अपवाद

| अपवाद | विवरण |
| :- | :- |
| [`PptxEditException`](/slides/python-net/hi/aspose.slides/pptxeditexception) | यदि लेआउट पहले से ही प्रस्तुति से हटा दिया गया है या यदि लेआउट प्रस्तुति में उपयोग किया गया है (उसकी HasDependingSlides प्रॉपर्टी true है) तो फेंका जाता है। |



### संबंधित देखें
* क्लास [`LayoutSlide`](/slides/python-net/hi/aspose.slides/layoutslide)
* क्लास [`PptxEditException`](/slides/python-net/hi/aspose.slides/pptxeditexception)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)