---
title: ILoadOptions class
second_title: مرجع API Aspose.Slides برای Python از طریق .NET
description: 
type: docs
url: /fa/aspose.slides/iloadoptions/
---
## ILoadOptions کلاس

به شما امکان می‌دهد گزینه‌های اضافی (مانند قالب یا قلم پیش‌فرض) را هنگام بارگذاری یک ارائه مشخص کنید.

نوع ILoadOptions اعضای زیر را ارائه می‌دهد:

## ویژگی‌ها

| Property | Description |
| :- | :- |
| [`load_format`](/slides/python-net/fa/aspose.slides/iloadoptions/load_format/) | قالب یک ارائه برای بارگذاری را برمی‌گرداند یا تنظیم می‌کند.<br/>            خواندن/نوشتن [`LoadFormat`](/slides/python-net/fa/aspose.slides/loadformat). |
| [`default_regular_font`](/slides/python-net/fa/aspose.slides/iloadoptions/default_regular_font/) | قلم معمولی که در صورت عدم یافتن قلم منبع استفاده می‌شود را برمی‌گرداند یا تنظیم می‌کند.<br/>            خواندن/نوشتن **str**. |
| [`default_symbol_font`](/slides/python-net/fa/aspose.slides/iloadoptions/default_symbol_font/) | قلم Symbol که در صورت عدم یافتن قلم منبع استفاده می‌شود را برمی‌گرداند یا تنظیم می‌کند.<br/>            خواندن/نوشتن **str**. |
| [`default_asian_font`](/slides/python-net/fa/aspose.slides/iloadoptions/default_asian_font/) | قلم Asian که در صورت عدم یافتن قلم منبع استفاده می‌شود را برمی‌گرداند یا تنظیم می‌کند.<br/>            خواندن/نوشتن **str**. |
| [`password`](/slides/python-net/fa/aspose.slides/iloadoptions/password/) | رمز عبور را دریافت یا تنظیم می‌کند.<br/>            خواندن/نوشتن **str**. |
| [`only_load_document_properties`](/slides/python-net/fa/aspose.slides/iloadoptions/only_load_document_properties/) | این ویژگی فقط در صورتی معنی دارد که فایل ارائه دارای رمز عبور باشد.<br/>            مقدار true به این معنی است که فقط ویژگی‌های سند باید از یک فایل ارائه رمزگذاری‌شده بارگذاری شوند و رمز عبور نادیده گرفته شود.<br/>            مقدار false به این معنی است که کل ارائه رمزگذاری‌شده باید با استفاده از رمز عبور صحیح بارگذاری شود.<br/>            اگر ارائه رمزگذاری نشده باشد، مقدار ویژگی همیشه نادیده گرفته می‌شود.<br/>            اگر ویژگی‌های سند یک فایل رمزگذاری‌شده عمومی نباشند و مقدار ویژگی true باشد، ویژگی‌های سند نمی‌توانند بارگذاری شوند و استثنا رخ خواهد داد.<br/>            خواندن/نوشتن **bool**. |
| [`warning_callback`](/slides/python-net/fa/aspose.slides/iloadoptions/warning_callback/) | یک شیء که هشدارها را دریافت می‌کند و تصمیم می‌گیرد آیا فرآیند بارگذاری ادامه یابد یا متوقف شود را برمی‌گرداند یا تنظیم می‌کند.<br/>            خواندن/نوشتن [`IWarningCallback`](/slides/python-net/fa/aspose.slides.warnings/iwarningcallback). |
| [`blob_management_options`](/slides/python-net/fa/aspose.slides/iloadoptions/blob_management_options/) | گزینه‌هایی را نمایندگی می‌کند که می‌توانند برای مدیریت رفتار پردازش Binary Large Objects (BLOBs) استفاده شوند،<br/>            مانند استفاده از فایل‌های موقت یا حداکثر بایت‌های BLOB در حافظه. این گزینه‌ها برای تنظیم نسبت بهترین عملکرد/مصرف حافظه برای یک محیط یا نیازهای خاص در نظر گرفته شده‌اند.<br/>            یک Binary Large Object (BLOB) داده‌ای باینری است که به‌صورت یک واحد ذخیره می‌شود - به‌عبارت دیگر BLOB می‌تواند<br/>            یک صدا، ویدئو یا خود ارائه باشد. |
| [`document_level_font_sources`](/slides/python-net/fa/aspose.slides/iloadoptions/document_level_font_sources/) | منابع قلم‌های خارجی که توسط ارائه استفاده می‌شوند را مشخص می‌کند.<br/>            این قلم‌ها در طول عمر ارائه در دسترس هستند و با دیگر ارائه‌ها به‌اشتراک گذاشته نمی‌شوند |
| [`interruption_token`](/slides/python-net/fa/aspose.slides/iloadoptions/interruption_token/) | توکنی برای نظارت بر درخواست‌های وقفه.<br/>            <br/>            این توکن عمر تمام نمونهٔ [`IPresentation`](/slides/python-net/fa/aspose.slides/ipresentation) را مدیریت می‌کند. هر عملیات طولانی‌مدت، مانند بارگذاری یا ذخیره‌سازی ارائه، از طریق فراخوانی روش [`IInterruptionTokenSource.interrupt`](/slides/python-net/fa/aspose.slides/iinterruptiontokensource/interrupt) از [`IInterruptionTokenSource`](/slides/python-net/fa/aspose.slides/iinterruptiontokensource) قطع خواهد شد. |
| [`resource_loading_callback`](/slides/python-net/fa/aspose.slides/iloadoptions/resource_loading_callback/) | یک اینترفیس callback که بارگذاری منابع خارجی را مدیریت می‌کند را برمی‌گرداند یا تنظیم می‌کند.<br/>            خواندن/نوشتن [`IResourceLoadingCallback`](/slides/python-net/fa/aspose.slides/iresourceloadingcallback). |
| [`spreadsheet_options`](/slides/python-net/fa/aspose.slides/iloadoptions/spreadsheet_options/) | گزینه‌هایی را نمایندگی می‌کند که می‌توانند برای مشخص کردن رفتار افزایشی صفحات گسترده استفاده شوند. |
| [`default_text_language`](/slides/python-net/fa/aspose.slides/iloadoptions/default_text_language/) | زبان پیش‌فرض برای متن ارائه را برمی‌گرداند یا تنظیم می‌کند.<br/>            خواندن/نوشتن **str**. |
| [`delete_embedded_binary_objects`](/slides/python-net/fa/aspose.slides/iloadoptions/delete_embedded_binary_objects/) | تعیین می‌کند آیا Aspose.Slides تمام اشیاء باینری جاسازی‌شده را هنگام بارگذاری ارائه حذف خواهد کرد یا خیر.<br/>            <br/>انواع اشیاء باینری جاسازی‌شده:<br/><br/><br/>* پروژه VBA [`IPresentation.vba_project`](/slides/python-net/fa/aspose.slides/ipresentation/vba_project)<br/>* داده‌های جاسازی‌شده OLE Object [`IOleEmbeddedDataInfo.embedded_file_data`](/slides/python-net/fa/aspose.slides/ioleembeddeddatainfo/embedded_file_data)<br/>* داده‌های باینری ActiveX Control [`IControl.active_x_control_binary`](/slides/python-net/fa/aspose.slides/icontrol/active_x_control_binary)<br/><br/><br/>            خواندن/نوشتن **bool**. |

### همچنین ببینید
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)