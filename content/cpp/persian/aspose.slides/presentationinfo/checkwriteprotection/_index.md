---
title: CheckWriteProtection()
second_title: Aspose.Slides برای C++ مرجع API
description: بررسی می‌کند که آیا رمز عبور برای اصلاح یک ارائه محافظت‌شده در مقابل نوشتن صحیح است یا خیر.
type: docs
weight: 66
url: /fa/aspose.slides/presentationinfo/checkwriteprotection/
---
## PresentationInfo::CheckWriteProtection(System::String) متد


بررسی می‌کند که آیا رمز عبور برای ویرایش برای یک ارائه محافظت‌شده در برابر نوشتن صحیح است یا خیر.

```cpp
bool Aspose::Slides::PresentationInfo::CheckWriteProtection(System::String password) override
```


### پارامترها

| Parameter | Type | Description |
| --- | --- | --- |
| password | [System::String](../../../system/string/) | رمز عبور برای بررسی. |

### مقدار بازگشت

True if the presentation is write protected and the password is correct. False otherwise.

## توضیحات



```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(presentationFilePath);
if (info->get_IsWriteProtected() == NullableBool::True)
{
    bool isWriteProtectedByPassword = info->CheckWriteProtection(u"my_password");
}
```



1. قبل از فراخوانی این متد باید ویژگی [PresentationInfo::get_IsWriteProtected](../get_iswriteprotected/) را بررسی کنید.
1. زمانی که رمز عبور خالی یا مقدار null باشد، این متد false را برمی‌گرداند.



## موارد مرتبط

* کلاس [String](../../../system/string/)
* کلاس [PresentationInfo](../)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)