---
title: InsertClone()
second_title: Aspose.Slides for C++ API संदर्भ
description: कलेक्शन में निर्दिष्ट स्थिति पर निर्दिष्ट स्लाइड की एक कॉपी डालता है।
type: docs
weight: 66
url: /hi/aspose.slides/slidecollection/insertclone/
---
## SlideCollection::InsertClone(int32_t, System::SharedPtr\<ISlide\>) method

कलेक्शन में निर्दिष्ट स्थिति पर एक निर्दिष्ट स्लाइड की कॉपी डालता है।

```cpp
System::SharedPtr<ISlide> Aspose::Slides::SlideCollection::InsertClone(int32_t index, System::SharedPtr<ISlide> sourceSlide) override
```

### Arguments

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | **int32_t** | नए स्लाइड का इंडेक्स। |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | क्लोन करने के लिए [Slide](../../slide/)। |

### Return Value

डाली गई स्लाइड।

## टिप्पणियाँ

जब विभिन्न प्रस्तुतियों के बीच एक स्लाइड को क्लोन किया जाता है तो स्लाइड का मास्टर भी क्लोन हो सकता है। एक आंतरिक रजिस्ट्री का उपयोग स्वचालित रूप से क्लोन किए गए मास्टरों को ट्रैक करने के लिए किया जाता है ताकि समान मास्टर स्लाइड के कई क्लोन बनने से बचा जा सके। मास्टर स्लाइडों का मैनुअल क्लोनिंग न तो रोका जाएगा न ही रजिस्टर्ड होगा। यदि आपको क्लोनिंग प्रक्रिया पर अधिक नियंत्रण चाहिए तो स्लाइडों को क्लोन करने के लिए [InsertClone(int32_t, SharedPtr<ISlide>, SharedPtr<ILayoutSlide>)](../../islidecollection/insertclone/) या [InsertClone(int32_t, SharedPtr<ISlide>, SharedPtr<IMasterSlide>, bool)](../../islidecollection/insertclone/) का उपयोग करें और मास्टर को क्लोन करने के लिए [IMasterSlideCollection::AddClone(SharedPtr<IMasterSlide>)](../../imasterslidecollection/addclone/) का उपयोग करें।

निम्न उदाहरण दर्शाता है कि [Presentation](../../presentation/) के भीतर किसी अन्य स्थिति पर कैसे क्लोन किया जाए। 
```cpp
// एक प्रस्तुति फ़ाइल का प्रतिनिधित्व करने वाली Presentation क्लास का उदाहरण बनाएं
auto pres = System::MakeObject<Presentation>(u"CloneWithInSamePresentation.pptx");

// इच्छित स्लाइड को उसी प्रस्तुति में स्लाइड्स कलेक्शन के अंत में क्लोन करें
System::SharedPtr<ISlideCollection> slides = pres->get_Slides();
// इच्छित स्लाइड को उसी प्रस्तुति में निर्दिष्ट इंडेक्स पर क्लोन करें
slides->InsertClone(2, slides->idx_get(1));
// संशोधित प्रस्तुति को डिस्क पर लिखें
pres->Save(u"Aspose_CloneWithInSamePresentation_out.pptx", SaveFormat::Pptx);
```
निम्न उदाहरण दर्शाता है कि [Presentation](../../presentation/) के भीतर किसी अन्य स्थिति पर कैसे क्लोन किया जाए। 
```cpp
// स्रोत प्रस्तुति फ़ाइल को लोड करने के लिए Presentation क्लास का उदाहरण बनाएं
auto srcPres = System::MakeObject<Presentation>(u"CloneAtEndOfAnother.pptx");

// गंतव्य PPTX के लिए Presentation क्लास का उदाहरण बनाएं (जहाँ स्लाइड को क्लोन किया जाना है)
auto destPres = System::MakeObject<Presentation>();

destPres->get_Slides()->InsertClone(2, srcPres->get_Slides()->idx_get(0));
// गंतव्य प्रस्तुति को डिस्क पर लिखें
destPres->Save(u"Aspose2_out.pptx", SaveFormat::Pptx);
```

## SlideCollection::InsertClone(int32_t, System::SharedPtr\<ISlide\>, System::SharedPtr\<ILayoutSlide\>) method

कलेक्शन में निर्दिष्ट स्थिति पर एक निर्दिष्ट स्लाइड की कॉपी डालता है।

```cpp
System::SharedPtr<ISlide> Aspose::Slides::SlideCollection::InsertClone(int32_t index, System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<ILayoutSlide> destLayout) override
```

### Arguments

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | **int32_t** | नए स्लाइड का इंडेक्स। |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | क्लोन करने के लिए [Slide](../../slide/)। |
| destLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | नए स्लाइड के लिए लेआउट स्लाइड। |

### Return Value

डाली गई स्लाइड।

## SlideCollection::InsertClone(int32_t, System::SharedPtr\<ISlide\>, System::SharedPtr\<IMasterSlide\>, bool) method

कलेक्शन में निर्दिष्ट स्थिति पर निर्दिष्ट स्रोत स्लाइड की एक कॉपी डाली जाती है। निर्दिष्ट मास्टर से उपयुक्त लेआउट स्वचालित रूप से चुना जाएगा (उपयुक्त लेआउट वह लेआउट है जिसका प्रकार या नाम स्रोत स्लाइड के लेआउट के समान हो)। यदि उपयुक्त लेआउट नहीं मिलता है तो स्रोत स्लाइड का लेआउट क्लोन किया जाएगा (यदि allowCloneMissingLayout true है) या PptxEditException फेंका जाएगा (यदि allowCloneMissingLayout false है)।

```cpp
System::SharedPtr<ISlide> Aspose::Slides::SlideCollection::InsertClone(int32_t index, System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<IMasterSlide> destMaster, bool allowCloneMissingLayout) override
```

### Arguments

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | **int32_t** | नए स्लाइड का इंडेक्स। |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | क्लोन करने के लिए [Slide](../../slide/)। |
| destMaster | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | नए स्लाइड के लिए मुख्य स्लाइड। |
| allowCloneMissingLayout | **bool** | यदि निर्दिष्ट मास्टर में उपयुक्त लेआउट नहीं है तो स्रोत स्लाइड का लेआउट क्लोन किया जाएगा (यदि allowCloneMissingLayout true है) या PptxEditException फेंका जाएगा (यदि allowCloneMissingLayout false है)। |

### Return Value

डाली गई स्लाइड।

## संबंधित देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [ISlide](../../islide/)
* क्लास [SlideCollection](../)
* क्लास [ILayoutSlide](../../ilayoutslide/)
* क्लास [IMasterSlide](../../imasterslide/)
* नामस्थान [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)