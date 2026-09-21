---
title: IMathDelimiter class
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides.mathtext/imathdelimiter/
---
## IMathDelimiter کلاس

شیء جداکننده را مشخص می‌کند که شامل کاراکترهای شروع و پایان (مانند پرانتز، 
            کروشه، قوس و خطوط عمودی) و یک یا چند عنصر ریاضی در داخل آن است که توسط یک کاراکتر مشخص جدا می‌شوند.
            مثال‌ها: (𝑥2); [𝑥2|𝑦2]

The IMathDelimiter type exposes the following members:

## ویژگی‌ها

| ویژگی | توضیح |
| :- | :- |
| [`arguments`](/slides/python-net/fa/aspose.slides.mathtext/imathdelimiter/arguments/) | یک یا چند عنصر ریاضی که توسط کاراکترهای جداکننده جدا شده‌اند |
| [`beginning_character`](/slides/python-net/fa/aspose.slides.mathtext/imathdelimiter/beginning_character/) | کاراکتر شروع جداکننده مقدار شروع یا کاراکتر باز شدن جداکننده را مشخص می‌کند. <br/>            جداکننده‌های ریاضی کاراکترهای محاطی مانند پرانتز، قوس و کروشه هستند.<br/>            مقدار پیش‌فرض: '('. |
| [`separator_character`](/slides/python-net/fa/aspose.slides.mathtext/imathdelimiter/separator_character/) | کاراکتر جداکننده جداکننده مقدار کاراکتری را که آرگومان‌ها را در شیء جداکننده جدا می‌کند، مشخص می‌کند. <br/>            مقدار پیش‌فرض: '\|'. |
| [`ending_character`](/slides/python-net/fa/aspose.slides.mathtext/imathdelimiter/ending_character/) | کاراکتر پایان جداکننده مقدار پایان یا کاراکتر بسته شدن جداکننده را مشخص می‌کند. <br/>            جداکننده‌های ریاضی کاراکترهای محاطی مانند پرانتز، قوس و کروشه هستند.<br/>            مقدار پیش‌فرض: ')'. |
| [`grow_to_match_operand_height`](/slides/python-net/fa/aspose.slides.mathtext/imathdelimiter/grow_to_match_operand_height/) | رشد BeginningCharacter, SeparatorCharacter, EndingCharacter را مشخص می‌کند<br/>            هنگامی که مقدار true باشد، جداکننده‌ها به صورت عمودی رشد می‌کنند تا با ارتفاع عملوندشان همخوانی داشته باشند.<br/>            مقدار پیش‌فرض true است |
| [`delimiter_shape`](/slides/python-net/fa/aspose.slides.mathtext/imathdelimiter/delimiter_shape/) | شکل جداکننده‌ها در شیء جداکننده را مشخص می‌کند. <br/>            وقتی مقدار MathDelimiterShape.Centered باشد، جداکننده‌ها حول محور ریاضی متن ریاضی متمرکز می‌شوند <br/>            و هنوز برای پر کردن تمام ارتفاع محتواهایشان تنظیم می‌شوند.<br/>            وقتی مقدار MathDelimiterShape.Match باشد، ارتفاع و شکل آن‌ها دقیقاً با محتواهایشان منطبق می‌شود. |

## متدها

| متد | توضیح |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/fa/aspose.slides.mathtext/imathdelimiter/join/#imathelement) |  |
| [`join(self, math_text)`](/slides/python-net/fa/aspose.slides.mathtext/imathdelimiter/join/#str) |  |
| [`divide(self, denominator)`](/slides/python-net/fa/aspose.slides.mathtext/imathdelimiter/divide/#imathelement) |  |
| [`divide(self, denominator)`](/slides/python-net/fa/aspose.slides.mathtext/imathdelimiter/divide/#str) |  |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/fa/aspose.slides.mathtext/imathdelimiter/divide/#imathelement-mathfractiontypes) |  |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/fa/aspose.slides.mathtext/imathdelimiter/divide/#str-mathfractiontypes) |  |
| [`enclose(self)`](/slides/python-net/fa/aspose.slides.mathtext/imathdelimiter/enclose/#) |  |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/fa/aspose.slides.mathtext/imathdelimiter/enclose/#char-char) |  |
| [`function(self, function_argument)`](/slides/python-net/fa/aspose.slides.mathtext/imathdelimiter/function/#imathelement) |  |
| [`function(self, function_argument)`](/slides/python-net/fa/aspose.slides.mathtext/imathdelimiter/function/#str) |  |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/fa/aspose.slides.mathtext/imathdelimiter/as_argument_of_function/#imathelement) |  |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/fa/aspose.slides.mathtext/imathdelimiter/as_argument_of_function/#str) |  |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/fa/aspose.slides.mathtext/imathdelimiter/as_argument_of_function/#mathfunctionsofoneargument) |  |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/fa/aspose.slides.mathtext/imathdelimiter/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) |  |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/fa/aspose.slides.mathtext/imathdelimiter/as_argument_of_function/#mathfunctionsoftwoarguments-str) |  |
| [`set_subscript(self, subscript)`](/slides/python-net/fa/aspose.slides.mathtext/imathdelimiter/set_subscript/#imathelement) |  |
| [`set_subscript(self, subscript)`](/slides/python-net/fa/aspose.slides.mathtext/imathdelimiter/set_subscript/#str) |  |
| [`set_superscript(self, superscript)`](/slides/python-net/fa/aspose.slides.mathtext/imathdelimiter/set_superscript/#imathelement) |  |
| [`set_superscript(self, superscript)`](/slides/python-net/fa/aspose.slides.mathtext/imathdelimiter/set_superscript/#str) |  |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/fa/aspose.slides.mathtext/imathdelimiter/set_sub_superscript_on_the_right/#imathelement-imathelement) |  |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/fa/aspose.slides.mathtext/imathdelimiter/set_sub_superscript_on_the_right/#str-str) |  |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/fa/aspose.slides.mathtext/imathdelimiter/set_sub_superscript_on_the_left/#imathelement-imathelement) |  |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/fa/aspose.slides.mathtext/imathdelimiter/set_sub_superscript_on_the_left/#str-str) |  |
| [`radical(self, degree)`](/slides/python-net/fa/aspose.slides.mathtext/imathdelimiter/radical/#imathelement) |  |
| [`radical(self, degree)`](/slides/python-net/fa/aspose.slides.mathtext/imathdelimiter/radical/#str) |  |
| [`set_upper_limit(self, limit)`](/slides/python-net/fa/aspose.slides.mathtext/imathdelimiter/set_upper_limit/#imathelement) |  |
| [`set_upper_limit(self, limit)`](/slides/python-net/fa/aspose.slides.mathtext/imathdelimiter/set_upper_limit/#str) |  |
| [`set_lower_limit(self, limit)`](/slides/python-net/fa/aspose.slides.mathtext/imathdelimiter/set_lower_limit/#imathelement) |  |
| [`set_lower_limit(self, limit)`](/slides/python-net/fa/aspose.slides.mathtext/imathdelimiter/set_lower_limit/#str) |  |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/fa/aspose.slides.mathtext/imathdelimiter/nary/#mathnaryoperatortypes-imathelement-imathelement) |  |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/fa/aspose.slides.mathtext/imathdelimiter/nary/#mathnaryoperatortypes-str-str) |  |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/fa/aspose.slides.mathtext/imathdelimiter/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) |  |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/fa/aspose.slides.mathtext/imathdelimiter/integral/#mathintegraltypes-imathelement-imathelement) |  |
| [`integral(self, integral_type)`](/slides/python-net/fa/aspose.slides.mathtext/imathdelimiter/integral/#mathintegraltypes) |  |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/fa/aspose.slides.mathtext/imathdelimiter/integral/#mathintegraltypes-str-str-mathlimitlocations) |  |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/fa/aspose.slides.mathtext/imathdelimiter/integral/#mathintegraltypes-str-str) |  |
| [`group(self)`](/slides/python-net/fa/aspose.slides.mathtext/imathdelimiter/group/#) |  |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/fa/aspose.slides.mathtext/imathdelimiter/group/#char-mathtopbotpositions-mathtopbotpositions) |  |
| [`to_border_box(self)`](/slides/python-net/fa/aspose.slides.mathtext/imathdelimiter/to_border_box/#) |  |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/fa/aspose.slides.mathtext/imathdelimiter/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) |  |
| [`delimit(self, separator_character)`](/slides/python-net/fa/aspose.slides.mathtext/imathdelimiter/delimit/#char) | Delimits arguments using the specified delimiter character |
| [`get_children(self)`](/slides/python-net/fa/aspose.slides.mathtext/imathdelimiter/get_children/#) |  |
| [`to_math_array(self)`](/slides/python-net/fa/aspose.slides.mathtext/imathdelimiter/to_math_array/#) |  |
| [`accent(self, accent_character)`](/slides/python-net/fa/aspose.slides.mathtext/imathdelimiter/accent/#char) |  |
| [`overbar(self)`](/slides/python-net/fa/aspose.slides.mathtext/imathdelimiter/overbar/#) |  |
| [`underbar(self)`](/slides/python-net/fa/aspose.slides.mathtext/imathdelimiter/underbar/#) |  |
| [`to_box(self)`](/slides/python-net/fa/aspose.slides.mathtext/imathdelimiter/to_box/#) |  |

### مراجعه به
* ماژول [`aspose.slides.mathtext`](/slides/python-net/fa/aspose.slides.mathtext)
* کتابخانه [`Aspose.Slides`](/slides/python-net)