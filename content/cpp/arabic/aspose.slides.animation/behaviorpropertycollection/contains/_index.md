---
title: Contains()
second_title: مرجع API Aspose.Slides for C++  
description: يحدد ما إذا كانت ICollection تحتوي على قيمة محددة.
type: docs
weight: 118
url: /ar/aspose.slides.animation/behaviorpropertycollection/contains/
---
## BehaviorPropertyCollection::Contains(const System::SharedPtr\<IBehaviorProperty\>\&) const طريقة


يحدد ما إذا كان [ICollection](../../../system.collections.generic/icollection/) يحتوي على قيمة محددة.

```cpp
bool Aspose::Slides::Animation::BehaviorPropertyCollection::Contains(const System::SharedPtr<IBehaviorProperty> &item) const override
```


### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| item | const [System::SharedPtr](../../../system/sharedptr/)\<[IBehaviorProperty](../../ibehaviorproperty/)\>\& | الخاصية التي يتم البحث عنها في [ICollection](../../../system.collections.generic/icollection/). |

### قيمة الإرجاع

true إذا تم العثور على *item* في [ICollection](../../../system.collections.generic/icollection/)؛ وإلا false.

## BehaviorPropertyCollection::Contains(const System::String\&) const طريقة


يحدد ما إذا كان [ICollection](../../../system.collections.generic/icollection/) يحتوي على قيمة محددة.

```cpp
bool Aspose::Slides::Animation::BehaviorPropertyCollection::Contains(const System::String &propertyValue) const override
```


### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| propertyValue | const [System::String](../../../system/string/)\& | قيمة الخاصية التي يتم البحث عنها في [ICollection](../../../system.collections.generic/icollection/). |

### قيمة الإرجاع

true إذا تم العثور على *propertyValue* في [ICollection](../../../system.collections.generic/icollection/)؛ وإلا false.

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IBehaviorProperty](../../ibehaviorproperty/)
* Class [BehaviorPropertyCollection](../)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)