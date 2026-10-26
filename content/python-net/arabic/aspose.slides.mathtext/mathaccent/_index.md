---
title: MathAccent class
second_title: مرجع API لـ Aspose.Slides للغة Python عبر .NET
description: 
type: docs
url: /ar/aspose.slides.mathtext/mathaccent/
---
## فئة MathAccent

يحدد دالة التشكيل، المكونة من قاعدة وعلامة تشكيل مركبة
            مثال: 𝑎́

**Inheritance:**[`MathAccent`](/slides/python-net/ar/aspose.slides.mathtext/mathaccent) → [`MathElementBase`](/slides/python-net/ar/aspose.slides.mathtext/mathelementbase)

تُظهر فئة MathAccent الأعضاء التالية:

## المنشئات

| المنشئ | الوصف |
| :- | :- |
| [`__init__(self, element)`](/slides/python-net/ar/aspose.slides.mathtext/mathaccent/__init__/#imathelement) | ينشئ تشكيلة رياضية تُطبق على عنصر رياضي محدد باستخدام قيمة حرف التشكيل الافتراضية |
| [`__init__(self, element, accent_character)`](/slides/python-net/ar/aspose.slides.mathtext/mathaccent/__init__/#imathelement-char) | ينشئ تشكيلة رياضية تُطبق على عنصر رياضي محدد |

## الخصائص

| الخاصية | الوصف |
| :- | :- |
| [`base`](/slides/python-net/ar/aspose.slides.mathtext/mathaccent/base/) | المعامل الذي تم تطبيق التشكيل عليه |
| [`character`](/slides/python-net/ar/aspose.slides.mathtext/mathaccent/character/) | حرف التشكيل<br/>            يجب أن تكون القيمة ضمن النطاق (U+0300–U+036F) أو (U+20D0–U+20EF)<br/>            القيمة الافتراضية: Combining Circumflex Accent (U+0302) |

## الطرق

| الطريقة | الوصف |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/ar/aspose.slides.mathtext/mathaccent/join/#imathelement) | يجمع عنصرًا رياضيًا ويشكل كتلة رياضية |
| [`join(self, math_text)`](/slides/python-net/ar/aspose.slides.mathtext/mathaccent/join/#str) | يجمع نصًا رياضيًا ويشكل كتلة رياضية |
| [`divide(self, denominator)`](/slides/python-net/ar/aspose.slides.mathtext/mathaccent/divide/#imathelement) | ينشئ كسرًا بهذا البسط ومقام محدد |
| [`divide(self, denominator)`](/slides/python-net/ar/aspose.slides.mathtext/mathaccent/divide/#str) | ينشئ كسرًا بهذا البسط ومقام محدد |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/ar/aspose.slides.mathtext/mathaccent/divide/#imathelement-mathfractiontypes) | ينشئ كسرًا من النوع المحدد بهذا البسط ومقام محدد |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/ar/aspose.slides.mathtext/mathaccent/divide/#str-mathfractiontypes) | ينشئ كسرًا من النوع المحدد بهذا البسط ومقام محدد |
| [`enclose(self)`](/slides/python-net/ar/aspose.slides.mathtext/mathaccent/enclose/#) | يحيط عنصرًا رياضيًا بأقواس |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/ar/aspose.slides.mathtext/mathaccent/enclose/#char-char) | يحيط عنصرًا رياضيًا بأحرف محددة مثل الأقواس أو أحرف أخرى كإطار |
| [`function(self, function_argument)`](/slides/python-net/ar/aspose.slides.mathtext/mathaccent/function/#imathelement) | يأخذ دالة بمعامل باستخدام هذا المثال كاسم الدالة |
| [`function(self, function_argument)`](/slides/python-net/ar/aspose.slides.mathtext/mathaccent/function/#str) | يأخذ دالة بمعامل باستخدام هذا المثال كاسم الدالة |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/ar/aspose.slides.mathtext/mathaccent/as_argument_of_function/#imathelement) | يأخذ الدالة المحددة باستخدام هذا المثال كمعامل |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/ar/aspose.slides.mathtext/mathaccent/as_argument_of_function/#str) | يأخذ الدالة المحددة باستخدام هذا المثال كمعامل |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/ar/aspose.slides.mathtext/mathaccent/as_argument_of_function/#mathfunctionsofoneargument) | يأخذ الدالة المحددة باستخدام هذا المثال كمعامل |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/ar/aspose.slides.mathtext/mathaccent/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | يأخذ الدالة المحددة باستخدام هذا المثال كمعامل ومعامل إضافي محدد |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/ar/aspose.slides.mathtext/mathaccent/as_argument_of_function/#mathfunctionsoftwoarguments-str) | يأخذ الدالة المحددة باستخدام هذا المثال كمعامل ومعامل إضافي محدد |
| [`set_subscript(self, subscript)`](/slides/python-net/ar/aspose.slides.mathtext/mathaccent/set_subscript/#imathelement) | ينشئ حروفًا سفلية |
| [`set_subscript(self, subscript)`](/slides/python-net/ar/aspose.slides.mathtext/mathaccent/set_subscript/#str) | ينشئ حروفًا سفلية |
| [`set_superscript(self, superscript)`](/slides/python-net/ar/aspose.slides.mathtext/mathaccent/set_superscript/#imathelement) | ينشئ حروفًا علوية |
| [`set_superscript(self, superscript)`](/slides/python-net/ar/aspose.slides.mathtext/mathaccent/set_superscript/#str) | ينشئ حروفًا علوية |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/ar/aspose.slides.mathtext/mathaccent/set_sub_superscript_on_the_right/#imathelement-imathelement) | ينشئ حروفًا سفلية وعلوية على اليمين |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/ar/aspose.slides.mathtext/mathaccent/set_sub_superscript_on_the_right/#str-str) | ينشئ حروفًا سفلية وعلوية على اليمين |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/ar/aspose.slides.mathtext/mathaccent/set_sub_superscript_on_the_left/#imathelement-imathelement) | ينشئ حروفًا سفلية وعلوية على اليسار |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/ar/aspose.slides.mathtext/mathaccent/set_sub_superscript_on_the_left/#str-str) | ينشئ حروفًا سفلية وعلوية على اليسار |
| [`radical(self, degree)`](/slides/python-net/ar/aspose.slides.mathtext/mathaccent/radical/#imathelement) | يحدد الجذر الرياضي للدرجة المعطاة من المعامل المحدد. |
| [`radical(self, degree)`](/slides/python-net/ar/aspose.slides.mathtext/mathaccent/radical/#str) | يحدد الجذر الرياضي للدرجة المعطاة من المعامل المحدد. |
| [`set_upper_limit(self, limit)`](/slides/python-net/ar/aspose.slides.mathtext/mathaccent/set_upper_limit/#imathelement) | يأخذ الحد الأعلى |
| [`set_upper_limit(self, limit)`](/slides/python-net/ar/aspose.slides.mathtext/mathaccent/set_upper_limit/#str) | أعلى حد |
| [`set_lower_limit(self, limit)`](/slides/python-net/ar/aspose.slides.mathtext/mathaccent/set_lower_limit/#imathelement) | يأخذ الحد الأدنى |
| [`set_lower_limit(self, limit)`](/slides/python-net/ar/aspose.slides.mathtext/mathaccent/set_lower_limit/#str) | الحد الأدنى |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/ar/aspose.slides.mathtext/mathaccent/nary/#mathnaryoperatortypes-imathelement-imathelement) | ينشئ مشغل N-ary |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/ar/aspose.slides.mathtext/mathaccent/nary/#mathnaryoperatortypes-str-str) | ينشئ مشغل N-ary |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/ar/aspose.slides.mathtext/mathaccent/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | يأخذ التكامل |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/ar/aspose.slides.mathtext/mathaccent/integral/#mathintegraltypes-imathelement-imathelement) | يأخذ التكامل |
| [`integral(self, integral_type)`](/slides/python-net/ar/aspose.slides.mathtext/mathaccent/integral/#mathintegraltypes) | يأخذ التكامل بدون حدود |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/ar/aspose.slides.mathtext/mathaccent/integral/#mathintegraltypes-str-str-mathlimitlocations) | يأخذ التكامل |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/ar/aspose.slides.mathtext/mathaccent/integral/#mathintegraltypes-str-str) | يأخذ التكامل |
| [`group(self)`](/slides/python-net/ar/aspose.slides.mathtext/mathaccent/group/#) | يضع هذا العنصر في مجموعة باستخدام قوس معقوف سفلي |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/ar/aspose.slides.mathtext/mathaccent/group/#char-mathtopbotpositions-mathtopbotpositions) | يضع هذا العنصر في مجموعة باستخدام رمز تجميع مثل قوس معقوف سفلي أو غيره |
| [`to_border_box(self)`](/slides/python-net/ar/aspose.slides.mathtext/mathaccent/to_border_box/#) | يضع هذا العنصر في صندوق حد |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/ar/aspose.slides.mathtext/mathaccent/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | يضع هذا العنصر في صندوق حد |
| [`to_math_array(self)`](/slides/python-net/ar/aspose.slides.mathtext/mathaccent/to_math_array/#) | يضع في مصفوفة رأسية |
| [`accent(self, accent_character)`](/slides/python-net/ar/aspose.slides.mathtext/mathaccent/accent/#char) | يضبط علامة تشكيل (حرف على أعلى هذا العنصر) |
| [`overbar(self)`](/slides/python-net/ar/aspose.slides.mathtext/mathaccent/overbar/#) | يضبط شريطًا على أعلى هذا العنصر |
| [`underbar(self)`](/slides/python-net/ar/aspose.slides.mathtext/mathaccent/underbar/#) | يضبط شريطًا على أسفل هذا العنصر |
| [`to_box(self)`](/slides/python-net/ar/aspose.slides.mathtext/mathaccent/to_box/#) | يضع هذا العنصر في صندوق غير مرئي (تجميع منطقي) <br/>            يُستخدم لتجميع مكونات معادلة أو مثال آخر من النص الرياضي.<br/>            يمكن لكائن مغلق (على سبيل المثال) أن يعمل كمحاكي معامل مع أو بدون نقطة محاذاة، <br/>            يعمل كنقطة فاصل سطر، أو يُجمّع بحيث لا يسمح بفواصل أسطر داخله. |
| [`get_children(self)`](/slides/python-net/ar/aspose.slides.mathtext/mathaccent/get_children/#) | الحصول على العناصر الفرعية |

### انظر أيضًا
* فئة [`MathAccent`](/slides/python-net/ar/aspose.slides.mathtext/mathaccent)
* فئة [`MathElementBase`](/slides/python-net/ar/aspose.slides.mathtext/mathelementbase)
* وحدة [`aspose.slides.mathtext`](/slides/python-net/ar/aspose.slides.mathtext)
* مكتبة [`Aspose.Slides`](/slides/python-net)