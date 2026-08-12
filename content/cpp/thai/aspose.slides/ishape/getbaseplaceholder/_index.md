---
title: GetBasePlaceholder()
second_title: Aspose.Slides สำหรับอ้างอิง API ของ C++
description: ส่งคืนรูปทรง placeholder พื้นฐาน (รูปทรงจากเลย์เอาต์และ/หรือสไลด์แม่ที่รูปทรงปัจจุบันสืบทอดมาจาก).
type: docs
weight: 573
url: /th/aspose.slides/ishape/getbaseplaceholder/
---
## IShape::GetBasePlaceholder() เมธอด

ส่งคืนรูปทรงตัวแทนพื้นฐาน (รูปทรงจากเลย์เอาต์และ/หรือสไลด์แม่ที่รูปทรงปัจจุบันสืบทอดมา).

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::IShape::GetBasePlaceholder()=0
```

## หมายเหตุ

จะส่งกลับค่า null หากรูปทรงปัจจุบันไม่ได้รับการสืบทอด.

```cpp
// ดึงเอาเอฟเฟกต์ที่เคลื่อนไหวทั้งหมด (master/layout/slide) ของรูปทรง placeholder
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

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IShape](../)
* เนมสเปซ [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)