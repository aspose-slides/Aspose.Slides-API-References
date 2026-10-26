---
title: set_DeleteEmbeddedBinaryObjects()
second_title: مرجع API Aspose.Slides برای C++
description: مشخص می‌کند که آیا Aspose.Slides تمام اشیای باینری جاسازی‌شده را هنگام بارگذاری ارائه حذف خواهد کرد.
type: docs
weight: 352
url: /fa/aspose.slides/loadoptions/set_deleteembeddedbinaryobjects/
---
## LoadOptions::set_DeleteEmbeddedBinaryObjects(bool) متد

مشخص می‌کند که آیا [Aspose.Slides](../../) تمام اشیای باینری جاسازی‌شده را هنگام بارگذاری ارائه حذف خواهد کرد.

```cpp
void Aspose::Slides::LoadOptions::set_DeleteEmbeddedBinaryObjects(bool value) override
```

## توضیحات

انواع اشیای باینری جاسازی‌شده:

* VBA Project [IPresentation::VbaProject](../)
* OLE Object embedded data [IOleEmbeddedDataInfo::get_EmbeddedFileData](../../ioleembeddeddatainfo/get_embeddedfiledata/)
* ActiveX [Control](../../control/) binary data [IControl::get_ActiveXControlBinary](../../icontrol/get_activexcontrolbinary/)

نوشتن **bool**. 

پیش‌فرض **false** است. 

مثال زیر نشان می‌دهد که چگونه ارائه را بدون هیچ شی باینری جاسازی‌شده‌ای بارگذاری کنید. 
```cpp
System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>();
loadOptions->set_DeleteEmbeddedBinaryObjects(true);

System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.ppt", loadOptions);
pres->Save(u"output_WithoutBinaryObjects.ppt", SaveFormat::Ppt);
```

## مراجع

* کلاس [LoadOptions](../)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)