---
title: GetBasePlaceholder()
second_title: مرجع API Aspose.Slides للغة C++
description: يُرجِع شكلاً أساسيًا للعنصر النائب (شكلاً من التخطيط و/أو الشريحة الرئيسية التي يُورّث منها الشكل الحالي).
type: docs
weight: 638
url: /ar/aspose.slides/shape/getbaseplaceholder/
---
## Shape::GetBasePlaceholder() طريقة

يُرجِع شكل عنصر نائب أساسي (شكل من التخطيط و/أو الشريحة الرئيسية التي يُورَّث منها الشكل الحالي).

```cpp
System::SharedPtr<IShape> Aspose::Slides::Shape::GetBasePlaceholder() override
```

## ملاحظات

يُرجَع null إذا لم يُورَّث الشكل الحالي.

```cpp
// احصل على جميع تأثيرات الرسوم المتحركة (الماستر/التخطيط/الشريحة) للشكل العنصر النائب
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

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IShape](../../ishape/)
* Class [Shape](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)