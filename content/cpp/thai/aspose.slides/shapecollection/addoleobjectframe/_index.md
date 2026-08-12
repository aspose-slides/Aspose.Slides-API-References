---
title: AddOleObjectFrame()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: สร้างเฟรมอ็อบเจ็กต์ OLE ใหม่และเพิ่มไปยังส่วนท้ายของคอลเลกชันรูปร่าง.
type: docs
weight: 183
url: /th/aspose.slides/shapecollection/addoleobjectframe/
---
## ShapeCollection::AddOleObjectFrame(float, float, float, float, System::SharedPtr\<IOleEmbeddedDataInfo\>) เมธอด


สร้างเฟรมอ็อบเจ็กต์ OLE ใหม่และเพิ่มไปยังส่วนท้ายของคอลเลกชันรูปร่าง

```cpp
System::SharedPtr<IOleObjectFrame> Aspose::Slides::ShapeCollection::AddOleObjectFrame(float x, float y, float width, float height, System::SharedPtr<IOleEmbeddedDataInfo> dataInfo) override
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| x | **float** | พิกัด x ของเฟรม OLE ใหม่ หน่วยเป็นจุด |
| y | **float** | พิกัด y ของเฟรม OLE ใหม่ หน่วยเป็นจุด |
| width | **float** | ความกว้างของเฟรม OLE ใหม่ หน่วยเป็นจุด |
| height | **float** | ความสูงของเฟรม OLE ใหม่ หน่วยเป็นจุด |
| dataInfo | [System::SharedPtr](../../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)\> | ข้อมูลเกี่ยวกับข้อมูล OLE ที่ฝังไว้ ([IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)) |

### ค่าที่คืนกลับ

ออบเจ็กต์ [IOleObjectFrame](../../ioleobjectframe/) ที่สร้างใหม่

## หมายเหตุ



ตัวอย่างต่อไปนี้แสดงวิธีการเพิ่มเฟรมอ็อบเจ็กต์ OLE ไปยัง [Slides](../../) ของ PowerPoint [Presentation](../../presentation/) 
```cpp
auto pres = System::MakeObject<Presentation>();

// เข้าถึงสไลด์แรก
auto slide = pres->get_Slides()->idx_get(0);
// โหลดไฟล์ Excel ไปยังสตรีม
System::SharedPtr<System::IO::MemoryStream> mstream = System::MakeObject<System::IO::MemoryStream>();
auto fs = System::MakeObject<System::IO::FileStream>(u"book1.xlsx", System::IO::FileMode::Open, System::IO::FileAccess::Read);

System::ArrayPtr<uint8_t> buf = System::MakeArray<uint8_t>(4096, 0);
while (true)
{
    int32_t bytesRead = fs->Read(buf, 0, buf->get_Length());
    if (bytesRead <= 0)
    {
        break;
    }
    mstream->Write(buf, 0, bytesRead);
}

// สร้างอ็อบเจ็กต์ข้อมูลสำหรับฝัง
auto dataInfo = System::MakeObject<OleEmbeddedDataInfo>(mstream->ToArray(), u"xlsx");
// เพิ่มรูปร่าง Ole Object Frame
auto slideSize = pres->get_SlideSize()->get_Size();
auto oleObjectFrame = slide->get_Shapes()->AddOleObjectFrame(0.0f, 0.0f, slideSize.get_Width(), slideSize.get_Height(), dataInfo);
// เขียนไฟล์ PPTX ลงดิสก์
pres->Save(u"OleEmbed_out.pptx", SaveFormat::Pptx);
```

## ShapeCollection::AddOleObjectFrame(float, float, float, float, System::String, System::String) เมธอด


สร้างเฟรมอ็อบเจ็กต์ OLE ใหม่และเพิ่มไปยังส่วนท้ายของคอลเลกชันรูปร่าง

```cpp
System::SharedPtr<IOleObjectFrame> Aspose::Slides::ShapeCollection::AddOleObjectFrame(float x, float y, float width, float height, System::String className, System::String path) override
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| x | **float** | พิกัด x ของเฟรม OLE ใหม่ หน่วยเป็นจุด |
| y | **float** | พิกัด y ของเฟรม OLE ใหม่ หน่วยเป็นจุด |
| width | **float** | ความกว้างของเฟรม OLE ใหม่ หน่วยเป็นจุด |
| height | **float** | ความสูงของเฟรม OLE ใหม่ หน่วยเป็นจุด |
| className | [System::String](../../../system/string/) | ชื่อคลาสของอ็อบเจ็กต์ OLE |
| path | [System::String](../../../system/string/) | เส้นทางไปยังไฟล์ที่เชื่อมโยง |

### ค่าที่คืนกลับ

ออบเจ็กต์ [IOleObjectFrame](../../ioleobjectframe/) ที่สร้างใหม่

## หมายเหตุ



เส้นทางนี้จะถูกเก็บไว้ตามเดิมในงานนำเสนอ หากระบุเส้นทางแบบสัมพันธ์ ไฟล์จะไม่สามารถเข้าถึงได้เมื่อเปิดงานนำเสนอจากไดเรกทอรีที่แตกต่าง

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IOleObjectFrame](../../ioleobjectframe/)
* Class [IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)
* Class [ShapeCollection](../)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)