---
title: MathNaryOperator class
second_title: مرجع API Aspose.Slides برای Python از طریق .NET
description: 
type: docs
url: /fa/aspose.slides.mathtext/mathnaryoperator/
---
## MathNaryOperator کلاس

Specifies an N-ary mathematical object, such as Summation and Integral.
            It consists of an operator, a base (or operand), and optional upper and lower limits. 
            Examples of N-ary operators are: Summation, Union, Intersection, Integral

**Inheritance:**[`MathNaryOperator`](/slides/python-net/fa/aspose.slides.mathtext/mathnaryoperator) → [`MathElementBase`](/slides/python-net/fa/aspose.slides.mathtext/mathelementbase)

The MathNaryOperator type exposes the following members:

## سازندگان

| سازنده | توضیح |
| :- | :- |
| [`__init__(self, operator_symbol, base_argument, lower_limit, upper_limit)`](/slides/python-net/fa/aspose.slides.mathtext/mathnaryoperator/__init__/#char-imathelement-imathelement-imathelement) | یک نمونه جدید از کلاس MathNaryOperator را مقداردهی اولیه می‌کند. |
| [`__init__(self, operator_symbol, base_argument, lower_limit)`](/slides/python-net/fa/aspose.slides.mathtext/mathnaryoperator/__init__/#char-imathelement-imathelement) | یک نمونه جدید از کلاس MathNaryOperator را مقداردهی اولیه می‌کند. |
| [`__init__(self, operator_symbol, base_argument)`](/slides/python-net/fa/aspose.slides.mathtext/mathnaryoperator/__init__/#char-imathelement) | یک نمونه جدید از کلاس MathNaryOperator را مقداردهی اولیه می‌کند. |

## ویژگی‌ها

| ویژگی | توضیح |
| :- | :- |
| [`base`](/slides/python-net/fa/aspose.slides.mathtext/mathnaryoperator/base/) | آرگومان پایه |
| [`subscript`](/slides/python-net/fa/aspose.slides.mathtext/mathnaryoperator/subscript/) | یک آرگومان زیرنویس را مشخص می‌کند که به عنوان مثال در حالت انتگرال، حد پایین را تعیین می‌کند |
| [`superscript`](/slides/python-net/fa/aspose.slides.mathtext/mathnaryoperator/superscript/) | یک آرگومان بالانویس را مشخص می‌کند که به عنوان مثال در حالت انتگرال، حد فوقانی را تعیین می‌کند |
| [`operator`](/slides/python-net/fa/aspose.slides.mathtext/mathnaryoperator/operator/) | کاراکتر عملگر Nary<br/>            به عنوان مثال: '∑', '∫' |
| [`limit_location`](/slides/python-net/fa/aspose.slides.mathtext/mathnaryoperator/limit_location/) | محل نمایش حدود (زیرنویس و بالانویس) |
| [`grow_to_match_operand_height`](/slides/python-net/fa/aspose.slides.mathtext/mathnaryoperator/grow_to_match_operand_height/) | کاراکتر عملگر به صورت عمودی بزرگ می‌شود تا با ارتفاع عملوند تطبیق یابد |
| [`hide_subscript`](/slides/python-net/fa/aspose.slides.mathtext/mathnaryoperator/hide_subscript/) | پنهان کردن زیرنویس |
| [`hide_superscript`](/slides/python-net/fa/aspose.slides.mathtext/mathnaryoperator/hide_superscript/) | پنهان کردن بالانویس |

## متدها

| متد | توضیح |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/fa/aspose.slides.mathtext/mathnaryoperator/join/#imathelement) | یک عنصر ریاضی را ترکیب می‌کند و یک بلوک ریاضی ایجاد می‌سازد |
| [`join(self, math_text)`](/slides/python-net/fa/aspose.slides.mathtext/mathnaryoperator/join/#str) | متن ریاضی را ترکیب می‌کند و یک بلوک ریاضی ایجاد می‌سازد |
| [`divide(self, denominator)`](/slides/python-net/fa/aspose.slides.mathtext/mathnaryoperator/divide/#imathelement) | کسر را با صورت این و مخرج مشخص شده ایجاد می‌کند |
| [`divide(self, denominator)`](/slides/python-net/fa/aspose.slides.mathtext/mathnaryoperator/divide/#str) | کسر را با صورت این و مخرج مشخص شده ایجاد می‌کند |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/fa/aspose.slides.mathtext/mathnaryoperator/divide/#imathelement-mathfractiontypes) | کسر را از نوع مشخص شده با صورت این و مخرج مشخص شده ایجاد می‌کند |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/fa/aspose.slides.mathtext/mathnaryoperator/divide/#str-mathfractiontypes) | کسر را از نوع مشخص شده با صورت این و مخرج مشخص شده ایجاد می‌کند |
| [`enclose(self)`](/slides/python-net/fa/aspose.slides.mathtext/mathnaryoperator/enclose/#) | یک عنصر ریاضی را در پرانتز می‌گیرد |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/fa/aspose.slides.mathtext/mathnaryoperator/enclose/#char-char) | یک عنصر ریاضی را در کاراکترهای مشخصی مانند پرانتز یا سایر کاراکترها به عنوان قاب می‌گیرد |
| [`function(self, function_argument)`](/slides/python-net/fa/aspose.slides.mathtext/mathnaryoperator/function/#imathelement) | یک تابع از آرگومان می‌گیرد که از این نمونه به عنوان نام تابع استفاده می‌کند |
| [`function(self, function_argument)`](/slides/python-net/fa/aspose.slides.mathtext/mathnaryoperator/function/#str) | یک تابع از آرگومان می‌گیرد که از این نمونه به عنوان نام تابع استفاده می‌کند |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/fa/aspose.slides.mathtext/mathnaryoperator/as_argument_of_function/#imathelement) | تابع مشخص شده‌ای را می‌گیرد که این نمونه را به عنوان آرگومان استفاده می‌کند |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/fa/aspose.slides.mathtext/mathnaryoperator/as_argument_of_function/#str) | تابع مشخص شده‌ای را می‌گیرد که این نمونه را به عنوان آرگومان استفاده می‌کند |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/fa/aspose.slides.mathtext/mathnaryoperator/as_argument_of_function/#mathfunctionsofoneargument) | تابع مشخص شده‌ای را می‌گیرد که این نمونه را به عنوان آرگومان استفاده می‌کند |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/fa/aspose.slides.mathtext/mathnaryoperator/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | تابع مشخص شده‌ای را می‌گیرد که این نمونه را به عنوان آرگومان استفاده می‌کند و آرگومان اضافه‌تری را نیز می‌پذیرد |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/fa/aspose.slides.mathtext/mathnaryoperator/as_argument_of_function/#mathfunctionsoftwoarguments-str) | تابع مشخص شده‌ای را می‌گیرد که این نمونه را به عنوان آرگومان استفاده می‌کند و آرگومان اضافه‌تری را نیز می‌پذیرد |
| [`set_subscript(self, subscript)`](/slides/python-net/fa/aspose.slides.mathtext/mathnaryoperator/set_subscript/#imathelement) | زیرنویس ایجاد می‌کند |
| [`set_subscript(self, subscript)`](/slides/python-net/fa/aspose.slides.mathtext/mathnaryoperator/set_subscript/#str) | زیرنویس ایجاد می‌کند |
| [`set_superscript(self, superscript)`](/slides/python-net/fa/aspose.slides.mathtext/mathnaryoperator/set_superscript/#imathelement) | بالانویس ایجاد می‌کند |
| [`set_superscript(self, superscript)`](/slides/python-net/fa/aspose.slides.mathtext/mathnaryoperator/set_superscript/#str) | بالانویس ایجاد می‌کند |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/fa/aspose.slides.mathtext/mathnaryoperator/set_sub_superscript_on_the_right/#imathelement-imathelement) | زیرنویس و بالانویس را در سمت راست ایجاد می‌کند |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/fa/aspose.slides.mathtext/mathnaryoperator/set_sub_superscript_on_the_right/#str-str) | زیرنویس و بالانویس را در سمت راست ایجاد می‌کند |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/fa/aspose.slides.mathtext/mathnaryoperator/set_sub_superscript_on_the_left/#imathelement-imathelement) | زیرنویس و بالانویس را در سمت چپ ایجاد می‌کند |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/fa/aspose.slides.mathtext/mathnaryoperator/set_sub_superscript_on_the_left/#str-str) | زیرنویس و بالانویس را در سمت چپ ایجاد می‌کند |
| [`radical(self, degree)`](/slides/python-net/fa/aspose.slides.mathtext/mathnaryoperator/radical/#imathelement) | ریشه ریاضی از درجه داده‌شده را از آرگومان مشخص شده تعیین می‌کند. |
| [`radical(self, degree)`](/slides/python-net/fa/aspose.slides.mathtext/mathnaryoperator/radical/#str) | ریشه ریاضی از درجه داده‌شده را از آرگومان مشخص شده تعیین می‌کند. |
| [`set_upper_limit(self, limit)`](/slides/python-net/fa/aspose.slides.mathtext/mathnaryoperator/set_upper_limit/#imathelement) | حد بالایی را می‌گیرد |
| [`set_upper_limit(self, limit)`](/slides/python-net/fa/aspose.slides.mathtext/mathnaryoperator/set_upper_limit/#str) | حد بالایی را می‌گیرد |
| [`set_lower_limit(self, limit)`](/slides/python-net/fa/aspose.slides.mathtext/mathnaryoperator/set_lower_limit/#imathelement) | حد پایین را می‌گیرد |
| [`set_lower_limit(self, limit)`](/slides/python-net/fa/aspose.slides.mathtext/mathnaryoperator/set_lower_limit/#str) | حد پایین را می‌گیرد |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/fa/aspose.slides.mathtext/mathnaryoperator/nary/#mathnaryoperatortypes-imathelement-imathelement) | یک عملگر N-ary ایجاد می‌کند |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/fa/aspose.slides.mathtext/mathnaryoperator/nary/#mathnaryoperatortypes-str-str) | یک عملگر N-ary ایجاد می‌کند |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/fa/aspose.slides.mathtext/mathnaryoperator/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | انتگرال را می‌گیرد |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/fa/aspose.slides.mathtext/mathnaryoperator/integral/#mathintegraltypes-imathelement-imathelement) | انتگرال را می‌گیرد |
| [`integral(self, integral_type)`](/slides/python-net/fa/aspose.slides.mathtext/mathnaryoperator/integral/#mathintegraltypes) | انتگرال را بدون حدود می‌گیرد |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/fa/aspose.slides.mathtext/mathnaryoperator/integral/#mathintegraltypes-str-str-mathlimitlocations) | انتگرال را می‌گیرد |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/fa/aspose.slides.mathtext/mathnaryoperator/integral/#mathintegraltypes-str-str) | انتگرال را می‌گیرد |
| [`group(self)`](/slides/python-net/fa/aspose.slides.mathtext/mathnaryoperator/group/#) | این عنصر را با استفاده از کروشهٔ پایین در یک گروه قرار می‌دهد |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/fa/aspose.slides.mathtext/mathnaryoperator/group/#char-mathtopbotpositions-mathtopbotpositions) | این عنصر را با استفاده از کاراکتر گروه‌بندی مانند کروشهٔ پایین یا سایر کاراکترها در یک گروه قرار می‌دهد |
| [`to_border_box(self)`](/slides/python-net/fa/aspose.slides.mathtext/mathnaryoperator/to_border_box/#) | این عنصر را در یک جعبه مرزی قرار می‌دهد |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/fa/aspose.slides.mathtext/mathnaryoperator/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | این عنصر را در یک جعبه مرزی قرار می‌دهد |
| [`to_math_array(self)`](/slides/python-net/fa/aspose.slides.mathtext/mathnaryoperator/to_math_array/#) | در آرایهٔ عمودی قرار می‌دهد |
| [`accent(self, accent_character)`](/slides/python-net/fa/aspose.slides.mathtext/mathnaryoperator/accent/#char) | علامت لهجه (یک کاراکتر در بالای این عنصر) را تنظیم می‌کند |
| [`overbar(self)`](/slides/python-net/fa/aspose.slides.mathtext/mathnaryoperator/overbar/#) | خطی در بالای این عنصر تنظیم می‌کند |
| [`underbar(self)`](/slides/python-net/fa/aspose.slides.mathtext/mathnaryoperator/underbar/#) | خطی در پایین این عنصر تنظیم می‌کند |
| [`to_box(self)`](/slides/python-net/fa/aspose.slides.mathtext/mathnaryoperator/to_box/#) | این عنصر را در یک جعبه غیر‌نمایشی (گروه‌بندی منطقی) <br/>            که برای گروه‌بندی مؤلفه‌های یک معادله یا سایر متون ریاضی استفاده می‌شود.<br/>            یک شی جعبه‌شده می‌تواند (به عنوان مثال) به عنوان شبیه‌ساز عملگر با یا بدون نقطهٔ تراز عمل کند، <br/>            به عنوان نقطهٔ شکست خط عمل کند، یا به‌گونه‌ای گروه‌بندی شود که اجازهٔ شکست خط درون آن نشود. |
| [`get_children(self)`](/slides/python-net/fa/aspose.slides.mathtext/mathnaryoperator/get_children/#) | دریافت عناصر فرزند |

### مراجع دیگر
* کلاس [`MathElementBase`](/slides/python-net/fa/aspose.slides.mathtext/mathelementbase)
* کلاس [`MathNaryOperator`](/slides/python-net/fa/aspose.slides.mathtext/mathnaryoperator)
* ماژول [`aspose.slides.mathtext`](/slides/python-net/fa/aspose.slides.mathtext)
* کتابخانه [`Aspose.Slides`](/slides/python-net)