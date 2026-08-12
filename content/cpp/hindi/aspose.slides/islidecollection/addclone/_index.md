---
title: AddClone()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट स्लाइड की एक प्रति संग्रह के अंत में जोड़ता है।
type: docs
weight: 14
url: /hi/aspose.slides/islidecollection/addclone/
---
## ISlideCollection::AddClone(System::SharedPtr\<ISlide\>) method

निर्दिष्ट स्लाइड की एक प्रति संग्रह के अंत में जोड़ता है।

```cpp
virtual System::SharedPtr<ISlide> Aspose::Slides::ISlideCollection::AddClone(System::SharedPtr<ISlide> sourceSlide)=0
```

### आर्ग्यूमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | क्लोन करने के लिए [Slide](../../slide/)। |

### वापसी मान

नया स्लाइड।

## टिप्पणियाँ

विभिन्न प्रस्तुतियों के बीच एक स्लाइड को क्लोन करते समय स्लाइड का मास्टर भी क्लोन किया जा सकता है। एक आंतरिक रजिस्ट्री का उपयोग स्वचालित रूप से क्लोन किए गए मास्टर को ट्रैक करने के लिए किया जाता है ताकि समान मास्टर स्लाइड की कई क्लोन बनाने से बचा जा सके। मास्टर स्लाइड्स को मैन्युअल रूप से क्लोन करना न तो रोका जाएगा और न ही रजिस्टर्ड होगा। यदि आपको क्लोनिंग प्रक्रिया पर अधिक नियंत्रण चाहिए तो स्लाइड्स को क्लोन करने के लिए [AddClone(SharedPtr<ISlide>, SharedPtr<ILayoutSlide>)](./) या [AddClone(SharedPtr<ISlide>, SharedPtr<IMasterSlide>, bool)](./) का उपयोग करें, लेआउट को क्लोन करने के लिए [IGlobalLayoutSlideCollection::AddClone(SharedPtr<ILayoutSlide>)](../../igloballayoutslidecollection/addclone/) या [IGlobalLayoutSlideCollection::AddClone(SharedPtr<ILayoutSlide>, SharedPtr<IMasterSlide>)](../../igloballayoutslidecollection/addclone/) और मास्टर को क्लोन करने के लिए [IMasterSlideCollection::AddClone(SharedPtr<IMasterSlide>)](../../imasterslidecollection/addclone/) का उपयोग करें।

## ISlideCollection::AddClone(System::SharedPtr\<ISlide\>, System::SharedPtr\<ISection\>) method

निर्दिष्ट स्लाइड की एक प्रति निर्दिष्ट सेक्शन के अंत में जोड़ता है।

```cpp
virtual System::SharedPtr<ISlide> Aspose::Slides::ISlideCollection::AddClone(System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<ISection> section)=0
```

### आर्ग्यूमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | क्लोन करने के लिए [Slide](../../slide/)। |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | नए स्लाइड के लिए [Section](../../section/)। |

### वापसी मान

नया स्लाइड।

## टिप्पणियाँ

```cpp
auto presentation = MakeObject<Presentation>();
presentation->get_Slides()->idx_get(0)->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 200.0f, 50.0f, 300.0f, 100.0f);
presentation->get_Sections()->AddSection(u"Section 1", presentation->get_Slides()->idx_get(0));
auto section2 = presentation->get_Sections()->AppendEmptySection(u"Section 2");
presentation->get_Slides()->AddClone(presentation->get_Slides()->idx_get(0), section2);
// अब दूसरा सेक्शन पहली स्लाइड की एक प्रति रखता है।
```

## ISlideCollection::AddClone(System::SharedPtr\<ISlide\>, System::SharedPtr\<ILayoutSlide\>) method

निर्दिष्ट स्लाइड की एक प्रति संग्रह के अंत में जोड़ता है।

```cpp
virtual System::SharedPtr<ISlide> Aspose::Slides::ISlideCollection::AddClone(System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<ILayoutSlide> destLayout)=0
```

### आर्ग्यूमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | क्लोन करने के लिए [Slide](../../slide/)। |
| destLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | नए स्लाइड के लिए लेआउट स्लाइड। |

### वापसी मान

नया स्लाइड।

## ISlideCollection::AddClone(System::SharedPtr\<ISlide\>, System::SharedPtr\<IMasterSlide\>, bool) method

निर्दिष्ट स्रोत स्लाइड की एक प्रति संग्रह के अंत में जोड़ता है। निर्दिष्ट मास्टर से उपयुक्त लेआउट स्वचालित रूप से चयन किया जाएगा (उपयुक्त लेआउट वह लेआउट है जिसका Type या Name स्रोत स्लाइड के लेआउट के समान हो)। यदि उपयुक्त लेआउट नहीं है तो स्रोत स्लाइड का लेआउट क्लोन किया जाएगा (यदि allowCloneMissingLayout true है) या PptxEditException फेंका जाएगा (यदि allowCloneMissingLayout false है)।

```cpp
virtual System::SharedPtr<ISlide> Aspose::Slides::ISlideCollection::AddClone(System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<IMasterSlide> destMaster, bool allowCloneMissingLayout)=0
```

### आर्ग्यूमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | क्लोन करने के लिए [Slide](../../slide/)। |
| destMaster | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | नए स्लाइड के लिए मास्टर स्लाइड। |
| allowCloneMissingLayout | **bool** | यदि निर्दिष्ट मास्टर में उपयुक्त लेआउट नहीं है तो स्रोत स्लाइड का लेआउट क्लोन किया जाएगा (यदि allowCloneMissingLayout true है) या PptxEditException फेंका जाएगा (यदि allowCloneMissingLayout false है)। |

### वापसी मान

नया स्लाइड।

## संबंधित

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISlide](../../islide/)
* Class [ISlideCollection](../)
* Class [ISection](../../isection/)
* Class [ILayoutSlide](../../ilayoutslide/)
* Class [IMasterSlide](../../imasterslide/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)