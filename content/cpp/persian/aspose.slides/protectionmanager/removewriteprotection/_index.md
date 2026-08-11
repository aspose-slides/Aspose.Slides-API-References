---
title: RemoveWriteProtection()
second_title: مرجع API Aspose.Slides برای C++
description: حفاظت نوشتاری این ارائه را حذف می‌کند.
type: docs
weight: 144
url: /fa/aspose.slides/protectionmanager/removewriteprotection/
---
## ProtectionManager::RemoveWriteProtection() روش


حفاظت نوشتاری این ارائه را حذف می‌کند.

```cpp
void Aspose::Slides::ProtectionManager::RemoveWriteProtection() override
```

## توضیحات


این کد نمونه نشان می‌دهد چگونه حفاظت نوشتاری را از یک PowerPoint [Presentation](../../presentation/) حذف کنید.
```cpp
auto presentation = System::MakeObject<Presentation>(u"pres.pptx");
presentation->get_ProtectionManager()->RemoveWriteProtection();
presentation->Save(u"write-protection-removed.pptx", SaveFormat::Pptx);
```

## موارد مرتبط

* کلاس [ProtectionManager](../)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)