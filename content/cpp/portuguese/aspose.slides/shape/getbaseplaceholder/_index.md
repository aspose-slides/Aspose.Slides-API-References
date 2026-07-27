---
title: GetBasePlaceholder()
second_title: Referência da API Aspose.Slides para C++
description: Retorna uma forma de placeholder básica (forma do layout e/ou slide mestre da qual a forma atual é herdada).
type: docs
weight: 638
url: /pt/aspose.slides/shape/getbaseplaceholder/
---
## Shape::GetBasePlaceholder() método

Retorna uma forma de placeholder básica (forma do layout e/ou slide mestre da qual a forma atual é herdada).

```cpp
System::SharedPtr<IShape> Aspose::Slides::Shape::GetBasePlaceholder() override
```

## Observações

É retornado null se a forma atual não for herdada.

```cpp
// obter todos os efeitos animados (master/layout/slide) da forma placeholder
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"sample.pptx");

System::SharedPtr<ISlide> slide = pres->get_Slide(0);
System::SharedPtr<IShape> shape = slide->get_Shape(0);
System::ArrayPtr<System::SharedPtr<IEffect>> shapeEffects = slide->get_Timeline()->get_MainSequence()->GetEffectsByShape(shape);

System::SharedPtr<IShape> layoutShape = shape->GetBasePlaceholder();
System::ArrayPtr<System::SharedPtr<IEffect>> layoutShapeEffects = slide->get_LayoutSlide()->get_Timeline()->get_MainSequence()->GetEffectsByShape(layoutShape);

System::SharedPtr<IShape> masterShape = layoutShape->GetBasePlaceholder();
System::ArrayPtr<System::SharedPtr<IEffect>> masterShapeEffects = slide->get_LayoutSlide()->get_MasterSlide()->get_Timeline()->get_MainSequence()->GetEffectsByShape(masterShape);
```

## Veja também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IShape](../../ishape/)
* Classe [Shape](../)
* Espaço de nomes [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)