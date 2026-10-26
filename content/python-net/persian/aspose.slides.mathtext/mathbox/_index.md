---
title: MathBox class
second_title: مرجع API Aspose.Slides برای Python از طریق .NET
description: 
type: docs
url: /fa/aspose.slides.mathtext/mathbox/
---
## MathBox کلاس

Specifies the logical boxing (packaging) of mathematical element.
            For example, a boxed object can serve as an operator emulator with or without an alignment point, 
            serve as a line break point, or be grouped such as not to allow line breaks within.
            For example, the "==" operator should be boxed to prevent line breaks.

**Inheritance:**[`MathBox`](/slides/python-net/fa/aspose.slides.mathtext/mathbox) → [`MathElementBase`](/slides/python-net/fa/aspose.slides.mathtext/mathelementbase)

The MathBox type exposes the following members:

## سازنده‌ها

| Constructor | Description |
| :- | :- |
| [`__init__(self, element)`](/slides/python-net/fa/aspose.slides.mathtext/mathbox/__init__/#imathelement) | Initializes MathBox with the specified element as an argument |

## خواص

| Property | Description |
| :- | :- |
| [`base`](/slides/python-net/fa/aspose.slides.mathtext/mathbox/base/) | آرگومان پایه |
| [`operator_emulator`](/slides/python-net/fa/aspose.slides.mathtext/mathbox/operator_emulator/) | Operator Emulator.<br/>            وقتی مقدار true باشد، جعبه و محتوای آن مانند یک عملگر واحد رفتار کرده و ویژگی‌های یک عملگر را به ارث می‌برد.<br/>            به عنوان مثال، این به این معنی است که کاراکتر می‌تواند به عنوان نقطه‌ای برای شکست خط عمل کند و می‌تواند با سایر عملگرها هم‌راستا شود.<br/>            شبیه‌سازهای عملگر اغلب وقتی که یک یا چند گلیف ترکیب شوند تا یک عملگر تشکیل دهند، مانند '=='.<br/>            مقدار پیش‌فرض: false |
| [`no_break`](/slides/python-net/fa/aspose.slides.mathtext/mathbox/no_break/) | No break<br/>            این ویژگی خصوصیت «قابل شکست نیست» را روی جعبه شیء مشخص می‌کند. وقتی مقدار true باشد، هیچ شکست خطی در داخل جعبه امکان‌پذیر نیست.<br/>            این می‌تواند برای شبیه‌سازهای عملگر که شامل بیش از یک عملگر دودویی هستند مهم باشد.<br/>            وقتی این عنصر مشخص نشده باشد، شکست‌ها می‌توانند داخل جعبه رخ دهند.<br/>            پیش‌فرض: true |
| [`differential`](/slides/python-net/fa/aspose.slides.mathtext/mathbox/differential/) | Differential<br/>            وقتی مقدار true باشد، جعبه به عنوان یک مشتق عمل می‌کند (مثلاً 𝑑𝑥 در یک ادغام) و فاصله افقی مناسب برای مشتق ریاضی دریافت می‌کند.<br/>            پیش‌فرض: false |
| [`alignment_point`](/slides/python-net/fa/aspose.slides.mathtext/mathbox/alignment_point/) | وقتی مقدار true باشد، این شبیه‌ساز عملگر به عنوان یک نقطه هم‌ترازی عمل می‌کند؛ یعنی نقاط هم‌ترازی مشخص شده در معادلات دیگر می‌توانند با آن هم‌تراز شوند.<br/>            پیش‌فرض: false |
| [`explicit_break`](/slides/python-net/fa/aspose.slides.mathtext/mathbox/explicit_break/) | Explicit break specifies whether there is a line break at the start of the Box object, <br/>            such that the line wraps at the start of the box object.<br/>            Specifies the number of the operator on the previous line of mathematical text which shall<br/>            be used as the alignment point for the current line of mathematical text<br/>            possible values: 1..255<br/>            Default: 0 (no explicit break) |

## متدها

| Method | Description |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/fa/aspose.slides.mathtext/mathbox/join/#imathelement) | یک عنصر ریاضی را می‌پیوندد و یک بلوک ریاضی ایجاد می‌کند |
| [`join(self, math_text)`](/slides/python-net/fa/aspose.slides.mathtext/mathbox/join/#str) | یک متن ریاضی را می‌پیوندد و یک بلوک ریاضی ایجاد می‌کند |
| [`divide(self, denominator)`](/slides/python-net/fa/aspose.slides.mathtext/mathbox/divide/#imathelement) | یک کسر با این صورت و مخرج مشخص ایجاد می‌کند |
| [`divide(self, denominator)`](/slides/python-net/fa/aspose.slides.mathtext/mathbox/divide/#str) | یک کسر با این صورت و مخرج مشخص ایجاد می‌کند |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/fa/aspose.slides.mathtext/mathbox/divide/#imathelement-mathfractiontypes) | یک کسر از نوع مشخص با این صورت و مخرج مشخص ایجاد می‌کند |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/fa/aspose.slides.mathtext/mathbox/divide/#str-mathfractiontypes) | یک کسر از نوع مشخص با این صورت و مخرج مشخص ایجاد می‌کند |
| [`enclose(self)`](/slides/python-net/fa/aspose.slides.mathtext/mathbox/enclose/#) | یک عنصر ریاضی را در پرانتز می‌نویسد |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/fa/aspose.slides.mathtext/mathbox/enclose/#char-char) | یک عنصر ریاضی را در کاراکترهای مشخصی مانند پرانتز یا سایر کاراکترها به‌عنوان قاب می‌نویسد |
| [`function(self, function_argument)`](/slides/python-net/fa/aspose.slides.mathtext/mathbox/function/#imathelement) | یک تابع از یک آرگومان را با استفاده از این نمونه به‌عنوان نام تابع می‌گیرد |
| [`function(self, function_argument)`](/slides/python-net/fa/aspose.slides.mathtext/mathbox/function/#str) | یک تابع از یک آرگومان را با استفاده از این نمونه به‌عنوان نام تابع می‌گیرد |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/fa/aspose.slides.mathtext/mathbox/as_argument_of_function/#imathelement) | تابع مشخصی را با استفاده از این نمونه به‌عنوان آرگومان می‌گیرد |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/fa/aspose.slides.mathtext/mathbox/as_argument_of_function/#str) | تابع مشخصی را با استفاده از این نمونه به‌عنوان آرگومان می‌گیرد |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/fa/aspose.slides.mathtext/mathbox/as_argument_of_function/#mathfunctionsofoneargument) | تابع مشخصی را با استفاده از این نمونه به‌عنوان آرگومان می‌گیرد |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/fa/aspose.slides.mathtext/mathbox/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | تابع مشخصی را با استفاده از این نمونه به‌عنوان آرگومان و آرگومان اضافه مشخص می‌گیرد |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/fa/aspose.slides.mathtext/mathbox/as_argument_of_function/#mathfunctionsoftwoarguments-str) | تابع مشخصی را با استفاده از این نمونه به‌عنوان آرگومان و آرگومان اضافه مشخص می‌گیرد |
| [`set_subscript(self, subscript)`](/slides/python-net/fa/aspose.slides.mathtext/mathbox/set_subscript/#imathelement) | زیرنویس ایجاد می‌کند |
| [`set_subscript(self, subscript)`](/slides/python-net/fa/aspose.slides.mathtext/mathbox/set_subscript/#str) | زیرنویس ایجاد می‌کند |
| [`set_superscript(self, superscript)`](/slides/python-net/fa/aspose.slides.mathtext/mathbox/set_superscript/#imathelement) | بالانویس ایجاد می‌کند |
| [`set_superscript(self, superscript)`](/slides/python-net/fa/aspose.slides.mathtext/mathbox/set_superscript/#str) | بالانویس ایجاد می‌کند |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/fa/aspose.slides.mathtext/mathbox/set_sub_superscript_on_the_right/#imathelement-imathelement) | زیرنویس و بالانویس را در سمت راست ایجاد می‌کند |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/fa/aspose.slides.mathtext/mathbox/set_sub_superscript_on_the_right/#str-str) | زیرنویس و بالانویس را در سمت راست ایجاد می‌کند |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/fa/aspose.slides.mathtext/mathbox/set_sub_superscript_on_the_left/#imathelement-imathelement) | زیرنویس و بالانویس را در سمت چپ ایجاد می‌کند |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/fa/aspose.slides.mathtext/mathbox/set_sub_superscript_on_the_left/#str-str) | زیرنویس و بالانویس را در سمت چپ ایجاد می‌کند |
| [`radical(self, degree)`](/slides/python-net/fa/aspose.slides.mathtext/mathbox/radical/#imathelement) | ریشه ریاضی با درجه داده شده از آرگومان مشخص شده را تعیین می‌کند. |
| [`radical(self, degree)`](/slides/python-net/fa/aspose.slides.mathtext/mathbox/radical/#str) | ریشه ریاضی با درجه داده شده از آرگومان مشخص شده را تعیین می‌کند. |
| [`set_upper_limit(self, limit)`](/slides/python-net/fa/aspose.slides.mathtext/mathbox/set_upper_limit/#imathelement) | حد فوقانی را می‌گیرد |
| [`set_upper_limit(self, limit)`](/slides/python-net/fa/aspose.slides.mathtext/mathbox/set_upper_limit/#str) | حد فوقانی را می‌گیرد |
| [`set_lower_limit(self, limit)`](/slides/python-net/fa/aspose.slides.mathtext/mathbox/set_lower_limit/#imathelement) | حد زیرین را می‌گیرد |
| [`set_lower_limit(self, limit)`](/slides/python-net/fa/aspose.slides.mathtext/mathbox/set_lower_limit/#str) | حد زیرین را می‌گیرد |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/fa/aspose.slides.mathtext/mathbox/nary/#mathnaryoperatortypes-imathelement-imathelement) | یک عملگر N-ary ایجاد می‌کند |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/fa/aspose.slides.mathtext/mathbox/nary/#mathnaryoperatortypes-str-str) | یک عملگر N-ary ایجاد می‌کند |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/fa/aspose.slides.mathtext/mathbox/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | انتگرال را می‌گیرد |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/fa/aspose.slides.mathtext/mathbox/integral/#mathintegraltypes-imathelement-imathelement) | انتگرال را می‌گیرد |
| [`integral(self, integral_type)`](/slides/python-net/fa/aspose.slides.mathtext/mathbox/integral/#mathintegraltypes) | انتگرال را بدون حدود می‌گیرد |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/fa/aspose.slides.mathtext/mathbox/integral/#mathintegraltypes-str-str-mathlimitlocations) | انتگرال را می‌گیرد |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/fa/aspose.slides.mathtext/mathbox/integral/#mathintegraltypes-str-str) | انتگرال را می‌گیرد |
| [`group(self)`](/slides/python-net/fa/aspose.slides.mathtext/mathbox/group/#) | این عنصر را با یک کروشه‌پایینی در یک گروه قرار می‌دهد |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/fa/aspose.slides.mathtext/mathbox/group/#char-mathtopbotpositions-mathtopbotpositions) | این عنصر را با یک کاراکتر گروهی مانند کروشه‌پایینی یا کاراکتر دیگر در یک گروه قرار می‌دهد |
| [`to_border_box(self)`](/slides/python-net/fa/aspose.slides.mathtext/mathbox/to_border_box/#) | این عنصر را در یک جعبهٔ حاشیه‌دار قرار می‌دهد |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/fa/aspose.slides.mathtext/mathbox/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | این عنصر را در یک جعبهٔ حاشیه‌دار قرار می‌دهد |
| [`to_math_array(self)`](/slides/python-net/fa/aspose.slides.mathtext/mathbox/to_math_array/#) | در یک آرایهٔ عمودی قرار می‌دهد |
| [`accent(self, accent_character)`](/slides/python-net/fa/aspose.slides.mathtext/mathbox/accent/#char) | یک علامت لهجه (یک کاراکتر در بالای این عنصر) تنظیم می‌کند |
| [`overbar(self)`](/slides/python-net/fa/aspose.slides.mathtext/mathbox/overbar/#) | نوار را در بالای این عنصر تنظیم می‌کند |
| [`underbar(self)`](/slides/python-net/fa/aspose.slides.mathtext/mathbox/underbar/#) | نوار را در پایین این عنصر تنظیم می‌کند |
| [`to_box(self)`](/slides/python-net/fa/aspose.slides.mathtext/mathbox/to_box/#) | این عنصر را در یک جعبهٔ غیر بصری (گروه‌بندی منطقی) قرار می‌دهد <br/>            که برای گروه‌بندی اجزاء یک معادله یا نمونه دیگری از متن ریاضی استفاده می‌شود.<br/>            یک شیء جعبه‌شده می‌تواند (به عنوان مثال) به عنوان شبیه‌ساز عملگر با یا بدون نقطه هم‌ترازی عمل کند، <br/>            به عنوان نقطه شکست خط عمل کند، یا به‌گونه‌ای گروه‌بندی شود که اجازه شکست خط در داخل آن ندهد. |
| [`get_children(self)`](/slides/python-net/fa/aspose.slides.mathtext/mathbox/get_children/#) | Get children elements |

### موارد مرتبط
* کلاس [`MathBox`](/slides/python-net/fa/aspose.slides.mathtext/mathbox)
* کلاس [`MathElementBase`](/slides/python-net/fa/aspose.slides.mathtext/mathelementbase)
* ماژول [`aspose.slides.mathtext`](/slides/python-net/fa/aspose.slides.mathtext)
* کتابخانه [`Aspose.Slides`](/slides/python-net)