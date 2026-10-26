---
title: CharacterRange
second_title: "مرجع API لـ Aspose.Slides للغة C++"
description: "يمثل نطاقًا من مواضع الأحرف في سلسلة. يجب تخصيص هذا النوع على المكدس وتمريره إلى الدوال بالقيمة أو بالمرجع. لا تستخدم أبداً فئة System::SmartPtr لإدارة كائنات هذا النوع."
type: docs
weight: 40
url: /ar/system.drawing/characterrange/
---
## CharacterRange فئة

يمثل مجموعة من مواضع الأحرف في سلسلة. يجب تخصيص هذا النوع على المكدس وتمريره إلى الدوال بالقيمة أو بالمرجع. لا تستخدم أبداً فئة [System::SmartPtr](../../system/smartptr/) لإدارة كائنات هذا النوع.

```cpp
class CharacterRange
```

## الطرق

| طريقة | الوصف |
| --- | --- |
|  [CharacterRange](./characterrange/)(**int32_t**, **int32_t**) | ينشئ نسخة جديدة من فئة [CharacterRange](./) تمثل النطاق المحدد. |
|  [CharacterRange](./characterrange/)() | ينشئ نسخة جديدة من فئة [CharacterRange](./) تمثل نطاقًا فارغًا. |
| **int32_t** [get_First](./get_first/)() const | إرجاع موقع الحرف الأول للنطاق الممثَّل بواسطة الكائن الحالي. |
| **int32_t** [get_Length](./get_length/)() const | إرجاع عدد الأحرف في النطاق الممثَّل بواسطة الكائن الحالي. |
| **bool** [operator!=](./operator_not_equal/)(const [CharacterRange](./)\&) const | يحدد ما إذا كان الكائنان الحالي والمحدد يمثلان نطاقات مختلفة. |
| **bool** [operator==](./operator_equal_equal/)(const [CharacterRange](./)\&) const | يحدد ما إذا كان الكائنان الحالي والمحدد يمثلان نفس النطاق. |
| void [set_First](./set_first/)(**int32_t**) | يضبط موقع الحرف الأول للنطاق الممثَّل بواسطة الكائن الحالي. |
| void [set_Length](./set_length/)(**int32_t**) | إرجاع عدد الأحرف في النطاق الممثَّل بواسطة الكائن الحالي. |

## انظر أيضًا

* النطاق [System::Drawing](../)
* المكتبة [Aspose.Slides](../../)