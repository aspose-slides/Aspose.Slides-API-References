---
title: get_RawFrame()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ส่งคืนคุณสมบัติโครงร่างดิบของรูปร่าง. อ่าน IShapeFrame.
type: docs
weight: 40
url: /th/aspose.slides/ishape/get_rawframe/
---
## IShape::get_RawFrame() เมธอด

ส่งคืนคุณสมบัติโครงร่างดิบของรูปร่าง. อ่าน [IShapeFrame](../../ishapeframe/).

```cpp
virtual System::SharedPtr<IShapeFrame> Aspose::Slides::IShape::get_RawFrame()=0
```

## หมายเหตุ

โค้ดที่พยายามกำหนดกรอบที่ไม่ได้กำหนดค่าให้กับ [IShape::set_Frame](../set_frame/) ไม่มีความหมายในกรณีทั่วไป (โดยเฉพาะในกรณีที่พาเรนท์ [GroupShape](../../groupshape/) ซ้อนหลายระดับใน GroupShape อื่น). ตัวอย่างเช่น: 
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
โค้ดดังกล่าวอาจนำไปสู่สถานการณ์ที่ไม่ชัดเจน. ดังนั้นจึงได้เพิ่มข้อจำกัดสำหรับการใช้ค่าที่ไม่ได้กำหนดให้กับ [IShape::set_Frame](../set_frame/). ค่า x, y, width, height, flipH, flipV และ rotationAngle ต้องถูกกำหนด (ไม่ใช่ std::numeric_limits<float>::quiet_NaN() หรือ [NullableBool::NotDefined](../../nullablebool/)). โค้ดตัวอย่างข้างต้นขณะนี้จะโยนข้อยกเว้น ArgumentException. นี่ใช้กับกรณีการใช้งานต่อไปนี้: 
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

แต่กรอบสำหรับเมธอด [IShape::set_RawFrame](../set_rawframe/) สามารถไม่มีการกำหนดค่าได้. สิ่งนี้มีเหตุผลเมื่อรูปร่างเชื่อมโยงกับ placeholder. จากนั้นค่าเฟรมของรูปร่างที่ไม่ได้กำหนดจะถูกทับโดยค่าใน placeholder พาเรนท์. หากไม่มี placeholder พาเรนท์สำหรับรูปร่างนั้น รูปร่างจะใช้ค่าเริ่มต้นเมื่อคำนวณเฟรมที่มีประสิทธิภาพตาม [IShape::get_RawFrame](./) ของมัน. ค่าเริ่มต้นคือ 0 และ [NullableBool::False](../../nullablebool/) สำหรับ x, y, width, height, flipH, flipV และ rotationAngle. ตัวอย่างเช่น: 
```cpp
SharedPtr<IShape> shape = ...; // shape เชื่อมโยงกับ placeholder
shape->set_RawFrame(System::MakeObject<ShapeFrame>(std::numeric_limits<float>::quiet_NaN(), 
std::numeric_limits<float>::quiet_NaN(), 100.0f, std::numeric_limits<float>::quiet_NaN(), 
NullableBool::NotDefined, NullableBool::NotDefined, 0.0f)); // ตอนนี้ shape สืบทอดค่า x, y, height, flipH, flipV จาก placeholder และแทนที่ width=100 และ rotationAngle=0.
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IShapeFrame](../../ishapeframe/)
* Class [IShape](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)