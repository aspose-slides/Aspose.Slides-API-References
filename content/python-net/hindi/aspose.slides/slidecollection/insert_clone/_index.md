---
title: insert_clone method
second_title: Aspose.Slides for Python via .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/slidecollection/insert_clone/
weight: 60
---
## insert_clone(self, index, source_slide) {#int-islide}
निर्दिष्ट स्लाइड की एक प्रतिलिपि को संग्रह के निर्दिष्ट स्थान पर सम्मिलित करता है।

### Returns

डाली गई स्लाइड.



```python
def insert_clone(self, index, source_slide):
    ...
```


| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| index | **int** | नई स्लाइड का इंडेक्स। |
| source_slide | [`ISlide`](/slides/python-net/hi/aspose.slides/islide) | क्लोन करने के लिए स्लाइड। |

### Remarks

जब विभिन्न प्रस्तुतियों के बीच स्लाइड को क्लोन किया जाता है तो स्लाइड का मास्टर भी क्लोन हो सकता है।
            आंतरिक रजिस्ट्री का उपयोग स्वचालित रूप से क्लोन किए गए मास्टर को ट्रैक करने के लिए किया जाता है ताकि समान मास्टर स्लाइड के कई क्लोन बनने से बचा जा सके।
            मास्टर स्लाइडों का मैनुअल क्लोनिंग न तो रोका जाएगा न ही रजिस्टर्ड किया जाएगा।
            यदि आपको क्लोनिंग प्रक्रिया पर अधिक नियंत्रण चाहिए तो उपयोग करें
            **Aspose.Slides.SlideCollection.InsertClone(System.Int32,Aspose.Slides.ISlide,Aspose.Slide** या
            **Aspose.Slides.SlideCollection.InsertClone(System.Int32,Aspose.Slides.ISlide,Aspose.Slides.IMasterSlide,Syste** स्लाइड क्लोन करने के लिए और
            **Aspose.Slides.IMasterSlideCollection.AddClone(Aspose.Slide** मास्टर क्लोन करने के लिए।



## insert_clone(self, index, source_slide, dest_layout) {#int-islide-ilayoutslide}
निर्दिष्ट स्लाइड की एक प्रतिलिपि को संग्रह के निर्दिष्ट स्थान पर सम्मिलित करता है।

### Returns

डाली गई स्लाइड.



```python
def insert_clone(self, index, source_slide, dest_layout):
    ...
```


| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| index | **int** | नई स्लाइड का इंडेक्स। |
| source_slide | [`ISlide`](/slides/python-net/hi/aspose.slides/islide) | क्लोन करने के लिए स्लाइड। |
| dest_layout | [`ILayoutSlide`](/slides/python-net/hi/aspose.slides/ilayoutslide) | नई स्लाइड के लिए लेआउट स्लाइड। |


## insert_clone(self, index, source_slide, dest_master, allow_clone_missing_layout) {#int-islide-imasterslide-bool}
निर्दिष्ट स्रोत स्लाइड की एक प्रतिलिपि को संग्रह के निर्दिष्ट स्थान पर सम्मिलित करता है।
            उपयुक्त लेआउट स्वचालित रूप से निर्दिष्ट 
            मास्टर से चुना जाएगा (उपयुक्त लेआउट वह लेआउट है जिसका Type या Name स्रोत स्लाइड के लेआउट के समान हो)।
            यदि कोई उपयुक्त लेआउट नहीं है तो
            स्रोत स्लाइड का लेआउट क्लोन किया जाएगा (यदि allowCloneMissingLayout 
            true है) या PptxEditException उत्पन्न किया जाएगा (यदि allowCloneMissingLayout
            false है)।

### Returns

डाली गई स्लाइड.



```python
def insert_clone(self, index, source_slide, dest_master, allow_clone_missing_layout):
    ...
```


| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| index | **int** | नई स्लाइड का इंडेक्स। |
| source_slide | [`ISlide`](/slides/python-net/hi/aspose.slides/islide) | क्लोन करने के लिए स्लाइड। |
| dest_master | [`IMasterSlide`](/slides/python-net/hi/aspose.slides/imasterslide) | नई स्लाइड के लिए मास्टर स्लाइड। |
| allow_clone_missing_layout | **bool** | यदि निर्दिष्ट मास्टर में कोई उपयुक्त लेआउट नहीं है तो स्रोत स्लाइड का लेआउट क्लोन किया जाएगा (यदि allowCloneMissingLayout true है) या <br/><br/>            PptxEditException उत्पन्न किया जाएगा (यदि allowCloneMissingLayout false है)। |

### Exceptions

| अपवाद | विवरण |
| :- | :- |
| [`PptxEditException`](/slides/python-net/hi/aspose.slides/pptxeditexception) | यदि निर्दिष्ट मास्टर में कोई उपयुक्त लेआउट नहीं है और <br/>            allowCloneMissingLayout false है तो उत्पन्न किया जाता है। |



### See Also
* क्लास [`ILayoutSlide`](/slides/python-net/hi/aspose.slides/ilayoutslide)
* क्लास [`IMasterSlide`](/slides/python-net/hi/aspose.slides/imasterslide)
* क्लास [`ISlide`](/slides/python-net/hi/aspose.slides/islide)
* क्लास [`PptxEditException`](/slides/python-net/hi/aspose.slides/pptxeditexception)
* क्लास [`SlideCollection`](/slides/python-net/hi/aspose.slides/slidecollection)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)