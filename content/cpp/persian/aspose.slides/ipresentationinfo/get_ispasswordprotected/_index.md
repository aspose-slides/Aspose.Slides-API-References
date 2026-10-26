---
title: get_IsPasswordProtected()
second_title: Aspose.Slides برای C++ مرجع API
description: یک مقدار بر می‌گرداند که نشان می‌دهد آیا ارائهٔ بایند شده با گذرواژه برای باز شدن محافظت شده است.
type: docs
weight: 14
url: /fa/aspose.slides/ipresentationinfo/get_ispasswordprotected/
---
## IPresentationInfo::get_IsPasswordProtected() متد

یک مقدار را بر می‌گرداند که نشان می‌دهد آیا ارائهٔ بایند شده با گذرواژه برای باز شدن محافظت شده است.

```cpp
virtual bool Aspose::Slides::IPresentationInfo::get_IsPasswordProtected()=0
```

## توضیحات

```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(presentationFilePath);
if (info->get_IsPasswordProtected())
{
    System::Console::WriteLine(System::String(u"The presentation '") + presentationFilePath + u"' is protected by a password to open.");
}
```

## مشاهده کنید

* کلاس [IPresentationInfo](../)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)