---
title: MathRadical class
second_title: Aspose.Slides للبايثون عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides.mathtext/mathradical/
---
## MathRadical فئة

يحدد دالة الجذر، التي تتألف من أساس ودرجة اختيارية.
مثال على كائن الجذر هو √𝑥.

**Inheritance:**[`MathRadical`](/slides/python-net/ar/aspose.slides.mathtext/mathradical) → [`MathElementBase`](/slides/python-net/ar/aspose.slides.mathtext/mathelementbase)

يعرض نوع MathRadical الأعضاء التالية:

## البنيات

| Constructor | Description |
| :- | :- |
| [`__init__(self, base_argument, degree_argument)`](/slides/python-net/ar/aspose.slides.mathtext/mathradical/__init__/#imathelement-imathelement) | ينشئ مثيلاً جديدًا من فئة MathRadical. |

## الخصائص

| Property | Description |
| :- | :- |
| [`base`](/slides/python-net/ar/aspose.slides.mathtext/mathradical/base/) | الوسيط الأساسي |
| [`degree`](/slides/python-net/ar/aspose.slides.mathtext/mathradical/degree/) | وسيط الدرجة |
| [`hide_degree`](/slides/python-net/ar/aspose.slides.mathtext/mathradical/hide_degree/) | إخفاء الدرجة<br/>            عندما تكون true، لا تُظهر الدرجة، كما في √𝑥 |

## الطرق

| Method | Description |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/ar/aspose.slides.mathtext/mathradical/join/#imathelement) | يجمع عنصرًا رياضيًا ويشكل كتلة رياضية |
| [`join(self, math_text)`](/slides/python-net/ar/aspose.slides.mathtext/mathradical/join/#str) | يجمع نصًا رياضيًا ويشكل كتلة رياضية |
| [`divide(self, denominator)`](/slides/python-net/ar/aspose.slides.mathtext/mathradical/divide/#imathelement) | ينشئ كسرًا بهذا البسط والمقام المحدد |
| [`divide(self, denominator)`](/slides/python-net/ar/aspose.slides.mathtext/mathradical/divide/#str) | ينشئ كسرًا بهذا البسط والمقام المحدد |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/ar/aspose.slides.mathtext/mathradical/divide/#imathelement-mathfractiontypes) | ينشئ كسرًا من النوع المحدد بهذا البسط والمقام المحدد |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/ar/aspose.slides.mathtext/mathradical/divide/#str-mathfractiontypes) | ينشئ كسرًا من النوع المحدد بهذا البسط والمقام المحدد |
| [`enclose(self)`](/slides/python-net/ar/aspose.slides.mathtext/mathradical/enclose/#) | يحيط عنصرًا رياضيًا بأقواس |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/ar/aspose.slides.mathtext/mathradical/enclose/#char-char) | يحيط عنصرًا رياضيًا بأحرف محددة مثل الأقواس أو أحرف أخرى كإطار |
| [`function(self, function_argument)`](/slides/python-net/ar/aspose.slides.mathtext/mathradical/function/#imathelement) | يأخذ دالة لوسيط باستخدام هذا المثيل كاسم الدالة |
| [`function(self, function_argument)`](/slides/python-net/ar/aspose.slides.mathtext/mathradical/function/#str) | يأخذ دالة لوسيط باستخدام هذا المثيل كاسم الدالة |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/ar/aspose.slides.mathtext/mathradical/as_argument_of_function/#imathelement) | يأخذ الدالة المحددة باستخدام هذا المثيل كوسيط |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/ar/aspose.slides.mathtext/mathradical/as_argument_of_function/#str) | يأخذ الدالة المحددة باستخدام هذا المثيل كوسيط |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/ar/aspose.slides.mathtext/mathradical/as_argument_of_function/#mathfunctionsofoneargument) | يأخذ الدالة المحددة باستخدام هذا المثيل كوسيط |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/ar/aspose.slides.mathtext/mathradical/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | يأخذ الدالة المحددة باستخدام هذا المثيل كوسيط ووسيط إضافي محدد |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/ar/aspose.slides.mathtext/mathradical/as_argument_of_function/#mathfunctionsoftwoarguments-str) | يأخذ الدالة المحددة باستخدام هذا المثيل كوسيط ووسيط إضافي محدد |
| [`set_subscript(self, subscript)`](/slides/python-net/ar/aspose.slides.mathtext/mathradical/set_subscript/#imathelement) | ينشئ مؤشر سفلي |
| [`set_subscript(self, subscript)`](/slides/python-net/ar/aspose.slides.mathtext/mathradical/set_subscript/#str) | ينشئ مؤشر سفلي |
| [`set_superscript(self, superscript)`](/slides/python-net/ar/aspose.slides.mathtext/mathradical/set_superscript/#imathelement) | ينشئ مؤشر علوي |
| [`set_superscript(self, superscript)`](/slides/python-net/ar/aspose.slides.mathtext/mathradical/set_superscript/#str) | ينشئ مؤشر علوي |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/ar/aspose.slides.mathtext/mathradical/set_sub_superscript_on_the_right/#imathelement-imathelement) | ينشئ مؤشر سفلي ومؤشر علوي على اليمين |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/ar/aspose.slides.mathtext/mathradical/set_sub_superscript_on_the_right/#str-str) | ينشئ مؤشر سفلي ومؤشر علوي على اليمين |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/ar/aspose.slides.mathtext/mathradical/set_sub_superscript_on_the_left/#imathelement-imathelement) | ينشئ مؤشر سفلي ومؤشر علوي على اليسار |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/ar/aspose.slides.mathtext/mathradical/set_sub_superscript_on_the_left/#str-str) | ينشئ مؤشر سفلي ومؤشر علوي على اليسار |
| [`radical(self, degree)`](/slides/python-net/ar/aspose.slides.mathtext/mathradical/radical/#imathelement) | يحدد الجذر الرياضي للدرجة المحددة من الوسيط المحدد. |
| [`radical(self, degree)`](/slides/python-net/ar/aspose.slides.mathtext/mathradical/radical/#str) | يحدد الجذر الرياضي للدرجة المحددة من الوسيط المحدد. |
| [`set_upper_limit(self, limit)`](/slides/python-net/ar/aspose.slides.mathtext/mathradical/set_upper_limit/#imathelement) | يأخذ الحد العلوي |
| [`set_upper_limit(self, limit)`](/slides/python-net/ar/aspose.slides.mathtext/mathradical/set_upper_limit/#str) | يأخذ الحد العلوي |
| [`set_lower_limit(self, limit)`](/slides/python-net/ar/aspose.slides.mathtext/mathradical/set_lower_limit/#imathelement) | يأخذ الحد السفلي |
| [`set_lower_limit(self, limit)`](/slides/python-net/ar/aspose.slides.mathtext/mathradical/set_lower_limit/#str) | يأخذ الحد السفلي |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/ar/aspose.slides.mathtext/mathradical/nary/#mathnaryoperatortypes-imathelement-imathelement) | ينشئ عاملًا N-ary |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/ar/aspose.slides.mathtext/mathradical/nary/#mathnaryoperatortypes-str-str) | ينشئ عاملًا N-ary |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/ar/aspose.slides.mathtext/mathradical/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | يأخذ التكامل |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/ar/aspose.slides.mathtext/mathradical/integral/#mathintegraltypes-imathelement-imathelement) | يأخذ التكامل |
| [`integral(self, integral_type)`](/slides/python-net/ar/aspose.slides.mathtext/mathradical/integral/#mathintegraltypes) | يأخذ التكامل بدون حدود |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/ar/aspose.slides.mathtext/mathradical/integral/#mathintegraltypes-str-str-mathlimitlocations) | يأخذ التكامل |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/ar/aspose.slides.mathtext/mathradical/integral/#mathintegraltypes-str-str) | يأخذ التكامل |
| [`group(self)`](/slides/python-net/ar/aspose.slides.mathtext/mathradical/group/#) | يضع هذا العنصر في مجموعة باستخدام قوس معقوف سفلي |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/ar/aspose.slides.mathtext/mathradical/group/#char-mathtopbotpositions-mathtopbotpositions) | يضع هذا العنصر في مجموعة باستخدام حرف تجميع مثل القوس المعقوف السفلي أو غيره |
| [`to_border_box(self)`](/slides/python-net/ar/aspose.slides.mathtext/mathradical/to_border_box/#) | يضع هذا العنصر في صندوق حدود |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/ar/aspose.slides.mathtext/mathradical/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | يضع هذا العنصر في صندوق حدود |
| [`to_math_array(self)`](/slides/python-net/ar/aspose.slides.mathtext/mathradical/to_math_array/#) | يوضع في مصفوفة عمودية |
| [`accent(self, accent_character)`](/slides/python-net/ar/aspose.slides.mathtext/mathradical/accent/#char) | يضبط علامة إكسنت (حرف فوق هذا العنصر) |
| [`overbar(self)`](/slides/python-net/ar/aspose.slides.mathtext/mathradical/overbar/#) | يضبط شريطًا فوق هذا العنصر |
| [`underbar(self)`](/slides/python-net/ar/aspose.slides.mathtext/mathradical/underbar/#) | يضبط شريطًا أسفل هذا العنصر |
| [`to_box(self)`](/slides/python-net/ar/aspose.slides.mathtext/mathradical/to_box/#) | يضع هذا العنصر في صندوق غير مرئي (تجميع منطقي) <br/>            يُستخدم لتجميع مكونات معادلة أو مثال آخر من النص الرياضي.<br/>            يمكن أن يكون الكائن المربع (على سبيل المثال) محاكيًا للمؤثر مع أو بدون نقطة محاذاة، <br/>            يعمل كنقطة فاصل سطر، أو يُجمع بحيث لا يُسمح بفواصل سطرية داخله. |
| [`get_children(self)`](/slides/python-net/ar/aspose.slides.mathtext/mathradical/get_children/#) | احصل على عناصر الأطفال |


### انظر أيضا
* فئة [`MathElementBase`](/slides/python-net/ar/aspose.slides.mathtext/mathelementbase)
* فئة [`MathRadical`](/slides/python-net/ar/aspose.slides.mathtext/mathradical)
* وحدة [`aspose.slides.mathtext`](/slides/python-net/ar/aspose.slides.mathtext)
* مكتبة [`Aspose.Slides`](/slides/python-net)