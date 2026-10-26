---
title: IndexOf()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: يحدد فهرس عنصر محدد في IList.
type: docs
weight: 40
url: /ar/aspose.slides.animation/behaviorpropertycollection/indexof/
---
## BehaviorPropertyCollection::IndexOf(const System::SharedPtr\<IBehaviorProperty\>\&) const طريقة

يحدد فهرس عنصر محدد في [IList](../../../system.collections.generic/ilist/).

```cpp
int32_t Aspose::Slides::Animation::BehaviorPropertyCollection::IndexOf(const System::SharedPtr<IBehaviorProperty> &item) const override
```

### الوسائط

| Parameter | Type | Description |
| --- | --- | --- |
| item | const [System::SharedPtr](../../../system/sharedptr/)\<[IBehaviorProperty](../../ibehaviorproperty/)\>\& | الكائن لتحديد موقعه في [IList](../../../system.collections.generic/ilist/). |

### قيمة الإرجاع

فهرس *item* إذا وجد في القائمة؛ وإلا -1.

## BehaviorPropertyCollection::IndexOf(const System::String\&) const طريقة

يحدد فهرس عنصر محدد بواسطة قيمة الخاصية في [IList](../../../system.collections.generic/ilist/).

```cpp
int32_t Aspose::Slides::Animation::BehaviorPropertyCollection::IndexOf(const System::String &propertyValue) const override
```

### الوسائط

| Parameter | Type | Description |
| --- | --- | --- |
| propertyValue | const [System::String](../../../system/string/)\& | قيمة الخاصية |

### قيمة الإرجاع

فهرس الخاصية ذات القيمة المحددة

## راجع أيضاً

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IBehaviorProperty](../../ibehaviorproperty/)
* فئة [BehaviorPropertyCollection](../)
* فئة [String](../../../system/string/)
* مساحة الاسم [Aspose::Slides::Animation](../../)
* مكتبة [Aspose.Slides](../../../)