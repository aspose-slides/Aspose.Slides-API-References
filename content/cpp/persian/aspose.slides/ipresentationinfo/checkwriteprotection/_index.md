---
title: CheckWriteProtection()
second_title: مرجع API Aspose.Slides برای C++
description: بررسی می‌کند که آیا رمز عبور برای ویرایش یک ارائهٔ محافظت‌شده صحیح است یا نه.
type: docs
weight: 66
url: /fa/aspose.slides/ipresentationinfo/checkwriteprotection/
---
## IPresentationInfo::CheckWriteProtection(System::String) متد

بررسی می‌کند که آیا رمز عبور برای ویرایش یک ارائهٔ محافظت‌شده صحیح است یا خیر.

```cpp
virtual bool Aspose::Slides::IPresentationInfo::CheckWriteProtection(System::String password)=0
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| password | [System::String](../../../system/string/) | رمز عبوری که باید بررسی شود. |

### مقدار بازگشتی

در صورتی که ارائهٔ محافظت‌شده باشد و رمز عبور صحیح باشد، True برگردانده می‌شود. در غیر این صورت False.

## توضیحات

```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(presentationFilePath);
if (info->get_IsWriteProtected() == NullableBool::True)
{
    bool isWriteProtectedByPassword = info->CheckWriteProtection(u"my_password");
}
```

1. قبل از فراخوانی این متد باید ویژگی [IPresentationInfo::get_IsWriteProtected](../get_iswriteprotected/) را بررسی کنید.
1. هنگامی که مقدار password خالی یا null باشد، این متد False باز می‌گرداند.

## مراجع

* کلاس [String](../../../system/string/)
* کلاس [IPresentationInfo](../)
* فضای نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)