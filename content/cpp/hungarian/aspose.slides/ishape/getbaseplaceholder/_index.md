---
title: GetBasePlaceholder()
second_title: Aspose.Slides C++ API referencia
description: Alap helyőrző alakzatot ad vissza (az elrendezésből és/vagy a mesterdiából származó alakzat, amelyből a jelenlegi alakzat örököl).
type: docs
weight: 573
url: /hu/aspose.slides/ishape/getbaseplaceholder/
---
## IShape::GetBasePlaceholder() metódus

Alap helyőrző alakzatot ad vissza (az elrendezésből és/vagy a mesterdiából származó alakzat, amelyből a jelenlegi alakzat örököl).

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::IShape::GetBasePlaceholder()=0
```

## Megjegyzés

Null érték kerül visszaadásra, ha a jelenlegi alakzat nem örököl.

```cpp
// az összes (mester/elrendezés/dián) animált effektus lekérése a helyőrző alakzatról
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

* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Osztály [IShape](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)