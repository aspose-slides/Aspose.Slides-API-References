---
title: MathematicalText class
second_title: Aspose.Slides للغة Python عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides.mathtext/mathematicaltext/
---
## فئة MathematicalText

نص رياضي

**الوراثة:**[`MathematicalText`](/slides/python-net/ar/aspose.slides.mathtext/mathematicaltext) → [`MathElementBase`](/slides/python-net/ar/aspose.slides.mathtext/mathelementbase)

The MathematicalText type exposes the following members:

## المُنشئات

| المُنشئ | الوصف |
| :- | :- |
| [`__init__(self)`](/slides/python-net/ar/aspose.slides.mathtext/mathematicaltext/__init__/#) | المنـشئ الافتراضي (إنشاء قيمة String.Empty) |
| [`__init__(self, math_symbol)`](/slides/python-net/ar/aspose.slides.mathtext/mathematicaltext/__init__/#char) | إنشاء MathText برمز واحد |
| [`__init__(self, math_text)`](/slides/python-net/ar/aspose.slides.mathtext/mathematicaltext/__init__/#str) | إنشاء MathematicalText من نص |
| [`__init__(self, math_text, portion_format)`](/slides/python-net/ar/aspose.slides.mathtext/mathematicaltext/__init__/#str-iportionformat) | إنشاء MathematicalText من نص وإعدادات التنسيق |

## الخصائص

| الخاصية | الوصف |
| :- | :- |
| [`value`](/slides/python-net/ar/aspose.slides.mathtext/mathematicaltext/value/) | قيمة النص |
| [`format`](/slides/python-net/ar/aspose.slides.mathtext/mathematicaltext/format/) | خصائص تنسيق النص |

## الطرق

| الطريقة | الوصف |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/ar/aspose.slides.mathtext/mathematicaltext/join/#imathelement) | يجمع عنصرًا رياضيًا ويشكل كتلة رياضية |
| [`join(self, math_text)`](/slides/python-net/ar/aspose.slides.mathtext/mathematicaltext/join/#str) | يجمع نصًا رياضيًا ويشكل كتلة رياضية |
| [`divide(self, denominator)`](/slides/python-net/ar/aspose.slides.mathtext/mathematicaltext/divide/#imathelement) | ينشئ كسرًا بهذا البسط والمقام المحدد |
| [`divide(self, denominator)`](/slides/python-net/ar/aspose.slides.mathtext/mathematicaltext/divide/#str) | ينشئ كسرًا بهذا البسط والمقام المحدد |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/ar/aspose.slides.mathtext/mathematicaltext/divide/#imathelement-mathfractiontypes) | ينشئ كسرًا من النوع المحدد بهذا البسط والمقام المحدد |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/ar/aspose.slides.mathtext/mathematicaltext/divide/#str-mathfractiontypes) | ينشئ كسرًا من النوع المحدد بهذا البسط والمقام المحدد |
| [`enclose(self)`](/slides/python-net/ar/aspose.slides.mathtext/mathematicaltext/enclose/#) | يغلف عنصرًا رياضيًا بأقواس |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/ar/aspose.slides.mathtext/mathematicaltext/enclose/#char-char) | يغلف عنصرًا رياضيًا بأحرف محددة مثل الأقواس أو أحرف أخرى كإطار |
| [`function(self, function_argument)`](/slides/python-net/ar/aspose.slides.mathtext/mathematicaltext/function/#imathelement) | يأخذ دالة للمعامل باستخدام هذا الكائن كاسم الدالة |
| [`function(self, function_argument)`](/slides/python-net/ar/aspose.slides.mathtext/mathematicaltext/function/#str) | يأخذ دالة للمعامل باستخدام هذا الكائن كاسم الدالة |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/ar/aspose.slides.mathtext/mathematicaltext/as_argument_of_function/#imathelement) | يأخذ دالة محددة باستخدام هذا الكائن كمعامل |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/ar/aspose.slides.mathtext/mathematicaltext/as_argument_of_function/#str) | يأخذ دالة محددة باستخدام هذا الكائن كمعامل |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/ar/aspose.slides.mathtext/mathematicaltext/as_argument_of_function/#mathfunctionsofoneargument) | يأخذ دالة محددة باستخدام هذا الكائن كمعامل |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/ar/aspose.slides.mathtext/mathematicaltext/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | يأخذ دالة محددة باستخدام هذا الكائن كمعامل ومعامل إضافي محدد |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/ar/aspose.slides.mathtext/mathematicaltext/as_argument_of_function/#mathfunctionsoftwoarguments-str) | يأخذ دالة محددة باستخدام هذا الكائن كمعامل ومعامل إضافي محدد |
| [`set_subscript(self, subscript)`](/slides/python-net/ar/aspose.slides.mathtext/mathematicaltext/set_subscript/#imathelement) | ينشئ نصًا سفليًا |
| [`set_subscript(self, subscript)`](/slides/python-net/ar/aspose.slides.mathtext/mathematicaltext/set_subscript/#str) | ينشئ نصًا سفليًا |
| [`set_superscript(self, superscript)`](/slides/python-net/ar/aspose.slides.mathtext/mathematicaltext/set_superscript/#imathelement) | ينشئ نصًا علويًا |
| [`set_superscript(self, superscript)`](/slides/python-net/ar/aspose.slides.mathtext/mathematicaltext/set_superscript/#str) | ينشئ نصًا علويًا |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/ar/aspose.slides.mathtext/mathematicaltext/set_sub_superscript_on_the_right/#imathelement-imathelement) | ينشئ نصًا سفليًا وعلويًا على اليمين |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/ar/aspose.slides.mathtext/mathematicaltext/set_sub_superscript_on_the_right/#str-str) | ينشئ نصًا سفليًا وعلويًا على اليمين |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/ar/aspose.slides.mathtext/mathematicaltext/set_sub_superscript_on_the_left/#imathelement-imathelement) | ينشئ نصًا سفليًا وعلويًا على اليسار |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/ar/aspose.slides.mathtext/mathematicaltext/set_sub_superscript_on_the_left/#str-str) | وينشئ نصًا سفليًا وعلويًا على اليسار |
| [`radical(self, degree)`](/slides/python-net/ar/aspose.slides.mathtext/mathematicaltext/radical/#imathelement) | يحدد الجذر الرياضي للدرجة المعطاة من المعامل المحدد. |
| [`radical(self, degree)`](/slides/python-net/ar/aspose.slides.mathtext/mathematicaltext/radical/#str) | يحدد الجذر الرياضي للدرجة المعطاة من المعامل المحدد. |
| [`set_upper_limit(self, limit)`](/slides/python-net/ar/aspose.slides.mathtext/mathematicaltext/set_upper_limit/#imathelement) | يأخذ الحد العلوي |
| [`set_upper_limit(self, limit)`](/slides/python-net/ar/aspose.slides.mathtext/mathematicaltext/set_upper_limit/#str) | يأخذ الحد العلوي |
| [`set_lower_limit(self, limit)`](/slides/python-net/ar/aspose.slides.mathtext/mathematicaltext/set_lower_limit/#imathelement) | يأخذ الحد السفلي |
| [`set_lower_limit(self, limit)`](/slides/python-net/ar/aspose.slides.mathtext/mathematicaltext/set_lower_limit/#str) | يأخذ الحد السفلي |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/ar/aspose.slides.mathtext/mathematicaltext/nary/#mathnaryoperatortypes-imathelement-imathelement) | ينشئ عاملًا N-اريًا |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/ar/aspose.slides.mathtext/mathematicaltext/nary/#mathnaryoperatortypes-str-str) | ينشئ عاملًا N-اريًا |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/ar/aspose.slides.mathtext/mathematicaltext/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | يأخذ التكامل |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/ar/aspose.slides.mathtext/mathematicaltext/integral/#mathintegraltypes-imathelement-imathelement) | يأخذ التكامل |
| [`integral(self, integral_type)`](/slides/python-net/ar/aspose.slides.mathtext/mathematicaltext/integral/#mathintegraltypes) | يأخذ التكامل بدون حدود |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/ar/aspose.slides.mathtext/mathematicaltext/integral/#mathintegraltypes-str-str-mathlimitlocations) | يأخذ التكامل |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/ar/aspose.slides.mathtext/mathematicaltext/integral/#mathintegraltypes-str-str) | يأخذ التكامل |
| [`group(self)`](/slides/python-net/ar/aspose.slides.mathtext/mathematicaltext/group/#) | يضع هذا العنصر في مجموعة باستخدام قوس معقوف سفلي |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/ar/aspose.slides.mathtext/mathematicaltext/group/#char-mathtopbotpositions-mathtopbotpositions) | يضع هذا العنصر في مجموعة باستخدام حرف تجميع مثل القوس المعقوف السفلي أو غيره |
| [`to_border_box(self)`](/slides/python-net/ar/aspose.slides.mathtext/mathematicaltext/to_border_box/#) | يضع هذا العنصر في مربع حد |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/ar/aspose.slides.mathtext/mathematicaltext/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | يضع هذا العنصر في مربع حد |
| [`to_math_array(self)`](/slides/python-net/ar/aspose.slides.mathtext/mathematicaltext/to_math_array/#) | يوضع في مصفوفة رأسية |
| [`accent(self, accent_character)`](/slides/python-net/ar/aspose.slides.mathtext/mathematicaltext/accent/#char) | يضبط علامة شدة (حرف فوق هذا العنصر) |
| [`overbar(self)`](/slides/python-net/ar/aspose.slides.mathtext/mathematicaltext/overbar/#) | يضبط شريطًا فوق هذا العنصر |
| [`underbar(self)`](/slides/python-net/ar/aspose.slides.mathtext/mathematicaltext/underbar/#) | يضبط شريطًا أسفل هذا العنصر |
| [`to_box(self)`](/slides/python-net/ar/aspose.slides.mathtext/mathematicaltext/to_box/#) | يوضع هذا العنصر في مربع غير مرئي (تجميع منطقي) <br/>            الذي يُستخدم لتجميع مكونات معادلة أو مثال آخر للنص الرياضي.<br/>            يمكن أن يعمل الكائن المربع (على سبيل المثال) كمحاكي للمعامل مع أو بدون نقطة محاذاة، <br/>            يعمل كنقطة كسر سطر، أو يتم تجميعه بحيث لا يسمح بوجود كسر سطر داخله. |
| [`get_children(self)`](/slides/python-net/ar/aspose.slides.mathtext/mathematicaltext/get_children/#) |  |

### انظر أيضًا
* فئة [`MathElementBase`](/slides/python-net/ar/aspose.slides.mathtext/mathelementbase)
* فئة [`MathematicalText`](/slides/python-net/ar/aspose.slides.mathtext/mathematicaltext)
* الوحدة [`aspose.slides.mathtext`](/slides/python-net/ar/aspose.slides.mathtext)
* المكتبة [`Aspose.Slides`](/slides/python-net)