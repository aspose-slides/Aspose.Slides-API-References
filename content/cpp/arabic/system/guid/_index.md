---
title: Guid
second_title: دليل واجهة برمجة التطبيقات Aspose.Slides للغة C++
description: "يمثّل معرفًا فريدًا عالميًا. يجب تخصيص هذا النوع على المكدس وتمريره إلى الدوال بالقيمة أو بالمرجع. لا تستخدم أبدًا فئة System::SmartPtr لإدارة كائنات هذا النوع."
type: docs
weight: 885
url: /ar/system/guid/
---
## فئة Guid

يمثّل معرفًا فريدًا عالميًا. يجب تخصيص هذا النوع على المكدس وتمريره إلى الدوال بالقيمة أو بالمرجع. لا تستخدم أبدًا الفئة [System::SmartPtr](../smartptr/) لإدارة كائنات هذا النوع.

```cpp
class Guid
```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| int [CompareTo](./compareto/)(const [Guid](./)\&) const | يُجري مقارنة حسابية بين الـ GUIDs التي تمثلها الكائنات الحالية والمحددة. |
| **bool** [Equals](./equals/)(const [Guid](./)\&) const | يحدد ما إذا كانت الـ GUIDs التي تمثلها الكائنات الحالية والمحددة متساوية. |
| int [GetHashCode](./gethashcode/)() const | يرجع رمز تجزئة للكائن الحالي. |
|  [Guid](./guid/)() | ينشئ كائنًا يمثل GUID يتكون من جميع الأصفار. |
|  [Guid](./guid/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&) | ينشئ كائنًا يمثل GUID محدد كمصفوفة من القيم الصحيحة غير الموقعة ذات ٨ بت. |
|  [Guid](./guid/)(const System::Details::ArrayView\<**uint8_t**\>\&) | ينشئ كائنًا يمثل GUID محدد كعرض لمصفوفة من القيم الصحيحة غير الموقعة ذات ٨ بت. |
|  [Guid](./guid/)(const [String](../string/)\&) | ينشئ كائنًا يمثل GUID محدد كسلسلة. |
|  [Guid](./guid/)(**int32_t**, **int16_t**, **int16_t**, const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&) | ينشئ مثالًا من الفئة [Guid](./) من مكونات الـ GUID المحددة. |
|  [Guid](./guid/)(**int32_t**, **int16_t**, **int16_t**, const System::Details::ArrayView\<**uint8_t**\>\&) | ينشئ مثالًا من الفئة [Guid](./) من مكونات الـ GUID المحددة. |
|  [Guid](./guid/)(**int32_t**, **int16_t**, **int16_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**) | ينشئ مثالًا من الفئة [Guid](./) من الأعداد الصحيحة غير الموقعة والبايتات المحددة. |
|  [Guid](./guid/)(**uint32_t**, **uint16_t**, **uint16_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**) | ينشئ مثالًا من الفئة [Guid](./) من الأعداد الصحيحة غير الموقعة والبايتات المحددة. |
|  [Guid](./guid/)(const [Guid](./)\&) | ينشئ كائنًا يمثل نفس الـ GUID مثل الكائن المحدد. |
| static [Guid](./) [NewGuid](./newguid/)() | يولد GUID جديدًا ويرجع كائن [Guid](./) الذي يمثل ذلك. |
| **bool** [operator!=](./operator_not_equal/)(const [Guid](./)\&) const | يحدد ما إذا كانت الـ GUIDs التي تمثلها الكائنات الحالية والمحددة غير متساوية. |
| [Guid](./)\& [operator=](./operator_equal/)(const [Guid](./)\&) | يعين للكائن الحالي قيمة الـ GUID التي يمثلها الكائن [Guid](./) المحدد. |
| **bool** [operator==](./operator_equal_equal/)(const [Guid](./)\&) const | يحدد ما إذا كانت الـ GUIDs التي تمثلها الكائنات الحالية والمحددة متساوية. |
| static [Guid](./) [Parse](./parse/)(const [String](../string/)\&) | يحوّل تمثيل السلسلة المحدد لِـ GUID إلى كائن [Guid](./) مكافئ. |
| [ArrayPtr](../arrayptr/)\<**uint8_t**\> [ToByteArray](./tobytearray/)() const | يحوّل الـ GUID الذي يمثله الكائن الحالي إلى مصفوفة من البايتات. |
| [String](../string/) [ToString](./tostring/)() const | يحوّل الـ GUID الذي يمثله الكائن الحالي إلى تمثيله كسلسلة. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&) const | يحوّل الـ GUID الذي يمثله الكائن الحالي إلى تمثيله كسلسلة باستخدام تنسيق السلسلة المحدد. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const | يحوّل الـ GUID الذي يمثله الكائن الحالي إلى تمثيله كسلسلة باستخدام تنسيق السلسلة المحدد والثقافة. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Guid](./)\&) | يحاول تحويل السلسلة المحددة إلى كائن [Guid](./). |
|  [~Guid](./~guid/)() | المدمر. |

## الحقول

| الحقل | الوصف |
| --- | --- |
| static [Empty](./empty/) | يمثّل GUID له قيمة 0. |

## انظر أيضًا

* مساحة الاسم [System](../)
* المكتبة [Aspose.Slides](../../)