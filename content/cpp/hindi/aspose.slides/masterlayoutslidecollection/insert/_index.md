---
title: Insert()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: संग्रह की निर्दिष्ट स्थिति में एक नया लेआउट स्लाइड सम्मिलित करता है।
type: docs
weight: 40
url: /hi/aspose.slides/masterlayoutslidecollection/insert/
---
## MasterLayoutSlideCollection::Insert(int32_t, SlideLayoutType, System::String) विधि

एक नया लेआउट स्लाइड संग्रह की निर्दिष्ट स्थिति में सम्मिलित करता है।

```cpp
System::SharedPtr<ILayoutSlide> Aspose::Slides::MasterLayoutSlideCollection::Insert(int32_t index, SlideLayoutType layoutType, System::String layoutName) override
```

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | **int32_t** | नए स्लाइड का सूचकांक। |
| layoutType | [SlideLayoutType](../../slidelayouttype/) | नया लेआउट के लिए लेआउट प्रकार। समर्थित लेआउट प्रकार: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. अन्य लेआउट प्रकार अभी समर्थित नहीं हैं: Text, TwoColumnText, [Table](../../table/), TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | [System::String](../../../system/string/) | नए लेआउट के लिए नाम। यदि दिया गया नाम पहले से उपयोग में है तो ArgumentException फेंका जाएगा। यदि null पैरामीटर पास किया गया तो नाम स्वचालित रूप से पास किए गए लेआउट प्रकार के अनुसार उत्पन्न होगा (उदाहरण के लिए "Title Slide" या "1_Title Slide", "2_..", आदि)। |

### वापसी मान

सम्मिलित स्लाइड।

## टिप्पणी

स्थापित लेआउट, मान [SlideLayoutType::Custom](../../slidelayouttype/) के *layoutType* के लिए, कोई प्लेसहोल्डर और कोई आकार नहीं रखता है।

## देखें

* एनम [SlideLayoutType](../../slidelayouttype/)
* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [ILayoutSlide](../../ilayoutslide/)
* क्लास [String](../../../system/string/)
* क्लास [MasterLayoutSlideCollection](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)