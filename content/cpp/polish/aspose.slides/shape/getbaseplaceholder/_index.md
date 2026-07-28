---
title: GetBasePlaceholder()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Zwraca podstawowy kształt zastępczy (kształt z układu i/lub slajdu głównego, z którego dziedziczony jest bieżący kształt).
type: docs
weight: 638
url: /pl/aspose.slides/shape/getbaseplaceholder/
---
## Shape::GetBasePlaceholder() metoda

Zwraca podstawowy kształt zastępczy (kształt z układu i/lub slajdu głównego, z którego dziedziczony jest bieżący kształt).

```cpp
System::SharedPtr<IShape> Aspose::Slides::Shape::GetBasePlaceholder() override
```

## Uwagi

Zwracane jest null, jeśli bieżący kształt nie jest dziedziczony.

```cpp
// pobierz wszystkie (master/layout/slide) animowane efekty kształtu zastępczego
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"sample.pptx");

System::SharedPtr<ISlide> slide = pres->get_Slide(0);
System::SharedPtr<IShape> shape = slide->get_Shape(0);
System::ArrayPtr<System::SharedPtr<IEffect>> shapeEffects = slide->get_Timeline()->get_MainSequence()->GetEffectsByShape(shape);

System::SharedPtr<IShape> layoutShape = shape->GetBasePlaceholder();
System::ArrayPtr<System::SharedPtr<IEffect>> layoutShapeEffects = slide->get_LayoutSlide()->get_Timeline()->get_MainSequence()->GetEffectsByShape(layoutShape);

System::SharedPtr<IShape> masterShape = layoutShape->GetBasePlaceholder();
System::ArrayPtr<System::SharedPtr<IEffect>> masterShapeEffects = slide->get_LayoutSlide()->get_MasterSlide()->get_Timeline()->get_MainSequence()->GetEffectsByShape(masterShape);
```

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IShape](../../ishape/)
* Klasa [Shape](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)