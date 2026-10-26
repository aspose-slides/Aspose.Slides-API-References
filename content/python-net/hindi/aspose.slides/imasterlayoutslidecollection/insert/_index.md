---
title: insert method
second_title: Aspose.Slides Python के लिए .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/imasterlayoutslidecollection/insert/
weight: 40
---
## insert(self, index, layout_type, layout_name) {#int-slidelayouttype-str}
संग्रह में निर्दिष्ट स्थान पर एक नया लेआउट स्लाइड सम्मिलित करता है।

### रिटर्न
सम्‍मिलित स्लाइड।

```python
def insert(self, index, layout_type, layout_name):
    ...
```


| परामीटर | प्रकार | विवरण |
| :- | :- | :- |
| index | **int** | नए स्लाइड का अनुक्रमणिका। |
| layout_type | [`SlideLayoutType`](/slides/python-net/hi/aspose.slides/slidelayouttype) | लेआउट प्रकार के लिए नया लेआउट।<br/><br/>            Supported layout types: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom.<br/><br/>            Other layout types are not supported now: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layout_name | **str** | नए लेआउट के लिए नाम। यदि दिया गया नाम पहले से उपयोग में है तो ArgumentException फेंका जाएगा।<br/><br/>यदि None पैरामीटर दिया जाता है तो दिया गया लेआउट प्रकार के अनुसार नाम स्वचालित रूप से उत्पन्न किया जाएगा<br/><br/>(उदाहरण के लिए "Title Slide" या "1_Title Slide", "2_..", आदि)। |

### टिप्पणियाँ
SlideLayoutType.Custom मान के लिए सम्मिलित लेआउट `layout_type` में कोई प्लेसहोल्डर और कोई आकार नहीं होते हैं।

### अपवाद
| अपवाद | विवरण |
| :- | :- |
| **RuntimeError(Proxy error(NotImplementedException))** | यदि पैरामीटर `layout_type` का असमर्थित मान दिया जाता है तो फेंका जाता है। Layout types that are not supported now: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| **RuntimeError(Proxy error(ArgumentException))** | यदि लेआउट नाम का मान `layout_name` इस लेआउट संग्रह में पहले से उपयोग में है तो फेंका जाता है। |

### देखें
* क्लास [`ILayoutSlide`](/slides/python-net/hi/aspose.slides/ilayoutslide)
* क्लास [`IMasterLayoutSlideCollection`](/slides/python-net/hi/aspose.slides/imasterlayoutslidecollection)
* एन्यूमरेशन [`SlideLayoutType`](/slides/python-net/hi/aspose.slides/slidelayouttype)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)