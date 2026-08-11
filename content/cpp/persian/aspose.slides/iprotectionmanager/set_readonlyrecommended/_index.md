---
title: set_ReadOnlyRecommended()
second_title: مرجع API Aspose.Slides برای C++ 
description: پیشنهاد فقط-خواندنی را تنظیم می‌کند. مقدار bool را می‌نویسد.
type: docs
weight: 92
url: /fa/aspose.slides/iprotectionmanager/set_readonlyrecommended/
---
## IProtectionManager::set_ReadOnlyRecommended(bool) متد


پیشنهاد فقط-خواندنی را تنظیم می‌کند. **bool** را می‌نویسد.

```cpp
virtual void Aspose::Slides::IProtectionManager::set_ReadOnlyRecommended(bool value)=0
```

## ملاحظات



```cpp
auto pres = System::MakeObject<Presentation>();
pres->get_ProtectionManager()->set_ReadOnlyRecommended(true);
pres->Save(u"ReadOnlyPresentation.pptx", SaveFormat::Pptx);
```

## مراجع

* کلاس [IProtectionManager](../)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)