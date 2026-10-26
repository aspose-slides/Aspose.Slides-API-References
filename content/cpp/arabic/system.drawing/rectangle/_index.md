---
title: Rectangle
second_title: مرجع API لـ Aspose.Slides للغة C++
description: "يمثل مساحة مستطيلة من صورة معرفة كإحداثيات X و Y صحيحة للزاوية العلوية اليسرى وعرضها وارتفاعها. ينبغي تخصيص هذا النوع على المكدس وتمريره إلى الدوال بالقيمة أو بالمرجع. لا تستخدم أبداً فئة System::SmartPtr لإدارة كائنات هذا النوع."
type: docs
weight: 235
url: /ar/system.drawing/rectangle/
---
## فئة Rectangle

يمثل مساحة مستطيلة من صورة معرفة كإحداثيات X و Y صحيحة للزاوية العلوية اليسرى وعرضها وارتفاعها. ينبغي تخصيص هذا النوع على المكدس وتمريره إلى الدوال بالقيمة أو بالمرجع. لا تستخدم فئة [System::SmartPtr](../../system/smartptr/) لإدارة كائنات هذا النوع.

```cpp
class Rectangle
```

## الأساليب

| الطريقة | الوصف |
| --- | --- |
| static [Rectangle](./) [Ceiling](./ceiling/)(const [RectangleF](../rectanglef/)\&) | ينشئ كائن [Rectangle](./) من الكائن [RectangleF](../rectanglef/) المحدد عن طريق تقريب قيم موقع وحجم الكائن [RectangleF](../rectanglef/) إلى القيم الصحيحة الأعلى. |
| **bool** [Contains](./contains/)(int, int) const | يحدد ما إذا كانت النقطة المحددة تقع داخل المستطيل الممثل بواسطة الكائن الحالي. |
| **bool** [Contains](./contains/)(const [Point](../point/)\&) const | يحدد ما إذا كانت النقطة المحددة تقع داخل المستطيل الممثل بواسطة الكائن الحالي. |
| **bool** [Contains](./contains/)(const [Rectangle](./)\&) const | يحدد ما إذا كان المستطيل المحدد يقع داخل المستطيل الممثل بواسطة الكائن الحالي. |
| **bool** [Equals](./equals/)(const [Rectangle](./)\&) const | يحدد ما إذا كان المستطيلان الممثلان بواسطة الكائن الحالي والكائن المحدد متماثلان. |
| static [Rectangle](./) [FromLTRB](./fromltrb/)(int, int, int, int) | ينشئ كائن [Rectangle](./) جديدًا يمثل مستطيلًا مع مواقع الحواف المحددة. |
| int [get_Bottom](./get_bottom/)() const | يرجع إحداثي y للحد السفلي للمستطيل الممثل بواسطة الكائن الحالي. |
| int [get_Height](./get_height/)() const | يرجع ارتفاع المستطيل الممثل بواسطة الكائن الحالي. |
| **bool** [get_IsEmpty](./get_isempty/)() const | يحدد ما إذا كانت إحداثيات X و Y للزاوية العلوية اليسرى للمستطيل الممثل بواسطة الكائن الحالي وكذلك عرضه وارتفاعه قيمها 0. |
| int [get_Left](./get_left/)() const | يرجع إحداثي X للحافة اليسرى للمستطيل الممثل بواسطة الكائن الحالي. |
| [Point](../point/) [get_Location](./get_location/)() const | يرجع نسخة من فئة [Point](../point/) التي تحدد موقع الزاوية العلوية اليسرى للمستطيل الممثل بواسطة الكائن الحالي. |
| int [get_Right](./get_right/)() const | يرجع إحداثي X للحافة اليمنى للمستطيل الممثل بواسطة الكائن الحالي. |
| [Size](../size/) [get_Size](./get_size/)() const | يرجع نسخة من فئة [Size](../size/) التي تحدد عرض وارتفاع المستطيل الممثل بواسطة الكائن الحالي. |
| int [get_Top](./get_top/)() const | يرجع إحداثي Y للحافة العليا للمستطيل الممثل بواسطة الكائن الحالي. |
| int [get_Width](./get_width/)() const | يرجع عرض المستطيل الممثل بواسطة الكائن الحالي. |
| int [get_X](./get_x/)() const | يرجع إحداثي X للزاوية العلوية اليسرى للمستطيل الممثل بواسطة الكائن الحالي. |
| int [get_Y](./get_y/)() const | يرجع إحداثي Y للزاوية العلوية اليسرى للمستطيل الممثل بواسطة الكائن الحالي. |
| int [GetHashCode](./gethashcode/)() const | يرجع قيمة التجزئة (hash code) للكائن الحالي. |
| void [Inflate](./inflate/)(int, int) | يزيد عرض وارتفاع المستطيل الممثل بواسطة الكائن الحالي، مع الحفاظ على موقع المركز الهندسي للمستطيل. يتم زيادة العرض والارتفاع في الاتجاهين بالمقدار المحدد. |
| void [Inflate](./inflate/)(const [Size](../size/)\&) | يزيد عرض وارتفاع المستطيل الممثل بواسطة الكائن الحالي، مع الحفاظ على موقع المركز الهندسي للمستطيل. يتم زيادة العرض والارتفاع في الاتجاهين بالقيم المحددة بواسطة قيم العرض والارتفاع لكائن الحجم المحدد على النحو المقابل. |
| static [Rectangle](./) [Inflate](./inflate/)(const [Rectangle](./)\&, int, int) | يزيد عرض وارتفاع المستطيل الممثل بواسطة الكائن المحدد، مع الحفاظ على موقع المركز الهندسي للمستطيل. يتم زيادة العرض والارتفاع في كلا الاتجاهين بالمقدار المحدد. |
| void [Intersect](./intersect/)(const [Rectangle](./)\&) | يستبدل المستطيل الممثل بواسطة الكائن الحالي بالمستطيل الناتج عن تقاطعه مع المستطيل الممثل بواسطة الكائن المحدد. |
| static [Rectangle](./) [Intersect](./intersect/)(const [Rectangle](./)\&, const [Rectangle](./)\&) | يرجع مستطيلًا يكون نتيجة تقاطع المستطيلات المحددة. |
| **bool** [IntersectsWith](./intersectswith/)(const [Rectangle](./)\&) | يحدد ما إذا كان المستطيلان الممثلان بواسطة الكائن الحالي والكائن المحدد يتقاطعان. |
| void [Offset](./offset/)(const [Point](../point/)\&) | يُزاح موضع المستطيل الممثل بواسطة الكائن الحالي بالمقادير المحددة. |
| void [Offset](./offset/)(int, int) | يُزاح موضع المستطيل الممثل بواسطة الكائن الحالي بالمقادر المحددة. |
| [operator RectangleF](./operator_rectanglef/)() const | يرجع كائن [RectangleF](../rectanglef/) يمثل مستطيلًا مكافئًا للمستطيل الممثل بواسطة الكائن الحالي. |
| **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const | دائمًا تُعيد true. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | دائمًا تُعيد false. |
| [Rectangle](./rectangle/)() | ينشئ نسخة جديدة من كائن [Rectangle](./) يمثل مستطيلًا بإحداثيات X و Y وعرض وارتفاع مضبوطة على 0. |
| [Rectangle](./rectangle/)(int, int, int, int) | ينشئ نسخة جديدة من كائن [Rectangle](./) يمثل مستطيلًا بالإحداثيات المحددة للزاوية العلوية اليسرى وعرضه وارتفاعه. |
| [Rectangle](./rectangle/)(const [Point](../point/)\&, const [Size](../size/)\&) | ينشئ نسخة جديدة من كائن [Rectangle](./) يمثل مستطيلًا بإحداثيات زاويةه العلوية اليسرى المحددة كنسخة من فئة [Point](../point/) وعرضه وارتفاعه كنسخة من فئة [Size](../size/). |
| [Rectangle](./rectangle/)(const **System::Windows::Forms::Screen::Rectangle_**\&) | ينشئ نسخة جديدة من كائن [Rectangle](./) يمثل المستطيل المكافئ للمعطى. |
| static [Rectangle](./) [Round](./round/)(const [RectangleF](../rectanglef/)\&) | ينشئ كائن [Rectangle](./) من الكائن [RectangleF](../rectanglef/) المحدد عن طريق تقريب قيم موقع وحجم الكائن [RectangleF](../rectanglef/) إلى أقرب قيم صحيحة. |
| void [set_Height](./set_height/)(int) | يضبط ارتفاع المستطيل الممثل بواسطة الكائن الحالي. |
| void [set_Location](./set_location/)([Point](../point/)) | يضبط موقع الزاوية العلوية اليسرى للمستطيل الممثل بواسطة الكائن الحالي. |
| void [set_Size](./set_size/)([Size](../size/)) | يضبط عرض وارتفاع المستطيل الممثل بواسطة الكائن الحالي. |
| void [set_Width](./set_width/)(int) | يضبط عرض المستطيل الممثل بواسطة الكائن الحالي. |
| void [set_X](./set_x/)(int) | يضبط إحداثي X للزاوية العلوية اليسرى للمستطيل الممثل بواسطة الكائن الحالي. |
| void [set_Y](./set_y/)(int) | يضبط إحداثي Y للزاوية العلوية اليسرى للمستطيل الممثل بواسطة الكائن الحالي. |
| [String](../../system/string/) [ToString](./tostring/)() const | يرجع تمثيل النص للكائن الحالي. |
| static [Rectangle](./) [Truncate](./truncate/)(const [RectangleF](../rectanglef/)\&) | ينشئ كائن [Rectangle](./) من الكائن [RectangleF](../rectanglef/) المحدد عن طريق تقليل قيم موقع وحجم الكائن [RectangleF](../rectanglef/) إلى القيم الصحيحة الأدنى. |
| static [Rectangle](./) [Union](./union/)(const [Rectangle](./)\&, const [Rectangle](./)\&) | يرجع مستطيلًا يكون نتيجة اتحاد المستطيلات المحددة. |

## الحقول

| الحقل | الوصف |
| --- | --- |
| static [Empty](./empty/) | مستطيل فارغ أي مستطيل تكون قيم موقعه وحجمه صفرية. |

## أنظر أيضًا

* المجال [System::Drawing](../)
* المكتبة [Aspose.Slides](../../)