---
title: Add()
second_title: Aspose.Slides for C++ API संदर्भ
description: प्रेजेंटेशन में एक नई लेआउट स्लाइड जोड़ता है।
type: docs
weight: 14
url: /hi/aspose.slides/globallayoutslidecollection/add/
---
## GlobalLayoutSlideCollection::Add(System::SharedPtr\<IMasterSlide\>, SlideLayoutType, System::String) विधि


प्रेजेंटेशन में एक नई लेआउट स्लाइड जोड़ता है।

```cpp
System::SharedPtr<ILayoutSlide> Aspose::Slides::GlobalLayoutSlideCollection::Add(System::SharedPtr<IMasterSlide> master, SlideLayoutType layoutType, System::String layoutName) override
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| master | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | नई लेआउट के लिए मास्टर स्लाइड। |
| layoutType | [SlideLayoutType](../../slidelayouttype/) | नई लेआउट के लिए लेआउट प्रकार। समर्थित लेआउट प्रकार: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. अन्य लेआउट प्रकार वर्तमान में समर्थित नहीं हैं: Text, TwoColumnText, [Table](../../table/), TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | [System::String](../../../system/string/) | नई लेआउट के लिए नाम। यदि दिया गया नाम पहले से उपयोग में है तो ArgumentException फेंका जाएगा। यदि null पैरामीटर पास किया जाता है तो नाम स्वचालित रूप से पास किए गए लेआउट प्रकार के अनुसार उत्पन्न किया जाएगा (उदाहरण के लिए "Title Slide" या "1_Title Slide", "2_..", आदि)। |

### रिटर्न वैल्यू

जोड़ी गई स्लाइड।

## टिप्पणियाँ

1) *layoutType* के मान [SlideLayoutType::Custom](../../slidelayouttype/) के लिए जोड़ा गया लेआउट कोई प्लेसहोल्डर और कोई आकृति नहीं रखता। 2) इस विधि का समानांतर [IMasterLayoutSlideCollection::Add(SlideLayoutType, String)](../../imasterlayoutslidecollection/add/) विधि है जिसे [IMasterSlide::get_LayoutSlides()](../../imasterslide/get_layoutslides/) प्रॉपर्टी के द्वारा एक्सेस किया जाता है।

## सम्बंधित देखें

* Enum [SlideLayoutType](../../slidelayouttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ILayoutSlide](../../ilayoutslide/)
* Class [IMasterSlide](../../imasterslide/)
* Class [String](../../../system/string/)
* Class [GlobalLayoutSlideCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)