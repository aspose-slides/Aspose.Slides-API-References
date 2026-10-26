---
title: add method
second_title: Aspose.Slides for Python via .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/globallayoutslidecollection/add/
weight: 10
---
## add(self, master, layout_type, layout_name) {#imasterslide-slidelayouttype-str}
नए लेआउट स्लाइड को प्रस्तुति में जोड़ता है।

### रिटर्न
जोड़ी गई स्लाइड।

```python
def add(self, master, layout_type, layout_name):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| master | [`IMasterSlide`](/slides/python-net/hi/aspose.slides/imasterslide) | नए लेआउट के लिए मास्टर स्लाइड। |
| layout_type | [`SlideLayoutType`](/slides/python-net/hi/aspose.slides/slidelayouttype) | नए लेआउट के लिए लेआउट प्रकार।<br/><br/>समर्थित लेआउट प्रकार: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom.<br/><br/>अन्य लेआउट प्रकार अभी समर्थित नहीं हैं: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layout_name | **str** | नए लेआउट के लिए नाम। यदि दिया गया नाम पहले से उपयोग में है तो ArgumentException फेंका जायेगा।<br/><br/>यदि None पैरामीटर पास किया जाता है तो नाम स्वचालित रूप से पास किए गए लेआउट प्रकार के आधार पर उत्पन्न किया जाता है <br/><br/> (उदाहरण के लिये "Title Slide" या "1_Title Slide", "2_..", आदि)। |

### टिप्पणी
1) SlideLayoutType.Custom मान के लिए `layout_type` में जोड़ी गई लेआउट में कोई प्लेसहोल्डर और कोई आकृति नहीं होती है।  
2) इस मेथड का समरूप मेथड **Aspose.Slides.IMasterLayoutSlideCollection.Add(Aspose.Slides.SlideLayoutType,Syste** है, जो [`IMasterSlide.layout_slides`](/slides/python-net/hi/aspose.slides/imasterslide/layout_slides) प्रॉपर्टी के साथ पहुँचाया जाता है।

### अपवाद
| अपवाद | विवरण |
| :- | :- |
| **RuntimeError(Proxy error(NotImplementedException))** | `layout_type` पैरामीटर का असमर्थित मान पास किया जाये तो फेंका जाता है। अभी समर्थित नहीं लेआउट प्रकार: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| **RuntimeError(Proxy error(ArgumentNullException))** | `master` None है तो फेंका जाता है। |
| **RuntimeError(Proxy error(ArgumentException))** | `master` किसी अन्य प्रस्तुति से संबंधित है तो फेंका जाता है। |
| **RuntimeError(Proxy error(ArgumentException))** | यदि `layout_name` लेआउट नाम का मान `master` के लेआउट संग्रह में पहले से उपयोग में है तो फेंका जाता है। |

### देखें
* क्लास [`GlobalLayoutSlideCollection`](/slides/python-net/hi/aspose.slides/globallayoutslidecollection)
* क्लास [`ILayoutSlide`](/slides/python-net/hi/aspose.slides/ilayoutslide)
* क्लास [`IMasterSlide`](/slides/python-net/hi/aspose.slides/imasterslide)
* एनीमरेशन [`SlideLayoutType`](/slides/python-net/hi/aspose.slides/slidelayouttype)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)