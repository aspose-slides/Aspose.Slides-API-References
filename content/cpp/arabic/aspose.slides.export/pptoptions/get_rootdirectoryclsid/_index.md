---
title: get_RootDirectoryClsid()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: يمثل معرف فئة الكائن (GUID) (CLSID) المخزن في إدخال الدليل الجذري. يمكن استخدامه لتفعيل COM لتطبيق المستند. القيمة الافتراضية هي '64818D11-4F9B-11CF-86EA-00AA00B929E8' التي تتطابق مع 'Microsoft Powerpoint.Slide.8'.
type: docs
weight: 1
url: /ar/aspose.slides.export/pptoptions/get_rootdirectoryclsid/
---
## PptOptions::get_RootDirectoryClsid() طريقة

يمثل معرف فئة الكائن (GUID) (CLSID) المخزن في إدخال الدليل الجذري. يمكن استخدامه لتفعيل COM لتطبيق المستند. القيمة الافتراضية هي '64818D11-4F9B-11CF-86EA-00AA00B929E8' التي تتطابق مع 'Microsoft Powerpoint.Slide.8'.

```cpp
System::Guid Aspose::Slides::Export::PptOptions::get_RootDirectoryClsid() override
```

## ملاحظات



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<PptOptions> pptOptions = System::MakeObject<PptOptions>();

pptOptions->set_RootDirectoryClsid(System::Guid(u"64818D10-4F9B-11CF-86EA-00AA00B929E8"));

pres->Save(u"pres.ppt", Aspose::Slides::Export::SaveFormat::Ppt, pptOptions);
```




## انظر أيضًا

* الفئة [Guid](../../../system/guid/)
* الفئة [PptOptions](../)
* النطاق [Aspose::Slides::Export](../../)
* المكتبة [Aspose.Slides](../../../)