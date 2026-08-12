---
title: AddGroupShape()
second_title: Aspose.Slides สำหรับ C++ อ้างอิง API
description: สร้างกลุ่มรูปแบบเปล่าใหม่และเพิ่มเข้าไปที่ส่วนท้ายของคอลเลกชันรูปแบบ กรอบของกลุ่มจะปรับอัตโนมัติเพื่อให้พอดีกับรูปแบบใด ๆ ที่เพิ่มเข้าไป
type: docs
weight: 391
url: /th/aspose.slides/shapecollection/addgroupshape/
---
## ShapeCollection::AddGroupShape() เมธอด

สร้างกลุ่มรูปแบบเปล่าที่ใหม่และเพิ่มเข้าไปที่ส่วนท้ายของคอลเลกชันรูปแบบ กรอบของกลุ่มจะปรับอัตโนมัติเพื่อให้พอกับรูปแบบใด ๆ ที่เพิ่มเข้าไป

```cpp
System::SharedPtr<IGroupShape> Aspose::Slides::ShapeCollection::AddGroupShape() override
```

### ค่าที่คืน

ออบเจกต์ที่สร้างใหม่ [IGroupShape](../../igroupshape/).

## หมายเหตุ

ตัวอย่างต่อไปนี้แสดงวิธีเพิ่มกลุ่มรูปแบบลงในสไลด์ของ PowerPoint [Presentation](../../presentation/).

```cpp
// สร้างอินสแตนซ์ของคลาส Presentation
auto pres = System::MakeObject<Presentation>();

// รับสไลด์แรก
auto slide = pres->get_Slides()->idx_get(0);
// เขาถึงคอลเลกชันรูปแบบของสไลด์
auto slideShapes = slide->get_Shapes();
// เพิ่มกลุ่มรูปแบบลงในสไลด์
System::SharedPtr<IGroupShape> groupShape = slideShapes->AddGroupShape();

// เพิ่มรูปแบบภายในกลุ่มรูปแบบที่เพิ่มไว้
groupShape->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 300.0f, 100.0f, 100.0f, 100.0f);
groupShape->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 500.0f, 100.0f, 100.0f, 100.0f);
groupShape->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 300.0f, 300.0f, 100.0f, 100.0f);
groupShape->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 500.0f, 300.0f, 100.0f, 100.0f);
// เพิ่มกรอบของกลุ่มรูปแบบ
groupShape->set_Frame(System::MakeObject<ShapeFrame>(100.0f, 300.0f, 500.0f, 40.0f, NullableBool::False, NullableBool::False, 0.0f));

// บันทึกไฟล์ PPTX ลงดิสก์
pres->Save(u"GroupShape_out.pptx", SaveFormat::Pptx);
```

## ShapeCollection::AddGroupShape(System::SharedPtr\<ISvgImage\>, float, float, float, float) เมธอด

สร้างกลุ่มรูปแบบใหม่ แปลงภาพ SVG ที่ระบุเป็นรูปแบบแยกส่วน และเพิ่มกลุ่มที่ได้ลงในส่วนท้ายของคอลเลกชันรูปแบบ

```cpp
System::SharedPtr<IGroupShape> Aspose::Slides::ShapeCollection::AddGroupShape(System::SharedPtr<ISvgImage> svgImage, float x, float y, float width, float height) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| svgImage | [System::SharedPtr](../../../system/sharedptr/)\<[ISvgImage](../../isvgimage/)\> | [ISvgImage](../../isvgimage/) ที่มีเนื้อหาเวกเตอร์เพื่อแปลงเป็นรูปแบบ |
| x | **float** | พิกัดแกน x ของกรอบกลุ่มในหน่วยจุด |
| y | **float** | พิกัดแกน y ของกรอบกลุ่มในหน่วยจุด |
| width | **float** | ความกว้างของกรอบกลุ่มในหน่วยจุด |
| height | **float** | ความสูงของกรอบกลุ่มในหน่วยจุด |

### ค่าที่คืน

ออบเจกต์ที่สร้างใหม่ [IGroupShape](../../igroupshape/).

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IGroupShape](../../igroupshape/)
* คลาส [ShapeCollection](../)
* คลาส [ISvgImage](../../isvgimage/)
* เนมสเปซ [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)