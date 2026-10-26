---
title: MathLimit class
second_title: Aspose.Slides لـ Python عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides.mathtext/mathlimit/
---
## MathLimit فئة

يحدد كائن Limit، الذي يتكون من نص على خط الأساس ونص بحجم أصغر مباشرةً فوقه أو تحته.

**الوراثة:**[`MathLimit`](/slides/python-net/ar/aspose.slides.mathtext/mathlimit) → [`MathElementBase`](/slides/python-net/ar/aspose.slides.mathtext/mathelementbase)

نوع MathLimit يكشف عن الأعضاء التالية:

## المنشئات

| المنشئ | الوصف |
| :- | :- |
| [`__init__(self, base_arg, limit, upper_limit)`](/slides/python-net/ar/aspose.slides.mathtext/mathlimit/__init__/#imathelement-imathelement-bool) | يقوم بتهيئة نسخة جديدة من فئة MathLimit. |
| [`__init__(self, base_arg, limit)`](/slides/python-net/ar/aspose.slides.mathtext/mathlimit/__init__/#imathelement-imathelement) | يقوم بتهيئة نسخة جديدة من فئة MathLimit مع حد أدنى |

## الخصائص

| الخاصية | الوصف |
| :- | :- |
| [`base`](/slides/python-net/ar/aspose.slides.mathtext/mathlimit/base/) | المعامل الأساسي |
| [`limit`](/slides/python-net/ar/aspose.slides.mathtext/mathlimit/limit/) | معامل الحد |
| [`upper_limit`](/slides/python-net/ar/aspose.slides.mathtext/mathlimit/upper_limit/) | يحدد الحد العلوي أو السفلي |

## الطرق

| الطريقة | الوصف |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/ar/aspose.slides.mathtext/mathlimit/join/#imathelement) | يجمع عنصرًا رياضيًا ويشكل كتلة رياضية |
| [`join(self, math_text)`](/slides/python-net/ar/aspose.slides.mathtext/mathlimit/join/#str) | يجمع نصًا رياضيًا ويشكل كتلة رياضية |
| [`divide(self, denominator)`](/slides/python-net/ar/aspose.slides.mathtext/mathlimit/divide/#imathelement) | ينشئ كسرًا باستخدام هذا البسط والمقام المحدد |
| [`divide(self, denominator)`](/slides/python-net/ar/aspose.slides.mathtext/mathlimit/divide/#str) | ينشئ كسرًا باستخدام هذا البسط والمقام المحدد |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/ar/aspose.slides.mathtext/mathlimit/divide/#imathelement-mathfractiontypes) | ينشئ كسرًا من النوع المحدد باستخدام هذا البسط والمقام المحدد |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/ar/aspose.slides.mathtext/mathlimit/divide/#str-mathfractiontypes) | ينشئ كسرًا من النوع المحدد باستخدام هذا البسط والمقام المحدد |
| [`enclose(self)`](/slides/python-net/ar/aspose.slides.mathtext/mathlimit/enclose/#) | يحتوي عنصرًا رياضيًا بين أقواس |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/ar/aspose.slides.mathtext/mathlimit/enclose/#char-char) | يحتوي عنصرًا رياضيًا في أحرف محددة مثل الأقواس أو أحرف أخرى كإطار |
| [`function(self, function_argument)`](/slides/python-net/ar/aspose.slides.mathtext/mathlimit/function/#imathelement) | يأخذ دالة لمعامل باستخدام هذا المثيل كاسم الدالة |
| [`function(self, function_argument)`](/slides/python-net/ar/aspose.slides.mathtext/mathlimit/function/#str) | يأخذ دالة لمعامل باستخدام هذا المثيل كاسم الدالة |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/ar/aspose.slides.mathtext/mathlimit/as_argument_of_function/#imathelement) | يأخذ الدالة المحددة باستخدام هذا المثيل كمعامل |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/ar/aspose.slides.mathtext/mathlimit/as_argument_of_function/#str) | يأخذ الدالة المحددة باستخدام هذا المثيل كمعامل |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/ar/aspose.slides.mathtext/mathlimit/as_argument_of_function/#mathfunctionsofoneargument) | يأخذ الدالة المحددة باستخدام هذا المثيل كمعامل |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/ar/aspose.slides.mathtext/mathlimit/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | يأخذ الدالة المحددة باستخدام هذا المثيل كمعامل وإضافة معامل إضافي محدد |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/ar/aspose.slides.mathtext/mathlimit/as_argument_of_function/#mathfunctionsoftwoarguments-str) | يأخذ الدالة المحددة باستخدام هذا المثيل كمعامل وإضافة معامل إضافي محدد |
| [`set_subscript(self, subscript)`](/slides/python-net/ar/aspose.slides.mathtext/mathlimit/set_subscript/#imathelement) | ينشئ مؤشر سفلي |
| [`set_subscript(self, subscript)`](/slides/python-net/ar/aspose.slides.mathtext/mathlimit/set_subscript/#str) | ينشئ مؤشر سفلي |
| [`set_superscript(self, superscript)`](/slides/python-net/ar/aspose.slides.mathtext/mathlimit/set_superscript/#imathelement) | ينشئ مؤشر علوي |
| [`set_superscript(self, superscript)`](/slides/python-net/ar/aspose.slides.mathtext/mathlimit/set_superscript/#str) | ينشئ مؤشر علوي |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/ar/aspose.slides.mathtext/mathlimit/set_sub_superscript_on_the_right/#imathelement-imathelement) | ينشئ مؤشر سفلي وعُلوي على اليمين |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/ar/aspose.slides.mathtext/mathlimit/set_sub_superscript_on_the_right/#str-str) | ينشئ مؤشر سفلي وعُلوي على اليمين |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/ar/aspose.slides.mathtext/mathlimit/set_sub_superscript_on_the_left/#imathelement-imathelement) | ينشئ مؤشر سفلي وعُلوي على اليسار |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/ar/aspose.slides.mathtext/mathlimit/set_sub_superscript_on_the_left/#str-str) | ينشئ مؤشر سفلي وعُلوي على اليسار |
| [`radical(self, degree)`](/slides/python-net/ar/aspose.slides.mathtext/mathlimit/radical/#imathelement) | يحدد الجذر الرياضي للدرجة المعطاة من المعامل المحدد. |
| [`radical(self, degree)`](/slides/python-net/ar/aspose.slides.mathtext/mathlimit/radical/#str) | يحدد الجذر الرياضي للدرجة المعطاة من المعامل المحدد. |
| [`set_upper_limit(self, limit)`](/slides/python-net/ar/aspose.slides.mathtext/mathlimit/set_upper_limit/#imathelement) | يأخذ الحد العلوي |
| [`set_upper_limit(self, limit)`](/slides/python-net/ar/aspose.slides.mathtext/mathlimit/set_upper_limit/#str) | يأخذ الحد العلوي |
| [`set_lower_limit(self, limit)`](/slides/python-net/ar/aspose.slides.mathtext/mathlimit/set_lower_limit/#imathelement) | يأخذ الحد السفلي |
| [`set_lower_limit(self, limit)`](/slides/python-net/ar/aspose.slides.mathtext/mathlimit/set_lower_limit/#str) | يأخذ الحد السفلي |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/ar/aspose.slides.mathtext/mathlimit/nary/#mathnaryoperatortypes-imathelement-imathelement) | ينشئ مشغل N-ary |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/ar/aspose.slides.mathtext/mathlimit/nary/#mathnaryoperatortypes-str-str) | ينشئ مشغل N-ary |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/ar/aspose.slides.mathtext/mathlimit/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | يأخذ التكامل |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/ar/aspose.slides.mathtext/mathlimit/integral/#mathintegraltypes-imathelement-imathelement) | يأخذ التكامل |
| [`integral(self, integral_type)`](/slides/python-net/ar/aspose.slides.mathtext/mathlimit/integral/#mathintegraltypes) | يأخذ التكامل بدون حدود |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/ar/aspose.slides.mathtext/mathlimit/integral/#mathintegraltypes-str-str-mathlimitlocations) | يأخذ التكامل |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/ar/aspose.slides.mathtext/mathlimit/integral/#mathintegraltypes-str-str) | يأخذ التكامل |
| [`group(self)`](/slides/python-net/ar/aspose.slides.mathtext/mathlimit/group/#) | يضع هذا العنصر في مجموعة باستخدام قوس معقوف سفلي |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/ar/aspose.slides.mathtext/mathlimit/group/#char-mathtopbotpositions-mathtopbotpositions) | يضع هذا العنصر في مجموعة باستخدام حرف تجميع مثل القوس المعقوف السفلي أو غيره |
| [`to_border_box(self)`](/slides/python-net/ar/aspose.slides.mathtext/mathlimit/to_border_box/#) | يضع هذا العنصر في مربع حدود |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/ar/aspose.slides.mathtext/mathlimit/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | يضع هذا العنصر في مربع حدود |
| [`to_math_array(self)`](/slides/python-net/ar/aspose.slides.mathtext/mathlimit/to_math_array/#) | يضع في مصفوفة رأسية |
| [`accent(self, accent_character)`](/slides/python-net/ar/aspose.slides.mathtext/mathlimit/accent/#char) | يضع علامة لهجة (حرف فوق هذا العنصر) |
| [`overbar(self)`](/slides/python-net/ar/aspose.slides.mathtext/mathlimit/overbar/#) | يضع شريطًا أعلى هذا العنصر |
| [`underbar(self)`](/slides/python-net/ar/aspose.slides.mathtext/mathlimit/underbar/#) | يضع شريطًا أسفل هذا العنصر |
| [`to_box(self)`](/slides/python-net/ar/aspose.slides.mathtext/mathlimit/to_box/#) | يضع هذا العنصر في مربع غير مرئي (تجميع منطقي) <br/>            يُستخدم لتجميع مكونات معادلة أو نص رياضي آخر.<br/>            يمكن أن يعمل الكائن المربع (على سبيل المثال) كمحاكي للمعامل مع أو بدون نقطة محاذاة، <br/>            يعمل كنقطة كسر سطر، أو يُجمع بطريقة لا تسمح بكسر الأسطر داخله. |
| [`get_children(self)`](/slides/python-net/ar/aspose.slides.mathtext/mathlimit/get_children/#) | احصل على العناصر الفرعية |

### انظر أيضاً
* فئة [`MathElementBase`](/slides/python-net/ar/aspose.slides.mathtext/mathelementbase)
* فئة [`MathLimit`](/slides/python-net/ar/aspose.slides.mathtext/mathlimit)
* وحدة [`aspose.slides.mathtext`](/slides/python-net/ar/aspose.slides.mathtext)
* مكتبة [`Aspose.Slides`](/slides/python-net)