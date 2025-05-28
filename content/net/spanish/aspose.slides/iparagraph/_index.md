---
title: IParagraph
second_title: Referencia de la API de Aspose.Slides para .NET
description: Representa un párrafo de un texto.
type: docs
weight: 6360
url: /es/aspose.slides/iparagraph/
---

## Interfaz IParagraph

Representa un párrafo de un texto.

```csharp
public interface IParagraph : ISlideComponent
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AsISlideComponent](../../aspose.slides/iparagraph/asislidecomponent) { get; } | Permite obtener la interfaz base ISlideComponent. Solo lectura [`ISlideComponent`](../islidecomponent). |
| [EndParagraphPortionFormat](../../aspose.slides/iparagraph/endparagraphportionformat) { get; set; } | Especifica las propiedades de porción que se utilizarán si se inserta otra porción después de la última. |
| [ParagraphFormat](../../aspose.slides/iparagraph/paragraphformat) { get; } | Devuelve el objeto de formato para este párrafo. Solo lectura [`IParagraphFormat`](../iparagraphformat). |
| [Portions](../../aspose.slides/iparagraph/portions) { get; } | Devuelve la colección de porciones de texto. Solo lectura [`IPortionCollection`](../iportioncollection). |
| [Text](../../aspose.slides/iparagraph/text) { get; set; } | Obtiene o establece el texto sin formato de un párrafo. Lectura/escritura String. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [GetLinesCount](../../aspose.slides/iparagraph/getlinescount)() | Obtiene el número de líneas en un párrafo. |
| [GetRect](../../aspose.slides/iparagraph/getrect)() | Obtiene las coordenadas del rectángulo que limita el párrafo. El rectángulo incluye todas las líneas de texto en el párrafo, incluidas las vacías. |
| [JoinPortionsWithSameFormatting](../../aspose.slides/iparagraph/joinportionswithsameformatting)() | Une las partes con el mismo formato. |

### Vea También

* interfaz [ISlideComponent](../islidecomponent)
* espacio de nombres [Aspose.Slides](../../aspose.slides)
* ensamblado [Aspose.Slides](../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->