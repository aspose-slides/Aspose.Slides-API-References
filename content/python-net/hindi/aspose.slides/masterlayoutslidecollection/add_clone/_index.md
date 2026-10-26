---
title: add_clone method
second_title: Aspose.Slides Python के लिए .NET API Reference के द्वारा
description: 
type: docs
url: /hi/aspose.slides/masterlayoutslidecollection/add_clone/
weight: 20
---
## add_clone(self, source_layout) {#ilayoutslide}
निर्दिष्ट लेआउट स्लाइड की एक प्रति संग्रह के अंत में जोड़ता है।

### रिटर्न
जोड़ दी गई स्लाइड।

```python
def add_clone(self, source_layout):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| source_layout | [`ILayoutSlide`](/slides/python-net/hi/aspose.slides/ilayoutslide) | क्लोन करने के लिए स्लाइड। |

### टिप्पणी
1) नया लेआउट इस लेआउट स्लाइड संग्रह के लिए पैरेंट मास्टर स्लाइड के साथ जुड़ा रहेगा।  
   इसलिए यह PowerPoint में "Use Destination Theme" विकल्प के साथ कॉपी/पेस्ट का समतुल्य है।  
2) इस मेथड का समकक्ष मेथड **Aspose.Slides.IGlobalLayoutSlideCollection.AddClone(Aspose.Slides.ILayoutSlide,Aspose.Slide** है, जिसे [`IPresentation.layout_slides`](/slides/python-net/hi/aspose.slides/ipresentation/layout_slides) प्रॉपर्टी के साथ एक्सेस किया जाता है।

### देखें
* क्लास [`ILayoutSlide`](/slides/python-net/hi/aspose.slides/ilayoutslide)
* क्लास [`MasterLayoutSlideCollection`](/slides/python-net/hi/aspose.slides/masterlayoutslidecollection)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)