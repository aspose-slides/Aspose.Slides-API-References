---
title: AddClone()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट लेआउट स्लाइड की एक प्रति प्रस्तुति में जोड़ता है।
type: docs
weight: 1
url: /hi/aspose.slides/globallayoutslidecollection/addclone/
---
## GlobalLayoutSlideCollection::AddClone(System::SharedPtr\<ILayoutSlide\>) विधि


निर्दिष्ट लेआउट स्लाइड की एक प्रति प्रस्तुति में जोड़ता है।

```cpp
System::SharedPtr<ILayoutSlide> Aspose::Slides::GlobalLayoutSlideCollection::AddClone(System::SharedPtr<ILayoutSlide> sourceLayout) override
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | वर्णन |
| --- | --- | --- |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) को क्लोन करने के लिए। |

### वापसी मान

जोड़ा गया स्लाइड।

## टिप्पणियाँ



जब विभिन्न प्रस्तुतियों के बीच लेआउट को क्लोन किया जाता है, तो लेआउट का मास्टर भी स्रोत स्वरूप को बनाए रखने के लिए क्लोन किया जा सकता है। आंतरिक रेज़िस्ट्री का उपयोग स्वचालित रूप से क्लोन किए गए मास्टर को ट्रैक करने के लिए किया जाता है, जिससे समान मास्टर स्लाइड के कई क्लोन बनना रोकता है। मास्टर स्लाइड्स की मैन्युअल क्लोनिंग न तो रोकी जाएगी और न ही रजिस्टर्ड होगी। 
## GlobalLayoutSlideCollection::AddClone(System::SharedPtr\<ILayoutSlide\>, System::SharedPtr\<IMasterSlide\>) विधि


निर्दिष्ट लेआउट स्लाइड की एक प्रति प्रस्तुति में जोड़ता है।

```cpp
System::SharedPtr<ILayoutSlide> Aspose::Slides::GlobalLayoutSlideCollection::AddClone(System::SharedPtr<ILayoutSlide> sourceLayout, System::SharedPtr<IMasterSlide> destMaster) override
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | वर्णन |
| --- | --- | --- |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) को क्लोन करने के लिए। |
| destMaster | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | नए लेआउट के लिए मास्टर स्लाइड। |

### वापसी मान

जोड़ा गया स्लाइड।

## टिप्पणियाँ



1) नया लेआउट गंतव्य प्रस्तुति में निर्धारित मास्टर से जुड़ा होगा। इसलिए यह PowerPoint में "Use Destination Theme" विकल्प के साथ कॉपी/पेस्ट के समान है। 2) इस विधि का समकक्ष विधि [IMasterLayoutSlideCollection::AddClone(SharedPtr<ILayoutSlide>)](../../imasterlayoutslidecollection/addclone/) है, जिसे [IMasterSlide::get_LayoutSlides()](../../imasterslide/get_layoutslides/) प्रॉपर्टी द्वारा पहुँचाया जाता है। 

## आगे देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [ILayoutSlide](../../ilayoutslide/)
* क्लास [GlobalLayoutSlideCollection](../)
* क्लास [IMasterSlide](../../imasterslide/)
* नेमस्पेस [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)