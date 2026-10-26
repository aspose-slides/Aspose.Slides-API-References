---
title: GetBasePlaceholder()
second_title: Aspose.Slides voor C++ API-referentie
description: Retourneert een basis placeholder-vorm (vorm uit de lay-out en/of masterslide waarvan de huidige vorm is geërfd).
type: docs
weight: 638
url: /nl/aspose.slides/shape/getbaseplaceholder/
---
## Shape::GetBasePlaceholder() methode

Retourneert een basis placeholder-vorm (vorm uit de lay-out en/of de masterslide waarvan de huidige vorm is geërfd).

```cpp
System::SharedPtr<IShape> Aspose::Slides::Shape::GetBasePlaceholder() override
```

## Opmerkingen

Er wordt null geretourneerd als de huidige vorm niet is geërfd.

```cpp
// haal alle (master/layout/slide) geanimeerde effecten van de placeholder-vorm op
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"sample.pptx");

System::SharedPtr<ISlide> slide = pres->get_Slide(0);
System::SharedPtr<IShape> shape = slide->get_Shape(0);
System::ArrayPtr<System::SharedPtr<IEffect>> shapeEffects = slide->get_Timeline()->get_MainSequence()->GetEffectsByShape(shape);

System::SharedPtr<IShape> layoutShape = shape->GetBasePlaceholder();
System::ArrayPtr<System::SharedPtr<IEffect>> layoutShapeEffects = slide->get_LayoutSlide()->get_Timeline()->get_MainSequence()->GetEffectsByShape(layoutShape);

System::SharedPtr<IShape> masterShape = layoutShape->GetBasePlaceholder();
System::ArrayPtr<System::SharedPtr<IEffect>> masterShapeEffects = slide->get_LayoutSlide()->get_MasterSlide()->get_Timeline()->get_MainSequence()->GetEffectsByShape(masterShape);
```


## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IShape](../../ishape/)
* Klasse [Shape](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)