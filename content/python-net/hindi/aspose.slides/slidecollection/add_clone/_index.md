---
title: add_clone method
second_title: Aspose.Slides for Python via .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/slidecollection/add_clone/
weight: 10
---
## add_clone(self, source_slide) {#islide}
एक निर्दिष्ट स्लाइड की प्रति संग्रह के अंत में जोड़ता है।

### Returns
नई स्लाइड।



```python
def add_clone(self, source_slide):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| source_slide | [`ISlide`](/slides/python-net/hi/aspose.slides/islide) | क्लोन करने के लिए स्लाइड। |

### टिप्पणियाँ
जब विभिन्न प्रस्तुतियों के बीच स्लाइड को क्लोन किया जाता है तो स्लाइड का मास्टर भी क्लोन किया जा सकता है।  
आंतरिक रजिस्ट्री का उपयोग स्वचालित रूप से क्लोन किए गए मास्टरों को ट्रैक करने के लिए किया जाता है ताकि समान मास्टर स्लाइड के कई क्लोन बनें नहीं।  
मास्टर स्लाइडों का मैन्युअल क्लोनिंग न तो रोका जाएगा न ही रजिस्टर्ड होगा।  
यदि आपको क्लोनिंग प्रक्रिया पर अधिक नियंत्रण चाहिए तो उपयोग करें  
**Aspose.Slides.SlideCollection.AddClone(Aspose.Slides.ISlide,Aspose.Slide** या  
**Aspose.Slides.SlideCollection.AddClone(Aspose.Slides.ISlide,Aspose.Slides.IMasterSlide,Syste** स्लाइडों को क्लोन करने के लिए,  
**Aspose.Slides.IGlobalLayoutSlideCollection.AddClone(Aspose.Slide** या  
**Aspose.Slides.IGlobalLayoutSlideCollection.AddClone(Aspose.Slides.ILayoutSlide,Aspose.Slide** लेआउट को क्लोन करने के लिए और  
**Aspose.Slides.IMasterSlideCollection.AddClone(Aspose.Slide** मास्टर को क्लोन करने के लिए।


## add_clone(self, source_slide, section) {#islide-isection}
एक निर्दिष्ट स्लाइड की प्रति निर्दिष्ट सेक्शन के अंत में जोड़ता है।

### Returns
नई स्लाइड।



```python
def add_clone(self, source_slide, section):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| source_slide | [`ISlide`](/slides/python-net/hi/aspose.slides/islide) | क्लोन करने के लिए स्लाइड। |
| section | [`ISection`](/slides/python-net/hi/aspose.slides/isection) | नई स्लाइड के लिए सेक्शन। |

### Exceptions

| Exception | विवरण |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** |  |
| [`PptxEditException`](/slides/python-net/hi/aspose.slides/pptxeditexception) |  |


## add_clone(self, source_slide, dest_layout) {#islide-ilayoutslide}
एक निर्दिष्ट स्लाइड की प्रति संग्रह के अंत में जोड़ता है।

### Returns
नई स्लाइड।



```python
def add_clone(self, source_slide, dest_layout):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| source_slide | [`ISlide`](/slides/python-net/hi/aspose.slides/islide) | क्लोन करने के लिए स्लाइड। |
| dest_layout | [`ILayoutSlide`](/slides/python-net/hi/aspose.slides/ilayoutslide) | नई स्लाइड के लिए लेआउट स्लाइड। |


## add_clone(self, source_slide, dest_master, allow_clone_missing_layout) {#islide-imasterslide-bool}
एक निर्दिष्ट स्रोत स्लाइड की प्रति संग्रह के अंत में जोड़ता है।  
उपयुक्त लेआउट स्वचालित रूप से निर्दिष्ट मास्टर से चुना जाएगा (उपयुक्त लेआउट वह लेआउट है जिसका Type या Name स्रोत स्लाइड के लेआउट के समान हो)। यदि उपयुक्त लेआउट नहीं मिलता तो स्रोत स्लाइड का लेआउट क्लोन किया जाएगा (यदि allowCloneMissingLayout true है) या PptxEditException फेंका जाएगा (यदि allowCloneMissingLayout false है)।

### Returns
नई स्लाइड।



```python
def add_clone(self, source_slide, dest_master, allow_clone_missing_layout):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| source_slide | [`ISlide`](/slides/python-net/hi/aspose.slides/islide) | क्लोन करने के लिए स्लाइड। |
| dest_master | [`IMasterSlide`](/slides/python-net/hi/aspose.slides/imasterslide) | नई स्लाइड के लिए मास्टर स्लाइड। |
| allow_clone_missing_layout | **bool** | यदि निर्दिष्ट मास्टर में उपयुक्त लेआउट नहीं है तो स्रोत स्लाइड का लेआउट क्लोन किया जाएगा (यदि allowCloneMissingLayout true है) या <br/><br/> PptxEditException फेंका जाएगा (यदि allowCloneMissingLayout false है)। |

### Exceptions

| Exception | विवरण |
| :- | :- |
| [`PptxEditException`](/slides/python-net/hi/aspose.slides/pptxeditexception) | यदि निर्दिष्ट मास्टर में उपयुक्त लेआउट नहीं है और <br/> allowCloneMissingLayout false है तो फेंका जाता है। |



### See Also
* क्लास [`ILayoutSlide`](/slides/python-net/hi/aspose.slides/ilayoutslide)
* क्लास [`IMasterSlide`](/slides/python-net/hi/aspose.slides/imasterslide)
* क्लास [`ISection`](/slides/python-net/hi/aspose.slides/isection)
* क्लास [`ISlide`](/slides/python-net/hi/aspose.slides/islide)
* क्लास [`PptxEditException`](/slides/python-net/hi/aspose.slides/pptxeditexception)
* क्लास [`SlideCollection`](/slides/python-net/hi/aspose.slides/slidecollection)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)