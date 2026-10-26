---
title: AddClone()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: निर्दिष्ट स्लाइड की एक कॉपी संग्रह के अंत में जोड़ता है।
type: docs
weight: 53
url: /hi/aspose.slides/slidecollection/addclone/
---
## SlideCollection::AddClone(System::SharedPtr\<ISlide\>) विधि

निर्दिष्ट स्लाइड की एक प्रतिलिपि संग्रह के अंत में जोड़ता है।

```cpp
System::SharedPtr<ISlide> Aspose::Slides::SlideCollection::AddClone(System::SharedPtr<ISlide> sourceSlide) override
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) को क्लोन करने के लिए। |

### रिटर्न वैल्यू

नया स्लाइड।

## टिप्पणियाँ

जब विभिन्न प्रस्तुतियों के बीच स्लाइड को क्लोन किया जाता है तो स्लाइड का मास्टर भी क्लोन किया जा सकता है। स्वचालित रूप से क्लोन किए गए मास्टर को ट्रैक करने के लिए आंतरिक रेजिस्ट्री का उपयोग किया जाता है ताकि समान मास्टर स्लाइड के कई क्लोन बनाने से बचा जा सके। मास्टर स्लाइड के मैनुअल क्लोनिंग को न तो रोका जाएगा न ही रजिस्टर किया जाएगा। यदि आपको क्लोनिंग प्रक्रिया पर अधिक नियंत्रण चाहिए तो स्लाइड को क्लोन करने के लिए [AddClone(SharedPtr<ISlide>, SharedPtr<ILayoutSlide>)](../../islidecollection/addclone/) या [AddClone(SharedPtr<ISlide>, SharedPtr<IMasterSlide>, bool)](../../islidecollection/addclone/) का उपयोग करें, लेआउट को क्लोन करने के लिए [IGlobalLayoutSlideCollection::AddClone(SharedPtr<ILayoutSlide>)](../../igloballayoutslidecollection/addclone/) या [IGlobalLayoutSlideCollection::AddClone(SharedPtr<ILayoutSlide>, SharedPtr<IMasterSlide>)](../../igloballayoutslidecollection/addclone/) और मास्टर को क्लोन करने के लिए [IMasterSlideCollection::AddClone(SharedPtr<IMasterSlide>)](../../imasterslidecollection/addclone/) का उपयोग करें।

## SlideCollection::AddClone(System::SharedPtr\<ISlide\>, System::SharedPtr\<ISection\>) विधि

निर्दिष्ट स्लाइड की एक प्रतिलिपि निर्दिष्ट सेक्शन के अंत में जोड़ता है।

```cpp
System::SharedPtr<ISlide> Aspose::Slides::SlideCollection::AddClone(System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<ISection> section) override
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) को क्लोन करने के लिए। |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | नए स्लाइड के लिए [Section](../../section/)। |

### रिटर्न वैल्यू

नया स्लाइड।

## टिप्पणियाँ

```cpp
auto presentation = MakeObject<Presentation>();
presentation->get_Slides()->idx_get(0)->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 200.0f, 50.0f, 300.0f, 100.0f);
presentation->get_Sections()->AddSection(u"Section 1", presentation->get_Slides()->idx_get(0));
auto section2 = presentation->get_Sections()->AppendEmptySection(u"Section 2");
presentation->get_Slides()->AddClone(presentation->get_Slides()->idx_get(0), section2);
// अब दूसरा सेक्शन पहले स्लाइड की एक कॉपी रखता है।
```

## SlideCollection::AddClone(System::SharedPtr\<ISlide\>, System::SharedPtr\<ILayoutSlide\>) विधि

निर्दिष्ट स्लाइड की एक प्रतिलिपि संग्रह के अंत में जोड़ता है।

```cpp
System::SharedPtr<ISlide> Aspose::Slides::SlideCollection::AddClone(System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<ILayoutSlide> destLayout) override
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) को क्लोन करने के लिए। |
| destLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | नए स्लाइड के लिए लेआउट स्लाइड। |

### रिटर्न वैल्यू

नया स्लाइड।

## SlideCollection::AddClone(System::SharedPtr\<ISlide\>, System::SharedPtr\<IMasterSlide\>, bool) विधि

निर्दिष्ट स्रोत स्लाइड की एक प्रतिलिपि संग्रह के अंत में जोड़ता है। उपयुक्त लेआउट स्वचालित रूप से निर्दिष्ट मास्टर से चयनित किया जाएगा (उपयुक्त लेआउट वह है जिसका Type या Name स्रोत स्लाइड के लेआउट के समान हो)। यदि उपयुक्त लेआउट नहीं है तो स्रोत स्लाइड का लेआउट क्लोन किया जाएगा (यदि allowCloneMissingLayout सत्य है) या PptxEditException फेंका जाएगा (यदि allowCloneMissingLayout असत्य है)।

```cpp
System::SharedPtr<ISlide> Aspose::Slides::SlideCollection::AddClone(System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<IMasterSlide> destMaster, bool allowCloneMissingLayout) override
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) को क्लोन करने के लिए। |
| destMaster | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | नए स्लाइड के लिए मास्टर स्लाइड। |
| allowCloneMissingLayout | **bool** | यदि निर्दिष्ट मास्टर में उपयुक्त लेआउट नहीं है तो स्रोत स्लाइड का लेआउट क्लोन किया जाएगा (यदि allowCloneMissingLayout सत्य है) या PptxEditException फेंका जाएगा (यदि allowCloneMissingLayout असत्य है)। |

### रिटर्न वैल्यू

नया स्लाइड।

## देखें

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [ISlide](../../islide/)
* क्लास [SlideCollection](../)
* क्लास [ISection](../../isection/)
* क्लास [ILayoutSlide](../../ilayoutslide/)
* क्लास [IMasterSlide](../../imasterslide/)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)