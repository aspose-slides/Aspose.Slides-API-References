---
title: GetFontBytes
second_title: Referencia de API de Aspose.Slides para .NET
description: Recupera el array de bytes que representa los datos de la fuente para un estilo de fuente y datos de fuente específicos.
type: docs
weight: 50
url: /es/aspose.slides/fontsmanager/getfontbytes/
---

## FontsManager.GetFontBytes method

Recupera el array de bytes que representa los datos de la fuente para un estilo de fuente y datos de fuente específicos.

```csharp
public byte[] GetFontBytes(IFontData fontData, FontStyle fontStyle)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fontData | IFontData | El objeto de datos de fuente que contiene la información sobre la fuente [`FontData`](../../fontdata). |
| fontStyle | FontStyle | El estilo de la fuente para el cual se deben recuperar los datos FontStyle. |

### Valor de Retorno

Un array de bytes que contiene los datos de la fuente para el estilo de fuente especificado. Si los datos de la fuente o el estilo no se encuentran, devuelve null.

### Ejemplos

```csharp
[C#]
using (Presentation pres = new Presentation ("Presentation.pptx"))
{
    // Recuperar todas las fuentes utilizadas en la presentación
    IFontData[] fonts = pres.FontsManager.GetFonts();

    // Obtener el array de bytes que representa el estilo regular de la primera fuente en la presentación
    byte[] bytes = pres.FontsManager.GetFontBytes(fonts[0], FontStyle.Regular);
}
```

### Ver También

* interface [IFontData](../../ifontdata)
* class [FontsManager](../../fontsmanager)
* namespace [Aspose.Slides](../../fontsmanager)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->