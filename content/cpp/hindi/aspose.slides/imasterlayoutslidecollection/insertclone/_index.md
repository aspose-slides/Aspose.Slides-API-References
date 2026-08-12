---
title: InsertClone()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट लेआउट स्लाइड की एक प्रति को संग्रह के निर्दिष्ट स्थान पर सम्मिलित करता है।
type: docs
weight: 14
url: /hi/aspose.slides/imasterlayoutslidecollection/insertclone/
---
## IMasterLayoutSlideCollection::InsertClone(int32_t, System::SharedPtr\<ILayoutSlide\>) विधि

निर्दिष्ट लेआउट स्लाइड की एक प्रति को संग्रह के निर्दिष्ट स्थान पर सम्मिलित करता है।

```cpp
virtual System::SharedPtr<ILayoutSlide> Aspose::Slides::IMasterLayoutSlideCollection::InsertClone(int32_t index, System::SharedPtr<ILayoutSlide> sourceLayout)=0
```

### आर्गुमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| index | **int32_t** | नए स्लाइड का इंडेक्स। |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) को क्लोन करने के लिए। |

### वापसी मान

सम्मिलित स्लाइड।

## टिप्पणी

नया लेआउट इस लेआउट स्लाइड्स संग्रह के पैरेंट मास्टर स्लाइड से जुड़ा होगा। इसलिए यह PowerPoint में \"Use Destination Theme\" विकल्प के साथ कॉपी/पेस्ट का समकक्ष है। 

## देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ILayoutSlide](../../ilayoutslide/)
* Class [IMasterLayoutSlideCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)