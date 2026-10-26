---
title: Add()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: संग्रह के अंत में एक नया लेआउट स्लाइड जोड़ता है।
type: docs
weight: 27
url: /hi/aspose.slides/masterlayoutslidecollection/add/
---
## MasterLayoutSlideCollection::Add(SlideLayoutType, System::String) मेथड

संग्रह के अंत में एक नया लेआउट स्लाइड जोड़ता है।

```cpp
System::SharedPtr<ILayoutSlide> Aspose::Slides::MasterLayoutSlideCollection::Add(SlideLayoutType layoutType, System::String layoutName) override
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| layoutType | [SlideLayoutType](../../slidelayouttype/) | नए लेआउट के लिए लेआउट प्रकार। समर्थित लेआउट प्रकार: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. अन्य लेआउट प्रकार वर्तमान में समर्थित नहीं हैं: Text, TwoColumnText, [Table](../../table/), TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | [System::String](../../../system/string/) | नए लेआउट के लिए नाम। यदि दिया गया नाम पहले से उपयोग में है तो ArgumentException फेंका जायेगा। यदि null पैरामीटर पास किया गया है तो नाम स्वचालित रूप से पास किए गए लेआउट प्रकार के अनुसार उत्पन्न किया जायेगा (उदाहरण के लिए "Title Slide" या "1_Title Slide", "2_..", आदि)। |

### रिटर्न वैल्यू

जोड़ दिया गया स्लाइड।

## टिप्पणियाँ

1) *layoutType* के मान [SlideLayoutType::Custom](../../slidelayouttype/) के लिए जोड़ा गया लेआउट में कोई प्लेसहोल्डर और कोई आकार नहीं है। 2) इस मेथड का समकक्ष मेथड [IGlobalLayoutSlideCollection::Add(SharedPtr<IMasterSlide>, SlideLayoutType, String)](../../igloballayoutslidecollection/add/) है जिसे [IPresentation::get_LayoutSlides()](../../ipresentation/get_layoutslides/) प्रॉपर्टी के साथ एक्सेस किया जाता है। 

## संबंधित देखें

* Enum [SlideLayoutType](../../slidelayouttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ILayoutSlide](../../ilayoutslide/)
* Class [String](../../../system/string/)
* Class [MasterLayoutSlideCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)