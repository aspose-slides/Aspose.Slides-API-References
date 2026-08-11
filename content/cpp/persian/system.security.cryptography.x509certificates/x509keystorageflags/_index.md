---
title: X509KeyStorageFlags
second_title: Aspose.Slides برای مرجع API C++
description: نحوهٔ ذخیره‌سازی کلید را تعریف می‌کند.
type: docs
weight: 261
url: /fa/system.security.cryptography.x509certificates/x509keystorageflags/
---
## X509KeyStorageFlags enum


کلید چگونه ذخیره شود را تعریف می‌کند.

```cpp
enum class X509KeyStorageFlags : int32_t
```

### مقادیر

| نام | مقدار | توضیح |
| --- | --- | --- |
| DefaultKeySet | 0 | از مجموعه کلید پیش‌فرض استفاده می‌شود. |
| UserKeySet | 1 | از ذخیره‌ساز مرتبط با کاربر به جای ذخیره‌ساز محلی ماشین استفاده می‌شود. |
| MachineKeySet | 2 | از ذخیره‌ساز محلی ماشین به جای ذخیره‌ساز کاربر استفاده می‌شود. |
| Exportable | 4 | کلیدهای وارد شده را به عنوان قابل صادرات علامت‌گذاری می‌کند. |
| UserProtected | 8 | به کاربر اطلاع می‌دهد که کلید در حال استفاده است. |
| PersistKeySet | 16 | کلید هنگام وارد کردن گواهی حفظ می‌شود. |

## موارد مرتبط

* Namespace [System::Security::Cryptography::X509Certificates](../)
* Library [Aspose.Slides](../../)