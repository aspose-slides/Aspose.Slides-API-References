---
title: Remove()
second_title: Aspose.Slides for C++ API संदर्भ
description: संग्रह से लेआउट को हटाता है।
type: docs
weight: 27
url: /hi/aspose.slides/ilayoutslidecollection/remove/
---
## ILayoutSlideCollection::Remove(System::SharedPtr\<ILayoutSlide\>) मेथड


संग्रह से लेआउट को हटाता है।

```cpp
virtual void Aspose::Slides::ILayoutSlideCollection::Remove(System::SharedPtr<ILayoutSlide> value)=0
```

### आर्ग्यूमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | संग्रह से हटाने के लिए लेआउट स्लाइड। |

## टिप्पणियाँ

1) PptxEditException को फ़ेंकने से बचने के लिए लेआउट की HasDependingSlides प्रॉपर्टी पहले जांचें। 2) आप कोड को सरल बनाने के लिए [ILayoutSlide::Remove](../../ilayoutslide/remove/) मेथड का भी उपयोग कर सकते हैं। 

## संबंधित देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [ILayoutSlide](../../ilayoutslide/)
* क्लास [ILayoutSlideCollection](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)