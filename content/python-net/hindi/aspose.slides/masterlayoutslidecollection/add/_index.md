---
title: add method
second_title: Aspose.Slides Python के लिए .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/masterlayoutslidecollection/add/
weight: 10
---
## add(self, layout_type, layout_name) {#slidelayouttype-str}
एक नई लेआउट स्लाइड को संग्रह के अंत में जोड़ता है।

### Returns
जोड़ी गई स्लाइड।

```python
def add(self, layout_type, layout_name):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| layout_type | [`SlideLayoutType`](/slides/python-net/hi/aspose.slides/slidelayouttype) | नई लेआउट के लिए लेआउट प्रकार।<br/><br/>Supported layout types: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom.<br/><br/>Other layout types are not supported now: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layout_name | **str** | नई लेआउट का नाम। यदि दिया गया नाम पहले से उपयोग में है तो ArgumentException फेंका जाएगा।<br/><br/>यदि None पैरामीटर पास किया जाता है तो पास किए गए लेआउट प्रकार के अनुसार नाम स्वतः उत्पन्न किया जाता है (उदाहरण के लिये "Title Slide" या "1_Title Slide", "2_..", आदि)। |

### Remarks
1) `layout_type` के SlideLayoutType.Custom मान के लिए जोड़ा गया लेआउट कोई प्लेसहोल्डर और कोई शेप नहीं रखता।  
2) इस मेथड का समतुल्य है मेथड **Aspose.Slides.IGlobalLayoutSlideCollection.Add(Aspose.Slides.IMasterSlide,Aspose.Slides.SlideLayoutType,Syste** जिसे [`IPresentation.layout_slides`](/slides/python-net/hi/aspose.slides/ipresentation/layout_slides) प्रॉपर्टी के साथ एक्सेस किया जाता है।

### Exceptions
| अपवाद | विवरण |
| :- | :- |
| **RuntimeError(Proxy error(NotImplementedException))** | यदि `layout_type` पैरामीटर के लिए असमर्थित मान पास किया जाता है तो फेंका जाता है। अभी असमर्थित लेआउट प्रकार: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| **RuntimeError(Proxy error(ArgumentException))** | यदि लेआउट नाम `layout_name` इस संग्रह में पहले से उपयोग में है तो फेंका जाता है। |

### See Also
* क्लास [`ILayoutSlide`](/slides/python-net/hi/aspose.slides/ilayoutslide)
* क्लास [`MasterLayoutSlideCollection`](/slides/python-net/hi/aspose.slides/masterlayoutslidecollection)
* enumeration [`SlideLayoutType`](/slides/python-net/hi/aspose.slides/slidelayouttype)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)