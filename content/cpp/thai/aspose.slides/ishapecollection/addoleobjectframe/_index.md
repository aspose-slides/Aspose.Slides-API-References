---
title: AddOleObjectFrame()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: สร้างเฟรมอ็อบเจ็กต์ OLE ใหม่และเพิ่มเข้าไปที่ส่วนท้ายของคอลเลกชันรูปร่าง.
type: docs
weight: 66
url: /th/aspose.slides/ishapecollection/addoleobjectframe/
---
## IShapeCollection::AddOleObjectFrame(float, float, float, float, System::SharedPtr\<IOleEmbeddedDataInfo\>) เมธอด

สร้างเฟรมอ็อบเจ็กต์ OLE ใหม่และเพิ่มเข้าไปที่ส่วนท้ายของคอลเลกชันรูปร่าง

```cpp
virtual System::SharedPtr<IOleObjectFrame> Aspose::Slides::IShapeCollection::AddOleObjectFrame(float x, float y, float width, float height, System::SharedPtr<IOleEmbeddedDataInfo> dataInfo)=0
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | พิกัด x ของเฟรม OLE ใหม่, มีหน่วยเป็นจุด. |
| y | **float** | พิกัด y ของเฟรม OLE ใหม่, มีหน่วยเป็นจุด. |
| width | **float** | ความกว้างของเฟรม OLE ใหม่, มีหน่วยเป็นจุด. |
| height | **float** | ความสูงของเฟรม OLE ใหม่, มีหน่วยเป็นจุด. |
| dataInfo | [System::SharedPtr](../../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)\> | ข้อมูล OLE ที่ฝังไว้ ([IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)). |

### ค่าที่คืน

[IOleObjectFrame](../../ioleobjectframe/) ที่สร้างใหม่

## IShapeCollection::AddOleObjectFrame(float, float, float, float, System::String, System::String) เมธอด

สร้างเฟรมอ็อบเจ็กต์ OLE ใหม่และเพิ่มเข้าไปที่ส่วนท้ายของคอลเลกชันรูปร่าง

```cpp
virtual System::SharedPtr<IOleObjectFrame> Aspose::Slides::IShapeCollection::AddOleObjectFrame(float x, float y, float width, float height, System::String className, System::String path)=0
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | พิกัด x ของเฟรม OLE ใหม่, มีหน่วยเป็นจุด. |
| y | **float** | พิกัด y ของเฟรม OLE ใหม่, มีหน่วยเป็นจุด. |
| width | **float** | ความกว้างของเฟรม OLE ใหม่, มีหน่วยเป็นจุด. |
| height | **float** | ความสูงของเฟรม OLE ใหม่, มีหน่วยเป็นจุด. |
| className | [System::String](../../../system/string/) | ชื่อคลาสของอ็อบเจ็กต์ OLE. |
| path | [System::String](../../../system/string/) | เส้นทางไปยังไฟล์ที่เชื่อมโยง. |

### ค่าที่คืน

[IOleObjectFrame](../../ioleobjectframe/) ที่สร้างใหม่

## หมายเหตุ

เส้นทางนี้จะถูกเก็บไว้ตามตัวอักษรในงานนำเสนอ หากระบุเส้นทางแบบสัมพันธ์ ไฟล์จะไม่สามารถเข้าถึงได้เมื่อเปิดงานนำเสนอจากไดเรกทอรีอื่น.

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IOleObjectFrame](../../ioleobjectframe/)
* Class [IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)
* Class [IShapeCollection](../)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)