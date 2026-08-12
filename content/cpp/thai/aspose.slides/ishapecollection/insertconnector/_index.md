---
title: InsertConnector()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: สร้างรูปแบบเชื่อมต่อใหม่และแทรกลงในคอลเลกชันรูปร่างที่ตำแหน่ง index ที่ระบุ โดยใช้สไตล์เทมเพลตเริ่มต้น
type: docs
weight: 391
url: /th/aspose.slides/ishapecollection/insertconnector/
---
## IShapeCollection::InsertConnector(int32_t, ShapeType, float, float, float, float) เมธอด


สร้างรูปร่างเชื่อมต่อใหม่และแทรกเข้าไปในคอลเลกชันรูปร่างที่ตำแหน่ง index ที่ระบุ โดยใช้สไตล์เทมเพลตเริ่มต้น

```cpp
virtual System::SharedPtr<IConnector> Aspose::Slides::IShapeCollection::InsertConnector(int32_t index, ShapeType shapeType, float x, float y, float width, float height)=0
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | **int32_t** | ตำแหน่ง index ที่เริ่มจากศูนย์ซึ่งใช้เพื่อแทรกรูปร่างเชื่อมต่อ |
| shapeType | [ShapeType](../../shapetype/) | [ShapeType](../../shapetype/) ของรูปร่างเชื่อมต่อที่จะแทรก |
| x | **float** | พิกัด x ของเฟรมของ connector, หน่วยเป็นจุด |
| y | **float** | พิกัด y ของเฟรมของ connector, หน่วยเป็นจุด |
| width | **float** | ความกว้างของเฟรมของ connector, หน่วยเป็นจุด |
| height | **float** | ความสูงของเฟรมของ connector, หน่วยเป็นจุด |

### ค่าที่คืน

[IConnector](../../iconnector/) ที่สร้างใหม่

## IShapeCollection::InsertConnector(int32_t, ShapeType, float, float, float, float, bool) เมธอด


สร้างรูปร่างเชื่อมต่อใหม่และแทรกเข้าไปในคอลเลกชันรูปร่างที่ตำแหน่ง index ที่ระบุ โดยอาจใช้สไตล์เทมเพลตเริ่มต้นตามต้องการ

```cpp
virtual System::SharedPtr<IConnector> Aspose::Slides::IShapeCollection::InsertConnector(int32_t index, ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate)=0
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | **int32_t** | ตำแหน่ง index ที่เริ่มจากศูนย์ซึ่งใช้เพื่อแทรกรูปร่างเชื่อมต่อ |
| shapeType | [ShapeType](../../shapetype/) | [ShapeType](../../shapetype/) ของรูปร่างเชื่อมต่อที่จะแทรก |
| x | **float** | พิกัด x ของเฟรมของ connector, หน่วยเป็นจุด |
| y | **float** | พิกัด y ของเฟรมของ connector, หน่วยเป็นจุด |
| width | **float** | ความกว้างของเฟรมของ connector, หน่วยเป็นจุด |
| height | **float** | ความสูงของเฟรมของ connector, หน่วยเป็นจุด |
| createFromTemplate | **bool** | True เพื่อใช้สไตล์เทมเพลตเริ่มต้น (ชื่อไม่ว่างเปล่า, สไตล์ธรรมดา); false เพื่อสร้าง connector ด้วยค่าคุณสมบัติเคลือเริ่มต้น |

### ค่าที่คืน

[IConnector](../../iconnector/) ที่สร้างใหม่

## ดูเพิ่มเติม

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IConnector](../../iconnector/)
* Class [IShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)