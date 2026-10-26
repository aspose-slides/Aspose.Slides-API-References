---
title: set_RawFrame()
second_title: Aspose.Slides สำหรับ API Reference ของ C++
description: ตั้งค่าคุณสมบัติของเฟรมรูปร่างดิบ เขียน IShapeFrame.
type: docs
weight: 53
url: /th/aspose.slides/ishape/set_rawframe/
---
## IShape::set_RawFrame(System::SharedPtr\<IShapeFrame\>) เมธอด

ตั้งค่าคุณสมบัติของเฟรมรูปร่างดิบ เขียน [IShapeFrame](../../ishapeframe/).

```cpp
virtual void Aspose::Slides::IShape::set_RawFrame(System::SharedPtr<IShapeFrame> value)=0
```

## หมายเหตุ

โค้ดที่พยายามกำหนดเฟรมที่ไม่ได้กำหนดค่าให้กับ [IShape::set_Frame](../set_frame/) ไม่สมเหตุสมผลในกรณีทั่วไป (โดยเฉพาะในกรณีที่พาเร้นท์ [GroupShape](../../groupshape/) ถูกซ้อนหลายชั้นใน GroupShape อื่น ๆ) ตัวอย่างเช่น:
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
โค้ดดังกล่าวอาจทำให้เกิดสถานการณ์ที่ไม่ชัดเจน ดังนั้นจึงมีการเพิ่มข้อจำกัดสำหรับการใช้ค่าที่ไม่ได้กำหนดสำหรับ [IShape::set_Frame](../set_frame/) ค่าของ x, y, width, height, flipH, flipV และ rotationAngle ต้องถูกกำหนด (ไม่ใช่ std::numeric_limits<float>::quiet_NaN() หรือ [NullableBool::NotDefined](../../nullablebool/)) โค้ดตัวอย่างด้านบนตอนนี้จะขว้างข้อยกเว้น ArgumentException นี้ใช้กับกรณีการใช้งานต่อไปนี้:
```cpp
SharedPtr<IShape> shape = ...;
shape->set_Frame(...); // ไม่สามารถเป็นค่าไม่กำหนดได้

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

แต่เฟรมสำหรับเมธอด [IShape::set_RawFrame](./) สามารถไม่ได้กำหนดค่าได้ สิ่งนี้มีเหตุผลเมื่อรูปร่างถูกเชื่อมโยงกับตัวแทนที่ จากนั้นค่าที่ไม่ได้กำหนดของเฟรมรูปร่างจะถูกแทนที่จากรูปร่างตัวแทนพาเร้นท์ หากไม่มีรูปร่างตัวแทนพาเร้นท์สำหรับรูปร่างนั้น รูปร่างนั้นจะใช้ค่าตั้งต้นเมื่อคำนวนเฟรมที่มีผลตาม [IShape::get_RawFrame](../get_rawframe/) ค่าตั้งต้นคือ 0 และ [NullableBool::False](../../nullablebool/) สำหรับ x, y, width, height, flipH, flipV และ rotationAngle ตัวอย่างเช่น:
```cpp
SharedPtr<IShape> shape = ...; // รูปร่างเชื่อมโยงกับตัวจับตำแหน่ง
shape->set_RawFrame(System::MakeObject<ShapeFrame>(std::numeric_limits<float>::quiet_NaN(), 
std::numeric_limits<float>::quiet_NaN(), 100.0f, std::numeric_limits<float>::quiet_NaN(), 
NullableBool::NotDefined, NullableBool::NotDefined, 0.0f)); // ตอนนี้รูปร่างสืบทอดค่า x, y, height, flipH, flipV จากตัวจับตำแหน่งและแทนที่ค่า width=100 และ rotationAngle=0.
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IShapeFrame](../../ishapeframe/)
* คลาส [IShape](../)
* เนมสเปซ [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)