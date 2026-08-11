---
title: get_ReadOnlyRecommended()
second_title: مرجع API Aspose.Slides برای C++
description: توصیهٔ فقط-خواندنی را دریافت می‌کند. مقدار bool را می‌خواند.
type: docs
weight: 79
url: /fa/aspose.slides/protectionmanager/get_readonlyrecommended/
---
## ProtectionManager::get_ReadOnlyRecommended() متد


توصیهٔ فقط-خواندنی را می‌گیرد. خواندن **bool**.

```cpp
bool Aspose::Slides::ProtectionManager::get_ReadOnlyRecommended() override
```

## توضیحات


کد نمونهٔ زیر نشان می‌دهد چگونه یک PowerPoint [Presentation](../../presentation/) را با استفاده از [Aspose.Slides](../../) در C# به حالت فقط-خواندنی تنظیم کنید. 
```cpp
auto pres = System::MakeObject<Presentation>();
pres->get_ProtectionManager()->set_ReadOnlyRecommended(true);
pres->Save(u"ReadOnlyPresentation.pptx", SaveFormat::Pptx);
```

## مراجع

* کلاس [ProtectionManager](../)
* فضای نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)