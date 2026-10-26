---
title: InsertClone()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट लेआउट स्लाइड की एक प्रति संग्रह के निर्दिष्ट स्थान पर सम्मिलित करता है।
type: docs
weight: 14
url: /hi/aspose.slides/masterlayoutslidecollection/insertclone/
---
## MasterLayoutSlideCollection::InsertClone(int32_t, System::SharedPtr\<ILayoutSlide\>) विधि


निर्दिष्ट लेआउट स्लाइड की एक प्रति संग्रह के निर्दिष्ट स्थान पर सम्मिलित करता है।

```cpp
System::SharedPtr<ILayoutSlide> Aspose::Slides::MasterLayoutSlideCollection::InsertClone(int32_t index, System::SharedPtr<ILayoutSlide> sourceLayout) override
```


### आर्ग्युमेंट्स

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | नए स्लाइड का सूचकांक। |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) को क्लोन करने के लिए। |

### रिटर्न मान

इंसर्ट की गई स्लाइड।

## टिप्पणियां

नया लेआउट इस लेआउट स्लाइड्स संग्रह के पैरेंट मास्टर स्लाइड के साथ लिंक किया जाएगा। इसलिए यह PowerPoint में "Use Destination Theme" विकल्प के साथ कॉपी/पेस्ट के समान है। 

## संबंधित देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ILayoutSlide](../../ilayoutslide/)
* Class [MasterLayoutSlideCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)