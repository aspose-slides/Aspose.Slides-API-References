---
title: CheckWriteProtection()
second_title: مرجع API Aspose.Slides برای C++
description: تعیین می‌کند که آیا ارائه برای اصلاح با رمز عبور محافظت شده است یا خیر.
type: docs
weight: 157
url: /fa/aspose.slides/iprotectionmanager/checkwriteprotection/
---
## IProtectionManager::CheckWriteProtection(System::String) متد

Determines whether a presentation is a password protected to modify.

```cpp
virtual bool Aspose::Slides::IProtectionManager::CheckWriteProtection(System::String password)=0
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| password | [System::String](../../../system/string/) | رمز عبور برای بررسی. |

### مقدار برگشتی

در صورتی که رمز عبور معتبر باشد true؛ در غیر این صورت false.

## توضیحات

```cpp
auto presentation = System::MakeObject<Presentation>(presentationFilePath);
bool isWriteProtected = presentation->get_ProtectionManager()->CheckWriteProtection(u"my_password");
```

1. شما باید قبل از فراخوانی این متد، ویژگی [IProtectionManager::get_IsWriteProtected](../get_iswriteprotected/) را بررسی کنید.
1. وقتی رمز عبور null یا خالی باشد، این متد false برمی‌گرداند.

## مراجع

* کلاس [String](../../../system/string/)
* کلاس [IProtectionManager](../)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)