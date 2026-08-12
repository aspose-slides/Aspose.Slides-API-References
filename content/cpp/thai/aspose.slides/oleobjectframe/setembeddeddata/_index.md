---
title: SetEmbeddedData()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ตั้งค่าข้อมูลเกี่ยวกับข้อมูล OLE ที่ฝังไว้.
type: docs
weight: 248
url: /th/aspose.slides/oleobjectframe/setembeddeddata/
---
## OleObjectFrame::SetEmbeddedData(System::SharedPtr\<IOleEmbeddedDataInfo\>) เมธอด

ตั้งค่าข้อมูลเกี่ยวกับข้อมูล OLE ที่ฝังไว้.

```cpp
void Aspose::Slides::OleObjectFrame::SetEmbeddedData(System::SharedPtr<IOleEmbeddedDataInfo> embeddedData) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| embeddedData | [System::SharedPtr](../../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)\> | ข้อมูลที่ฝัง [IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/) |
## หมายเหตุ

เมธอดนี้จะเปลี่ยนแปลงคุณสมบัติของอ็อบเจกต์เพื่อสะท้อนข้อมูลใหม่และตั้งค่าแฟล็ก IsObjectLink เป็น false ซึ่งบ่งบอกว่าอ็อบเจกต์ OLE ถูกฝังไว้.



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"SomePresentation.pptx");

System::SharedPtr<OleObjectFrame> oof = System::AsCast<Aspose::Slides::OleObjectFrame>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
if (oof != nullptr)
{
    System::SharedPtr<IOleEmbeddedDataInfo> newData = System::MakeObject<OleEmbeddedDataInfo>(System::IO::File::ReadAllBytes(u"Picture.png"), u"png");
    oof->SetEmbeddedData(newData);
}
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)
* คลาส [OleObjectFrame](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)