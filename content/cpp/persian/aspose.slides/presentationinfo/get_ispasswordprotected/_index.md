---
title: get_IsPasswordProtected()
second_title: مرجع API Aspose.Slides برای C++
description: یک مقدار را برمی‌گرداند که نشان می‌دهد آیا ارائهٔ بایند شده با رمز عبور برای باز کردن محافظت شده است.
type: docs
weight: 14
url: /fa/aspose.slides/presentationinfo/get_ispasswordprotected/
---
## PresentationInfo::get_IsPasswordProtected() متد


یک مقدار را بر می‌گرداند که نشان می‌دهد آیا ارائهٔ بایند شده با رمز عبور برای باز کردن محافظت شده است.

```cpp
bool Aspose::Slides::PresentationInfo::get_IsPasswordProtected() override
```

## توضییات



```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(presentationFilePath);
if (info->get_IsPasswordProtected())
{
    System::Console::WriteLine(System::String(u"The presentation '") + presentationFilePath + u"' is protected by password to open.");
}
```

## موارد مرتبط

* کلاس [PresentationInfo](../)
* فضای نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)