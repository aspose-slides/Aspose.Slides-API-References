---
title: MathArray class
second_title: Aspose.Slides للغة Python عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides.mathtext/matharray/
---
## MathArray فئة

يحدد مصفوفة رأسية من المعادلات أو أي كائنات رياضية

**Inheritance:**[`MathArray`](/slides/python-net/ar/aspose.slides.mathtext/matharray) → [`MathElementBase`](/slides/python-net/ar/aspose.slides.mathtext/mathelementbase)

يعرض نوع MathArray الأعضاء التالية:

## المنشئات

| Constructor | Description |
| :- | :- |
| [`__init__(self, element)`](/slides/python-net/ar/aspose.slides.mathtext/matharray/__init__/#imathelement) | ينشئ مصفوفة رياضية ويضع العنصر المحدد فيها |
| [`__init__(self, elements)`](/slides/python-net/ar/aspose.slides.mathtext/matharray/__init__/#iterableimathelement) |  |

## الخصائص

| Property | Description |
| :- | :- |
| [`arguments`](/slides/python-net/ar/aspose.slides.mathtext/matharray/arguments/) | مجموعة عناصر المصفوفة |
| [`base_justification`](/slides/python-net/ar/aspose.slides.mathtext/matharray/base_justification/) | يحدد محاذاة المصفوفة بالنسبة للنص المحيط<br/>            يمكن محاذاة النص خارج المصفوفة إلى الأسفل أو الأعلى أو وسط كائن المصفقة.<br/>            القيمة الافتراضية: الوسط |
| [`maximum_distribution`](/slides/python-net/ar/aspose.slides.mathtext/matharray/maximum_distribution/) | التوزيع الأقصى<br/>            عندما يكون true، يتم توزيع المصفوفة لتملأ الحد الأقصى لعرض العنصر الحاوي (صفحة، عمود، خلية، إلخ). |
| [`object_distribution`](/slides/python-net/ar/aspose.slides.mathtext/matharray/object_distribution/) | توزيع الكائن<br/>            عندما يكون true، يتم توزيع محتويات المصفوفة لتملأ الحد الأقصى لعرض كائن المصفوفة. |
| [`row_spacing_rule`](/slides/python-net/ar/aspose.slides.mathtext/matharray/row_spacing_rule/) | نوع التباعد العمودي بين عناصر المصفوفة<br/>            الافتراضي: SingleLineGap |
| [`row_spacing`](/slides/python-net/ar/aspose.slides.mathtext/matharray/row_spacing/) | التباعد بين صفوف المصفوفة<br/>            يُستخدم فقط عندما تكون RowSpacingRule مضبوطة على 3 Exactly حيث تكون وحدة القياس نقطًا <br/>            أو Multiple حيث تكون وحدة القياس نصف سطر.<br/>            الافتراضي: 0 |

## الطرق

| Method | Description |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/ar/aspose.slides.mathtext/matharray/join/#imathelement) | يجمع عنصرًا رياضيًا ويشكل كتلة رياضية |
| [`join(self, math_text)`](/slides/python-net/ar/aspose.slides.mathtext/matharray/join/#str) | يجمع نصًا رياضيًا ويشكل كتلة رياضية |
| [`divide(self, denominator)`](/slides/python-net/ar/aspose.slides.mathtext/matharray/divide/#imathelement) | ينشئ كسرًا باستخدام هذا البسط والمقام المحدد |
| [`divide(self, denominator)`](/slides/python-net/ar/aspose.slides.mathtext/matharray/divide/#str) | ينشئ كسرًا باستخدام هذا البسط والمقام المحدد |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/ar/aspose.slides.mathtext/matharray/divide/#imathelement-mathfractiontypes) | ينشئ كسرًا من النوع المحدد باستخدام هذا البسط والمقام المحدد |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/ar/aspose.slides.mathtext/matharray/divide/#str-mathfractiontypes) | ينشئ كسرًا من النوع المحدد باستخدام هذا البسط والمقام المحدد |
| [`enclose(self)`](/slides/python-net/ar/aspose.slides.mathtext/matharray/enclose/#) | يضع العنصر الرياضي بين قوسين |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/ar/aspose.slides.mathtext/matharray/enclose/#char-char) | يضع العنصر الرياضي بين أحرف محددة مثل الأقواس أو أحرف أخرى كإطار |
| [`function(self, function_argument)`](/slides/python-net/ar/aspose.slides.mathtext/matharray/function/#imathelement) | يأخذ دالة ذات معامل باستخدام هذه الحالة كاسم الدالة |
| [`function(self, function_argument)`](/slides/python-net/ar/aspose.slides.mathtext/matharray/function/#str) | يأخذ دالة ذات معامل باستخدام هذه الحالة كاسم الدالة |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/ar/aspose.slides.mathtext/matharray/as_argument_of_function/#imathelement) | يأخذ الدالة المحددة باستخدام هذه الحالة كمعامل |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/ar/aspose.slides.mathtext/matharray/as_argument_of_function/#str) | يأخذ الدالة المحددة باستخدام هذه الحالة كمعامل |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/ar/aspose.slides.mathtext/matharray/as_argument_of_function/#mathfunctionsofoneargument) | يأخذ الدالة المحددة باستخدام هذه الحالة كمعامل |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/ar/aspose.slides.mathtext/matharray/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | يأخذ الدالة المحددة باستخدام هذه الحالة كمعامل ومعامل إضافي محدد |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/ar/aspose.slides.mathtext/matharray/as_argument_of_function/#mathfunctionsoftwoarguments-str) | يأخذ الدالة المحددة باستخدام هذه الحالة كمعامل ومعامل إضافي محدد |
| [`set_subscript(self, subscript)`](/slides/python-net/ar/aspose.slides.mathtext/matharray/set_subscript/#imathelement) | ينشئ حروفًا منخفضة |
| [`set_subscript(self, subscript)`](/slides/python-net/ar/aspose.slides.mathtext/matharray/set_subscript/#str) | ينشئ حروفًا منخفضة |
| [`set_superscript(self, superscript)`](/slides/python-net/ar/aspose.slides.mathtext/matharray/set_superscript/#imathelement) | ينشئ حروفًا علوية |
| [`set_superscript(self, superscript)`](/slides/python-net/ar/aspose.slides.mathtext/matharray/set_superscript/#str) | ينشئ حروفًا علوية |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/ar/aspose.slides.mathtext/matharray/set_sub_superscript_on_the_right/#imathelement-imathelement) | ينشئ حروفًا منخفضة وعالية على اليمين |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/ar/aspose.slides.mathtext/matharray/set_sub_superscript_on_the_right/#str-str) | ينشئ حروفًا منخفضة وعالية على اليمين |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/ar/aspose.slides.mathtext/matharray/set_sub_superscript_on_the_left/#imathelement-imathelement) | ينشئ حروفًا منخفضة وعالية على اليسار |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/ar/aspose.slides.mathtext/matharray/set_sub_superscript_on_the_left/#str-str) | ينشئ حروفًا منخفضة وعالية على اليسار |
| [`radical(self, degree)`](/slides/python-net/ar/aspose.slides.mathtext/matharray/radical/#imathelement) | يحدد الجذر الرياضي للدرجة المعطاة من المعامل المحدد. |
| [`radical(self, degree)`](/slides/python-net/ar/aspose.slides.mathtext/matharray/radical/#str) | يحدد الجذر الرياضي للدرجة المعطاة من المعامل المحدد. |
| [`set_upper_limit(self, limit)`](/slides/python-net/ar/aspose.slides.mathtext/matharray/set_upper_limit/#imathelement) | يأخذ الحد الأعلى |
| [`set_upper_limit(self, limit)`](/slides/python-net/ar/aspose.slides.mathtext/matharray/set_upper_limit/#str) | يأخذ الحد الأعلى |
| [`set_lower_limit(self, limit)`](/slides/python-net/ar/aspose.slides.mathtext/matharray/set_lower_limit/#imathelement) | يأخذ الحد السفلي |
| [`set_lower_limit(self, limit)`](/slides/python-net/ar/aspose.slides.mathtext/matharray/set_lower_limit/#str) | يأخذ الحد السفلي |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/ar/aspose.slides.mathtext/matharray/nary/#mathnaryoperatortypes-imathelement-imathelement) | ينشئ عاملًا N-ary |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/ar/aspose.slides.mathtext/matharray/nary/#mathnaryoperatortypes-str-str) | ينشئ عاملًا N-ary |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/ar/aspose.slides.mathtext/matharray/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | يأخذ التكامل |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/ar/aspose.slides.mathtext/matharray/integral/#mathintegraltypes-imathelement-imathelement) | يأخذ التكامل |
| [`integral(self, integral_type)`](/slides/python-net/ar/aspose.slides.mathtext/matharray/integral/#mathintegraltypes) | يأخذ التكامل بدون حدود |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/ar/aspose.slides.mathtext/matharray/integral/#mathintegraltypes-str-str-mathlimitlocations) | يأخذ التكامل |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/ar/aspose.slides.mathtext/matharray/integral/#mathintegraltypes-str-str) | يأخذ التكامل |
| [`group(self)`](/slides/python-net/ar/aspose.slides.mathtext/matharray/group/#) | يضع هذا العنصر في مجموعة باستخدام قوس معكوف سفلي |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/ar/aspose.slides.mathtext/matharray/group/#char-mathtopbotpositions-mathtopbotpositions) | يضع هذا العنصر في مجموعة باستخدام حرف تجميع مثل القوس المعكوف السفلي أو غيره |
| [`to_border_box(self)`](/slides/python-net/ar/aspose.slides.mathtext/matharray/to_border_box/#) | يضع هذا العنصر في صندوق حد |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/ar/aspose.slides.mathtext/matharray/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | يضع هذا العنصر في صندوق حد |
| [`to_math_array(self)`](/slides/python-net/ar/aspose.slides.mathtext/matharray/to_math_array/#) | يضعه في مصفوفة رأسية |
| [`accent(self, accent_character)`](/slides/python-net/ar/aspose.slides.mathtext/matharray/accent/#char) | يعيّن علامة تشديد (حرف فوق هذا العنصر) |
| [`overbar(self)`](/slides/python-net/ar/aspose.slides.mathtext/matharray/overbar/#) | يعيّن شريطًا أعلى هذا العنصر |
| [`underbar(self)`](/slides/python-net/ar/aspose.slides.mathtext/matharray/underbar/#) | يعيّن شريطًا أسفل هذا العنصر |
| [`to_box(self)`](/slides/python-net/ar/aspose.slides.mathtext/matharray/to_box/#) | يضع هذا العنصر في صندوق غير مرئي (تجميع منطقي) <br/>            يُستخدم لتجميع مكونات معادلة أو نص رياضي آخر.<br/>            يمكن أن يعمل الكائن المربع (على سبيل المثال) كمحاكي عامل مع أو بدون نقطة محاذاة، <br/>            أو كنقطة كسر سطر، أو يُجَمّع بحيث لا يسمح بانقطاع السطر داخله. |
| [`get_children(self)`](/slides/python-net/ar/aspose.slides.mathtext/matharray/get_children/#) | جلب عناصر الأطفال |

### انظر أيضًا
* class [`MathArray`](/slides/python-net/ar/aspose.slides.mathtext/matharray)
* class [`MathElementBase`](/slides/python-net/ar/aspose.slides.mathtext/mathelementbase)
* module [`aspose.slides.mathtext`](/slides/python-net/ar/aspose.slides.mathtext)
* library [`Aspose.Slides`](/slides/python-net)