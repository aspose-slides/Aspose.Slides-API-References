---
title: Remove()
second_title: Aspose.Slides for C++ API संदर्भ
description: ICollection से किसी विशिष्ट ऑब्जेक्ट की पहली उपस्थिति को हटाता है।
type: docs
weight: 131
url: /hi/aspose.slides/paragraphcollection/remove/
---
## ParagraphCollection::Remove(System::SharedPtr\<IParagraph\>) मेथड


एक विशिष्ट ऑब्जेक्ट की पहली उपस्थिति को [ICollection](../../../system.collections.generic/icollection/) से हटाता है।

```cpp
bool Aspose::Slides::ParagraphCollection::Remove(System::SharedPtr<IParagraph> item) override
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IParagraph](../../iparagraph/)\> | [ICollection](../../../system.collections.generic/icollection/) से हटाने के लिए ऑब्जेक्ट। |

### वापसी मान

यदि *item* को [ICollection](../../../system.collections.generic/icollection/) से सफलतापूर्वक हटा दिया गया हो तो true; अन्यथा false। यह मेथड तब भी false लौटाता है जब *item* मूल [ICollection](../../../system.collections.generic/icollection/) में नहीं मिला।

## देखें भी

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IParagraph](../../iparagraph/)
* Class [ParagraphCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)