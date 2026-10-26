---
title: insert_clone method
second_title: Aspose.Slides for Python के लिए .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/islidecollection/insert_clone/
weight: 60
---
## insert_clone(self, index, source_slide) {#int-islide}
एक निर्दिष्ट स्लाइड की प्रतिलिपि को संग्रह के निर्दिष्ट स्थान पर सम्मिलित करता है।

### Returns
समाविष्ट स्लाइड।

```python
def insert_clone(self, index, source_slide):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| index | **int** | नए स्लाइड का इंडेक्स। |
| source_slide | [`ISlide`](/slides/python-net/hi/aspose.slides/islide) | क्लोन करने के लिये स्लाइड। |

### Remarks
जब विभिन्न प्रस्तुतियों के बीच एक स्लाइड को क्लोन किया जाता है, तो स्लाइड का मास्टर भी क्लोन किया जा सकता है।  
आंतरिक रजिस्ट्री का उपयोग स्वचालित रूप से क्लोन किए गए मास्टर को ट्रैक करने के लिए किया जाता है ताकि समान मास्टर स्लाइड के कई क्लोन निर्माण को रोका जा सके।  
मास्टर स्लाइडों की मैन्युअल क्लोनिंग न तो रोकी जाएगी और न ही पंजीकृत होगी।  
यदि आपको क्लोनिंग प्रक्रिया पर अधिक नियंत्रण चाहिए तो उपयोग करें  
**Aspose.Slides.ISlideCollection.InsertClone(System.Int32,Aspose.Slides.ISlide,Aspose.Slide** या  
**Aspose.Slides.ISlideCollection.InsertClone(System.Int32,Aspose.Slides.ISlide,Aspose.Slides.IMasterSlide,Syste** स्लाइड्स को क्लोन करने के लिये और  
**Aspose.Slides.IMasterSlideCollection.AddClone(Aspose.Slide** मास्टर को क्लोन करने के लिये।

## insert_clone(self, index, source_slide, dest_layout) {#int-islide-ilayoutslide}
एक निर्दिष्ट स्लाइड की प्रतिलिपि को संग्रह के निर्दिष्ट स्थान पर सम्मिलित करता है।

### Returns
समाविष्ट स्लाइड।

```python
def insert_clone(self, index, source_slide, dest_layout):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| index | **int** | नए स्लाइड का इंडेक्स। |
| source_slide | [`ISlide`](/slides/python-net/hi/aspose.slides/islide) | क्लोन करने के लिये स्लाइड। |
| dest_layout | [`ILayoutSlide`](/slides/python-net/hi/aspose.slides/ilayoutslide) | नए स्लाइड के लिये लेआउट स्लाइड। |

## insert_clone(self, index, source_slide, dest_master, allow_clone_missing_layout) {#int-islide-imasterslide-bool}
एक निर्दिष्ट स्रोत स्लाइड की प्रतिलिपि को संग्रह के निर्दिष्ट स्थान पर सम्मिलित करता है।  
उपयुक्त लेआउट निर्दिष्ट मास्टर से स्वचालित रूप से चुना जाएगा (उपयुक्त लेआउट वह लेआउट है जिसका प्रकार या नाम स्रोत स्लाइड के लेआउट के समान है)। यदि उपयुक्त लेआउट नहीं है तो स्रोत स्लाइड का लेआउट क्लोन किया जाएगा (यदि allowCloneMissingLayout सत्य है) या PptxEditException फेंका जाएगा (यदि allowCloneMissingLayout असत्य है)।

### Returns
समाविष्ट स्लाइड।

```python
def insert_clone(self, index, source_slide, dest_master, allow_clone_missing_layout):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| index | **int** | नए स्लाइड का इंडेक्स। |
| source_slide | [`ISlide`](/slides/python-net/hi/aspose.slides/islide) | क्लोन करने के लिये स्लाइड। |
| dest_master | [`IMasterSlide`](/slides/python-net/hi/aspose.slides/imasterslide) | नए स्लाइड के लिये मास्टर स्लाइड। |
| allow_clone_missing_layout | **bool** | यदि निर्दिष्ट मास्टर में कोई उपयुक्त लेआउट नहीं है तो लेआउट <br/><br/>            स्रोत स्लाइड का क्लोन किया जाएगा (यदि allowCloneMissingLayout सत्य है) या <br/><br/>            PptxEditException फेंका जाएगा (यदि allowCloneMissingLayout असत्य है)। |

### Exceptions

| अपवाद | विवरण |
| :- | :- |
| [`PptxEditException`](/slides/python-net/hi/aspose.slides/pptxeditexception) | यदि निर्दिष्ट मास्टर में कोई उपयुक्त लेआउट नहीं है और <br/>            allowCloneMissingLayout असत्य है तो फेंका जाता है। |

### See Also
* क्लास [`ILayoutSlide`](/slides/python-net/hi/aspose.slides/ilayoutslide)
* क्लास [`IMasterSlide`](/slides/python-net/hi/aspose.slides/imasterslide)
* क्लास [`ISlide`](/slides/python-net/hi/aspose.slides/islide)
* क्लास [`ISlideCollection`](/slides/python-net/hi/aspose.slides/islidecollection)
* क्लास [`PptxEditException`](/slides/python-net/hi/aspose.slides/pptxeditexception)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)