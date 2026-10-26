---
title: GetBasePlaceholder()
second_title: Aspose.Slides dla C++ Dokumentacja API
description: Zwraca podstawowy kształt zastępczy (kształt z układu i/lub slajdu wzorcowego, z którego dziedziczy bieżący kształt).
type: docs
weight: 573
url: /pl/aspose.slides/ishape/getbaseplaceholder/
---
## IShape::GetBasePlaceholder() metoda


Zwraca podstawowy obiekt zastępczy (obiekt z układu i/lub slajdu wzorcowego, z którego dziedziczy bieżący obiekt).

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::IShape::GetBasePlaceholder()=0
```

## Uwagi


Zwracane jest null, jeśli bieżący obiekt nie jest dziedziczony.


```cpp
// pobierz wszystkie (master/layout/slide) efekty animacji kształtu zastępczego
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"sample.pptx");

System::SharedPtr<ISlide> slide = pres->get_Slide(0);
System::SharedPtr<IShape> shape = slide->get_Shape(0);
System::ArrayPtr<System::SharedPtr<IEffect>> shapeEffects = slide->get_Timeline()->get_MainSequence()->GetEffectsByShape(shape);

System::SharedPtr<IShape> layoutShape = shape->GetBasePlaceholder();
System::ArrayPtr<System::SharedPtr<IEffect>> layoutShapeEffects = slide->get_LayoutSlide()->get_Timeline()->get_MainSequence()->GetEffectsByShape(layoutShape);

System::SharedPtr<IShape> masterShape = layoutShape->GetBasePlaceholder();
System::ArrayPtr<System::SharedPtr<IEffect>> masterShapeEffects = slide->get_LayoutSlide()->get_MasterSlide()->get_Timeline()->get_MainSequence()->GetEffectsByShape(masterShape);
```




## Zobacz też

* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [IShape](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)