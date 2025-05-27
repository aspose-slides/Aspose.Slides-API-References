---
title: GetFontBytes
second_title: Referencia de API de Aspose.Slides para .NET
description: Recupera el arreglo de bytes que representa los datos de la fuente para un estilo de fuente y datos de fuente específicos.
type: docs
weight: 50
url: /es/aspose.slides/fontsmanager/getfontbytes/
---

## FontsManager.GetFontBytes método

Recupera el arreglo de bytes que representa los datos de la fuente para un estilo de fuente y datos de fuente específicos.

```csharp
public byte[] GetFontBytes(IFontData fontData, FontStyle fontStyle)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fontData | IFontData | El objeto de datos de fuente que contiene la información sobre la fuente [`FontData`](../../fontdata). |
| fontStyle | FontStyle | El estilo de la fuente para el cual se deben recuperar los datos FontStyle. |

### Valor de Retorno

Un arreglo de bytes que contiene los datos de la fuente para el estilo de fuente especificado. Si los datos de la fuente o el estilo no se encuentran, devuelve null.

### Ejemplos

```csharp
[C#]
using (Presentation pres = new Presentation ("Presentation.pptx"))
{
    // Recuperar todas las fuentes utilizadas en la presentación
    IFontData[] fonts = pres.FontsManager.GetFonts();

    // Obtener el arreglo de bytes que representa el estilo regular de la primera fuente en la presentación
    byte[] bytes = pres.FontsManager.GetFontBytes(fonts[0], FontStyle.Regular);
}
```

### Véase También

* interfaz [IFontData](../../ifontdata)
* clase [FontsManager](../../fontsmanager)
* espacio de nombres [Aspose.Slides](../../fontsmanager)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->