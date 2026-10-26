---
title: MathNaryOperator class
second_title: Aspose.Slides for Python عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides.mathtext/mathnaryoperator/
---
## فئة MathNaryOperator

يحدد كائنًا رياضيًا متعدد المتغيرات (N-ary)، مثل Summation و Integral.
يتكون من عامل، قاعدة (أو معامل)، وحدود علوية وسفلية اختيارية.
أمثلة على عوامل N-ary هي: Summation، Union، Intersection، Integral

**Inheritance:**[`MathNaryOperator`](/slides/python-net/ar/aspose.slides.mathtext/mathnaryoperator) → [`MathElementBase`](/slides/python-net/ar/aspose.slides.mathtext/mathelementbase)

نوع MathNaryOperator يكشف عن الأعضاء التالية:

## Constructors

| Constructor | Description |
| :- | :- |
| [`__init__(self, operator_symbol, base_argument, lower_limit, upper_limit)`](/slides/python-net/ar/aspose.slides.mathtext/mathnaryoperator/__init__/#char-imathelement-imathelement-imathelement) | يُهيئ مثيًرا جديدًا من الفئة MathNaryOperator. |
| [`__init__(self, operator_symbol, base_argument, lower_limit)`](/slides/python-net/ar/aspose.slides.mathtext/mathnaryoperator/__init__/#char-imathelement-imathelement) | يُهيئ مثيًرا جديدًا من الفئة MathNaryOperator. |
| [`__init__(self, operator_symbol, base_argument)`](/slides/python-net/ar/aspose.slides.mathtext/mathnaryoperator/__init__/#char-imathelement) | يُهيئ مثيًرا جديدًا من الفئة MathNaryOperator. |

## Properties

| Property | Description |
| :- | :- |
| [`base`](/slides/python-net/ar/aspose.slides.mathtext/mathnaryoperator/base/) | الوسيط الأساسي |
| [`subscript`](/slides/python-net/ar/aspose.slides.mathtext/mathnaryoperator/subscript/) | يحدد وسيطًا سفليًا، على سبيل المثال في حالة التكامل، يحدد الحد الأدنى |
| [`superscript`](/slides/python-net/ar/aspose.slides.mathtext/mathnaryoperator/superscript/) | يحدد وسيطًا علويًا، على سبيل المثال في حالة التكامل، يحدد الحد الأعلى |
| [`operator`](/slides/python-net/ar/aspose.slides.mathtext/mathnaryoperator/operator/) | حرف عامل N-ary<br/>            على سبيل المثال: '∑', '∫' |
| [`limit_location`](/slides/python-net/ar/aspose.slides.mathtext/mathnaryoperator/limit_location/) | موقع الحدود (السفلي والعلوي) |
| [`grow_to_match_operand_height`](/slides/python-net/ar/aspose.slides.mathtext/mathnaryoperator/grow_to_match_operand_height/) | حرف العامل ينمو عموديًا ليتطابق مع ارتفاع المعامل |
| [`hide_subscript`](/slides/python-net/ar/aspose.slides.mathtext/mathnaryoperator/hide_subscript/) | إخفاء السطر السفلي |
| [`hide_superscript`](/slides/python-net/ar/aspose.slides.mathtext/mathnaryoperator/hide_superscript/) | إخفاء السطر العلوي |

## Methods

| Method | Description |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/ar/aspose.slides.mathtext/mathnaryoperator/join/#imathelement) | يجمع عنصرًا رياضيًا ويشكل كتلة رياضية |
| [`join(self, math_text)`](/slides/python-net/ar/aspose.slides.mathtext/mathnaryoperator/join/#str) | يجمع نصًا رياضيًا ويشكل كتلة رياضية |
| [`divide(self, denominator)`](/slides/python-net/ar/aspose.slides.mathtext/mathnaryoperator/divide/#imathelement) | ينشئ كسرًا بهذا البسط والمقام المحدد |
| [`divide(self, denominator)`](/slides/python-net/ar/aspose.slides.mathtext/mathnaryoperator/divide/#str) | ينشئ كسرًا بهذا البسط والمقام المحدد |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/ar/aspose.slides.mathtext/mathnaryoperator/divide/#imathelement-mathfractiontypes) | ينشئ كسرًا من النوع المحدد بهذا البسط والمقام المحدد |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/ar/aspose.slides.mathtext/mathnaryoperator/divide/#str-mathfractiontypes) | ينشئ كسرًا من النوع المحدد بهذا البسط والمقام المحدد |
| [`enclose(self)`](/slides/python-net/ar/aspose.slides.mathtext/mathnaryoperator/enclose/#) | يضع عنصرًا رياضيًا بين قوسين |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/ar/aspose.slides.mathtext/mathnaryoperator/enclose/#char-char) | يضع عنصرًا رياضيًا بين أحرف محددة مثل القوس أو أحرف أخرى كإطار |
| [`function(self, function_argument)`](/slides/python-net/ar/aspose.slides.mathtext/mathnaryoperator/function/#imathelement) | يأخذ دالة لوسيط باستخدام هذا المثال كاسم الدالة |
| [`function(self, function_argument)`](/slides/python-net/ar/aspose.slides.mathtext/mathnaryoperator/function/#str) | يأخذ دالة لوسيط باستخدام هذا المثال كاسم الدالة |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/ar/aspose.slides.mathtext/mathnaryoperator/as_argument_of_function/#imathelement) | يأخذ دالة محددة باستخدام هذا المثال كوسيط |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/ar/aspose.slides.mathtext/mathnaryoperator/as_argument_of_function/#str) | يأخذ دالة محددة باستخدام هذا المثال كوسيط |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/ar/aspose.slides.mathtext/mathnaryoperator/as_argument_of_function/#mathfunctionsofoneargument) | يأخذ دالة محددة باستخدام هذا المثال كوسيط |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/ar/aspose.slides.mathtext/mathnaryoperator/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | يأخذ دالة محددة باستخدام هذا المثال كوسيط ويضيف وسيطًا إضافيًا محددًا |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/ar/aspose.slides.mathtext/mathnaryoperator/as_argument_of_function/#mathfunctionsoftwoarguments-str) | يأخذ دالة محددة باستخدام هذا المثال كوسيط ويضيف وسيطًا إضافيًا محددًا |
| [`set_subscript(self, subscript)`](/slides/python-net/ar/aspose.slides.mathtext/mathnaryoperator/set_subscript/#imathelement) | ينشئ سطرًا سفليًا |
| [`set_subscript(self, subscript)`](/slides/python-net/ar/aspose.slides.mathtext/mathnaryoperator/set_subscript/#str) | ينشئ سطرًا سفليًا |
| [`set_superscript(self, superscript)`](/slides/python-net/ar/aspose.slides.mathtext/mathnaryoperator/set_superscript/#imathelement) | ينشئ سطرًا علويًا |
| [`set_superscript(self, superscript)`](/slides/python-net/ar/aspose.slides.mathtext/mathnaryoperator/set_superscript/#str) | ينشئ سطرًا علويًا |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/ar/aspose.slides.mathtext/mathnaryoperator/set_sub_superscript_on_the_right/#imathelement-imathelement) | ينشئ سطرًا سفليًا وعلويًا على اليمين |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/ar/aspose.slides.mathtext/mathnaryoperator/set_sub_superscript_on_the_right/#str-str) | ينشئ سطرًا سفليًا وعلويًا على اليمين |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/ar/aspose.slides.mathtext/mathnaryoperator/set_sub_superscript_on_the_left/#imathelement-imathelement) | ينشئ سطرًا سفليًا وعلويًا على اليسار |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/ar/aspose.slides.mathtext/mathnaryoperator/set_sub_superscript_on_the_left/#str-str) | ينشئ سطرًا سفليًا وعلويًا على اليسار |
| [`radical(self, degree)`](/slides/python-net/ar/aspose.slides.mathtext/mathnaryoperator/radical/#imathelement) | يحدد الجذر الرياضي للدرجة المعطاة من الوسيط المحدد |
| [`radical(self, degree)`](/slides/python-net/ar/aspose.slides.mathtext/mathnaryoperator/radical/#str) | يحدد الجذر الرياضي للدرجة المعطاة من الوسيط المحدد |
| [`set_upper_limit(self, limit)`](/slides/python-net/ar/aspose.slides.mathtext/mathnaryoperator/set_upper_limit/#imathelement) | يأخذ الحد الأعلى |
| [`set_upper_limit(self, limit)`](/slides/python-net/ar/aspose.slides.mathtext/mathnaryoperator/set_upper_limit/#str) | يأخذ الحد الأعلى |
| [`set_lower_limit(self, limit)`](/slides/python-net/ar/aspose.slides.mathtext/mathnaryoperator/set_lower_limit/#imathelement) | يأخذ الحد الأدنى |
| [`set_lower_limit(self, limit)`](/slides/python-net/ar/aspose.slides.mathtext/mathnaryoperator/set_lower_limit/#str) | يأخذ الحد الأدنى |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/ar/aspose.slides.mathtext/mathnaryoperator/nary/#mathnaryoperatortypes-imathelement-imathelement) | ينشئ عاملًا N-ary |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/ar/aspose.slides.mathtext/mathnaryoperator/nary/#mathnaryoperatortypes-str-str) | ينشئ عاملًا N-ary |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/ar/aspose.slides.mathtext/mathnaryoperator/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | يأخذ التكامل |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/ar/aspose.slides.mathtext/mathnaryoperator/integral/#mathintegraltypes-imathelement-imathelement) | يأخذ التكامل |
| [`integral(self, integral_type)`](/slides/python-net/ar/aspose.slides.mathtext/mathnaryoperator/integral/#mathintegraltypes) | يأخذ التكامل بدون حدود |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/ar/aspose.slides.mathtext/mathnaryoperator/integral/#mathintegraltypes-str-str-mathlimitlocations) | يأخذ التكامل |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/ar/aspose.slides.mathtext/mathnaryoperator/integral/#mathintegraltypes-str-str) | يأخذ التكامل |
| [`group(self)`](/slides/python-net/ar/aspose.slides.mathtext/mathnaryoperator/group/#) | يضع هذا العنصر في مجموعة باستخدام قوس معقوف سفلي |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/ar/aspose.slides.mathtext/mathnaryoperator/group/#char-mathtopbotpositions-mathtopbotpositions) | يضع هذا العنصر في مجموعة باستخدام حرف تجميع مثل القوس المعقوف السفلي أو غيره |
| [`to_border_box(self)`](/slides/python-net/ar/aspose.slides.mathtext/mathnaryoperator/to_border_box/#) | يضع هذا العنصر في صندوق حدود |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/ar/aspose.slides.mathtext/mathnaryoperator/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | يضع هذا العنصر في صندوق حدود |
| [`to_math_array(self)`](/slides/python-net/ar/aspose.slides.mathtext/mathnaryoperator/to_math_array/#) | يضعه في صف عمودي |
| [`accent(self, accent_character)`](/slides/python-net/ar/aspose.slides.mathtext/mathnaryoperator/accent/#char) | يحدد علامة شدة (حرف فوق هذا العنصر) |
| [`overbar(self)`](/slides/python-net/ar/aspose.slides.mathtext/mathnaryoperator/overbar/#) | يضع شريطًا فوق هذا العنصر |
| [`underbar(self)`](/slides/python-net/ar/aspose.slides.mathtext/mathnaryoperator/underbar/#) | يضع شريطًا أسفل هذا العنصر |
| [`to_box(self)`](/slides/python-net/ar/aspose.slides.mathtext/mathnaryoperator/to_box/#) | يضع هذا العنصر في صندوق غير مرئي (تجميع منطقي) <br/>            يُستخدم لتجميع مكونات معادلة أو نص رياضي آخر.<br/>            يمكن أن يعمل الصندوق (على سبيل المثال) كمحاكي عامل مع أو بدون نقطة محاذاة، <br/>            أو كنقطة فاصل سطر، أو يجمعه بحيث لا يسمح بفواصل سطر داخله. |
| [`get_children(self)`](/slides/python-net/ar/aspose.slides.mathtext/mathnaryoperator/get_children/#) | الحصول على العناصر الفرعية |

### See Also
* فئة [`MathElementBase`](/slides/python-net/ar/aspose.slides.mathtext/mathelementbase)
* فئة [`MathNaryOperator`](/slides/python-net/ar/aspose.slides.mathtext/mathnaryoperator)
* وحدة [`aspose.slides.mathtext`](/slides/python-net/ar/aspose.slides.mathtext)
* مكتبة [`Aspose.Slides`](/slides/python-net)