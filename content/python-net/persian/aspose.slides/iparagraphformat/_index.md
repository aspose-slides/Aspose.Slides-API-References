---
title: IParagraphFormat class
second_title: Aspose.Slides برای پایتون از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides/iparagraphformat/
---
## IParagraphFormat کلاس

این کلاس شامل ویژگی‌های قالب‌بندی پاراگراف است. بر خلاف [`IParagraphFormatEffectiveData`](/slides/python-net/fa/aspose.slides/iparagraphformateffectivedata)، همه ویژگی‌های این کلاس قابل نوشتن هستند.

نوع IParagraphFormat اعضای زیر را نمایش می‌دهد:

## خصوصیات

| Property | Description |
| :- | :- |
| [`bullet`](/slides/python-net/fa/aspose.slides/iparagraphformat/bullet/) | بازگرداندن قالب گلوله پاراگراف.<br/>            فقط-خواندنی [`IBulletFormat`](/slides/python-net/fa/aspose.slides/ibulletformat). |
| [`depth`](/slides/python-net/fa/aspose.slides/iparagraphformat/depth/) | بازگرداندن یا تنظیم عمق پاراگراف.<br/>            مقدار 0 به معنای مقدار تعریف‌نشده است.<br/>            خواندنی/نوشتنی **int**. |
| [`alignment`](/slides/python-net/fa/aspose.slides/iparagraphformat/alignment/) | بازگرداندن یا تنظیم ترازبندی متن در یک پاراگراف بدون وراثت.<br/>            خواندنی/نوشتنی [`TextAlignment`](/slides/python-net/fa/aspose.slides/textalignment). |
| [`space_within`](/slides/python-net/fa/aspose.slides/iparagraphformat/space_within/) | بازگرداندن یا تنظیم مقدار فاصله بین خطوط پایه در یک پاراگراف. مقدار مثبت به معنای درصد، مقدار منفی اندازه به واحد نقطه است. وراثتی اعمال نمی‌شود.<br/>            خواندنی/نوشتنی **float**. |
| [`space_before`](/slides/python-net/fa/aspose.slides/iparagraphformat/space_before/) | بازگرداندن یا تنظیم مقدار فاصله قبل از خط اول در یک پاراگراف بدون وراثت.<br/>            مقدار مثبت درصد اندازه قلم را که فضای سفید باید باشد تعیین می‌کند.<br/>            مقدار منفی اندازه فضای سفید را به واحد نقطه مشخص می‌کند.<br/>            خواندنی/نوشتنی **float**. |
| [`space_after`](/slides/python-net/fa/aspose.slides/iparagraphformat/space_after/) | بازگرداندن یا تنظیم مقدار فاصله پس از خط آخر در یک پاراگراف بدون وراثت.<br/>            مقدار مثبت درصد اندازه قلم را که فضای سفید باید باشد تعیین می‌کند.<br/>            مقدار منفی اندازه فضای سفید را به واحد نقطه مشخص می‌کند.<br/>            خواندنی/نوشتنی **float**. |
| [`east_asian_line_break`](/slides/python-net/fa/aspose.slides/iparagraphformat/east_asian_line_break/) | تعیین می‌کند که آیا شکست خط آسیای شرقی در پاراگراف استفاده شود یا نه. وراثتی اعمال نمی‌شود.<br/>            خواندنی/نوشتنی [`NullableBool`](/slides/python-net/fa/aspose.slides/nullablebool). |
| [`right_to_left`](/slides/python-net/fa/aspose.slides/iparagraphformat/right_to_left/) | تعیین می‌کند که آیا نوشتار راست به چپ در پاراگراف استفاده شود یا نه. وراثتی اعمال نمی‌شود.<br/>            خواندنی/نوشتنی [`NullableBool`](/slides/python-net/fa/aspose.slides/nullablebool). |
| [`latin_line_break`](/slides/python-net/fa/aspose.slides/iparagraphformat/latin_line_break/) | تعیین می‌کند که آیا شکست خط لاتین در پاراگراف استفاده شود یا نه. وراثتی اعمال نمی‌شود.<br/>            خواندنی/نوشتنی [`NullableBool`](/slides/python-net/fa/aspose.slides/nullablebool). |
| [`hanging_punctuation`](/slides/python-net/fa/aspose.slides/iparagraphformat/hanging_punctuation/) | تعیین می‌کند که آیا نقطه‌گذاری معلق در پاراگراف استفاده شود یا نه. وراثتی اعمال نمی‌شود.<br/>            خواندنی/نوشتنی [`NullableBool`](/slides/python-net/fa/aspose.slides/nullablebool). |
| [`margin_left`](/slides/python-net/fa/aspose.slides/iparagraphformat/margin_left/) | بازگرداندن یا تنظیم حاشیه چپ در یک پاراگراف بدون وراثت.<br/>            خواندنی/نوشتنی **float**. |
| [`margin_right`](/slides/python-net/fa/aspose.slides/iparagraphformat/margin_right/) | بازگرداندن یا تنظیم حاشیه راست در یک پاراگراف بدون وراثت.<br/>            خواندنی/نوشتنی **float**. |
| [`indent`](/slides/python-net/fa/aspose.slides/iparagraphformat/indent/) | بازگرداندن یا تنظیم تورفتگی خط اول/تورفتگی معلق پاراگراف بدون وراثت. تورفتگی معلق می‌تواند با مقادیر منفی تعریف شود.<br/>            خواندنی/نوشتنی **float**. |
| [`default_tab_size`](/slides/python-net/fa/aspose.slides/iparagraphformat/default_tab_size/) | بازگرداندن یا تنظیم اندازه پیش‌فرض تب بدون وراثت.<br/>            خواندنی/نوشتنی **float**. |
| [`tabs`](/slides/python-net/fa/aspose.slides/iparagraphformat/tabs/) | بازگرداندن تبولات یک پاراگراف. وراثتی اعمال نمی‌شود.<br/>            فقط-خواندنی [`ITabCollection`](/slides/python-net/fa/aspose.slides/itabcollection). |
| [`font_alignment`](/slides/python-net/fa/aspose.slides/iparagraphformat/font_alignment/) | بازگرداندن یا تنظیم ترازبندی قلم در یک پاراگراف بدون وراثت.<br/>            خواندنی/نوشتنی [`FontAlignment`](/slides/python-net/fa/aspose.slides/fontalignment). |
| [`default_portion_format`](/slides/python-net/fa/aspose.slides/iparagraphformat/default_portion_format/) | بازگرداندن فرمت بخش پیش‌فرض یک پاراگراف. وراثتی اعمال نمی‌شود.<br/>            فقط-خواندنی [`IPortionFormat`](/slides/python-net/fa/aspose.slides/iportionformat). |

## متدها

| Method | Description |
| :- | :- |
| [`get_effective(self)`](/slides/python-net/fa/aspose.slides/iparagraphformat/get_effective/#) | داده‌های قالب‌بندی مؤثر پاراگراف را با اعمال وراثت دریافت می‌کند. |

### توضیحات

از این کلاس برای بازگرداندن و دستکاری ویژگی‌های قالب‌بندی پاراگراف تعریف‌شده برای پاراگراف خاص استفاده می‌شود. این بدان معنی است که هنگام دریافت مقادیر، وراثتی اعمال نمی‌شود، بنابراین در اکثر موارد مقادیری دریافت می‌کنید که به معنای "تعریف‌نشده" هستند.

برای دریافت مقادیر پارامترهای قالب‌بندی مؤثر شامل وراثت، باید از متد [`IParagraphFormat.get_effective`](/slides/python-net/fa/aspose.slides/iparagraphformat/get_effective) استفاده کنید که یک نمونه [`IParagraphFormatEffectiveData`](/slides/python-net/fa/aspose.slides/iparagraphformateffectivedata) را برمی‌گرداند.

### موارد مرتبط
* کلاس [`IParagraphFormatEffectiveData`](/slides/python-net/fa/aspose.slides/iparagraphformateffectivedata)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)