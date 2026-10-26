---
title: Hyperlink class
second_title: مرجع API Aspose.Slides برای Python از طریق .NET
description: 
type: docs
url: /fa/aspose.slides/hyperlink/
---
## کلاس Hyperlink

یک پیوند را نشان می‌دهد.

**Inheritance:**[`Hyperlink`](/slides/python-net/fa/aspose.slides/hyperlink) → [`PVIObject`](/slides/python-net/fa/aspose.slides/pviobject)

نوع Hyperlink اعضای زیر را در اختیار می‌گذارد:

## سازنده‌ها

| سازنده | توضیح |
| :- | :- |
| [`__init__(self, url)`](/slides/python-net/fa/aspose.slides/hyperlink/__init__/#str) | یک نمونه از پیوند را ایجاد می‌کند. |
| [`__init__(self, slide)`](/slides/python-net/fa/aspose.slides/hyperlink/__init__/#islide) | یک نمونه از پیوندی را ایجاد می‌کند که به اسلاید خاصی اشاره می‌کند.<br/>            نکته: پیوند ایجاد شده باید به شیئی از همان ارائه اختصاص یابد، در غیر این صورت لینک به عنوان NoAction ذخیره خواهد شد. |
| [`__init__(self, source, target_frame, tooltip, history, stop_sounds_on_click, highlight_click)`](/slides/python-net/fa/aspose.slides/hyperlink/__init__/#hyperlink-str-str-bool-bool-bool) | یک نمونه از پیوند را با استفاده از پیوند دیگر به عنوان منبع ایجاد می‌کند و ویژگی‌های ثانویه را بازنویسی می‌نماید. |

## ویژگی‌ها

| ویژگی | توضیح |
| :- | :- |
| [`no_action`](/slides/python-net/fa/aspose.slides/hyperlink/no_action/) | یک پیوند ویژه "کاری‌نکردن" را برمی‌گرداند.<br/>            فقط‌قابل‌خواندن [`Hyperlink`](/slides/python-net/fa/aspose.slides/hyperlink). |
| [`media`](/slides/python-net/fa/aspose.slides/hyperlink/media/) | یک پیوند ویژه "پخش فایل‌مدیا" را برمی‌گرداند. در AudioFrame و VideoFrame استفاده می‌شود.<br/>            فقط‌قابل‌خواندن [`Hyperlink`](/slides/python-net/fa/aspose.slides/hyperlink). |
| [`next_slide`](/slides/python-net/fa/aspose.slides/hyperlink/next_slide/) | یک پیوند به اسلاید بعدی را برمی‌گرداند.<br/>            فقط‌قابل‌خواندن [`Hyperlink`](/slides/python-net/fa/aspose.slides/hyperlink). |
| [`previous_slide`](/slides/python-net/fa/aspose.slides/hyperlink/previous_slide/) | یک پیوند به اسلاید قبلی را برمی‌گرداند.<br/>            فقط‌قابل‌خواندن [`Hyperlink`](/slides/python-net/fa/aspose.slides/hyperlink). |
| [`first_slide`](/slides/python-net/fa/aspose.slides/hyperlink/first_slide/) | یک پیوند به اولین اسلاید ارائه را برمی‌گرداند.<br/>            فقط‌قابل‌خواندن [`Hyperlink`](/slides/python-net/fa/aspose.slides/hyperlink). |
| [`last_slide`](/slides/python-net/fa/aspose.slides/hyperlink/last_slide/) | یک پیوند به آخرین اسلاید ارائه را برمی‌گرداند.<br/>            فقط‌قابل‌خواندن [`Hyperlink`](/slides/python-net/fa/aspose.slides/hyperlink). |
| [`last_vieved_slide`](/slides/python-net/fa/aspose.slides/hyperlink/last_vieved_slide/) | یک پیوند به آخرین اسلاید مشاهده‌شده را برمی‌گرداند.<br/>            فقط‌قابل‌خواندن [`Hyperlink`](/slides/python-net/fa/aspose.slides/hyperlink). |
| [`end_show`](/slides/python-net/fa/aspose.slides/hyperlink/end_show/) | یک پیوند که نمایش را پایان می‌دهد را برمی‌گرداند.<br/>            فقط‌قابل‌خواندن [`Hyperlink`](/slides/python-net/fa/aspose.slides/hyperlink). |
| [`action_type`](/slides/python-net/fa/aspose.slides/hyperlink/action_type/) | نوع اقدام Hyperlink را برمی‌گرداند.<br/>            فقط‌قابل‌خواندن [`HyperlinkActionType`](/slides/python-net/fa/aspose.slides/hyperlinkactiontype). |
| [`external_url`](/slides/python-net/fa/aspose.slides/hyperlink/external_url/) | URL خارجی را مشخص می‌کند.<br/>            فقط‌قابل‌خواندن **str**. |
| [`target_slide`](/slides/python-net/fa/aspose.slides/hyperlink/target_slide/) | اگر Hyperlink به اسلاید خاصی هدف داشته باشد، این اسلاید را برمی‌گرداند.<br/>            فقط‌قابل‌خواندن [`ISlide`](/slides/python-net/fa/aspose.slides/islide). |
| [`external_url_original`](/slides/python-net/fa/aspose.slides/hyperlink/external_url_original/) | یک پیوند را نشان می‌دهد که برای این بخش تنظیم شده است بدون توجه به محتوای واقعی بخش.<br/>            <br/>            PowerPoint رفتار خاصی برای لینک‌ها و متن متناظر آن‌ها در یک بخش دارد. این امکان را می‌دهد که متن برای پیوند به شکل یک URL معتبر ایجاد شود که متفاوت از آدرس واقعی لینک باشد. در این صورت، وقتی لینک را در پنجره ویرایش مشاهده می‌کنید، به متن بخش تغییر خواهد یافت. این ویژگی مقدار اصلی پیوند را نشان می‌دهد. |
| [`target_frame`](/slides/python-net/fa/aspose.slides/hyperlink/target_frame/) | قاب داخل مجموعه فریم‌های HTML والد را برای هدف<br/>            پیوند والد برمی‌گرداند هنگامی که موجود باشد.<br/>            خواندن/نوشتن **str**. |
| [`tooltip`](/slides/python-net/fa/aspose.slides/hyperlink/tooltip/) | رشته‌ای را برمی‌گرداند که ممکن است در رابط کاربری نمایش داده شود<br/>            به عنوان مرتبط با پیوند والد.<br/>            خواندن/نوشتن **str**. |
| [`history`](/slides/python-net/fa/aspose.slides/hyperlink/history/) | تعیین می‌کند آیا هدف پیوند والد هنگام فراخوانی به فهرست پیوندهای مشاهده‌شده اضافه شود یا خیر.<br/>            خواندن/نوشتن **bool**. |
| [`highlight_click`](/slides/python-net/fa/aspose.slides/hyperlink/highlight_click/) | تعیین می‌کند آیا پیوند هنگام کلیک برجسته شود یا خیر.<br/>            خواندن/نوشتن **bool**. |
| [`stop_sound_on_click`](/slides/python-net/fa/aspose.slides/hyperlink/stop_sound_on_click/) | تعیین می‌کند آیا صدا هنگام کلیک روی پیوند متوقف شود یا خیر.<br/>            خواندن/نوشتن **bool**. |
| [`sound`](/slides/python-net/fa/aspose.slides/hyperlink/sound/) | صدا پخش‌شده توسط پیوند را نشان می‌دهد.<br/>            خواندن/نوشتن [`IAudio`](/slides/python-net/fa/aspose.slides/iaudio). |
| [`color_source`](/slides/python-net/fa/aspose.slides/hyperlink/color_source/) | منبع رنگ پیوند را نشان می‌دهد - یا استایل‌ها یا قالب‌بندی بخش.<br/>            خواندن/نوشتن [`HyperlinkColorSource`](/slides/python-net/fa/aspose.slides/hyperlinkcolorsource). |
| [`slide`](/slides/python-net/fa/aspose.slides/hyperlink/slide/) |  |
| [`presentation`](/slides/python-net/fa/aspose.slides/hyperlink/presentation/) |  |

## متدها

| متد | توضیح |
| :- | :- |
| [`equals(self, hlink)`](/slides/python-net/fa/aspose.slides/hyperlink/equals/#ihyperlink) | تعیین می‌کند آیا دو نمونه Hyperlink برابر هستند یا خیر. |

### مراجع دیگر
* کلاس [`Hyperlink`](/slides/python-net/fa/aspose.slides/hyperlink)
* کلاس [`PVIObject`](/slides/python-net/fa/aspose.slides/pviobject)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)