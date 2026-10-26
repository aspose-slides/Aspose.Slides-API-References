---
title: MathArray class
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides.mathtext/matharray/
---
## MathArray کلاس

Specifies a vertical array of equations or any mathematical objects

**Inheritance:**[`MathArray`](/slides/python-net/fa/aspose.slides.mathtext/matharray) → [`MathElementBase`](/slides/python-net/fa/aspose.slides.mathtext/mathelementbase)

The MathArray type exposes the following members:

## سازنده‌ها

| سازنده | توضیح |
| :- | :- |
| [`__init__(self, element)`](/slides/python-net/fa/aspose.slides.mathtext/matharray/__init__/#imathelement) | یک آرایهٔ ریاضی ایجاد می‌کند و عنصر مشخص‌شده را در آن قرار می‌دهد |
| [`__init__(self, elements)`](/slides/python-net/fa/aspose.slides.mathtext/matharray/__init__/#iterableimathelement) |  |

## ویژگی‌ها

| ویژگی | توضیح |
| :- | :- |
| [`arguments`](/slides/python-net/fa/aspose.slides.mathtext/matharray/arguments/) | مجموعه‌ای از موارد آرایه |
| [`base_justification`](/slides/python-net/fa/aspose.slides.mathtext/matharray/base_justification/) | ترازبندی آرایه نسبت به متن اطراف را مشخص می‌کند<br/>            متن خارج از آرایه می‌تواند با پایین، بالای یا مرکز شیء آرایه هم‌راستا شود.<br/>            مقدار پیش‌فرض: Center |
| [`maximum_distribution`](/slides/python-net/fa/aspose.slides.mathtext/matharray/maximum_distribution/) | پراکندگی حداکثر<br/>            وقتی مقدار true باشد، آرایه تا حداکثر عرض عنصر حاوی (صفحه، ستون، سلول و غیره) فاصله می‌گیرد. |
| [`object_distribution`](/slides/python-net/fa/aspose.slides.mathtext/matharray/object_distribution/) | پراکندگی شیء<br/>            وقتی مقدار true باشد، محتویات آرایه تا حداکثر عرض شیء آرایه فاصله گرفته می‌شود. |
| [`row_spacing_rule`](/slides/python-net/fa/aspose.slides.mathtext/matharray/row_spacing_rule/) | نوع فاصله عمودی بین عناصر آرایه<br/>            پیش‌فرض: SingleLineGap |
| [`row_spacing`](/slides/python-net/fa/aspose.slides.mathtext/matharray/row_spacing/) | فاصله بین سطرهای یک آرایه<br/>            فقط وقتی RowSpacingRule برابر 3 Exactly باشد استفاده می‌شود که در این حالت واحد اندازه‌گیری points است <br/>            یا Multiple که در این حالت واحد اندازه‌گیری half-lines است.<br/>            پیش‌فرض: 0 |

## متدها

| متد | توضیح |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/fa/aspose.slides.mathtext/matharray/join/#imathelement) | یک عنصر ریاضی را به هم می‌پیوندد و یک بلوک ریاضی تشکیل می‌دهد |
| [`join(self, math_text)`](/slides/python-net/fa/aspose.slides.mathtext/matharray/join/#str) | یک متن ریاضی را به هم می‌پیوندد و یک بلوک ریاضی تشکیل می‌دهد |
| [`divide(self, denominator)`](/slides/python-net/fa/aspose.slides.mathtext/matharray/divide/#imathelement) | کسر با این صورت‌عدد و مخرج مشخص‌شده ایجاد می‌کند |
| [`divide(self, denominator)`](/slides/python-net/fa/aspose.slides.mathtext/matharray/divide/#str) | کسر با این صورت‌عدد و مخرج مشخص‌شده ایجاد می‌کند |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/fa/aspose.slides.mathtext/matharray/divide/#imathelement-mathfractiontypes) | کسر از نوع مشخص‌شده را با این صورت‌عدد و مخرج مشخص ایجاد می‌کند |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/fa/aspose.slides.mathtext/matharray/divide/#str-mathfractiontypes) | کسر از نوع مشخص‌شده را با این صورت‌عدد و مخرج مشخص ایجاد می‌کند |
| [`enclose(self)`](/slides/python-net/fa/aspose.slides.mathtext/matharray/enclose/#) | یک عنصر ریاضی را در پرانتز می‌گیرد |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/fa/aspose.slides.mathtext/matharray/enclose/#char-char) | یک عنصر ریاضی را در کاراکترهای مشخص‌شده مانند پرانتز یا سایر کاراکترها به‌عنوان قاب می‌گیرد |
| [`function(self, function_argument)`](/slides/python-net/fa/aspose.slides.mathtext/matharray/function/#imathelement) | یک تابع از یک آرگومان می‌گیرد که از این نمونه به عنوان نام تابع استفاده می‌کند |
| [`function(self, function_argument)`](/slides/python-net/fa/aspose.slides.mathtext/matharray/function/#str) | یک تابع از یک آرگومان می‌گیرد که از این نمونه به عنوان نام تابع استفاده می‌کند |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/fa/aspose.slides.mathtext/matharray/as_argument_of_function/#imathelement) | تابعی مشخص را می‌گیرد که این نمونه به عنوان آرگومان استفاده می‌شود |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/fa/aspose.slides.mathtext/matharray/as_argument_of_function/#str) | تابعی مشخص را می‌گیرد که این نمونه به عنوان آرگومان استفاده می‌شود |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/fa/aspose.slides.mathtext/matharray/as_argument_of_function/#mathfunctionsofoneargument) | تابعی مشخص را می‌گیرد که این نمونه به عنوان آرگومان استفاده می‌شود |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/fa/aspose.slides.mathtext/matharray/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | تابعی مشخص را می‌گیرد که این نمونه به عنوان آرگومان و یک آرگومان اضافهٔ مشخص استفاده می‌شود |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/fa/aspose.slides.mathtext/matharray/as_argument_of_function/#mathfunctionsoftwoarguments-str) | تابعی مشخص را می‌گیرد که این نمونه به عنوان آرگومان و یک آرگومان اضافهٔ مشخص استفاده می‌شود |
| [`set_subscript(self, subscript)`](/slides/python-net/fa/aspose.slides.mathtext/matharray/set_subscript/#imathelement) | زیرنویس ایجاد می‌کند |
| [`set_subscript(self, subscript)`](/slides/python-net/fa/aspose.slides.mathtext/matharray/set_subscript/#str) | زیرنویس ایجاد می‌کند |
| [`set_superscript(self, superscript)`](/slides/python-net/fa/aspose.slides.mathtext/matharray/set_superscript/#imathelement) | بالانویس ایجاد می‌کند |
| [`set_superscript(self, superscript)`](/slides/python-net/fa/aspose.slides.mathtext/matharray/set_superscript/#str) | بالانویس ایجاد می‌کند |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/fa/aspose.slides.mathtext/matharray/set_sub_superscript_on_the_right/#imathelement-imathelement) | زیرنویس و بالانویس را در سمت راست ایجاد می‌کند |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/fa/aspose.slides.mathtext/matharray/set_sub_superscript_on_the_right/#str-str) | زیرنویس و بالانویس را در سمت راست ایجاد می‌کند |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/fa/aspose.slides.mathtext/matharray/set_sub_superscript_on_the_left/#imathelement-imathelement) | زیرنویس و بالانویس را در سمت چپ ایجاد می‌کند |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/fa/aspose.slides.mathtext/matharray/set_sub_superscript_on_the_left/#str-str) | زیرنویس و بالانویس را در سمت چپ ایجاد می‌کند |
| [`radical(self, degree)`](/slides/python-net/fa/aspose.slides.mathtext/matharray/radical/#imathelement) | ریشهٔ ریاضی درجهٔ داده‌شده را از آرگومان مشخص‌شده تعیین می‌کند. |
| [`radical(self, degree)`](/slides/python-net/fa/aspose.slides.mathtext/matharray/radical/#str) | ریشهٔ ریاضی درجهٔ داده‌شده را از آرگومان مشخص‌شده تعیین می‌کند. |
| [`set_upper_limit(self, limit)`](/slides/python-net/fa/aspose.slides.mathtext/matharray/set_upper_limit/#imathelement) | حد بالا را می‌گیرد |
| [`set_upper_limit(self, limit)`](/slides/python-net/fa/aspose.slides.mathtext/matharray/set_upper_limit/#str) | حد بالا را می‌گیرد |
| [`set_lower_limit(self, limit)`](/slides/python-net/fa/aspose.slides.mathtext/matharray/set_lower_limit/#imathelement) | حد پایین را می‌گیرد |
| [`set_lower_limit(self, limit)`](/slides/python-net/fa/aspose.slides.mathtext/matharray/set_lower_limit/#str) | حد پایین را می‌گیرد |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/fa/aspose.slides.mathtext/matharray/nary/#mathnaryoperatortypes-imathelement-imathelement) | یک عملگر N-ary ایجاد می‌کند |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/fa/aspose.slides.mathtext/matharray/nary/#mathnaryoperatortypes-str-str) | یک عملگر N-ary ایجاد می‌کند |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/fa/aspose.slides.mathtext/matharray/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | انتگرال را می‌گیرد |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/fa/aspose.slides.mathtext/matharray/integral/#mathintegraltypes-imathelement-imathelement) | انتگرال را می‌گیرد |
| [`integral(self, integral_type)`](/slides/python-net/fa/aspose.slides.mathtext/matharray/integral/#mathintegraltypes) | انتگرال بدون حدود را می‌گیرد |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/fa/aspose.slides.mathtext/matharray/integral/#mathintegraltypes-str-str-mathlimitlocations) | انتگرال را می‌گیرد |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/fa/aspose.slides.mathtext/matharray/integral/#mathintegraltypes-str-str) | انتگرال را می‌گیرد |
| [`group(self)`](/slides/python-net/fa/aspose.slides.mathtext/matharray/group/#) | این عنصر را با استفاده از کروشهٔ پایینی در یک گروه قرار می‌دهد |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/fa/aspose.slides.mathtext/matharray/group/#char-mathtopbotpositions-mathtopbotpositions) | این عنصر را با استفاده از یک کاراکتر گروه‌بندی مانند کروشهٔ پایین یا کاراکتر دیگر در یک گروه قرار می‌دهد |
| [`to_border_box(self)`](/slides/python-net/fa/aspose.slides.mathtext/matharray/to_border_box/#) | این عنصر را در یک جعبهٔ مرزی قرار می‌دهد |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/fa/aspose.slides.mathtext/matharray/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | این عنصر را در یک جعبهٔ مرزی قرار می‌دهد |
| [`to_math_array(self)`](/slides/python-net/fa/aspose.slides.mathtext/matharray/to_math_array/#) | در یک آرایهٔ عمودی قرار می‌دهد |
| [`accent(self, accent_character)`](/slides/python-net/fa/aspose.slides.mathtext/matharray/accent/#char) | نشان تأکید می‌گذارد (کاراکتری بر بالای این عنصر) |
| [`overbar(self)`](/slides/python-net/fa/aspose.slides.mathtext/matharray/overbar/#) | یک خط در بالای این عنصر تنظیم می‌کند |
| [`underbar(self)`](/slides/python-net/fa/aspose.slides.mathtext/matharray/underbar/#) | یک خط در پایین این عنصر تنظیم می‌کند |
| [`to_box(self)`](/slides/python-net/fa/aspose.slides.mathtext/matharray/to_box/#) | این عنصر را در یک جعبه غیر‌قابل مشاهده (گروه‌بندی منطقی) قرار می‌دهد <br/>            که برای گروه‌بندی اجزای یک معادله یا نمونهٔ دیگر متن ریاضی استفاده می‌شود.<br/>            یک شیء جعبه‌ای می‌تواند (به عنوان مثال) به‌عنوان شبیه‌ساز عملگر با یا بدون نقطهٔ تراز عمل کند، <br/>            به‌عنوان نقطهٔ شکست خط عمل کند، یا به‌گونه‌ای گروه‌بندی شود که اجازهٔ شکست خط درون آن داده نشود. |
| [`get_children(self)`](/slides/python-net/fa/aspose.slides.mathtext/matharray/get_children/#) | دریافت عناصر فرزند |


### موارد مرتبط
* کلاس [`MathArray`](/slides/python-net/fa/aspose.slides.mathtext/matharray)
* کلاس [`MathElementBase`](/slides/python-net/fa/aspose.slides.mathtext/mathelementbase)
* ماژول [`aspose.slides.mathtext`](/slides/python-net/fa/aspose.slides.mathtext)
* کتابخانه [`Aspose.Slides`](/slides/python-net)