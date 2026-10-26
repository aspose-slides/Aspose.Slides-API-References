---
title: IProtectionManager class
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides/iprotectionmanager/
---
## IProtectionManager کلاس

مدیریت محافظت با رمز عبور ارائه.

نوع IProtectionManager اعضای زیر را نشان می‌دهد:

## ویژگی‌ها

| ویژگی | توضیح |
| :- | :- |
| [`encrypt_document_properties`](/slides/python-net/fa/aspose.slides/iprotectionmanager/encrypt_document_properties/) | این ویژگی زمانی معنی دارد که ارائه دارای رمز عبور باشد.<br/>            اگر true باشد، خصوصیات سند در فایل ارائه رمزگذاری می‌شود.<br/>            اگر false باشد، خصوصیات سند عمومی است در حالی که ارائه رمزگذاری شده است.<br/>            خواندن/نوشتن **bool**. |
| [`is_encrypted`](/slides/python-net/fa/aspose.slides/iprotectionmanager/is_encrypted/) | مقداردهی می‌کند که آیا این نمونه رمزگذاری شده است یا خیر.<br/>            فقط خواندنی **bool**. |
| [`is_only_document_properties_loaded`](/slides/python-net/fa/aspose.slides/iprotectionmanager/is_only_document_properties_loaded/) | این ویژگی زمانی معنی دارد که فایل ارائه دارای رمز عبور باشد و خصوصیات سند این فایل عمومی باشد.<br/>            مقدار true به این معنی است که فقط خصوصیات سند از یک فایل ارائه رمزگذاری شده بدون استفاده از رمز عبور بارگذاری می‌شود.<br/>            مقدار false به این معنی است که کل ارائه رمزگذاری شده با استفاده از رمز عبور صحیح بارگذاری می‌شود، نه فقط خصوصیات سند.<br/>            اگر ارائه رمزگذاری نشده باشد، مقدار ویژگی همیشه false است.<br/>            اگر خصوصیات سند یک فایل رمزگذاری شده عمومی نباشند، مقدار ویژگی همیشه false است.<br/>            اگر PresentationEx.EncryptDocumentProperties برابر true باشد، مقدار ویژگی IsOnlyDocumentPropertiesLoaded همیشه false است.<br/>            فقط خواندنی **bool**. |
| [`is_write_protected`](/slides/python-net/fa/aspose.slides/iprotectionmanager/is_write_protected/) | مقداردهی می‌کند که آیا این ارائه محافظت نوشتنی دارد یا خیر.<br/>            فقط خواندنی **bool**. |
| [`encryption_password`](/slides/python-net/fa/aspose.slides/iprotectionmanager/encryption_password/) | رمز عبور رمزگذاری را برمی‌گرداند.<br/>            فقط خواندنی **str**. |
| [`read_only_recommended`](/slides/python-net/fa/aspose.slides/iprotectionmanager/read_only_recommended/) | مقداردهی یا تنظیم توصیه فقط خواندنی.<br/>            خواندن/نوشتن **bool**. |

## متدها

| متد | توضیح |
| :- | :- |
| [`encrypt(self, encryption_password)`](/slides/python-net/fa/aspose.slides/iprotectionmanager/encrypt/#str) | ارائه را با رمز عبور مشخص رمزگذاری می‌کند. |
| [`remove_encryption(self)`](/slides/python-net/fa/aspose.slides/iprotectionmanager/remove_encryption/#) | رمزگذاری را حذف می‌کند. |
| [`set_write_protection(self, password)`](/slides/python-net/fa/aspose.slides/iprotectionmanager/set_write_protection/#str) | محافظت نوشتن برای این ارائه با رمز عبور مشخص تنظیم می‌کند. |
| [`remove_write_protection(self)`](/slides/python-net/fa/aspose.slides/iprotectionmanager/remove_write_protection/#) | محافظت نوشتن این ارائه را حذف می‌کند. |
| [`check_write_protection(self, password)`](/slides/python-net/fa/aspose.slides/iprotectionmanager/check_write_protection/#str) | تعیین می‌کند که آیا یک ارائه با رمز عبور برای ویرایش محافظت شده است یا خیر. |

### مراجع مرتبط
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)