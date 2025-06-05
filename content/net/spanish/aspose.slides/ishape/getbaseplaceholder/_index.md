---
title: GetBasePlaceholder
second_title: Referencia de API Aspose.Slides para .NET
description: Devuelve una forma de marcador de posición básica de la diapositiva de diseño y/o maestro de la cual se hereda la forma actual. Se devuelve un null si la forma actual no es heredada.
type: docs
weight: 310
url: /es/aspose.slides/ishape/getbaseplaceholder/
---

## IShape.GetBasePlaceholder método

Devuelve una forma de marcador de posición básica (forma de la diapositiva de diseño y/o maestro de la cual se hereda la forma actual). Se devuelve un null si la forma actual no es heredada.

```csharp
public IShape GetBasePlaceholder()
```

### Ejemplos

```csharp
[C#]
// obtener todos los efectos animados (de maestro/diseño/diapositiva) de la forma de marcador de posición
using (Presentation pres = new Presentation("sample.pptx"))
{
    ISlide slide = pres.Slides[0];
    IShape shape = slide.Shapes[0];
    IEffect[] shapeEffects = slide.Timeline.MainSequence.GetEffectsByShape(shape);

    IShape layoutShape = shape.GetBasePlaceholder();
    IEffect[] layoutShapeEffects = slide.LayoutSlide.Timeline.MainSequence.GetEffectsByShape(layoutShape);

    IShape masterShape = layoutShape.GetBasePlaceholder();
    IEffect[] masterShapeEffects = slide.LayoutSlide.MasterSlide.Timeline.MainSequence.GetEffectsByShape(masterShape);
}
```

### Ver También

* interfaz [IShape](../../ishape)
* espacio de nombres [Aspose.Slides](../../ishape)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->