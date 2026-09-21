---
title: remove_at method
second_title: Aspose.Slides for Python के माध्यम से .NET API रेफ़रेंस
description: 
type: docs
url: /hi/aspose.slides/imasterlayoutslidecollection/remove_at/
weight: 70
---
## remove_at(self, index) {#int}
संग्रह में निर्दिष्ट इंडेक्स पर स्थित तत्व को हटाता है।


```python
def remove_at(self, index):
    ...
```


| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| index | **int** | हटाने वाले तत्व का शून्य-आधारित इंडेक्स। |

### टिप्पणियां

1) PptxEditException के फेंके जाने से बचने हेतु, पहले लेआउट की HasDependingSlides प्रॉपर्टी जाँचें।  
2) आप कोड को सरल बनाने के लिए [`ILayoutSlide.remove`](/slides/python-net/hi/aspose.slides/ilayoutslide/remove) मेथड का भी उपयोग कर सकते हैं।

### अपवाद

| अपवाद | विवरण |
| :- | :- |
| [`PptxEditException`](/slides/python-net/hi/aspose.slides/pptxeditexception) | यदि लेआउट प्रस्तुति में उपयोग हो रहा है (इसकी HasDependingSlides प्रॉपर्टी true है) तो यह फेंका जाता है। |



### संबंधित देखें
* वर्ग [`IMasterLayoutSlideCollection`](/slides/python-net/hi/aspose.slides/imasterlayoutslidecollection)
* वर्ग [`PptxEditException`](/slides/python-net/hi/aspose.slides/pptxeditexception)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)