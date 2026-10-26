---
title: InsertClone()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट स्लाइड की एक कॉपी को कलेक्शन की निर्दिष्ट स्थिति में सम्मिलित करता है।
type: docs
weight: 27
url: /hi/aspose.slides/islidecollection/insertclone/
---
## ISlideCollection::InsertClone(int32_t, System::SharedPtr\<ISlide\>) विधि

एक निर्दिष्ट स्लाइड की कॉपी को कलेक्शन की निर्दिष्ट स्थिति में डालता है।

```cpp
virtual System::SharedPtr<ISlide> Aspose::Slides::ISlideCollection::InsertClone(int32_t index, System::SharedPtr<ISlide> sourceSlide)=0
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | **int32_t** | नयी स्लाइड का इंडेक्स। |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) को क्लोन करने के लिए। |

### रिटर्न वैल्यू

इन्सर्टेड स्लाइड।

## टिप्पणियाँ

जब विभिन्न प्रस्तुतियों के बीच स्लाइड को क्लोन किया जाता है तो स्लाइड का मास्टर भी क्लोन किया जा सकता है। आंतरिक रजिस्ट्री का उपयोग स्वचालित रूप से क्लोन किए गए मास्टर्स को ट्रैक करने के लिए किया जाता है ताकि एक ही मास्टर स्लाइड के कई क्लोन बनाने से रोका जा सके। मास्टर स्लाइड्स का मैन्युअल क्लोनिंग न तो रोका जाएगा न ही रजिस्टर्ड किया जाएगा। यदि आपको क्लोनिंग प्रक्रिया पर अधिक नियंत्रण चाहिए तो स्लाइड्स को क्लोन करने के लिए [InsertClone(int32_t, SharedPtr<ISlide>, SharedPtr<ILayoutSlide>)](./) या [InsertClone(int32_t, SharedPtr<ISlide>, SharedPtr<IMasterSlide>, bool)](./) और मास्टर्स को क्लोन करने के लिए [IMasterSlideCollection::AddClone(SharedPtr<IMasterSlide>)](../../imasterslidecollection/addclone/) का उपयोग करें।

## ISlideCollection::InsertClone(int32_t, System::SharedPtr\<ISlide\>, System::SharedPtr\<ILayoutSlide\>) विधि

एक निर्दिष्ट स्लाइड की कॉपी को कलेक्शन की निर्दिष्ट स्थिति में डालता है।

```cpp
virtual System::SharedPtr<ISlide> Aspose::Slides::ISlideCollection::InsertClone(int32_t index, System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<ILayoutSlide> destLayout)=0
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | **int32_t** | नयी स्लाइड का इंडेक्स। |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) को क्लोन करने के लिए। |
| destLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | नयी स्लाइड के लिए लेआउट स्लाइड। |

### रिटर्न वैल्यू

इन्सर्टेड स्लाइड।

## ISlideCollection::InsertClone(int32_t, System::SharedPtr\<ISlide\>, System::SharedPtr\<IMasterSlide\>, bool) विधि

एक निर्दिष्ट स्रोत स्लाइड की कॉपी को कलेक्शन की निर्दिष्ट स्थिति में डालता है। उपयुक्त लेआउट को निर्दिष्ट मास्टर से स्वचालित रूप से चुना जाएगा (उपयुक्त लेआउट वह लेआउट है जिसका Type या Name स्रोत स्लाइड के लेआउट के समान है)। यदि उपयुक्त लेआउट नहीं है तो स्रोत स्लाइड का लेआउट क्लोन किया जाएगा (यदि allowCloneMissingLayout true है) या PptxEditException फेंका जाएगा (यदि allowCloneMissingLayout false है)।

```cpp
virtual System::SharedPtr<ISlide> Aspose::Slides::ISlideCollection::InsertClone(int32_t index, System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<IMasterSlide> destMaster, bool allowCloneMissingLayout)=0
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | **int32_t** | नयी स्लाइड का इंडेक्स। |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) को क्लोन करने के लिए। |
| destMaster | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | नयी स्लाइड के लिए मास्टर स्लाइड। |
| allowCloneMissingLayout | **bool** | यदि निर्दिष्ट मास्टर में उपयुक्त लेआउट नहीं है तो स्रोत स्लाइड का लेआउट क्लोन किया जाएगा (यदि allowCloneMissingLayout true है) या PptxEditException फेंका जाएगा (यदि allowCloneMissingLayout false है)। |

### रिटर्न वैल्यू

इन्सर्टेड स्लाइड।

## संबंधित देखें

* टाइपडिफ़ [SharedPtr](../../../system/sharedptr/)
* क्लास [ISlide](../../islide/)
* क्लास [ISlideCollection](../)
* क्लास [ILayoutSlide](../../ilayoutslide/)
* क्लास [IMasterSlide](../../imasterslide/)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)