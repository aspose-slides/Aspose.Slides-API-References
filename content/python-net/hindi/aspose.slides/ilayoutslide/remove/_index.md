---
title: remove method
second_title: Aspose.Slides for Python के लिए .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/ilayoutslide/remove/
weight: 60
---
## remove(self) {#}
प्रस्तुति से लेआउट हटाता है.

```python
def remove(self):
    ...
```

### टिप्पणी
PptxEditException के उत्पन्न होने से बचने के लिए, पहले लेआउट की HasDependingSlides प्रॉपर्टी जांचें।

### अपवाद

| अपवाद | विवरण |
| :- | :- |
| [`PptxEditException`](/slides/python-net/hi/aspose.slides/pptxeditexception) | यदि लेआउट पहले ही प्रस्तुति से हटाया गया है या यदि लेआउट प्रस्तुति में उपयोग किया गया है (उसकी <br/>            HasDependingSlides प्रॉपर्टी true है) तो फेंका जाता है। |

### देखें
* क्लास [`ILayoutSlide`](/slides/python-net/hi/aspose.slides/ilayoutslide)
* क्लास [`PptxEditException`](/slides/python-net/hi/aspose.slides/pptxeditexception)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)