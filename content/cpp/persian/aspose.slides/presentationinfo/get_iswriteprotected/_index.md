---
title: get_IsWriteProtected()
second_title: Aspose.Slides برای مرجع API C++
description: مقداری را برمی‌گرداند که نشان می‌دهد آیا ارائهٔ پیوند شده محافظت نوشتاری است.
type: docs
weight: 27
url: /fa/aspose.slides/presentationinfo/get_iswriteprotected/
---
## PresentationInfo::get_IsWriteProtected() متد

مقداری را بر می‌گرداند که نشان می‌دهد آیا ارائهٔ پیوند شده محافظت نوشتاری است.

```cpp
NullableBool Aspose::Slides::PresentationInfo::get_IsWriteProtected() override
```

## یادداشت‌ها



```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(presentationFilePath);
if (info->get_IsWriteProtected() == NullableBool::True)
{
    System::Console::WriteLine(System::String(u"The presentation '") + presentationFilePath + u"' is write protected by a password.");
}
```

اگر ارائه توسط رمز عبور برای باز کردن محافظت شود، مقدار ویژگی برابر با NotDefined است.

## موارد مرتبط

* Enum [NullableBool](../../nullablebool/)
* Class [PresentationInfo](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)