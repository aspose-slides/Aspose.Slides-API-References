---
title: get_DeleteEmbeddedBinaryObjects()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: يحدد ما إذا كان Aspose.Slides سيحذف جميع الكائنات الثنائية المضمنة أثناء تحميل العرض التقديمي.
type: docs
weight: 339
url: /ar/aspose.slides/iloadoptions/get_deleteembeddedbinaryobjects/
---
## ILoadOptions::get_DeleteEmbeddedBinaryObjects() طريقة

يحدد ما إذا كان [Aspose.Slides](../../) سيحذف جميع الكائنات الثنائية المضمنة أثناء تحميل العرض التقديمي.

```cpp
virtual bool Aspose::Slides::ILoadOptions::get_DeleteEmbeddedBinaryObjects()=0
```

## ملاحظات

أنواع الكائنات الثنائية المضمنة:

* VBA مشروع [IPresentation::VbaProject](../)
* بيانات كائن OLE المضمنة [IOleEmbeddedDataInfo::get_EmbeddedFileData](../../ioleembeddeddatainfo/get_embeddedfiledata/)
* ActiveX [Control](../../control/) البيانات الثنائية [IControl::get_ActiveXControlBinary](../../icontrol/get_activexcontrolbinary/)

قراءة **bool**.

الافتراضي هو **false**.

يوضح المثال التالي كيفية تحميل العرض التقديمي دون أي كائنات ثنائية مضمّنة.
```cpp
System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>();
loadOptions->set_DeleteEmbeddedBinaryObjects(true);

System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.ppt", loadOptions);
pres->Save(u"output_WithoutBinaryObjects.ppt", SaveFormat::Ppt);
```

## انظر أيضاً

* الفئة [ILoadOptions](../)
* مساحة الاسم [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)