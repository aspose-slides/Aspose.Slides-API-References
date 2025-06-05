---
title: HtmlGenerator
second_title: Referencia del API de Aspose.Slides para .NET
description: Generador de Html.
type: docs
weight: 3710
url: /es/aspose.slides.export/htmlgenerator/
---

## Clase HtmlGenerator

Generador de Html.

```csharp
public sealed class HtmlGenerator : IHtmlGenerator
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [NextSlideIndex](../../aspose.slides.export/htmlgenerator/nextslideindex) { get; } | Devuelve el índice de una diapositiva, que se renderizará después de la diapositiva actual o -1 si actualmente se está renderizando la última diapositiva. Solo lectura Int32. |
| [PreviousSlideIndex](../../aspose.slides.export/htmlgenerator/previousslideindex) { get; } | Devuelve el índice de la diapositiva renderizada anteriormente o -1 si se está renderizando la primera diapositiva. Solo lectura Int32. |
| [SlideImageSize](../../aspose.slides.export/htmlgenerator/slideimagesize) { get; } | Devuelve el tamaño de la imagen de la diapositiva. Solo lectura SizeF. |
| [SlideImageSizeUnit](../../aspose.slides.export/htmlgenerator/slideimagesizeunit) { get; } | Devuelve una unidad en la que se especifica el tamaño de la imagen de la diapositiva. Solo lectura [`SvgCoordinateUnit`](../svgcoordinateunit). |
| [SlideImageSizeUnitCode](../../aspose.slides.export/htmlgenerator/slideimagesizeunitcode) { get; } | Devuelve un código CSS de la unidad en la que se especifica el tamaño de la imagen de la diapositiva. Solo lectura String. |
| [SlideIndex](../../aspose.slides.export/htmlgenerator/slideindex) { get; } | Devuelve el índice de la diapositiva que se está renderizando actualmente. Solo lectura Int32. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [AddAttributeValue](../../aspose.slides.export/htmlgenerator/addattributevalue#addattributevalue)(char[]) | Cita el valor del atributo y lo agrega al archivo HTML. |
| [AddAttributeValue](../../aspose.slides.export/htmlgenerator/addattributevalue#addattributevalue_2)(string) | Cita el valor del atributo y lo agrega al archivo HTML. |
| [AddAttributeValue](../../aspose.slides.export/htmlgenerator/addattributevalue#addattributevalue_1)(char[], int, int) | Cita el valor del atributo y lo agrega al archivo HTML. |
| [AddHtml](../../aspose.slides.export/htmlgenerator/addhtml#addhtml)(char[]) | Agrega texto HTML formateado. |
| [AddHtml](../../aspose.slides.export/htmlgenerator/addhtml#addhtml_2)(string) | Agrega texto HTML formateado. |
| [AddHtml](../../aspose.slides.export/htmlgenerator/addhtml#addhtml_1)(char[], int, int) | Agrega texto HTML formateado. |
| [AddText](../../aspose.slides.export/htmlgenerator/addtext#addtext)(char[]) | Agrega texto plano a los archivos HTML, reemplazando caracteres especiales por entidades HTML. Los saltos de línea y los espacios en blanco no se reemplazan. |
| [AddText](../../aspose.slides.export/htmlgenerator/addtext#addtext_2)(string) | Agrega texto plano a los archivos HTML, reemplazando caracteres especiales por entidades HTML. Los saltos de línea y los espacios en blanco no se reemplazan. |
| [AddText](../../aspose.slides.export/htmlgenerator/addtext#addtext_1)(char[], int, int) | Agrega texto plano a los archivos HTML, reemplazando caracteres especiales por entidades HTML. Los saltos de línea y los espacios en blanco no se reemplazan. |

### Ver También

* interfaz [IHtmlGenerator](../ihtmlgenerator)
* espacio de nombres [Aspose.Slides.Export](../../aspose.slides.export)
* ensamblado [Aspose.Slides](../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->