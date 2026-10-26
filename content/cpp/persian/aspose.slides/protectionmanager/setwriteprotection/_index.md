---
title: SetWriteProtection()
second_title: Aspose.Slides برای مرجع API C++
description: محافظت نوشتن این ارائه را با گذرواژهٔ مشخص تنظیم می‌کند.
type: docs
weight: 131
url: /fa/aspose.slides/protectionmanager/setwriteprotection/
---
## ProtectionManager::SetWriteProtection(System::String) متد

محافظت نوشتن برای این ارائه را با گذرواژهٔ مشخص تنظیم می‌کند.

```cpp
void Aspose::Slides::ProtectionManager::SetWriteProtection(System::String password) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| password | [System::String](../../../system/string/) | گذرواژه. |

## ملاحظات

کد نمونهٔ زیر نشان می‌دهد چگونه محافظت نوشتن را برای یک ارائه تنظیم کنید.
```cpp
auto presentation = System::MakeObject<Presentation>(u"pres.pptx");
presentation->get_ProtectionManager()->SetWriteProtection(u"123123");
presentation->Save(u"write-protected-pres.pptx", SaveFormat::Pptx);
```

## مراجع

* کلاس [String](../../../system/string/)
* کلاس [ProtectionManager](../)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)