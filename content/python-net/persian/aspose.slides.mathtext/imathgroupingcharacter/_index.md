---
title: IMathGroupingCharacter class
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides.mathtext/imathgroupingcharacter/
---
## IMathGroupingCharacter کلاس

یک نماد گروه‌بندی را بالای یا زیر یک عبارت مشخص می‌کند که معمولاً برای برجسته کردن رابطه بین عناصر استفاده می‌شود

نوع IMathGroupingCharacter اعضای زیر را ارائه می‌دهد:

## ویژگی‌ها

| ویژگی | توضیح |
| :- | :- |
| [`base`](/slides/python-net/fa/aspose.slides.mathtext/imathgroupingcharacter/base/) | آرگومان پایه |
| [`character`](/slides/python-net/fa/aspose.slides.mathtext/imathgroupingcharacter/character/) | کاراکتر گروه‌بندی<br/>            مقدار پیش‌فرض: U+23DF (پرانتز منحنی پایینی) |
| [`position`](/slides/python-net/fa/aspose.slides.mathtext/imathgroupingcharacter/position/) | موقعیت کاراکتر گروه‌بندی.<br/>            مقدار پیش‌فرض: Bottom |
| [`vertical_justification`](/slides/python-net/fa/aspose.slides.mathtext/imathgroupingcharacter/vertical_justification/) | تراز عمودی کاراکتر گروه.<br/>            موقعیت شی را نسبت به baseline تعیین می‌کند.<br/>            به عنوان مثال، وقتی کاراکتر گروه بالای شی باشد، <br/>            VerticalJustification مقدار Top نشان می‌دهد که بالای شی روی baseline قرار می‌گیرد؛<br/>            وقتی VerticalJustification بر روی Bottom تنظیم شود، پایین شی روی baseline قرار می‌گیرد<br/>            مقدار پیش‌فرض: Bottom برای Position=Top، و Top برای Position=Bottom |

## متدها

| متد | توضیح |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/fa/aspose.slides.mathtext/imathgroupingcharacter/join/#imathelement) |  |
| [`join(self, math_text)`](/slides/python-net/fa/aspose.slides.mathtext/imathgroupingcharacter/join/#str) |  |
| [`divide(self, denominator)`](/slides/python-net/fa/aspose.slides.mathtext/imathgroupingcharacter/divide/#imathelement) |  |
| [`divide(self, denominator)`](/slides/python-net/fa/aspose.slides.mathtext/imathgroupingcharacter/divide/#str) |  |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/fa/aspose.slides.mathtext/imathgroupingcharacter/divide/#imathelement-mathfractiontypes) |  |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/fa/aspose.slides.mathtext/imathgroupingcharacter/divide/#str-mathfractiontypes) |  |
| [`enclose(self)`](/slides/python-net/fa/aspose.slides.mathtext/imathgroupingcharacter/enclose/#) |  |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/fa/aspose.slides.mathtext/imathgroupingcharacter/enclose/#char-char) |  |
| [`function(self, function_argument)`](/slides/python-net/fa/aspose.slides.mathtext/imathgroupingcharacter/function/#imathelement) |  |
| [`function(self, function_argument)`](/slides/python-net/fa/aspose.slides.mathtext/imathgroupingcharacter/function/#str) |  |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/fa/aspose.slides.mathtext/imathgroupingcharacter/as_argument_of_function/#imathelement) |  |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/fa/aspose.slides.mathtext/imathgroupingcharacter/as_argument_of_function/#str) |  |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/fa/aspose.slides.mathtext/imathgroupingcharacter/as_argument_of_function/#mathfunctionsofoneargument) |  |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/fa/aspose.slides.mathtext/imathgroupingcharacter/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) |  |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/fa/aspose.slides.mathtext/imathgroupingcharacter/as_argument_of_function/#mathfunctionsoftwoarguments-str) |  |
| [`set_subscript(self, subscript)`](/slides/python-net/fa/aspose.slides.mathtext/imathgroupingcharacter/set_subscript/#imathelement) |  |
| [`set_subscript(self, subscript)`](/slides/python-net/fa/aspose.slides.mathtext/imathgroupingcharacter/set_subscript/#str) |  |
| [`set_superscript(self, superscript)`](/slides/python-net/fa/aspose.slides.mathtext/imathgroupingcharacter/set_superscript/#imathelement) |  |
| [`set_superscript(self, superscript)`](/slides/python-net/fa/aspose.slides.mathtext/imathgroupingcharacter/set_superscript/#str) |  |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/fa/aspose.slides.mathtext/imathgroupingcharacter/set_sub_superscript_on_the_right/#imathelement-imathelement) |  |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/fa/aspose.slides.mathtext/imathgroupingcharacter/set_sub_superscript_on_the_right/#str-str) |  |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/fa/aspose.slides.mathtext/imathgroupingcharacter/set_sub_superscript_on_the_left/#imathelement-imathelement) |  |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/fa/aspose.slides.mathtext/imathgroupingcharacter/set_sub_superscript_on_the_left/#str-str) |  |
| [`radical(self, degree)`](/slides/python-net/fa/aspose.slides.mathtext/imathgroupingcharacter/radical/#imathelement) |  |
| [`radical(self, degree)`](/slides/python-net/fa/aspose.slides.mathtext/imathgroupingcharacter/radical/#str) |  |
| [`set_upper_limit(self, limit)`](/slides/python-net/fa/aspose.slides.mathtext/imathgroupingcharacter/set_upper_limit/#imathelement) |  |
| [`set_upper_limit(self, limit)`](/slides/python-net/fa/aspose.slides.mathtext/imathgroupingcharacter/set_upper_limit/#str) |  |
| [`set_lower_limit(self, limit)`](/slides/python-net/fa/aspose.slides.mathtext/imathgroupingcharacter/set_lower_limit/#imathelement) |  |
| [`set_lower_limit(self, limit)`](/slides/python-net/fa/aspose.slides.mathtext/imathgroupingcharacter/set_lower_limit/#str) |  |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/fa/aspose.slides.mathtext/imathgroupingcharacter/nary/#mathnaryoperatortypes-imathelement-imathelement) |  |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/fa/aspose.slides.mathtext/imathgroupingcharacter/nary/#mathnaryoperatortypes-str-str) |  |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/fa/aspose.slides.mathtext/imathgroupingcharacter/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) |  |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/fa/aspose.slides.mathtext/imathgroupingcharacter/integral/#mathintegraltypes-imathelement-imathelement) |  |
| [`integral(self, integral_type)`](/slides/python-net/fa/aspose.slides.mathtext/imathgroupingcharacter/integral/#mathintegraltypes) |  |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/fa/aspose.slides.mathtext/imathgroupingcharacter/integral/#mathintegraltypes-str-str-mathlimitlocations) |  |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/fa/aspose.slides.mathtext/imathgroupingcharacter/integral/#mathintegraltypes-str-str) |  |
| [`group(self)`](/slides/python-net/fa/aspose.slides.mathtext/imathgroupingcharacter/group/#) |  |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/fa/aspose.slides.mathtext/imathgroupingcharacter/group/#char-mathtopbotpositions-mathtopbotpositions) |  |
| [`to_border_box(self)`](/slides/python-net/fa/aspose.slides.mathtext/imathgroupingcharacter/to_border_box/#) |  |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/fa/aspose.slides.mathtext/imathgroupingcharacter/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) |  |
| [`get_children(self)`](/slides/python-net/fa/aspose.slides.mathtext/imathgroupingcharacter/get_children/#) |  |
| [`to_math_array(self)`](/slides/python-net/fa/aspose.slides.mathtext/imathgroupingcharacter/to_math_array/#) |  |
| [`accent(self, accent_character)`](/slides/python-net/fa/aspose.slides.mathtext/imathgroupingcharacter/accent/#char) |  |
| [`overbar(self)`](/slides/python-net/fa/aspose.slides.mathtext/imathgroupingcharacter/overbar/#) |  |
| [`underbar(self)`](/slides/python-net/fa/aspose.slides.mathtext/imathgroupingcharacter/underbar/#) |  |
| [`to_box(self)`](/slides/python-net/fa/aspose.slides.mathtext/imathgroupingcharacter/to_box/#) |  |

### موارد مرتبط
* ماژول [`aspose.slides.mathtext`](/slides/python-net/fa/aspose.slides.mathtext)
* کتابخانه [`Aspose.Slides`](/slides/python-net)