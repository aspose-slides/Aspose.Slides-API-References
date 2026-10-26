---
title: get_DeleteEmbeddedBinaryObjects()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يحدد ما إذا كان Aspose.Slides سيحذف جميع الكائنات الثنائية المضمنة أثناء تحميل العرض التقديمي.
type: docs
weight: 339
url: /ar/aspose.slides/loadoptions/get_deleteembeddedbinaryobjects/
---
## LoadOptions::get_DeleteEmbeddedBinaryObjects() الطريقة

يحدد ما إذا كان [Aspose.Slides](../../) سيحذف جميع الكائنات الثنائية المضمنة أثناء تحميل العرض التقديمي.

```cpp
bool Aspose::Slides::LoadOptions::get_DeleteEmbeddedBinaryObjects() override
```

## ملاحظات

أنواع الكائنات الثنائية المضمنة:

* مشروع VBA [IPresentation::VbaProject](../)
* بيانات كائن OLE المضمنة [IOleEmbeddedDataInfo::get_EmbeddedFileData](../../ioleembeddeddatainfo/get_embeddedfiledata/)
* ActiveX [Control](../../control/) بيانات ثنائية [IControl::get_ActiveXControlBinary](../../icontrol/get_activexcontrolbinary/)

قراءة **bool**. 

القيمة الافتراضية هي **false**. 

يوضح المثال التالي كيفية تحميل العرض التقديمي بدون أي كائنات ثنائية مدمجة. 
```cpp
System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>();
loadOptions->set_DeleteEmbeddedBinaryObjects(true);

System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.ppt", loadOptions);
pres->Save(u"output_WithoutBinaryObjects.ppt", SaveFormat::Ppt);
```

## انظر أيضًا

* الفئة [LoadOptions](../)
* النطاق [Aspose::Slides](../../)
* المكتبة [Aspose.Slides](../../../)