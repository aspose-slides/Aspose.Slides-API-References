---
title: insert method
second_title: Aspose.Slides for Python के माध्यम से .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/masterlayoutslidecollection/insert/
weight: 40
---
## insert(self, index, layout_type, layout_name) {#int-slidelayouttype-str}
संग्रह में निर्दिष्ट स्थान पर एक नई लेआउट स्लाइड डालता है।

### रिटर्न

डाली गई स्लाइड।

```python
def insert(self, index, layout_type, layout_name):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| index | **int** | नई स्लाइड का इंडेक्स। |
| layout_type | [`SlideLayoutType`](/slides/python-net/hi/aspose.slides/slidelayouttype) | नई लेआउट के लिए लेआउट प्रकार।<br/><br/>            Supported layout types: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom.<br/><br/>            Other layout types are not supported now: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layout_name | **str** | नई लेआउट के लिए नाम। यदि दिया गया नाम पहले से उपयोग में है तो ArgumentException फेंका जाएगा।<br/><br/>            यदि None पैरामीटर पास किया जाता है तो पास किए गए लेआउट प्रकार के अनुसार नाम स्वतः उत्पन्न किया जाता है <br/><br/>            (उदाहरण के लिए "Title Slide" या "1_Title Slide", "2_..", आदि)। |

### टिप्पणियां

SlideLayoutType.Custom मान के लिए डाली गई लेआउट `layout_type` में कोई प्लेसहोल्डर और कोई आकृति नहीं है।

### अपवाद

| अपवाद | विवरण |
| :- | :- |
| **RuntimeError(Proxy error(NotImplementedException))** | यदि पैरामीटर `layout_type` का असमर्थित मान पास किया जाता है तो फेंका जाता है। वर्तमान में समर्थित नहीं वाले लेआउट प्रकार: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| **RuntimeError(Proxy error(ArgumentException))** | यदि लेआउट नाम `layout_name` इस लेआउट संग्रह में पहले से उपयोग में है तो फेंका जाता है। |

### देखें
* क्लास [`ILayoutSlide`](/slides/python-net/hi/aspose.slides/ilayoutslide)
* क्लास [`MasterLayoutSlideCollection`](/slides/python-net/hi/aspose.slides/masterlayoutslidecollection)
* enumeration [`SlideLayoutType`](/slides/python-net/hi/aspose.slides/slidelayouttype)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)