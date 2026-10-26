---
title: insert_clone method
second_title: Python के लिए Aspose.Slides .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/masterlayoutslidecollection/insert_clone/
weight: 50
---
## insert_clone(self, index, source_layout) {#int-ilayoutslide}
निर्दिष्ट लेआउट स्लाइड की एक प्रति को संग्रह के निर्दिष्ट स्थान पर सम्मिलित करता है।

### वापसी

डाली गई स्लाइड।

```python
def insert_clone(self, index, source_layout):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| index | **int** | नई स्लाइड का इंडेक्स। |
| source_layout | [`ILayoutSlide`](/slides/python-net/hi/aspose.slides/ilayoutslide) | क्लोन करने के लिए स्लाइड। |

### टिप्पणियाँ

नई लेआउट इस लेआउट स्लाइड्स संग्रह के लिए पैरेंट मास्टर स्लाइड के साथ लिंक किया जाएगा।  
इसलिए यह PowerPoint में "Use Destination Theme" विकल्प के साथ कॉपी/पेस्ट के समान है।

### संबंधित
* वर्ग [`ILayoutSlide`](/slides/python-net/hi/aspose.slides/ilayoutslide)
* वर्ग [`MasterLayoutSlideCollection`](/slides/python-net/hi/aspose.slides/masterlayoutslidecollection)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)