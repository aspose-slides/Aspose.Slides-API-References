---
title: TextFrame
second_title: Aspose.Slides para .NET Referencia de API
description: Representa un TextFrame.
type: docs
weight: 10640
url: /es/aspose.slides/textframe/
---

## Clase TextFrame

Representa un TextFrame.

```csharp
public sealed class TextFrame : ITextFrame
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [HyperlinkQueries](../../aspose.slides/textframe/hyperlinkqueries) { get; } | Proporciona acceso fácil a los hipervínculos contenidos. Solo lectura [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [Paragraphs](../../aspose.slides/textframe/paragraphs) { get; } | Devuelve la lista de todos los párrafos en un marco. Solo lectura [`IParagraphCollection`](../iparagraphcollection). |
| [ParentCell](../../aspose.slides/textframe/parentcell) { get; } | Devuelve la celda padre o null si el objeto padre no implementa la interfaz ICell. Solo lectura [`ICell`](../icell). |
| [ParentShape](../../aspose.slides/textframe/parentshape) { get; } | Devuelve la forma padre o null si el objeto padre no implementa la interfaz IShape. Solo lectura [`IShape`](../ishape). |
| [Presentation](../../aspose.slides/textframe/presentation) { get; } | Devuelve la presentación padre de un TextFrame. Solo lectura [`IPresentation`](../ipresentation). |
| [Slide](../../aspose.slides/textframe/slide) { get; } | Devuelve la diapositiva padre de un TextFrame. Solo lectura [`IBaseSlide`](../ibaseslide). |
| [Text](../../aspose.slides/textframe/text) { get; set; } | Obtiene o establece el texto sin formato para un TextFrame. Lectura/escritura String. |
| [TextFrameFormat](../../aspose.slides/textframe/textframeformat) { get; } | Devuelve el objeto de formato para este objeto TextFrame. Solo lectura [`ITextFrameFormat`](../itextframeformat). |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [HighlightRegex](../../aspose.slides/textframe/highlightregex#highlightregex_1)(Regex, Color, IFindResultCallback) | Resalta todas las coincidencias de la expresión regular con el color especificado. |
| [HighlightText](../../aspose.slides/textframe/highlighttext#highlighttext)(string, Color) | Resalta todas las coincidencias del texto de muestra con el color especificado. |
| [HighlightText](../../aspose.slides/textframe/highlighttext#highlighttext_2)(string, Color, ITextSearchOptions, IFindResultCallback) | Resalta todas las coincidencias del texto de muestra con el color especificado. |
| [JoinPortionsWithSameFormatting](../../aspose.slides/textframe/joinportionswithsameformatting)() | Une partes con el mismo formato en todos los párrafos. |
| [ReplaceRegex](../../aspose.slides/textframe/replaceregex)(Regex, string, IFindResultCallback) | Reemplaza todas las coincidencias de la expresión regular con la cadena especificada. |
| [ReplaceText](../../aspose.slides/textframe/replacetext)(string, string, ITextSearchOptions, IFindResultCallback) | Reemplaza todas las ocurrencias del texto especificado con otro texto especificado. |
| [SplitTextByColumns](../../aspose.slides/textframe/splittextbycolumns)() | Divide el contenido de texto del [`ITextFrame`](../itextframe) en un arreglo de cadenas, donde cada elemento corresponde a una columna de texto separada dentro del marco. |

### Véase También

* interfaz [ITextFrame](../itextframe)
* espacio de nombres [Aspose.Slides](../../aspose.slides)
* ensamblado [Aspose.Slides](../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->