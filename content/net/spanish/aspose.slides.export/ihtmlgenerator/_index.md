---
title: IHtmlGenerator
second_title: Referencia de API de Aspose.Slides para .NET
description: Generador de Html.
type: docs
weight: 3790
url: /es/aspose.slides.export/ihtmlgenerator/
---

## Interfaz IHtmlGenerator

Generador de Html.

```csharp
public interface IHtmlGenerator
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [NextSlideIndex](../../aspose.slides.export/ihtmlgenerator/nextslideindex) { get; } | Devuelve el índice de una diapositiva, que se renderizará después de la diapositiva actual o -1 si se está renderizando la última diapositiva. Solo lectura Int32. |
| [PreviousSlideIndex](../../aspose.slides.export/ihtmlgenerator/previousslideindex) { get; } | Devuelve el índice de la diapositiva renderizada anteriormente o -1 si se está renderizando la primera diapositiva. Solo lectura Int32. |
| [SlideImageSize](../../aspose.slides.export/ihtmlgenerator/slideimagesize) { get; } | Devuelve el tamaño de la imagen de la diapositiva. Solo lectura SizeF. |
| [SlideImageSizeUnit](../../aspose.slides.export/ihtmlgenerator/slideimagesizeunit) { get; } | Devuelve una unidad en la que se especifica el tamaño de la imagen de la diapositiva. Solo lectura [`SvgCoordinateUnit`](../svgcoordinateunit). |
| [SlideImageSizeUnitCode](../../aspose.slides.export/ihtmlgenerator/slideimagesizeunitcode) { get; } | Devuelve un código css de la unidad en la que se especifica el tamaño de la imagen de la diapositiva. Solo lectura String. |
| [SlideIndex](../../aspose.slides.export/ihtmlgenerator/slideindex) { get; } | Devuelve el índice de la diapositiva que se está renderizando actualmente. Solo lectura Int32. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [AddAttributeValue](../../aspose.slides.export/ihtmlgenerator/addattributevalue#addattributevalue)(char[]) | Cita el valor del atributo y lo añade al archivo html. |
| [AddAttributeValue](../../aspose.slides.export/ihtmlgenerator/addattributevalue#addattributevalue_2)(string) | Cita el valor del atributo y lo añade al archivo html. |
| [AddAttributeValue](../../aspose.slides.export/ihtmlgenerator/addattributevalue#addattributevalue_1)(char[], int, int) | Cita el valor del atributo y lo añade al archivo html. |
| [AddHtml](../../aspose.slides.export/ihtmlgenerator/addhtml#addhtml)(char[]) | Añade texto HTML formateado. |
| [AddHtml](../../aspose.slides.export/ihtmlgenerator/addhtml#addhtml_2)(string) | Añade texto HTML formateado. |
| [AddHtml](../../aspose.slides.export/ihtmlgenerator/addhtml#addhtml_1)(char[], int, int) | Añade texto HTML formateado. |
| [AddText](../../aspose.slides.export/ihtmlgenerator/addtext#addtext)(char[]) | Añade texto sin formato a los archivos html, reemplazando caracteres especiales por entidades html. Los saltos de línea y espacios en blanco no son reemplazados. |
| [AddText](../../aspose.slides.export/ihtmlgenerator/addtext#addtext_2)(string) | Añade texto sin formato a los archivos html, reemplazando caracteres especiales por entidades html. Los saltos de línea y espacios en blanco no son reemplazados. |
| [AddText](../../aspose.slides.export/ihtmlgenerator/addtext#addtext_1)(char[], int, int) | Añade texto sin formato a los archivos html, reemplazando caracteres especiales por entidades html. Los saltos de línea y espacios en blanco no son reemplazados. |

### Ver También

* namespace [Aspose.Slides.Export](../../aspose.slides.export)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->