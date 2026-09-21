---
title: insert_clone method
second_title: Aspose.Slides के लिए Python के माध्यम से .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/imasterlayoutslidecollection/insert_clone/
weight: 50
---
## insert_clone(self, index, source_layout) {#int-ilayoutslide}
संग्रह में निर्दिष्ट स्थिति पर निर्दिष्ट लेआउट स्लाइड की एक प्रति सम्मिलित करता है।

### Returns
समाविष्ट स्लाइड।

```python
def insert_clone(self, index, source_layout):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| index | **int** | नई स्लाइड का अनुक्रमणिका। |
| source_layout | [`ILayoutSlide`](/slides/python-net/hi/aspose.slides/ilayoutslide) | क्लोन करने के लिए स्लाइड। |

### Remarks
नया लेआउट इस लेआउट स्लाइड्स संग्रह के पैरेंट मास्टर स्लाइड से जुड़ा होगा। इसलिए यह PowerPoint में "Use Destination Theme" विकल्प के साथ कॉपी/पेस्ट के समान है।

### See Also
* क्लास [`ILayoutSlide`](/slides/python-net/hi/aspose.slides/ilayoutslide)
* क्लास [`IMasterLayoutSlideCollection`](/slides/python-net/hi/aspose.slides/imasterlayoutslidecollection)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)