---
title: set_DeleteEmbeddedBinaryObjects()
second_title: مرجع API الخاص بـ Aspose.Slides للغة C++
description: يحدد ما إذا كان Aspose.Slides سيحذف جميع الكائنات الثنائية المدمجة أثناء تحميل العرض التقديمي.
type: docs
weight: 352
url: /ar/aspose.slides/iloadoptions/set_deleteembeddedbinaryobjects/
---
## ILoadOptions::set_DeleteEmbeddedBinaryObjects(bool) طريقة

يحدد ما إذا كان [Aspose.Slides](../../) سيحذف جميع الكائنات الثنائية المدمجة أثناء تحميل العرض التقديمي.

```cpp
virtual void Aspose::Slides::ILoadOptions::set_DeleteEmbeddedBinaryObjects(bool value)=0
```

## ملاحظات

* VBA Project [IPresentation::VbaProject](../)
* OLE Object البيانات المضمَّنة [IOleEmbeddedDataInfo::get_EmbeddedFileData](../../ioleembeddeddatainfo/get_embeddedfiledata/)
* ActiveX [Control](../../control/) بيانات ثنائية [IControl::get_ActiveXControlBinary](../../icontrol/get_activexcontrolbinary/)

اكتب **bool**. 

القيمة الافتراضية هي **false**. 

يوضح المثال التالي كيفية تحميل العرض التقديمي دون أي كائنات ثنائية مدمجة. 
```cpp
System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>();
loadOptions->set_DeleteEmbeddedBinaryObjects(true);

System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.ppt", loadOptions);
pres->Save(u"output_WithoutBinaryObjects.ppt", SaveFormat::Ppt);
```

## أنظر أيضًا

* فئة [ILoadOptions](../)
* مساحة الأسماء [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)