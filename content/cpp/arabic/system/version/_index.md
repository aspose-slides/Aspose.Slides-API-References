---
title: Version
second_title: مرجع API لـ Aspose.Slides للغة C++
description: "يمثل رقم إصدار. يجب تخصيص هذا النوع على المكدس وتمريره إلى الدوال بالقيمة أو بالمرجع. لا تستخدم أبداً الفئة System::SmartPtr لإدارة كائنات من هذا النوع."
type: docs
weight: 1470
url: /ar/system/version/
---
## Version فئة


يمثل رقم إصدار. يجب تخصيص هذا النوع على المكدس وتمريره إلى الدوال بالقيمة أو بالمرجع. لا تستخدم الفئة [System::SmartPtr](../smartptr/) لإدارة كائنات من هذا النوع.

```cpp
class Version
```

## الطرق

| طريقة | الوصف |
| --- | --- |
| int [CompareTo](./compareto/)(const [Version](./)\&) const | يقارن الإصدارات التي يمثلها الكائن الحالي والكائن المحدد. |
| **bool** [Equals](./equals/)(const [Version](./)\&) const | يحدد ما إذا كانت أرقام الإصدار التي يمثلها الكائنان الحالي والمحدد متساوية. |
| int [get_Build](./get_build/)() const | يعيد رقم البناء. |
| int [get_Major](./get_major/)() const | يعيد الإصدار الرئيسي. |
| **int16_t** [get_MajorRevision](./get_majorrevision/)() const | يعيد القيمة العليا ذات 16 بت لرقم المراجعة. |
| int [get_Minor](./get_minor/)() const | يعيد الإصدار الفرعي. |
| **int16_t** [get_MinorRevision](./get_minorrevision/)() const | يعيد القيمة السفلى ذات 16 بت لرقم المراجعة. |
| int [get_Revision](./get_revision/)() const | يعيد رقم المراجعة. |
| int [GetHashCode](./gethashcode/)() const | يعيد رمز تجزئة للكائن الحالي. |
| static [Version](./) [Parse](./parse/)(const [String](../string/)\&) | يحوّل تمثيل النص لرقم إصدار إلى نسخة مكافئة من الفئة [Version](./). |
| [String](../string/) [ToString](./tostring/)() const | يعيد تمثيل النص لرقم الإصدار الذي يمثله الكائن الحالي. |
| [String](../string/) [ToString](./tostring/)(int) const | يعيد تمثيل النص للعدد المحدد من أقسام رقم الإصدار الذي يمثله الكائن الحالي. |
|  [Version](./version/)(int, int, int, int) | ينشئ نسخة تمثل القيم المحددة للنسخة الرئيسية والفرعية والبناء والمراجعة. |
|  [Version](./version/)(int, int, int) | ينشئ نسخة تمثل القيم المحددة للنسخة الرئيسية والفرعية والبناء. |
|  [Version](./version/)(int, int) | ينشئ نسخة تمثل القيم المحددة للنسخة الرئيسية والقيم. |
|  [Version](./version/)(const [String](../string/)\&) | ينشئ نسخة تمثل رقم الإصدار الممثل كنص. |
|  [Version](./version/)() | ينشئ نسخة تمثل رقم الإصدار 0.0.-1.-1. |
## راجع أيضًا

* النطاق [System](../)
* المكتبة [Aspose.Slides](../../)