---
title: GetFontEmbeddingLevel
second_title: Aspose.Slides para .NET Referencia de API
description: Determina el nivel de incrustación de una fuente a partir del arreglo de bytes dado y el nombre de la fuente.
type: docs
weight: 60
url: /es/aspose.slides/fontsmanager/getfontembeddinglevel/
---

## FontsManager.GetFontEmbeddingLevel método

Determina el nivel de incrustación de una fuente a partir del arreglo de bytes dado y el nombre de la fuente.

```csharp
public EmbeddingLevel GetFontEmbeddingLevel(byte[] fontBytes, string fontName)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fontBytes | Byte[] | El arreglo de bytes que contiene los datos de la fuente. |
| fontName | String | El nombre de la fuente. |

### Valor de Retorno

El nivel de incrustación de la fuente especificada.

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | Lanzada cuando *fontBytes* es null. |

### Ejemplos

```csharp
[C#]
using (Presentation pres = new Presentation(pptxFileName))
{
    // Recuperar todas las fuentes utilizadas en la presentación
    IFontData[] fontDatas = pres.FontsManager.GetFonts();

    // Obtener el arreglo de bytes que representa el estilo regular de la primera fuente en la presentación
    byte[] bytes = pres.FontsManager.GetFontBytes(fontDatas[0], FontStyle.Regular);

    // Determinar el nivel de incrustación de la fuente
    EmbeddingLevel embeddingLevel = pres.FontsManager.GetFontEmbeddingLevel(bytes, fontDatas[0].FontName);
}
```

### Véase También

* enum [EmbeddingLevel](../../embeddinglevel)
* class [FontsManager](../../fontsmanager)
* namespace [Aspose.Slides](../../fontsmanager)
* assembly [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->