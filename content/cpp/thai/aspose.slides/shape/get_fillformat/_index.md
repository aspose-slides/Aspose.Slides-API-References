---
title: get_FillFormat()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: "ส่งคืนวัตถุ FillFormat ที่บรรจุคุณสมบัติการจัดรูปแบบเติมสีสำหรับรูปร่าง. หมายเหตุ: สามารถคืนค่า null สำหรับรูปร่างบางประเภทที่ไม่มีคุณสมบัติการเติมสี. อ่านอย่างเดียว IFillFormat."
type: docs
weight: 131
url: /th/aspose.slides/shape/get_fillformat/
---
## Shape::get_FillFormat() เมธอด


ส่งคืนวัตถุ [FillFormat](../../fillformat/) ที่บรรจุคุณสมบัติการจัดรูปแบบเติมสีสำหรับรูปร่าง. หมายเหตุ: สามารถคืนค่า null สำหรับรูปร่างบางประเภทที่ไม่มีคุณสมบัติการเติมสี. อ่านอย่างเดียว [IFillFormat](../../ifillformat/).

```cpp
System::SharedPtr<IFillFormat> Aspose::Slides::Shape::get_FillFormat() override
```

## หมายเหตุ


ตัวอย่างต่อไปนี้แสดงวิธีการเปลี่ยนสีสำเนียงสำหรับธีมของ PowerPoint [Presentation](../../presentation/). 
```cpp
auto pres = System::MakeObject<Presentation>();

auto slide = pres->get_Slides()->idx_get(0);
auto shape = slide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 10.0f, 10.0f, 100.0f, 100.0f);

shape->get_FillFormat()->set_FillType(FillType::Solid);
shape->get_FillFormat()->get_SolidFillColor()->set_SchemeColor(SchemeColor::Accent4);
```
 ตัวอย่างต่อไปนี้แสดงวิธีการดึงสีพาเล็ตต์จากสีธีมหลักและนำไปใช้ในรูปร่าง. 
```cpp
auto presentation = System::MakeObject<Presentation>();

auto slide = presentation->get_Slides->idx_get(0);
auto shapes = slide->get_Shapes();

// สีเน้น 4
auto shape1 = shapes->AddAutoShape(ShapeType::Rectangle, 10.0f, 10.0f, 50.0f, 50.0f);
auto fillFormat1 = shape1->get_FillFormat();

fillFormat1->set_FillType(FillType::Solid);
fillFormat1->get_SolidFillColor()->set_SchemeColor(SchemeColor::Accent4);

// สีเน้น 4, เบาขึ้น 80%
auto shape2 = shapes->AddAutoShape(ShapeType::Rectangle, 10.0f, 70.0f, 50.0f, 50.0f);
auto fillFormat2 = shape2->get_FillFormat();
auto solidFillColor2 = fillFormat2->get_SolidFillColor();

fillFormat2->set_FillType(FillType::Solid);
solidFillColor2->set_SchemeColor(SchemeColor::Accent4);
solidFillColor2->get_ColorTransform()->Add(ColorTransformOperation::MultiplyLuminance, 0.2f);
solidFillColor2->get_ColorTransform()->Add(ColorTransformOperation::AddLuminance, 0.8f);

// สีเน้น 4, เบาขึ้น 60%
auto shape3 = shapes->AddAutoShape(ShapeType::Rectangle, 10.0f, 130.0f, 50.0f, 50.0f);
auto fillFormat3 = shape3->get_FillFormat();
auto solidFillColor3 = fillFormat3->get_SolidFillColor();

fillFormat3->set_FillType(FillType::Solid);
solidFillColor3->set_SchemeColor(SchemeColor::Accent4);
solidFillColor3->get_ColorTransform()->Add(ColorTransformOperation::MultiplyLuminance, 0.4f);
solidFillColor3->get_ColorTransform()->Add(ColorTransformOperation::AddLuminance, 0.6f);

// สีเน้น 4, เบาขึ้น 40%
auto shape4 = shapes->AddAutoShape(ShapeType::Rectangle, 10.0f, 190.0f, 50.0f, 50.0f);
auto fillFormat4 = shape4->get_FillFormat();
auto solidFillColor4 = fillFormat4->get_SolidFillColor();

fillFormat4->set_FillType(FillType::Solid);
solidFillColor4->set_SchemeColor(SchemeColor::Accent4);
solidFillColor4->get_ColorTransform()->Add(ColorTransformOperation::MultiplyLuminance, 0.6f);
solidFillColor4->get_ColorTransform()->Add(ColorTransformOperation::AddLuminance, 0.4f);

// สีเน้น 4, มืดขึ้น 25%
auto shape5 = shapes->AddAutoShape(ShapeType::Rectangle, 10.0f, 250.0f, 50.0f, 50.0f);
auto fillFormat5 = shape5->get_FillFormat();
auto solidFillColor5 = fillFormat5->get_SolidFillColor();

fillFormat5->set_FillType(FillType::Solid);
solidFillColor5->set_SchemeColor(SchemeColor::Accent4);
solidFillColor5->get_ColorTransform()->Add(ColorTransformOperation::MultiplyLuminance, 0.75f);

// สีเน้น 4, มืดขึ้น 50%
auto shape6 = shapes->AddAutoShape(ShapeType::Rectangle, 10.0f, 310.0f, 50.0f, 50.0f);
auto fillFormat6 = shape6->get_FillFormat();
auto solidFillColor6 = fillFormat6->get_SolidFillColor();

fillFormat6->set_FillType(FillType::Solid);
solidFillColor6->set_SchemeColor(SchemeColor::Accent4);
solidFillColor6->get_ColorTransform()->Add(ColorTransformOperation::MultiplyLuminance, 0.5f);

presentation->Save(u"example.pptx", SaveFormat::Pptx);
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IFillFormat](../../ifillformat/)
* คลาส [Shape](../)
* เนมส페ซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)