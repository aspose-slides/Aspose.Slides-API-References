---
title: Reorder()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: स्लाइड को संग्रह से निर्दिष्ट स्थिति में ले जाता है।
type: docs
weight: 157
url: /hi/aspose.slides/slidecollection/reorder/
---
## SlideCollection::Reorder(int32_t, System::SharedPtr\<ISlide\>) विधि

स्लाइड को संग्रह से निर्दिष्ट स्थिति में ले जाता है।

```cpp
void Aspose::Slides::SlideCollection::Reorder(int32_t index, System::SharedPtr<ISlide> slide) override
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | **int32_t** | लक्ष्य अनुक्रमणिका। |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) को स्थानांतरित करने के लिए। |

## SlideCollection::Reorder(int32_t, const System::ArrayPtr\<System::SharedPtr\<ISlide\>\>\&) विधि

स्लाइड्स को संग्रह से निर्दिष्ट स्थिति में ले जाता है। [Slides](../../) को सूची में जिस क्रम में प्रकट होते हैं, उसके क्रम में अनुक्रमणिका से शुरू होकर रखा जाएगा।

```cpp
void Aspose::Slides::SlideCollection::Reorder(int32_t index, const System::ArrayPtr<System::SharedPtr<ISlide>> &slides) override
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | **int32_t** | लक्ष्य अनुक्रमणिका। |
| slides | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\>\>\& | [Slides](../../) को स्थानांतरित करने के लिए। |

## संबंधित देखें

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* टाइपडिफ [ArrayPtr](../../../system/arrayptr/)
* क्लास [ISlide](../../islide/)
* क्लास [SlideCollection](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)