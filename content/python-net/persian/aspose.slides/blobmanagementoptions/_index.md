---
title: BlobManagementOptions class
second_title: Aspose.Slides برای پایتون از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides/blobmanagementoptions/
---
## BlobManagementOptions کلاس

نمایش‌دهنده گزینه‌هایی که می‌توان برای مدیریت قوانین پردازش BLOB و سایر تنظیمات BLOB استفاده کرد.

نوع BlobManagementOptions اعضای زیر را ارائه می‌دهد:

## سازنده‌ها

| Constructor | Description |
| :- | :- |
| [`__init__(self)`](/slides/python-net/fa/aspose.slides/blobmanagementoptions/__init__/#) | گزینه‌های پیش‌فرض مدیریت BLOB جدیدی را ایجاد می‌کند. |

## ویژگی‌ها

| Property | Description |
| :- | :- |
| [`presentation_locking_behavior`](/slides/python-net/fa/aspose.slides/blobmanagementoptions/presentation_locking_behavior/) | این ویژگی تعیین می‌کند که آیا یک نمونه از کلاس Presentation می‌تواند مالک منبع - فایل <br/>            یا جریان در طول عمر نمونه باشد. اگر نمونه مالک باشد، منبع را قفل می‌کند. این به <br/>            بهبود مصرف حافظه و عملکرد هنگام کار با BLOBها کمک می‌کند، اما منبع (جریان یا فایل) <br/>            در طول عمر نمونه Presentation نمی‌تواند تغییر یابد. |
| [`is_temporary_files_allowed`](/slides/python-net/fa/aspose.slides/blobmanagementoptions/is_temporary_files_allowed/) | این ویژگی تعیین می‌کند که آیا فایل‌های موقت می‌توانند در حین کار با BLOBها ایجاد شوند، که به‌طور قابل‌توجهی مصرف حافظه را کاهش می‌دهد اما نیاز به مجوزهای ایجاد فایل دارد.<br/>            تمام فایل‌ها پس از اتمام کار با ارائه حذف خواهند شد. |
| [`temp_files_root_path`](/slides/python-net/fa/aspose.slides/blobmanagementoptions/temp_files_root_path/) | مسیر ریشه‌ای که فایل‌های موقت در آن ایجاد می‌شوند. به‌طور پیش‌فرض از پوشه موقت سیستم استفاده می‌شود. <br/>            فرآیند میزبانی باید مجوزهای <br/>            ایجاد فایل‌ها و پوشه‌ها را در آن داشته باشد. |
| [`max_blobs_bytes_in_memory`](/slides/python-net/fa/aspose.slides/blobmanagementoptions/max_blobs_bytes_in_memory/) | حداکثر اندازه کل (به بایت) که تمام BLOBها می‌توانند در حافظه اشغال کنند را تعریف می‌کند. به‌طور پیش‌فرض، تمام BLOBها<br/>            در حافظه بارگذاری می‌شوند؛ فقط پس از رسیدن به این محدودیت، مکانیزم‌های جایگزین (مانند فایل‌های موقت)<br/>            به کار گرفته می‌شوند. نگه داشتن BLOBها در حافظه عملکرد را حداکثر می‌کند اما می‌تواند منجر به مصرف زیاد حافظه شود. از این ویژگی برای تنظیم رفتار مطابق با محیط یا نیازهای خود استفاده کنید. |

### همچنین
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)