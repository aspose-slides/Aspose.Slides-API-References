---
title: GetBasePlaceholder()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: ส่งคืนรูปทรงตัวแบบพื้นฐาน (รูปทรงจากการจัดวางและ/หรือสไลด์แม่ที่รูปทรงปัจจุบันสืบทอดมาจาก)
type: docs
weight: 638
url: /th/aspose.slides/shape/getbaseplaceholder/
---
## Shape::GetBasePlaceholder() เมธอด

ส่งคืนรูปทรงตัวแบบพื้นฐาน (รูปทรงจากการจัดวางและ/หรือสไลด์แม่ที่รูปทรงปัจจุบันสืบทอดมาจาก)

```cpp
System::SharedPtr<IShape> Aspose::Slides::Shape::GetBasePlaceholder() override
```

## หมายเหตุ

จะส่งค่ากลับเป็น null หากรูปทรงปัจจุบันไม่ได้ถูกสืบทอด

```cpp
// ดึงเอาเอฟเฟกต์แอนิเมชันทั้งหมด (master/layout/slide) ของรูปทรงตัวแบบ
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"sample.pptx");

System::SharedPtr<ISlide> slide = pres->get_Slide(0);
System::SharedPtr<IShape> shape = slide->get_Shape(0);
System::ArrayPtr<System::SharedPtr<IEffect>> shapeEffects = slide->get_Timeline()->get_MainSequence()->GetEffectsByShape(shape);

System::SharedPtr<IShape> layoutShape = shape->GetBasePlaceholder();
System::ArrayPtr<System::SharedPtr<IEffect>> layoutShapeEffects = slide->get_LayoutSlide()->get_Timeline()->get_MainSequence()->GetEffectsByShape(layoutShape);

System::SharedPtr<IShape> masterShape = layoutShape->GetBasePlaceholder();
System::ArrayPtr<System::SharedPtr<IEffect>> masterShapeEffects = slide->get_LayoutSlide()->get_MasterSlide()->get_Timeline()->get_MainSequence()->GetEffectsByShape(masterShape);
```

## ดูเพิ่มเติม

* ประเภทนิยาม [SharedPtr](../../../system/sharedptr/)
* คลาส [IShape](../../ishape/)
* คลาส [Shape](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)