---
title: GetBasePlaceholder()
second_title: Aspose.Slides C++ API hivatkozás
description: Visszaad egy alaphelyettesítő alakzatot (az elrendezésből és/vagy a mester-diából származó alakzat, amelyből a jelenlegi alakzat származik).
type: docs
weight: 638
url: /hu/aspose.slides/shape/getbaseplaceholder/
---
## Shape::GetBasePlaceholder() metódus


Visszaad egy alaphelyettesítő alakzatot (az elrendezésből és/vagy a mesterdiából származó alakzat, amelyből a jelenlegi alakzat származik).

```cpp
System::SharedPtr<IShape> Aspose::Slides::Shape::GetBasePlaceholder() override
```

## Megjegyzés


null értéket ad vissza, ha a jelenlegi alakzat nem öröklődik.


```cpp
// lekéri a helyettesítő alakzat összes (mester/elrendezés/dián) animált effektusát
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"sample.pptx");

System::SharedPtr<ISlide> slide = pres->get_Slide(0);
System::SharedPtr<IShape> shape = slide->get_Shape(0);
System::ArrayPtr<System::SharedPtr<IEffect>> shapeEffects = slide->get_Timeline()->get_MainSequence()->GetEffectsByShape(shape);

System::SharedPtr<IShape> layoutShape = shape->GetBasePlaceholder();
System::ArrayPtr<System::SharedPtr<IEffect>> layoutShapeEffects = slide->get_LayoutSlide()->get_Timeline()->get_MainSequence()->GetEffectsByShape(layoutShape);

System::SharedPtr<IShape> masterShape = layoutShape->GetBasePlaceholder();
System::ArrayPtr<System::SharedPtr<IEffect>> masterShapeEffects = slide->get_LayoutSlide()->get_MasterSlide()->get_Timeline()->get_MainSequence()->GetEffectsByShape(masterShape);
```




## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IShape](../../ishape/)
* Osztály [Shape](../)
* Névtér [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)