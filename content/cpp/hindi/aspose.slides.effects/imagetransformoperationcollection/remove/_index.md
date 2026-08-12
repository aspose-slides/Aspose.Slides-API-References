---
title: Remove()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: ICollection से किसी विशिष्ट वस्तु की पहली घटना को हटाता है।
type: docs
weight: 339
url: /hi/aspose.slides.effects/imagetransformoperationcollection/remove/
---
## ImageTransformOperationCollection::Remove(const System::SharedPtr\<IImageTransformOperation\>\&) विधि

एक विशिष्ट वस्तु की पहली घटना को [ICollection](../../../system.collections.generic/icollection/) से हटाता है।

```cpp
bool Aspose::Slides::Effects::ImageTransformOperationCollection::Remove(const System::SharedPtr<IImageTransformOperation> &item) override
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| item | const [System::SharedPtr](../../../system/sharedptr/)\<[IImageTransformOperation](../../iimagetransformoperation/)\>\& | वस्तु जिसे [ICollection](../../../system.collections.generic/icollection/) से हटाया जाना है। |

### वापसी मान

*item* को [ICollection](../../../system.collections.generic/icollection/) से सफलतापूर्वक हटाया गया हो तो true; अन्यथा false। यह विधि false भी लौटाएगी यदि *item* मूल [ICollection](../../../system.collections.generic/icollection/) में नहीं मिला।

## संबंधित देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [IImageTransformOperation](../../iimagetransformoperation/)
* क्लास [ImageTransformOperationCollection](../)
* नेमस्पेस [Aspose::Slides::Effects](../../)
* लाइब्रेरी [Aspose.Slides](../../../)