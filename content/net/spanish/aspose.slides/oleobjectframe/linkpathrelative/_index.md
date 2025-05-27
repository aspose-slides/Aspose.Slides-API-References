---
title: LinkPathRelative
second_title: Aspose.Slides para .NET Referencia de API
description: Devuelve la ruta relativa a un archivo vinculado si está presente, de lo contrario devuelve una cadena vacía. Solo lectura String.
type: docs
weight: 90
url: /es/aspose.slides/oleobjectframe/linkpathrelative/
---

## Propiedad OleObjectFrame.LinkPathRelative

Devuelve la ruta relativa a un archivo vinculado si está presente, de lo contrario devuelve una cadena vacía. Solo lectura String.

```csharp
public string LinkPathRelative { get; }
```

### Comentarios

En las presentaciones de Ppt, algunos enlaces de objetos Ole pueden tener una representación relativa.

### Ejemplos

```csharp
[C#]
using (Presentation presentation = new Presentation("demo.ppt"))
{
    IOleObjectFrame oleFrame = presentation.Slides[0].Shapes[0] as IOleObjectFrame;

    if (oleFrame != null)
    {
        Console.WriteLine("La ruta relativa: " + oleFrame.LinkPathRelative);
    } 
}
```

### Ver También

* clase [OleObjectFrame](../../oleobjectframe)
* espacio de nombres [Aspose.Slides](../../oleobjectframe)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->