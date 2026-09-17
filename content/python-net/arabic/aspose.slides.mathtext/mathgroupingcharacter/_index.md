---
title: MathGroupingCharacter class
second_title: Aspose.Slides للبايثون عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides.mathtext/mathgroupingcharacter/
---
## فئة MathGroupingCharacter

يحدد رمز تجميع فوق أو تحت تعبير، عادةً لتسليط الضوء على العلاقة بين العناصر

**الوراثة:**[`MathGroupingCharacter`](/slides/python-net/ar/aspose.slides.mathtext/mathgroupingcharacter) → [`MathElementBase`](/slides/python-net/ar/aspose.slides.mathtext/mathelementbase)

نوع MathGroupingCharacter يكشف عن الأعضاء التالية:

## المنشئين

| منشئ | الوصف |
| :- | :- |
| [`__init__(self, element)`](/slides/python-net/ar/aspose.slides.mathtext/mathgroupingcharacter/__init__/#imathelement) | ينشئ مثيلاً جديداً لفئة MathGroupingCharacter <br/>            باستخدام رمز التجميع الافتراضي U+23DF (قوس معقوف سفلي) |
| [`__init__(self, element, character, position, vertical_justification)`](/slides/python-net/ar/aspose.slides.mathtext/mathgroupingcharacter/__init__/#imathelement-char-mathtopbotpositions-mathtopbotpositions) | ينشئ مثيلاً جديداً لفئة MathGroupingCharacter. |

## الخصائص

| الخاصية | الوصف |
| :- | :- |
| [`base`](/slides/python-net/ar/aspose.slides.mathtext/mathgroupingcharacter/base/) | معامل أساسي |
| [`character`](/slides/python-net/ar/aspose.slides.mathtext/mathgroupingcharacter/character/) | رمز التجميع<br/>            القيمة الافتراضية: U+23DF (قوس معقوف سفلي) |
| [`position`](/slides/python-net/ar/aspose.slides.mathtext/mathgroupingcharacter/position/) | موضع رمز التجميع.<br/>            القيمة الافتراضية: أسفل |
| [`vertical_justification`](/slides/python-net/ar/aspose.slides.mathtext/mathgroupingcharacter/vertical_justification/) | محاذاة رأسية لرمز المجموعة.<br/>            يحدد محاذاة الكائن بالنسبة إلى خط القاعدة.<br/>            على سبيل المثال، عندما يكون رمز المجموعة فوق الكائن، <br/>            يعني VerticalJustification لـ Top أن الجزء العلوي من الكائن يقع على خط القاعدة؛<br/>            عندما يتم تعيين VerticalJustification إلى Bottom، يكون الجزء السفلي من الكائن على خط القاعدة<br/>            الافتراضي: Bottom عندما Position=Top، وTop عندما Position=Bottom |

## الطرق

| الطريقة | الوصف |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/ar/aspose.slides.mathtext/mathgroupingcharacter/join/#imathelement) | يجمع عنصرًا رياضيًا ويشكل كتلة رياضية |
| [`join(self, math_text)`](/slides/python-net/ar/aspose.slides.mathtext/mathgroupingcharacter/join/#str) | يجمع نصًا رياضيًا ويشكل كتلة رياضية |
| [`divide(self, denominator)`](/slides/python-net/ar/aspose.slides.mathtext/mathgroupingcharacter/divide/#imathelement) | ينشئ كسرًا بهذا البسط والمقام المحدد |
| [`divide(self, denominator)`](/slides/python-net/ar/aspose.slides.mathtext/mathgroupingcharacter/divide/#str) | ينشئ كسرًا بهذا البسط والمقام المحدد |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/ar/aspose.slides.mathtext/mathgroupingcharacter/divide/#imathelement-mathfractiontypes) | ينشئ كسرًا من النوع المحدد بهذا البسط والمقام المحدد |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/ar/aspose.slides.mathtext/mathgroupingcharacter/divide/#str-mathfractiontypes) | ينشئ كسرًا من النوع المحدد بهذا البسط والمقام المحدد |
| [`enclose(self)`](/slides/python-net/ar/aspose.slides.mathtext/mathgroupingcharacter/enclose/#) | يضع عنصرًا رياضيًا بين أقواس |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/ar/aspose.slides.mathtext/mathgroupingcharacter/enclose/#char-char) | يضع عنصرًا رياضيًا بين أحرف محددة مثل الأقواس أو أحرف أخرى كإطار |
| [`function(self, function_argument)`](/slides/python-net/ar/aspose.slides.mathtext/mathgroupingcharacter/function/#imathelement) | يأخذ دالة لوسيط باستخدام هذا المثيل كاسم الدالة |
| [`function(self, function_argument)`](/slides/python-net/ar/aspose.slides.mathtext/mathgroupingcharacter/function/#str) | يأخذ دالة لوسيط باستخدام هذا المثيل كاسم الدالة |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/ar/aspose.slides.mathtext/mathgroupingcharacter/as_argument_of_function/#imathelement) | يأخذ دالة محددة باستخدام هذا المثيل كوسيطة |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/ar/aspose.slides.mathtext/mathgroupingcharacter/as_argument_of_function/#str) | يأخذ دالة محددة باستخدام هذا المثيل كوسيطة |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/ar/aspose.slides.mathtext/mathgroupingcharacter/as_argument_of_function/#mathfunctionsofoneargument) | يأخذ دالة محددة باستخدام هذا المثيل كوسيطة |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/ar/aspose.slides.mathtext/mathgroupingcharacter/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | يأخذ دالة محددة باستخدام هذا المثيل كوسيطة وإضافة وسيط إضافي محدد |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/ar/aspose.slides.mathtext/mathgroupingcharacter/as_argument_of_function/#mathfunctionsoftwoarguments-str) | يأخذ دالة محددة باستخدام هذا المثيل كوسيطة وإضافة وسيط إضافي محدد |
| [`set_subscript(self, subscript)`](/slides/python-net/ar/aspose.slides.mathtext/mathgroupingcharacter/set_subscript/#imathelement) | ينشئ نصًا سفليًا |
| [`set_subscript(self, subscript)`](/slides/python-net/ar/aspose.slides.mathtext/mathgroupingcharacter/set_subscript/#str) | ينشئ نصًا سفليًا |
| [`set_superscript(self, superscript)`](/slides/python-net/ar/aspose.slides.mathtext/mathgroupingcharacter/set_superscript/#imathelement) | ينشئ نصًا علويًا |
| [`set_superscript(self, superscript)`](/slides/python-net/ar/aspose.slides.mathtext/mathgroupingcharacter/set_superscript/#str) | ينشئ نصًا علويًا |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/ar/aspose.slides.mathtext/mathgroupingcharacter/set_sub_superscript_on_the_right/#imathelement-imathelement) | ينشئ نصًا سفليًا وعلويًا على اليمين |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/ar/aspose.slides.mathtext/mathgroupingcharacter/set_sub_superscript_on_the_right/#str-str) | ينشئ نصًا سفليًا وعلويًا على اليمين |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/ar/aspose.slides.mathtext/mathgroupingcharacter/set_sub_superscript_on_the_left/#imathelement-imathelement) | ينشئ نصًا سفليًا وعلويًا على اليسار |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/ar/aspose.slides.mathtext/mathgroupingcharacter/set_sub_superscript_on_the_left/#str-str) | ينشئ نصًا سفليًا وعلويًا على اليسار |
| [`radical(self, degree)`](/slides/python-net/ar/aspose.slides.mathtext/mathgroupingcharacter/radical/#imathelement) | يحدد الجذر الرياضي للدرجة المحددة من الوسيط المحدد. |
| [`radical(self, degree)`](/slides/python-net/ar/aspose.slides.mathtext/mathgroupingcharacter/radical/#str) | يحدد الجذر الرياضي للدرجة المحددة من الوسيط المحدد. |
| [`set_upper_limit(self, limit)`](/slides/python-net/ar/aspose.slides.mathtext/mathgroupingcharacter/set_upper_limit/#imathelement) | يأخذ حدًا أعلى |
| [`set_upper_limit(self, limit)`](/slides/python-net/ar/aspose.slides.mathtext/mathgroupingcharacter/set_upper_limit/#str) | يأخذ حدًا أعلى |
| [`set_lower_limit(self, limit)`](/slides/python-net/ar/aspose.slides.mathtext/mathgroupingcharacter/set_lower_limit/#imathelement) | يأخذ حدًا سفليًا |
| [`set_lower_limit(self, limit)`](/slides/python-net/ar/aspose.slides.mathtext/mathgroupingcharacter/set_lower_limit/#str) | يأخذ حدًا سفليًا |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/ar/aspose.slides.mathtext/mathgroupingcharacter/nary/#mathnaryoperatortypes-imathelement-imathelement) | ينشئ عاملًا متعدد الحدود |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/ar/aspose.slides.mathtext/mathgroupingcharacter/nary/#mathnaryoperatortypes-str-str) | ينشئ عاملًا متعدد الحدود |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/ar/aspose.slides.mathtext/mathgroupingcharacter/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | يأخذ التكامل |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/ar/aspose.slides.mathtext/mathgroupingcharacter/integral/#mathintegraltypes-imathelement-imathelement) | يأخذ التكامل |
| [`integral(self, integral_type)`](/slides/python-net/ar/aspose.slides.mathtext/mathgroupingcharacter/integral/#mathintegraltypes) | يأخذ التكامل بدون حدود |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/ar/aspose.slides.mathtext/mathgroupingcharacter/integral/#mathintegraltypes-str-str-mathlimitlocations) | يأخذ التكامل |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/ar/aspose.slides.mathtext/mathgroupingcharacter/integral/#mathintegraltypes-str-str) | يأخذ التكامل |
| [`group(self)`](/slides/python-net/ar/aspose.slides.mathtext/mathgroupingcharacter/group/#) | يضع هذا العنصر في مجموعة باستخدام قوس معقوف سفلي |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/ar/aspose.slides.mathtext/mathgroupingcharacter/group/#char-mathtopbotpositions-mathtopbotpositions) | يضع هذا العنصر في مجموعة باستخدام رمز تجميع مثل قوس معقوف سفلي أو آخر |
| [`to_border_box(self)`](/slides/python-net/ar/aspose.slides.mathtext/mathgroupingcharacter/to_border_box/#) | يضع هذا العنصر في إطار حدود |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/ar/aspose.slides.mathtext/mathgroupingcharacter/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | يضع هذا العنصر في إطار حدود |
| [`to_math_array(self)`](/slides/python-net/ar/aspose.slides.mathtext/mathgroupingcharacter/to_math_array/#) | يضعه في مصفوفة رأسية |
| [`accent(self, accent_character)`](/slides/python-net/ar/aspose.slides.mathtext/mathgroupingcharacter/accent/#char) | يحدد علامة لهجة (حرف فوق هذا العنصر) |
| [`overbar(self)`](/slides/python-net/ar/aspose.slides.mathtext/mathgroupingcharacter/overbar/#) | يضع شريطًا فوق هذا العنصر |
| [`underbar(self)`](/slides/python-net/ar/aspose.slides.mathtext/mathgroupingcharacter/underbar/#) | يضع شريطًا تحت هذا العنصر |
| [`to_box(self)`](/slides/python-net/ar/aspose.slides.mathtext/mathgroupingcharacter/to_box/#) | يضع هذا العنصر في صندوق غير مرئي (تجميع منطقي) <br/>            يستخدم لتجميع مكونات معادلة أو مثال آخر من النص الرياضي.<br/>            يمكن أن يعمل كجهاز محاكاة للمعامل مع أو بدون نقطة محاذاة، <br/>            أو كنقطة كسر سطر، أو يتم تجميعه بحيث لا يسمح بكسور سطر داخله. |
| [`get_children(self)`](/slides/python-net/ar/aspose.slides.mathtext/mathgroupingcharacter/get_children/#) | الحصول على عناصر الأطفال |

### أنظر أيضًا
* فئة [`MathElementBase`](/slides/python-net/ar/aspose.slides.mathtext/mathelementbase)
* فئة [`MathGroupingCharacter`](/slides/python-net/ar/aspose.slides.mathtext/mathgroupingcharacter)
* وحدة [`aspose.slides.mathtext`](/slides/python-net/ar/aspose.slides.mathtext)
* مكتبة [`Aspose.Slides`](/slides/python-net)