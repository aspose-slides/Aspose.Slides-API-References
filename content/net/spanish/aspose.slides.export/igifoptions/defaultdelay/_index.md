---
title: DefaultDelay
second_title: Aspose.Slides para .NET Referencia de API
description: Obtiene o establece el tiempo de demora predeterminado en ms. Este valor se usará si no se establece AdvanceAfterTimeaspose.slides/../aspose.slides/islideshowtransition/advanceaftertime. El valor predeterminado es 1000.
type: docs
weight: 20
url: /es/aspose.slides.export/igifoptions/defaultdelay/
---

## Propiedad IGifOptions.DefaultDelay

Obtiene o establece el tiempo de demora predeterminado [ms]. Este valor se usará si [`AdvanceAfterTime`](../../../aspose.slides/islideshowtransition/advanceaftertime) no se establece. El valor predeterminado es 1000.

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

### Ver También

* interfaz [IGifOptions](../../igifoptions)
* espacio de nombres [Aspose.Slides.Export](../../igifoptions)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->