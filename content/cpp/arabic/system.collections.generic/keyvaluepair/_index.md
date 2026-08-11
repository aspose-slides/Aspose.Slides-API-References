---
title: KeyValuePair
second_title: مرجع واجهة برمجة التطبيقات Aspose.Slides للغة C++
description: "زوج من المفتاح والقيمة. يجب تخصيص هذا النوع على المكدس وتمريره إلى الدوال بالقيمة أو بالمرجع. لا تستخدم الفئة System::SmartPtr لإدارة كائنات هذا النوع."
type: docs
weight: 378
url: /ar/system.collections.generic/keyvaluepair/
---
## فئة KeyValuePair

زوج من المفتاح والقيمة. يجب تخصيص هذا النوع على المكدس وتمريره إلى الدوال بالقيمة أو بالمرجع. لا تستخدم فئة [System::SmartPtr](../../system/smartptr/) لإدارة كائنات هذا النوع.

```cpp
template<typename TKey,typename TValue>class KeyValuePair
```

## الطرق

| طريقة | الوصف |
| --- | --- |
| const TKey\& [get_Key](./get_key/)() const | يُعيد المفتاح. |
| const TValue\& [get_Value](./get_value/)() const | يُعيد القيمة. |
| int [GetHashCode](./gethashcode/)() const | يحسب تجزئة (hash) زوج المفتاح-القيمة عن طريق XOR لتجزئات المفتاح والقيمة. |
| **bool** [IsNull](./isnull/)() const | دائمًا يُعيد false. |
|  [KeyValuePair](./keyvaluepair/)() | مُهيئ زوج المفتاح-القيمة الفارغ. |
|  [KeyValuePair](./keyvaluepair/)(const TKey\&, const TValue\&) | منشئ. |
|  [KeyValuePair](./keyvaluepair/)(const std::pair\<OtherK, OtherV\>\&) | منشئ تحويل النوع. |
| **bool** [operator<](./operator_less/)(const [KeyValuePair](./)\&) const | إصلاح للفئات الموروثة من IComparer<KeyValuePair<TKey, TValue>>، لا يقارن شيئًا. |
| [String](../../system/string/) [ToString](./tostring/)() const | يحوِّل زوج المفتاح-القيمة إلى سلسلة. |

## انظر أيضًا

* النطاق [System::Collections::Generic](../)
* المكتبة [Aspose.Slides](../../)