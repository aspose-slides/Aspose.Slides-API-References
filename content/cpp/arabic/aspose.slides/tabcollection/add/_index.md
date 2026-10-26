---
title: Add()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يضيف علامة تبويب إلى المجموعة.
type: docs
weight: 53
url: /ar/aspose.slides/tabcollection/add/
---
## TabCollection::Add(double, TabAlignment) طريقة

يضيف [Tab](../../tab/) إلى المجموعة.

```cpp
System::SharedPtr<ITab> Aspose::Slides::TabCollection::Add(double position, TabAlignment align) override
```

### قيمة الإرجاع

علامة تبويب مضافة.

## TabCollection::Add(System::SharedPtr\<ITab\>) طريقة

يضيف [Tab](../../tab/) إلى المجموعة.

```cpp
int32_t Aspose::Slides::TabCollection::Add(System::SharedPtr<ITab> value) override
```

### المعطيات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[ITab](../../itab/)\> | الكائن [Tab](../../tab/) الذي سيُضاف في نهاية المجموعة. |

### قيمة الإرجاع

الفهرس الذي تم إضافة العلامة إليه.

## انظر أيضًا

* Enum [TabAlignment](../../tabalignment/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [ITab](../../itab/)
* فئة [TabCollection](../)
* نطاق [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)