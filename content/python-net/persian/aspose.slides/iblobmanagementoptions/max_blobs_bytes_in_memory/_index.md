---
title: max_blobs_bytes_in_memory property
second_title: Aspose.Slides برای Python از طریق .NET API Reference
description: 
type: docs
url: /fa/aspose.slides/iblobmanagementoptions/max_blobs_bytes_in_memory/
weight: 20
---
## max_blobs_bytes_in_memory ویژگی
حداکثر اندازه کل (بر حسب بایت) که همه BLOBها می‌توانند در حافظه اشغال کنند را تعریف می‌کند. به طور پیش‌فرض، همه BLOBها به حافظه بارگذاری می‌شوند؛ فقط زمانی که این محدودیت رسید، مکانیزم‌های جایگزین (مانند فایل‌های موقت) به کار گرفته می‌شوند. نگه داشتن BLOBها در حافظه عملکرد را به حداکثر می‌رساند اما می‌تواند منجر به مصرف بالای حافظه شود. از این ویژگی برای تنظیم رفتار مطابق با محیط یا نیازهای خود استفاده کنید.


### توضیحات

این ویژگی نادیده گرفته می‌شود اگر [`IBlobManagementOptions.is_temporary_files_allowed`](/slides/python-net/fa/aspose.slides/iblobmanagementoptions/is_temporary_files_allowed) روی false تنظیم شده باشد، زیرا در آن زمان حافظه تنها مکان ذخیره‌سازی موجود است و محدود کردن استفاده از BLOB در حافظه تأثیری ندارد.

### تعریف:
```python
@property
def max_blobs_bytes_in_memory(self):
    ...

@max_blobs_bytes_in_memory.setter
def max_blobs_bytes_in_memory(self, value):
    ...
```


### مراجع
* کلاس [`IBlobManagementOptions`](/slides/python-net/fa/aspose.slides/iblobmanagementoptions)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)