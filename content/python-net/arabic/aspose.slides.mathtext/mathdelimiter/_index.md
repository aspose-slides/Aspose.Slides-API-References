---
title: MathDelimiter class
second_title: Aspose.Slides لـ Python عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides.mathtext/mathdelimiter/
---
## MathDelimiter فئة

يحدد كائن الفاصل، المكوّن من أحرف الفتح والإغلاق (مثل الأقواس، الأقواس المعقوفة، الأقواس المربعة، والشرطة العمودية)، وعنصر أو أكثر رياضي داخلها، مفصولًا بحرف محدد. أمثلة: (𝑥2); [𝑥2|𝑦2]

**الوراثة:**[`MathDelimiter`](/slides/python-net/ar/aspose.slides.mathtext/mathdelimiter) → [`MathElementBase`](/slides/python-net/ar/aspose.slides.mathtext/mathelementbase)

يعرض نوع MathDelimiter الأعضاء التالية:

## المنشئات

| المنشئ | الوصف |
| :- | :- |
| [`__init__(self, element)`](/slides/python-net/ar/aspose.slides.mathtext/mathdelimiter/__init__/#imathelement) | ينشئ MathDelimiter بالعنصر المحدد كحجة قاعدة واحدة |

## الخصائص

| الخاصية | الوصف |
| :- | :- |
| [`arguments`](/slides/python-net/ar/aspose.slides.mathtext/mathdelimiter/arguments/) | عنصر أو أكثر رياضي مفصول بأحرف الفاصل |
| [`beginning_character`](/slides/python-net/ar/aspose.slides.mathtext/mathdelimiter/beginning_character/) | حرف بداية الفاصل يحدد حرف البداية أو الفتح للفاصل. <br/>            الفواصل الرياضية هي أحرف تغليف مثل الأقواس، الأقواس المربعة، والأقواس المعقوفة.<br/>            القيمة الافتراضية: '('. |
| [`separator_character`](/slides/python-net/ar/aspose.slides.mathtext/mathdelimiter/separator_character/) | حرف فاصل الفاصل يحدد الحرف الذي يفصل الحجج في كائن الفاصل. <br/>            القيمة الافتراضية: '\|'. |
| [`ending_character`](/slides/python-net/ar/aspose.slides.mathtext/mathdelimiter/ending_character/) | حرف نهاية الفاصل يحدد حرف النهاية أو الإغلاق للفاصل. <br/>            الفواصل الرياضية هي أحرف تغليف مثل الأقواس، الأقواس المربعة، والأقواس المعقوفة.<br/>            القيمة الافتراضية: ')'. |
| [`grow_to_match_operand_height`](/slides/python-net/ar/aspose.slides.mathtext/mathdelimiter/grow_to_match_operand_height/) | يحدد نمو BeginningCharacter و SeparatorCharacter و EndingCharacter<br/>            عندما تكون true، ينمو الفاصل عموديًا لمطابقة ارتفاع المعامل.<br/>            القيمة الافتراضية هي true |
| [`delimiter_shape`](/slides/python-net/ar/aspose.slides.mathtext/mathdelimiter/delimiter_shape/) | يحدد شكل الفواصل في كائن الفاصل. <br/>            عندما تكون MathDelimiterShape.Centered، تكون الفواصل متمركة حول محور الرياضيات للنص الرياضي <br/>            وتُضبط لتناسب الارتفاع الكامل لمحتوياتها.<br/>            عندما تكون MathDelimiterShape.Match، يتغير ارتفاعها وشكلها لتطابق محتوياتها تمامًا. |

## الطرق

| الطريقة | الوصف |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/ar/aspose.slides.mathtext/mathdelimiter/join/#imathelement) | يجمع عنصرًا رياضيًا ويشكل كتلة رياضية |
| [`join(self, math_text)`](/slides/python-net/ar/aspose.slides.mathtext/mathdelimiter/join/#str) | يجمع نصًا رياضيًا ويشكل كتلة رياضية |
| [`divide(self, denominator)`](/slides/python-net/ar/aspose.slides.mathtext/mathdelimiter/divide/#imathelement) | ينشئ كسرًا بهذا البسط والمقام المحدد |
| [`divide(self, denominator)`](/slides/python-net/ar/aspose.slides.mathtext/mathdelimiter/divide/#str) | ينشئ كسرًا بهذا البسط والمقام المحدد |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/ar/aspose.slides.mathtext/mathdelimiter/divide/#imathelement-mathfractiontypes) | ينشئ كسرًا من النوع المحدد بهذا البسط والمقام المحدد |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/ar/aspose.slides.mathtext/mathdelimiter/divide/#str-mathfractiontypes) | ينشئ كسرًا من النوع المحدد بهذا البسط والمقام المحدد |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/ar/aspose.slides.mathtext/mathdelimiter/enclose/#char-char) | يحيط عنصر رياضي بأحرف محددة مثل الأقواس أو أحرف أخرى كإطار |
| [`enclose(self)`](/slides/python-net/ar/aspose.slides.mathtext/mathdelimiter/enclose/#) | يحيط عنصر رياضي بأقواس |
| [`function(self, function_argument)`](/slides/python-net/ar/aspose.slides.mathtext/mathdelimiter/function/#imathelement) | يأخذ دالة لوسيط باستخدام هذه المثيلة كاسم الدالة |
| [`function(self, function_argument)`](/slides/python-net/ar/aspose.slides.mathtext/mathdelimiter/function/#str) | يأخذ دالة لوسيط باستخدام هذه المثيلة كاسم الدالة |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/ar/aspose.slides.mathtext/mathdelimiter/as_argument_of_function/#imathelement) | يأخذ الدالة المحددة باستخدام هذه المثيلة كوسيط |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/ar/aspose.slides.mathtext/mathdelimiter/as_argument_of_function/#str) | يأخذ الدالة المحددة باستخدام هذه المثيلة كوسيط |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/ar/aspose.slides.mathtext/mathdelimiter/as_argument_of_function/#mathfunctionsofoneargument) | يأخذ الدالة المحددة باستخدام هذه المثيلة كوسيط |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/ar/aspose.slides.mathtext/mathdelimiter/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | يأخذ الدالة المحددة باستخدام هذه المثيلة كوسيط ومع وسيط إضافي محدد |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/ar/aspose.slides.mathtext/mathdelimiter/as_argument_of_function/#mathfunctionsoftwoarguments-str) | يأخذ الدالة المحددة باستخدام هذه المثيلة كوسيط ومع وسيط إضافي محدد |
| [`set_subscript(self, subscript)`](/slides/python-net/ar/aspose.slides.mathtext/mathdelimiter/set_subscript/#imathelement) | ينشئ مؤشرًا سفليًا |
| [`set_subscript(self, subscript)`](/slides/python-net/ar/aspose.slides.mathtext/mathdelimiter/set_subscript/#str) | ينشئ مؤشرًا سفليًا |
| [`set_superscript(self, superscript)`](/slides/python-net/ar/aspose.slides.mathtext/mathdelimiter/set_superscript/#imathelement) | ينشئ مؤشرًا عُلويًا |
| [`set_superscript(self, superscript)`](/slides/python-net/ar/aspose.slides.mathtext/mathdelimiter/set_superscript/#str) | ينشئ مؤشرًا عُلويًا |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/ar/aspose.slides.mathtext/mathdelimiter/set_sub_superscript_on_the_right/#imathelement-imathelement) | ينشئ مؤشرين سفلي وعُلوي على اليمين |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/ar/aspose.slides.mathtext/mathdelimiter/set_sub_superscript_on_the_right/#str-str) | ينشئ مؤشرين سفلي وعُلوي على اليمين |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/ar/aspose.slides.mathtext/mathdelimiter/set_sub_superscript_on_the_left/#imathelement-imathelement) | ينشئ مؤشرين سفلي وعُلوي على اليسار |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/ar/aspose.slides.mathtext/mathdelimiter/set_sub_superscript_on_the_left/#str-str) | ينشئ مؤشرين سفلي وعُلوي على اليسار |
| [`radical(self, degree)`](/slides/python-net/ar/aspose.slides.mathtext/mathdelimiter/radical/#imathelement) | يحدد الجذر الرياضي بالدرجة المعطاة من الوسيط المحدد. |
| [`radical(self, degree)`](/slides/python-net/ar/aspose.slides.mathtext/mathdelimiter/radical/#str) | يحدد الجذر الرياضي بالدرجة المعطاة من الوسيط المحدد. |
| [`set_upper_limit(self, limit)`](/slides/python-net/ar/aspose.slides.mathtext/mathdelimiter/set_upper_limit/#imathelement) | يأخذ الحد العلوي |
| [`set_upper_limit(self, limit)`](/slides/python-net/ar/aspose.slides.mathtext/mathdelimiter/set_upper_limit/#str) | يأخذ الحد العلوي |
| [`set_lower_limit(self, limit)`](/slides/python-net/ar/aspose.slides.mathtext/mathdelimiter/set_lower_limit/#imathelement) | يأخذ الحد السفلي |
| [`set_lower_limit(self, limit)`](/slides/python-net/ar/aspose.slides.mathtext/mathdelimiter/set_lower_limit/#str) | يأخذ الحد السفلي |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/ar/aspose.slides.mathtext/mathdelimiter/nary/#mathnaryoperatortypes-imathelement-imathelement) | ينشئ مشغلاً N-اري |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/ar/aspose.slides.mathtext/mathdelimiter/nary/#mathnaryoperatortypes-str-str) | ينشئ مشغلاً N-اري |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/ar/aspose.slides.mathtext/mathdelimiter/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | يأخذ التكامل |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/ar/aspose.slides.mathtext/mathdelimiter/integral/#mathintegraltypes-imathelement-imathelement) | يأخذ التكامل |
| [`integral(self, integral_type)`](/slides/python-net/ar/aspose.slides.mathtext/mathdelimiter/integral/#mathintegraltypes) | يأخذ التكامل بدون حدود |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/ar/aspose.slides.mathtext/mathdelimiter/integral/#mathintegraltypes-str-str-mathlimitlocations) | يأخذ التكامل |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/ar/aspose.slides.mathtext/mathdelimiter/integral/#mathintegraltypes-str-str) | يأخذ التكامل |
| [`group(self)`](/slides/python-net/ar/aspose.slides.mathtext/mathdelimiter/group/#) | يضع هذا العنصر في مجموعة باستخدام قوس معقوف سفلي |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/ar/aspose.slides.mathtext/mathdelimiter/group/#char-mathtopbotpositions-mathtopbotpositions) | يضع هذا العنصر في مجموعة باستخدام حرف تجميع مثل القوس المعقوف السفلي أو غيره |
| [`to_border_box(self)`](/slides/python-net/ar/aspose.slides.mathtext/mathdelimiter/to_border_box/#) | يضع هذا العنصر في صندوق حدودي |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/ar/aspose.slides.mathtext/mathdelimiter/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | يضع هذا العنصر في صندوق حدودي |
| [`to_math_array(self)`](/slides/python-net/ar/aspose.slides.mathtext/mathdelimiter/to_math_array/#) | يضع في مصفوفة رأسية |
| [`accent(self, accent_character)`](/slides/python-net/ar/aspose.slides.mathtext/mathdelimiter/accent/#char) | يضبط علامة إشارة (حرف فوق هذا العنصر) |
| [`overbar(self)`](/slides/python-net/ar/aspose.slides.mathtext/mathdelimiter/overbar/#) | يضبط شريطًا فوق هذا العنصر |
| [`underbar(self)`](/slides/python-net/ar/aspose.slides.mathtext/mathdelimiter/underbar/#) | يضبط شريطًا أسفل هذا العنصر |
| [`to_box(self)`](/slides/python-net/ar/aspose.slides.mathtext/mathdelimiter/to_box/#) | يوضع هذا العنصر في صندوق غير مرئي (تجميع منطقي) <br/>            يُستخدم لتجميع مكونات معادلة أو نص رياضي آخر.<br/>            يمكن لكائن محاط بالصندوق (على سبيل المثال) أن يعمل كمحاكي للعمليات مع أو بدون نقطة محاذاة، <br/>            أو يعمل كنقطة كسر سطر، أو يُجمع بحيث لا يُسمح بفواصل سطر داخله. |
| [`delimit(self, separator_character)`](/slides/python-net/ar/aspose.slides.mathtext/mathdelimiter/delimit/#char) | يفصل الحجج باستخدام حرف الفاصل المحدد |
| [`get_children(self)`](/slides/python-net/ar/aspose.slides.mathtext/mathdelimiter/get_children/#) | يحصل على عناصر الأطفال |

### انظر أيضًا
* فئة [`MathDelimiter`](/slides/python-net/ar/aspose.slides.mathtext/mathdelimiter)
* فئة [`MathElementBase`](/slides/python-net/ar/aspose.slides.mathtext/mathelementbase)
* وحدة [`aspose.slides.mathtext`](/slides/python-net/ar/aspose.slides.mathtext)
* مكتبة [`Aspose.Slides`](/slides/python-net)