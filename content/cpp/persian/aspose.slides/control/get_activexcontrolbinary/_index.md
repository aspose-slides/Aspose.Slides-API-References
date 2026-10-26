---
title: get_ActiveXControlBinary()
second_title: Aspose.Slides برای C++ مرجع API
description: پایداری یک کنترل ActiveX را مشخص می‌کند زمانی که روش استفاده‌شده برای حفظ، یا PersistStream، PersistStreamInit یا PersistStorage باشد.
type: docs
weight: 118
url: /fa/aspose.slides/control/get_activexcontrolbinary/
---
## Control::get_ActiveXControlBinary() متد

پایداری یک کنترل ActiveX را هنگامی که متد مورد استفاده برای حفظ، یا PersistStream یا PersistStreamInit یا PersistStorage باشد، مشخص می‌کند.

```cpp
System::ArrayPtr<uint8_t> Aspose::Slides::Control::get_ActiveXControlBinary() override
```

## یادداشت‌ها


مثال بعدی استفاده از ویژگی ActiveXControlBinary را برای تغییر ویژگی‌های ActiveX نشان می‌دهد: 
```cpp
if (control->get_Persistence() == PersistenceType::PersistPropertyBag)
{
    control->get_Properties()->idx_set(u"Value", value);
}
else
{
    // برای مدیریت ویژگی‌های ActiveX که در فایل باینری آن ذخیره شده‌اند، از روش خود استفاده کنید
    YourMethodHere(control->get_ActiveXControlBinary());
}
```

## موارد مرتبط

* تعریف‌نوع [ArrayPtr](../../../system/arrayptr/)
* کلاس [Control](../)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)