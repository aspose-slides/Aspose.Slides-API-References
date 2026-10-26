---
title: add_clone method
second_title: Aspose.Slides for Python via .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/igloballayoutslidecollection/add_clone/
weight: 20
---
## add_clone(self, source_layout) {#ilayoutslide}
प्रस्तुति में निर्दिष्ट लेआउट स्लाइड की एक प्रति जोड़ता है।

### Returns
जोड़ी गई स्लाइड।

```python
def add_clone(self, source_layout):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| source_layout | [`ILayoutSlide`](/slides/python-net/hi/aspose.slides/ilayoutslide) | क्लोन करने के लिए स्लाइड। |

### Remarks
जब विभिन्न प्रस्तुतियों के बीच लेआउट को क्लोन किया जाता है तो लेआउट का मास्टर भी स्रोत फ़ॉर्मेटिंग बनाए रखने के लिए क्लोन किया जा सकता है।  
आंतरिक रेजिस्ट्री का उपयोग स्वचालित रूप से क्लोन किए गए मास्टर को ट्रैक करने के लिए किया जाता है ताकि समान मास्टर स्लाइड के कई क्लोन बनाने से बचा जा सके।  
मैनुअल रूप से मास्टर स्लाइड्स को क्लोन करना न तो रोका जाएगा न ही रेजिस्टर किया जाएगा।

## add_clone(self, source_layout, dest_master) {#ilayoutslide-imasterslide}
प्रस्तुति में निर्दिष्ट लेआउट स्लाइड की एक प्रति जोड़ता है।

### Returns
जोड़ी गई स्लाइड।

```python
def add_clone(self, source_layout, dest_master):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| source_layout | [`ILayoutSlide`](/slides/python-net/hi/aspose.slides/ilayoutslide) | क्लोन करने के लिए स्लाइड। |
| dest_master | [`IMasterSlide`](/slides/python-net/hi/aspose.slides/imasterslide) | नए लेआउट के लिए मास्टर स्लाइड। |

### Remarks
नया लेआउट गंतव्य प्रस्तुति में परिभाषित मास्टर के साथ जुड़ जाएगा।  
इसलिए यह PowerPoint में "Use Destination Theme" विकल्प के साथ प्रतिलिपि/पेस्ट के समान है।

### See Also
* class [`IGlobalLayoutSlideCollection`](/slides/python-net/hi/aspose.slides/igloballayoutslidecollection)
* class [`ILayoutSlide`](/slides/python-net/hi/aspose.slides/ilayoutslide)
* class [`IMasterSlide`](/slides/python-net/hi/aspose.slides/imasterslide)
* module [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)