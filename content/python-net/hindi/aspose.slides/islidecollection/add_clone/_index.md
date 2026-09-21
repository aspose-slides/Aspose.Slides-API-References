---
title: add_clone method
second_title: Aspose.Slides for Python via .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/islidecollection/add_clone/
weight: 10
---
## add_clone(self, source_slide) {#islide}
निर्दिष्ट slide की एक प्रति संग्रह के अंत में जोड़ता है।

### रिटर्न

नई slide.



```python
def add_clone(self, source_slide):
    ...
```


| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| source_slide | [`ISlide`](/slides/python-net/hi/aspose.slides/islide) | Slide को क्लोन करने के लिए। |

### टिप्पणी

जब विभिन्न प्रस्तुतियों के बीच एक slide को क्लोन किया जाता है, तो slide के master को भी क्लोन किया जा सकता है।  
आंतरिक रजिस्ट्री का उपयोग स्वचालित रूप से क्लोन किए गए masters को ट्रैक करने के लिए किया जाता है ताकि एक ही master slide के कई क्लोन बनने से रोका जा सके।  
मैनुअल क्लोनिंग of master slides न तो रोकी जाएगी और न ही रजिस्टर्ड की जाएगी।  
यदि आपको क्लोनिंग प्रक्रिया पर अधिक नियंत्रण चाहिए तो उपयोग करें  
**Aspose.Slides.ISlideCollection.AddClone(Aspose.Slides.ISlide,Aspose.Slide** या  
**Aspose.Slides.ISlideCollection.AddClone(Aspose.Slides.ISlide,Aspose.Slides.IMasterSlide,Syste** for cloning slides,  
**Aspose.Slides.IGlobalLayoutSlideCollection.AddClone(Aspose.Slide** या  
**Aspose.Slides.IGlobalLayoutSlideCollection.AddClone(Aspose.Slides.ILayoutSlide,Aspose.Slide** for cloning layouts and  
**Aspose.Slides.IMasterSlideCollection.AddClone(Aspose.Slide** for cloning masters.



## add_clone(self, source_slide, section) {#islide-isection}
निर्दिष्ट slide की एक प्रति निर्दिष्ट सेक्शन के अंत में जोड़ता है।

### रिटर्न

नई slide.



```python
def add_clone(self, source_slide, section):
    ...
```


| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| source_slide | [`ISlide`](/slides/python-net/hi/aspose.slides/islide) | Slide को क्लोन करने के लिए। |
| section | [`ISection`](/slides/python-net/hi/aspose.slides/isection) | Section नई slide के लिए। |

### अपवाद

| अपवाद | विवरण |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** |  |
| [`PptxEditException`](/slides/python-net/hi/aspose.slides/pptxeditexception) |  |


## add_clone(self, source_slide, dest_layout) {#islide-ilayoutslide}
निर्दिष्ट slide की एक प्रति संग्रह के अंत में जोड़ता है।

### रिटर्न

नई slide.



```python
def add_clone(self, source_slide, dest_layout):
    ...
```


| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| source_slide | [`ISlide`](/slides/python-net/hi/aspose.slides/islide) | Slide को क्लोन करने के लिए। |
| dest_layout | [`ILayoutSlide`](/slides/python-net/hi/aspose.slides/ilayoutslide) | Layout slide नई slide के लिए। |


## add_clone(self, source_slide, dest_master, allow_clone_missing_layout) {#islide-imasterslide-bool}
निर्दिष्ट source slide की एक प्रति संग्रह के अंत में जोड़ता है।  
उपयुक्त layout स्वतः निर्दिष्ट master से चयनित किया जाएगा (उपयुक्त layout वह layout है जिसका Type या Name source slide के layout के समान है)। यदि कोई उपयुक्त layout नहीं है तो source slide का layout क्लोन किया जाएगा (यदि allowCloneMissingLayout true है) या PptxEditException फेंका जाएगा (यदि allowCloneMissingLayout false है)।

### रिटर्न

नई slide.



```python
def add_clone(self, source_slide, dest_master, allow_clone_missing_layout):
    ...
```


| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| source_slide | [`ISlide`](/slides/python-net/hi/aspose.slides/islide) | Slide को क्लोन करने के लिए। |
| dest_master | [`IMasterSlide`](/slides/python-net/hi/aspose.slides/imasterslide) | Master slide नई slide के लिए। |
| allow_clone_missing_layout | **bool** | यदि निर्दिष्ट master में कोई उपयुक्त layout नहीं है तो source slide का layout क्लोन किया जाएगा (यदि allowCloneMissingLayout true है) या <br/><br/> PptxEditException फेंका जाएगा (यदि allowCloneMissingLayout false है)। |

### अपवाद

| अपवाद | विवरण |
| :- | :- |
| [`PptxEditException`](/slides/python-net/hi/aspose.slides/pptxeditexception) | यदि निर्दिष्ट master में कोई उपयुक्त layout नहीं है और <br/> allowCloneMissingLayout false है तो फेंका जाता है। |



### देखें
* क्लास [`ILayoutSlide`](/slides/python-net/hi/aspose.slides/ilayoutslide)
* क्लास [`IMasterSlide`](/slides/python-net/hi/aspose.slides/imasterslide)
* क्लास [`ISection`](/slides/python-net/hi/aspose.slides/isection)
* क्लास [`ISlide`](/slides/python-net/hi/aspose.slides/islide)
* क्लास [`ISlideCollection`](/slides/python-net/hi/aspose.slides/islidecollection)
* क्लास [`PptxEditException`](/slides/python-net/hi/aspose.slides/pptxeditexception)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)