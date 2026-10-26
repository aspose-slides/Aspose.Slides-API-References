---
title: set_DeleteEmbeddedBinaryObjects()
second_title: Aspose.Slides สำหรับ C++ อ้างอิง API
description: กำหนดว่า Aspose.Slides จะลบวัตถุไบนารีที่ฝังอยู่ทั้งหมดขณะโหลดการนำเสนอหรือไม่.
type: docs
weight: 352
url: /th/aspose.slides/iloadoptions/set_deleteembeddedbinaryobjects/
---
## ILoadOptions::set_DeleteEmbeddedBinaryObjects(bool) method

กำหนดว่า [Aspose.Slides](../../) จะลบวัตถุไบนารีที่ฝังไว้ทั้งหมดขณะโหลดการนำเสนอหรือไม่.

```cpp
virtual void Aspose::Slides::ILoadOptions::set_DeleteEmbeddedBinaryObjects(bool value)=0
```

## หมายเหตุ

ประเภทของวัตถุไบนารีที่ฝังอยู่:

* โครงการ VBA [IPresentation::VbaProject](../)
* ข้อมูลที่ฝังของ OLE Object [IOleEmbeddedDataInfo::get_EmbeddedFileData](../../ioleembeddeddatainfo/get_embeddedfiledata/)
* ActiveX [Control](../../control/) ข้อมูลไบนารี [IControl::get_ActiveXControlBinary](../../icontrol/get_activexcontrolbinary/)

เขียน **bool**.

ค่าเริ่มต้นคือ **false**.

ตัวอย่างต่อไปนี้แสดงวิธีโหลดการนำเสนอโดยไม่มีวัตถุไบนารีที่ฝังอยู่. 
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