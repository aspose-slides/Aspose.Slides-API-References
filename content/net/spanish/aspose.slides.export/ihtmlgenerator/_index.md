---
title: IHtmlGenerator
second_title: Referencia de la API de Aspose.Slides para .NET
description: Generador de HTML.
type: docs
weight: 3640
url: /es/aspose.slides.export/ihtmlgenerator/
---
## IHtmlGenerator interface

Generador de HTML.

```csharp
public interface IHtmlGenerator
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [NextSlideIndex](../../aspose.slides.export/ihtmlgenerator/nextslideindex) { get; } | Devuelve el índice de una diapositiva, que se representará después de la diapositiva actual o -1 si actualmente se representa la última diapositiva. Solo lecturaInt32 . |
| [PreviousSlideIndex](../../aspose.slides.export/ihtmlgenerator/previousslideindex) { get; } | Devuelve el índice de la diapositiva procesada anteriormente o -1 si se está procesando la primera diapositiva. Solo lecturaInt32 . |
| [SlideImageSize](../../aspose.slides.export/ihtmlgenerator/slideimagesize) { get; } | Devuelve el tamaño de la imagen de la diapositiva. Solo lecturaSizeF . |
| [SlideImageSizeUnit](../../aspose.slides.export/ihtmlgenerator/slideimagesizeunit) { get; } | Devuelve una unidad en la que se especifica el tamaño de la imagen de la diapositiva. Solo lectura[`SvgCoordinateUnit`](../svgcoordinateunit) . |
| [SlideImageSizeUnitCode](../../aspose.slides.export/ihtmlgenerator/slideimagesizeunitcode) { get; } | Devuelve un código CSS de la unidad en la que se especifica el tamaño de la imagen de la diapositiva. Solo lecturaString . |
| [SlideIndex](../../aspose.slides.export/ihtmlgenerator/slideindex) { get; } | Devuelve el índice de la diapositiva renderizada actualmente. Solo lecturaInt32 . |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [AddAttributeValue](../../aspose.slides.export/ihtmlgenerator/addattributevalue#addattributevalue)(char[]) | Cita el valor del atributo y lo agrega al archivo html. |
| [AddAttributeValue](../../aspose.slides.export/ihtmlgenerator/addattributevalue#addattributevalue_2)(string) | Cita el valor del atributo y lo agrega al archivo html. |
| [AddAttributeValue](../../aspose.slides.export/ihtmlgenerator/addattributevalue#addattributevalue_1)(char[], int, int) | Cita el valor del atributo y lo agrega al archivo html. |
| [AddHtml](../../aspose.slides.export/ihtmlgenerator/addhtml#addhtml)(char[]) | Agrega texto HTML formateado. |
| [AddHtml](../../aspose.slides.export/ihtmlgenerator/addhtml#addhtml_2)(string) | Agrega texto HTML formateado. |
| [AddHtml](../../aspose.slides.export/ihtmlgenerator/addhtml#addhtml_1)(char[], int, int) | Agrega texto HTML formateado. |
| [AddText](../../aspose.slides.export/ihtmlgenerator/addtext#addtext)(char[]) | Agrega texto sin formato a los archivos html, reemplazando los caracteres especiales con entidades html. Los saltos de línea y los espacios en blanco no se reemplazan. |
| [AddText](../../aspose.slides.export/ihtmlgenerator/addtext#addtext_2)(string) | Agrega texto sin formato a los archivos html, reemplazando los caracteres especiales con entidades html. Los saltos de línea y los espacios en blanco no se reemplazan. |
| [AddText](../../aspose.slides.export/ihtmlgenerator/addtext#addtext_1)(char[], int, int) | Agrega texto sin formato a los archivos html, reemplazando los caracteres especiales con entidades html. Los saltos de línea y los espacios en blanco no se reemplazan. |

### Ver también

* espacio de nombres [Aspose.Slides.Export](../../aspose.slides.export)
* asamblea [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
