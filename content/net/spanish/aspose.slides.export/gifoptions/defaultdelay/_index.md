---
title: DefaultDelay
second_title: Aspose.Sildes para .NET Referencia de API
description: Obtiene o establece el tiempo de retraso predeterminado en ms. Este valor se utilizará si AdvanceAfterTime no está establecido. El valor predeterminado es 1000.
type: docs
weight: 20
url: /es/aspose.slides.export/gifoptions/defaultdelay/
---

## GifOptions.DefaultDelay propiedad

Obtiene o establece el tiempo de retraso predeterminado [ms]. Este valor se utilizará si [`AdvanceAfterTime`](../../../aspose.slides/islideshowtransition/advanceaftertime) no está establecido. El valor predeterminado es 1000.

```csharp
public int DefaultDelay { get; set; }
```

### Ejemplos

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
	pres.Save("pres.gif", SaveFormat.Gif, new GifOptions { DefaultDelay = 2000 });
}
```

### Véase también

* clase [GifOptions](../../gifoptions)
* espacio de nombres [Aspose.Slides.Export](../../gifoptions)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->