---
title: InsertOleObjectFrame()
second_title: Aspose.Slides สำหรับ C++ อ้างอิง API
description: สร้างเฟรมอ็อบเจ็กต์ OLE ใหม่และแทรกลงในคอลเลกชันรูปทรงที่ดัชนีที่ระบุ
type: docs
weight: 79
url: /th/aspose.slides/ishapecollection/insertoleobjectframe/
---
## IShapeCollection::InsertOleObjectFrame(int32_t, float, float, float, float, System::SharedPtr\<IOleEmbeddedDataInfo\>) เมธอด


สร้างเฟรมอ็อบเจ็กต์ OLE ใหม่และแทรกลงในคอลเลกชันรูปทรงที่ดัชนีที่ระบุ

```cpp
virtual System::SharedPtr<IOleObjectFrame> Aspose::Slides::IShapeCollection::InsertOleObjectFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<IOleEmbeddedDataInfo> dataInfo)=0
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| index | **int32_t** | ดัชนีเริ่มจากศูนย์ที่ใช้แทรกเฟรมอ็อบเจ็กต์ OLE |
| x | **float** | พิกัด x ของเฟรม OLE ใหม่, หน่วยเป็นจุด |
| y | **float** | พิกัด y ของเฟรม OLE ใหม่, หน่วยเป็นจุด |
| width | **float** | ความกว้างของเฟรม OLE ใหม่, หน่วยเป็นจุด |
| height | **float** | ความสูงของเฟรม OLE ใหม่, หน่วยเป็นจุด |
| dataInfo | [System::SharedPtr](../../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)\> | ข้อมูล OLE ที่ฝังไว้ ([IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)) |

### ค่าที่ส่งคืน

[IOleObjectFrame](../../ioleobjectframe/) ที่สร้างใหม่

## IShapeCollection::InsertOleObjectFrame(int32_t, float, float, float, float, System::String, System::String) เมธอด


สร้างเฟรมอ็อบเจ็กต์ OLE ใหม่และแทรกลงในคอลเลกชันรูปทรงที่ดัชนีที่ระบุ

```cpp
virtual System::SharedPtr<IOleObjectFrame> Aspose::Slides::IShapeCollection::InsertOleObjectFrame(int32_t index, float x, float y, float width, float height, System::String className, System::String path)=0
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| index | **int32_t** | ดัชนีเริ่มจากศูนย์ที่ใช้แทรกเฟรมอ็อบเจ็กต์ OLE |
| x | **float** | พิกัด x ของเฟรม OLE ใหม่, หน่วยเป็นจุด |
| y | **float** | พิกัด y ของเฟรม OLE ใหม่, หน่วยเป็นจุด |
| width | **float** | ความกว้างของเฟรม OLE ใหม่, หน่วยเป็นจุด |
| height | **float** | ความสูงของเฟรม OLE ใหม่, หน่วยเป็นจุด |
| className | [System::String](../../../system/string/) | ชื่อคลาสของอ็อบเจ็กต์ OLE |
| path | [System::String](../../../system/string/) | พาธไปยังไฟล์ที่เชื่อมโยง |

### ค่าที่ส่งคืน

[IOleObjectFrame](../../ioleobjectframe/) ที่สร้างใหม่

## หมายเหตุ



พาธนี้จะถูกจัดเก็บตามที่เป็นในงานนำเสนอ หากระบุพาธสัมพัทธ์ ไฟล์จะไม่สามารถเข้าถึงได้เมื่อเปิดงานนำเสนอจากไดเรกทอรีที่แตกต่าง

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IOleObjectFrame](../../ioleobjectframe/)
* คลาส [IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)
* คลาส [IShapeCollection](../)
* คลาส [String](../../../system/string/)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)