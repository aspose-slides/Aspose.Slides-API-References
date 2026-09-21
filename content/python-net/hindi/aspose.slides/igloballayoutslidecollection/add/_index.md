---
title: add method
second_title: Aspose.Slides Python के लिए .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/igloballayoutslidecollection/add/
weight: 10
---
## add(self, master, layout_type, layout_name) {#imasterslide-slidelayouttype-str}
प्रेजेंटेशन में एक नया लेआउट स्लाइड जोड़ता है।

### Returns

जोड़ी गई स्लाइड।



```python
def add(self, master, layout_type, layout_name):
    ...
```


| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| master | [`IMasterSlide`](/slides/python-net/hi/aspose.slides/imasterslide) | नए लेआउट के लिए मास्टर स्लाइड। |
| layout_type | [`SlideLayoutType`](/slides/python-net/hi/aspose.slides/slidelayouttype) | नए लेआउट के लिए लेआउट प्रकार।<br/><br/>            Supported layout types: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom.<br/><br/>            Other layout types are not supported now: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layout_name | **str** | नए लेआउट के लिए नाम। यदि दिया गया नाम पहले से उपयोग में है तो ArgumentException फेंका जाएगा।<br/><br/>            यदि None पैरामीटर पास किया जाता है तो नाम स्वचालित रूप से पास किए गए लेआउट प्रकार के अनुसार उत्पन्न किया जाएगा (उदाहरण के लिए "Title Slide" या "1_Title Slide", "2_..", आदि)। |

### Remarks

1) `layout_type` के SlideLayoutType.Custom मान के लिए जोड़ा गया लेआउट किसी भी प्लेसहोल्डर और किसी भी आकार को शामिल नहीं करता है।  
2) इस विधि का समानार्थी विधि **Aspose.Slides.IMasterLayoutSlideCollection.Add(Aspose.Slides.SlideLayoutType,Syste** है, जिसे [`IMasterSlide.layout_slides`](/slides/python-net/hi/aspose.slides/imasterslide/layout_slides) प्रॉपर्टी के साथ एक्सेस किया जाता है।

### Exceptions

| अपवाद | विवरण |
| :- | :- |
| **RuntimeError(Proxy error(NotImplementedException))** | यदि पैरामीटर `layout_type` का असमर्थित मान पास किया जाता है तो यह फेंका जाता है। वर्तमान में समर्थित नहीं होने वाले लेआउट प्रकार: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| **RuntimeError(Proxy error(ArgumentNullException))** | यदि `master` None है तो यह फेंका जाता है। |
| **RuntimeError(Proxy error(ArgumentException))** | यदि `master` किसी अन्य प्रस्तुति से संबंधित है तो यह फेंका जाता है। |
| **RuntimeError(Proxy error(ArgumentException))** | यदि `layout_name` मान `master` के लेआउट संग्रह में पहले से उपयोग में है तो यह फेंका जाता है। |



### See Also
* क्लास [`IGlobalLayoutSlideCollection`](/slides/python-net/hi/aspose.slides/igloballayoutslidecollection)
* क्लास [`ILayoutSlide`](/slides/python-net/hi/aspose.slides/ilayoutslide)
* क्लास [`IMasterSlide`](/slides/python-net/hi/aspose.slides/imasterslide)
* एन्यूमरेशन [`SlideLayoutType`](/slides/python-net/hi/aspose.slides/slidelayouttype)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)