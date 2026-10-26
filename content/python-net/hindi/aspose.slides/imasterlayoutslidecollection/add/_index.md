---
title: add method
second_title: Aspose.Slides के लिए Python द्वारा .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/imasterlayoutslidecollection/add/
weight: 10
---
## add(self, layout_type, layout_name) {#slidelayouttype-str}
एक नई लेआउट स्लाइड को संग्रह के अंत में जोड़ता है।

### रिटर्न
जोड़ी गई स्लाइड।


```python
def add(self, layout_type, layout_name):
    ...
```


| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| layout_type | [`SlideLayoutType`](/slides/python-net/hi/aspose.slides/slidelayouttype) | नई लेआउट के लिए लेआउट प्रकार।<br/><br/>            समर्थित लेआउट प्रकार: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom.<br/><br/>            अन्य लेआउट प्रकार अभी समर्थित नहीं हैं: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layout_name | **str** | नई लेआउट का नाम। यदि दिया गया नाम पहले से उपयोग में है तो ArgumentException फेंका जाएगा।<br/><br/>            यदि None पैरामीटर पास किया जाता है तो नाम स्वचालित रूप से पास किए गए लेआउट प्रकार के अनुसार उत्पन्न किया जाता है <br/><br/>            (उदाहरण के लिए "Title Slide" या "1_Title Slide", "2_..", आदि)। |

### टिप्पणी
1) `layout_type` के मान SlideLayoutType.Custom के लिए जोड़ी गई लेआउट में कोई प्लेसहोल्डर और कोई आकार नहीं होते हैं।  
2) इस विधि का समतुल्य  
method **Aspose.Slides.IGlobalLayoutSlideCollection.Add(Aspose.Slides.IMasterSlide,Aspose.Slides.SlideLayoutType,Syste**  
[`IPresentation.layout_slides`](/slides/python-net/hi/aspose.slides/ipresentation/layout_slides) प्रॉपर्टी के साथ एक्सेस किया जाता है।

### अपवाद
| अपवाद | विवरण |
| :- | :- |
| **RuntimeError(Proxy error(NotImplementedException))** | यदि पैरामीटर `layout_type` का असहायक मान पास किया जाता है तो यह फेंका जाता है। अब समर्थित नहीं लेआउट प्रकार: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| **RuntimeError(Proxy error(ArgumentException))** | यदि लेआउट नाम `layout_name` पहले से ही इस लेआउट संग्रह में उपयोग में है तो यह फेंका जाता है। |

### संबंधित
* क्लास [`ILayoutSlide`](/slides/python-net/hi/aspose.slides/ilayoutslide)
* क्लास [`IMasterLayoutSlideCollection`](/slides/python-net/hi/aspose.slides/imasterlayoutslidecollection)
* एन्यूमरेशन [`SlideLayoutType`](/slides/python-net/hi/aspose.slides/slidelayouttype)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)