---
title: AddClone()
second_title: Aspose.Slides C++ के लिए API संदर्भ
description: निर्दिष्ट लेआउट स्लाइड की एक प्रति प्रस्तुति में जोड़ता है।
type: docs
weight: 1
url: /hi/aspose.slides/igloballayoutslidecollection/addclone/
---
## IGlobalLayoutSlideCollection::AddClone(System::SharedPtr\<ILayoutSlide\>) मेथड


निर्दिष्ट लेआउट स्लाइड की एक प्रति प्रस्तुति में जोड़ता है।

```cpp
virtual System::SharedPtr<ILayoutSlide> Aspose::Slides::IGlobalLayoutSlideCollection::AddClone(System::SharedPtr<ILayoutSlide> sourceLayout)=0
```


### तर्क

| परामिति | प्रकार | विवरण |
| --- | --- | --- |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) to clone. |

### वापसी मान

जोड़ी गई स्लाइड।
## टिप्पणी



विभिन्न प्रस्तुतियों के बीच लेआउट को क्लोन करने पर लेआउट का मास्टर भी क्लोन किया जा सकता है ताकि स्रोत फ़ॉर्मेटिंग बरकरार रहे। इंटरनल रेजिस्ट्री का उपयोग स्वचालित रूप से क्लोन किए गए मास्टर को ट्रैक करने के लिए किया जाता है, जिससे समान मास्टर स्लाइड के कई क्लोन बनने से बचा जा सके। मास्टर स्लाइड की मैन्युअल क्लोनिंग को न तो रोका जाएगा न ही रजिस्टर किया जाएगा। 
## IGlobalLayoutSlideCollection::AddClone(System::SharedPtr\<ILayoutSlide\>, System::SharedPtr\<IMasterSlide\>) मेथड


निर्दिष्ट लेआउट स्लाइड की एक प्रति प्रस्तुति में जोड़ता है।

```cpp
virtual System::SharedPtr<ILayoutSlide> Aspose::Slides::IGlobalLayoutSlideCollection::AddClone(System::SharedPtr<ILayoutSlide> sourceLayout, System::SharedPtr<IMasterSlide> destMaster)=0
```


### तर्क

| परामिति | प्रकार | विवरण |
| --- | --- | --- |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) to clone. |
| destMaster | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | नए लेआउट के लिए मास्टर स्लाइड। |

### वापसी मान

जोड़ी गई स्लाइड।
## टिप्पणी



नया लेआउट गंतव्य प्रस्तुति में परिभाषित मास्टर के साथ जुड़ा रहेगा। इसलिए यह PowerPoint में "Use Destination Theme" विकल्प के साथ कॉपी/पेस्ट के समान है। 
## संबंधित देखें

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* वर्ग [ILayoutSlide](../../ilayoutslide/)
* वर्ग [IGlobalLayoutSlideCollection](../)
* वर्ग [IMasterSlide](../../imasterslide/)
* नामस्थान [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)