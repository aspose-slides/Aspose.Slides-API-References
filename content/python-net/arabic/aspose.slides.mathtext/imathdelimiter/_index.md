---
title: IMathDelimiter class
second_title: Aspose.Slides للـ Python عبر مرجع API لـ .NET
description:
type: docs
url: /ar/aspose.slides.mathtext/imathdelimiter/
---
## IMathDelimiter فئة

يحدد كائن الفاصل، المكوّن من أحرف الفتح والإغلاق (مثل الأقواس، الأقواس المعقوفة، الأقواس المربعة، والشرائط العمودية)، وعنصر أو أكثر رياضي داخلها، مفصولين بحرف محدد. أمثلة: (𝑥2)؛ [𝑥2|𝑦2]

نوع IMMathDelimiter يُظهر الأعضاء التالية:

## خصائص

| الخاصية | الوصف |
| :- | :- |
| [`arguments`](/slides/python-net/ar/aspose.slides.mathtext/imathdelimiter/arguments/) | عنصر أو أكثر رياضي مفصول بأحرف الفاصل |
| [`beginning_character`](/slides/python-net/ar/aspose.slides.mathtext/imathdelimiter/beginning_character/) | Delimiter Beginning Character يحدد حرف بداية الفاصل، أو حرف الفتح. <br/>            الفواصل الرياضية هي أحرف محيطة مثل الأقواس، الأقواس المربعة، والأقواس المعقوفة.<br/>            القيمة الافتراضية: '('. |
| [`separator_character`](/slides/python-net/ar/aspose.slides.mathtext/imathdelimiter/separator_character/) | Delimiter Separator Character يحدد الحرف الذي يفصل المعاملات في كائن الفاصل. <br/>            القيمة الافتراضية: '\|'. |
| [`ending_character`](/slides/python-net/ar/aspose.slides.mathtext/imathdelimiter/ending_character/) | Delimiter Ending Character يحدد حرف نهاية الفاصل، أو حرف الإغلاق. <br/>            الفواصل الرياضية هي أحرف محيطة مثل الأقواس، الأقواس المربعة، والأقواس المعقوفة.<br/>            القيمة الافتراضية: ')'. |
| [`grow_to_match_operand_height`](/slides/python-net/ar/aspose.slides.mathtext/imathdelimiter/grow_to_match_operand_height/) | يحدد نمو BeginningCharacter، SeparatorCharacter، EndingCharacter<br/>            عندما تكون true، ينمو الفاصل عمودياً ليتطابق مع ارتفاع العامل.<br/>            القيمة الافتراضية هي true |
| [`delimiter_shape`](/slides/python-net/ar/aspose.slides.mathtext/imathdelimiter/delimiter_shape/) | يحدد شكل الفواصل في كائن الفاصل. <br/>            عندما تكون MathDelimiterShape.Centered، تكون الفواصل متمركزة حول محور الرياضيات للنص الرياضي <br/>            وتُضبط لتناسب كامل ارتفاع محتواها.<br/>            عندما تكون MathDelimiterShape.Match، يتغير ارتفاعها وشكلها لتطابق تماماً محتواها. |

## الطرق

| الطريقة | الوصف |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/ar/aspose.slides.mathtext/imathdelimiter/join/#imathelement) |  |
| [`join(self, math_text)`](/slides/python-net/ar/aspose.slides.mathtext/imathdelimiter/join/#str) |  |
| [`divide(self, denominator)`](/slides/python-net/ar/aspose.slides.mathtext/imathdelimiter/divide/#imathelement) |  |
| [`divide(self, denominator)`](/slides/python-net/ar/aspose.slides.mathtext/imathdelimiter/divide/#str) |  |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/ar/aspose.slides.mathtext/imathdelimiter/divide/#imathelement-mathfractiontypes) |  |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/ar/aspose.slides.mathtext/imathdelimiter/divide/#str-mathfractiontypes) |  |
| [`enclose(self)`](/slides/python-net/ar/aspose.slides.mathtext/imathdelimiter/enclose/#) |  |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/ar/aspose.slides.mathtext/imathdelimiter/enclose/#char-char) |  |
| [`function(self, function_argument)`](/slides/python-net/ar/aspose.slides.mathtext/imathdelimiter/function/#imathelement) |  |
| [`function(self, function_argument)`](/slides/python-net/ar/aspose.slides.mathtext/imathdelimiter/function/#str) |  |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/ar/aspose.slides.mathtext/imathdelimiter/as_argument_of_function/#imathelement) |  |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/ar/aspose.slides.mathtext/imathdelimiter/as_argument_of_function/#str) |  |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/ar/aspose.slides.mathtext/imathdelimiter/as_argument_of_function/#mathfunctionsofoneargument) |  |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/ar/aspose.slides.mathtext/imathdelimiter/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) |  |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/ar/aspose.slides.mathtext/imathdelimiter/as_argument_of_function/#mathfunctionsoftwoarguments-str) |  |
| [`set_subscript(self, subscript)`](/slides/python-net/ar/aspose.slides.mathtext/imathdelimiter/set_subscript/#imathelement) |  |
| [`set_subscript(self, subscript)`](/slides/python-net/ar/aspose.slides.mathtext/imathdelimiter/set_subscript/#str) |  |
| [`set_superscript(self, superscript)`](/slides/python-net/ar/aspose.slides.mathtext/imathdelimiter/set_superscript/#imathelement) |  |
| [`set_superscript(self, superscript)`](/slides/python-net/ar/aspose.slides.mathtext/imathdelimiter/set_superscript/#str) |  |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/ar/aspose.slides.mathtext/imathdelimiter/set_sub_superscript_on_the_right/#imathelement-imathelement) |  |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/ar/aspose.slides.mathtext/imathdelimiter/set_sub_superscript_on_the_right/#str-str) |  |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/ar/aspose.slides.mathtext/imathdelimiter/set_sub_superscript_on_the_left/#imathelement-imathelement) |  |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/ar/aspose.slides.mathtext/imathdelimiter/set_sub_superscript_on_the_left/#str-str) |  |
| [`radical(self, degree)`](/slides/python-net/ar/aspose.slides.mathtext/imathdelimiter/radical/#imathelement) |  |
| [`radical(self, degree)`](/slides/python-net/ar/aspose.slides.mathtext/imathdelimiter/radical/#str) |  |
| [`set_upper_limit(self, limit)`](/slides/python-net/ar/aspose.slides.mathtext/imathdelimiter/set_upper_limit/#imathelement) |  |
| [`set_upper_limit(self, limit)`](/slides/python-net/ar/aspose.slides.mathtext/imathdelimiter/set_upper_limit/#str) |  |
| [`set_lower_limit(self, limit)`](/slides/python-net/ar/aspose.slides.mathtext/imathdelimiter/set_lower_limit/#imathelement) |  |
| [`set_lower_limit(self, limit)`](/slides/python-net/ar/aspose.slides.mathtext/imathdelimiter/set_lower_limit/#str) |  |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/ar/aspose.slides.mathtext/imathdelimiter/nary/#mathnaryoperatortypes-imathelement-imathelement) |  |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/ar/aspose.slides.mathtext/imathdelimiter/nary/#mathnaryoperatortypes-str-str) |  |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/ar/aspose.slides.mathtext/imathdelimiter/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) |  |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/ar/aspose.slides.mathtext/imathdelimiter/integral/#mathintegraltypes-imathelement-imathelement) |  |
| [`integral(self, integral_type)`](/slides/python-net/ar/aspose.slides.mathtext/imathdelimiter/integral/#mathintegraltypes) |  |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/ar/aspose.slides.mathtext/imathdelimiter/integral/#mathintegraltypes-str-str-mathlimitlocations) |  |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/ar/aspose.slides.mathtext/imathdelimiter/integral/#mathintegraltypes-str-str) |  |
| [`group(self)`](/slides/python-net/ar/aspose.slides.mathtext/imathdelimiter/group/#) |  |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/ar/aspose.slides.mathtext/imathdelimiter/group/#char-mathtopbotpositions-mathtopbotpositions) |  |
| [`to_border_box(self)`](/slides/python-net/ar/aspose.slides.mathtext/imathdelimiter/to_border_box/#) |  |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/ar/aspose.slides.mathtext/imathdelimiter/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) |  |
| [`delimit(self, separator_character)`](/slides/python-net/ar/aspose.slides.mathtext/imathdelimiter/delimit/#char) | يفصل المعاملات باستخدام حرف الفاصل المحدد |
| [`get_children(self)`](/slides/python-net/ar/aspose.slides.mathtext/imathdelimiter/get_children/#) |  |
| [`to_math_array(self)`](/slides/python-net/ar/aspose.slides.mathtext/imathdelimiter/to_math_array/#) |  |
| [`accent(self, accent_character)`](/slides/python-net/ar/aspose.slides.mathtext/imathdelimiter/accent/#char) |  |
| [`overbar(self)`](/slides/python-net/ar/aspose.slides.mathtext/imathdelimiter/overbar/#) |  |
| [`underbar(self)`](/slides/python-net/ar/aspose.slides.mathtext/imathdelimiter/underbar/#) |  |
| [`to_box(self)`](/slides/python-net/ar/aspose.slides.mathtext/imathdelimiter/to_box/#) |  |

### انظر أيضًا
* الوحدة [`aspose.slides.mathtext`](/slides/python-net/ar/aspose.slides.mathtext)
* المكتبة [`Aspose.Slides`](/slides/python-net)