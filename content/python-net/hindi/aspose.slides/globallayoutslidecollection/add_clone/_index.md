---
title: add_clone method
second_title: Aspose.Slides for Python द्वारा .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/globallayoutslidecollection/add_clone/
weight: 20
---
## add_clone(self, source_layout) {#ilayoutslide}
उक्त निर्दिष्ट लेआउट स्लाइड की एक प्रति प्रस्तुति में जोड़ता है।

### परिणाम

जोड़ी गई स्लाइड।



```python
def add_clone(self, source_layout):
    ...
```


| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| source_layout | [`ILayoutSlide`](/slides/python-net/hi/aspose.slides/ilayoutslide) | क्लोन करने के लिये स्लाइड। |

### टिप्पणी

जब विभिन्न प्रस्तुतियों के बीच लेआउट को क्लोन किया जाता है, तो लेआउट का मास्टर भी क्लोन किया जा सकता है
            ताकि स्रोत स्वरूपण बना रहे।
            आंतरिक रजिस्ट्री का उपयोग स्वचालित रूप से क्लोन किए गए मास्टरों को ट्रैक करने के लिए किया जाता है ताकि निर्माण को रोका जा सके 
            एक ही मास्टर स्लाइड के कई क्लोन बनना।
            मास्टर स्लाइडों का मैनुअल क्लोनिंग न तो रोका जाएगा न ही पंजीकृत किया जाएगा।


## add_clone(self, source_layout, dest_master) {#ilayoutslide-imasterslide}
उक्त निर्दिष्ट लेआउट स्लाइड की एक प्रति प्रस्तुति में जोड़ता है।

### परिणाम

जोड़ी गई स्लाइड।



```python
def add_clone(self, source_layout, dest_master):
    ...
```


| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| source_layout | [`ILayoutSlide`](/slides/python-net/hi/aspose.slides/ilayoutslide) | क्लोन करने के लिये स्लाइड। |
| dest_master | [`IMasterSlide`](/slides/python-net/hi/aspose.slides/imasterslide) | नए लेआउट के लिये मास्टर स्लाइड। |

### टिप्पणी

1) नया लेआउट गंतव्य प्रस्तुति में परिभाषित मास्टर से जुड़ा होगा।
            इसलिए यह PowerPoint में "Use Destination Theme" विकल्प के साथ कॉपी/पेस्ट के समान है।
            2) इस विधि का समकक्ष विधि **Aspose.Slides.IMasterLayoutSlideCollection.AddClone(Aspose.Slide** है,
            जिसे [`IMasterSlide.layout_slides`](/slides/python-net/hi/aspose.slides/imasterslide/layout_slides) प्रॉपर्टी द्वारा एक्सेस किया जाता है।



### देखें
* क्लास [`GlobalLayoutSlideCollection`](/slides/python-net/hi/aspose.slides/globallayoutslidecollection)
* क्लास [`ILayoutSlide`](/slides/python-net/hi/aspose.slides/ilayoutslide)
* क्लास [`IMasterSlide`](/slides/python-net/hi/aspose.slides/imasterslide)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)