---
title: IndexOf()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: IList में किसी विशिष्ट आइटम का सूचकांक निर्धारित करता है।
type: docs
weight: 40
url: /hi/aspose.slides.animation/behaviorpropertycollection/indexof/
---
## BehaviorPropertyCollection::IndexOf(const System::SharedPtr\<IBehaviorProperty\>\&) const method


विशिष्ट आइटम का सूचकांक [IList](../../../system.collections.generic/ilist/) में निर्धारित करता है।

```cpp
int32_t Aspose::Slides::Animation::BehaviorPropertyCollection::IndexOf(const System::SharedPtr<IBehaviorProperty> &item) const override
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| item | const [System::SharedPtr](../../../system/sharedptr/)\<[IBehaviorProperty](../../ibehaviorproperty/)\>\& | [IList](../../../system.collections.generic/ilist/) में स्थित करने के लिये वस्तु। |

### वापसी मान

*item* का सूचकांक यदि सूची में मिला तो; अन्यथा -1।

## BehaviorPropertyCollection::IndexOf(const System::String\&) const method


विशिष्ट आइटम का सूचकांक प्रॉपर्टी वैल्यू द्वारा [IList](../../../system.collections.generic/ilist/) में निर्धारित करता है।

```cpp
int32_t Aspose::Slides::Animation::BehaviorPropertyCollection::IndexOf(const System::String &propertyValue) const override
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| propertyValue | const [System::String](../../../system/string/)\& | प्रॉपर्टी का मान |

### वापसी मान

निर्दिष्ट मान वाले प्रॉपर्टी का सूचकांक

## संबंधित देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IBehaviorProperty](../../ibehaviorproperty/)
* Class [BehaviorPropertyCollection](../)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)