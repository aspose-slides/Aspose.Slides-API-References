---
title: get_DeleteEmbeddedBinaryObjects()
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ C++
description: กำหนดว่า Aspose.Slides จะลบอ็อบเจ็กต์ไบเนอรีที่ฝังอยู่ทั้งหมดขณะโหลดการนำเสนอหรือไม่.
type: docs
weight: 339
url: /th/aspose.slides/iloadoptions/get_deleteembeddedbinaryobjects/
---
## ILoadOptions::get_DeleteEmbeddedBinaryObjects() เมธอด

Determines if [Aspose.Slides](../../) will delete all embedded binary objects while presentation loading.

```cpp
virtual bool Aspose::Slides::ILoadOptions::get_DeleteEmbeddedBinaryObjects()=0
```

## หมายเหตุ

The types of the embedded binary objects:

* VBA Project [IPresentation::VbaProject](../)
* OLE Object embedded data [IOleEmbeddedDataInfo::get_EmbeddedFileData](../../ioleembeddeddatainfo/get_embeddedfiledata/)
* ActiveX [Control](../../control/) binary data [IControl::get_ActiveXControlBinary](../../icontrol/get_activexcontrolbinary/)

Read **bool**. 

Default is **false**. 

The following example shows how to load the presentation without any embedded binary objects. 
```cpp
System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>();
loadOptions->set_DeleteEmbeddedBinaryObjects(true);

System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.ppt", loadOptions);
pres->Save(u"output_WithoutBinaryObjects.ppt", SaveFormat::Ppt);
```

## ดูเพิ่มเติม

* คลาส [ILoadOptions](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)