---
title: max_blobs_bytes_in_memory property
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides/blobmanagementoptions/max_blobs_bytes_in_memory/
weight: 30
---
## max_blobs_bytes_in_memory ویژگی
حداکثر اندازه کل (به بایت) که تمام BLOBها ممکن است در حافظه اشغال کنند را تعریف می‌کند. به‌طور پیش‌فرض، تمام BLOBها
            در حافظه بارگذاری می‌شوند؛ تنها زمانی که این حد برسد، مکانیزم‌های جایگزین (مانند فایل‌های موقت)
            به کار گرفته می‌شوند. نگهداری BLOBها در حافظه عملکرد را به حداکثر می‌رساند اما می‌تواند منجر به مصرف بالای حافظه شود. از
            این ویژگی برای تطبیق رفتار با محیط یا نیازهای خود استفاده کنید.


### یادداشت‌ها

این ویژگی نادیده گرفته می‌شود اگر [`BlobManagementOptions.is_temporary_files_allowed`](/slides/python-net/fa/aspose.slides/blobmanagementoptions/is_temporary_files_allowed) روی false تنظیم شده باشد، چون حافظه
            تنها مکان ذخیره‌سازی موجود است و محدود کردن استفاده از BLOB در حافظه تأثیری ندارد.

### تعریف:
```python
@property
def max_blobs_bytes_in_memory(self):
    ...

@max_blobs_bytes_in_memory.setter
def max_blobs_bytes_in_memory(self, value):
    ...
```


### موارد مرتبط
* کلاس [`BlobManagementOptions`](/slides/python-net/fa/aspose.slides/blobmanagementoptions)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)