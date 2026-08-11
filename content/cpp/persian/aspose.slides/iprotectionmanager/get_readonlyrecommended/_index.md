---
title: get_ReadOnlyRecommended()
second_title: Aspose.Slides برای C++ مرجع API
description: دریافت می‌کند توصیه فقط-خواندنی. خواندن bool.
type: docs
weight: 79
url: /fa/aspose.slides/iprotectionmanager/get_readonlyrecommended/
---
## IProtectionManager::get_ReadOnlyRecommended() متد


دریافت می‌کند توصیه فقط-خواندنی. خواندن **bool**.

```cpp
virtual bool Aspose::Slides::IProtectionManager::get_ReadOnlyRecommended()=0
```

## توضیحات



```cpp
auto pres = System::MakeObject<Presentation>();
pres->get_ProtectionManager()->set_ReadOnlyRecommended(true);
pres->Save(u"ReadOnlyPresentation.pptx", SaveFormat::Pptx);
```

## مراجع

* کلاس [IProtectionManager](../)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)