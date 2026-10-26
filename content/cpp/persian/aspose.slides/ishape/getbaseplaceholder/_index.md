---
title: GetBasePlaceholder()
second_title: مرجع API Aspose.Slides برای C++
description: یک شکل پیش‌فرض جایگزین را برمی‌گرداند (شکل از چیدمان و/یا اسلاید اصلی که شکل فعلی از آن به ارث برده شده است).
type: docs
weight: 573
url: /fa/aspose.slides/ishape/getbaseplaceholder/
---
## IShape::GetBasePlaceholder() method


یک شکل پیش‌فرض جایگزین را برمی‌گرداند (شکل از چیدمان و/یا اسلاید اصلی که شکل فعلی از آن به ارث برده شده است).

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::IShape::GetBasePlaceholder()=0
```

## توضیحات


اگر شکل فعلی به ارث نرسیده باشد، مقدار null بازگردانده می‌شود.


```cpp
// دریافت تمام اثرات انیمیشنی (master/layout/slide) شکل جایگزین
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"sample.pptx");

System::SharedPtr<ISlide> slide = pres->get_Slide(0);
System::SharedPtr<IShape> shape = slide->get_Shape(0);
System::ArrayPtr<System::SharedPtr<IEffect>> shapeEffects = slide->get_Timeline()->get_MainSequence()->GetEffectsByShape(shape);

System::SharedPtr<IShape> layoutShape = shape->GetBasePlaceholder();
System::ArrayPtr<System::SharedPtr<IEffect>> layoutShapeEffects = slide->get_LayoutSlide()->get_Timeline()->get_MainSequence()->GetEffectsByShape(layoutShape);

System::SharedPtr<IShape> masterShape = layoutShape->GetBasePlaceholder();
System::ArrayPtr<System::SharedPtr<IEffect>> masterShapeEffects = slide->get_LayoutSlide()->get_MasterSlide()->get_Timeline()->get_MainSequence()->GetEffectsByShape(masterShape);
```




## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [IShape](../)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)