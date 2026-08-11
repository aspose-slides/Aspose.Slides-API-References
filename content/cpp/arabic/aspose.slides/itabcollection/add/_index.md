---
title: Add()
second_title: مرجع واجهة برمجة تطبيقات Aspose.Slides لـ C++
description: يضيف علامة تبويب إلى المجموعة.
type: docs
weight: 14
url: /ar/aspose.slides/itabcollection/add/
---
## ITabCollection::Add(double, TabAlignment) طريقة

يضيف [Tab](../../tab/) إلى المجموعة.

```cpp
virtual System::SharedPtr<ITab> Aspose::Slides::ITabCollection::Add(double position, TabAlignment align)=0
```

### المعاملات

| Parameter | Type | Description |
| --- | --- | --- |
| position | **double** | [Tab](../../tab/) الموضع. |
| align | [TabAlignment](../../tabalignment/) | [Tab](../../tab/) محاذاة. |

### قيمة الإرجاع

علامة تبويب مضافة.

## ITabCollection::Add(System::SharedPtr\<ITab\>) طريقة

يضيف [Tab](../../tab/) إلى المجموعة.

```cpp
virtual int32_t Aspose::Slides::ITabCollection::Add(System::SharedPtr<ITab> value)=0
```

### المعاملات

| Parameter | Type | Description |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[ITab](../../itab/)\> | الكائن [Tab](../../tab/) الذي سيُضاف في نهاية المجموعة. |

### قيمة الإرجاع

المؤشر الذي أضيفت إليه علامة التبويب.

## انظر أيضًا

* Enum [TabAlignment](../../tabalignment/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ITab](../../itab/)
* Class [ITabCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)