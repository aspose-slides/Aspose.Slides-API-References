---
title: IBlobManagementOptions class
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides/iblobmanagementoptions/
---
## IBlobManagementOptions کلاس

یک شیء بزرگ دودویی (BLOB) داده‌ای باینری است که به‌عنوان یک موجودیت واحد ذخیره می‌شود - یعنی BLOB می‌تواند یک صدا، ویدیو یا خود ارائه باشد. برای بهینه‌سازی مصرف حافظه هنگام کار با BLOBها از چندین تکنیک استفاده می‌شود - چه این‌که BLOB قبلاً در ارائه ذخیره شده باشد یا به‌صورت برنامه‌نویسی بعداً اضافه شود. با استفاده از [`IBlobManagementOptions`](/slides/python-net/fa/aspose.slides/iblobmanagementoptions) می‌توانید جنبه‌های رفتاری مختلف مربوط به مدیریت BLOBها را برای طول عمر نمونه [`IPresentation`](/slides/python-net/fa/aspose.slides/ipresentation) تغییر دهید.

The IBlobManagementOptions type exposes the following members:

## ویژگی‌ها

| Property | Description |
| :- | :- |
| [`presentation_locking_behavior`](/slides/python-net/fa/aspose.slides/iblobmanagementoptions/presentation_locking_behavior/) | این ویژگی تعیین می‌کند که آیا یک نمونه از کلاس Presentation می‌تواند مالک منبع - فایل <br/>            یا جریان در طول طول عمر نمونه باشد. اگر نمونه مالک باشد، منبعقفل می‌شود. این به <br/>            بهبود مصرف حافظه و عملکرد هنگام کار با BLOBها کمک می‌کند، اما منبع (جریان یا فایل) <br/>            نمی‌تواند در طول طول عمر نمونه Presentation تغییر کند. این یک مثال است: |
| [`is_temporary_files_allowed`](/slides/python-net/fa/aspose.slides/iblobmanagementoptions/is_temporary_files_allowed/) | این ویژگی تعیین می‌کند که آیا می‌توان فایل‌های موقت را هنگام کار با BLOBها ایجاد کرد، که به‌ طور قابل‌ توجهی <br/>            مصرف حافظه را کاهش می‌دهد اما نیاز به مجوزهای ایجاد فایل دارد.<br/>            تمام فایل‌ها پس از اتمام کار با ارائه حذف خواهند شد. |
| [`temp_files_root_path`](/slides/python-net/fa/aspose.slides/iblobmanagementoptions/temp_files_root_path/) | مسیر ریشه‌ای که در آن فایل‌های موقت ایجاد می‌شوند. به‌ طور پیش‌فرض از دایرکتوری موقت سیستم استفاده خواهد شد. <br/>            فرآیند میزبانی باید مجوزهای لازم برای <br/>            ایجاد فایل‌ها و پوشه‌ها در آنجا داشته باشد. |
| [`max_blobs_bytes_in_memory`](/slides/python-net/fa/aspose.slides/iblobmanagementoptions/max_blobs_bytes_in_memory/) | حداکثر اندازه کل (به بایت) را که تمام BLOBها می‌توانند در حافظه اشغال کنند، تعریف می‌کند. به‌ طور پیش‌فرض، تمام BLOBها<br/>            در حافظه بارگذاری می‌شوند؛ فقط وقتی این حد رسیده شود، مکانیزم‌های جایگزین (مانند فایل‌های موقت)<br/>            به کار گرفته می‌شوند. نگه داشتن BLOBها در حافظه عملکرد را به حداکثر می‌رساند اما ممکن است منجر به مصرف بالا شود. از<br/>            این ویژگی برای تنظیم رفتار بر حسب محیط یا نیازهای خود استفاده کنید. |


### موارد مرتبط
* کلاس [`IBlobManagementOptions`](/slides/python-net/fa/aspose.slides/iblobmanagementoptions)
* کلاس [`IPresentation`](/slides/python-net/fa/aspose.slides/ipresentation)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)