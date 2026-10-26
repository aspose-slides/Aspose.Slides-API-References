---
title: Encrypt()
second_title: مرجع API Aspose.Slides برای C++
description: Presentation را با رمز عبور مشخص رمزگذاری می‌کند.
type: docs
weight: 105
url: /fa/aspose.slides/protectionmanager/encrypt/
---
## ProtectionManager::Encrypt(System::String) متد


[Presentation](../../presentation/) را با رمز عبور مشخص رمزگذاری می‌کند.

```cpp
void Aspose::Slides::ProtectionManager::Encrypt(System::String encryptionPassword) override
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| encryptionPassword | [System::String](../../../system/string/) | رمز عبور. |
## توضیحات



کد نمونه زیر نشان می‌دهد چگونه یک [Presentation](../../presentation/) پاورپوینت را رمزگذاری کنید. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"pres.pptx");
presentation->get_ProtectionManager()->Encrypt(u"123123");
presentation->Save(u"encrypted-pres.pptx", SaveFormat::Pptx);
```

## موارد مرتبط

* کلاس [String](../../../system/string/)
* کلاس [ProtectionManager](../)
* فضای نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)