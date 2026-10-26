---
title: GetBasePlaceholder()
second_title: Aspose.Slides برای C++ مرجع API
description: یک شکل نگهدارندهٔ پایه را برمی‌گرداند (شکل از طرح‌بندی و/یا اسلاید اصلی که شکل فعلی از آن به ارث برده شده است).
type: docs
weight: 638
url: /fa/aspose.slides/shape/getbaseplaceholder/
---
## Shape::GetBasePlaceholder() متد

یک شکل نگهدارندهٔ پایه را برمی‌گرداند (شکل از طرح‌بندی و/یا اسلاید اصلی که شکل فعلی از آن به ارث برده شده است).

```cpp
System::SharedPtr<IShape> Aspose::Slides::Shape::GetBasePlaceholder() override
```

## ملاحظات

اگر شکل فعلی ارث‌بری نشود، مقدار null برگردانده می‌شود.

```cpp
// دریافت همهٔ افکت‌های انیمیشنی (مستر/طرح‌بندی/اسلاید) شکل نگهدارنده
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"sample.pptx");

System::SharedPtr<ISlide> slide = pres->get_Slide(0);
System::SharedPtr<IShape> shape = slide->get_Shape(0);
System::ArrayPtr<System::SharedPtr<IEffect>> shapeEffects = slide->get_Timeline()->get_MainSequence()->GetEffectsByShape(shape);

System::SharedPtr<IShape> layoutShape = shape->GetBasePlaceholder();
System::ArrayPtr<System::SharedPtr<IEffect>> layoutShapeEffects = slide->get_LayoutSlide()->get_Timeline()->get_MainSequence()->GetEffectsByShape(layoutShape);

System::SharedPtr<IShape> masterShape = layoutShape->GetBasePlaceholder();
System::ArrayPtr<System::SharedPtr<IEffect>> masterShapeEffects = slide->get_LayoutSlide()->get_MasterSlide()->get_Timeline()->get_MainSequence()->GetEffectsByShape(masterShape);
```

## نگاه کنید به

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [IShape](../../ishape/)
* کلاس [Shape](../)
* فضای نام [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)