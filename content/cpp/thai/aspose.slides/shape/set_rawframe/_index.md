---
title: set_RawFrame()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ตั้งค่าคุณสมบัติของเฟรมรูปร่างดิบ. เขียน IShapeFrame.
type: docs
weight: 53
url: /th/aspose.slides/shape/set_rawframe/
---
## Shape::set_RawFrame(System::SharedPtr\<IShapeFrame\>) เมธอด

ตั้งค่าคุณสมบัติของเฟรมรูปร่างดิบ เขียน [IShapeFrame](../../ishapeframe/).

```cpp
void Aspose::Slides::Shape::set_RawFrame(System::SharedPtr<IShapeFrame> value) override
```

## หมายเหตุ

โค้ดที่พยายามกำหนดเฟรมที่ไม่ได้กำหนดค่าให้กับ [IShape::set_Frame](../../ishape/set_frame/) ไม่มีความหมายในกรณีทั่วไป (โดยเฉพาะในกรณีที่พาเรนท์ [GroupShape](../../groupshape/) ถูกซ้อนหลายระดับเข้าไปใน GroupShape-s). ตัวอย่างเช่น: 
```cpp
SharedPtr<IShape> shape = ...;
shape->set_Frame(System::MakeObject<ShapeFrame>(std::numeric_limits<float>::quiet_NaN(), 
std::numeric_limits<float>::quiet_NaN(), std::numeric_limits<float>::quiet_NaN(), 
std::numeric_limits<float>::quiet_NaN(), NullableBool::NotDefined, 
NullableBool::NotDefined, std::numeric_limits<float>::quiet_NaN()));
```
 or 
```cpp
slide->get_Shapes()->AddAutoShape(ShapeType::RoundCornerRectangle,
std::numeric_limits<float>::quiet_NaN(), std::numeric_limits<float>::quiet_NaN(), 
std::numeric_limits<float>::quiet_NaN(), std::numeric_limits<float>::quiet_NaN());
```
โค้ดดังกล่าวอาจทำให้เกิดสถานการณ์ที่ไม่ชัดเจน. ดังนั้นจึงได้เพิ่มข้อจำกัดสำหรับการใช้ค่าที่ไม่ได้กำหนดสำหรับ [IShape::set_Frame](../../ishape/set_frame/). ค่าของ x, y, width, height, flipH, flipV และ rotationAngle ต้องถูกกำหนด (ไม่ใช่ std::numeric_limits<float>::quiet_NaN() หรือ [NullableBool::NotDefined](../../nullablebool/)). โค้ดตัวอย่างด้านบนตอนนี้จะโยนข้อยกเว้น ArgumentException. ข้อกำหนดนี้ใช้กับกรณีการใช้งานต่อไปนี้: 
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

แต่เฟรมสำหรับเมธอด [IShape::set_RawFrame](../../ishape/set_rawframe/) สามารถไม่ได้กำหนดค่าได้. สิ่งนี้มีเหตุผลเมื่อรูปทรงเชื่อมโยงกับ placeholder. จากนั้นค่าของเฟรมรูปทรงที่ไม่ได้กำหนดจะถูกทับโดยค่าจากรูปทรง placeholder ของพาเรนท์. หากไม่มีรูปทรง placeholder ของพาเรนท์สำหรับรูปทรงนั้น รูปทรงนั้นจะใช้ค่าเริ่มต้นเมื่อคำนวณเฟรมที่มีประสิทธิภาพโดยอิงจาก [IShape::get_RawFrame](../../ishape/get_rawframe/) ของมัน. ค่าเริ่มต้นคือ 0 และ [NullableBool::False](../../nullablebool/) สำหรับ x, y, width, height, flipH, flipV และ rotationAngle. ตัวอย่างเช่น: 
```cpp
SharedPtr<IShape> shape = ...; // shape ถูกเชื่อมโยงกับ placeholder
shape->set_RawFrame(System::MakeObject<ShapeFrame>(std::numeric_limits<float>::quiet_NaN(), 
std::numeric_limits<float>::quiet_NaN(), 100.0f, std::numeric_limits<float>::quiet_NaN(), 
NullableBool::NotDefined, NullableBool::NotDefined, 0.0f)); // ตอนนี้ shape สืบทอดค่าของ x, y, height, flipH, flipV จาก placeholder และแทนที่ width=100 และ rotationAngle=0.
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IShapeFrame](../../ishapeframe/)
* คลาส [Shape](../)
* เนมสเปซ [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)