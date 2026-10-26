---
title: set_DeleteEmbeddedBinaryObjects()
second_title: Aspose.Slides برای مرجع API C++
description: تشخیص می‌دهد که آیا Aspose.Slides تمام اشیاء باینری جاسازی‌شده را هنگام بارگذاری ارائه حذف می‌کند.
type: docs
weight: 352
url: /fa/aspose.slides/iloadoptions/set_deleteembeddedbinaryobjects/
---
## ILoadOptions::set_DeleteEmbeddedBinaryObjects(bool) متد

تشخیص می‌دهد که آیا [Aspose.Slides](../../) تمام اشیاء باینری جاسازی‌شده را هنگام بارگذاری ارائه حذف می‌کند یا خیر.

```cpp
virtual void Aspose::Slides::ILoadOptions::set_DeleteEmbeddedBinaryObjects(bool value)=0
```

## توضیحات

انواع اشیاء باینری جاسازی‌شده:

* VBA Project [IPresentation::VbaProject](../)
* OLE Object embedded data [IOleEmbeddedDataInfo::get_EmbeddedFileData](../../ioleembeddeddatainfo/get_embeddedfiledata/)
* ActiveX [Control](../../control/) داده باینری [IControl::get_ActiveXControlBinary](../../icontrol/get_activexcontrolbinary/)

نوشتن **bool**.

مقدار پیش‌فرض **false** است.

مثال زیر نشان می‌دهد چگونه ارائه را بدون هیچ شی باینری جاسازی‌شده‌ای بارگذاری کنید.
```cpp
System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>();
loadOptions->set_DeleteEmbeddedBinaryObjects(true);

System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.ppt", loadOptions);
pres->Save(u"output_WithoutBinaryObjects.ppt", SaveFormat::Ppt);
```

## موارد مرتبط

* Class [ILoadOptions](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)