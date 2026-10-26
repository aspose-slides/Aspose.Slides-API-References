---
title: GetBasePlaceholder()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يرجع شكل عنصر نائب أساسي (الشكل من التخطيط و/أو الشريحة الأساسية التي يُورث منها الشكل الحالي).
type: docs
weight: 573
url: /ar/aspose.slides/ishape/getbaseplaceholder/
---
## طريقة IShape::GetBasePlaceholder() method

يُرجع شكل عنصر نائب أساسي (الشكل من التخطيط و/أو الشريحة الأساسية التي يُورث منها الشكل الحالي).

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::IShape::GetBasePlaceholder()=0
```

## ملاحظات

يتم إرجاع قيمة فارغة إذا لم يكن الشكل الحالي موروثًا.

```cpp
// احصل على جميع التأثيرات المتحركة (master/layout/slide) لشكل العنصر النائب
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"sample.pptx");

System::SharedPtr<ISlide> slide = pres->get_Slide(0);
System::SharedPtr<IShape> shape = slide->get_Shape(0);
System::ArrayPtr<System::SharedPtr<IEffect>> shapeEffects = slide->get_Timeline()->get_MainSequence()->GetEffectsByShape(shape);

System::SharedPtr<IShape> layoutShape = shape->GetBasePlaceholder();
System::ArrayPtr<System::SharedPtr<IEffect>> layoutShapeEffects = slide->get_LayoutSlide()->get_Timeline()->get_MainSequence()->GetEffectsByShape(layoutShape);

System::SharedPtr<IShape> masterShape = layoutShape->GetBasePlaceholder();
System::ArrayPtr<System::SharedPtr<IEffect>> masterShapeEffects = slide->get_LayoutSlide()->get_MasterSlide()->get_Timeline()->get_MainSequence()->GetEffectsByShape(masterShape);
```



## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IShape](../)
* مساحة الأسماء [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)