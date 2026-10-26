---
title: MathBlock class
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides.mathtext/mathblock/
---
## MathBlock کلاس

یک نمونه از متن ریاضی را که در داخل یک MathParagraph قرار دارد و در خط خود جدا شروع می‌شود مشخص می‌کند.  
تمام نواحی ریاضی، از جمله معادله‌ها، عبارات، آرایه‌های معادله‌ها یا عبارات و فرمول‌ها توسط بلاک ریاضی نشان داده می‌شوند.

**ارث‌بری:**[`MathBlock`](/slides/python-net/fa/aspose.slides.mathtext/mathblock) → [`MathElementBase`](/slides/python-net/fa/aspose.slides.mathtext/mathelementbase)

نوع MathBlock اعضای زیر را در دسترس می‌گذارد:

## سازنده‌ها

| سازنده | توضیح |
| :- | :- |
| [`__init__(self)`](/slides/python-net/fa/aspose.slides.mathtext/mathblock/__init__/#) | یک نمونه جدید از کلاس MathBlock را مقداردهی اولیه می‌کند. |
| [`__init__(self, math_element)`](/slides/python-net/fa/aspose.slides.mathtext/mathblock/__init__/#imathelement) | یک بلاک ریاضی جدید ایجاد می‌کند و عنصر مشخص شده را در آن قرار می‌دهد |
| [`__init__(self, math_elements)`](/slides/python-net/fa/aspose.slides.mathtext/mathblock/__init__/#iterableimathelement) |  |

## ویژگی‌ها

| ویژگی | توضیح |
| :- | :- |
| [`count`](/slides/python-net/fa/aspose.slides.mathtext/mathblock/count/) | تعداد عناصر ریاضی فرزند واقعاً موجود در مجموعه را بر می‌گرداند.<br/>            فقط-خواندنی **int**. |
| [`is_read_only`](/slides/python-net/fa/aspose.slides.mathtext/mathblock/is_read_only/) | false را برمی‌گرداند زیرا مجموعه عناصر فرزند قابل تغییر است. |

دریافت یا تنظیم IMathElement در ایندکس مشخص شده.

## ایندکس‌گر

| نام | توضیح |
| :- | :- |
| [`[index]`](/slides/python-net/fa/aspose.slides.mathtext/mathblock/__getitem__/) | اندیس صفر-مبنای این آیتم |

## متدها

| متد | توضیح |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/fa/aspose.slides.mathtext/mathblock/join/#imathelement) | یک عنصر ریاضی را با این بلاک ریاضی پیوند می‌دهد |
| [`join(self, math_text)`](/slides/python-net/fa/aspose.slides.mathtext/mathblock/join/#str) | یک متن ریاضی را با این بلاک ریاضی پیوند می‌دهد |
| [`divide(self, denominator)`](/slides/python-net/fa/aspose.slides.mathtext/mathblock/divide/#imathelement) | یک کسر با صورت این و مخرج مشخص شده ایجاد می‌کند |
| [`divide(self, denominator)`](/slides/python-net/fa/aspose.slides.mathtext/mathblock/divide/#str) | یک کسر با صورت این و مخرج مشخص شده ایجاد می‌کند |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/fa/aspose.slides.mathtext/mathblock/divide/#imathelement-mathfractiontypes) | یک کسر از نوع مشخص شده با صورت این و مخرج مشخص شده ایجاد می‌کند |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/fa/aspose.slides.mathtext/mathblock/divide/#str-mathfractiontypes) | یک کسر از نوع مشخص شده با صورت این و مخرج مشخص شده ایجاد می‌کند |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/fa/aspose.slides.mathtext/mathblock/enclose/#char-char) | عناصر فرزند این بلاک را در نویسه‌های مشخص شده مانند پرانتز یا سایر نویسه‌ها به عنوان قاب می‌گیرد |
| [`enclose(self, beginning_character, ending_character, separator_character)`](/slides/python-net/fa/aspose.slides.mathtext/mathblock/enclose/#char-char-char) | عناصر فرزند این بلاک را در نویسه‌های مشخص شده مانند پرانتز یا سایر به‌عنوان قاب می‌گیرد<br/>            و با یک نویسه جداکننده محدود می‌کند |
| [`enclose(self)`](/slides/python-net/fa/aspose.slides.mathtext/mathblock/enclose/#) | یک عنصر ریاضی را در پرانتز می‌گیرد |
| [`function(self, function_argument)`](/slides/python-net/fa/aspose.slides.mathtext/mathblock/function/#imathelement) | یک تابع از یک آرگومان را می‌گیرد که از این نمونه به‌عنوان نام تابع استفاده می‌کند |
| [`function(self, function_argument)`](/slides/python-net/fa/aspose.slides.mathtext/mathblock/function/#str) | یک تابع از یک آرگومان را می‌گیرد که از این نمونه به‌عنوان نام تابع استفاده می‌کند |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/fa/aspose.slides.mathtext/mathblock/as_argument_of_function/#imathelement) | یک تابع مشخص را می‌گیرد که این نمونه به‌عنوان آرگومان استفاده می‌شود |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/fa/aspose.slides.mathtext/mathblock/as_argument_of_function/#str) | یک تابع مشخص را می‌گیرد که این نمونه به‌عنوان آرگومان استفاده می‌شود |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/fa/aspose.slides.mathtext/mathblock/as_argument_of_function/#mathfunctionsofoneargument) | یک تابع مشخص را می‌گیرد که این نمونه به‌عنوان آرگومان استفاده می‌شود |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/fa/aspose.slides.mathtext/mathblock/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | یک تابع مشخص را می‌گیرد که این نمونه به‌عنوان آرگومان و یک آرگومان اضافه مشخص استفاده می‌شود |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/fa/aspose.slides.mathtext/mathblock/as_argument_of_function/#mathfunctionsoftwoarguments-str) | یک تابع مشخص را می‌گیرد که این نمونه به‌عنوان آرگومان و یک آرگومان اضافه مشخص استفاده می‌شود |
| [`set_subscript(self, subscript)`](/slides/python-net/fa/aspose.slides.mathtext/mathblock/set_subscript/#imathelement) | زیرنویس ایجاد می‌کند |
| [`set_subscript(self, subscript)`](/slides/python-net/fa/aspose.slides.mathtext/mathblock/set_subscript/#str) | زیرنویس ایجاد می‌کند |
| [`set_superscript(self, superscript)`](/slides/python-net/fa/aspose.slides.mathtext/mathblock/set_superscript/#imathelement) | بالانویس ایجاد می‌کند |
| [`set_superscript(self, superscript)`](/slides/python-net/fa/aspose.slides.mathtext/mathblock/set_superscript/#str) | بالانویس ایجاد می‌کند |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/fa/aspose.slides.mathtext/mathblock/set_sub_superscript_on_the_right/#imathelement-imathelement) | زیرنویس و بالانویس را در سمت راست ایجاد می‌کند |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/fa/aspose.slides.mathtext/mathblock/set_sub_superscript_on_the_right/#str-str) | زیرنویس و بالانویس را در سمت راست ایجاد می‌کند |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/fa/aspose.slides.mathtext/mathblock/set_sub_superscript_on_the_left/#imathelement-imathelement) | زیرنویس و بالانویس را در سمت چپ ایجاد می‌کند |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/fa/aspose.slides.mathtext/mathblock/set_sub_superscript_on_the_left/#str-str) | زیرنویس و بالانویس را در سمت چپ ایجاد می‌کند |
| [`radical(self, degree)`](/slides/python-net/fa/aspose.slides.mathtext/mathblock/radical/#imathelement) | ریشه ریاضی از درجه داده‌شده را از آرگومان مشخص شده تعیین می‌کند. |
| [`radical(self, degree)`](/slides/python-net/fa/aspose.slides.mathtext/mathblock/radical/#str) | ریشه ریاضی از درجه داده‌شده را از آرگومان مشخص شده تعیین می‌کند. |
| [`set_upper_limit(self, limit)`](/slides/python-net/fa/aspose.slides.mathtext/mathblock/set_upper_limit/#imathelement) | حد بالایی را می‌گیرد |
| [`set_upper_limit(self, limit)`](/slides/python-net/fa/aspose.slides.mathtext/mathblock/set_upper_limit/#str) | حد بالایی را می‌گیرد |
| [`set_lower_limit(self, limit)`](/slides/python-net/fa/aspose.slides.mathtext/mathblock/set_lower_limit/#imathelement) | حد پایین را می‌گیرد |
| [`set_lower_limit(self, limit)`](/slides/python-net/fa/aspose.slides.mathtext/mathblock/set_lower_limit/#str) | حد پایین را می‌گیرد |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/fa/aspose.slides.mathtext/mathblock/nary/#mathnaryoperatortypes-imathelement-imathelement) | یک عملگر N-آرگی ایجاد می‌کند |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/fa/aspose.slides.mathtext/mathblock/nary/#mathnaryoperatortypes-str-str) | یک عملگر N-آرگی ایجاد می‌کند |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/fa/aspose.slides.mathtext/mathblock/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | انتگرال را می‌گیرد |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/fa/aspose.slides.mathtext/mathblock/integral/#mathintegraltypes-imathelement-imathelement) | انتگرال را می‌گیرد |
| [`integral(self, integral_type)`](/slides/python-net/fa/aspose.slides.mathtext/mathblock/integral/#mathintegraltypes) | انتگرال را بدون حدها می‌گیرد |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/fa/aspose.slides.mathtext/mathblock/integral/#mathintegraltypes-str-str-mathlimitlocations) | انتگرال را می‌گیرد |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/fa/aspose.slides.mathtext/mathblock/integral/#mathintegraltypes-str-str) | انتگرال را می‌گیرد |
| [`group(self)`](/slides/python-net/fa/aspose.slides.mathtext/mathblock/group/#) | این عنصر را در یک گروه با استفاده از کروشهٔ پایین قرار می‌دهد |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/fa/aspose.slides.mathtext/mathblock/group/#char-mathtopbotpositions-mathtopbotpositions) | این عنصر را در یک گروه با استفاده از یک نویسهٔ گروه‌بندی مانند کروشهٔ پایین یا دیگر نویسه‌ها قرار می‌دهد |
| [`to_border_box(self)`](/slides/python-net/fa/aspose.slides.mathtext/mathblock/to_border_box/#) | این عنصر را در یک جعبه حاشیه‌ای قرار می‌دهد |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/fa/aspose.slides.mathtext/mathblock/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | این عنصر را در یک جعبه حاشیه‌ای قرار می‌دهد |
| [`to_math_array(self)`](/slides/python-net/fa/aspose.slides.mathtext/mathblock/to_math_array/#) | عناصر فرزند را در یک آرایهٔ عمودی قرار می‌دهد |
| [`accent(self, accent_character)`](/slides/python-net/fa/aspose.slides.mathtext/mathblock/accent/#char) | یک علامت لحن (نویسه‌ای در بالای این عنصر) تنظیم می‌کند |
| [`overbar(self)`](/slides/python-net/fa/aspose.slides.mathtext/mathblock/overbar/#) | یک خط بر روی بالای این عنصر تنظیم می‌کند |
| [`underbar(self)`](/slides/python-net/fa/aspose.slides.mathtext/mathblock/underbar/#) | یک خط بر روی پایین این عنصر تنظیم می‌کند |
| [`to_box(self)`](/slides/python-net/fa/aspose.slides.mathtext/mathblock/to_box/#) | این عنصر را در یک جعبه غیر‌مظهر (گروه‌بندی منطقی) قرار می‌دهد <br/>            که برای گروه‌بندی اجزای یک معادله یا نمونهٔ دیگر متن ریاضی استفاده می‌شود.<br/>            یک شیء جعبه‌دار می‌تواند (به عنوان مثال) به‌عنوان شبیه‌ساز عملگر با یا بدون نقطهٔ تراز، <br/>            به‌عنوان نقطهٔ شکست خط، یا به‌صورت گروه‌بندی باشد به-طوری‌که شکست خط داخل آن مجاز نباشد. |
| [`get_children(self)`](/slides/python-net/fa/aspose.slides.mathtext/mathblock/get_children/#) | دریافت عناصر فرزند |
| [`add(self, item)`](/slides/python-net/fa/aspose.slides.mathtext/mathblock/add/#imathelement) | یک عنصر ریاضی را به انتهای مجموعه اضافه می‌کند. |
| [`clear(self)`](/slides/python-net/fa/aspose.slides.mathtext/mathblock/clear/#) | تمام عناصر را از مجموعه حذف می‌کند. |
| [`contains(self, item)`](/slides/python-net/fa/aspose.slides.mathtext/mathblock/contains/#imathelement) | تعیین می‌کند آیا مجموعه شامل مقدار خاصی است یا نه. |
| [`copy_to(self, array, array_index)`](/slides/python-net/fa/aspose.slides.mathtext/mathblock/copy_to/#listimathelement-int) | به آرایهٔ مشخص‌شده کپی می‌کند. |
| [`remove(self, item)`](/slides/python-net/fa/aspose.slides.mathtext/mathblock/remove/#imathelement) | اولین رخداد یک شیء خاص را از مجموعه حذف می‌کند. |
| [`index_of(self, item)`](/slides/python-net/fa/aspose.slides.mathtext/mathblock/index_of/#imathelement) | اندیس یک عنصر ریاضی خاص در مجموعه را تعیین می‌کند. |
| [`insert(self, index, item)`](/slides/python-net/fa/aspose.slides.mathtext/mathblock/insert/#int-imathelement) | یک MathElement را در مجموعه در ایندکس مشخص شده وارد می‌کند. |
| [`remove_at(self, index)`](/slides/python-net/fa/aspose.slides.mathtext/mathblock/remove_at/#int) | عنصر را در ایندکس مشخص‌شده از مجموعه حذف می‌کند. |
| [`join_block(self, other)`](/slides/python-net/fa/aspose.slides.mathtext/mathblock/join_block/#imathblock) | یک بلاک ریاضی دیگر را با این بلاک پیوند می‌دهد |
| [`delimit(self, separator_character)`](/slides/python-net/fa/aspose.slides.mathtext/mathblock/delimit/#char) | عناصر فرزند را با نویسهٔ جداکننده (بدون کروشه) محدود می‌کند |
| [`write_as_math_ml(self, stream)`](/slides/python-net/fa/aspose.slides.mathtext/mathblock/write_as_math_ml/#iorawiobase) | محتویات این [`MathBlock`](/slides/python-net/fa/aspose.slides.mathtext/mathblock) را به عنوان MathML ذخیره می‌کند |

### موارد مرتبط
* کلاس [`MathBlock`](/slides/python-net/fa/aspose.slides.mathtext/mathblock)
* کلاس [`MathElementBase`](/slides/python-net/fa/aspose.slides.mathtext/mathelementbase)
* ماژول [`aspose.slides.mathtext`](/slides/python-net/fa/aspose.slides.mathtext)
* کتابخانه [`Aspose.Slides`](/slides/python-net)