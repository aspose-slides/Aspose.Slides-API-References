---
title: get_IsWriteProtected()
second_title: Aspose.Slides برای C++ مرجع API
description: یک مقدار را برمی‌گرداند که نشان می‌دهد آیا ارائه بایند شده محافظت‌نوشتاری است.
type: docs
weight: 27
url: /fa/aspose.slides/ipresentationinfo/get_iswriteprotected/
---
## IPresentationInfo::get_IsWriteProtected() متد

یک مقدار را برمی‌گرداند که نشان می‌دهد آیا ارائه بایند شده محافظت‌نوشتاری است.

```cpp
virtual NullableBool Aspose::Slides::IPresentationInfo::get_IsWriteProtected()=0
```

## ملاحظات

```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(presentationFilePath);
if (info->get_IsWriteProtected() == NullableBool::True)
{
    System::Console::WriteLine(System::String(u"The presentation '") + presentationFilePath + u"' is write protected by a password.");
}
```

اگر ارائه با رمز عبور برای باز کردن محافظت شده باشد، مقدار ویژگی برابر NotDefined است. برای مشاهدهٔ شمارش [NullableBool](../../nullablebool/) مراجعه کنید.

## همچنین ببینید

* Enum [NullableBool](../../nullablebool/)
* کلاس [IPresentationInfo](../)
* فضای نام [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)