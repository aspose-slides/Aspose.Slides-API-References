---
title: GetBasePlaceholder()
second_title: Aspose.Slides för C++ API-referens
description: Returnerar en grundläggande platshållarform (form från layouten och/eller mastern som den aktuella formen ärvs från).
type: docs
weight: 638
url: /sv/aspose.slides/shape/getbaseplaceholder/
---
## Shape::GetBasePlaceholder() metod


Returnerar en grundläggande platshållarform (form från layouten och/eller mastern som den aktuella formen ärvs från).

```cpp
System::SharedPtr<IShape> Aspose::Slides::Shape::GetBasePlaceholder() override
```

## Anmärkningar


null returneras om den aktuella formen inte ärvs.


```cpp
// hämta alla (master/layout/slide) animerade effekter för platshållarformen
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"sample.pptx");

System::SharedPtr<ISlide> slide = pres->get_Slide(0);
System::SharedPtr<IShape> shape = slide->get_Shape(0);
System::ArrayPtr<System::SharedPtr<IEffect>> shapeEffects = slide->get_Timeline()->get_MainSequence()->GetEffectsByShape(shape);

System::SharedPtr<IShape> layoutShape = shape->GetBasePlaceholder();
System::ArrayPtr<System::SharedPtr<IEffect>> layoutShapeEffects = slide->get_LayoutSlide()->get_Timeline()->get_MainSequence()->GetEffectsByShape(layoutShape);

System::SharedPtr<IShape> masterShape = layoutShape->GetBasePlaceholder();
System::ArrayPtr<System::SharedPtr<IEffect>> masterShapeEffects = slide->get_LayoutSlide()->get_MasterSlide()->get_Timeline()->get_MainSequence()->GetEffectsByShape(masterShape);
```




## Se även

* Typdefinition [SharedPtr](../../../system/sharedptr/)
* Klass [IShape](../../ishape/)
* Klass [Shape](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)