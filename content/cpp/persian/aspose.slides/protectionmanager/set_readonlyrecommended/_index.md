---
title: set_ReadOnlyRecommended()
second_title: مرجع API Aspose.Slides برای C++
description: توصیه فقط-خواندنی را تنظیم می‌کند. مقدار bool را می‌نویسد.
type: docs
weight: 92
url: /fa/aspose.slides/protectionmanager/set_readonlyrecommended/
---
## ProtectionManager::set_ReadOnlyRecommended(bool) متد

توصیه فقط-خواندنی را تنظیم می‌کند. مقدار **bool** را می‌نویسد.

```cpp
void Aspose::Slides::ProtectionManager::set_ReadOnlyRecommended(bool value) override
```

## توضیحات

کد نمونه زیر نشان می‌دهد چگونه یک PowerPoint [Presentation](../../presentation/) را در C# با استفاده از [Aspose.Slides](../../) به حالت فقط-خواندنی تنظیم کنید. 
```cpp
auto pres = System::MakeObject<Presentation>();
pres->get_ProtectionManager()->set_ReadOnlyRecommended(true);
pres->Save(u"ReadOnlyPresentation.pptx", SaveFormat::Pptx);
```

## موارد مرتبط

* کلاس [ProtectionManager](../)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)