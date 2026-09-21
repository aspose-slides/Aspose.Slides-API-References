---
title: is_only_document_properties_loaded property
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides/iprotectionmanager/is_only_document_properties_loaded/
weight: 90
---
## is_only_document_properties_loaded ویژگی
این ویژگی زمانی معنی دارد که فایل ارائه با گذرواژه محافظت شده باشد و
            ویژگی‌های این فایل عمومی باشند.
            مقدار true به این معنی است که فقط ویژگی‌های سند از یک ارائه رمزنگاری‌شده
            بارگذاری می‌شوند، بدون استفاده از گذرواژه.
            مقدار false به این معنی است که کل ارائهٔ رمزنگاری‌شده با استفاده از گذرواژهٔ صحیح
            بارگذاری می‌شود، نه فقط ویژگی‌های سند.
            اگر ارائه رمزنگاری نشده باشد، مقدار ویژگی همیشه false است.
            اگر ویژگی‌های سند یک فایل رمزنگاری‌شده عمومی نباشند، مقدار ویژگی همیشه false است.
            اگر PresentationEx.EncryptDocumentProperties برابر true باشد، آنگاه IsOnlyDocumentPropertiesLoaded
            مقدار ویژگی همیشه false است.
            فقط-خواندنی **bool**.

### تعریف:
```python
@property
def is_only_document_properties_loaded(self):
    ...
```

### موارد مرتبط
* کلاس [`IProtectionManager`](/slides/python-net/fa/aspose.slides/iprotectionmanager)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)