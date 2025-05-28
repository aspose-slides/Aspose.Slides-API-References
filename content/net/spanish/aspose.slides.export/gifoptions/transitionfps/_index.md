---
title: TransitionFps
second_title: Referencia de la API de Aspose.Slides para .NET
description: Obtiene o establece los FPS de transición frames/sec. El valor predeterminado es 25.
type: docs
weight: 50
url: /es/aspose.slides.export/gifoptions/transitionfps/
---

## Propiedad GifOptions.TransitionFps

Obtiene o establece los FPS de transición [frames/sec]. El valor predeterminado es 25.

```csharp
public int TransitionFps { get; set; }
```

### Ejemplos

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
	pres.Save("pres.gif", SaveFormat.Gif, new GifOptions { TransitionFps = 60 });
}
```

### Véase También

* clase [GifOptions](../../gifoptions)
* espacio de nombres [Aspose.Slides.Export](../../gifoptions)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->