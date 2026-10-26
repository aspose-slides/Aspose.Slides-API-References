---
title: Encrypt()
second_title: Aspose.Slides لواجهة برمجة التطبيقات (API) للغة C++
description: يقوم بتشفير العرض التقديمي باستخدام كلمة مرور محددة.
type: docs
weight: 105
url: /ar/aspose.slides/protectionmanager/encrypt/
---
## ProtectionManager::Encrypt(System::String) طريقة


يقوم بتشفير [Presentation](../../presentation/) باستخدام كلمة مرور محددة.

```cpp
void Aspose::Slides::ProtectionManager::Encrypt(System::String encryptionPassword) override
```


### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| encryptionPassword | [System::String](../../../system/string/) | كلمة المرور. |
## ملاحظات



يعرض لك نموذج الشيفرة التالي كيفية تشفير ملف PowerPoint [Presentation](../../presentation/). 
```cpp
auto presentation = System::MakeObject<Presentation>(u"pres.pptx");
presentation->get_ProtectionManager()->Encrypt(u"123123");
presentation->Save(u"encrypted-pres.pptx", SaveFormat::Pptx);
```

## انظر أيضاً

* الفئة [String](../../../system/string/)
* الفئة [ProtectionManager](../)
* مساحة الأسماء [Aspose::Slides](../../)
* المكتبة [Aspose.Slides](../../../)