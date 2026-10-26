---
title: LoadOptions class
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides/loadoptions/
---
## LoadOptions کلاس

به شما امکان می‌دهد گزینه‌های اضافی (مانند قالب یا قلم پیش‌فرض) را هنگام بارگذاری یک ارائه مشخص کنید.

نوع LoadOptions اعضای زیر را در اختیار می‌گذارد:

## سازنده‌ها

| Constructor | Description |
| :- | :- |
| [`__init__(self)`](/slides/python-net/fa/aspose.slides/loadoptions/__init__/#) | یک گزینه بارگذاری پیش‌فرض جدید ایجاد می‌کند. |
| [`__init__(self, load_format)`](/slides/python-net/fa/aspose.slides/loadoptions/__init__/#loadformat) | یک گزینه بارگذاری جدید ایجاد می‌کند. |

## ویژگی‌ها

| Property | Description |
| :- | :- |
| [`load_format`](/slides/python-net/fa/aspose.slides/loadoptions/load_format/) | قالب ارائه‌ای که باید بارگذاری شود را برمی‌گرداند یا تنظیم می‌کند.<br/>            خواندنی/قابل نوشتن [`LoadFormat`](/slides/python-net/fa/aspose.slides/loadformat). |
| [`default_regular_font`](/slides/python-net/fa/aspose.slides/loadoptions/default_regular_font/) | قلم Regular استفاده‌شده در صورتی که قلم منبع یافت نشود را برمی‌گرداند یا تنظیم می‌کند.<br/>            خواندنی/قابل نوشتن **str**. |
| [`default_symbol_font`](/slides/python-net/fa/aspose.slides/loadoptions/default_symbol_font/) | قلم Symbol که در صورت عدم یافتن قلم منبع استفاده می‌شود را برمی‌گرداند یا تنظیم می‌کند.<br/>            خواندنی/قابل نوشتن **str**. |
| [`default_asian_font`](/slides/python-net/fa/aspose.slides/loadoptions/default_asian_font/) | قلم Asian که در صورت عدم یافتن قلم منبع استفاده می‌شود را برمی‌گرداند یا تنظیم می‌کند.<br/>            خواندنی/قابل نوشتن **str**. |
| [`password`](/slides/python-net/fa/aspose.slides/loadoptions/password/) | رمز عبور را دریافت یا تنظیم می‌کند.<br/>            خواندنی/قابل نوشتن **str**. |
| [`only_load_document_properties`](/slides/python-net/fa/aspose.slides/loadoptions/only_load_document_properties/) | این ویژگی فقط زمانی معنی دارد که فایل ارائه با رمز محافظت شده باشد.<br/>            مقدار true به این معنی است که تنها ویژگی‌های سند باید از یک فایل ارائه رمزگذاری شده بارگذاری شوند و رمز عبور نادیده گرفته شود.<br/>            مقدار false به این معنی است که کل ارائه رمزگذاری شده باید با استفاده از رمز عبور صحیح بارگذاری شود.<br/>            اگر ارائه رمزگذاری نشده باشد، مقدار ویژگی همیشه نادیده گرفته می‌شود.<br/>            اگر ویژگی‌های سند یک فایل رمزگذاری شده عمومی نباشند و مقدار ویژگی true باشد، ویژگی‌های سند نمی‌توانند بارگذاری شوند و استثنایی رخ خواهد داد.<br/>            خواندنی/قابل نوشتن **bool**. |
| [`warning_callback`](/slides/python-net/fa/aspose.slides/loadoptions/warning_callback/) | شیئ که هشدارها را دریافت می‌کند و تصمیم می‌گیرد آیا فرآیند بارگذاری ادامه یابد یا متوقف شود.<br/>            خواندنی/قابل نوشتن [`IWarningCallback`](/slides/python-net/fa/aspose.slides.warnings/iwarningcallback). |
| [`blob_management_options`](/slides/python-net/fa/aspose.slides/loadoptions/blob_management_options/) | گزینه‌هایی را که می‌توان برای مدیریت رفتار پردازش Binary Large Objects (BLOBها) استفاده کرد، نشان می‌دهد،<br/>            مانند استفاده از فایل‌های موقت یا حداکثر بایت‌های BLOB در حافظه. این گزینه‌ها برای تنظیم بهترین نسبت عملکرد/مصرف حافظه برای یک محیط یا نیازهای خاص در نظر گرفته شده‌اند.<br/>            یک Binary Large Object (BLOB) داده باینری است که به عنوان یک موجودیت واحد ذخیره می‌شود - یعنی BLOB می‌تواند<br/>            یک صوت، ویدیو یا خود ارائه باشد. |
| [`document_level_font_sources`](/slides/python-net/fa/aspose.slides/loadoptions/document_level_font_sources/) | منابع فونت‌های خارجی‌ای که توسط ارائه استفاده می‌شوند را مشخص می‌کند.<br/>            این فونت‌ها در طول عمر ارائه در دسترس هستند و با ارائه‌های دیگر به اشتراک گذاشته نمی‌شوند |
| [`interruption_token`](/slides/python-net/fa/aspose.slides/loadoptions/interruption_token/) | توکنی برای نظارت بر درخواست‌های قطع.<br/>            <br/>            این توکن کل زمان حیات نمونه [`IPresentation`](/slides/python-net/fa/aspose.slides/ipresentation) را مدیریت می‌کند. هر عملیات طولانی‌مدت، مانند بارگذاری <br/>            یا ذخیره‌سازی ارائه، از طریق فراخوانی متد [`InterruptionTokenSource.interrupt`](/slides/python-net/fa/aspose.slides/interruptiontokensource/interrupt) از <br/>            [`InterruptionTokenSource`](/slides/python-net/fa/aspose.slides/interruptiontokensource) قطع خواهد شد. |
| [`resource_loading_callback`](/slides/python-net/fa/aspose.slides/loadoptions/resource_loading_callback/) | رابط بازگشت فراخوانی که بارگذاری منابع خارجی را مدیریت می‌کند را دریافت یا تنظیم می‌کند.<br/>            خواندنی/قابل نوشتن [`IResourceLoadingCallback`](/slides/python-net/fa/aspose.slides/iresourceloadingcallback). |
| [`spreadsheet_options`](/slides/python-net/fa/aspose.slides/loadoptions/spreadsheet_options/) | گزینه‌های مربوط به صفحات گسترده را دریافت می‌کند. به عنوان مثال، این گزینه‌ها بر محاسبه فرمول‌ها برای نمودارها تأثیر می‌گذارند. |
| [`default_text_language`](/slides/python-net/fa/aspose.slides/loadoptions/default_text_language/) | زبان پیش‌فرض متن ارائه را دریافت یا تنظیم می‌کند.<br/>            خواندنی/قابل نوشتن **str**. |
| [`delete_embedded_binary_objects`](/slides/python-net/fa/aspose.slides/loadoptions/delete_embedded_binary_objects/) | تعیین می‌کند آیا Aspose.Slides تمام اشیاء باینری جاسازی‌شده را هنگام بارگذاری ارائه حذف خواهد کرد یا نه.<br/>            <br/>انواع اشیاء باینری جاسازی‌شده:<br/><br/><br/>* VBA Project [`IPresentation.vba_project`](/slides/python-net/fa/aspose.slides/ipresentation/vba_project)<br/>* OLE Object embedded data [`IOleEmbeddedDataInfo.embedded_file_data`](/slides/python-net/fa/aspose.slides/ioleembeddeddatainfo/embedded_file_data)<br/>* ActiveX Control binary data [`IControl.active_x_control_binary`](/slides/python-net/fa/aspose.slides/icontrol/active_x_control_binary)<br/><br/><br/>            خواندنی/قابل نوشتن **bool**. |

### موارد مرتبط
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)