---
title: GetBasePlaceholder
second_title: Aspose.Sildes para .NET Referencia de API
description: Devuelve una forma de marcador de posición básico de la disposición y/o la diapositiva maestra de la que se hereda la forma actual. Se devuelve un null si la forma actual no se hereda.
type: docs
weight: 310
url: /es/aspose.slides/ishape/getbaseplaceholder/
---

## Método IShape.GetBasePlaceholder

Devuelve una forma de marcador de posición básica (forma de la disposición y/o la diapositiva maestra de la que se hereda la forma actual). Se devuelve un null si la forma actual no se hereda.

```csharp
public IShape GetBasePlaceholder()
```

### Ejemplos

```csharp
[C#]
// obtener todos los efectos animados (maestra/disposición/diapositiva) de la forma de marcador de posición
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

* interfaz [IShape](../../ishape)
* espacio de nombres [Aspose.Slides](../../ishape)
* ensamblaje [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->