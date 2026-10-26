---
title: set_DeleteEmbeddedBinaryObjects()
second_title: Aspose.Slides สำหรับ API Reference ของ C++
description: กำหนดว่า Aspose.Slides จะลบวัตถุไบนารีที่ฝังทั้งหมดขณะโหลดการนำเสนอหรือไม่.
type: docs
weight: 352
url: /th/aspose.slides/loadoptions/set_deleteembeddedbinaryobjects/
---
## LoadOptions::set_DeleteEmbeddedBinaryObjects(bool) เมธอด


กำหนดว่า [Aspose.Slides](../../) จะลบวัตถุไบนารีที่ฝังทั้งหมดขณะโหลดการนำเสนอหรือไม่.

```cpp
void Aspose::Slides::LoadOptions::set_DeleteEmbeddedBinaryObjects(bool value) override
```

## หมายเหตุ


ประเภทของวัตถุไบนารีที่ฝังอยู่:

* VBA Project [IPresentation::VbaProject](../)
* OLE Object embedded data [IOleEmbeddedDataInfo::get_EmbeddedFileData](../../ioleembeddeddatainfo/get_embeddedfiledata/)
* ActiveX [Control](../../control/) ข้อมูลไบนารี [IControl::get_ActiveXControlBinary](../../icontrol/get_activexcontrolbinary/)


เขียน **bool**. 

ค่าเริ่มต้นคือ **false**. 

ตัวอย่างต่อไปนี้แสดงวิธีโหลดการนำเสนอโดยไม่รวมวัตถุไบนารีที่ฝังไว้ใด ๆ. 
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