---
title: SetEmbeddedData()
second_title: Aspose.Slides สำหรับเอกสารอ้างอิง API ของ C++
description: ตั้งค่าข้อมูลเกี่ยวกับ OLE embedded data.
type: docs
weight: 248
url: /th/aspose.slides/ioleobjectframe/setembeddeddata/
---
## IOleObjectFrame::SetEmbeddedData(System::SharedPtr\<IOleEmbeddedDataInfo\>) เมธอด


ตั้งค่าข้อมูลเกี่ยวกับ OLE embedded data

```cpp
virtual void Aspose::Slides::IOleObjectFrame::SetEmbeddedData(System::SharedPtr<IOleEmbeddedDataInfo> embeddedData)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| embeddedData | [System::SharedPtr](../../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)\> | ข้อมูลที่ฝังอยู่ [IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/) |
## Remarks


เมธอดนี้จะเปลี่ยนแปลงคุณสมบัติของอ็อบเจกต์ให้สอดคล้องกับข้อมูลใหม่และตั้งค่า IsObjectLink flag เป็น false เพื่อระบุว่า OLE object ถูกฝังอยู่


ตัวอย่างต่อไปนี้แสดงวิธีการเปลี่ยน OLE embedded data และประเภทของมันสำหรับอ็อบเจกต์ [IOleObjectFrame](../) ที่มีอยู่แล้ว
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"SomePresentation.pptx");

System::SharedPtr<OleObjectFrame> oof = System::AsCast<Aspose::Slides::OleObjectFrame>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
if (oof != nullptr)
{
    System::SharedPtr<IOleEmbeddedDataInfo> newData = System::MakeObject<OleEmbeddedDataInfo>(System::IO::File::ReadAllBytes(u"Picture.png"), u"png");
    oof->SetEmbeddedData(newData);
}
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)
* คลาส [IOleObjectFrame](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)