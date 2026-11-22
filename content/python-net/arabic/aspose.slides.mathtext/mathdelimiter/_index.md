---
title: MathDelimiter class
second_title: Aspose.Slides للـ Python عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides.mathtext/mathdelimiter/
---
## MathDelimiter فئة

يحدد كائن الفاصل، المكوّن من أحرف الفتح والإغلاق (مثل الأقواس، الأقواس المعقوفة، الأقواس المربعة، والشرطة العمودية)، وعنصر أو أكثر رياضي داخلها، مفصولًا بحرف محدد. أمثلة: (𝑥2); [𝑥2|𝑦2]

**الوراثة:**[`MathDelimiter`](/slides/python-net/ar/aspose.slides.mathtext/mathdelimiter) → [`MathElementBase`](/slides/python-net/ar/aspose.slides.mathtext/mathelementbase)

نوع MathDelimiter يعرِض الأعضاء التالية:

## المُنشئات

| المُنشئ | الوصف |
| :- | :- |
| [`__init__(self, element)`](/slides/python-net/ar/aspose.slides.mathtext/mathdelimiter/__init__/#imathelement) | يُهيئ MathDelimiter بالعنصر المحدد كحجة أساسية واحدة |

## الخصائص

| الخاصية | الوصف |
| :- | :- |
| [`arguments`](/slides/python-net/ar/aspose.slides.mathtext/mathdelimiter/arguments/) | عنصر أو أكثر رياضي مفصول بأحرف الفاصل |
| [`beginning_character`](/slides/python-net/ar/aspose.slides.mathtext/mathdelimiter/beginning_character/) | حرف بداية الفاصل يحدد حرف الفاصل الافتتاحي أو البداية.<br/>            الفواصل الرياضية هي أحرف تغليف مثل الأقواس، الأقواس المربعة، والأقواس المعقوفة.<br/>            القيمة الافتراضية: '('. |
| [`separator_character`](/slides/python-net/ar/aspose.slides.mathtext/mathdelimiter/separator_character/) | حرف فاصل الفاصل يحدد الحرف الذي يفصل الحجج في كائن الفاصل.<br/>            القيمة الافتراضية: '\|'. |
| [`ending_character`](/slides/python-net/ar/aspose.slides.mathtext/mathdelimiter/ending_character/) | حرف نهاية الفاصل يحدد حرف الفاصل الختامي أو الإغلاق.<br/>            الفواصل الرياضية هي أحرف تغليف مثل الأقواس، الأقواس المربعة، والأقواس المعقوفة.<br/>            القيمة الافتراضية: ')'. |
| [`grow_to_match_operand_height`](/slides/python-net/ar/aspose.slides.mathtext/mathdelimiter/grow_to_match_operand_height/) | يحدد نمو BeginningCharacter، SeparatorCharacter، EndingCharacter<br/>            عندما تكون true، ينمو الفاصل عموديًا لمطابقة ارتفاع المعامل.<br/>            القيمة الافتراضية هي true |
| [`delimiter_shape`](/slides/python-net/ar/aspose.slides.mathtext/mathdelimiter/delimiter_shape/) | يحدد شكل الفواصل في كائن الفاصل.<br/>            عندما تكون MathDelimiterShape.Centered، تكون الفواصل مركزة حول محور الرياضيات للنص الرياضي<br/>            وتُصنَّع لتلائم ارتفاع محتوياتها بالكامل.<br/>            عندما تكون MathDelimiterShape.Match، يتم تعديل ارتفاعها وشكلها لتطابق المحتوى بالضبط. |

## الطرق

| الطريقة | الوصف |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/ar/aspose.slides.mathtext/mathdelimiter/join/#imathelement) | يجمع عنصرًا رياضيًا ويشكل كتلة رياضية |
| [`join(self, math_text)`](/slides/python-net/ar/aspose.slides.mathtext/mathdelimiter/join/#str) | يجمع نصًا رياضيًا ويشكل كتلة رياضية |
| [`divide(self, denominator)`](/slides/python-net/ar/aspose.slides.mathtext/mathdelimiter/divide/#imathelement) | ينشئ كسرًا بالبسط الحالي والمقام المحدد |
| [`divide(self, denominator)`](/slides/python-net/ar/aspose.slides.mathtext/mathdelimiter/divide/#str) | ينشئ كسرًا بالبسط الحالي والمقام المحدد |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/ar/aspose.slides.mathtext/mathdelimiter/divide/#imathelement-mathfractiontypes) | ينشئ كسرًا من النوع المحدد بالبسط الحالي والمقام المحدد |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/ar/aspose.slides.mathtext/mathdelimiter/divide/#str-mathfractiontypes) | ينشئ كسرًا من النوع المحدد بالبسط الحالي والمقام المحدد |
| [`enclose(self)`](/slides/python-net/ar/aspose.slides.mathtext/mathdelimiter/enclose/#) | يُغلف عنصرًا رياضيًا بأقواس |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/ar/aspose.slides.mathtext/mathdelimiter/enclose/#char-char) | يُغلف عنصرًا رياضيًا بأحرف محددة مثل الأقواس أو أحرف أخرى كإطار |
| [`function(self, function_argument)`](/slides/python-net/ar/aspose.slides.mathtext/mathdelimiter/function/#imathelement) | يأخذ دالة لحجة باستخدام هذه المثيل كاسم الدالة |
| [`function(self, function_argument)`](/slides/python-net/ar/aspose.slides.mathtext/mathdelimiter/function/#str) | يأخذ دالة لحجةusing هذه المثيل كاسم الدالة |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/ar/aspose.slides.mathtext/mathdelimiter/as_argument_of_function/#imathelement) | يأخذ الدالة المحددة باستخدام هذه المثيل كحجة |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/ar/aspose.slides.mathtext/mathdelimiter/as_argument_of_function/#str) | يأخذ الدالة المحددة باستخدام هذه المثيل كحجة |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/ar/aspose.slides.mathtext/mathdelimiter/as_argument_of_function/#mathfunctionsofoneargument) | يأخذ الدالة المحددة باستخدام هذه المثيل كحجة |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/ar/aspose.slides.mathtext/mathdelimiter/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | يأخذ الدالة المحددة باستخدام هذه المثيل كحجة وحجة إضافية محددة |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/ar/aspose.slides.mathtext/mathdelimiter/as_argument_of_function/#mathfunctionsoftwoarguments-str) | يأخذ الدالة المحددة باستخدام هذه المثيل كحجة وحجة إضافية محددة |
| [`set_subscript(self, subscript)`](/slides/python-net/ar/aspose.slides.mathtext/mathdelimiter/set_subscript/#imathelement) | ينشئ مؤشر سفلي |
| [`set_subscript(self, subscript)`](/slides/python-net/ar/aspose.slides.mathtext/mathdelimiter/set_subscript/#str) | ينشئ مؤشر سفلي |
| [`set_superscript(self, superscript)`](/slides/python-net/ar/aspose.slides.mathtext/mathdelimiter/set_superscript/#imathelement) | ينشئ مؤشر علوي |
| [`set_superscript(self, superscript)`](/slides/python-net/ar/aspose.slides.mathtext/mathdelimiter/set_superscript/#str) | ينشئ مؤشر علوي |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/ar/aspose.slides.mathtext/mathdelimiter/set_sub_superscript_on_the_right/#imathelement-imathelement) | ينشئ مؤشر سفلي وعلوي على اليمين |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/ar/aspose.slides.mathtext/mathdelimiter/set_sub_superscript_on_the_right/#str-str) | ينشئ مؤشر سفلي وعلوي على اليمين |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/ar/aspose.slides.mathtext/mathdelimiter/set_sub_superscript_on_the_left/#imathelement-imathelement) | ينشئ مؤشر سفلي وعلوي على اليسار |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/ar/aspose.slides.mathtext/mathdelimiter/set_sub_superscript_on_the_left/#str-str) | ينشئ مؤشر سفلي وعلوي على اليسار |
| [`radical(self, degree)`](/slides/python-net/ar/aspose.slides.mathtext/mathdelimiter/radical/#imathelement) | يحدد الجذر الرياضي للدرجة المعطاة من الحجة المحددة. |
| [`radical(self, degree)`](/slides/python-net/ar/aspose.slides.mathtext/mathdelimiter/radical/#str) | يحدد الجذر الرياضي للدرجة المعطاة من الحجة المحددة. |
| [`set_upper_limit(self, limit)`](/slides/python-net/ar/aspose.slides.mathtext/mathdelimiter/set_upper_limit/#imathelement) | يأخذ الحد الأعلى |
| [`set_upper_limit(self, limit)`](/slides/python-net/ar/aspose.slides.mathtext/mathdelimiter/set_upper_limit/#str) | يأخذ الحد الأعلى |
| [`set_lower_limit(self, limit)`](/slides/python-net/ar/aspose.slides.mathtext/mathdelimiter/set_lower_limit/#imathelement) | يأخذ الحد الأدنى |
| [`set_lower_limit(self, limit)`](/slides/python-net/ar/aspose.slides.mathtext/mathdelimiter/set_lower_limit/#str) | يأخذ الحد الأدنى |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/ar/aspose.slides.mathtext/mathdelimiter/nary/#mathnaryoperatortypes-imathelement-imathelement) | ينشئ معاملًا N-ارّيًا |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/ar/aspose.slides.mathtext/mathdelimiter/nary/#mathnaryoperatortypes-str-str) | ينشئ معاملًا N-ارّيًا |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/ar/aspose.slides.mathtext/mathdelimiter/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | يأخذ التكامل |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/ar/aspose.slides.mathtext/mathdelimiter/integral/#mathintegraltypes-imathelement-imathelement) | يأخذ التكامل |
| [`integral(self, integral_type)`](/slides/python-net/ar/aspose.slides.mathtext/mathdelimiter/integral/#mathintegraltypes) | يأخذ التكامل دون حدود |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/ar/aspose.slides.mathtext/mathdelimiter/integral/#mathintegraltypes-str-str-mathlimitlocations) | يأخذ التكامل دون حدود |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/ar/aspose.slides.mathtext/mathdelimiter/integral/#mathintegraltypes-str-str) | يأخذ التكامل دون حدود |
| [`group(self)`](/slides/python-net/ar/aspose.slides.mathtext/mathdelimiter/group/#) | يضع هذا العنصر في مجموعة باستخدام قوس معقوف سفلي |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/ar/aspose.slides.mathtext/mathdelimiter/group/#char-mathtopbotpositions-mathtopbotpositions) | يضع هذا العنصر في مجموعة باستخدام حرف تجميع مثل القوس المعقوف السفلي أو غيره |
| [`to_border_box(self)`](/slides/python-net/ar/aspose.slides.mathtext/mathdelimiter/to_border_box/#) | يضع هذا العنصر في صندوق حدودي |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/ar/aspose.slides.mathtext/mathdelimiter/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | يضع هذا العنصر في صندوق حدودي |
| [`to_math_array(self)`](/slides/python-net/ar/aspose.slides.mathtext/mathdelimiter/to_math_array/#) | يضعه في مصفوفة عمودية |
| [`accent(self, accent_character)`](/slides/python-net/ar/aspose.slides.mathtext/mathdelimiter/accent/#char) | يضبط علامة لهجة (حرف فوق هذا العنصر) |
| [`overbar(self)`](/slides/python-net/ar/aspose.slides.mathtext/mathdelimiter/overbar/#) | يضع خطًا فوق هذا العنصر |
| [`underbar(self)`](/slides/python-net/ar/aspose.slides.mathtext/mathdelimiter/underbar/#) | يضع خطًا أسفل هذا العنصر |
| [`to_box(self)`](/slides/python-net/ar/aspose.slides.mathtext/mathdelimiter/to_box/#) | يضع هذا العنصر في صندوق غير مرئي (تجميع منطقي) <br/>            يُستخدم لتجميع مكونات معادلة أو مثال آخر من النص الرياضي.<br/>            يمكن لكائن مُحاط (على سبيل المثال) أن يعمل كمحاكي لمعامل مع أو بدون نقطة محاذاة، <br/>            أو أن يكون نقطة فاصل سطر، أو يُجمع بحيث لا يسمح بفواصل سطر داخلية. |
| [`delimit(self, separator_character)`](/slides/python-net/ar/aspose.slides.mathtext/mathdelimiter/delimit/#char) | يفصل الحجج باستخدام حرف الفاصل المحدد |
| [`get_children(self)`](/slides/python-net/ar/aspose.slides.mathtext/mathdelimiter/get_children/#) | يحصل على عناصر الأطفال |

### أنظر أيضاً
* فئة [`MathDelimiter`](/slides/python-net/ar/aspose.slides.mathtext/mathdelimiter)
* فئة [`MathElementBase`](/slides/python-net/ar/aspose.slides.mathtext/mathelementbase)
* وحدة [`aspose.slides.mathtext`](/slides/python-net/ar/aspose.slides.mathtext)
* مكتبة [`Aspose.Slides`](/slides/python-net)