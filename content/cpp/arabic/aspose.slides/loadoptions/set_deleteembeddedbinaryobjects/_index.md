---
title: set_DeleteEmbeddedBinaryObjects()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يحدد ما إذا كان Aspose.Slides سيحذف جميع الكائنات الثنائية المضمَّنة أثناء تحميل العرض التقديمي.
type: docs
weight: 352
url: /ar/aspose.slides/loadoptions/set_deleteembeddedbinaryobjects/
---
## LoadOptions::set_DeleteEmbeddedBinaryObjects(bool) طريقة

يحدد ما إذا كان [Aspose.Slides](../../) سيحذف جميع الكائنات الثنائية المضمنة أثناء تحميل العرض التقديمي.

```cpp
void Aspose::Slides::LoadOptions::set_DeleteEmbeddedBinaryObjects(bool value) override
```

## ملاحظات

أنواع الكائنات الثنائية المضمنة:

* VBA Project [IPresentation::VbaProject](../)
* OLE Object embedded data [IOleEmbeddedDataInfo::get_EmbeddedFileData](../../ioleembeddeddatainfo/get_embeddedfiledata/)
* ActiveX [Control](../../control/) binary data [IControl::get_ActiveXControlBinary](../../icontrol/get_activexcontrolbinary/)

اكتب **bool**. 

القيمة الافتراضية هي **false**. 

يوضح المثال التالي كيفية تحميل العرض التقديمي دون أي كائنات ثنائية مضمَّنة. 
```cpp
System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>();
loadOptions->set_DeleteEmbeddedBinaryObjects(true);

System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.ppt", loadOptions);
pres->Save(u"output_WithoutBinaryObjects.ppt", SaveFormat::Ppt);
```

## انظر أيضًا

* فئة [LoadOptions](../)
* نطاق [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)