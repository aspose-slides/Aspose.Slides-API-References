---
title: remove method
second_title: Aspose.Slides for Python के लिए .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/layoutslidecollection/remove/
weight: 20
---
## remove(self, value) {#ilayoutslide}
संग्रह से एक लेआउट हटाता है।

```python
def remove(self, value):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| value | [`ILayoutSlide`](/slides/python-net/hi/aspose.slides/ilayoutslide) | संग्रह से हटाने के लिए लेआउट स्लाइड। |

### टिप्पणियाँ

1) PptxEditException को फेंके जाने से बचाने के लिए लेआउट की HasDependingSlides प्रॉपर्टी की जाँच करें।  
2) कोड को सरल बनाने के लिए आप [`ILayoutSlide.remove`](/slides/python-net/hi/aspose.slides/ilayoutslide/remove) मेथड का भी उपयोग कर सकते हैं।

### अपवाद

| अपवाद | विवरण |
| :- | :- |
| [`PptxEditException`](/slides/python-net/hi/aspose.slides/pptxeditexception) | यदि लेआउट प्रस्तुति में उपयोग किया गया है (उसकी HasDependingSlides प्रॉपर्टी true है) तो फेंका जाता है। |

### देखें
* क्लास [`ILayoutSlide`](/slides/python-net/hi/aspose.slides/ilayoutslide)
* क्लास [`LayoutSlideCollection`](/slides/python-net/hi/aspose.slides/layoutslidecollection)
* क्लास [`PptxEditException`](/slides/python-net/hi/aspose.slides/pptxeditexception)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)