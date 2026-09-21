---
title: remove_at method
second_title: Aspose.Slides for Python via .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/masterlayoutslidecollection/remove_at/
weight: 70
---
## remove_at(self, index) {#int}
संग्रह में निर्दिष्ट अनुक्रमांक पर तत्व को हटाता है।

```python
def remove_at(self, index):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| index | **int** | हटाने वाले तत्व का शून्य-आधारित अनुक्रमांक। |

### टिप्पणियाँ

1) PptxEditException को फेंकने से बचने के लिए, पहले लेआउट की HasDependingSlides प्रॉपर्टी जाँचें।  
2) आप कोड को सरल बनाने के लिए [`ILayoutSlide.remove`](/slides/python-net/hi/aspose.slides/ilayoutslide/remove) मेथड का भी उपयोग कर सकते हैं।

### अपवाद

| अपवाद | विवरण |
| :- | :- |
| [`PptxEditException`](/slides/python-net/hi/aspose.slides/pptxeditexception) | यदि लेआउट प्रस्तुति में उपयोग किया गया है (उसकी HasDependingSlides प्रॉपर्टी true है) तो फेंका जाता है। |

### संदर्भ
* class [`MasterLayoutSlideCollection`](/slides/python-net/hi/aspose.slides/masterlayoutslidecollection)
* class [`PptxEditException`](/slides/python-net/hi/aspose.slides/pptxeditexception)
* module [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)