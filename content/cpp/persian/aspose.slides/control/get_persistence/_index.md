---
title: get_Persistence()
second_title: Aspose.Slides برای مرجع API C++
description: متد مورد استفاده برای ذخیره‌سازی ویژگی‌های کنترل ActiveX را دریافت می‌کند. فقط-خواندنی PersistenceType.
type: docs
weight: 1
url: /fa/aspose.slides/control/get_persistence/
---
## Control::get_Persistence() متد

متد مورد استفاده برای ذخیره‌سازی ویژگی‌های کنترل ActiveX را دریافت می‌کند. فقط-خواندنی [PersistenceType](../../persistencetype/).

```cpp
PersistenceType Aspose::Slides::Control::get_Persistence() override
```

## توضیحات

مثال بعدی نحوه استفاده از ویژگی Persistence را برای بررسی این که آیا ویژگی‌های شیء ActiveX می‌توانند به‌صورت ویژگی‌های ActiveX مبتنی بر XML تغییر یابند، نشان می‌دهد:
```cpp
if (control->get_Persistence() == PersistenceType::PersistPropertyBag)
{
    control->get_Properties()->idx_set(u"Value", value);
}
else
{
    // برای مدیریت ویژگی‌های ActiveX که در فایل باینری آن ذخیره شده‌اند، روش خود را استفاده کنید
    YourMethodHere(control->get_ActiveXControlBinary());
}
```

## موارد مرتبط

* Enum [PersistenceType](../../persistencetype/)
* کلاس [Control](../)
* فضای نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)