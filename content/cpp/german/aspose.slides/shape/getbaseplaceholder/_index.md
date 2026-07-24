---
title: GetBasePlaceholder()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt eine grundlegende Platzhalterform zurück (Form aus dem Layout und/oder Master-Folie, von der die aktuelle Form geerbt wird).
type: docs
weight: 638
url: /de/aspose.slides/shape/getbaseplaceholder/
---
## Shape::GetBasePlaceholder() Methode

Gibt eine grundlegende Platzhalterform zurück (Form aus dem Layout und/oder der Master-Folien, von der die aktuelle Form geerbt wird).

```cpp
System::SharedPtr<IShape> Aspose::Slides::Shape::GetBasePlaceholder() override
```

## Anmerkungen

Ein null wird zurückgegeben, wenn die aktuelle Form nicht vererbt ist.

```cpp
// Alle (master/layout/slide) animierten Effekte der Platzhalterform abrufen
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"sample.pptx");

System::SharedPtr<ISlide> slide = pres->get_Slide(0);
System::SharedPtr<IShape> shape = slide->get_Shape(0);
System::ArrayPtr<System::SharedPtr<IEffect>> shapeEffects = slide->get_Timeline()->get_MainSequence()->GetEffectsByShape(shape);

System::SharedPtr<IShape> layoutShape = shape->GetBasePlaceholder();
System::ArrayPtr<System::SharedPtr<IEffect>> layoutShapeEffects = slide->get_LayoutSlide()->get_Timeline()->get_MainSequence()->GetEffectsByShape(layoutShape);

System::SharedPtr<IShape> masterShape = layoutShape->GetBasePlaceholder();
System::ArrayPtr<System::SharedPtr<IEffect>> masterShapeEffects = slide->get_LayoutSlide()->get_MasterSlide()->get_Timeline()->get_MainSequence()->GetEffectsByShape(masterShape);
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IShape](../../ishape/)
* Klasse [Shape](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)