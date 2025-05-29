---
title: GetBasePlaceholder
second_title: Aspose.Slides für .NET API-Referenz
description: Gibt eine grundlegende Platzhalterform zurück, die von dem Layout und/oder der Master-Folie, von der die aktuelle Form abgeleitet ist, stammt. Ein null wird zurückgegeben, wenn die aktuelle Form nicht abgeleitet ist.
type: docs
weight: 310
url: /de/aspose.slides/ishape/getbaseplaceholder/
---

## IShape.GetBasePlaceholder-Methode

Gibt eine grundlegende Platzhalterform (Form aus dem Layout und/oder der Master-Folie, von der die aktuelle Form abgeleitet ist) zurück. Ein null wird zurückgegeben, wenn die aktuelle Form nicht abgeleitet ist.

```csharp
public IShape GetBasePlaceholder()
```

### Beispiele

```csharp
[C#]
// Holen Sie sich alle (Master/Layout/Folie) animierten Effekte der Platzhalterform
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

### Siehe Auch

* interface [IShape](../../ishape)
* namespace [Aspose.Slides](../../ishape)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generiert von xmldocmd für Aspose.Slides.dll -->