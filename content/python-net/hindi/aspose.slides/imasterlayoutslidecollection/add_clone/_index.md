---
title: add_clone method
second_title: Aspose.Slides for Python के माध्यम से .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/imasterlayoutslidecollection/add_clone/
weight: 20
---
## add_clone(self, source_layout) {#ilayoutslide}
निर्दिष्ट लेआउट स्लाइड की एक प्रति संग्रह के अंत में जोड़ता है।

### रिटर्न मान

जोडी गई स्लाइड।



```python
def add_clone(self, source_layout):
    ...
```


| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| source_layout | [`ILayoutSlide`](/slides/python-net/hi/aspose.slides/ilayoutslide) | क्लोन करने के लिए स्लाइड। |

### टिप्पणियाँ

1) नया लेआउट इस लेआउट स्लाइड्स संग्रह के लिए पैरेंट मास्टर स्लाइड के साथ लिंक किया जाएगा।  
   इसलिए यह PowerPoint में "Use Destination Theme" विकल्प के साथ कॉपी/पेस्ट के समान है।  
2) इस विधि के समान विधि है **Aspose.Slides.IGlobalLayoutSlideCollection.AddClone(Aspose.Slides.ILayoutSlide,Aspose.Slide** को [`IPresentation.layout_slides`](/slides/python-net/hi/aspose.slides/ipresentation/layout_slides) प्रॉपर्टी से एक्सेस किया जाता है।



### संबंधित देखें
* वर्ग [`ILayoutSlide`](/slides/python-net/hi/aspose.slides/ilayoutslide)
* वर्ग [`IMasterLayoutSlideCollection`](/slides/python-net/hi/aspose.slides/imasterlayoutslidecollection)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)