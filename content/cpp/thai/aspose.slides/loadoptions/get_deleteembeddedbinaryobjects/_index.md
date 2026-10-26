---
title: get_DeleteEmbeddedBinaryObjects()
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ C++
description: กำหนดว่า Aspose.Slides จะลบวัตถุไบนารีฝังทั้งหมดขณะโหลดงานนำเสนอหรือไม่.
type: docs
weight: 339
url: /th/aspose.slides/loadoptions/get_deleteembeddedbinaryobjects/
---
## LoadOptions::get_DeleteEmbeddedBinaryObjects() เมธอด

กำหนดว่า [Aspose.Slides](../../) จะลบวัตถุไบนารีฝังทั้งหมดขณะโหลดงานนำเสนอหรือไม่.

```cpp
bool Aspose::Slides::LoadOptions::get_DeleteEmbeddedBinaryObjects() override
```

## หมายเหตุ

ประเภทของวัตถุไบนารีฝัง:

* VBA Project [IPresentation::VbaProject](../)
* OLE Object embedded data [IOleEmbeddedDataInfo::get_EmbeddedFileData](../../ioleembeddeddatainfo/get_embeddedfiledata/)
* ActiveX [Control](../../control/) binary data [IControl::get_ActiveXControlBinary](../../icontrol/get_activexcontrolbinary/)

อ่าน **bool**. 

ค่าเริ่มต้นคือ **false**. 

ตัวอย่างต่อไปนี้แสดงวิธีโหลดงานนำเสนอโดยไม่มีวัตถุไบนารีฝังใด ๆ. 
```cpp
System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>();
loadOptions->set_DeleteEmbeddedBinaryObjects(true);

System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.ppt", loadOptions);
pres->Save(u"output_WithoutBinaryObjects.ppt", SaveFormat::Ppt);
```

## ดูเพิ่มเติม

* คลาส [LoadOptions](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)