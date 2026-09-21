---
title: BulletFormat class
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides/bulletformat/
---
## کلاس BulletFormat

خواص قالب‌بندی گلوله پاراگراف را نشان می‌دهد.

**ارث‌بری:**[`BulletFormat`](/slides/python-net/fa/aspose.slides/bulletformat) → [`PVIObject`](/slides/python-net/fa/aspose.slides/pviobject)

نوع BulletFormat اعضای زیر را در اختیار می‌گذارد:

## ویژگی‌ها

| ویژگی | توضیح |
| :- | :- |
| [`type`](/slides/python-net/fa/aspose.slides/bulletformat/type/) | مقدار یا تنظیم نوع گلوله یک پاراگراف بدون ارث‌بری را برمی‌گرداند.<br/>            خواندن/نوشتن [`BulletType`](/slides/python-net/fa/aspose.slides/bullettype). |
| [`char`](/slides/python-net/fa/aspose.slides/bulletformat/char/) | مقدار یا تنظیم کاراکتر گلوله یک پاراگراف بدون ارث‌بری را برمی‌گرداند.<br/>            خواندن/نوشتن **System.Char**. |
| [`font`](/slides/python-net/fa/aspose.slides/bulletformat/font/) | مقدار یا تنظیم قلم گلوله یک پاراگراف بدون ارث‌بری را برمی‌گرداند.<br/>            خواندن/نوشتن [`IFontData`](/slides/python-net/fa/aspose.slides/ifontdata). |
| [`height`](/slides/python-net/fa/aspose.slides/bulletformat/height/) | مقدار یا تنظیم ارتفاع گلوله یک پاراگراف بدون ارث‌بری را برمی‌گرداند.<br/>            مقدار float.NaN تعیین می‌کند که گلوله ارتفاع را از اولین بخش پاراگراف به ارث می‌برد.<br/>            خواندن/نوشتن **float**. |
| [`color`](/slides/python-net/fa/aspose.slides/bulletformat/color/) | قالب رنگ یک گلوله پاراگراف بدون ارث‌بری را برمی‌گرداند.<br/>            فقط-خواندنی [`IColorFormat`](/slides/python-net/fa/aspose.slides/icolorformat). |
| [`numbered_bullet_start_with`](/slides/python-net/fa/aspose.slides/bulletformat/numbered_bullet_start_with/) | مقدار یا تنظیم اولین عدد که برای گروه گلوله‌های شماره‌دار استفاده می‌شود بدون ارث‌بری را برمی‌گرداند.<br/>            خواندن/نوشتن **int**. |
| [`numbered_bullet_style`](/slides/python-net/fa/aspose.slides/bulletformat/numbered_bullet_style/) | مقدار یا تنظیم سبک یک گلوله شماره‌دار بدون ارث‌بری را برمی‌گرداند.<br/>            خواندن/نوشتن [`NumberedBulletStyle`](/slides/python-net/fa/aspose.slides/numberedbulletstyle). |
| [`is_bullet_hard_color`](/slides/python-net/fa/aspose.slides/bulletformat/is_bullet_hard_color/) | تعیین می‌کند آیا گلوله رنگ خود را دارد یا از اولین بخش پاراگراف به ارث می‌برد.<br/>            **NullableBool.True**  اگر گلوله رنگ خود را داشته باشد و **NullableBool.False**  اگر گلوله<br/>            رنگ را از اولین بخش پاراگراف به ارث ببرد.<br/>            خواندن/نوشتن [`NullableBool`](/slides/python-net/fa/aspose.slides/nullablebool). |
| [`is_bullet_hard_font`](/slides/python-net/fa/aspose.slides/bulletformat/is_bullet_hard_font/) | تعیین می‌کند آیا گلوله قلم خود را دارد یا از اولین بخش پاراگراف به ارث می‌برد.<br/>            **NullableBool.True**  اگر گلوله قلم خود را داشته باشد و **NullableBool.False**  اگر گلوله<br/>            قلم را از اولین بخش پاراگراف به ارث ببرد.<br/>            خواندن/نوشتن [`NullableBool`](/slides/python-net/fa/aspose.slides/nullablebool). |
| [`picture`](/slides/python-net/fa/aspose.slides/bulletformat/picture/) | تصویری که به عنوان گلوله در یک پاراگراف بدون ارث‌بری استفاده می‌شود را برمی‌گرداند.<br/>            فقط-خواندنی [`ISlidesPicture`](/slides/python-net/fa/aspose.slides/islidespicture). |
| [`slide`](/slides/python-net/fa/aspose.slides/bulletformat/slide/) |  |
| [`presentation`](/slides/python-net/fa/aspose.slides/bulletformat/presentation/) |  |

## متدها

| متد | توضیح |
| :- | :- |
| [`apply_default_paragraph_indents_shifts(self)`](/slides/python-net/fa/aspose.slides/bulletformat/apply_default_paragraph_indents_shifts/#) | شifts پیش‌فرض غیر صفر برای Indent و MarginLeft مؤثر پاراگراف را تنظیم می‌کند وقتی bullets فعال باشد (مانند کاری که PowerPoint هنگام فعال کردن گلوله‌ها/شماره‌گذاری پاراگراف انجام می‌دهد). اگر bullets غیرفعال باشد فقط Indent و MarginLeft پاراگراف را بازنشانی می‌کند (مانند کاری که PowerPoint هنگام غیرفعال کردن گلوله‌ها/شماره‌گذاری پاراگراف انجام می‌دهد). جابه‌جایی‌های تو رفتگی نسبت به زمینه فعلی گلوله - IBulletFormat.Type، .NumberedBulletStyle و FontHeight اولین بخش اعمال می‌شوند. جابه‌جایی‌های غیر صفر بر روی Indent و MarginLeft مؤثر پاراگرام فعلی اعمال می‌شوند (تا مقادیر حاصل به مقادیر محلی تبدیل شوند). |
| [`get_effective(self)`](/slides/python-net/fa/aspose.slides/bulletformat/get_effective/#) | داده‌های قالب‌بندی مؤثر گلوله را همراه با اعمال ارث‌بری بر می‌گرداند. |

### مراجع
* کلاس [`BulletFormat`](/slides/python-net/fa/aspose.slides/bulletformat)
* کلاس [`PVIObject`](/slides/python-net/fa/aspose.slides/pviobject)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)