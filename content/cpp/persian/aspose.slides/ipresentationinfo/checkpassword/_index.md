---
title: CheckPassword()
second_title: مرجع API Aspose.Slides برای C++
description: بررسی می‌کند که آیا رمز عبور برای یک ارائه که با رمز عبور باز محافظت شده است صحیح می‌باشد.
type: docs
weight: 53
url: /fa/aspose.slides/ipresentationinfo/checkpassword/
---
## IPresentationInfo::CheckPassword(System::String) متد

بررسی می‌کند که آیا رمز عبور برای ارائه‌ای که با رمز عبور باز محافظت شده صحیح است یا خیر.

```cpp
virtual bool Aspose::Slides::IPresentationInfo::CheckPassword(System::String password)=0
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| password | [System::String](../../../system/string/) | رمز عبوری که باید بررسی شود. |

### مقدار بازگشت

True اگر ارائه با رمز عبور باز محافظت شده باشد و رمز عبور صحیح باشد و در غیر این صورت False.

## توضیحات

```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(u"pres.pptx");
bool isPasswordCorrect = info->CheckPassword(u"my_password");
```

هنگامی که رمز عبور مقدار null یا خالی باشد، این متد مقدار false را باز می‌گرداند.

## موارد مرتبط

* کلاس [String](../../../system/string/)
* کلاس [IPresentationInfo](../)
* فضای نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)