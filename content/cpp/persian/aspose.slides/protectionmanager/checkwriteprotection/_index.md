---
title: CheckWriteProtection()
second_title: مرجع API Aspose.Slides برای C++
description: تعیین می‌کند آیا ارائه برای ویرایش با رمز عبور محافظت شده است یا خیر.
type: docs
weight: 157
url: /fa/aspose.slides/protectionmanager/checkwriteprotection/
---
## ProtectionManager::CheckWriteProtection(System::String) متد

مشخص می‌کند آیا ارائه برای ویرایش دارای رمز عبور محافظت شده است یا خیر.

```cpp
bool Aspose::Slides::ProtectionManager::CheckWriteProtection(System::String password) override
```

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| password | [System::String](../../../system/string/) | رمز عبوری که برای بررسی استفاده می‌شود. |

### Return Value

True if the password is valid; otherwise, false.
## Remarks

```cpp
auto presentation = System::MakeObject<Presentation>(presentationFilePath);
bool isWriteProtected = presentation->get_ProtectionManager()->CheckWriteProtection(u"my_password");
```

1. قبل از فراخوانی این متد باید ویژگی [ProtectionManager::get_IsWriteProtected](../get_iswriteprotected/) را بررسی کنید.
1. زمانی که رمز عبور null یا خالی باشد، این متد false برمی‌گرداند.

## See Also

* کلاس [String](../../../system/string/)
* کلاس [ProtectionManager](../)
* فضای نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)