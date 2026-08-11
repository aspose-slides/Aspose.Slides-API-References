---
title: CheckPassword()
second_title: Aspose.Slides برای C++ مرجع API
description: بررسی می‌کند که آیا رمز عبور برای ارائه‌ای که با رمز عبور باز محافظت شده است صحیح است یا خیر.
type: docs
weight: 53
url: /fa/aspose.slides/presentationinfo/checkpassword/
---
## متد PresentationInfo::CheckPassword(System::String)

بررسی می‌کند که آیا رمز عبور برای ارائه‌ای که با رمز عبور باز محافظت شده است صحیح است یا خیر.

```cpp
bool Aspose::Slides::PresentationInfo::CheckPassword(System::String password) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| password | [System::String](../../../system/string/) | رمز عبوری که باید بررسی شود. |

### مقدار بازگشت

True اگر ارائه با رمز عبور باز محافظت شده باشد و رمز عبور صحیح باشد و در غیر این صورت False.

## نکات

```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(u"pres.pptx");
bool isPasswordCorrect = info->CheckPassword(u"my_password");
```

زمانی که رمز عبور null یا خالی باشد، این متد مقدار false را برمی‌گرداند.

## موارد مرتبط

* کلاس [String](../../../system/string/)
* کلاس [PresentationInfo](../)
* فضای نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)