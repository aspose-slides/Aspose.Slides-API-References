---
title: Range
second_title: مرجع API لـ Aspose.Slides للغة C++
description: "يمثل نطاقًا بمؤشر بداية ومؤشر نهاية. يجب تخصيص هذا النوع على المكدس وتمريره إلى الدوال بالقيمة أو بالمرجع. لا تستخدم الفئة System::SmartPtr لإدارة كائنات من هذا النوع."
type: docs
weight: 1197
url: /ar/system/range/
---
## فئة النطاق

يمثل نطاقًا بمؤشر بداية ومؤشر نهاية. يجب تخصيص هذا النوع على المكدس وتمريره إلى الدوال بالقيمة أو بالمرجع. لا تستخدم فئة [System::SmartPtr](../smartptr/) لإدارة كائنات من هذا النوع.

```cpp
class Range : public System::Details::BoxableObjectBase
```

## طرق

| طريقة | الوصف |
| --- | --- |
| static constexpr [Range](./) [EndAt](./endat/)(const [Index](../index/)\&) | ينشئ نطاقًا يبدأ من بداية المجموعة وينتهي عند الفهرس النهائي المحدد. |
| **bool** [Equals](./equals/)(const [Range](./)\&) const | يحدد ما إذا كان النطاق الحالي مساويًا للنطاق المحدد. |
| static constexpr [Range](./) [get_All](./get_all/)() | يُرجِع [Range](./) الذي يمثل المجموعة بأكملها. |
| const [Index](../index/)\& [get_End](./get_end/)() const | يحصل على الفهرس End. |
| const [Index](../index/)\& [get_Start](./get_start/)() const | يحصل على الفهرس Start. |
| **int32_t** [GetHashCode](./gethashcode/)() const | يُرجِع قيمة تجزئة للنطاق الحالي. |
| [System::ValueTuple](../valuetuple/)\<**int32_t**, **int32_t**\> [GetOffsetAndLength](./getoffsetandlength/)(**int32_t**) const | يحسب إزاحة البداية المستندة إلى الصفر والطول للطول المحدد للمجموعة. |
| constexpr [Range](./range/)() | يبني نطاقًا فارغًا. |
| constexpr [Range](./range/)(const [Index](../index/)\&, const [Index](../index/)\&) | يبني [Range](./) من الفهارس البداية والنهاية المحددة. |
| static constexpr [Range](./) [StartAt](./startat/)(const [Index](../index/)\&) | ينشئ نطاقًا يبدأ من الفهرس البداية المحدد ويمتد إلى نهاية المجموعة. |

## راجع أيضًا

* المجال [System](../)
* المكتبة [Aspose.Slides](../../)