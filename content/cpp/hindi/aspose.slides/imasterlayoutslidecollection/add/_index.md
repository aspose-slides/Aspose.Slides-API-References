---
title: Add()
second_title: Aspose.Slides for C++ API संदर्भ
description: संग्रह के अंत में एक नया लेआउट स्लाइड जोड़ता है।
type: docs
weight: 27
url: /hi/aspose.slides/imasterlayoutslidecollection/add/
---
## IMasterLayoutSlideCollection::Add(SlideLayoutType, System::String) विधि

संग्रह के अंत में एक नया लेआउट स्लाइड जोड़ता है।

```cpp
virtual System::SharedPtr<ILayoutSlide> Aspose::Slides::IMasterLayoutSlideCollection::Add(SlideLayoutType layoutType, System::String layoutName)=0
```

### आर्ग्यूमेंट्स

| Parameter | Type | Description |
| --- | --- | --- |
| layoutType | [SlideLayoutType](../../slidelayouttype/) | नए लेआउट के लिए लेआउट प्रकार। समर्थित लेआउट प्रकार: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. अन्य लेआउट प्रकार वर्तमान में समर्थित नहीं हैं: Text, TwoColumnText, [Table](../../table/), TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | [System::String](../../../system/string/) | नए लेआउट का नाम। यदि दिया गया नाम पहले से उपयोग में है तो ArgumentException उत्पन्न किया जाएगा। यदि null पैरामीटर दिया जाता है तो नाम को पास किए गए लेआउट प्रकार के आधार पर स्वचालित रूप से उत्पन्न किया जाएगा (उदाहरण के लिए \"Title Slide\" या \"1_Title Slide\", \"2_..\", आदि)। |

### रिटर्न वैल्यू

जोड़ा गया स्लाइड।

## टिप्पणी

1) *layoutType* के मान [SlideLayoutType::Custom](../../slidelayouttype/) के लिए जोड़ा गया लेआउट में कोई प्लेसहोल्डर और कोई आकार नहीं हैं। 2) इस मेथड का समकक्ष मेथड [IGlobalLayoutSlideCollection::Add(SharedPtr<IMasterSlide>, SlideLayoutType, String)](../../igloballayoutslidecollection/add/) है, जिसे [IPresentation::get_LayoutSlides()](../../ipresentation/get_layoutslides/) प्रॉपर्टी के माध्यम से एक्सेस किया जाता है। 

## संबंधित देखें

* Enum [SlideLayoutType](../../slidelayouttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [ILayoutSlide](../../ilayoutslide/)
* क्लास [String](../../../system/string/)
* क्लास [IMasterLayoutSlideCollection](../)
* नामस्थान [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)