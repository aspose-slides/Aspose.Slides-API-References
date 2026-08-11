---
title: set_RootDirectoryClsid()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يمثل GUID فئة الكائن (CLSID) المخزن في إدخال الدليل الجذر. يمكن استخدامه لتفعيل COM لتطبيق المستند. القيمة الافتراضية هي '64818D11-4F9B-11CF-86EA-00AA00B929E8' التي تتوافق مع 'Microsoft Powerpoint.Slide.8'.
type: docs
weight: 14
url: /ar/aspose.slides.export/pptoptions/set_rootdirectoryclsid/
---
## PptOptions::set_RootDirectoryClsid(System::Guid) طريقة


يمثل GUID فئة الكائن (CLSID) المخزن في إدخال الدليل الجذر. يمكن استخدامه لتفعيل COM لتطبيق المستند. القيمة الافتراضية هي '64818D11-4F9B-11CF-86EA-00AA00B929E8' التي تتوافق مع 'Microsoft Powerpoint.Slide.8'.

```cpp
void Aspose::Slides::Export::PptOptions::set_RootDirectoryClsid(System::Guid value) override
```

## ملاحظات



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<PptOptions> pptOptions = System::MakeObject<PptOptions>();

pptOptions->set_RootDirectoryClsid(System::Guid(u"64818D10-4F9B-11CF-86EA-00AA00B929E8"));

pres->Save(u"pres.ppt", Aspose::Slides::Export::SaveFormat::Ppt, pptOptions);
```




## انظر أيضاً

* الفئة [Guid](../../../system/guid/)
* الفئة [PptOptions](../)
* مساحة الاسم [Aspose::Slides::Export](../../)
* المكتبة [Aspose.Slides](../../../)