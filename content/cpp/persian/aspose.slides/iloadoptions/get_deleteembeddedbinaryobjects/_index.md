---
title: get_DeleteEmbeddedBinaryObjects()
second_title: مرجع API Aspose.Slides برای C++
description: مشخص می‌کند که آیا Aspose.Slides تمام اشیای باینری جاسازی‌شده را هنگام بارگذاری ارائه حذف خواهد کرد.
type: docs
weight: 339
url: /fa/aspose.slides/iloadoptions/get_deleteembeddedbinaryobjects/
---
## ILoadOptions::get_DeleteEmbeddedBinaryObjects() method

مشخص می‌کند که آیا [Aspose.Slides](../../) تمام اشیای باینری جاسازی‌شده را هنگام بارگذاری ارائه حذف خواهد کرد.

```cpp
virtual bool Aspose::Slides::ILoadOptions::get_DeleteEmbeddedBinaryObjects()=0
```

## توضیحات

انواع اشیای باینری جاسازی‌شده:

* پروژه VBA [IPresentation::VbaProject](../)
* داده‌های جاسازی‌شدهٔ شی OLE [IOleEmbeddedDataInfo::get_EmbeddedFileData](../../ioleembeddeddatainfo/get_embeddedfiledata/)
* ActiveX [Control](../../control/) داده‌های باینری [IControl::get_ActiveXControlBinary](../../icontrol/get_activexcontrolbinary/)

خواندن **bool**. 

پیش‌فرض **false** است. 

مثال زیر نشان می‌دهد چگونه ارائه را بدون هیچ‌یک از اشیای باینری جاسازی‌شده بارگذاری کنید. 
```cpp
System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>();
loadOptions->set_DeleteEmbeddedBinaryObjects(true);

System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.ppt", loadOptions);
pres->Save(u"output_WithoutBinaryObjects.ppt", SaveFormat::Ppt);
```

## موارد مرتبط

* کلاس [ILoadOptions](../)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)