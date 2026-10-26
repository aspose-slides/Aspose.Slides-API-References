---
title: only_load_document_properties property
second_title: مرجع API Aspose.Slides برای Python از طریق .NET
description: 
type: docs
url: /fa/aspose.slides/loadoptions/only_load_document_properties/
weight: 110
---
## only_load_document_properties ویژگی
This property makes sense, if presentation file is password protected.
            مقدار true به این معناست که فقط ویژگی‌های سند باید از یک فایل ارائهٔ رمزگذاری‌شده 
            بارگذاری شوند و رمز عبور نادیده گرفته شود.
            مقدار false به این معناست که تمام ارائهٔ رمزگذاری‌شده باید با استفاده از رمز عبور صحیح 
            بارگذاری شود.
            اگر ارائه رمزگذاری نشده باشد، مقدار ویژگی همیشه نادیده گرفته می‌شود.
            اگر ویژگی‌های سند یک فایل رمزگذاری‌شده عمومی نباشند و مقدار ویژگی true باشد،
            قابلیت بارگذاری ویژگی‌های سند وجود ندارد و استثنا پرتاب خواهد شد.
            خواندن/نوشتن **bool**.

### تعریف:
```python
@property
def only_load_document_properties(self):
    ...

@only_load_document_properties.setter
def only_load_document_properties(self, value):
    ...
```

### موارد مرتبط
* کلاس [`LoadOptions`](/slides/python-net/fa/aspose.slides/loadoptions)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)