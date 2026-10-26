---
title: GetBasePlaceholder()
second_title: Referência da API Aspose.Slides para C++
description: Retorna uma forma de placeholder básica (forma do layout e/ou slide mestre da qual a forma atual é herdada).
type: docs
weight: 573
url: /pt/aspose.slides/ishape/getbaseplaceholder/
---
## IShape::GetBasePlaceholder() método


Retorna uma forma de placeholder básica (forma do layout e/ou slide mestre da qual a forma atual é herdada).

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::IShape::GetBasePlaceholder()=0
```

## Observações


Um null é retornado se a forma atual não for herdada.


```cpp
// obtenha todos os efeitos animados (master/layout/slide) da forma placeholder
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"sample.pptx");

System::SharedPtr<ISlide> slide = pres->get_Slide(0);
System::SharedPtr<IShape> shape = slide->get_Shape(0);
System::ArrayPtr<System::SharedPtr<IEffect>> shapeEffects = slide->get_Timeline()->get_MainSequence()->GetEffectsByShape(shape);

System::SharedPtr<IShape> layoutShape = shape->GetBasePlaceholder();
System::ArrayPtr<System::SharedPtr<IEffect>> layoutShapeEffects = slide->get_LayoutSlide()->get_Timeline()->get_MainSequence()->GetEffectsByShape(layoutShape);

System::SharedPtr<IShape> masterShape = layoutShape->GetBasePlaceholder();
System::ArrayPtr<System::SharedPtr<IEffect>> masterShapeEffects = slide->get_LayoutSlide()->get_MasterSlide()->get_Timeline()->get_MainSequence()->GetEffectsByShape(masterShape);
```




## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IShape](../)
* Namespace [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)