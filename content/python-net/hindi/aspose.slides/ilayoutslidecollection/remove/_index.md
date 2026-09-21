---
title: remove method
second_title: Aspose.Slides for Python via .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/ilayoutslidecollection/remove/
weight: 20
---
## remove(self, value) {#ilayoutslide}
कलेक्शन से एक लेआउट को हटाता है।


```python
def remove(self, value):
    ...
```


| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| value | [`ILayoutSlide`](/slides/python-net/hi/aspose.slides/ilayoutslide) | कलेक्शन से हटाने के लिये लेआउट स्लाइड। |

### टिप्पणियाँ

1) PptxEditException के थ्रो होने से बचने के लिए, लेआउट की HasDependingSlides प्रॉपर्टी को पहले जांचें।
2) कोड को सरल बनाने के लिए आप [`ILayoutSlide.remove`](/slides/python-net/hi/aspose.slides/ilayoutslide/remove) मेथड का भी उपयोग कर सकते हैं।

### अपवाद

| अपवाद | विवरण |
| :- | :- |
| [`PptxEditException`](/slides/python-net/hi/aspose.slides/pptxeditexception) | अगर लेआउट प्रस्तुति में उपयोग किया गया हो (its HasDependingSlides प्रॉपर्टी true हो) तो थ्रो किया जाता है। |



### संबंधित देखें
* क्लास [`ILayoutSlide`](/slides/python-net/hi/aspose.slides/ilayoutslide)
* क्लास [`ILayoutSlideCollection`](/slides/python-net/hi/aspose.slides/ilayoutslidecollection)
* क्लास [`PptxEditException`](/slides/python-net/hi/aspose.slides/pptxeditexception)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)