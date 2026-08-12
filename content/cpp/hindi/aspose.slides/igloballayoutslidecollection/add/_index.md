---
title: Add()
second_title: Aspose.Slides for C++ API संदर्भ
description: प्रेज़ेंटेशन में एक नया लेआउट स्लाइड जोड़ता है।
type: docs
weight: 14
url: /hi/aspose.slides/igloballayoutslidecollection/add/
---
## IGlobalLayoutSlideCollection::Add(System::SharedPtr\<IMasterSlide\>, SlideLayoutType, System::String) मेथड

प्रेज़ेंटेशन में एक नया लेआउट स्लाइड जोड़ता है।

```cpp
virtual System::SharedPtr<ILayoutSlide> Aspose::Slides::IGlobalLayoutSlideCollection::Add(System::SharedPtr<IMasterSlide> master, SlideLayoutType layoutType, System::String layoutName)=0
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| master | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | नए लेआउट के लिए मास्टर स्लाइड। |
| layoutType | [SlideLayoutType](../../slidelayouttype/) | नए लेआउट के लिए लेआउट प्रकार। समर्थित लेआउट प्रकार: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. अभी अन्य लेआउट प्रकार समर्थित नहीं हैं: Text, TwoColumnText, [Table](../../table/), TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | [System::String](../../../system/string/) | नए लेआउट के लिए नाम। यदि दिया गया नाम पहले से उपयोग में है तो ArgumentException फेंका जाएगा। यदि null पैरामीटर दिया जाता है तो नाम स्वतः उत्पन्न किया जाएगा, जो दिए गए लेआउट प्रकार के अनुसार होगा (उदाहरण के लिये \"Title Slide\" या \"1_Title Slide\", \"2_..\", आदि)। |

### रिटर्न वैल्यू

जोड़ा गया स्लाइड।

## टिप्पणियाँ

1) [SlideLayoutType::Custom](../../slidelayouttype/) मान के लिए *layoutType* पर जोड़ा गया लेआउट में कोई प्लेसहोल्डर और कोई शेप नहीं है। 2) इस मेथड का समकक्ष मेथड [IMasterLayoutSlideCollection::Add(SlideLayoutType, String)](../../imasterlayoutslidecollection/add/) है जो [IMasterSlide::get_LayoutSlides()](../../imasterslide/get_layoutslides/) प्रॉपर्टी के माध्यम से एक्सेस किया जाता है। 

## संबंधित देखें

* एन्युम [SlideLayoutType](../../slidelayouttype/)
* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [ILayoutSlide](../../ilayoutslide/)
* क्लास [IMasterSlide](../../imasterslide/)
* क्लास [String](../../../system/string/)
* क्लास [IGlobalLayoutSlideCollection](../)
* नामस्थान [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)