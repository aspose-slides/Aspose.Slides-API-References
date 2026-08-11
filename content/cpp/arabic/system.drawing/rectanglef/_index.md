---
title: RectangleF
second_title: مرجع API لـ Aspose.Slides للغة C++
description: "يمثل مساحة مستطيلة في صورة معرفة بإحداثيات X و Y ذات دقة أحادية للزاوية العلوية اليسرى وعرضها وارتفاعها. يجب تخصيص هذا النوع على المكدس وتمريره إلى الدوال بالقيمة أو بالمرجع. لا تستخدم فئة System::SmartPtr لإدارة كائنات هذا النوع."
type: docs
weight: 248
url: /ar/system.drawing/rectanglef/
---
## RectangleF فئة

Represents a rectangular area of an image defined as single-precision floating point X and Y coordinates of its upper left corner and its width and height. This type should be allocated on stack and passed to functions by value or by reference. Never use [System::SmartPtr](../../system/smartptr/) الفئة to manage objects of this type.

```cpp
class RectangleF
```

## الطرق

| طريقة | وصف |
| --- | --- |
| **bool** [Contains](./contains/)(**float**, **float**) | يحدد ما إذا كانت النقطة المحددة تقع داخل المستطيل المُمثل بالكائن الحالي. |
| **bool** [Contains](./contains/)(const [PointF](../pointf/)\&) | يحدد ما إذا كانت النقطة المحددة تقع داخل المستطيل المُمثل بالكائن الحالي. |
| **bool** [Contains](./contains/)(const [RectangleF](./)\&) | يحدد ما إذا كان المستطيل المحدد يقع داخل المستطيل المُمثل بالكائن الحالي. |
| **bool** [Equals](./equals/)(const [RectangleF](./)\&) const | يحدد ما إذا كان المستطيلان المُمثلان بالكائن الحالي والكائن المحدد متماثلان. |
| static [RectangleF](./) [FromLTRB](./fromltrb/)(**float**, **float**, **float**, **float**) | يبني كائن [RectangleF](./) جديد يمثل مستطيلًا بمواقع الحواف المحددة. |
| **float** [get_Bottom](./get_bottom/)() const | يعيد إحداثي y للحافة السفلية للمستطيل المُمثل بالكائن الحالي. |
| **float** [get_Height](./get_height/)() const | يعيد ارتفاع المستطيل المُمثل بالكائن الحالي. |
| **bool** [get_IsEmpty](./get_isempty/)() const | يحدد ما إذا كانت إحداثيات X وY للزاوية العلوية اليسرى للمستطيل المُمثل بالكائن الحالي بالإضافة إلى عرضه وارتفاعه تساوي 0. |
| **float** [get_Left](./get_left/)() const | يعيد إحداثي X للحافة اليسرى للمستطيل المُمثل بالكائن الحالي. |
| [PointF](../pointf/) [get_Location](./get_location/)() const | يعيد نسخة من الفئة [PointF](../pointf/) التي تحدد موقع الزاوية العلوية اليسرى للمستطيل المُمثل بالكائن الحالي. |
| **float** [get_Right](./get_right/)() const | يعيد إحداثي X للحافة اليمنى للمستطيل المُمثل بالكائن الحالي. |
| [SizeF](../sizef/) [get_Size](./get_size/)() const | يعيد نسخة من الفئة [SizeF](../sizef/) التي تحدد عرض وارتفاع المستطيل المُمثل بالكائن الحالي. |
| **float** [get_Top](./get_top/)() const | يعيد إحداثي Y للحافة العليا للمستطيل المُمثل بالكائن الحالي. |
| **float** [get_Width](./get_width/)() const | يعيد عرض المستطيل المُمثل بالكائن الحالي. |
| **float** [get_X](./get_x/)() const | يعيد إحداثي X للزاوية العلوية اليسرى للمستطيل المُمثل بالكائن الحالي. |
| **float** [get_Y](./get_y/)() const | يعيد إحداثي Y للزاوية العلوية اليسرى للمستطيل المُمثل بالكائن الحالي. |
| int [GetHashCode](./gethashcode/)() const | يعيد رمز تجزئة للكائن الحالي. |
| void [Inflate](./inflate/)(**float**, **float**) | يزيد عرض وارتفاع المستطيل المُمثل بالكائن الحالي، مع الحفاظ على موقع المركز الهندسي للمستطيل. يتم زيادة العرض والارتفاع في الاتجاهين بالمقدار المحدد. |
| void [Inflate](./inflate/)(const [SizeF](../sizef/)\&) | يزيد عرض وارتفاع المستطيل المُمثل بالكائن الحالي، مع الحفاظ على موقع المركز الهندسي للمستطيل. يتم زيادة العرض والارتفاع في الاتجاهين بالمقابل للقيم المحددة للعرض والارتفاع في كائن الحجم المحدد. |
| static [RectangleF](./) [Inflate](./inflate/)(const [RectangleF](./)\&, **float**, **float**) | يزيد عرض وارتفاع المستطيل المُمثل بالكائن المحدد، مع الحفاظ على موقع المركز الهندسي للمستطيل. يتم زيادة العرض والارتفاع في الاتجاهين بالمقدار المحدد. |
| void [Intersect](./intersect/)(const [RectangleF](./)\&) | يستبدل المستطيل المُمثل بالكائن الحالي بالمستطيل الناتج عن تقاطعه مع المستطيل المُمثل بالكائن المحدد. |
| static [RectangleF](./) [Intersect](./intersect/)(const [RectangleF](./)\&, const [RectangleF](./)\&) | يعيد مستطيلًا يكون نتيجة تقاطع المستطيلات المحددة. |
| **bool** [IntersectsWith](./intersectswith/)(const [RectangleF](./)\&) | يحدد ما إذا كان المستطيلان المُمثلان بالكائن الحالي والكائن المحدد يتقاطعان. |
| void [Offset](./offset/)(const [PointF](../pointf/)\&) | يُزاح موقع المستطيل المُمثل بالكائن الحالي بالمقدارات المحددة. |
| void [Offset](./offset/)(**float**, **float**) | يُزاح موقع المستطيل المُمثل بالكائن الحالي بالمقدارات المحددة. |
| **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const | دائمًا ما يُعيد true. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | دائمًا ما يُعيد false. |
| [RectangleF](./rectanglef/)() | يبني نسخة جديدة من كائن [RectangleF](./) يمثل مستطيلًا بإحداثيات X وY وعرض وارتفاع مُعدة إلى 0. |
| [RectangleF](./rectanglef/)(**float**, **float**, **float**, **float**) | يبني نسخة جديدة من كائن [RectangleF](./) يمثل مستطيلًا بالإحداثيات المحددة للزاوية العلوية اليسرى وعرض وارتفاع. |
| [RectangleF](./rectanglef/)(const [PointF](../pointf/)\&, const [SizeF](../sizef/)\&) | يبني نسخة جديدة من كائن [RectangleF](./) يمثل مستطيلًا بإحداثيات الزاوية العلوية اليسرى المحددة كنسخة من الفئة [PointF](../pointf/) وعرضه وارتفاعه كنسخة من الفئة [SizeF](../sizef/). |
| explicit  [RectangleF](./rectanglef/)(const [Rectangle](../rectangle/)\&) | يبني نسخة جديدة من كائن [RectangleF](./) يمثل المستطيل المكافئ للمستطيل المحدد. |
| void [set_Height](./set_height/)(**float**) | يعين ارتفاع المستطيل المُمثل بالكائن الحالي. |
| void [set_Location](./set_location/)([PointF](../pointf/)) | يعين موقع الزاوية العلوية اليسرى للمستطيل المُمثل بالكائن الحالي. |
| void [set_Size](./set_size/)([SizeF](../sizef/)) | يعين عرض وارتفاع المستطيل المُمثل بالكائن الحالي. |
| void [set_Width](./set_width/)(**float**) | يعين عرض المستطيل المُمثل بالكائن الحالي. |
| void [set_X](./set_x/)(**float**) | يعين إحداثي X للزاوية العلوية اليسرى للمستطيل المُمثل بالكائن الحالي. |
| void [set_Y](./set_y/)(**float**) | يعين إحداثي Y للزاوية العلوية اليسرى للمستطيل المُمثل بالكائن الحالي. |
| [System::String](../../system/string/) [ToString](./tostring/)() const | يعيد تمثيل النص للكائن الحالي. |
| static [RectangleF](./) [Union](./union/)(const [RectangleF](./)\&, const [RectangleF](./)\&) | يعيد مستطيلًا يكون نتيجة اتحاد المستطيلات المحددة. |

## الحقول

| حقل | وصف |
| --- | --- |
| static [Empty](./empty/) | مستطيل فارغ أي مستطيل تكون قيم موقعه وحجمه صفرًا. |

## انظر أيضًا

* النطاق [System::Drawing](../)
* المكتبة [Aspose.Slides](../../)