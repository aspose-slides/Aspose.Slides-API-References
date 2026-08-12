---
title: AddConnector()
second_title: อ้างอิง API Aspose.Slides สำหรับ C++
description: สร้างรูปแบบตัวเชื่อมใหม่พร้อมสไตล์เทมเพลตเริ่มต้นและเพิ่มลงในส่วนท้ายของคอลเลกชันรูปทรง.
type: docs
weight: 417
url: /th/aspose.slides/shapecollection/addconnector/
---
## ShapeCollection::AddConnector(ShapeType, float, float, float, float) method


สร้างรูปแบบตัวเชื่อมใหม่พร้อมสไตล์เทมเพลตเริ่มต้นและเพิ่มลงในส่วนท้ายของคอลเลกชันรูปทรง

```cpp
System::SharedPtr<IConnector> Aspose::Slides::ShapeCollection::AddConnector(ShapeType shapeType, float x, float y, float width, float height) override
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | [ShapeType](../../shapetype/) ของรูปแบบตัวเชื่อมที่จะเพิ่ม. |
| x | **float** | พิกัด x ของกรอบตัวเชื่อม, หน่วยเป็นจุด. |
| y | **float** | พิกัด y ของกรอบตัวเชื่อม, หน่วยเป็นจุด. |
| width | **float** | ความกว้างของกรอบตัวเชื่อม, หน่วยเป็นจุด. |
| height | **float** | ความสูงของกรอบตัวเชื่อม, หน่วยเป็นจุด. |

### ค่าที่ส่งคืน

[IConnector](../../iconnector/) ที่สร้างใหม่.

## หมายเหตุ



ตัวอย่างต่อไปนี้แสดงวิธีการเพิ่มตัวเชื่อม (ตัวเชื่อมโค้ง) ระหว่างสองรูป (วงรีและสี่เหลี่ยม) ใน PowerPoint [Presentation](../../presentation/). 
```cpp
// สร้างอินสแตนซ์ของคลาส Presentation ที่แทนไฟล์ PPTX
auto input = System::MakeObject<Presentation>();

// เข้าถึงคอลเลกชันรูปทรงของสไลด์ที่กำหนด
auto shapes = input->get_Slides()->idx_get(0)->get_Shapes();
// เพิ่มรูปร่างอัตโนมัติ Ellipse
System::SharedPtr<IAutoShape> ellipse = shapes->AddAutoShape(ShapeType::Ellipse, 0.0f, 100.0f, 100.0f, 100.0f);
// เพิ่มรูปร่างอัตโนมัติ Rectangle
System::SharedPtr<IAutoShape> rectangle = shapes->AddAutoShape(ShapeType::Rectangle, 100.0f, 300.0f, 100.0f, 100.0f);

// เพิ่มรูปแบบตัวเชื่อมลงในคอลเลกชันรูปทรงของสไลด์
System::SharedPtr<IConnector> connector = shapes->AddConnector(ShapeType::BentConnector2, 0.0f, 0.0f, 10.0f, 10.0f);
// เชื่อมต่อรูปทรงโดยใช้ตัวเชื่อม
connector->set_StartShapeConnectedTo(ellipse);
connector->set_EndShapeConnectedTo(rectangle);
// เรียกใช้ reroute เพื่อกำหนดเส้นทางสั้นที่สุดอัตโนมัติระหว่างรูปทรง
connector->Reroute();

// บันทึกงานนำเสนอ
input->Save(u"Shapes-connector.pptx", SaveFormat::Pptx);
```

## ShapeCollection::AddConnector(ShapeType, float, float, float, float, bool) method


สร้างรูปแบบตัวเชื่อมใหม่และเพิ่มลงในส่วนท้ายของคอลเลกชันรูปทรง, โดยอาจใช้สไตล์เทมเพลตเริ่มต้น

```cpp
System::SharedPtr<IConnector> Aspose::Slides::ShapeCollection::AddConnector(ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate) override
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | [ShapeType](../../shapetype/) ของรูปแบบตัวเชื่อมที่จะสร้าง. |
| x | **float** | พิกัด x ของกรอบตัวเชื่อม, หน่วยเป็นจุด. |
| y | **float** | พิกัด y ของกรอบตัวเชื่อม, หน่วยเป็นจุด. |
| width | **float** | ความกว้างของกรอบตัวเชื่อม, หน่วยเป็นจุด. |
| height | **float** | ความสูงของกรอบตัวเชื่อม, หน่วยเป็นจุด. |
| createFromTemplate | **bool** | True เพื่อใช้สไตล์เทมเพลตเริ่มต้น (ชื่อไม่ว่างเปล่า, สไตล์แบบง่าย); false เพื่อสร้างตัวเชื่อมโดยใช้ค่าเริ่มต้นของคุณสมบัติ. |

### ค่าที่ส่งคืน

[IConnector](../../iconnector/) ที่สร้างใหม่.

## ดูเพิ่มเติม

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IConnector](../../iconnector/)
* คลาส [ShapeCollection](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)