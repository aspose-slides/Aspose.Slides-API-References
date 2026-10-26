---
title: Remove()
second_title: Aspose.Slides C++ के लिए API संदर्भ
description: कलेक्शन से एक लेआउट को हटाता है।
type: docs
weight: 66
url: /hi/aspose.slides/layoutslidecollection/remove/
---
## LayoutSlideCollection::Remove(System::SharedPtr\<ILayoutSlide\>) विधि

संग्रह से एक लेआउट को हटाता है।

```cpp
void Aspose::Slides::LayoutSlideCollection::Remove(System::SharedPtr<ILayoutSlide> value) override
```


### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | संग्रह से हटाने के लिए लेआउट स्लाइड। |
## टिप्पणियाँ

1) PptxEditException को फेंके जाने से बचने के लिए लेआउट की HasDependingSlides प्रॉपर्टी को पहले जांचें। 2) आप कोड को सरल बनाने के लिए [ILayoutSlide::Remove](../../ilayoutslide/remove/) विधि का भी उपयोग कर सकते हैं। 
## संबंधित देखें

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [ILayoutSlide](../../ilayoutslide/)
* क्लास [LayoutSlideCollection](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)