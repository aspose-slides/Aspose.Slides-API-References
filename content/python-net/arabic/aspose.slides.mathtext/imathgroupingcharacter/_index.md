---
title: IMathGroupingCharacter class
second_title: Aspose.Slides لبايثون عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides.mathtext/imathgroupingcharacter/
---
## IMathGroupingCharacter الفئة

يحدد رمز التجميع فوق أو تحت تعبير، عادةً لتسليط الضوء على العلاقة بين العناصر

The IMathGroupingCharacter type exposes the following members:

## الخصائص

| الخاصية | الوصف |
| :- | :- |
| [`base`](/slides/python-net/ar/aspose.slides.mathtext/imathgroupingcharacter/base/) | الوسيط الأساسي |
| [`character`](/slides/python-net/ar/aspose.slides.mathtext/imathgroupingcharacter/character/) | حرف التجميع<br/>            القيمة الافتراضية: U+23DF (القوس المعقوف السفلي) |
| [`position`](/slides/python-net/ar/aspose.slides.mathtext/imathgroupingcharacter/position/) | موضع حرف التجميع.<br/>            الافتراضي: أسفل |
| [`vertical_justification`](/slides/python-net/ar/aspose.slides.mathtext/imathgroupingcharacter/vertical_justification/) | محاذاة عمودية لحرف التجميع.<br/>            يحدد موضع الكائن بالنسبة للخط الأساسي.<br/>            على سبيل المثال، عندما يكون حرف التجميع فوق الكائن، <br/>            يعني ضبط VerticalJustification إلى Top أن أعلى الكائن يقع على الخط الأساسي؛<br/>            عندما يتم ضبط VerticalJustification إلى Bottom، يكون أسفل الكائن على الخط الأساسي<br/>            الافتراضي: Bottom عندما Position=Top، وTop عندما Position=Bottom |

## الطرق

| الطريقة | الوصف |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/ar/aspose.slides.mathtext/imathgroupingcharacter/join/#imathelement) |  |
| [`join(self, math_text)`](/slides/python-net/ar/aspose.slides.mathtext/imathgroupingcharacter/join/#str) |  |
| [`divide(self, denominator)`](/slides/python-net/ar/aspose.slides.mathtext/imathgroupingcharacter/divide/#imathelement) |  |
| [`divide(self, denominator)`](/slides/python-net/ar/aspose.slides.mathtext/imathgroupingcharacter/divide/#str) |  |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/ar/aspose.slides.mathtext/imathgroupingcharacter/divide/#imathelement-mathfractiontypes) |  |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/ar/aspose.slides.mathtext/imathgroupingcharacter/divide/#str-mathfractiontypes) |  |
| [`enclose(self)`](/slides/python-net/ar/aspose.slides.mathtext/imathgroupingcharacter/enclose/#) |  |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/ar/aspose.slides.mathtext/imathgroupingcharacter/enclose/#char-char) |  |
| [`function(self, function_argument)`](/slides/python-net/ar/aspose.slides.mathtext/imathgroupingcharacter/function/#imathelement) |  |
| [`function(self, function_argument)`](/slides/python-net/ar/aspose.slides.mathtext/imathgroupingcharacter/function/#str) |  |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/ar/aspose.slides.mathtext/imathgroupingcharacter/as_argument_of_function/#imathelement) |  |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/ar/aspose.slides.mathtext/imathgroupingcharacter/as_argument_of_function/#str) |  |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/ar/aspose.slides.mathtext/imathgroupingcharacter/as_argument_of_function/#mathfunctionsofoneargument) |  |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/ar/aspose.slides.mathtext/imathgroupingcharacter/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) |  |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/ar/aspose.slides.mathtext/imathgroupingcharacter/as_argument_of_function/#mathfunctionsoftwoarguments-str) |  |
| [`set_subscript(self, subscript)`](/slides/python-net/ar/aspose.slides.mathtext/imathgroupingcharacter/set_subscript/#imathelement) |  |
| [`set_subscript(self, subscript)`](/slides/python-net/ar/aspose.slides.mathtext/imathgroupingcharacter/set_subscript/#str) |  |
| [`set_superscript(self, superscript)`](/slides/python-net/ar/aspose.slides.mathtext/imathgroupingcharacter/set_superscript/#imathelement) |  |
| [`set_superscript(self, superscript)`](/slides/python-net/ar/aspose.slides.mathtext/imathgroupingcharacter/set_superscript/#str) |  |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/ar/aspose.slides.mathtext/imathgroupingcharacter/set_sub_superscript_on_the_right/#imathelement-imathelement) |  |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/ar/aspose.slides.mathtext/imathgroupingcharacter/set_sub_superscript_on_the_right/#str-str) |  |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/ar/aspose.slides.mathtext/imathgroupingcharacter/set_sub_superscript_on_the_left/#imathelement-imathelement) |  |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/ar/aspose.slides.mathtext/imathgroupingcharacter/set_sub_superscript_on_the_left/#str-str) |  |
| [`radical(self, degree)`](/slides/python-net/ar/aspose.slides.mathtext/imathgroupingcharacter/radical/#imathelement) |  |
| [`radical(self, degree)`](/slides/python-net/ar/aspose.slides.mathtext/imathgroupingcharacter/radical/#str) |  |
| [`set_upper_limit(self, limit)`](/slides/python-net/ar/aspose.slides.mathtext/imathgroupingcharacter/set_upper_limit/#imathelement) |  |
| [`set_upper_limit(self, limit)`](/slides/python-net/ar/aspose.slides.mathtext/imathgroupingcharacter/set_upper_limit/#str) |  |
| [`set_lower_limit(self, limit)`](/slides/python-net/ar/aspose.slides.mathtext/imathgroupingcharacter/set_lower_limit/#imathelement) |  |
| [`set_lower_limit(self, limit)`](/slides/python-net/ar/aspose.slides.mathtext/imathgroupingcharacter/set_lower_limit/#str) |  |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/ar/aspose.slides.mathtext/imathgroupingcharacter/nary/#mathnaryoperatortypes-imathelement-imathelement) |  |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/ar/aspose.slides.mathtext/imathgroupingcharacter/nary/#mathnaryoperatortypes-str-str) |  |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/ar/aspose.slides.mathtext/imathgroupingcharacter/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) |  |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/ar/aspose.slides.mathtext/imathgroupingcharacter/integral/#mathintegraltypes-imathelement-imathelement) |  |
| [`integral(self, integral_type)`](/slides/python-net/ar/aspose.slides.mathtext/imathgroupingcharacter/integral/#mathintegraltypes) |  |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/ar/aspose.slides.mathtext/imathgroupingcharacter/integral/#mathintegraltypes-str-str-mathlimitlocations) |  |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/ar/aspose.slides.mathtext/imathgroupingcharacter/integral/#mathintegraltypes-str-str) |  |
| [`group(self)`](/slides/python-net/ar/aspose.slides.mathtext/imathgroupingcharacter/group/#) |  |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/ar/aspose.slides.mathtext/imathgroupingcharacter/group/#char-mathtopbotpositions-mathtopbotpositions) |  |
| [`to_border_box(self)`](/slides/python-net/ar/aspose.slides.mathtext/imathgroupingcharacter/to_border_box/#) |  |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/ar/aspose.slides.mathtext/imathgroupingcharacter/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) |  |
| [`get_children(self)`](/slides/python-net/ar/aspose.slides.mathtext/imathgroupingcharacter/get_children/#) |  |
| [`to_math_array(self)`](/slides/python-net/ar/aspose.slides.mathtext/imathgroupingcharacter/to_math_array/#) |  |
| [`accent(self, accent_character)`](/slides/python-net/ar/aspose.slides.mathtext/imathgroupingcharacter/accent/#char) |  |
| [`overbar(self)`](/slides/python-net/ar/aspose.slides.mathtext/imathgroupingcharacter/overbar/#) |  |
| [`underbar(self)`](/slides/python-net/ar/aspose.slides.mathtext/imathgroupingcharacter/underbar/#) |  |
| [`to_box(self)`](/slides/python-net/ar/aspose.slides.mathtext/imathgroupingcharacter/to_box/#) |  |

### انظر أيضًا
* الوحدة [`aspose.slides.mathtext`](/slides/python-net/ar/aspose.slides.mathtext)
* المكتبة [`Aspose.Slides`](/slides/python-net)