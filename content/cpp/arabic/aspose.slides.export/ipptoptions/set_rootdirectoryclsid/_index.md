---
title: set_RootDirectoryClsid()
second_title: Aspose.Slides للـ C++ مرجع API
description: يمثل GUID لفئة الكائن (CLSID) المخزن في إدخال الدليل الجذر. يمكن استخدامه لتفعيل COM لتطبيق المستند. القيمة الافتراضية هي '64818D11-4F9B-11CF-86EA-00AA00B929E8' التي تقابل 'Microsoft Powerpoint.Slide.8'.
type: docs
weight: 14
url: /ar/aspose.slides.export/ipptoptions/set_rootdirectoryclsid/
---
## IPptOptions::set_RootDirectoryClsid(System::Guid) طريقة

يمثل معرّف GUID لفئة الكائن (CLSID) المخزن في إدخال الدليل الجذر. يمكن استخدامه لتفعيل COM لتطبيق المستند. القيمة الافتراضية هي '64818D11-4F9B-11CF-86EA-00AA00B929E8' التي تقابل 'Microsoft Powerpoint.Slide.8'.

```cpp
virtual void Aspose::Slides::Export::IPptOptions::set_RootDirectoryClsid(System::Guid value)=0
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
* الفئة [IPptOptions](../)
* النطاق [Aspose::Slides::Export](../../)
* المكتبة [Aspose.Slides](../../../)