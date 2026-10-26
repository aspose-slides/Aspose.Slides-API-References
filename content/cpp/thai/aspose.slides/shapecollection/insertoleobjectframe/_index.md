---
title: InsertOleObjectFrame()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: สร้างเฟรมอ็อบเจ็กต์ OLE ใหม่และแทรกมันเข้าสู่คอลเลกชันรูปร่างที่อินดексที่ระบุ
type: docs
weight: 196
url: /th/aspose.slides/shapecollection/insertoleobjectframe/
---
## ShapeCollection::InsertOleObjectFrame(int32_t, float, float, float, float, System::SharedPtr\<IOleEmbeddedDataInfo\>) เมธอด


สร้างเฟรมอ็อบเจ็กต์ OLE ใหม่และแทรกลงในคอลเลกชันรูปร่างที่อินดексที่ระบุ

```cpp
System::SharedPtr<IOleObjectFrame> Aspose::Slides::ShapeCollection::InsertOleObjectFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<IOleEmbeddedDataInfo> dataInfo) override
```


### Arguments

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| index | **int32_t** | อินดексаเริ่มจากศูนย์ที่ใช้แทรกเฟรมอ็อบเจ็กต์ OLE |
| x | **float** | พิกัด x ของเฟรม OLE ใหม่, หน่วยเป็นพอยต์ |
| y | **float** | พิกัด y ของเฟรม OLE ใหม่, หน่วยเป็นพอยต์ |
| width | **float** | ความกว้างของเฟรม OLE ใหม่, หน่วยเป็นพอยต์ |
| height | **float** | ความสูงของเฟรม OLE ใหม่, หน่วยเป็นพอยต์ |
| dataInfo | [System::SharedPtr](../../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)\> | ข้อมูล OLE ที่ฝังไว้ ([IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)) |

### Return Value

ออบเจ็กต์ [IOleObjectFrame](../../ioleobjectframe/) ที่สร้างใหม่
## Remarks



ตัวอย่างนี้แสดงการแทรกอ็อบเจ็กต์ OLE ที่อินดексที่สอง: 
```cpp
ArrayPtr<uint8_t> fileData = IO::File::ReadAllBytes(u"test.zip");
auto dataInfo = MakeObject<OleEmbeddedDataInfo>(fileData, u"zip");
auto oleObjectFrame = slide->get_Shapes()->InsertOleObjectFrame(2, 150.0f, 20.0f, 50.0f, 50.0f, dataInfo);
```

## ShapeCollection::InsertOleObjectFrame(int32_t, float, float, float, float, System::String, System::String) เมธอด


สร้างเฟรมอ็อบเจ็กต์ OLE ใหม่และแทรกลงในคอลเลกชันรูปร่างที่อินดексที่ระบุ

```cpp
System::SharedPtr<IOleObjectFrame> Aspose::Slides::ShapeCollection::InsertOleObjectFrame(int32_t index, float x, float y, float width, float height, System::String className, System::String path) override
```


### Arguments

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| index | **int32_t** | อินดексаเริ่มจากศูนย์ที่ใช้แทรกเฟรมอ็อบเจ็กต์ OLE |
| x | **float** | พิกัด x ของเฟรม OLE ใหม่, หน่วยเป็นพอยต์ |
| y | **float** | พิกัด y ของเฟรม OLE ใหม่, หน่วยเป็นพอยต์ |
| width | **float** | ความกว้างของเฟรม OLE ใหม่, หน่วยเป็นพอยต์ |
| height | **float** | ความสูงของเฟรม OLE ใหม่, หน่วยเป็นพอยต์ |
| className | [System::String](../../../system/string/) | ชื่อคลาสของอ็อบเจ็กต์ OLE |
| path | [System::String](../../../system/string/) | เส้นทางไปยังไฟล์ที่เชื่อมโยง |

### Return Value

เฟรมอ็อบเจ็กต์ OLE ที่สร้างใหม่
## Remarks



เส้นทางนี้จะถูกเก็บไว้ตามเดิมในพรีเซนเทชัน หากระบุเส้นทางแบบสัมพัทธ์ ไฟล์จะไม่สามารถเข้าถึงได้เมื่อเปิดพรีเซนเทชันจากไดเรกทอรีอื่น

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IOleObjectFrame](../../ioleobjectframe/)
* คลาส [IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)
* คลาส [ShapeCollection](../)
* คลาส [String](../../../system/string/)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)