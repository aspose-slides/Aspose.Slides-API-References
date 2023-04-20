---
title: GetBasePlaceholder()
second_title: Aspose.Slides for C++ API Reference
description: Returns a basic placeholder shape (shape from the layout and/or master slide that the current shape is inherited from).
type: docs
weight: 547
url: /cpp/aspose.slides/ishape/getbaseplaceholder/
---
## IShape::GetBasePlaceholder() method


Returns a basic placeholder shape (shape from the layout and/or master slide that the current shape is inherited from).

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::IShape::GetBasePlaceholder()=0
```

## Remarks


A null is returned if the current shape is not inherited.


```cpp
// get all (master/layout/slide) animated effects of the placeholder shape
auto pres = System::MakeObject<Presentation>(u"sample.pptx");

auto slide = pres->get_Slides()->idx_get(0);
auto shape = slide->get_Shapes()->idx_get(0);
auto sequence = slide->get_LayoutSlide()->get_Timeline()->get_MainSequence();

auto shapeEffects = sequence->GetEffectsByShape(shape);

System::SharedPtr<IShape> layoutShape = shape->GetBasePlaceholder();
auto layoutShapeEffects = sequence->GetEffectsByShape(layoutShape);

System::SharedPtr<IShape> masterShape = layoutShape->GetBasePlaceholder();
auto masterShapeEffects = slide->get_LayoutSlide()->get_MasterSlide()->get_Timeline()->get_MainSequence()->GetEffectsByShape(masterShape);
```




## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IShape](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)