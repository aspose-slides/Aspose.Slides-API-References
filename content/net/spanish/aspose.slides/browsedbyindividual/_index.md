---
title: BrowsedByIndividual
second_title: Referencia de la API de Aspose.Slides para .NET
description: Ventana visitada por individuo
type: docs
weight: 970
url: /es/aspose.slides/browsedbyindividual/
---

## Clase BrowsedByIndividual

Visitada por individuo (ventana)

```csharp
public class BrowsedByIndividual : SlideShowType
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [BrowsedByIndividual](browsedbyindividual)() | Inicializa una nueva instancia de la clase BrowsedByIndividual. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [ShowScrollbar](../../aspose.slides/browsedbyindividual/showscrollbar) { get; set; } | Mostrar barra de desplazamiento en la ventana |

### Ejemplos

```csharp
[C#]
using (Presentation pres = new Presentation())
{
    pres.SlideShowSettings.SlideShowType = new BrowsedByIndividual();
    pres.Save("pres.pptx", SaveFormat.Pptx);
}
```

### Ver también

* clase [SlideShowType](../slideshowtype)
* espacio de nombres [Aspose.Slides](../../aspose.slides)
* ensamblaje [Aspose.Slides](../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->