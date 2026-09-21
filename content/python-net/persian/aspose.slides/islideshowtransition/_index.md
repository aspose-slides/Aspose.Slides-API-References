---
title: ISlideShowTransition class
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides/islideshowtransition/
---
## ISlideShowTransition کلاس

نمایش اسلاید انتقال را نشان می‌دهد.

نوع ISlideShowTransition اعضای زیر را فراهم می‌کند:

## ویژگی‌ها

| Feature | توضیح |
| :- | :- |
| [`sound`](/slides/python-net/fa/aspose.slides/islideshowtransition/sound/) | داده‌های صوتی جاسازی شده را باز می‌گرداند یا تنظیم می‌کند.<br/>            قابل خواندن/نوشتن [`IAudio`](/slides/python-net/fa/aspose.slides/iaudio). |
| [`sound_mode`](/slides/python-net/fa/aspose.slides/islideshowtransition/sound_mode/) | حالت صدا برای انتقال اسلاید را تنظیم یا باز می‌گرداند.<br/>            قابل خواندن/نوشتن [`TransitionSoundMode`](/slides/python-net/fa/aspose.slides.slideshow/transitionsoundmode). |
| [`sound_loop`](/slides/python-net/fa/aspose.slides/islideshowtransition/sound_loop/) | این ویژگی مشخص می‌کند که آیا صدا تا وقوع رویداد صوتی بعدی در<br/>            نمایش اسلاید حلقه می‌زند یا نه.<br/>            قابل خواندن/نوشتن **bool**. |
| [`advance_on_click`](/slides/python-net/fa/aspose.slides/islideshowtransition/advance_on_click/) | مشخص می‌کند آیا یک کلیک ماوس اسلاید را پیش می‌برد یا نه. اگر این ویژگی<br/>            مشخص نشود مقدار true در نظر گرفته می‌شود.<br/>            قابل خواندن/نوشتن **bool**. |
| [`advance_after`](/slides/python-net/fa/aspose.slides/islideshowtransition/advance_after/) | این ویژگی مشخص می‌کند که آیا نمایش اسلاید پس از زمان معینی به اسلاید بعدی می‌رود یا نه.<br/>            قابل خواندن/نوشتن **bool**. |
| [`advance_after_time`](/slides/python-net/fa/aspose.slides/islideshowtransition/advance_after_time/) | زمان، به میلی‌ثانیه، پس از آن که انتقال باید شروع شود را مشخص می‌کند. این تنظیم می‌تواند همراه با ویژگی advClick استفاده شود. اگر این ویژگی مشخص نشود<br/>            فرض می‌شود که هیچ پیشروی خودکار رخ نخواهد داد.<br/>            قابل خواندن/نوشتن **int**. |
| [`speed`](/slides/python-net/fa/aspose.slides/islideshowtransition/speed/) | سرعت انتقالی که هنگام تغییر از اسلاید جاری به اسلاید بعدی استفاده می‌شود را مشخص می‌کند.<br/>            قابل خواندن/نوشتن [`TransitionSpeed`](/slides/python-net/fa/aspose.slides.slideshow/transitionspeed). |
| [`value`](/slides/python-net/fa/aspose.slides/islideshowtransition/value/) | مقدار انتقال نمایش اسلاید.<br/>            فقط خواندنی [`ITransitionValueBase`](/slides/python-net/fa/aspose.slides.slideshow/itransitionvaluebase). |
| [`type`](/slides/python-net/fa/aspose.slides/islideshowtransition/type/) | نوع انتقال.<br/>            قابل خواندن/نوشتن [`TransitionType`](/slides/python-net/fa/aspose.slides.slideshow/transitiontype). |
| [`sound_is_built_in`](/slides/python-net/fa/aspose.slides/islideshowtransition/sound_is_built_in/) | مشخص می‌کند آیا این صدا یک صدا داخلی است یا نه. اگر این ویژگی به true تنظیم شود برنامه تولیدکننده هشدار می‌شود تا ویژگی name را که برای این صدا در فهرست صداهای داخلی مشخص شده است، بررسی کند و سپس می‌تواند نام یا رابط کاربری سفارشی را ارائه دهد.<br/>            قابل خواندن/نوشتن **bool**. |
| [`sound_name`](/slides/python-net/fa/aspose.slides/islideshowtransition/sound_name/) | نام قابل خواندن انسانی برای صدای انتقال را مشخص می‌کند. برای دریافت یا تنظیم نام صدا باید ویژگی [`ISlideShowTransition.sound`](/slides/python-net/fa/aspose.slides/islideshowtransition/sound) مقداردهی شود.<br/>            قابل خواندن/نوشتن **str**. |
| [`duration`](/slides/python-net/fa/aspose.slides/islideshowtransition/duration/) | مدت اثر انتقال اسلاید را به میلی‌ثانیه دریافت یا تنظیم می‌کند.<br/>            قابل خواندن/نوشتن **int**. |

### ارجاع‌ها
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)