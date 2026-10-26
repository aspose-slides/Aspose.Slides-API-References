---
title: PointF
second_title: مرجع API لـ Aspose.Slides للغة C++
description: "يمثل زوجًا من إحداثيات X و Y بنقطة عائمة ذات دقة أحادية على سطح ثنائي الأبعاد. يجب تخصيص هذا النوع على المكدس وتمريره إلى الدوال بالقيمة أو بالمرجع. لا تستخدم أبدًا فئة System::SmartPtr لإدارة الكائنات من هذا النوع."
type: docs
weight: 222
url: /ar/system.drawing/pointf/
---
## PointF فئة

يمثل زوجًا من إحداثيات X و Y بنقطة عائم ذات دقة أحادية للمنطقة ذات بعدين. يجب تخصيص هذا النوع على المكدس وتمريره إلى الدوال بالقيمة أو بالمرجع. لا تستخدم [System::SmartPtr](../../system/smartptr/) فئة لإدارة الكائنات من هذا النوع.

```cpp
class PointF
```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| static [PointF](./) [Add](./add/)(const [PointF](./)\&, const [SizeF](../sizef/)\&) | يضيف قيم عرض وارتفاع الكائن [SizeF](../sizef/) المحدد إلى قيم إحداثيات X و Y للكائن [PointF](./) المحدد على التوالي. |
| static [PointF](./) [Add](./add/)(const [PointF](./)\&, const [Size](../size/)\&) | يضيف قيم عرض وارتفاع الكائن [Size](../size/) المحدد إلى قيم إحداثيات X و Y للكائن [PointF](./) المحدد على التوالي. |
| **bool** [Equals](./equals/)(const [PointF](./)\&) const | يحدد ما إذا كان الكائن الحالي والكائن المحدد متساويين، أي يمثلان نفس زوج قيم إحداثيات X و Y. |
| **bool** [get_IsEmpty](./get_isempty/)() const | يحدد ما إذا كانت قيم إحداثيات X و Y كلاهما مساوية للصفر. |
| **float** [get_X](./get_x/)() const | يعيد قيمة إحداثية X التي يمثلها الكائن الحالي. |
| **float** [get_Y](./get_y/)() const | يعيد قيمة إحداثية Y التي يمثلها الكائن الحالي. |
| int [GetHashCode](./gethashcode/)() const | يعيد قيمة تجزئة (hash code) للكائن الحالي. |
| **bool** [IsNull](./isnull/)() const | دائمًا يرجع false. |
| explicit  [operator bool](./operator_bool/)() | دائمًا يرجع true. |
|  [PointF](./pointf/)() | ينشئ كائنًا جديدًا من النوع [PointF](./) ويُهيئ قيم إحداثيات X و Y إلى 0. |
|  [PointF](./pointf/)(**float**, **float**) | ينشئ كائنًا جديدًا من النوع [PointF](./) ويُهيئه بالقيم المحددة. |
|  [PointF](./pointf/)(const [SizeF](../sizef/)\&) | ينشئ كائنًا جديدًا من النوع [PointF](./) ويُهيئ قيم إحداثيات X و Y بقيم العرض والارتفاع للكائن [SizeF](../sizef/) المحدد على التوالي. |
| void [set_X](./set_x/)(**float**) | يضبط قيمة إحداثية X التي يمثلها الكائن الحالي. |
| void [set_Y](./set_y/)(**float**) | يضبط قيمة إحداثية Y التي يمثلها الكائن الحالي. |
| static [PointF](./) [Subtract](./subtract/)(const [PointF](./)\&, const [SizeF](../sizef/)\&) | يطرح قيم عرض وارتفاع الكائن [SizeF](../sizef/) المحدد من قيم إحداثيات X و Y للكائن [PointF](./) المحدد على التوالي. |
| static [PointF](./) [Subtract](./subtract/)(const [PointF](./)\&, const [Size](../size/)\&) | يطرح قيم عرض وارتفاع الكائن [Size](../size/) المحدد من قيم إحداثيات X و Y للكائن [PointF](./) المحدد على التوالي. |
| [System::String](../../system/string/) [ToString](./tostring/)() const | يعيد تمثيل السلسلة (string) للزوج من قيم إحداثيات X و Y التي يمثلها الكائن الحالي. |

## الحقول

| الحقل | الوصف |
| --- | --- |
| static [Empty](./empty/) | مثال فارغ من [PointF](./) فئة تكون قيم إحداثيات X و Y فيه 0. |

## انظر أيضًا

* النطاق [System::Drawing](../)
* المكتبة [Aspose.Slides](../../)