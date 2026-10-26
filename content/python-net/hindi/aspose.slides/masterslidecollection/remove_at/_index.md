---
title: remove_at method
second_title: Aspose.Slides Python के लिए .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/masterslidecollection/remove_at/
weight: 40
---
## remove_at(self, index) {#int}
संग्रह में निर्दिष्ट सूचकांक पर तत्व को हटाता है।

```python
def remove_at(self, index):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| index | **int** | हटाने वाले तत्व का शून्य-आधारित सूचकांक। |

### टिप्पणी

PptxEditException के फेंके जाने से बचने के लिए, पहले मास्टर की HasDependingSlides प्रॉपर्टी को जाँचें।

### अपवाद

| अपवाद | विवरण |
| :- | :- |
| [`PptxEditException`](/slides/python-net/hi/aspose.slides/pptxeditexception) | यदि हटाने वाला मास्टर प्रस्तुति में उपयोग हो रहा है (उसकी HasDependingSlides प्रॉपर्टी सत्य है) तो फेंका जाता है। |

### और देखें
* क्लास [`MasterSlideCollection`](/slides/python-net/hi/aspose.slides/masterslidecollection)
* क्लास [`PptxEditException`](/slides/python-net/hi/aspose.slides/pptxeditexception)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)