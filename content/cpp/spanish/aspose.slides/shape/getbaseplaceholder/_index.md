---
title: GetBasePlaceholder()
second_title: Referencia de API de Aspose.Slides para C++
description: Devuelve una forma de marcador de posición básica (forma del diseño y/o diapositiva maestra de la que se hereda la forma actual).
type: docs
weight: 638
url: /es/aspose.slides/shape/getbaseplaceholder/
---
## Shape::GetBasePlaceholder() método


Devuelve una forma de marcador de posición básica (forma del diseño y/o diapositiva maestra de la que se hereda la forma actual).

```cpp
System::SharedPtr<IShape> Aspose::Slides::Shape::GetBasePlaceholder() override
```

## Observaciones


Se devuelve null si la forma actual no se hereda.


```cpp
// obtener todos los efectos animados (maestro/disposición/diapositiva) de la forma de marcador de posición
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"sample.pptx");

System::SharedPtr<ISlide> slide = pres->get_Slide(0);
System::SharedPtr<IShape> shape = slide->get_Shape(0);
System::ArrayPtr<System::SharedPtr<IEffect>> shapeEffects = slide->get_Timeline()->get_MainSequence()->GetEffectsByShape(shape);

System::SharedPtr<IShape> layoutShape = shape->GetBasePlaceholder();
System::ArrayPtr<System::SharedPtr<IEffect>> layoutShapeEffects = slide->get_LayoutSlide()->get_Timeline()->get_MainSequence()->GetEffectsByShape(layoutShape);

System::SharedPtr<IShape> masterShape = layoutShape->GetBasePlaceholder();
System::ArrayPtr<System::SharedPtr<IEffect>> masterShapeEffects = slide->get_LayoutSlide()->get_MasterSlide()->get_Timeline()->get_MainSequence()->GetEffectsByShape(masterShape);
```




## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IShape](../../ishape/)
* Clase [Shape](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)