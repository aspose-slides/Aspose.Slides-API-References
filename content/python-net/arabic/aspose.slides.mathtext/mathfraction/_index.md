---
title: MathFraction class
second_title: Aspose.Slides للبايثون عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides.mathtext/mathfraction/
---
## فئة MathFraction

يحدد كائن الكسر، المكوّن من البسط والمقام المفصولين بشريط الكسر.
            يمكن أن يكون شريط الكسر أفقيًا أو مائلًا، حسب خصائص الكسر.
            يُستخدم كائن الكسر أيضًا لتمثيل دالة التكدس، التي تضع عنصرًا فوق آخر دون شريط كسر.

**الوراثة:**[`MathFraction`](/slides/python-net/ar/aspose.slides.mathtext/mathfraction) → [`MathElementBase`](/slides/python-net/ar/aspose.slides.mathtext/mathelementbase)

يعرض نوع MathFraction الأعضاء التاليين:

## المنشئات

| المنشئ | الوصف |
| :- | :- |
| [`__init__(self, numerator, denominator, fraction_type)`](/slides/python-net/ar/aspose.slides.mathtext/mathfraction/__init__/#imathelement-imathelement-mathfractiontypes) | يُهيئ MathFraction بالعدد البسط والمقام والنوع المحددين |
| [`__init__(self, numerator, denominator)`](/slides/python-net/ar/aspose.slides.mathtext/mathfraction/__init__/#imathelement-imathelement) | يُهيئ MathFraction من النوع 'Bar' بالعدد البسط والمقام المحددين |

## الخصائص

| الخاصية | الوصف |
| :- | :- |
| [`fraction_type`](/slides/python-net/ar/aspose.slides.mathtext/mathfraction/fraction_type/) | نوع الكسر<br/>            القيمة الافتراضية: Bar |
| [`numerator`](/slides/python-net/ar/aspose.slides.mathtext/mathfraction/numerator/) | البسط |
| [`denominator`](/slides/python-net/ar/aspose.slides.mathtext/mathfraction/denominator/) | المقام |

## الطرق

| الطريقة | الوصف |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/ar/aspose.slides.mathtext/mathfraction/join/#imathelement) | يجمع عنصرًا رياضيًا ويكوّن كتلة رياضية |
| [`join(self, math_text)`](/slides/python-net/ar/aspose.slides.mathtext/mathfraction/join/#str) | يجمع نصًا رياضيًا ويكوّن كتلة رياضية |
| [`divide(self, denominator)`](/slides/python-net/ar/aspose.slides.mathtext/mathfraction/divide/#imathelement) | ينشئ كسرًا بهذا البسط والمقام المحدد |
| [`divide(self, denominator)`](/slides/python-net/ar/aspose.slides.mathtext/mathfraction/divide/#str) | ينشئ كسرًا بهذا البسط والمقام المحدد |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/ar/aspose.slides.mathtext/mathfraction/divide/#imathelement-mathfractiontypes) | ينشئ كسرًا من النوع المحدد بهذا البسط والمقام المحدد |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/ar/aspose.slides.mathtext/mathfraction/divide/#str-mathfractiontypes) | ينشئ كسرًا من النوع المحدد بهذا البسط والمقام المحدد |
| [`enclose(self)`](/slides/python-net/ar/aspose.slides.mathtext/mathfraction/enclose/#) | يُحِط عنصرًا رياضيًا بأقواس |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/ar/aspose.slides.mathtext/mathfraction/enclose/#char-char) | يُحِط عنصرًا رياضيًا بأحرف محددة مثل الأقواس أو أحرف أخرى كإطار |
| [`function(self, function_argument)`](/slides/python-net/ar/aspose.slides.mathtext/mathfraction/function/#imathelement) | يأخذ دالة للمعامل باستخدام هذا المثيل كاسم الدالة |
| [`function(self, function_argument)`](/slides/python-net/ar/aspose.slides.mathtext/mathfraction/function/#str) | يأخذ دالة للمعامل باستخدام هذا المثيل كاسم الدالة |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/ar/aspose.slides.mathtext/mathfraction/as_argument_of_function/#imathelement) | يأخذ الدالة المحددة باستخدام هذا المثيل كمعامل |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/ar/aspose.slides.mathtext/mathfraction/as_argument_of_function/#str) | يأخذ الدالة المحددة باستخدام هذا المثيل كمعامل |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/ar/aspose.slides.mathtext/mathfraction/as_argument_of_function/#mathfunctionsofoneargument) | يأخذ الدالة المحددة باستخدام هذا المثيل كمعامل |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/ar/aspose.slides.mathtext/mathfraction/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | يأخذ الدالة المحددة باستخدام هذا المثيل كمعامل ومعامل إضافي محدد |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/ar/aspose.slides.mathtext/mathfraction/as_argument_of_function/#mathfunctionsoftwoarguments-str) | يأخذ الدالة المحددة باستخدام هذا المثيل كمعامل ومعامل إضافي محدد |
| [`set_subscript(self, subscript)`](/slides/python-net/ar/aspose.slides.mathtext/mathfraction/set_subscript/#imathelement) | ينشئ نصًا سفليًا |
| [`set_subscript(self, subscript)`](/slides/python-net/ar/aspose.slides.mathtext/mathfraction/set_subscript/#str) | ينشئ نصًا سفليًا |
| [`set_superscript(self, superscript)`](/slides/python-net/ar/aspose.slides.mathtext/mathfraction/set_superscript/#imathelement) | ينشئ نصًا علويًا |
| [`set_superscript(self, superscript)`](/slides/python-net/ar/aspose.slides.mathtext/mathfraction/set_superscript/#str) | ينشئ نصًا علويًا |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/ar/aspose.slides.mathtext/mathfraction/set_sub_superscript_on_the_right/#imathelement-imathelement) | ينشئ نصًا سفليًا وعلويًا على اليمين |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/ar/aspose.slides.mathtext/mathfraction/set_sub_superscript_on_the_right/#str-str) | ينشئ نصًا سفليًا وعلويًا على اليمين |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/ar/aspose.slides.mathtext/mathfraction/set_sub_superscript_on_the_left/#imathelement-imathelement) | ينشئ نصًا سفليًا وعلويًا على اليسار |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/ar/aspose.slides.mathtext/mathfraction/set_sub_superscript_on_the_left/#str-str) | ينشئ نصًا سفليًا وعلويًا على اليسار |
| [`radical(self, degree)`](/slides/python-net/ar/aspose.slides.mathtext/mathfraction/radical/#imathelement) | يحدد الجذر الرياضي للدرجة المعطاة من المعامل المحدد. |
| [`radical(self, degree)`](/slides/python-net/ar/aspose.slides.mathtext/mathfraction/radical/#str) | يحدد الجذر الرياضي للدرجة المعطاة من المعامل المحدد. |
| [`set_upper_limit(self, limit)`](/slides/python-net/ar/aspose.slides.mathtext/mathfraction/set_upper_limit/#imathelement) | يأخذ حدًا أعلى |
| [`set_upper_limit(self, limit)`](/slides/python-net/ar/aspose.slides.mathtext/mathfraction/set_upper_limit/#str) | يأخذ حدًا أعلى |
| [`set_lower_limit(self, limit)`](/slides/python-net/ar/aspose.slides.mathtext/mathfraction/set_lower_limit/#imathelement) | يأخذ حدًا سفليًا |
| [`set_lower_limit(self, limit)`](/slides/python-net/ar/aspose.slides.mathtext/mathfraction/set_lower_limit/#str) | يأخذ حدًا سفليًا |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/ar/aspose.slides.mathtext/mathfraction/nary/#mathnaryoperatortypes-imathelement-imathelement) | ينشئ مشغلًا N-ary |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/ar/aspose.slides.mathtext/mathfraction/nary/#mathnaryoperatortypes-str-str) | ينشئ مشغلًا N-ary |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/ar/aspose.slides.mathtext/mathfraction/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | يأخذ التكامل |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/ar/aspose.slides.mathtext/mathfraction/integral/#mathintegraltypes-imathelement-imathelement) | يأخذ التكامل |
| [`integral(self, integral_type)`](/slides/python-net/ar/aspose.slides.mathtext/mathfraction/integral/#mathintegraltypes) | يأخذ التكامل بدون حدود |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/ar/aspose.slides.mathtext/mathfraction/integral/#mathintegraltypes-str-str-mathlimitlocations) | يأخذ التكامل |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/ar/aspose.slides.mathtext/mathfraction/integral/#mathintegraltypes-str-str) | يأخذ التكامل |
| [`group(self)`](/slides/python-net/ar/aspose.slides.mathtext/mathfraction/group/#) | يضع هذا العنصر في مجموعة باستخدام قوس معقوف سفلي |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/ar/aspose.slides.mathtext/mathfraction/group/#char-mathtopbotpositions-mathtopbotpositions) | يضع هذا العنصر في مجموعة باستخدام حرف تجميع مثل القوس المعقوف السفلي أو غيره |
| [`to_border_box(self)`](/slides/python-net/ar/aspose.slides.mathtext/mathfraction/to_border_box/#) | يضع هذا العنصر في مربع حدود |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/ar/aspose.slides.mathtext/mathfraction/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | يضع هذا العنصر في مربع حدود |
| [`to_math_array(self)`](/slides/python-net/ar/aspose.slides.mathtext/mathfraction/to_math_array/#) | يضع في مصفوفة عمودية |
| [`accent(self, accent_character)`](/slides/python-net/ar/aspose.slides.mathtext/mathfraction/accent/#char) | يضبط علامة تشديد (حرف فوق هذا العنصر) |
| [`overbar(self)`](/slides/python-net/ar/aspose.slides.mathtext/mathfraction/overbar/#) | يضبط شريطًا فوق هذا العنصر |
| [`underbar(self)`](/slides/python-net/ar/aspose.slides.mathtext/mathfraction/underbar/#) | يضبط شريطًا أسفل هذا العنصر |
| [`to_box(self)`](/slides/python-net/ar/aspose.slides.mathtext/mathfraction/to_box/#) | يضع هذا العنصر في صندوق غير مرئي (تجميع منطقي)<br/>            يُستخدم لتجميع مكونات معادلة أو نسخة أخرى من النص الرياضي.<br/>            يمكن للكائن في صندوق (على سبيل المثال) أن يعمل كمحاكي لمشغل مع أو بدون نقطة محاذاة،<br/>            يعمل كنقطة كسر سطر، أو يُجمع بحيث لا يسمح بوجود فواصل سطر داخلها. |
| [`get_children(self)`](/slides/python-net/ar/aspose.slides.mathtext/mathfraction/get_children/#) | احصل على العناصر الفرعية |

### انظر أيضا
* فئة [`MathElementBase`](/slides/python-net/ar/aspose.slides.mathtext/mathelementbase)
* فئة [`MathFraction`](/slides/python-net/ar/aspose.slides.mathtext/mathfraction)
* وحدة [`aspose.slides.mathtext`](/slides/python-net/ar/aspose.slides.mathtext)
* مكتبة [`Aspose.Slides`](/slides/python-net)