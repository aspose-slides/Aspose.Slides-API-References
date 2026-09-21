---
title: MathematicalText class
second_title: مرجع API Aspose.Slides برای Python از طریق .NET
description: 
type: docs
url: /fa/aspose.slides.mathtext/mathematicaltext/
---
## MathematicalText کلاس

متن ریاضی

**Inheritance:**[`MathematicalText`](/slides/python-net/fa/aspose.slides.mathtext/mathematicaltext) → [`MathElementBase`](/slides/python-net/fa/aspose.slides.mathtext/mathelementbase)

نوع MathematicalText اعضای زیر را نشان می‌دهد:

## سازنده‌ها

| سازنده | توضیح |
| :- | :- |
| [`__init__(self)`](/slides/python-net/fa/aspose.slides.mathtext/mathematicaltext/__init__/#) | سازنده پیش‌فرض (ایجاد مقدار String.Empty) |
| [`__init__(self, math_symbol)`](/slides/python-net/fa/aspose.slides.mathtext/mathematicaltext/__init__/#char) | ایجاد MathText با یک نماد منفرد |
| [`__init__(self, math_text)`](/slides/python-net/fa/aspose.slides.mathtext/mathematicaltext/__init__/#str) | ایجاد MathematicalText از متن |
| [`__init__(self, math_text, portion_format)`](/slides/python-net/fa/aspose.slides.mathtext/mathematicaltext/__init__/#str-iportionformat) | ایجاد MathematicalText از متن و تنظیمات قالب |

## خواص

| ویژگی | توضیح |
| :- | :- |
| [`value`](/slides/python-net/fa/aspose.slides.mathtext/mathematicaltext/value/) | مقدار متن |
| [`format`](/slides/python-net/fa/aspose.slides.mathtext/mathematicaltext/format/) | ویژگی‌های قالب‌بندی متن |

## متدها

| متد | توضیح |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/fa/aspose.slides.mathtext/mathematicaltext/join/#imathelement) | یک عنصر ریاضی را می‌پیونَد و یک بلوک ریاضی ایجاد می‌کند |
| [`join(self, math_text)`](/slides/python-net/fa/aspose.slides.mathtext/mathematicaltext/join/#str) | یک متن ریاضی را می‌پیونَد و یک بلوک ریاضی ایجاد می‌کند |
| [`divide(self, denominator)`](/slides/python-net/fa/aspose.slides.mathtext/mathematicaltext/divide/#imathelement) | یک کسر با این صورت و مخرج مشخص ایجاد می‌کند |
| [`divide(self, denominator)`](/slides/python-net/fa/aspose.slides.mathtext/mathematicaltext/divide/#str) | یک کسر با این صورت و مخرج مشخص ایجاد می‌کند |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/fa/aspose.slides.mathtext/mathematicaltext/divide/#imathelement-mathfractiontypes) | یک کسر از نوع مشخص با این صورت و مخرج مشخص ایجاد می‌کند |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/fa/aspose.slides.mathtext/mathematicaltext/divide/#str-mathfractiontypes) | یک کسر از نوع مشخص با این صورت و مخرج مشخص ایجاد می‌کند |
| [`enclose(self)`](/slides/python-net/fa/aspose.slides.mathtext/mathematicaltext/enclose/#) | یک عنصر ریاضی را در پرانتز می‌گذارد |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/fa/aspose.slides.mathtext/mathematicaltext/enclose/#char-char) | یک عنصر ریاضی را در نویسه‌های مشخص مانند پرانتز یا سایر نویسه‌ها به عنوان قاب می‌گذارد |
| [`function(self, function_argument)`](/slides/python-net/fa/aspose.slides.mathtext/mathematicaltext/function/#imathelement) | یک تابع از یک آرگومان می‌گیرد که این نمونه به عنوان نام تابع استفاده می‌شود |
| [`function(self, function_argument)`](/slides/python-net/fa/aspose.slides.mathtext/mathematicaltext/function/#str) | یک تابع از یک آرگومان می‌گیرد که این نمونه به عنوان نام تابع استفاده می‌شود |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/fa/aspose.slides.mathtext/mathematicaltext/as_argument_of_function/#imathelement) | تابع مشخصی را می‌گیرد که این نمونه به عنوان آرگومان استفاده می‌شود |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/fa/aspose.slides.mathtext/mathematicaltext/as_argument_of_function/#str) | تابع مشخصی را می‌گیرد که این نمونه به عنوان آرگومان استفاده می‌شود |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/fa/aspose.slides.mathtext/mathematicaltext/as_argument_of_function/#mathfunctionsofoneargument) | تابع مشخصی را می‌گیرد که این نمونه به عنوان آرگومان استفاده می‌شود |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/fa/aspose.slides.mathtext/mathematicaltext/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | تابع مشخصی را می‌گیرد که این نمونه به عنوان آرگومان و یک آرگومان اضافی مشخص به کار می‌رود |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/fa/aspose.slides.mathtext/mathematicaltext/as_argument_of_function/#mathfunctionsoftwoarguments-str) | تابع مشخصی را می‌گیرد که این نمونه به عنوان آرگومان و یک آرگومان اضافی مشخص به کار می‌رود |
| [`set_subscript(self, subscript)`](/slides/python-net/fa/aspose.slides.mathtext/mathematicaltext/set_subscript/#imathelement) | ایجاد زیرنویس |
| [`set_subscript(self, subscript)`](/slides/python-net/fa/aspose.slides.mathtext/mathematicaltext/set_subscript/#str) | ایجاد زیرنویس |
| [`set_superscript(self, superscript)`](/slides/python-net/fa/aspose.slides.mathtext/mathematicaltext/set_superscript/#imathelement) | ایجاد بالانویس |
| [`set_superscript(self, superscript)`](/slides/python-net/fa/aspose.slides.mathtext/mathematicaltext/set_superscript/#str) | ایجاد بالانویس |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/fa/aspose.slides.mathtext/mathematicaltext/set_sub_superscript_on_the_right/#imathelement-imathelement) | زیرنویس و بالانویس را در سمت راست ایجاد می‌کند |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/fa/aspose.slides.mathtext/mathematicaltext/set_sub_superscript_on_the_right/#str-str) | زیرنویس و بالانویس را در سمت راست ایجاد می‌کند |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/fa/aspose.slides.mathtext/mathematicaltext/set_sub_superscript_on_the_left/#imathelement-imathelement) | زیرنویس و بالانویس را در سمت چپ ایجاد می‌کند |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/fa/aspose.slides.mathtext/mathematicaltext/set_sub_superscript_on_the_left/#str-str) | زیرنویس و بالانویس را در سمت چپ ایجاد می‌کند |
| [`radical(self, degree)`](/slides/python-net/fa/aspose.slides.mathtext/mathematicaltext/radical/#imathelement) | ریشه ریاضی با درجه داده‌شده را از آرگومان مشخص تعیین می‌کند. |
| [`radical(self, degree)`](/slides/python-net/fa/aspose.slides.mathtext/mathematicaltext/radical/#str) | ریشه ریاضی با درجه داده‌شده را از آرگومان مشخص تعیین می‌کند. |
| [`set_upper_limit(self, limit)`](/slides/python-net/fa/aspose.slides.mathtext/mathematicaltext/set_upper_limit/#imathelement) | حد بالایی را می‌گیرد |
| [`set_upper_limit(self, limit)`](/slides/python-net/fa/aspose.slides.mathtext/mathematicaltext/set_upper_limit/#str) | حد بالایی را می‌گیرد |
| [`set_lower_limit(self, limit)`](/slides/python-net/fa/aspose.slides.mathtext/mathematicaltext/set_lower_limit/#imathelement) | حد پایینی را می‌گیرد |
| [`set_lower_limit(self, limit)`](/slides/python-net/fa/aspose.slides.mathtext/mathematicaltext/set_lower_limit/#str) | حد پایینی را می‌گیرد |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/fa/aspose.slides.mathtext/mathematicaltext/nary/#mathnaryoperatortypes-imathelement-imathelement) | یک عملگر N-ary ایجاد می‌کند |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/fa/aspose.slides.mathtext/mathematicaltext/nary/#mathnaryoperatortypes-str-str) | یک عملگر N-ary ایجاد می‌کند |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/fa/aspose.slides.mathtext/mathematicaltext/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | انتگرال را می‌گیرد |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/fa/aspose.slides.mathtext/mathematicaltext/integral/#mathintegraltypes-imathelement-imathelement) | انتگرال را می‌گیرد |
| [`integral(self, integral_type)`](/slides/python-net/fa/aspose.slides.mathtext/mathematicaltext/integral/#mathintegraltypes) | انتگرال بدون حدها را می‌گیرد |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/fa/aspose.slides.mathtext/mathematicaltext/integral/#mathintegraltypes-str-str-mathlimitlocations) | انتگرال را می‌گیرد |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/fa/aspose.slides.mathtext/mathematicaltext/integral/#mathintegraltypes-str-str) | انتگرال را می‌گیرد |
| [`group(self)`](/slides/python-net/fa/aspose.slides.mathtext/mathematicaltext/group/#) | این عنصر را با استفاده از کروشه قوسی پایین در یک گروه قرار می‌دهد |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/fa/aspose.slides.mathtext/mathematicaltext/group/#char-mathtopbotpositions-mathtopbotpositions) | این عنصر را با استفاده از نویسهٔ گروه‌بندی مانند کروشه قوسی پایین یا دیگری در یک گروه قرار می‌دهد |
| [`to_border_box(self)`](/slides/python-net/fa/aspose.slides.mathtext/mathematicaltext/to_border_box/#) | این عنصر را در یک border-box قرار می‌دهد |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/fa/aspose.slides.mathtext/mathematicaltext/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | این عنصر را در یک border-box قرار می‌دهد |
| [`to_math_array(self)`](/slides/python-net/fa/aspose.slides.mathtext/mathematicaltext/to_math_array/#) | در یک آرایه عمودی قرار می‌دهد |
| [`accent(self, accent_character)`](/slides/python-net/fa/aspose.slides.mathtext/mathematicaltext/accent/#char) | علامت لهجه را تنظیم می‌کند (یک نویسه در بالای این عنصر) |
| [`overbar(self)`](/slides/python-net/fa/aspose.slides.mathtext/mathematicaltext/overbar/#) | یک نوار در بالای این عنصر تنظیم می‌کند |
| [`underbar(self)`](/slides/python-net/fa/aspose.slides.mathtext/mathematicaltext/underbar/#) | یک نوار در پایین این عنصر تنظیم می‌کند |
| [`to_box(self)`](/slides/python-net/fa/aspose.slides.mathtext/mathematicaltext/to_box/#) | این عنصر را در یک جعبه غیر‌نمایشی (گروه‌بندی منطقی) قرار می‌دهد <br/>            که برای گروه‌بندی مؤلفه‌های یک معادله یا سایر نمونه‌های متن ریاضی استفاده می‌شود.<br/>            یک شیء جعبه‌دار می‌تواند (به عنوان مثال) به عنوان شبیه‌ساز عملگر با یا بدون نقطه‌هم‌راستا عمل کند، <br/>            به عنوان نقطه شکست خط عمل کند، یا به‌گونه‌ای گروه‌بندی شود که از شکست خط درون آن جلوگیری شود. |
| [`get_children(self)`](/slides/python-net/fa/aspose.slides.mathtext/mathematicaltext/get_children/#) |  |

### موارد مرتبط
* کلاس [`MathElementBase`](/slides/python-net/fa/aspose.slides.mathtext/mathelementbase)
* کلاس [`MathematicalText`](/slides/python-net/fa/aspose.slides.mathtext/mathematicaltext)
* ماژول [`aspose.slides.mathtext`](/slides/python-net/fa/aspose.slides.mathtext)
* کتابخانه [`Aspose.Slides`](/slides/python-net)