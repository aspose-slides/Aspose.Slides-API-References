---
title: ProtectionManager class
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides/protectionmanager/
---
## ProtectionManager کلاس

مدیریت حفاظت پسورد ارائه.

نوع ProtectionManager اعضای زیر را ارائه می‌دهد:

## ویژگی‌ها

| ویژگی | توضیح |
| :- | :- |
| [`encrypt_document_properties`](/slides/python-net/fa/aspose.slides/protectionmanager/encrypt_document_properties/) | این ویژگی زمانی مفهوم دارد که ارائه با پسورد محافظت شده باشد.<br/>اگر مقدار true باشد، ویژگی‌های سند در فایل ارائه رمزگذاری می‌شود.<br/>اگر مقدار false باشد، ویژگی‌های سند عمومی است در حالی که ارائه رمزگذاری شده است.<br/>Read/write **bool**. |
| [`is_encrypted`](/slides/python-net/fa/aspose.slides/protectionmanager/is_encrypted/) | یک مقدار را برمی‌گرداند که نشان می‌دهد آیا این نمونه رمزگذاری شده است.<br/>Read-only **bool**. |
| [`is_only_document_properties_loaded`](/slides/python-net/fa/aspose.slides/protectionmanager/is_only_document_properties_loaded/) | این ویژگی زمانی مفهوم دارد که فایل ارائه با پسورد محافظت شده باشد و ویژگی‌های سند این فایل عمومی باشند.<br/>مقدار true به این معنی است که فقط ویژگی‌های سند از یک فایل ارائه رمزگذاری‌شده بدون استفاده از پسورد بارگذاری می‌شوند.<br/>مقدار false به این معنی است که تمام ارائه رمزگذاری‌شده با استفاده از پسورد صحیح بارگذاری می‌شود و نه فقط ویژگی‌های سند.<br/>اگر ارائه رمزگذاری نشده باشد، مقدار ویژگی همیشه false است.<br/>اگر ویژگی‌های سند یک فایل رمزگذاری‌شده عمومی نباشند، مقدار ویژگی همیشه false است.<br/>اگر Presentation.EncryptDocumentProperties برابر true باشد، مقدار ویژگی IsOnlyDocumentPropertiesLoaded همیشه false است.<br/>Read-only **bool**. |
| [`is_write_protected`](/slides/python-net/fa/aspose.slides/protectionmanager/is_write_protected/) | یک مقدار را برمی‌گرداند که نشان می‌دهد آیا این ارائه از نوشتن محافظت شده است.<br/>Read-only **bool**. |
| [`encryption_password`](/slides/python-net/fa/aspose.slides/protectionmanager/encryption_password/) | پسوردی که برای رمزگذاری ارائه استفاده می‌شود را برمی‌گرداند.<br/>Read-only **str**. |
| [`read_only_recommended`](/slides/python-net/fa/aspose.slides/protectionmanager/read_only_recommended/) | توصیه‌ی فقط-خواندنی را دریافت یا تنظیم می‌کند.<br/>Read/write **bool**. |

## متدها

| متد | توضیح |
| :- | :- |
| [`encrypt(self, encryption_password)`](/slides/python-net/fa/aspose.slides/protectionmanager/encrypt/#str) | Presentation را با پسورد مشخص شده رمزگذاری می‌کند. |
| [`remove_encryption(self)`](/slides/python-net/fa/aspose.slides/protectionmanager/remove_encryption/#) | رمزگذاری را حذف می‌کند. |
| [`set_write_protection(self, password)`](/slides/python-net/fa/aspose.slides/protectionmanager/set_write_protection/#str) | محافظت نوشتن برای این ارائه را با پسورد مشخص شده تنظیم می‌کند. |
| [`remove_write_protection(self)`](/slides/python-net/fa/aspose.slides/protectionmanager/remove_write_protection/#) | محافظت نوشتن این ارائه را حذف می‌کند. |
| [`check_write_protection(self, password)`](/slides/python-net/fa/aspose.slides/protectionmanager/check_write_protection/#str) | مشخص می‌کند که آیا یک ارائه برای ویرایش محافظت شده با پسورد است. |

### همچنین ببینید
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)