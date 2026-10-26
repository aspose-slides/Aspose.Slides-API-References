---
title: BitVector32
second_title: مرجع API الخاص بـ Aspose.Slides للغة C++
description: يوفر متجه بتات بسيط وخفيف مع وصول سهل إلى عدد صحيح أو بولي إلى مساحة تخزين بحجم 32 بت.
type: docs
weight: 1
url: /ar/system.collections.specialized/bitvector32/
---
## BitVector32 الفئة

يوفر متجه بتات بسيط وخفيف مع وصول سهل إلى عدد صحيح أو [Boolean](../../system/boolean/) إلى سعة 32 بت.

```cpp
class BitVector32
```

## الأساليب

| الطريقة | الوصف |
| --- | --- |
|  [BitVector32](./bitvector32/)() | يقوم بإنشاء نسخة جديدة فارغة من [BitVector32](./). |
|  [BitVector32](./bitvector32/)(**int32_t**) | يقوم بإنشاء نسخة جديدة من بنية [BitVector32](./) مع البيانات الداخلية المحددة. |
|  [BitVector32](./bitvector32/)(const [BitVector32](./)\&) | يقوم بإنشاء نسخة جديدة من بنية [BitVector32](./) بالمعلومات الموجودة في القيمة المحددة. |
| static **int32_t** [CreateMask](./createmask/)() | ينشئ القناع الأول في سلسلة. |
| static **int32_t** [CreateMask](./createmask/)(**int32_t**) | ينشئ القناع التالي في سلسلة. |
| static **BitVector32::Section** [CreateSection](./createsection/)(**int16_t**) | ينشئ القسم الأول في سلسلة، بالقيمة القصوى المحددة. |
| static **BitVector32::Section** [CreateSection](./createsection/)(**int16_t**, **BitVector32::Section**) | ينشئ القسم التالي في سلسلة، بالقيمة القصوى المحددة. |
| **bool** [Equals](./equals/)(const [BitVector32](./)\&) | يحدد ما إذا كان الكائن المحدد هو نفسه الحالي. |
| **int32_t** [get_Data](./get_data/)() | يرجع البيانات الخام المخزنة في هذا المتجه البت... |
| **int32_t** [GetHashCode](./gethashcode/)() const | يرجع رمز تجزئة للكائن الحالي. |
| **bool** [idx_get](./idx_get/)(**int32_t**) | يحصل على قيمة تشير إلى ما إذا كانت جميع البتات المحددة مفعلة. |
| **int32_t** [idx_get](./idx_get/)(**BitVector32::Section**) | يحصل على القيمة للقسم المحدد. |
| void [idx_set](./idx_set/)(**int32_t**, **bool**) | يضبط قيمة تشير إلى ما إذا كانت جميع البتات المحددة مفعلة. |
| void [idx_set](./idx_set/)(**BitVector32::Section**, **int32_t**) | يضبط القيمة للقسم المحدد. |
| static [String](../../system/string/) [ToString](./tostring/)(const [BitVector32](./)\&) | يحوله القيمة الممثلة بواسطة معلمة القيمة إلى سلسلة. |
| [String](../../system/string/) [ToString](./tostring/)() const | يحول القيمة الممثلة بالكائن الحالي إلى سلسلة. |

## انظر أيضًا

* النطاق [System::Collections::Specialized](../)
* المكتبة [Aspose.Slides](../../)