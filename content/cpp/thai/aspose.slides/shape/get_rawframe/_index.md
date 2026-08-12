---
title: get_RawFrame()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: คืนค่าคุณสมบัติของกรอบรูปร่างดิบ อ่าน IShapeFrame.
type: docs
weight: 40
url: /th/aspose.slides/shape/get_rawframe/
---
## Shape::get_RawFrame() เมธอด


คืนค่าคุณสมบัติของกรอบรูปร่างดิบ อ่าน [IShapeFrame](../../ishapeframe/).

```cpp
System::SharedPtr<IShapeFrame> Aspose::Slides::Shape::get_RawFrame() override
```

## หมายเหตุ


โค้ดที่พยายามกำหนดเฟรมที่ไม่ได้กำหนดให้กับ [IShape::set_Frame](../../ishape/set_frame/) ไม่สมเหตุสมผลในกรณีทั่วไป (โดยเฉพาะในกรณีที่พาเรนท์ [GroupShape](../../groupshape/) ถูกซ้อนหลายชั้นเข้าใน GroupShape-s อื่น) ตัวอย่าง: 
```cpp
SharedPtr<IShape> shape = ...;
shape->set_Frame(System::MakeObject<ShapeFrame>(std::numeric_limits<float>::quiet_NaN(), 
std::numeric_limits<float>::quiet_NaN(), std::numeric_limits<float>::quiet_NaN(), 
std::numeric_limits<float>::quiet_NaN(), NullableBool::NotDefined, 
NullableBool::NotDefined, std::numeric_limits<float>::quiet_NaN()));
```
หรือ 
```cpp
slide->get_Shapes()->AddAutoShape(ShapeType::RoundCornerRectangle,
std::numeric_limits<float>::quiet_NaN(), std::numeric_limits<float>::quiet_NaN(), 
std::numeric_limits<float>::quiet_NaN(), std::numeric_limits<float>::quiet_NaN());
```
โค้ดดังกล่าวอาจนำไปสู่สถานการณ์ที่ไม่ชัดเจน ดังนั้นจึงมีการเพิ่มข้อจำกัดในการใช้ค่าที่ไม่ได้กำหนดสำหรับ [IShape::set_Frame](../../ishape/set_frame/) ค่าของ x, y, width, height, flipH, flipV และ rotationAngle ต้องถูกกำหนด (ไม่ใช่ std::numeric_limits<float>::quiet_NaN() หรือ [NullableBool::NotDefined](../../nullablebool/)) ตัวอย่างโค้ดข้างต้นตอนนี้จะโยนข้อยกเว้น ArgumentException ข้อจำกัดนี้ใช้กับกรณีการใช้งานต่อไปนี้: 
```cpp
SharedPtr<IShape> shape = ...;
shape->set_Frame(...); // ไม่สามารถเป็นค่า undefined ได้

SharedPtr<IShapeCollection> shapes = ...;
// พารามิเตอร์ x, y, width, height ไม่สามารถเป็น std::numeric_limits<float>::quiet_NaN() ได้:
{
    shapes->AddAudioFrameCD(...);
    shapes->AddAudioFrameEmbedded(...);
    shapes->AddAudioFrameLinked(...);
    shapes->AddAutoShape(...);
    shapes->AddChart(...);
    shapes->AddConnector(...);
    shapes->AddOleObjectFrame(...);
    shapes->AddPictureFrame(...);
    shapes->AddSmartArt(...);
    shapes->AddTable(...);
    shapes->AddVideoFrame(...);
    shapes->InsertAudioFrameEmbedded(...);
    shapes->InsertAudioFrameLinked(...);
    shapes->InsertAutoShape(...);
    shapes->InsertChart(...);
    shapes->InsertConnector(...);
    shapes->InsertOleObjectFrame(...);
    shapes->InsertPictureFrame(...);
    shapes->InsertTable(...);
    shapes->InsertVideoFrame(...);
}
```


แต่กรอบสำหรับเมธอด [IShape::set_RawFrame](../../ishape/set_rawframe/) อาจไม่มีการกำหนดค่าได้ นี่มีเหตุผลเมื่อรูปร่างเชื่อมโยงกับพาเลสโฮลเดอร์ จากนั้นค่ากรอบรูปร่างที่ไม่ได้กำหนดจะถูกแทนที่จากพาเรนท์พาเลสโฮลเดอร์ หากไม่มีพาเรนท์พาเลสโฮลเดอร์สำหรับรูปร่างนั้น รูปร่างจะใช้ค่าดีฟอลต์เมื่อคำนวณกรอบที่มีผลตาม [IShape::get_RawFrame](../../ishape/get_rawframe/) ค่าเริ่มต้นคือ 0 และ [NullableBool::False](../../nullablebool/) สำหรับ x, y, width, height, flipH, flipV และ rotationAngle ตัวอย่าง: 
```cpp
SharedPtr<IShape> shape = ...; // shape เชื่อมโยงกับ placeholder
shape->set_RawFrame(System::MakeObject<ShapeFrame>(std::numeric_limits<float>::quiet_NaN(), 
std::numeric_limits<float>::quiet_NaN(), 100.0f, std::numeric_limits<float>::quiet_NaN(), 
NullableBool::NotDefined, NullableBool::NotDefined, 0.0f)); // ตอนนี้ shape สืบทอดค่า x, y, height, flipH, flipV จาก placeholder และแทนที่ค่า width=100 และ rotationAngle=0.
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IShapeFrame](../../ishapeframe/)
* คลาส [Shape](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)