---
title: MathBar class
second_title: Aspose.Slides للـ Python عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides.mathtext/mathbar/
---
## فئة MathBar

يحدد دالة الشريط، المتكوّنة من معامل أساسي وشريط فوقي أو سفلي

**الوراثة:**[`MathBar`](/slides/python-net/ar/aspose.slides.mathtext/mathbar) → [`MathElementBase`](/slides/python-net/ar/aspose.slides.mathtext/mathelementbase)

نوع MathBar يعرّض الأعضاء التالية:

## المنشئون

| المنشئ | الوصف |
| :- | :- |
| [`__init__(self, element)`](/slides/python-net/ar/aspose.slides.mathtext/mathbar/__init__/#imathelement) | يُهيّء MathBar مع شريط فوقي (الموضع الأعلى) |
| [`__init__(self, element, position)`](/slides/python-net/ar/aspose.slides.mathtext/mathbar/__init__/#imathelement-mathtopbotpositions) | يُهيّء MathBar مع موضع محدد |

## الخصائص

| الخاصية | الوصف |
| :- | :- |
| [`base`](/slides/python-net/ar/aspose.slides.mathtext/mathbar/base/) | معامل أساسي |
| [`position`](/slides/python-net/ar/aspose.slides.mathtext/mathbar/position/) | موضع خط الشريط. <br/>            الافتراضي: الأعلى |

## الطرق

| الطريقة | الوصف |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/ar/aspose.slides.mathtext/mathbar/join/#imathelement) | يجمع عنصرًا رياضيًا ويكوّن كتلة رياضية |
| [`join(self, math_text)`](/slides/python-net/ar/aspose.slides.mathtext/mathbar/join/#str) | يجمع نصًا رياضيًا ويكوّن كتلة رياضية |
| [`divide(self, denominator)`](/slides/python-net/ar/aspose.slides.mathtext/mathbar/divide/#imathelement) | ينشئ كسرًا بهذا البسط والمقام المحدد |
| [`divide(self, denominator)`](/slides/python-net/ar/aspose.slides.mathtext/mathbar/divide/#str) | ينشئ كسرًا بهذا البسط والمقام المحدد |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/ar/aspose.slides.mathtext/mathbar/divide/#imathelement-mathfractiontypes) | ينشئ كسرًا من النوع المحدد بهذا البسط والمقام المحدد |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/ar/aspose.slides.mathtext/mathbar/divide/#str-mathfractiontypes) | ينشئ كسرًا من النوع المحدد بهذا البسط والمقام المحدد |
| [`enclose(self)`](/slides/python-net/ar/aspose.slides.mathtext/mathbar/enclose/#) | يضع عنصرًا رياضيًا بين أقواس |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/ar/aspose.slides.mathtext/mathbar/enclose/#char-char) | يحيط عنصر رياضي بأحرف محددة مثل الأقواس أو أحرف أخرى كإطار |
| [`function(self, function_argument)`](/slides/python-net/ar/aspose.slides.mathtext/mathbar/function/#imathelement) | يأخذ دالة للمعامل باستخدام هذا الكائن كاسم الدالة |
| [`function(self, function_argument)`](/slides/python-net/ar/aspose.slides.mathtext/mathbar/function/#str) | يأخذ دالة للمعامل باستخدام هذا الكائن كاسم الدالة |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/ar/aspose.slides.mathtext/mathbar/as_argument_of_function/#imathelement) | يأخذ دالة محددة باستخدام هذا الكائن كمعامل |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/ar/aspose.slides.mathtext/mathbar/as_argument_of_function/#str) | يأخذ دالة محددة باستخدام هذا الكائن كمعامل |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/ar/aspose.slides.mathtext/mathbar/as_argument_of_function/#mathfunctionsofoneargument) | يأخذ دالة محددة باستخدام هذا الكائن كمعامل |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/ar/aspose.slides.mathtext/mathbar/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | يأخذ دالة محددة باستخدام هذا الكائن كمعامل ومعامل إضافي محدد |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/ar/aspose.slides.mathtext/mathbar/as_argument_of_function/#mathfunctionsoftwoarguments-str) | يأخذ دالة محددة باستخدام هذا الكائن كمعامل ومعامل إضافي محدد |
| [`set_subscript(self, subscript)`](/slides/python-net/ar/aspose.slides.mathtext/mathbar/set_subscript/#imathelement) | ينشئ حرفًا سفليًا |
| [`set_subscript(self, subscript)`](/slides/python-net/ar/aspose.slides.mathtext/mathbar/set_subscript/#str) | ينشئ حرفًا سفليًا |
| [`set_superscript(self, superscript)`](/slides/python-net/ar/aspose.slides.mathtext/mathbar/set_superscript/#imathelement) | ينشئ حرفًا علويًا |
| [`set_superscript(self, superscript)`](/slides/python-net/ar/aspose.slides.mathtext/mathbar/set_superscript/#str) | ينشئ حرفًا علويًا |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/ar/aspose.slides.mathtext/mathbar/set_sub_superscript_on_the_right/#imathelement-imathelement) | ينشئ حرفًا سفليًا وعلويًا على اليمين |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/ar/aspose.slides.mathtext/mathbar/set_sub_superscript_on_the_right/#str-str) | ينشئ حرفًا سفليًا وعلويًا على اليمين |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/ar/aspose.slides.mathtext/mathbar/set_sub_superscript_on_the_left/#imathelement-imathelement) | ينشئ حرفًا سفليًا وعلويًا على اليسار |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/ar/aspose.slides.mathtext/mathbar/set_sub_superscript_on_the_left/#str-str) | ينشئ حرفًا سفليًا وعلويًا على اليسار |
| [`radical(self, degree)`](/slides/python-net/ar/aspose.slides.mathtext/mathbar/radical/#imathelement) | يحدد الجذر الرياضي للدرجة المعطاة من المعامل المحدد. |
| [`radical(self, degree)`](/slides/python-net/ar/aspose.slides.mathtext/mathbar/radical/#str) | يحدد الجذر الرياضي للدرجة المعطاة من المعامل المحدد. |
| [`set_upper_limit(self, limit)`](/slides/python-net/ar/aspose.slides.mathtext/mathbar/set_upper_limit/#imathelement) | يأخذ الحد العلوي |
| [`set_upper_limit(self, limit)`](/slides/python-net/ar/aspose.slides.mathtext/mathbar/set_upper_limit/#str) | يأخذ الحد العلوي |
| [`set_lower_limit(self, limit)`](/slides/python-net/ar/aspose.slides.mathtext/mathbar/set_lower_limit/#imathelement) | يأخذ الحد السفلي |
| [`set_lower_limit(self, limit)`](/slides/python-net/ar/aspose.slides.mathtext/mathbar/set_lower_limit/#str) | يأخذ الحد السفلي |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/ar/aspose.slides.mathtext/mathbar/nary/#mathnaryoperatortypes-imathelement-imathelement) | ينشئ مشغلًا متعدد المتغيرات |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/ar/aspose.slides.mathtext/mathbar/nary/#mathnaryoperatortypes-str-str) | ينشئ مشغلًا متعدد المتغيرات |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/ar/aspose.slides.mathtext/mathbar/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | يأخذ التكامل |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/ar/aspose.slides.mathtext/mathbar/integral/#mathintegraltypes-imathelement-imathelement) | يأخذ التكامل |
| [`integral(self, integral_type)`](/slides/python-net/ar/aspose.slides.mathtext/mathbar/integral/#mathintegraltypes) | يأخذ التكامل بدون حدود |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/ar/aspose.slides.mathtext/mathbar/integral/#mathintegraltypes-str-str-mathlimitlocations) | يأخذ التكامل |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/ar/aspose.slides.mathtext/mathbar/integral/#mathintegraltypes-str-str) | يأخذ التكامل |
| [`group(self)`](/slides/python-net/ar/aspose.slides.mathtext/mathbar/group/#) | يضع هذا العنصر في مجموعة باستخدام قوس معقوف سفلي |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/ar/aspose.slides.mathtext/mathbar/group/#char-mathtopbotpositions-mathtopbotpositions) | يضع هذا العنصر في مجموعة باستخدام حرف تجميع مثل القوس المعقوف السفلي أو غيره |
| [`to_border_box(self)`](/slides/python-net/ar/aspose.slides.mathtext/mathbar/to_border_box/#) | يضع هذا العنصر في صندوق حدود |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/ar/aspose.slides.mathtext/mathbar/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | يضع هذا العنصر في صندوق حدود |
| [`to_math_array(self)`](/slides/python-net/ar/aspose.slides.mathtext/mathbar/to_math_array/#) | يضعه في صف عمودي |
| [`accent(self, accent_character)`](/slides/python-net/ar/aspose.slides.mathtext/mathbar/accent/#char) | يضبط علامة لهجة (حرف فوق هذا العنصر) |
| [`overbar(self)`](/slides/python-net/ar/aspose.slides.mathtext/mathbar/overbar/#) | يضبط شريطًا فوق هذا العنصر |
| [`underbar(self)`](/slides/python-net/ar/aspose.slides.mathtext/mathbar/underbar/#) | يضبط شريطًا أسفل هذا العنصر |
| [`to_box(self)`](/slides/python-net/ar/aspose.slides.mathtext/mathbar/to_box/#) | يوضع هذا العنصر في صندوق غير مرئي (تجميع منطقي) <br/>            يُستَخدم لتجميع مكوّنات معادلة أو نص رياضي آخر.<br/>            يمكن أن يعمل الكائن المعبأ (على سبيل المثال) كمحاكي مشغل مع أو بدون نقطة محاذاة، <br/>            يعمل كنقطة فاصل سطر، أو يُجمّع بحيث لا يسمح بوجود فواصل سطر داخله. |
| [`get_children(self)`](/slides/python-net/ar/aspose.slides.mathtext/mathbar/get_children/#) | يحصل على عناصر الأطفال |

### انظر أيضا
* فئة [`MathBar`](/slides/python-net/ar/aspose.slides.mathtext/mathbar)
* فئة [`MathElementBase`](/slides/python-net/ar/aspose.slides.mathtext/mathelementbase)
* وحدة [`aspose.slides.mathtext`](/slides/python-net/ar/aspose.slides.mathtext)
* مكتبة [`Aspose.Slides`](/slides/python-net)