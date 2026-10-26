---
title: IndexOf()
second_title: Aspose.Slides برای API مرجع C++
description: اندیس یک مورد خاص را در IList تعیین می‌کند.
type: docs
weight: 40
url: /fa/aspose.slides.animation/behaviorpropertycollection/indexof/
---
## BehaviorPropertyCollection::IndexOf(const System::SharedPtr\<IBehaviorProperty\>\&) const متد

اندیس یک مورد خاص را در [IList](../../../system.collections.generic/ilist/) تعیین می‌کند.

```cpp
int32_t Aspose::Slides::Animation::BehaviorPropertyCollection::IndexOf(const System::SharedPtr<IBehaviorProperty> &item) const override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| item | const [System::SharedPtr](../../../system/sharedptr/)\<[IBehaviorProperty](../../ibehaviorproperty/)\>\& | شیء‌ای که باید در [IList](../../../system.collections.generic/ilist/) پیدا شود. |

### مقدار بازگشت

اندیس *item* اگر در لیست یافت شود؛ در غیر این صورت -1.

## BehaviorPropertyCollection::IndexOf(const System::String\&) const متد

اندیس یک مورد خاص را بر اساس مقدار ویژگی در [IList](../../../system.collections.generic/ilist/) تعیین می‌کند.

```cpp
int32_t Aspose::Slides::Animation::BehaviorPropertyCollection::IndexOf(const System::String &propertyValue) const override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| propertyValue | const [System::String](../../../system/string/)\& | مقدار ویژگی |

### مقدار بازگشت

اندیس ویژگی با مقدار مشخص‌شده

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [IBehaviorProperty](../../ibehaviorproperty/)
* کلاس [BehaviorPropertyCollection](../)
* کلاس [String](../../../system/string/)
* فضای نام [Aspose::Slides::Animation](../../)
* کتابخانه [Aspose.Slides](../../../)