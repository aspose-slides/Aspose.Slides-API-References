---
title: get_DeleteEmbeddedBinaryObjects()
second_title: مرجع API Aspose.Slides برای C++
description: تعیین می‌کند که آیا Aspose.Slides تمام اشیای باینری جاسازی‌شده را هنگام بارگذاری ارائه حذف خواهد کرد.
type: docs
weight: 339
url: /fa/aspose.slides/loadoptions/get_deleteembeddedbinaryobjects/
---
## LoadOptions::get_DeleteEmbeddedBinaryObjects() متد

تعیین می‌کند که آیا [Aspose.Slides](../../) تمام اشیای باینری جاسازی‌شده را هنگام بارگذاری ارائه حذف خواهد کرد.

```cpp
bool Aspose::Slides::LoadOptions::get_DeleteEmbeddedBinaryObjects() override
```

## نکات

انواع اشیای باینری جاسازی‌شده:

* VBA Project [IPresentation::VbaProject](../)
* OLE Object دادهٔ جاسازی‌شده [IOleEmbeddedDataInfo::get_EmbeddedFileData](../../ioleembeddeddatainfo/get_embeddedfiledata/)
* ActiveX [Control](../../control/) دادهٔ باینی [IControl::get_ActiveXControlBinary](../../icontrol/get_activexcontrolbinary/)

خواندنی **bool**. 

پیش‌فرض **false** است. 

مثال زیر نشان می‌دهد چگونه ارائه را بدون هیچ اشیای باینری جاسازی‌شده بارگذاری کنیم. 
```cpp
System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>();
loadOptions->set_DeleteEmbeddedBinaryObjects(true);

System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.ppt", loadOptions);
pres->Save(u"output_WithoutBinaryObjects.ppt", SaveFormat::Ppt);
```

## موارد مرتبط

* کلاس [LoadOptions](../)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)