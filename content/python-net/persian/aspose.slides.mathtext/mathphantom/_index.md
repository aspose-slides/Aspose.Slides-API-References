---
title: MathPhantom class
second_title: مرجع API Aspose.Slides برای Python از طریق .NET
description: 
type: docs
url: /fa/aspose.slides.mathtext/mathphantom/
---
## کلاس MathPhantom

یک شیء ریاضی فانتوم (<m:phant>) را نمایندگی می‌کند که چیدمان عنصر فرزندش را بدون لزوماً نمایش دادن آن تحت تأثیر قرار می‌دهد. فانتوم می‌تواند عبارت پایه خود را پنهان کند در حالی که عرض، ارتفاع یا عمق آن را برای تراز فرمول‌ها یا اختصاص فضای ذخیره‌شده حفظ می‌کند. ویژگی‌های دید و رفتار هندسی توسط خصوصیتی مانند Show، ZeroWid، ZeroAsc، ZeroDesc و Transp کنترل می‌شوند.

**وراثت:**[`MathPhantom`](/slides/python-net/fa/aspose.slides.mathtext/mathphantom) → [`MathElementBase`](/slides/python-net/fa/aspose.slides.mathtext/mathelementbase)

نوع MathPhantom اعضای زیر را فراهم می‌کند:

## سازنده‌ها

| سازنده | توضیح |
| :- | :- |
| [`__init__(self, element)`](/slides/python-net/fa/aspose.slides.mathtext/mathphantom/__init__/#imathelement) | یک نمونه جدید از کلاس [`MathPhantom`](/slides/python-net/fa/aspose.slides.mathtext/mathphantom) را مقداردهی اولیه می‌کند <br/>            با استفاده از عنصر ریاضی پایه مشخص شده. |

## ویژگی‌ها

| ویژگی | توضیح |
| :- | :- |
| [`base`](/slides/python-net/fa/aspose.slides.mathtext/mathphantom/base/) | آرگومان پایه |
| [`show`](/slides/python-net/fa/aspose.slides.mathtext/mathphantom/show/) | یک مقدار که نشان می‌دهد آیا عنصر پایه نمایش داده می‌شود را دریافت یا تنظیم می‌کند. |
| [`zero_width`](/slides/python-net/fa/aspose.slides.mathtext/mathphantom/zero_width/) | یک مقدار که نشان می‌دهد آیا عرض عنصر پایه <br/>            باید به‌عنوان صفر در نظر گرفته شود را دریافت یا تنظیم می‌کند. |
| [`zero_asc`](/slides/python-net/fa/aspose.slides.mathtext/mathphantom/zero_asc/) | یک مقدار که نشان می‌دهد آیا صعود (ارتفاع بالای خط پایه) <br/>            عنصر پایه باید به‌عنوان صفر در نظر گرفته شود را دریافت یا تنظیم می‌کند. |
| [`zero_desc`](/slides/python-net/fa/aspose.slides.mathtext/mathphantom/zero_desc/) | یک مقدار که نشان می‌دهد آیا نزول (عمق زیر خط پایه)<br/>            عنصر پایه باید به‌عنوان صفر در نظر گرفته شود را دریافت یا تنظیم می‌کند. |
| [`transp`](/slides/python-net/fa/aspose.slides.mathtext/mathphantom/transp/) | یک مقدار که نشان می‌دهد آیا فانتوم برای قوانین فاصله‌گذاری بر پایه کلاس <br/>            شفاف است را دریافت یا تنظیم می‌کند. |

## متدها

| متد | توضیح |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/fa/aspose.slides.mathtext/mathphantom/join/#imathelement) | یک عنصر ریاضی را به‌هم می‌پیوندد و یک بلوک ریاضی تشکیل می‌دهد |
| [`join(self, math_text)`](/slides/python-net/fa/aspose.slides.mathtext/mathphantom/join/#str) | متن ریاضی را به‌هم می‌پیوندد و یک بلوک ریاضی تشکیل می‌دهد |
| [`divide(self, denominator)`](/slides/python-net/fa/aspose.slides.mathtext/mathphantom/divide/#imathelement) | یک کسر را با این صورت و مخرج مشخص شده ایجاد می‌کند |
| [`divide(self, denominator)`](/slides/python-net/fa/aspose.slides.mathtext/mathphantom/divide/#str) | یک کسر را با این صورت و مخرج مشخص شده ایجاد می‌کند |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/fa/aspose.slides.mathtext/mathphantom/divide/#imathelement-mathfractiontypes) | کسر از نوع مشخص شده را با این صورت و مخرج مشخص ایجاد می‌کند |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/fa/aspose.slides.mathtext/mathphantom/divide/#str-mathfractiontypes) | کسر از نوع مشخص شده را با این صورت و مخرج مشخص ایجاد می‌کند |
| [`enclose(self)`](/slides/python-net/fa/aspose.slides.mathtext/mathphantom/enclose/#) | یک عنصر ریاضی را در پرانتز می‌گیرد |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/fa/aspose.slides.mathtext/mathphantom/enclose/#char-char) | یک عنصر ریاضی را در کاراکترهای مشخص شده مانند پرانتز یا کاراکترهای دیگر به‌عنوان قاب می‌گیرد |
| [`function(self, function_argument)`](/slides/python-net/fa/aspose.slides.mathtext/mathphantom/function/#imathelement) | یک تابع از یک آرگومان را می‌گیرد به‌طوری که این نمونه به‌عنوان نام تابع استفاده می‌شود |
| [`function(self, function_argument)`](/slides/python-net/fa/aspose.slides.mathtext/mathphantom/function/#str) | یک تابع از یک آرگومان را می‌گیرد به‌طوری که این نمونه به‌عنوان نام تابع استفاده می‌شود |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/fa/aspose.slides.mathtext/mathphantom/as_argument_of_function/#imathelement) | تابع مشخص شده‌ای را می‌گیرد که این نمونه به‌عنوان آرگومان استفاده می‌شود |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/fa/aspose.slides.mathtext/mathphantom/as_argument_of_function/#str) | تابع مشخص شده‌ای را می‌گیرد که این نمونه به‌عنوان آرگومان استفاده می‌شود |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/fa/aspose.slides.mathtext/mathphantom/as_argument_of_function/#mathfunctionsofoneargument) | تابع مشخص شده‌ای را می‌گیرد که این نمونه به‌عنوان آرگومان استفاده می‌شود |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/fa/aspose.slides.mathtext/mathphantom/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | تابع مشخص شده‌ای را می‌گیرد که این نمونه به‌عنوان آرگومان و یک آرگومان اضافی مشخص استفاده می‌شود |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/fa/aspose.slides.mathtext/mathphantom/as_argument_of_function/#mathfunctionsoftwoarguments-str) | تابع مشخص شده‌ای را می‌گیرد که این نمونه به‌عنوان آرگومان و یک آرگومان اضافی مشخص استفاده می‌شود |
| [`set_subscript(self, subscript)`](/slides/python-net/fa/aspose.slides.mathtext/mathphantom/set_subscript/#imathelement) | زیرنویس ایجاد می‌کند |
| [`set_subscript(self, subscript)`](/slides/python-net/fa/aspose.slides.mathtext/mathphantom/set_subscript/#str) | زیرنویس ایجاد می‌کند |
| [`set_superscript(self, superscript)`](/slides/python-net/fa/aspose.slides.mathtext/mathphantom/set_superscript/#imathelement) | بالنویس ایجاد می‌کند |
| [`set_superscript(self, superscript)`](/slides/python-net/fa/aspose.slides.mathtext/mathphantom/set_superscript/#str) | بالنویس ایجاد می‌کند |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/fa/aspose.slides.mathtext/mathphantom/set_sub_superscript_on_the_right/#imathelement-imathelement) | زیرنویس و بالنویس را در سمت راست ایجاد می‌کند |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/fa/aspose.slides.mathtext/mathphantom/set_sub_superscript_on_the_right/#str-str) | زیرنویس و بالنویس را در سمت راست ایجاد می‌کند |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/fa/aspose.slides.mathtext/mathphantom/set_sub_superscript_on_the_left/#imathelement-imathelement) | زیرنویس و بالنویس را در سمت چپ ایجاد می‌کند |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/fa/aspose.slides.mathtext/mathphantom/set_sub_superscript_on_the_left/#str-str) | زیرنویس و بالنویس را در سمت چپ ایجاد می‌کند |
| [`radical(self, degree)`](/slides/python-net/fa/aspose.slides.mathtext/mathphantom/radical/#imathelement) | ریشه ریاضی با درجه داده‌شده از آرگومان مشخص‌شده را تعیین می‌کند. |
| [`radical(self, degree)`](/slides/python-net/fa/aspose.slides.mathtext/mathphantom/radical/#str) | ریشه ریاضی با درجه داده‌شده از آرگومان مشخص‌شده را تعیین می‌کند. |
| [`set_upper_limit(self, limit)`](/slides/python-net/fa/aspose.slides.mathtext/mathphantom/set_upper_limit/#imathelement) | حد بالایی را می‌گیرد |
| [`set_upper_limit(self, limit)`](/slides/python-net/fa/aspose.slides.mathtext/mathphantom/set_upper_limit/#str) | حد بالایی را می‌گیرد |
| [`set_lower_limit(self, limit)`](/slides/python-net/fa/aspose.slides.mathtext/mathphantom/set_lower_limit/#imathelement) | حد پایین را می‌گیرد |
| [`set_lower_limit(self, limit)`](/slides/python-net/fa/aspose.slides.mathtext/mathphantom/set_lower_limit/#str) | حد پایین را می‌گیرد |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/fa/aspose.slides.mathtext/mathphantom/nary/#mathnaryoperatortypes-imathelement-imathelement) | یک اپراتور N-آری ایجاد می‌کند |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/fa/aspose.slides.mathtext/mathphantom/nary/#mathnaryoperatortypes-str-str) | یک اپراتور N-آری ایجاد می‌کند |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/fa/aspose.slides.mathtext/mathphantom/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | انتگرال را می‌گیرد |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/fa/aspose.slides.mathtext/mathphantom/integral/#mathintegraltypes-imathelement-imathelement) | انتگرال را می‌گیرد |
| [`integral(self, integral_type)`](/slides/python-net/fa/aspose.slides.mathtext/mathphantom/integral/#mathintegraltypes) | انتگرال را بدون حدها می‌گیرد |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/fa/aspose.slides.mathtext/mathphantom/integral/#mathintegraltypes-str-str-mathlimitlocations) | انتگرال را می‌گیرد |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/fa/aspose.slides.mathtext/mathphantom/integral/#mathintegraltypes-str-str) | انتگرال را می‌گیرد |
| [`group(self)`](/slides/python-net/fa/aspose.slides.mathtext/mathphantom/group/#) | این عنصر را در یک گروه با استفاده از یک پرانتز منحنی پایین قرار می‌دهد |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/fa/aspose.slides.mathtext/mathphantom/group/#char-mathtopbotpositions-mathtopbotpositions) | این عنصر را در یک گروه با استفاده از یک کاراکتر گروه‌بندی مانند پرانتز منحنی پایین یا دیگری قرار می‌دهد |
| [`to_border_box(self)`](/slides/python-net/fa/aspose.slides.mathtext/mathphantom/to_border_box/#) | این عنصر را در یک جعبه حاشیه‌ای قرار می‌دهد |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/fa/aspose.slides.mathtext/mathphantom/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | این عنصر را در یک جعبه حاشیه‌ای قرار می‌دهد |
| [`to_math_array(self)`](/slides/python-net/fa/aspose.slides.mathtext/mathphantom/to_math_array/#) | در یک آرایه عمودی قرار می‌دهد |
| [`accent(self, accent_character)`](/slides/python-net/fa/aspose.slides.mathtext/mathphantom/accent/#char) | یک علامت accent (یک کاراکتر بالای این عنصر) تنظیم می‌کند |
| [`overbar(self)`](/slides/python-net/fa/aspose.slides.mathtext/mathphantom/overbar/#) | یک خط بالا روی این عنصر تنظیم می‌کند |
| [`underbar(self)`](/slides/python-net/fa/aspose.slides.mathtext/mathphantom/underbar/#) | یک خط پایین روی این عنصر تنظیم می‌کند |
| [`to_box(self)`](/slides/python-net/fa/aspose.slides.mathtext/mathphantom/to_box/#) | این عنصر را در یک جعبه غیر بصری (گروه‌بندی منطقی) قرار می‌دهد <br/>            که برای گروه‌بندی اجزای یک معادله یا نمونه دیگری از متن ریاضی استفاده می‌شود.<br/>            یک شی جعبه‌دار می‌تواند (به عنوان مثال) به‌عنوان یک شبیه‌ساز اپراتور با یا بدون نقطه تراز عمل کند، <br/>            به‌عنوان نقطه شکست خط عمل کند، یا به‌گونه‌ای گروه‌بندی شود که اجازه خطوط شکسته درون آن نشود. |
| [`get_children(self)`](/slides/python-net/fa/aspose.slides.mathtext/mathphantom/get_children/#) | دریافت عناصر فرزند |

### موارد مرتبط
* کلاس [`MathElementBase`](/slides/python-net/fa/aspose.slides.mathtext/mathelementbase)
* کلاس [`MathPhantom`](/slides/python-net/fa/aspose.slides.mathtext/mathphantom)
* ماژول [`aspose.slides.mathtext`](/slides/python-net/fa/aspose.slides.mathtext)
* کتابخانه [`Aspose.Slides`](/slides/python-net)